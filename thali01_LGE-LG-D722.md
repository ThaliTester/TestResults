#### Test 78968685da35147_thali01_LGE-LG-D722 Logs


```
--------- beginning of main
07-27 08:53:57.701   295   356 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 08:53:58.860  5697  5697 D AndroidRuntime: 
07-27 08:53:58.860  5697  5697 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-27 08:53:58.864  5697  5697 D AndroidRuntime: CheckJNI is OFF
07-27 08:53:59.068  5697  5697 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
07-27 08:53:59.102   862  1970 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-27 08:53:59.209   862  1970 D ActivityManager: setTaskToReturnTo : TaskRecord{3c53dfdc #253 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-27 08:53:59.211   862  1970 D ActivityManager: setTaskToReturnTo : TaskRecord{3c53dfdc #253 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
07-27 08:53:59.230   862  1970 D WindowStateEx: AppWindowTokenEx init.. 
07-27 08:53:59.245   862  1015 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
07-27 08:53:59.262   862  1970 D InputDispatcher: Focus left window: Window{239be6e2 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
07-27 08:53:59.266   862  1015 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
07-27 08:53:59.268  5697  5697 D AndroidRuntime: Shutting down VM
07-27 08:53:59.275  1947  1947 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
07-27 08:53:59.282   862  1015 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
07-27 08:53:59.282   862  1015 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
07-27 08:53:59.308   862  1015 D SplitWindow: check instance of lgWin Window{8da4e74 u0 Starting com.test.thalitest}
07-27 08:53:59.366   862  1906 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5716 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-27 08:53:59.378  1947  1947 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
07-27 08:53:59.428  2023  2023 I HotwordDetector: Closing mic
07-27 08:53:59.439  2023  2391 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@1f267a29
07-27 08:53:59.439  2023  2391 V AudioRecord: stop()
07-27 08:53:59.439  2023  2391 D AudioRecord: AudioRecord->stop()
07-27 08:53:59.439   279  1606 V AudioFlinger: RecordHandle::stop()
07-27 08:53:59.439   279  1606 V AudioFlinger: RecordThread::stop
07-27 08:53:59.458   279  1606 V AudioFlinger: Record stopped OK
07-27 08:53:59.461   279  1606 V AudioPolicyManager: stopInput() input 17
07-27 08:53:59.463   279  1606 V AudioPolicyService: AudioCommandThread() adding release patch delay 0
07-27 08:53:59.463   279  1606 V AudioPolicyService: inserting command: 8 at index 0, num commands 0
07-27 08:53:59.463   279  1059 V AudioPolicyService: AudioCommandThread() waking up
07-27 08:53:59.463   279  1059 V AudioPolicyService: AudioCommandThread() processing release audio patch
07-27 08:53:59.463   279  1059 V AudioFlinger::PatchPanel: releaseAudioPatch handle 18
07-27 08:53:59.463   279  1059 V AudioFlinger::PatchPanel: releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
07-27 08:53:59.463   279  1059 V AudioFlinger: ThreadBase::setParameters() routing=0
07-27 08:53:59.466   279  2612 D audio_hw_primary: in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
,07-27 08:53:59.478  1947  1947 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
07-27 08:53:59.511   279  2612 V audio_hw_primary: stop_input_stream: enter: usecase(7: audio-record)
07-27 08:53:59.511   279  2612 V audio_hw_primary: disable_audio_route: enter: usecase(7)
07-27 08:53:59.511   279  2612 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
07-27 08:53:59.511   279  2612 V audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
07-27 08:53:59.515   279  2612 V audio_hw_primary: disable_audio_route: exit
07-27 08:53:59.515   279  2612 E audio_hw_primary: disable_snd_device: enter 144
07-27 08:53:59.515   279  2612 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
07-27 08:53:59.515   279  2612 V audio_hw_primary: disable_snd_device: snd_device(144: lg-vr-handset-mic)
07-27 08:53:59.519   862  2370 I WindowStateAnimator: Starting window displayed
07-27 08:53:59.519   279  2612 V audio_hw_primary: stop_input_stream: exit: status(0)
07-27 08:53:59.519   279  2612 V audio_hw_primary: in_standby: exit:  status(0)
07-27 08:53:59.520   279  2612 V AudioFlinger: RecordThread: loop stopping
07-27 08:53:59.520   279  1059 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
07-27 08:53:59.520   279  2612 V AudioFlinger: RecordThread: loop starting
07-27 08:53:59.520   279  2612 V AudioFlinger: processConfigEvents_l() remaining events 1
07-27 08:53:59.520   279  2612 V AudioFlinger: processConfigEvents_l() DONE thread 0xb384c000
07-27 08:53:59.520   279  2612 V AudioFlinger: RecordThread: loop stopping
07-27 08:53:59.521   279  1059 V AudioPolicyService: AudioCommandThread() going to sleep
07-27 08:53:59.521   279  1606 V AudioPolicyManager: resetInputDevice() releaseAudioPatch returned -22
07-27 08:53:59.521   279  1606 V AudioPolicyManager: removeAudioPatch() handle 18 af handle 18
07-27 08:53:59.521   279  1606 V AudioPolicyService: AudioCommandThread() adding update audio patch list
07-27 08:53:59.521   279  1606 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
07-27 08:53:59.521   279  1060 V AudioPolicyService: AudioCommandThread() waking up
07-27 08:53:59.522   279  1060 V AudioPolicyService: AudioCommandThread() processing update audio patch list
07-27 08:53:59.522   279  1060 V AudioPolicyService: AudioCommandThread() going to sleep
07-27 08:53:59.522   279  1606 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
07-27 08:53:59.522   279  1606 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
07-27 08:53:59.523   279  1059 V AudioPolicyService: AudioCommandThread() waking up
07-27 08:53:59.523   279  1059 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=0, io 17
07-27 08:53:59.523   279  1059 V AudioFlinger: setParameters(): io 17, keyvalue hotword_active=0, calling pid 279
07-27 08:53:59.523   279  1059 V AudioFlinger: ThreadBase::setParameters() hotword_active=0
07-27 08:53:59.523   279  1059 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
07-27 08:53:59.523   279  2612 V AudioFlinger: RecordThread: loop starting
07-27 08:53:59.523   279  2612 V AudioFlinger: processConfigEvents_l() remaining events 1
07-27 08:53:59.523   279  2612 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=0
07-27 08:53:59.523   279  2612 V audio_hw_primary: in_set_parameters: exit: status(0)
07-27 08:53:59.523   279  2612 V AudioFlinger: processConfigEvents_l() DONE thread 0xb384c000
07-27 08:53:59.523   279  2612 V AudioFlinger: RecordThread: loop stopping
07-27 08:53:59.524   279  1059 V AudioPolicyService: AudioCommandThread() going to sleep
07-27 08:53:59.527   862  1013 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
07-27 08:53:59.531   862  1013 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
07-27 08:53:59.534   862  1013 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
07-27 08:53:59.534   862  1013 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
07-27 08:53:59.534   862  1013 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-27 08:53:59.534   862  1013 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@326212a7,  pkg=WindowManager.LayoutParams
07-27 08:53:59.534   862  1013 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
07-27 08:53:59.541  2023  2391 V AudioRecord: stop()
07-27 08:53:59.541  2023  2391 V AudioRecord: stop()
07-27 08:53:59.541  2023  2391 V AudioRecord: stop()
07-27 08:53:59.542  1368  1368 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
07-27 08:53:59.542   279   279 V AudioFlinger: RecordHandle::stop()
07-27 08:53:59.542   279   279 V AudioFlinger: RecordThread::stop
07-27 08:53:59.542   279   279 V AudioPolicyManager: releaseInput() 17
07-27 08:53:59.542   279   279 V AudioPolicyManager: closeInput(17)
07-27 08:53:59.542   279   279 V AudioFlinger: closeInput() 17
07-27 08:53:59.542   279   279 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-27 08:53:59.543  1368  1392 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-27 08:53:59.543   279   279 V AudioFlinger: ThreadBase::exit
07-27 08:53:59.543   279  2612 V AudioFlinger: RecordThread: loop starting
07-27 08:53:59.543  2023  2047 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-27 08:53:59.543   862  2204 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-27 08:53:59.543  1368  1368 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
07-27 08:53:59.543  1368  1368 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
07-27 08:53:59.543  1368  1368 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
07-27 08:53:59.543  2865  2882 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-27 08:53:59.544  1787  1814 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-27 08:53:59.544  3103  3119 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
07-27 08:53:59.544   279  2612 V AudioFlinger: RecordThread 0xb384c000 exiting
07-27 08:53:59.544   279   279 D audio_hw_primary: adev_close_input_stream: enter:stream_handle(0xb546dd40)
07-27 08:53:59.544   279   279 D audio_hw_primary: in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
07-27 08:53:59.544   279   279 V audio_hw_primary: in_standby: exit:  status(0)
07-27 08:53:59.544   279   279 V AudioPolicyService: AudioCommandThread() adding update audio port list
07-27 08:53:59.545   279   279 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
07-27 08:53:59.545   279  1060 V AudioPolicyService: AudioCommandThread() waking up
07-27 08:53:59.545   279  1060 V AudioPolicyService: AudioCommandThread() processing update audio port list
07-27 08:53:59.545   279   279 V AudioPolicyManager: releaseInput() exit
07-27 08:53:59.545   279   279 V AudioFlinger: virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
07-27 08:53:59.545   279   279 V AudioFlinger: removeClient_l() pid 2023, calling pid 279
07-27 08:53:59.546   279   279 V AudioFlinger: releasing 16 from 2023 for -1
07-27 08:53:59.546   279   279 V AudioFlinger:  decremented refcount to 0
07-27 08:53:59.546   279   279 V AudioFlinger: purging stale effects
07-27 08:53:59.546   279  1060 V AudioPolicyService: AudioCommandThread() going to sleep
07-27 08:53:59.547  2023  2405 I HotwordRecognitionRnr: Stopping hotword detection.
07-27 08:53:59.559  2023  2600 I HotwordRecognitionRnr: Hotword detection finished
07-27 08:53:59.611  5716  5716 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
07-27 08:53:59.693  5716  5716 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
07-27 08:53:59.765  5716  5716 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 729-732)
07-27 08:53:59.765  5716  5716 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 08:53:59.795  5716  5716 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {124d1539}
07-27 08:53:59.797  5716  5716 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 08:53:59.808  5716  5716 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-27 08:53:59.831  5716  5716 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-27 08:53:59.832  5716  5716 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 08:53:59.838  5716  5716 E SysUtils: ApplicationContext is null in ApplicationStatus
07-27 08:53:59.897  5716  5755 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
07-27 08:53:59.928  5716  5716 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-27 08:53:59.941  5716  5716 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-27 08:53:59.941  5716  5716 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-27 08:53:59.944  5716  5716 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-27 08:53:59.944  5716  5716 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-27 08:53:59.944  5716  5716 I Adreno-EGL: Build Date: 03/02/15 Mon
07-27 08:53:59.944  5716  5716 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-27 08:53:59.944  5716  5716 I Adreno-EGL: Remote Branch: 
07-27 08:53:59.944  5716  5716 I Adreno-EGL: Local Patches: 
07-27 08:53:59.944  5716  5716 I Adreno-EGL: Reconstruct Branch: 
07-27 08:54:00.000   862  1283 D PowerManagerServiceEx: acquireWakeLockInternal: lock=566032396, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=862
07-27 08:54:00.016  2847  2847 D WeatherService: 2 : TimeTick Intent has been received, Time(hour:min:sec) 8:54:0
07-27 08:54:00.018  2847  2847 D WeatherService: 2 : TimeTick Intent And Screen On
07-27 08:54:00.018  2847  2847 D WeatherService: 2 : SDK version : 21
07-27 08:54:00.020   862  1970 W ActivityManager: getTasks: caller 10074 does not hold GET_TASKS; limiting output
07-27 08:54:00.020  2847  2847 D Weather.Utils: 2 : Utils getTopActivity com.lge.launcher2 / true
07-27 08:54:00.021  2847  2847 D WeatherService: 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
07-27 08:54:00.021  2847  2847 D WeatherService: 2 : shouldTimeTickRegistered : true - home screen widget is shown.
07-27 08:54:00.021  2847  2847 D WeatherService: 2 : requestRefreshAppWidget, isUpdateStart : false
07-27 08:54:00.024  2847  2847 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-27 08:54:00.024  2847  2847 D WeatherService: 2 : requestRefreshAppWidget, isUpdating : false
07-27 08:54:00.025  2847  2847 D WeatherAncestor: 2 : buildUpdate, appWidgetId: 2
07-27 08:54:00.026  2847  2847 D WeatherTheme: 2 : Current Theme Name: com.lge.launcher2.theme.optimus
07-27 08:54:00.026  2847  2847 D WeatherTheme: 2 : Fixed theme : optimus
07-27 08:54:00.035  2847  2847 D WeatherReflect: 2 : Map key string is -2
07-27 08:54:00.040  2847  2847 D lim     : 2 : time = 08:54
07-27 08:54:00.042  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 08:54:00.042  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 08:54:00.043  2847  2847 I WeatherReflect: Model Name : LG-D722
07-27 08:54:00.044  2847  2847 D WeatherTheme: 2 : Different view - status_min_formatted : 53 != 54
07-27 08:54:00.044  2847  2847 D WeatherTheme: 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
07-27 08:54:00.045  2847  2847 D WeatherReflect: 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
07-27 08:54:00.049  2847  2847 D Theme   : strTheme: com.lge.launcher2.theme.optimus
07-27 08:54:00.049  2847  2847 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
07-27 08:54:00.049  2847  2847 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
07-27 08:54:00.049  2847  2847 D Weather4x2_optimus: currentPackage=com.lge.sizechangable.weather.theme.optimus
07-27 08:54:00.054  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
07-27 08:54:00.056  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 08:54:00.058  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
07-27 08:54:00.105  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
07-27 08:54:00.108  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 08:54:00.140  2847  2847 D Weather4x2_optimus: [[[[[[Theme package!!]]]]]] RemoteViews are created 2
07-27 08:54:00.140  2847  2847 D Weather4x2_optimus: widgetType = 1, orientation = 1
07-27 08:54:00.140  2847  2847 D Weather4x2_optimus: forecast size is 0
07-27 08:54:00.140  2847  2847 D Theme   : strTheme: com.lge.launcher2.theme.optimus
07-27 08:54:00.140  2847  2847 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
07-27 08:54:00.140  2847  2847 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
07-27 08:54:00.141  2847  2847 D Theme   : strTheme: com.lge.launcher2.theme.optimus
07-27 08:54:00.141  2847  2847 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
07-27 08:54:00.141  2847  2847 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
07-27 08:54:00.142  2847  2847 D Theme   : strTheme: com.lge.launcher2.theme.optimus
07-27 08:54:00.142  2847  2847 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
07-27 08:54:00.142  2847  2847 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
07-27 08:54:00.142  2847  2847 I Theme_WeatherAncestor_optimus: WEATHER_CP_ACCU : 
07-27 08:54:00.142  2847  2847 I Theme_WeatherAncestor_optimus: weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
07-27 08:54:00.142  2847  2847 D Theme   : strTheme: com.lge.launcher2.theme.optimus
07-27 08:54:00.142  2847  2847 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
07-27 08:54:00.142  2847  2847 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
07-27 08:54:00.142  2847  2847 D Theme_WeatherAncestor_optimus: setTouchIntent, appWidgetId: 2
07-27 08:54:00.144  2847  2847 D Theme_WeatherAncestor_optimus: url is : null
07-27 08:54:00.147  2847  2847 D Theme   : strTheme: com.lge.launcher2.theme.optimus
07-27 08:54:00.147  2847  2847 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
07-27 08:54:00.147  2847  2847 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
07-27 08:54:00.149  2847  2847 D WeatherAncestor: 2 : update view, appWidgetId: 2
07-27 08:54:00.156  2847  2847 D WeatherService: 2 : TimeTick Intent has been processed, Time(hour:min:sec) 8:54:0
07-27 08:54:00.160   279  1321 V AudioPolicyService: registerClient() client 0xb4027560, uid 10030
07-27 08:54:00.167   862   862 D PowerManagerServiceEx: releaseWakeLockInternal: lock=566032396 [*alarm*], flags=0x0
07-27 08:54:00.195   862  1014 D BluetoothManagerService: Message: 20
07-27 08:54:00.195   862  1014 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@18e83ca4:true
07-27 08:54:00.202  5716  5771 D BluetoothAdapter: 961224699: getState() :  mService = null. Returning STATE_OFF
07-27 08:54:00.308  1947  1947 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
07-27 08:54:00.340  5716  5716 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 08:54:00.352  5716  5716 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-27 08:54:00.357  5716  5716 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
07-27 08:54:00.361  5716  5716 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
07-27 08:54:00.361  5716  5716 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
07-27 08:54:00.374  5716  5716 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
07-27 08:54:00.382  5716  5716 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 08:54:00.382  5716  5716 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 08:54:00.404  1947  1947 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
07-27 08:54:00.456  5716  5716 I Activity: Activity.onPostResume() called 
07-27 08:54:00.465  5716  5788 D OpenGLRenderer: Render dirty regions requested: true
07-27 08:54:00.466  5716  5788 I OpenGLRenderer: Initialized EGL, version 1.4
07-27 08:54:00.474  5716  5788 D OpenGLRenderer: Enabling debug mode 0
07-27 08:54:00.495  5716  5716 D Atlas   : Validating map...
07-27 08:54:00.499   862  1883 D SplitWindow: check instance of lgWin Window{3d2616d4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-27 08:54:00.510  5716  5769 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
07-27 08:54:00.535   862  1883 D InputDispatcher: Focus entered window: Window{3d2616d4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-27 08:54:00.614   862  1906 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
07-27 08:54:00.623   862  1015 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s297ms
07-27 08:54:00.626   862  1015 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3e1388e5 u0 com.test.thalitest/.MainActivity t253} time:121591
07-27 08:54:00.634  5716  5716 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@dbee748 time:121601
07-27 08:54:00.745  5716  5716 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5716
,07-27 08:54:01.362  5716  5716 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-27 08:54:01.488  5716  5794 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1623026432
,07-27 08:54:01.496  5716  5794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-27 08:54:01.496  5716  5794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-27 08:54:01.496  5716  5794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-27 08:54:01.496  5716  5794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-27 08:54:01.496  5716  5794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-27 08:54:01.496  5716  5794 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19e768d5 added. We now have 1 listener(s)
07-27 08:54:01.501   862   881 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 08:54:01.504  5716  5794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
,07-27 08:54:01.508  5716  5794 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
07-27 08:54:01.509  5716  5794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-27 08:54:01.509  5716  5794 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 08:54:01.521  5716  5794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-27 08:54:01.521  5716  5794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-27 08:54:01.521  5716  5794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-27 08:54:01.521  5716  5794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
07-27 08:54:01.521  5716  5794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-27 08:54:01.521  5716  5794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-27 08:54:01.521  5716  5794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-27 08:54:01.521  5716  5794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-27 08:54:01.521  5716  5794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-27 08:54:01.521  5716  5794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-27 08:54:01.521  5716  5794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-27 08:54:01.521  5716  5794 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@189eb278 added. We now have 1 listener(s)
07-27 08:54:01.522  5716  5794 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 08:54:01.531  5716  5794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:54:01.531  5716  5794 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
07-27 08:54:01.538  5716  5794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-27 08:54:01.538  5716  5794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-27 08:54:01.539  5716  5794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-27 08:54:01.539  5716  5794 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-27 08:54:01.541  5716  5794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 08:54:01.541   862  1851 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 08:54:01.542  5716  5794 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
07-27 08:54:01.544  5716  5794 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:54:01.544  5716  5794 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 08:54:01.544  5716  5794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:54:01.544  5716  5794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-27 08:54:01.544  5716  5794 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 08:54:01.544  5716  5794 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 08:54:01.544  5716  5794 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 08:54:01.544  5716  5794 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 08:54:01.544  5716  5794 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 08:54:01.544  5716  5794 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-27 08:54:01.544  5716  5794 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 08:54:01.545  5716  5794 I io.jxcore.node.LifeCycleMonitor: start: OK
07-27 08:54:01.575  5716  5716 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-27 08:54:01.764  5716  5731 I art     : CheckpointMarkThreadRoots callback created = 0xb07fa2d0
,07-27 08:54:01.791  5716  5731 I art     : CheckpointMarkThreadRoots callback created = 0xb07fa2a0
,07-27 08:54:02.233  5716  5809 W jxcore-log: Initializing JXcore engine
07-27 08:54:02.233  5716  5809 W jxcore-log: JXcore engine is ready
,07-27 08:54:02.296  5809  5809 W Thread-669: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5321]" dev="sockfs" ino=5321 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
07-27 08:54:02.296  5809  5809 W Thread-669: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-27 08:54:02.296  5809  5809 W Thread-669: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[5434]" dev="sockfs" ino=5434 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
07-27 08:54:02.296  5809  5809 W Thread-669: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
07-27 08:54:02.296  5809  5809 W Thread-669: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
07-27 08:54:02.296  5809  5809 W Thread-669: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[26775]" dev="sockfs" ino=26775 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-27 08:54:02.319  5716  5809 W jxcore-log: Starting JXcore engine
07-27 08:54:02.438   862  2021 I art     : Explicit concurrent mark sweep GC freed 39952(1919KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 4.148ms total 241.793ms
,07-27 08:54:02.468  5716  5809 W jxcore-log: Platform android
07-27 08:54:02.468  5716  5809 W jxcore-log: 
,07-27 08:54:02.468  5716  5809 W jxcore-log: Process ARCH arm
07-27 08:54:02.468  5716  5809 W jxcore-log: 
07-27 08:54:02.700  5716  5809 I jxcore-log: JXcore Cordova bridge is ready!
07-27 08:54:02.700  5716  5809 I jxcore-log: 
07-27 08:54:02.700  5716  5809 W jxcore-log: JXcore engine is started
,07-27 08:54:02.706   295   356 I ThermalEngine: Sensor:pa_therm0:31000 mC
07-27 08:54:02.706  5716  5794 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
07-27 08:54:02.708  5716  5716 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
07-27 08:54:06.130  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,07-27 08:54:06.133  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 08:54:06.136  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,07-27 08:54:06.141   464   464 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-27 08:54:06.141  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 08:54:06.142  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-27 08:54:06.184  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-27 08:54:06.185  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-27 08:54:06.185  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
07-27 08:54:06.185  1368  1368 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
,07-27 08:54:06.187  1873  2040 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 08:54:06.187  1873  2040 D LEDHandler: Battery Level Remaining: 100%
07-27 08:54:06.188  1873  2040 D LEDHandler: Battery Temp: 290, mChargingStatus=5, mChargingStop=false
07-27 08:54:06.189  1368  1368 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
07-27 08:54:06.192  5579  5579 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-27 08:54:06.198  1368  1368 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,07-27 08:54:06.202   862  1312 D WifiController: battery changed pluggedType: 2
07-27 08:54:07.711   295   356 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 08:54:09.461   862  1283 V AlarmManager: ELAPSED_WAKEUP set : Alarm{4d38517 type 2 when 120000 com.google.android.gms} when 120000
,07-27 08:54:09.462   862  1283 V AlarmManager: ELAPSED_WAKEUP set : Alarm{766dd04 type 2 when 120678 com.google.android.gms} when 120678
,07-27 08:54:09.685   862  2204 D ConnectivityService: listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:54:09.685   862  1313 D ConnectivityService: dumpNetworkRequest
07-27 08:54:09.748  1757  3060 I art     : Explicit concurrent mark sweep GC freed 44588(2MB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 14MB/23MB, paused 1.892ms total 117.995ms
,07-27 08:54:09.767  5349  5859 W DriveInitializer: Background init thread started
,07-27 08:54:09.821   244   325 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-27 08:54:09.821   244   325 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
07-27 08:54:09.821   244   325 W Vold    : Returning OperationFailed - no handler for errno 0
,07-27 08:54:09.825  5349  5859 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
07-27 08:54:09.892  5349  5859 W DriveInitializer: Background init thread ended
,07-27 08:54:12.197   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 08:54:12.197   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 08:54:12.197   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 133164853391; DSPS: 4455113; Offset : -2804519026
,07-27 08:54:12.716   295   356 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 08:54:16.987  2865  2865 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,07-27 08:54:16.997  2865  2865 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
07-27 08:54:17.721   295   356 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 08:54:19.137  5716  5809 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-27 08:54:19.137  5716  5809 I jxcore-log: 
07-27 08:54:19.140  5716  5809 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-27 08:54:19.140  5716  5809 I jxcore-log: 
,07-27 08:54:19.143  5716  5809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:54:19.143  5716  5809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 08:54:19.143  5716  5809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:54:19.143  5716  5809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-27 08:54:19.143  5716  5809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 08:54:19.143  5716  5809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 08:54:19.143  5716  5809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 08:54:19.143  5716  5809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 08:54:19.143  5716  5809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 08:54:19.143  5716  5809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:54:19.144  5716  5809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 08:54:19.146  5716  5809 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-27 08:54:19.146  5716  5809 I jxcore-log: 
07-27 08:54:19.149  5716  5809 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-27 08:54:19.149  5716  5809 I jxcore-log: 
07-27 08:54:19.674  5716  5809 I jxcore-log: Unit Test app is loaded
07-27 08:54:19.674  5716  5809 I jxcore-log: 
,07-27 08:54:19.681  5716  5809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 08:54:19.681  5716  5809 I jxcore-log: 
07-27 08:54:19.696  5716  5716 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-27 08:54:19.702   862  1946 D WifiServiceImplEx: setWifiEnabled: true pid=5716, uid=10030, package= com.test.thalitest, App Lable : ThaliTest
07-27 08:54:19.716   862  1946 D WifiService: setWifiEnabled: true pid=5716, uid=10030
,07-27 08:54:19.752   862  2204 D WifiServiceImplEx: disconnect pid=5716, uid=10030, packageName=com.test.thalitest
,07-27 08:54:19.755   862   882 D WifiServiceImplEx: reconnect pid=5716, uid=10030, packageName=com.test.thalitest
07-27 08:54:19.759   862  1906 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 08:54:19.763   862  1307 I LGFTMITEM: [GET_FTM][id=6], offset=12288
07-27 08:54:19.765   862  1307 E WifiHW  : Wifi MAC Address = a0:39:f7:70:12:80
,07-27 08:54:19.765   862  1906 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
07-27 08:54:19.774   862   862 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-27 08:54:19.776   862   862 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,07-27 08:54:19.777   862  1307 E WifiHW  : wifi_check_config compare "cur_etheraddr=a0:39:f7:70:12:80
07-27 08:54:19.777   862  1307 E WifiHW  : band=b
07-27 08:54:19.777   862  1307 E WifiHW  : ": cur_etheraddr=a0:39:f7:70:12:80
07-27 08:54:19.785   862   862 D Ulp_jni : JNI:system_update. Event-4
,07-27 08:54:19.789   862  1014 D BluetoothManagerService: Message: 1
07-27 08:54:19.790   275   915 D SoftapController: Softap fwReload - Ok
07-27 08:54:19.790   862  1014 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
07-27 08:54:19.790   862   862 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-27 08:54:19.791   862   862 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
07-27 08:54:19.791   862   862 D Ulp_jni : JNI:system_update. Event-4
07-27 08:54:19.795  5716  5809 I jxcore-log: My device name is: LGE-LG-D722
07-27 08:54:19.795  5716  5809 I jxcore-log: 
07-27 08:54:19.799  5716  5809 I jxcore-log: WARN testUtils: myNameCallback not set!
07-27 08:54:19.799  5716  5809 I jxcore-log: 
07-27 08:54:19.802  2074  2074 D BluetoothAdapterService(340792543): onBind()
,07-27 08:54:19.806   862   862 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
07-27 08:54:19.807   862  1014 D BluetoothManagerService: Message: 40
07-27 08:54:19.807   862  1014 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
07-27 08:54:19.810   862  1307 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:19.810   862  1307 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:54:19.813   275   915 D CommandListener: Setting iface cfg
07-27 08:54:19.813   275   915 D CommandListener: Trying to bring down wlan0
07-27 08:54:19.814   275   915 D CommandListener: Clearing all IP addresses on wlan0
07-27 08:54:19.829   862  1307 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,07-27 08:54:19.843   862  1307 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-27 08:54:19.844  2074  2091 I bluedroid: config_hci_snoop_log
07-27 08:54:19.853  5716  5716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 08:54:19.857  1909  1909 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
07-27 08:54:19.867  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-27 08:54:19.865 DNS addrs= 0.0.0.0, 0.0.0.0, 
,07-27 08:54:19.871  1909  1909 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
07-27 08:54:19.885   862  1014 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
07-27 08:54:19.885   862  1014 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,07-27 08:54:19.951   862   902 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=5885 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
07-27 08:54:19.952  2074  2090 V LGMDMManagerInternal: Create singleton instance
07-27 08:54:19.956  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-27 08:54:19.958   862   862 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
07-27 08:54:19.958  5875  5875 I wpa_supplicant: Successfully initialized wpa_supplicant
07-27 08:54:19.965  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 08:54:19.965  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
07-27 08:54:19.965  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
,07-27 08:54:20.010  5875  5875 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-27 08:54:20.010  5875  5875 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,07-27 08:54:20.073  2074  2090 D BluetoothAdapterService(340792543): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@20c384ad
07-27 08:54:20.073  2074  2090 D BluetoothAdapterService(340792543): enable() - Enable called with quiet mode status =  false
07-27 08:54:20.075  2074  2237 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
07-27 08:54:20.075  2074  2237 D BluetoothAdapterProperties: Setting state to 11
07-27 08:54:20.076  2074  2237 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
07-27 08:54:20.078  2074  2237 D BluetoothAdapterService(340792543): updateAdapterState() - Broadcasting state to 1 receivers.
07-27 08:54:20.082   862  1014 D BluetoothManagerService: Message: 60
,07-27 08:54:20.084   862  1014 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
07-27 08:54:20.085  2074  2237 D BluetoothAdapterService(340792543): processStart()
07-27 08:54:20.086   862  1014 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
07-27 08:54:20.089  2074  2237 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-27 08:54:20.092  2074  2090 D BluetoothAdapterService(340792543): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@20c384ad
07-27 08:54:20.093  2074  2091 D BluetoothAdapterService(340792543): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@20c384ad
,07-27 08:54:20.096  1873  1873 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
07-27 08:54:20.105  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.bluetooth.adapter.action.STATE_CHANGED at null
07-27 08:54:20.112  1368  1368 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,07-27 08:54:20.128  2074  2237 D BtSettings.ProfileConfig: Unable to read settings
07-27 08:54:20.128  2074  2237 D BtSettings.ProfileConfig: android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
07-27 08:54:20.128  2074  2237 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
07-27 08:54:20.128  2074  2237 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getInt(Settings.java:1443)
07-27 08:54:20.128  2074  2237 D BtSettings.ProfileConfig: 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
07-27 08:54:20.128  2074  2237 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:672)
07-27 08:54:20.128  2074  2237 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
07-27 08:54:20.128  2074  2237 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
07-27 08:54:20.128  2074  2237 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
07-27 08:54:20.128  2074  2237 D BtSettings.ProfileConfig: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:54:20.128  2074  2237 D BtSettings.ProfileConfig: 	at android.os.Looper.loop(Looper.java:135)
07-27 08:54:20.128  2074  2237 D BtSettings.ProfileConfig: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-27 08:54:20.132  2074  2237 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
07-27 08:54:20.132  2074  2237 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,07-27 08:54:20.134  2074  2237 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
07-27 08:54:20.134  2074  2237 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-27 08:54:20.135  2074  2237 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
07-27 08:54:20.135  2074  2237 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-27 08:54:20.136  2074  2237 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
07-27 08:54:20.136  2074  2237 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-27 08:54:20.137  2074  2237 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
07-27 08:54:20.137  2074  2237 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
07-27 08:54:20.137  2074  2237 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
07-27 08:54:20.137  2074  2237 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-27 08:54:20.141  2074  2237 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
07-27 08:54:20.141  2074  2237 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-27 08:54:20.142  2074  2237 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
07-27 08:54:20.142  2074  2237 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
07-27 08:54:20.142  2074  2237 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.ftp.FTPService
07-27 08:54:20.142  2074  2237 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
07-27 08:54:20.144  2074  2237 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.opp.OppService
07-27 08:54:20.144  2074  2237 D BluetoothAdapterService(340792543): processStart() - Make Bond State Machine
,07-27 08:54:20.156  2074  2237 D BluetoothBondStateMachine: make
07-27 08:54:20.167  2074  2237 D BluetoothAdapterService: setAdapterService() - set to: null
07-27 08:54:20.167  2074  2237 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@145014df
07-27 08:54:20.167  2074  2237 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
,07-27 08:54:20.172  2074  5904 I BluetoothBondStateMachine: StableState(): Entering Off State
07-27 08:54:20.177  2074  2237 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-27 08:54:20.177  2074  2237 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
07-27 08:54:20.177  2074  2237 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-27 08:54:20.178  2074  2237 D BtSettings.ProfileConfig: Unable to read settings
07-27 08:54:20.178  2074  2237 D BtSettings.ProfileConfig: android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
07-27 08:54:20.178  2074  2237 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
07-27 08:54:20.178  2074  2237 D BtSettings.ProfileConfig: 	at android.provider.Settings$System.getInt(Settings.java:1443)
07-27 08:54:20.178  2074  2237 D BtSettings.ProfileConfig: 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
07-27 08:54:20.178  2074  2237 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
07-27 08:54:20.178  2074  2237 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:712)
07-27 08:54:20.178  2074  2237 D BtSettings.ProfileConfig: 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
07-27 08:54:20.178  2074  2237 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
07-27 08:54:20.178  2074  2237 D BtSettings.ProfileConfig: 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
07-27 08:54:20.178  2074  2237 D BtSettings.ProfileConfig: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:54:20.178  2074  2237 D BtSettings.ProfileConfig: 	at android.os.Looper.loop(Looper.java:135)
07-27 08:54:20.178  2074  2237 D BtSettings.ProfileConfig: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-27 08:54:20.178  2074  2237 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
07-27 08:54:20.178  2074  2237 D BluetoothAdapterService(340792543): setProfileServiceState() - Starting service com.android.bluetooth.hfp.HeadsetService
,07-27 08:54:20.189  2074  2237 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-27 08:54:20.192  2074  2237 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
07-27 08:54:20.192  2074  2237 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-27 08:54:20.192  2074  2237 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,07-27 08:54:20.192  2074  2237 D BluetoothAdapterService(340792543): setProfileServiceState() - Starting service com.android.bluetooth.a2dp.A2dpService
07-27 08:54:20.195  2074  2074 D HeadsetService: Received start request. Starting profile...
07-27 08:54:20.198  1787  1787 D BluetoothHeadset: Proxy object connected
07-27 08:54:20.199   862   862 D BluetoothHeadset: Proxy object connected
07-27 08:54:20.208  2074  2074 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
,07-27 08:54:20.211  2074  2237 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-27 08:54:20.211  2074  2237 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
07-27 08:54:20.211  2074  2237 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-27 08:54:20.211  2074  2237 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
07-27 08:54:20.211  2074  2237 D BluetoothAdapterService(340792543): setProfileServiceState() - Starting service com.android.bluetooth.hid.HidService
07-27 08:54:20.215  2074  2237 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-27 08:54:20.216  2074  2237 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
07-27 08:54:20.216  2074  2237 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-27 08:54:20.216  2074  2237 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
07-27 08:54:20.216  2074  2237 D BluetoothAdapterService(340792543): setProfileServiceState() - Starting service com.android.bluetooth.hdp.HealthService
07-27 08:54:20.221  2074  2237 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-27 08:54:20.221  2074  2237 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
07-27 08:54:20.221  2074  2237 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-27 08:54:20.221  2074  2237 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
07-27 08:54:20.221  2074  2237 D BluetoothAdapterService(340792543): setProfileServiceState() - Starting service com.android.bluetooth.pan.PanService
,07-27 08:54:20.226  2074  2237 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-27 08:54:20.226  2074  2237 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
07-27 08:54:20.226  2074  2237 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
07-27 08:54:20.226  2074  2237 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
07-27 08:54:20.226  2074  2237 D BluetoothAdapterService(340792543): setProfileServiceState() - Starting service com.android.bluetooth.gatt.GattService
07-27 08:54:20.230  2074  2091 D BluetoothAdapterService(340792543): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@20c384ad
07-27 08:54:20.235  2074  2237 D BluetoothAdapterService: getQuietmodeRadioCount = 0
,07-27 08:54:20.235  2074  2237 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
07-27 08:54:20.235  2074  2237 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-27 08:54:20.236  2074  2237 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
07-27 08:54:20.236  2074  2237 D BluetoothAdapterService(340792543): setProfileServiceState() - Starting service com.android.bluetooth.map.BluetoothMapService
07-27 08:54:20.244  2074  2074 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-27 08:54:20.245  2074  2074 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-27 08:54:20.247  1787  1787 D BluetoothHeadset: Proxy object connected
07-27 08:54:20.248  2074  2237 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-27 08:54:20.248  2074  2237 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
07-27 08:54:20.248  2074  2237 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-27 08:54:20.248  2074  2237 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
07-27 08:54:20.248  2074  2237 D BluetoothAdapterService(340792543): setProfileServiceState() - Starting service com.broadcom.bt.service.sap.SapService
,07-27 08:54:20.250  2074  2074 D HeadsetStateMachine: make
07-27 08:54:20.251  1787  1787 D BluetoothHeadset: Proxy object connected
07-27 08:54:20.256  2074  2237 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-27 08:54:20.256  2074  2237 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
07-27 08:54:20.256  2074  2237 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
07-27 08:54:20.256  2074  2237 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.ftp.FTPService
07-27 08:54:20.256  2074  2237 D BluetoothAdapterService(340792543): setProfileServiceState() - Starting service com.broadcom.bt.service.ftp.FTPService
07-27 08:54:20.263  2074  2237 D BluetoothAdapterService: getQuietmodeRadioCount = 0
07-27 08:54:20.263  2074  2237 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
07-27 08:54:20.263  2074  2237 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
07-27 08:54:20.263  2074  2237 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.opp.OppService
07-27 08:54:20.264  2074  2237 D BluetoothAdapterService(340792543): setProfileServiceState() - Starting service com.broadcom.bt.service.opp.OppService
,07-27 08:54:20.272  2074  2237 V LGMDMManager: Create singleton instance
07-27 08:54:20.292  2074  2237 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,07-27 08:54:20.297  2074  2074 D HeadsetStateMachine: max_hf_connections = 1
07-27 08:54:20.297  2074  2074 I bluedroid: get_profile_interface handsfree
07-27 08:54:20.302  2074  2074 I bt-btif : btif_hf_get_interface
07-27 08:54:20.302  2074  2074 I bt-btif : init
07-27 08:54:20.302  2074  2074 D bt-btif : max_hf_clients = 1
07-27 08:54:20.302  2074  2074 D bt-btif : btif_max_hf_clients = 1
07-27 08:54:20.302  2074  2074 D bt-btif : btif_enable_service: current services:0xa066d330
07-27 08:54:20.310  2074  2074 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
07-27 08:54:20.311   279  1321 V AudioPolicyService: registerClient() client 0xb4027800, uid 1002
,07-27 08:54:20.312   279  1606 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
07-27 08:54:20.312   279  1606 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-27 08:54:20.312   279  1606 V AudioPolicyManagerEx: getOutput() returns output 2
07-27 08:54:20.313   279  1298 V AudioFlinger: registerClient() client 0xb4033148, pid 2074
07-27 08:54:20.313   279  1298 V AudioFlinger: sendConfigEvent_l() num events 1 event 0
07-27 08:54:20.313   279  1298 V AudioFlinger: sendConfigEvent_l() num events 1 event 0
07-27 08:54:20.313   279  1298 V AudioFlinger: sendConfigEvent_l() num events 1 event 0
07-27 08:54:20.313  2074  2074 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
07-27 08:54:20.314   279  1290 V AudioFlinger: thread 0xb5735000 type 0 TID 1290 waking up
07-27 08:54:20.314   279  1287 V AudioFlinger: thread 0xb5651000 type 0 TID 1287 waking up
07-27 08:54:20.314   279  1290 V AudioFlinger: processConfigEvents_l() remaining events 1
07-27 08:54:20.314   279  1287 V AudioFlinger: processConfigEvents_l() remaining events 1
07-27 08:54:20.314   279  1290 V AudioFlinger: PlaybackThread::audioConfigChanged, thread 0xb5735000, event 0, param 0
07-27 08:54:20.314   279  1287 V AudioFlinger: PlaybackThread::audioConfigChanged, thread 0xb5651000, event 0, param 0
07-27 08:54:20.314   279  1288 V AudioFlinger: thread 0xb56eb000 type 0 TID 1288 waking up
07-27 08:54:20.315   279  1288 V AudioFlinger: processConfigEvents_l() remaining events 1
07-27 08:54:20.315   279  1288 V AudioFlinger: PlaybackThread::audioConfigChanged, thread 0xb56eb000, event 0, param 0
07-27 08:54:20.315   279  1288 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 08:54:20.315   279  1288 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 08:54:20.316   862  1946 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 08:54:20.316  1368  1610 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 08:54:20.316  1368  1610 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 08:54:20.316   862  1946 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 08:54:20.316   279  1288 V AudioFlinger: processConfigEvents_l() DONE thread 0xb56eb000
07-27 08:54:20.316  1787  3141 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 08:54:20.316  1787  3141 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 08:54:20.316  2023  5742 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 08:54:20.316  2023  5742 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 08:54:20.316  3103  3119 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 08:54:20.316  3103  3119 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 08:54:20.316  2074  2090 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 08:54:20.316  2074  2090 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
07-27 08:54:20.316  2865  2882 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
07-27 08:54:20.316  2865  2882 V AudioSystem: ioConfigChanged() opening already existing output! 4
07-27 08:54:20.316   279  1287 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 08:54:20.317   279  1287 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 08:54:20.317  1368  2009 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 08:54:20.317  2023  2047 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 08:54:20.317  1368  2009 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 08:54:20.317  2023  2047 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 08:54:20.317   279  1287 V AudioFlinger: processConfigEvents_l() DONE thread 0xb5651000
07-27 08:54:20.317  2074  2091 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 08:54:20.317   279  1290 V ,AudioSystem: ioConfigChanged() event 0, ioHandle 6
07-27 08:54:20.317   279  1290 V AudioSystem: ioConfigChanged() opening already existing output! 6
07-27 08:54:20.317   862  1291 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 08:54:20.317   862  1291 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 08:54:20.317   862  1291 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
07-27 08:54:20.317   862  1291 V AudioSystem: ioConfigChanged() opening already existing output! 6
07-27 08:54:20.317   279  1290 V AudioFlinger: processConfigEvents_l() DONE thread 0xb5735000
07-27 08:54:20.317  1787  1808 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 08:54:20.317  1787  1808 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 08:54:20.317  1787  1808 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
07-27 08:54:20.317  1368  1392 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
07-27 08:54:20.317  1787  1808 V AudioSystem: ioConfigChanged() opening already existing output! 6
07-27 08:54:20.317  1368  1392 V AudioSystem: ioConfigChanged() opening already existing output! 6
07-27 08:54:20.317  2865  2880 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 08:54:20.317  2023  2046 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
07-27 08:54:20.317  2865  2880 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 08:54:20.317  2023  2046 V AudioSystem: ioConfigChanged() opening already existing output! 6
07-27 08:54:20.317  2865  2880 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
07-27 08:54:20.317  2865  2880 V AudioSystem: ioConfigChanged() opening already existing output! 6
07-27 08:54:20.318  3103  3120 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
07-27 08:54:20.318  3103  3120 V AudioSystem: ioConfigChanged() opening already existing output! 2
07-27 08:54:20.318  2074  2091 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
07-27 08:54:20.318  3103  3120 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
07-27 08:54:20.318  3103  3120 V AudioSystem: ioConfigChanged() opening already existing output! 6
07-27 08:54:20.318  2074  2091 V AudioSystem: ioConfigChanged() event 0, ioHandle 6
07-27 08:54:20.318  2074  2091 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 1152 latency 112
07-27 08:54:20.318  2074  2074 V ToneGenerator: Create Track: 0xb4909480
07-27 08:54:20.318  2074  2074 V AudioTrack: set(): streamType 8, sampleRate 48000, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
07-27 08:54:20.318  2074  2074 V AudioTrack: set() streamType 8, sampleRate 48000, format 1, frameCount 0, flags 0004
07-27 08:54:20.318   279  1321 I AudioFlinger: isAudioPlaybackHookOn() false
07-27 08:54:20.318  2074  2074 D AudioTrack: TrackOffload: AudioTrack Offload disabled by property, returning false
07-27 08:54:20.319   279  1606 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
07-27 08:54:20.319   279  1606 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
07-27 08:54:20.319   279  1606 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
07-27 08:54:20.319   279  1606 V AudioPolicyManagerEx: getOutput() returns output 2
07-27 08:54:20.319  2074  2074 V AudioSystem: getLatency() output 2, latency 50
07-27 08:54:20.319  2074  2074 V AudioSystem: getFrameCount() output 2, frameCount 960
07-27 08:54:20.319  2074  2074 V AudioTrack: createTrack_l() output 2 afLatency 50
07-27 08:54:20.319  2074  2074 V AudioTrack: Create normal PCM 0x1 Track
07-27 08:54:20.320   279   279 V AudioFlinger: createTrack() lSessionId: 22
07-27 08:54:20.320   279   279 V AudioFlinger: AUDIO_OUTPUT_FLAG_FAST accepted: frameCount=480 mFrameCount=240
07-27 08:54:20.320   279   279 V AudioFlinger: sendConfigEvent_l() num events 1 event 1
07-27 08:54:20.321  2074  2074 V AudioTrack: Flags here  0x4 
07-27 08:54:20.321  2074  2074 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
07-27 08:54:20.322   279  1606 V AudioFlinger: acquiring 22 from 2074, for 2074
07-27 08:54:20.322   279  1606 V AudioFlinger:  added new entry for 22
07-27 08:54:20.328   279  1287 V AudioFlinger: processConfigEvents_l() remaining events 1
07-27 08:54:20.330   279  1287 V AudioFlinger: processConfigEvents_l() DONE thread 0xb5651000
07-27 08:54:20.332  2074  2074 V ToneGenerator: ToneGenerator INIT OK, time: 141300
07-27 08:54:20.332  2074  2074 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@145014df
07-27 08:54:20.335  2074  2074 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@145014df
07-27 08:54:20.340  2074  2074 D A2dpService: Received start request. Starting profile...
07-27 08:54:20.340   862   862 D BluetoothA2dp: Proxy object connected
07-27 08:54:20.341  2074  2074 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-27 08:54:20.344  2074  5905 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
07-27 08:54:20.344  2074  2074 V Avrcp   : make
07-27 08:54:20.345  2074  2074 D Avrcp   : [BTUI] Use Native AVRCP : init jni
07-27 08:54:20.345  2074  2074 I bluedroid: get_profile_interface avrcp
07-27 08:54:20.346  2074  5905 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
07-27 08:54:20.346  2074  5905 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
07-27 08:54:20.348  2074  2074 I bt-btif : btif_rc_get_interface
07-27 08:54:20.348  2074  2074 I bt-btif : ## init ##
07-27 08:54:20.348  2074  5905 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
07-27 08:54:20.349   279  1321 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 2074
07-27 08:54:20.349  2074  2090 D BluetoothAdapterService(340792543): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@20c384ad
,07-27 08:54:20.351  2074  2074 I LGBluetoothAvrcpServiceJni: classInitNative: succeeds
07-27 08:54:20.353  2074  2074 I LGBluetoothAvrcpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
07-27 08:54:20.353  2074  2074 I LGBluetoothAvrcpServiceJni: initNative: succeeds
07-27 08:54:20.355   279  1321 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
07-27 08:54:20.355   279  1321 V voice   : voice_set_parameters: enter: bt_samplerate=8000
07-27 08:54:20.355   279  1321 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
07-27 08:54:20.355   279  1321 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-27 08:54:20.355   279  1321 V voice   : voice_set_parameters: exit with code(0)
07-27 08:54:20.355   279  1321 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
07-27 08:54:20.355   279  1321 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
07-27 08:54:20.356  2074  2074 I BluetoothAvrcpBrcmAdapterJni: classInitBrcmNative
07-27 08:54:20.357   279  1321 V msm8974_platform: platform_set_parameters: exit with code(0)
07-27 08:54:20.358   279  1321 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-27 08:54:20.358   279  1321 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
07-27 08:54:20.358   279  1321 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-27 08:54:20.358  2074  5905 V ToneGenerator: ToneGenerator destructor
07-27 08:54:20.358  2074  5905 V ToneGenerator: stopTone
07-27 08:54:20.358  2074  5905 V ToneGenerator: Delete Track: 0xb4909480
07-27 08:54:20.358  2074  5905 V AudioTrack: ~AudioTrack, releasing session id from 2074 on behalf of 2074
07-27 08:54:20.359   279  1298 V AudioFlinger: releasing 22 from 2074 for 2074
07-27 08:54:20.359   279  1298 V AudioFlinger:  decremented refcount to 0
07-27 08:54:20.359   279  1298 V AudioFlinger: purging stale effects
07-27 08:54:20.359   279  1298 V AudioFlinger: remove track (4099) and delete from mixer
07-27 08:54:20.359   279  1298 V AudioPolicyService: AudioCommandThread() adding release output 2
07-27 08:54:20.359   279  1298 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
07-27 08:54:20.359   279  1060 V AudioPolicyService: AudioCommandThread() waking up
07-27 08:54:20.359   279  1060 V AudioPolicyService: AudioCommandThread() processing release output 2
07-27 08:54:20.359   279  1060 V AudioPolicyManager: releaseOutput() 2
07-27 08:54:20.359   279  1060 V AudioPolicyService: AudioCommandThread() going to sleep
07-27 08:54:20.359   279  1298 V AudioFlinger: PlaybackThread::Track destructor
07-27 08:54:20.359   279  1298 V AudioFlinger: removeClient_l() pid 2074, calling pid 279
,07-27 08:54:20.368  2074  2074 I BluetoothAvrcpBrcmAdapterJni: initBrcmNative
07-27 08:54:20.535  5885  5885 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 08:54:20.536  5885  5885 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
07-27 08:54:20.536  5885  5885 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-27 08:54:20.537  5885  5885 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,07-27 08:54:20.547   862   882 V AudioService: updateRemoteControllerOnExistingMediaPlayers: size of Player list: 0
07-27 08:54:20.548   862   882 E AudioService: No RCC entry present to update
07-27 08:54:20.548  2074  2074 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-27 08:54:20.549  2074  2074 I BluetoothA2dpServiceJni: classInitNative
07-27 08:54:20.549  2074  2074 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-27 08:54:20.549  2074  2074 D A2dpStateMachine: make
07-27 08:54:20.550  2074  2074 I bluedroid: get_profile_interface a2dp
07-27 08:54:20.550  2074  2074 I bt-btif : btif_av_get_src_interface
07-27 08:54:20.550  2074  2074 I bt-btif : init
07-27 08:54:20.550  2074  2074 D bt-btif : btif_enable_service: current services:0xa066d330
07-27 08:54:20.552  2074  2074 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
07-27 08:54:20.552  2074  2074 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
07-27 08:54:20.553  2074  2074 D LGBluetoothPowerControlManager: [BTUI] getInstance
,07-27 08:54:20.556  2074  2074 D LGBluetoothPowerControlManager: [BTUI] init
07-27 08:54:20.557  2074  2074 D LGBluetoothPowerControlManager: [BTUI] init : getProfileProxy
07-27 08:54:20.560   862  1014 D BluetoothManagerService: Message: 30
07-27 08:54:20.562  2074  2074 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@145014df
07-27 08:54:20.562  2074  5913 D A2dpStateMachine: Enter Disconnected: -2
07-27 08:54:20.563  2074  2074 I BluetoothHidServiceJni: classInitNative: succeeds
07-27 08:54:20.566  2074  2074 D HidService: Received start request. Starting profile...
07-27 08:54:20.567  2074  2074 I bluedroid: get_profile_interface hidhost
07-27 08:54:20.567  2074  2074 I bt-btif : btif_hh_get_interface
07-27 08:54:20.567  2074  2074 I bt-btif : init
07-27 08:54:20.567  2074  2074 D bt-btif : btif_enable_service: current services:0xa066d330
07-27 08:54:20.567  2074  2074 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@145014df
,07-27 08:54:20.567  2074  2074 I BluetoothHealthServiceJni: classInitNative: succeeds
07-27 08:54:20.571  2074  2074 D HealthService: Received start request. Starting profile...
07-27 08:54:20.573  2074  2074 I bluedroid: get_profile_interface health
07-27 08:54:20.573  2074  2074 I bt-btif : btif_hl_get_interface
07-27 08:54:20.573  2074  2074 I bt-btif : init
07-27 08:54:20.573  2074  2074 D bt-btif : Process name (droid.bluetooth)
07-27 08:54:20.573  2074  2074 D bt-btif : btif_hl_soc_thread_init
07-27 08:54:20.574  2074  2074 D bt-btif : create_thread: entered
07-27 08:54:20.575  2074  2074 D bt-btif : create_thread: thread created successfully
07-27 08:54:20.575  2074  5915 D bt-btif : entered btif_hl_select_thread
07-27 08:54:20.575  2074  5915 D bt-btif : btif_hl_select_wakeup_init
07-27 08:54:20.575  2074  5915 D bt-btif : btif_hl_select_wakeup_init signal_fds[0]=55 signal_fds[1]=56
07-27 08:54:20.575  2074  5915 D bt-btif : max_s=55 
07-27 08:54:20.575  2074  5915 D bt-btif : set curr_set = org_set 
07-27 08:54:20.575  2074  2074 I LGBluetoothHealthServiceJni: classInitNative: succeeds
07-27 08:54:20.575  2074  2074 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@145014df
07-27 08:54:20.577  2074  2074 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-27 08:54:20.580  2074  2074 D PanService: Received start request. Starting profile...
,07-27 08:54:20.580  2074  2074 D BluetoothPanServiceJni: initializeNative(L110): pan
07-27 08:54:20.580  2074  2074 I bluedroid: get_profile_interface pan
07-27 08:54:20.581  2074  2074 D bt-btif : stack_initialized = 0, btpan_cb.enabled:0
07-27 08:54:20.589  2074  2074 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
07-27 08:54:20.589  2074  2074 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@145014df
07-27 08:54:20.590  2074  2074 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
07-27 08:54:20.595  2074  2074 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-27 08:54:20.596  2074  2074 D BtGatt.GattService: Received start request. Starting profile...
07-27 08:54:20.596  2074  2074 D BtGatt.GattService: start()
07-27 08:54:20.596  2074  2074 I bluedroid: get_profile_interface gatt
07-27 08:54:20.597  2074  2074 D BtGatt.AdvertiseManager: advertise manager created
07-27 08:54:20.603  2074  2074 I LGBluetoothGattAdapter: [BTUI] getInstance : create [LGBluetoothGattAdapter]
07-27 08:54:20.603  2074  2074 D LGBluetoothGattAdapter: setGattService:  set to: null
07-27 08:54:20.603  2074  2074 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@145014df
07-27 08:54:20.606  2074  2074 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@145014df
,07-27 08:54:20.607  2074  2074 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
07-27 08:54:20.608  2074  2074 V BluetoothMapService: BluetoothMapBinder()
07-27 08:54:20.609  2074  2074 D BluetoothMapService: Received start request. Starting profile...
07-27 08:54:20.609  2074  2074 D BluetoothMapService: start()
07-27 08:54:20.616  2074  2074 D BluetoothMapEmailSettingsLoader: Found 0 applications
07-27 08:54:20.616  2074  2074 D BluetoothMapEmailAppObserver: createReceiver()
07-27 08:54:20.617  2074  2074 D BluetoothMapEmailAppObserver: initObservers()
07-27 08:54:20.617  2074  2074 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,07-27 08:54:20.622  5885  5885 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
07-27 08:54:20.625  2074  2074 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@145014df
07-27 08:54:20.631  2074  2074 I BluetoothSAPServiceJni: classInitNative(L170): succeeds
07-27 08:54:20.634  2074  2074 D SapService: Received start request. Starting profile...
07-27 08:54:20.634  2074  2074 D BluetoothSAPServiceJni: initializeNative(L175): sap
,07-27 08:54:20.634  2074  2074 I bluedroid: get_profile_interface sap
,07-27 08:54:20.634  2074  2074 I bt-btif : btif_sc_get_interface
07-27 08:54:20.634  2074  2074 I bt-btif : init
07-27 08:54:20.634  2074  2074 D bt-btif : btif_enable_service: current services:0xa066d330
07-27 08:54:20.634  2074  2074 I LGBluetoothSapAdapter: [BTUI] getInstance : create [LGBluetoothSapAdapter]
07-27 08:54:20.634  2074  2074 I LGBluetoothSapAdapter: [BTUI] Create LGBluetoothSapManager Instance
07-27 08:54:20.636  2074  2074 D LGBluetoothSapManager: [BTUI] initSapManager
07-27 08:54:20.645  1787  1787 D LgeBluetoothSimManager: [BTUI] SAP_ENABLE_EVT
07-27 08:54:20.674  2074  2074 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@145014df
,07-27 08:54:20.687  2074  2074 V BluetoothFTPServiceJni: classInitNative
07-27 08:54:20.688  2074  2074 I BluetoothFTPServiceJni: classInitNative(L271): succeeds
07-27 08:54:20.688  2074  2074 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@145014df
07-27 08:54:20.689  2074  2074 D BluetoothFTPService: BluetoothFtpBinder()
07-27 08:54:20.690  2074  2074 D **BluetoothFTPService: Received start request. Starting profile...
07-27 08:54:20.690  2074  2074 V BluetoothFTPService: FTP-Server Service start
,07-27 08:54:20.692  2074  2074 D BluetoothFTPServiceJni: initFtpNativeDataNative(L275): FTP
,07-27 08:54:20.692  2074  2074 I bluedroid: get_profile_interface ftp
07-27 08:54:20.692  2074  2074 I bt-btif : btif_fts_get_interface
07-27 08:54:20.692  2074  2074 I bt-btif : init
07-27 08:54:20.692  2074  2074 D bt-btif : btif_enable_service: current services:0xa066d330
07-27 08:54:20.692  2074  2074 D BluetoothFTPServiceJni: initFtpNativeDataNative(L317): FTP init done
07-27 08:54:20.693  2074  2074 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@145014df
07-27 08:54:20.693  2074  2074 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-27 08:54:20.693  2074  2074 E BluetoothOPPServiceJni: classInitNative
07-27 08:54:20.694  2074  2074 I BluetoothOPPServiceJni: classInitNative(L373): succeeds
07-27 08:54:20.694  2074  2074 V OppService: Opp initBinder
07-27 08:54:20.696  2074  2074 D **OppService: Received start request. Starting profile...
07-27 08:54:20.696  2074  2074 D OppService: Starting OppService 
07-27 08:54:20.697  2074  2074 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
07-27 08:54:20.703  2074  2074 I NotificationManager: com.android.bluetooth: cancelAll by com.android.bluetooth
07-27 08:54:20.704  2074  2074 V BluetoothOppNotification: send message
,07-27 08:54:20.710  2074  2074 D BluetoothOppPreference: Dumping Names:  
07-27 08:54:20.710  2074  2074 D BluetoothOppPreference: {}
07-27 08:54:20.710  2074  2074 D BluetoothOppPreference: Dumping Channels:  
07-27 08:54:20.710  2074  2074 D BluetoothOppPreference: {}
07-27 08:54:20.711  2074  2074 D OppService: Start()
07-27 08:54:20.711  2074  2074 W BluetoothOPPServiceJni: initOppNative
07-27 08:54:20.711  2074  2074 D BluetoothOPPServiceJni: initOppNative(L383): OPP
07-27 08:54:20.711  2074  2074 I bluedroid: get_profile_interface opp
07-27 08:54:20.711  2074  2074 I bt-btif : btif_op_get_interface
07-27 08:54:20.711  2074  2074 D BluetoothOPPServiceJni: initOppNative(L411): mOppCallbacksObj 2098426
07-27 08:54:20.711  2074  2074 D BluetoothOPPServiceJni: initOppNative(L413): calling OPP init
07-27 08:54:20.712  2074  2074 I bt-btif : btif_opp_init
07-27 08:54:20.712  2074  2074 D bt-btif : btif_enable_service: current services:0xa066d330
07-27 08:54:20.712  2074  2074 D BluetoothOPPServiceJni: initOppNative(L429): OPC and OPS init Succesful
07-27 08:54:20.712  2074  2074 D BluetoothOPPServiceJni: initOppNative(L430): mOppCallbacksObj 2098426
07-27 08:54:20.712  2074  2074 V OppService: setOppService(): set to: com.broadcom.bt.service.opp.OppService@10d543fd
07-27 08:54:20.713  2074  2074 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@145014df
07-27 08:54:20.713  2074  2074 D HeadsetStateMachine: Proxy object connected
07-27 08:54:20.714  2074  2074 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
07-27 08:54:20.714  2074  2074 D BluetoothAdapterService(340792543): handleMessage() - Message: 1
07-27 08:54:20.714  2074  2074 D BluetoothAdapterService(340792543): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-27 08:54:20.715  2074  2074 D BluetoothAdapterService(340792543): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
07-27 08:54:20.715  2074  2074 D BluetoothAdapterState: isTurningOnRadio()=false
07-27 08:54:20.715  2074  2074 D BluetoothAdapterState: isTurningOffRadio()=false
07-27 08:54:20.715  2074  2074 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-27 08:54:20.715  2074  2074 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-27 08:54:20.715  2074  2074 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
07-27 08:54:20.716  2074  5923 V OppService: pendingUpdate is :  true
,07-27 08:54:20.721  2074  2074 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
07-27 08:54:20.721  2074  2074 D BluetoothA2dp: Proxy object connected
07-27 08:54:20.722  2074  2074 D LGBluetoothPowerControlManager: [BTUI] onServiceConnected : Got BluetoothA2dp: android.bluetooth.BluetoothA2dp@383338f2
07-27 08:54:20.722  2074  5905 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 08:54:20.722  2074  2074 D BluetoothAdapterService(340792543): handleMessage() - Message: 1
07-27 08:54:20.722  2074  2074 D BluetoothAdapterService(340792543): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-27 08:54:20.722  2074  2074 D BluetoothAdapterService(340792543): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
07-27 08:54:20.722  2074  2074 D BluetoothAdapterState: isTurningOnRadio()=false
07-27 08:54:20.722  2074  2074 D BluetoothAdapterState: isTurningOffRadio()=false
07-27 08:54:20.722  2074  2074 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-27 08:54:20.722  2074  2074 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-27 08:54:20.722  2074  2074 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
07-27 08:54:20.723  2074  5905 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-27 08:54:20.723  2074  5905 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-27 08:54:20.726  2074  2074 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
07-27 08:54:20.726  2074  2074 D BluetoothAdapterService(340792543): handleMessage() - Message: 1
07-27 08:54:20.726  2074  2074 D BluetoothAdapterService(340792543): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-27 08:54:20.726  2074  2074 D BluetoothAdapterService(340792543): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
07-27 08:54:20.726  2074  2074 D BluetoothAdapterState: isTurningOnRadio()=false
07-27 08:54:20.726  2074  2074 D BluetoothAdapterState: isTurningOffRadio()=false
07-27 08:54:20.726  2074  2074 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-27 08:54:20.726  2074  2074 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-27 08:54:20.726  2074  2074 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
07-27 08:54:20.728  2074  2074 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
07-27 08:54:20.729  2074  2074 D BluetoothAdapterService(340792543): handleMessage() - Message: 1
07-27 08:54:20.729  2074  2074 D BluetoothAdapterService(340792543): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-27 08:54:20.729  2074  2074 D BluetoothAdapterService(340792543): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
07-27 08:54:20.729  2074  2074 D BluetoothAdapterState: isTurningOnRadio()=false
07-27 08:54:20.729  2074  2074 D BluetoothAdapterState: isTurningOffRadio()=false
07-27 08:54:20.729  2074  2074 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-27 08:54:20.729  2074  2074 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-27 08:54:20.729  2074  2074 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
,07-27 08:54:20.732  2074  2074 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
07-27 08:54:20.732  2074  2074 V PanService: [BTUI] SIM Extra State :ABSENT
07-27 08:54:20.732  2074  2074 D BluetoothAdapterService(340792543): handleMessage() - Message: 1
07-27 08:54:20.732  2074  2074 D BluetoothAdapterService(340792543): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-27 08:54:20.732  2074  2074 D BluetoothAdapterService(340792543): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
07-27 08:54:20.732  2074  2074 D BluetoothAdapterState: isTurningOnRadio()=false
07-27 08:54:20.732  2074  2074 D BluetoothAdapterState: isTurningOffRadio()=false
07-27 08:54:20.732  2074  2074 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-27 08:54:20.732  2074  2074 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-27 08:54:20.732  2074  2074 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
07-27 08:54:20.735  2074  2074 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
07-27 08:54:20.735  2074  2074 D BluetoothAdapterService(340792543): handleMessage() - Message: 1
07-27 08:54:20.735  2074  2074 D BluetoothAdapterService(340792543): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-27 08:54:20.735  2074  2074 D BluetoothAdapterService(340792543): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=true
07-27 08:54:20.735  2074  2074 D BluetoothAdapterState: isTurningOnRadio()=false
07-27 08:54:20.735  2074  2074 D BluetoothAdapterState: isTurningOffRadio()=false
07-27 08:54:20.735  2074  2074 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-27 08:54:20.735  2074  2074 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-27 08:54:20.735  2074  2074 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
07-27 08:54:20.737  2074  2074 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
07-27 08:54:20.737  2074  2074 V BluetoothMapService: Handler(): got msg=1
07-27 08:54:20.738  2074  2074 D BluetoothAdapterService(340792543): handleMessage() - Message: 1
07-27 08:54:20.738  2074  2074 D BluetoothAdapterService(340792543): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-27 08:54:20.738  2074  2074 D BluetoothAdapterService(340792543): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
07-27 08:54:20.738  2074  2074 D BluetoothAdapterState: isTurningOnRadio()=false
07-27 08:54:20.738  2074  2074 D BluetoothAdapterState: isTurningOffRadio()=false
07-27 08:54:20.738  2074  2074 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-27 08:54:20.738  2074  2074 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-27 08:54:20.738  2074  2074 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
07-27 08:54:20.740  2074  2074 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
07-27 08:54:20.740  2074  2074 D BluetoothAdapterService(340792543): handleMessage() - Message: 1
07-27 08:54:20.741  2074  2074 D BluetoothAdapterService(340792543): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-27 08:54:20.741  2074  2074 D BluetoothAdapterService(340792543): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
07-27 08:54:20.741  2074  2074 D BluetoothAdapterState: isTurningOnRadio()=false
07-27 08:54:20.741  2074  2074 D BluetoothAdapterStat,e: isTurningOffRadio()=false
07-27 08:54:20.741  2074  2074 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-27 08:54:20.741  2074  2074 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-27 08:54:20.741  2074  2074 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
07-27 08:54:20.743  2074  2074 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
07-27 08:54:20.743  2074  2074 D BluetoothAdapterService(340792543): handleMessage() - Message: 1
07-27 08:54:20.743  2074  2074 D BluetoothAdapterService(340792543): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-27 08:54:20.744  2074  2074 D BluetoothAdapterService(340792543): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, doUpdate=true
07-27 08:54:20.744  2074  2074 D BluetoothAdapterState: isTurningOnRadio()=false
07-27 08:54:20.744  2074  2074 D BluetoothAdapterState: isTurningOffRadio()=false
07-27 08:54:20.744  2074  2074 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-27 08:54:20.744  2074  2074 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-27 08:54:20.744  2074  2074 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
,07-27 08:54:20.746  2074  2074 D BluetoothAdapterService: Profile still not running:com.broadcom.bt.service.opp.OppService
07-27 08:54:20.746  2074  2074 V BluetoothOppNotification: new notify threadi!
07-27 08:54:20.747  2074  2074 V BluetoothOppNotification: send delay message
07-27 08:54:20.747  2074  2074 D BluetoothAdapterService(340792543): handleMessage() - Message: 1
07-27 08:54:20.747  2074  2074 D BluetoothAdapterService(340792543): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
07-27 08:54:20.747  2074  2074 D BluetoothAdapterService(340792543): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=12, doUpdate=true
07-27 08:54:20.747  2074  2074 D BluetoothAdapterState: isTurningOnRadio()=false
07-27 08:54:20.747  2074  2074 D BluetoothAdapterState: isTurningOffRadio()=false
07-27 08:54:20.747  2074  2074 D BluetoothAdapterState: isQuietModeServiceTurningOn()=false
07-27 08:54:20.747  2074  2074 D BluetoothAdapterState: isQuietModeServiceTurningOff()=false
07-27 08:54:20.747  2074  2074 D BluetoothAdapterService: processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
07-27 08:54:20.747  2074  2074 D BluetoothAdapterService(340792543): onProfileServiceStateChange() - All profile services started.
07-27 08:54:20.748  2074  2237 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
07-27 08:54:20.748  2074  2237 I bluedroid: enable
07-27 08:54:20.748  2074  5923 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-27 08:54:20.749  2074  2237 I bt-btif : BTIF ENABLE BLUETOOTH :: current btif_core_radio_refcount: 0, btif_core_state: 0, btif_core_cb.dut_mode: 0
07-27 08:54:20.749  2074  2237 E bt-btu  : VERSION AFBT-LREL-30_00.06 (BTE: BTE0322_00.20.00)
07-27 08:54:20.750  2074  2074 V OppService: ContentObserver received notification
07-27 08:54:20.750  2074  5920 V OppService: Deleted complete outbound shares, number =  0
07-27 08:54:20.752  2074  2074 V OppService: ContentObserver received notification
07-27 08:54:20.753  2074  5920 V OppService: Deleted complete inbound failed shares, number = 0
07-27 08:54:20.753  2074  5920 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
07-27 08:54:20.753  2074  2237 I bt_hci_bdroid: init
07-27 08:54:20.753  2074  2237 I bt_vendor: init
07-27 08:54:20.753  2074  2237 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-27 08:54:20.754  2074  5925 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
07-27 08:54:20.755  2074  5920 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f3722f9 on behalf of 
07-27 08:54:20.755  2074  2237 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
07-27 08:54:20.755  2074  5924 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,07-27 08:54:20.757  2074  5925 I bt-btu  : btu_task pending for preload complete event
07-27 08:54:20.757  2074  2237 I bt-btif : libbt-hci init returns 0
07-27 08:54:20.759  2074  5923 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@cb7f23e on behalf of 
07-27 08:54:20.761  5885  5885 I IndexDatabaseHelper: Using schema version: 115
07-27 08:54:20.763  5885  5885 I IndexDatabaseHelper: Index is fine
,07-27 08:54:20.773  2074  5923 V OppService: pendingUpdate is :  true
07-27 08:54:20.773  2074  5923 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
07-27 08:54:20.774  2074  5924 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1015389f on behalf of 
07-27 08:54:20.774  2074  5923 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a43bdec on behalf of 
07-27 08:54:20.775  2074  5923 V BluetoothOppNotification: update too frequent, put in queue
07-27 08:54:20.775  2074  5924 V BluetoothOppNotification: mUpdateCompleteNotification = true
07-27 08:54:20.776  2074  5923 V OppService: pendingUpdate is :  false
07-27 08:54:20.776  2074  5923 E OppService: UpdateThread is Completed
07-27 08:54:20.777  2074  5924 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-27 08:54:20.781  2074  5924 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33df5b5 on behalf of 
07-27 08:54:20.782  2074  5924 V BluetoothOppNotification: outbound: succ-0  fail-0
,07-27 08:54:20.783  2074  5924 I NotificationManager: com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
07-27 08:54:20.784  2074  5924 V BluetoothOppNotification: outbound notification was removed.
07-27 08:54:20.784  2074  5924 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-27 08:54:20.785  2074  5924 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@13cf44a on behalf of 
07-27 08:54:20.786  2074  5924 V BluetoothOppNotification: inbound: succ-0  fail-0
07-27 08:54:20.787  2074  5924 I NotificationManager: com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
07-27 08:54:20.788  2074  5924 V BluetoothOppNotification: inbound notification was removed.
07-27 08:54:20.788  2074  5924 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-27 08:54:20.789  2074  5924 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@149ebfbb on behalf of 
07-27 08:54:20.842  2074  5927 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS99
,07-27 08:54:20.844  2074  5927 D bt_userial_vendor: userial_vendor_open():UART is setup
07-27 08:54:20.844  2074  5927 I bt_userial_vendor: device fd = 68 open
07-27 08:54:20.863  2074  5927 D bt_hwcfg: hw_config_cback opcode:0x0c03
07-27 08:54:20.863  2074  5927 D bt_hwcfg: hw_config_cback state=1
,07-27 08:54:20.889  2074  5927 D bt_hwcfg: hw_config_cback opcode:0x0c14
07-27 08:54:20.889  2074  5927 D bt_hwcfg: hw_config_cback state=4
07-27 08:54:20.889  2074  5927 D bt_hwcfg: Chipset Name: BCM4334B0
07-27 08:54:20.889  2074  5927 D bt_hwcfg: Chipset BCM4334B0
07-27 08:54:20.889  2074  5927 D bt_hwcfg: Target name = [BCM4334B0]
,07-27 08:54:20.889  2074  5927 I bt_hwcfg: Found patchfile: /system/bin//BCM4334B0_002.001.013.1820.2163.hcd
,07-27 08:54:20.894  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc45
07-27 08:54:20.894  2074  5927 D bt_hwcfg: hw_config_cback state=2
07-27 08:54:20.899  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc18
07-27 08:54:20.899  2074  5927 D bt_hwcfg: hw_config_cback state=3
07-27 08:54:20.899  2074  5927 I bt_hwcfg: bt vendor lib: set UART baud 4000000
07-27 08:54:20.921  5885  5885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,07-27 08:54:20.933  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc2e
07-27 08:54:20.934  2074  5927 D bt_hwcfg: hw_config_cback state=5
,07-27 08:54:20.960  5885  5885 D WiFiOffLoadUpdatePriority: remove : truetruefalse
07-27 08:54:20.964  5885  5885 D WiFiOffLoadUpdatePriority: remove2
07-27 08:54:20.964  5885  5885 V WiFiOffLoadSharedPrefsUtils: save wifi state
07-27 08:54:20.964  5885  5885 V WiFiOffLoadSharedPrefsUtils: save remove
07-27 08:54:20.965  5885  5885 D WiFiOffLoadBroadcast: mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
07-27 08:54:20.965  5885  5885 D WiFiOffLoadBroadcast: S: false, R: true
07-27 08:54:20.985  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:20.985  2074  5927 D bt_hwcfg: hw_config_cback state=6
,07-27 08:54:20.987  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:20.987  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:20.988  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:20.988  2074  5927 D bt_hwcfg: hw_config_cback state=6
,07-27 08:54:20.989  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:20.989  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:20.991  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:20.991  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:20.994  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:20.994  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:20.995  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:20.995  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:20.996  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:20.996  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:20.997  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:20.997  2074  5927 D bt_hwcfg: hw_config_cback state=6
,07-27 08:54:20.999  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:20.999  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.000  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.000  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.001  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.001  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.003  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.003  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.004  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.004  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.005  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.005  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.006  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.006  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.007  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.007  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.009   275   908 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
07-27 08:54:21.009   275   908 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
07-27 08:54:21.010  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.010  2074  5927 D bt_hwcfg: hw_config_cback state=6
,07-27 08:54:21.013  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.013  2074  5927 D bt_hwcfg: hw_config_cback state=6
,07-27 08:54:21.015   862  2370 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5931 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
07-27 08:54:21.016  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.016  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.017  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.017  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.018  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.018  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.021  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.021  2074  5927 D bt_hwcfg: hw_config_cback state=6
,07-27 08:54:21.022  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,07-27 08:54:21.022  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.023  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.023  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.024  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.024  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.025  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.025  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.026   862  2370 I ActivityManager: Killing 5038:com.android.defcontainer/u0a4 (adj 15): empty #11
07-27 08:54:21.026  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.026  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.027  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.027  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.028  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.028  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.030  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.030  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.035  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.035  2074  5927 D bt_hwcfg: hw_config_cback state=6
,07-27 08:54:21.037  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.037  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.038  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.038  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.039  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.039  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.040  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.040  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.041  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.041  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.042  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.042  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.043  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.043  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.043  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.043  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.045  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.045  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.046  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.046  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.047  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.047  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.047  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.047  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.048  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.048  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.049  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.049  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.050  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.050  2074  5927 D bt_hwcfg: hw_config_cback state=6
,07-27 08:54:21.050  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.051  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.052  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.052  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.052  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.052  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.052  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.053  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.053  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.053  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.054  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.054  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.054  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.055  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.055  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.056  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.056  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.056  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.057  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.057  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.058  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.058  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.059  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.059  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.060  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.060  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.061  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.061  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.062  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.062  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.062  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.062  2074  5927 D bt_hwcfg: hw_config_cback state=6
,07-27 08:54:21.064  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.064  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.065  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.065  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.066  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.066  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.067  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.067  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.067  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.067  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.068  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.068  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.068  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.068  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.069  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.069  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.070  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.070  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.071  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.071  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.072  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.072  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.073  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.073  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.074  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.074  2074  5927 D bt_hwcfg: hw_config_cback state=6
,07-27 08:54:21.074  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.074  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.075  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.075  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.076  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.076  5875  5875 E wpa_supplicant: USIM:  scard_init function
07-27 08:54:21.076  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.077  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.077  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.077  5875  5875 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-27 08:54:21.078  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.078  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.078  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.078  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.079   275   908 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
07-27 08:54:21.079  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.079  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.080   275   908 I Netd    : M: Get netlink event, ifname: p2p0 action: 9
07-27 08:54:21.080  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.080  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.081  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.081  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.081   275   908 I Netd    : M: Get netlink event, ifname: p2p0 action: 4
07-27 08:54:21.082  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.082  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.083  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.083  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.085  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.085  2074  5927 D bt_hwcfg: hw_config_cback state=6
,07-27 08:54:21.086   862  1012 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:21.086   862  1012 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:54:21.087  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.087  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.088  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.088  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.089  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.089  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.089  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.089  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.090  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.090  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.091  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.091  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.093  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.093  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.094  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.094  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.094  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.094  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.094  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.094  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.095  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.095  2074  5927 D bt_hwcfg: hw_config_cback state=6
,07-27 08:54:21.096  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,07-27 08:54:21.096  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.097  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.097  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.098  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.098  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.099  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.099  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.100  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.100  2074  5927 D bt_hwcfg: hw_config_cback state=6
,07-27 08:54:21.101  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.101  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.101  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.101  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.102  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.102  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.103  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.103  2074  5927 D bt_hwcfg: hw_config_cback state=6
,07-27 08:54:21.104  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.104  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.105  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.105  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.106  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.106  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.107  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.107  2074  5927 D bt_hwcfg: hw_config_cback state=6
,07-27 08:54:21.108  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.108  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.109  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.109  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.110  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.110  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.111  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.111  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.112  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.112  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.113  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.113  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.114  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.114  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.114  2074  2074 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-27 08:54:21.115  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.115  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.115  2074  2074 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 08:54:21.116  2074  2074 V BluetoothPbapReceiver: ***********state = 11
07-27 08:54:21.116  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.116  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.117  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.117  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.117   862  1014 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-27 08:54:21.118  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.118  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.119  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.119  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.120  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.120  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.120  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.120  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.121  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.121  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.125  5875  5875 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
07-27 08:54:21.129  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.129  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.131  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.131  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.132  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.132  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.133  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.133  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.133  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.133  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.134  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.134  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.135  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.135  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.136  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.136  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.137  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.137  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.138  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.138  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.139  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.139  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.140  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.140  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.140  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.140  2074  5927 D bt_hwcfg: hw_config_cback state=6
,07-27 08:54:21.141  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.141  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.142  5875  5875 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
07-27 08:54:21.142  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.142  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.143   862  1307 D WifiStateMachine: MAC Addr from driver = a0:39:f7:70:12:80
07-27 08:54:21.143  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.143  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.144  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.144  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.145  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.145  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.146  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.146  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.147  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.147  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.148  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.148  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.149  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.149  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.149   862  1307 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
07-27 08:54:21.150  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.150  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.151  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.151  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.152  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.152  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.152   862  1375 I ActivityManager: Process com.google.android.apps.docs (pid 5456) has died
07-27 08:54:21.153  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.153  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.154  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.154  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.154   862  1291 W libprocessgroup: failed to open /acct/uid_10004/pid_5038/cgroup.procs: No such file or directory
07-27 08:54:21.155  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.155  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.156  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.156  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.157  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.157  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.158  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.158  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.159  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.159  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.160  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.160  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.161  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.161  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.162  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.162  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.163  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.163  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.164  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.164  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.164  1909  1909 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
07-27 08:54:21.164  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.164  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.165   862   862 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:21.165   862   862 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:21.165  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.165  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.166  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-27 08:54:21.164 DNS addrs= 0.0.0.0, 0.0.0.0, 
07-27 08:54:21.166  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.166  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.166  1909  1909 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
07-27 08:54:21.167  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.167  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.167  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.167  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.168  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.168  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.168  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-27 08:54:21.169  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.169  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 08:54:21.169  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.169  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-27 08:54:21.169  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.169  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.170  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.170  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.171  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.171  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.171  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.171  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.172  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.172  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.172  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.WIFI_STATE_CHANGED at null
07-27 08:54:21.173  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.173  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.173  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.173  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.174   862  1304 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:21.174   862  1304 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:54:21.174  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.174  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.174  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.174  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.175  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.175  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.175  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.175  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.176  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.176  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.177   862   862 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
,07-27 08:54:21.177  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.177  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.178  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.178  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.178  5716  5716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:54:21.178  5716  5716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 08:54:21.178  5716  5716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:54:21.178  5716  5716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-27 08:54:21.178  5716  5716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 08:54:21.178  5716  5716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 08:54:21.178  5716  5716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 08:54:21.178  5716  5716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 08:54:21.178  5716  5716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 08:54:21.178  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.178  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.179  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.179   862  1304 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:21.179  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.179   862  1304 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:54:21.179  5716  5716 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:54:21.179  5716  5716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-27 08:54:21.180  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.180  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.180  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.180  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.181   862  1311 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
07-27 08:54:21.181  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.181  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.181   862   862 E WifiServerServiceExt: sendAutoJoinStatus  LgeWifiConfig.mEnableAutoJoin : 0
07-27 08:54:21.182  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.182  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.182   275   910 E BandwidthController: [LG DATA] No such appUid: 1000
07-27 08:54:21.182   275   910 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
07-27 08:54:21.183   275  5949 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
07-27 08:54:21.183   275  5949 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:54:21.183  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.183  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.183   275  5949 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0, netid=0
07-27 08:54:21.184  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.184  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.184   862  1012 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-27 08:54:21.185  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.185  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.185  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.185  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.186  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.186  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.187  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.187  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.187  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.187  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.188  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.188  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.189  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.189  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.190  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.190  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.191  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.191  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.192  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.192  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.193  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.193  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.194  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.194  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.195  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.195  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.196  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.196  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.197  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.197  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.197  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.198  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.198  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.198  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.199  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.199  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.199  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.199  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.199  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.200  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.200  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.200  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.201  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.201  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.202  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.202  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.203  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.203  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.204  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.204  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.205  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.205  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.205   862  1305 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:21.206  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.206  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.206   862  1305 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:54:21.207  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.207  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.208  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.208  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.209  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.209  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.209  5885  5885 D BluetoothPermissionRequest: onReceive
07-27 08:54:21.210  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.210  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.210  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.210  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.211  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.211  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.211  5885  5885 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
07-27 08:54:21.212  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.212  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.213  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.213  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.214  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.214  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.215  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.215  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.216  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.216  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.217  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
,07-27 08:54:21.217  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.218   862  1307 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-27 08:54:21.218  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.218  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.219  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.219  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.219   862  1307 D WifiStateMachine: enableVerboseLogging : level 2
07-27 08:54:21.220  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.220  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.221  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.221  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.222  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.222  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.223  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.223  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.224  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.224  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.225  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.225  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.225  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.226  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.226  1873  1873 D WfdsService: Supplicant Connection state is changed : true
07-27 08:54:21.226  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.227  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.227  1873  2177 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
07-27 08:54:21.227   862  1307 D WifiStateMachine: Setting OUI to DA-A1-19
07-27 08:54:21.227  1873  2177 D WfdsService: Set the WFDS Monitor: true
07-27 08:54:21.227   862  1307 D WifiNative-HAL: Setting external_sim to 1
07-27 08:54:21.227  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.228  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.228   862  1307 I WifiNative-HAL: startHal
07-27 08:54:21.228   862  1307 E wifi    : getStaticLongField sWifiHalHandle 0x9b4598ec
07-27 08:54:21.228   862  1307 I WifiHAL : Initializing wifi
07-27 08:54:21.228   862  1307 I WifiHAL : Creating socket
07-27 08:54:21.228  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.228  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.229  1873  2177 D WfdsMonitor: WfdsMonitorThread create
07-27 08:54:21.229  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.229  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.230   862  1307 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
07-27 08:54:21.230   862  1307 D wifi    : Did set static halHandle = 0xb05dd4c0
07-27 08:54:21.230   862  1307 D wifi    : halHandle = 0xb05dd4c0, mVM = 0xb487c280, mCls = 0x901a5a
07-27 08:54:21.230   862  1307 E wifi    : getStaticLongField sWifiHalHandle 0x9b45989c
07-27 08:54:21.230  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.230   862  1307 D wifi    : array field set
07-27 08:54:21.230  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.230   862  1307 I WifiNative-HAL: interface[0] = wlan0
07-27 08:54:21.230   862  1307 I WifiNative-HAL: interface[1] = p2p0
07-27 08:54:21.231  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.231  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.231   862  1307 D wifi    : setting scan oui 0x9a0bf310
07-27 08:54:21.231   862  1307 D WifiHAL : Sending mac address OUI
07-27 08:54:21.231   862  1307 E WifiHAL : failed to set scanning mac OUI; result = -95
07-27 08:54:21.232   862  1307 D WifiStateMachine: Setting OUI to DA-A1-19
07-27 08:54:21.232   862  1307 I WifiNative-HAL: startHal
07-27 08:54:21.232   862  1307 D wifi    : setting scan oui 0x9a0bf310
07-27 08:54:21.232   862  1307 D WifiHAL : Sending mac address OUI
07-27 08:54:21.232   862  1307 E WifiHAL : failed to set scanning mac OUI; result = -95
07-27 08:54:21.232  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.232  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.233  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.233  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.233  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.233  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.233  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.234  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.234  1873  2177 D WfdsMonitor: WFDS Monitor is created and started
07-27 08:54:21.234  1873  2177 D WfdsService: WiFi: Supplicant connection re-established
07-27 08:54:21.234  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.235  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.235  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.236  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.236  1873  5951 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
07-27 08:54:21.236  1909  1909 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
07-27 08:54:21.237  1873  5951 E CtrlSupplicant: Succeed to open control connection
07-27 08:54:21.237  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.237  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.237  1873  5951 E CtrlSupplicant: Succeed to open monitor connection
07-27 08:54:21.237  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.238  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.238  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.238  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.239  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.239  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.240  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.240  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.241  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.241  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.241  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-27 08:54:21.241 DNS addrs= 0.0.0.0, 0.0.0.0, 
07-27 08:54:21.242  1909  1909 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
07-27 08:54:21.242  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.242  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.242   862   862 D WifiHS20: hidePasspointNotification off =false
07-27 08:54:21.243  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.243  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.244   862   862 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:21.244   862   862 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:21.244   862   862 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
07-27 08:54:21.244  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.244  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.245  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.245  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.246  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.246  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.247  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.247  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.248  1873  5951 D WfdsMonitor: Supplicant connection established
07-27 08:54:21.248  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.248  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.249  1368  1368 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 08:54:21.249  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.249  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.249  1873  2177 D WfdsService: Connected to the supplicant for wfds
07-27 08:54:21.250  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.250  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.251   862  5950 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=-1336027968
07-27 08:54:21.251  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.251  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.251   862  5950 D wifi    : waitForHalEvents called, vm = 0xb487c280, obj = 0x901a5a, env = 0x9d8bdbe0
07-27 08:54:21.251   862  5950 E wifi    : getStaticLongField sWifiHalHandle 0x993c0b2c
07-27 08:54:21.252  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.252  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.252  5601  5601 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:21.253  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.253  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.253  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-27 08:54:21.254  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 08:54:21.254  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.254  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.254  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-27 08:54:21.254  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
07-27 08:54:21.254  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.254  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.255  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.255  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.255  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.255  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.256  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.256  2074  5927 D bt_hwcfg: hw_config_cback state=6
,07-27 08:54:21.257  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.257  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.258   862  1306 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:21.258  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.258  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.259  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.259  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.259  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-27 08:54:21.259  1368  1368 I [SystemUI]QuickSettingsHandler: Remote
07-27 08:54:21.259   862  1306 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:21.260   862  1306 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:54:21.260   275   915 D CommandListener: Setting iface cfg
07-27 08:54:21.260   275   915 D CommandListener: Trying to bring up p2p0
07-27 08:54:21.260  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.260  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.260   862  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-27 08:54:21.261   862  1306 D LGWifiP2pService: P2pEnablingState
07-27 08:54:21.261   862  1306 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:21.261   862  1306 D LGWifiP2pService: P2p socket connection successful
07-27 08:54:21.261   862  1306 D LGWifiP2pService: P2pEnabledState
07-27 08:54:21.261  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.261  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.262  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.263  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.263  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.264  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.264  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.264  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.264  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.265  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.265  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.266  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.266  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.267  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.267  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.267  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.267  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.267  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.268  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.268  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.269  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.269  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.270   862   862 D WifiScanningService: SCAN_AVAILABLE : 3
07-27 08:54:21.270   862   862 D RttService: SCAN_AVAILABLE : 3
07-27 08:54:21.270   862  1327 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:21.270   862  1327 I WifiNative-HAL: startHal
07-27 08:54:21.270  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.270  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.271   862  1328 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:21.272  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.272  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.273  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.273  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.273  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.273  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.273  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.273  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.274  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.274  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.275  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.275  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.275  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.275  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.276  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.276  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.277  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.277  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.278  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.278  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.279  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.279  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.280  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.280  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.281  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.281  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.281  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.281  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.281  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.281  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.282  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.282  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.283  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.283  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.283   862  1014 D BluetoothManagerService: Message: 20
07-27 08:54:21.283   862  1014 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b46dc7:true
07-27 08:54:21.283   862  1327 D wifi    : getting scan capabilities on interface[0] = 0x9a0bf310
07-27 08:54:21.283   862  1327 D WifiHAL : Creating message to get scan capablities; iface = 24
07-27 08:54:21.284   862  1327 D wifi    : failed to get capabilities : -95
07-27 08:54:21.284   862  1327 E WifiScanningService: could not get scan capabilities
07-27 08:54:21.284  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.284  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.285  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.285  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.286  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.286  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.287  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.287  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.287  1368  1368 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 08:54:21.288  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.288   862  1306 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
07-27 08:54:21.288  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.288   862  1306 D LGWifiP2pService: before postfix = G3s-1
07-27 08:54:21.288   862  1306 D WifiServerServiceExt: postfix byte check : 5
07-27 08:54:21.289   862  1306 D LGWifiP2pService: after postfix = G3s-1
07-27 08:54:21.289  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.289  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.290  1909  1909 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
07-27 08:54:21.290  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.290  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.290  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-27 08:54:21.29 DNS addrs= 0.0.0.0, 0.0.0.0, 
07-27 08:54:21.290  1909  1909 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
07-27 08:54:21.291  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-27 08:54:21.291  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.291  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.291  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 08:54:21.291  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-27 08:54:21.292  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.292  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.293  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
07-27 08:54:21.293  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-27 08:54:21.293  1368  1368 I [SystemUI]QuickSettingsHandler: Remote
07-27 08:54:21.293   862   862 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:21.293   862   862 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:21.293   862   862 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
07-27 08:54:21.294  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.294  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.295  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.295  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.294   862  1306 D WifiNative-HAL: p2pGetDeviceAddress
07-27 08:54:21.296   862  1306 D WifiNative-HAL: p2pGetDeviceAddress returning a2:39:f7:70:12:80
,07-27 08:54:21.296  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.296  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.297  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.297  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.297  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.298  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.298  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.298  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.298  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.299  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.299  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.299  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.299  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.299  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.300  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.300  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.300  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.300  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.301  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.301  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.301  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.301  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.302  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.302  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.302  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.302  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.303  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.303  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.303  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.303  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.304  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.304  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.304   862  1307 I WifiServerServiceExt: set CMD_ADD_DEFAULT_PROFILE
07-27 08:54:21.304  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.304  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.305  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.305  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.305  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.305  2074  5927 D bt_hwcfg: hw_config_cback state=6
,07-27 08:54:21.306  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.306  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.306  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.306  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.307  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.307  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.307  1873  1873 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
07-27 08:54:21.307  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.307  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.308  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.308  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.308  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.308  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.308  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.308  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.309  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.309  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.309  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.309  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.310  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.310  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.310  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.310  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.310  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.310  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.311  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.311  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.311  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.311  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.312  2074  2074 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-27 08:54:21.312  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.312  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.313  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.313  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.313  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.313  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.313  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.313  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.314  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.314  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.314   862  1306 D LGWifiP2pService: DeviceAddress: a2:39:f7:70:12:80
07-27 08:54:21.314  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4c
07-27 08:54:21.314  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.314  2074  2074 D LGBluetoothStateChangeReceiver: [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
07-27 08:54:21.315  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc4e
07-27 08:54:21.315  2074  5927 D bt_hwcfg: hw_config_cback state=6
07-27 08:54:21.316   862  1307 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
,07-27 08:54:21.321  1873  1873 D WfdsService: Update P2p Interface State: 3
07-27 08:54:21.349  5875  5875 E wpa_supplicant: nWIFIDualbandAPConnection: 1
,07-27 08:54:21.351   862  1307 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
,07-27 08:54:21.351   862  1291 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=5955 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
07-27 08:54:21.351  5875  5875 E wpa_supplicant: disconnect_rssi_lvl: -100
07-27 08:54:21.351   862  1306 D LGWifiP2pService: sending p2p persistent groups changed broadcast
07-27 08:54:21.353   862  1306 D LGWifiP2pService: sending p2p connection changed broadcast
07-27 08:54:21.354   862  1306 D LGWifiP2pService: InactiveState
07-27 08:54:21.354   862  1307 I WifiServerServiceExt: set CMD_SET_FRAMEWORK_AUTO_JOIN 0
07-27 08:54:21.355  5875  5875 E wpa_supplicant: wpa_supplicant_ctrl_iface_set_framework_auto_join: enable : 0
07-27 08:54:21.356   862  1306 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:21.356   862  1306 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:21.356   862  1306 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:21.356   862  1306 D LGWifiP2pService: InactiveState{ when=-2ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:21.357   862  1306 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:21.357   862  1306 D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:21.357   862   862 E WifiServerServiceExt: No p2p device connected
07-27 08:54:21.358   862  1307 I WifiServerServiceExt: set CMD_UPDATE_DEFAULT_PROFILE
07-27 08:54:21.375   305   305 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 307us total 22.396ms
07-27 08:54:21.376  5931  5931 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-27 08:54:21.380  5875  5875 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
07-27 08:54:21.382  5875  5875 I wpa_supplicant: [LGE_PATCH]scan interval[0] = 2 sec.
07-27 08:54:21.383  1873  5951 D WfdsMonitor: Event [CTRL-EVENT-SCAN-RESULTS ]
07-27 08:54:21.384   862  1306 D LGWifiP2pService: InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:21.384   862  1306 D LGWifiP2pService: P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:21.384   862  1306 D LGWifiP2pService: DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:21.387  1909  1909 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
07-27 08:54:21.388  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-27 08:54:21.388 DNS addrs= 0.0.0.0, 0.0.0.0, 
07-27 08:54:21.388  1909  1909 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
07-27 08:54:21.388   862   862 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:21.388   862   862 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:21.388   862   862 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,07-27 08:54:21.394  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.p2p.STATE_CHANGED at null
07-27 08:54:21.395  1873  1873 D WfdsService: WifiP2pState is changed : true
07-27 08:54:21.395  1873  1873 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
07-27 08:54:21.395  1873  2177 D WfdsService: Receive the WFDS_ENABLE Method
07-27 08:54:21.395  1873  2177 D WfdsService: Set the WFDS Monitor: true
07-27 08:54:21.395  1873  2177 D WfdsService: Connected to the supplicant for wfds
07-27 08:54:21.396  1873  2177 D WfdsJNI : doCommand: WFDS_SET TRUE
07-27 08:54:21.402  1368  1368 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 08:54:21.404   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 291us total 26.626ms
07-27 08:54:21.406  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-27 08:54:21.407  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 08:54:21.407  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-27 08:54:21.407  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
07-27 08:54:21.407  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-27 08:54:21.407  1368  1368 I [SystemUI]QuickSettingsHandler: Remote
07-27 08:54:21.409  5875  5875 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
07-27 08:54:21.409  5875  5875 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
07-27 08:54:21.410  1873  1873 D WfdsService: isConnected: false
07-27 08:54:21.411  1873  2177 D WfdsJNI : doCommand: WFDS_GET_MAC_ADDRESS
07-27 08:54:21.411  5875  5875 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
,07-27 08:54:21.411   862  1306 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:21.411   862  1306 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:21.411   862  1306 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:21.411   862  1306 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:21.411   862  1306 D LGWifiP2pService: P2pEnabledState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:21.411   862  1306 D LGWifiP2pService: DefaultState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:21.411  1873  1873 D WfdsService: GroupInfoAvailable: mGroupInfo is null
07-27 08:54:21.412  1873  2177 D WfdsJNI : doCommand: WFDS_CLEAR_PD_INFO
07-27 08:54:21.412  5875  5875 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = CLEAR_PD_INFO
07-27 08:54:21.412  1873  2177 D WfdsJNI : wfds_send_command: [WFDS_CLEAR_PD_INFO] failed
07-27 08:54:21.413  1873  2177 D WfdsJNI : doCommand: IFNAME=wlan0 GET_CAPABILITY channels
07-27 08:54:21.413  1873  2177 D WfdsService: selectPreferredScanChannel [6]
07-27 08:54:21.413  1873  2177 D WfdsService: STATE : WfdsEnabledState - enter: this device mac a2:39:f7:70:12:80
07-27 08:54:21.414  1873  2177 W WfdsService: DefaultState - msg [9441285] is not handled
07-27 08:54:21.415  2074  5927 I bt_hwcfg: bt vendor lib: set UART baud 115200
07-27 08:54:21.415  2074  5927 D bt_hwcfg: Settlement delay -- 100 ms
07-27 08:54:21.415  2074  5927 I bt_hwcfg: Setting fw settlement delay to 100 
07-27 08:54:21.415   862   862 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 08:54:21.416   862   862 D WifiServerServiceExt: setSupplicantStateSCANNING
07-27 08:54:21.425   862   862 D LocSvc_java: onReceive
07-27 08:54:21.427   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 21.886ms
07-27 08:54:21.429   862   862 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 08:54:21.429   862   862 D WifiServerServiceExt: setSupplicantStateSCANNING
07-27 08:54:21.436  5885  5885 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
07-27 08:54:21.436  5885  5885 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
07-27 08:54:21.436  5885  5885 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
07-27 08:54:21.436  5885  5885 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,07-27 08:54:21.441  5885  5885 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
07-27 08:54:21.442  1787  1787 D GONS    : GONS isTestMode: false Country: 
07-27 08:54:21.468  5885  5885 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
07-27 08:54:21.468  5885  5885 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
07-27 08:54:21.468  5885  5885 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
07-27 08:54:21.468  5885  5885 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
07-27 08:54:21.468  5885  5885 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
07-27 08:54:21.469  5885  5885 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
07-27 08:54:21.469  5885  5885 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,07-27 08:54:21.472  5885  5885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
07-27 08:54:21.475  5885  5885 D WiFiOffLoadUpdatePriority: remove : truetruetrue
07-27 08:54:21.477  5955  5955 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-27 08:54:21.504  5885  5885 D WiFiOffLoadUpdatePriority: remove1
07-27 08:54:21.504  5885  5885 V WiFiOffLoadSharedPrefsUtils: save remove
,07-27 08:54:21.518  5885  5885 D WiFiOffLoadBroadcast: mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
07-27 08:54:21.518  5885  5885 D WiFiOffLoadBroadcast: S: false, R: false
,07-27 08:54:21.520  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc45
07-27 08:54:21.520  2074  5927 D bt_hwcfg: hw_config_cback state=2
07-27 08:54:21.521  5955  5955 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information EasySettings
07-27 08:54:21.522  5885  5885 D WiFiOffLoadUpdatePriority: saved SSID: "NG700"
07-27 08:54:21.522  5885  5885 D WiFiOffLoadUpdatePriority: connected SSID: null
07-27 08:54:21.522  5885  5885 D WiFiOffLoadUpdatePriority: private wpa: "NG700" 300
07-27 08:54:21.524   862  1946 D WifiServiceImplEx: addOrUpdateNetwork pid=5885, uid=1000, packageName=android.uid.system:1000
07-27 08:54:21.525   862  1946 E addOrUpdateNetwork:  uid = 1000 SSID "NG700" nid=0
07-27 08:54:21.525  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc18
07-27 08:54:21.525  2074  5927 D bt_hwcfg: hw_config_cback state=7
07-27 08:54:21.525  2074  5927 I bt_hwcfg: bt vendor lib: set UART baud 4000000
07-27 08:54:21.526  2074  5927 I bt_hwcfg: Setting local bd addr to F8:95:C7:87:85:54
07-27 08:54:21.527   862  1307 E WifiConfigStore:  key="NG700"WPA_PSK netId=0 uid=0/1000
07-27 08:54:21.533  1757  1757 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-27 08:54:21.545  1757  1757 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-27 08:54:21.552  2074  5927 D bt_hwcfg: hw_config_cback opcode:0xfc01
07-27 08:54:21.552  2074  5927 D bt_hwcfg: hw_config_cback state=8
07-27 08:54:21.552  2074  5927 I bt_hwcfg: vendor lib fwcfg completed
07-27 08:54:21.552  2074  5927 I bt-btif : HC preload_cb 0 [0:SUCCESS 1:FAIL]
07-27 08:54:21.552  2074  5925 I bt-btu  : btu_task received preload complete event
,07-27 08:54:21.558  2074  5925 I         : BTE_InitTraceLevels -- TRC_HCI,2
07-27 08:54:21.558  2074  5925 I         : BTE_InitTraceLevels -- TRC_L2CAP,2
07-27 08:54:21.558  2074  5925 I         : BTE_InitTraceLevels -- TRC_RFCOMM,2
07-27 08:54:21.558  2074  5925 I         : BTE_InitTraceLevels -- TRC_OBEX,2
07-27 08:54:21.558  2074  5925 I         : BTE_InitTraceLevels -- TRC_AVCT,2
07-27 08:54:21.558  2074  5925 I         : BTE_InitTraceLevels -- TRC_AVDT,2
07-27 08:54:21.558  2074  5925 I         : BTE_InitTraceLevels -- TRC_AVRC,2
07-27 08:54:21.558  2074  5925 I         : BTE_InitTraceLevels -- TRC_AVDT_SCB,2
07-27 08:54:21.558  2074  5925 I         : BTE_InitTraceLevels -- TRC_A2D,2
07-27 08:54:21.558  2074  5925 I         : BTE_InitTraceLevels -- TRC_BNEP,2
07-27 08:54:21.558  2074  5925 I         : BTE_InitTraceLevels -- TRC_BTM,2
07-27 08:54:21.558  2074  5925 I         : BTE_InitTraceLevels -- TRC_GAP,2
07-27 08:54:21.558  2074  5925 I         : BTE_InitTraceLevels -- TRC_PAN,2
07-27 08:54:21.558  2074  5925 I         : BTE_InitTraceLevels -- TRC_SAP,2
07-27 08:54:21.558  2074  5925 I         : BTE_InitTraceLevels -- TRC_SDP,2
07-27 08:54:21.558  2074  5925 I         : BTE_InitTraceLevels -- TRC_GATT,2
07-27 08:54:21.558  2074  5925 I         : BTE_InitTraceLevels -- TRC_SMP,2
07-27 08:54:21.558  2074  5925 I         : BTE_InitTraceLevels -- TRC_BTAPP,3
07-27 08:54:21.558  2074  5925 I         : BTE_InitTraceLevels -- TRC_BTIF,3
07-27 08:54:21.558  2074  5925 I         : BTE_InitTraceLevels -- TRC_PROTOCOL,0
,07-27 08:54:21.589  5885  5885 D WiFiOffLoadUpdatePriority:  ssid "NG700" prio 300
07-27 08:54:21.589  5885  5885 D WiFiOffLoadUpdatePriority: configuration updated: 0
07-27 08:54:21.590   862  1307 I WifiServerServiceExt: set CMD_UPDATE_DEFAULT_PROFILE
,07-27 08:54:21.600  5885  5885 D WiFiOffLoadUpdatePriority: configuration saved: true
07-27 08:54:21.603  5931  5931 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,07-27 08:54:21.604   862  2370 I ActivityManager: Killing 5552:com.google.android.apps.plus/u0a86 (adj 15): empty #11
07-27 08:54:21.699  2074  5925 E bt-btif : bta_dm_ctrl_features_rd_cmpl_cback Ctrl BLE feature read failed: status :1
,07-27 08:54:21.701  2074  5977 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
07-27 08:54:21.701  2074  2256 E bt-btif : warning : media task started media_task_refcnt 1 
07-27 08:54:21.702  2074  5977 D BT_PROF_AUDIO: created moving average (N=100)
07-27 08:54:21.702  2074  5977 D BT_PROF_AUDIO: reset rate average
07-27 08:54:21.702  2074  5977 W bt-btif : overflow 0, enter 0, exit 0
07-27 08:54:21.706  2074  2256 E bt-btif : Calling BTA_HhEnable
07-27 08:54:21.707  2074  2256 E bt-btif : btif_storage_get_adapter_property service_mask:0x1201c8
07-27 08:54:21.707  2074  2256 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
07-27 08:54:21.707  2074  2256 D BluetoothAdapterProperties: Address is:F8:95:C7:87:85:54
07-27 08:54:21.708  2074  5925 W bt-smp  : Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
07-27 08:54:21.708  2074  5925 W bt-smp  : Plain text(LSB ~ MSB) = c7 21 50 00 00 00 00 00 00 00 00 00 00 00 00 00 
07-27 08:54:21.708  2074  5925 W bt-smp  : Encrypted text(LSB ~ MSB) = 27 9b 49 e1 28 5b 68 6d a1 51 b3 cf b0 e3 b4 dd 
07-27 08:54:21.708  2074  5925 W bt-btm  : Stopping oneshot timer
07-27 08:54:21.708  2074  2256 D BluetoothAdapterProperties: Name is: G3s-1
07-27 08:54:21.708   862   862 D BluetoothManagerService: Bluetooth Adapter name changed to G3s-1
07-27 08:54:21.709   862   862 D BluetoothManagerService: Stored Bluetooth name: G3s-1
07-27 08:54:21.710   862  2008 W libprocessgroup: failed to open /acct/uid_10086/pid_5552/cgroup.procs: No such file or directory
07-27 08:54:21.710  2074  2256 D BluetoothAdapterProperties: Scan Mode:20
07-27 08:54:21.711  2074  2256 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-27 08:54:21.713  2074  2256 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
07-27 08:54:21.713  2074  2256 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
07-27 08:54:21.713  2074  2256 E bt-btif : btif_sock_init: !radio_req && !rfc_init
07-27 08:54:21.713  2074  2256 I bt-btif : BTA_JvEnable
07-27 08:54:21.713  2074  2256 E bt-btif : btsock_vendor_hci_init: !vhci_init
07-27 08:54:21.713  2074  2256 D bt-btif : btsock_ctrl_hci_init(L191): poll handle:6
07-27 08:54:21.714  2074  2256 D bt-btif : init_hci_slots(L136): in
07-27 08:54:21.714  2074  2256 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
07-27 08:54:21.715  2074  2256 D IOP_DB_BT: db_open: db_open : handle 2691135452l, read 11046 bytes onto local cache
07-27 08:54:21.715  2074  2256 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
07-27 08:54:21.715  2074  2256 D IOP_DB_BT: db_query: result 1
07-27 08:54:21.715  2074  2256 I         : iop_db_open: iop_db_open status 0
07-27 08:54:21.715  2074  2256 E bt-btif : btif_sock_init, radio_req:0, rfc_init:1, vhci_init:1
07-27 08:54:21.715  2074  2256 D bt-btif : btsock_ctrl_hci_init(L191): poll handle:6
07-27 08:54:21.716  2074  5925 I bt-btif : bta_pan_co_init
07-27 08:54:21.717  2074  2256 D bte_conf: Device ID record 1 : primary
07-27 08:54:21.717  2074  2256 D bte_conf:   vendorId            = 00c4
07-27 08:54:21.717  2074  2256 D bte_conf:   vendorIdSource      = 0001
07-27 08:54:21.717  2074  2256 D bte_conf:   product             = 13a1
07-27 08:54:21.717  2074  2256 D bte_conf:   version             = 1000
07-27 08:54:21.717  2074  2256 D bte_conf:   clientExecutableURL = 
07-27 08:54:21.717  2074  2256 D bte_conf:   serviceDescription  = 
07-27 08:54:21.717  2074  2256 D bte_conf:   documentationURL    = 
07-27 08:54:21.717  2074  2256 D bte_conf: bte_load_did_conf no section named DID2.
07-27 08:54:21.718  2074  2256 I bt-btif : HAL bt_hal_cbacks->adapter_state_changed_cb
07-27 08:54:21.718  2074  2237 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-27 08:54:21.719  2074  2237 D BluetoothAdapterProperties: ScanMode =  20
07-27 08:54:21.719  2074  2237 D BluetoothAdapterProperties: State =  11
07-27 08:54:21.719  2074  2237 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
07-27 08:54:21.719  5716  5716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 08:54:21.719  2074  2237 D BluetoothAdapterProperties: Setting state to 12
07-27 08:54:21.719  2074  2237 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-27 08:54:21.719  2074  2237 D BluetoothAdapterService(340792543): updateAdapterState() - Broadcasting state to 1 receivers.
07-27 08:54:21.719   862  1014 D BluetoothManagerService: Message: 60
07-27 08:54:21.719   862  1014 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
07-27 08:54:21.719  2074  2237 I BluetoothAdapterState: Entering On State
07-27 08:54:21.720  2074  2237 I BluetoothAdapterState: Entering On State from state = 11
07-27 08:54:21.720   862  1014 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 6 receivers.
07-27 08:54:21.720  2074  2256 E bt-btif : btif_hf_upstreams_evt: wrong handle = 8240 
07-27 08:54:21.720  2074  2256 I bt-btif : HAL bt_op_callbacks->opc_state_cb
07-27 08:54:21.720  2074  2256 D BluetoothOPPServiceJni: opc_state_cb(L140):  opc_state_cb state:0
07-27 08:54:21.720  2074  2256 D OppService: onOpcStateChange()
07-27 08:54:21.720  2074  2074 D OppService: Recieved MESSAGE_OPC_ENABLE
07-27 08:54:21.721  2074  2237 D BluetoothAdapterService(340792543): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@20c384ad
07-27 08:54:21.721  1787  2392 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 08:54:21.721  2074  2074 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-27 08:54:21.721  2074  2256 I bt-btif : HAL bt_op_callba,cks->ops_state_cb
07-27 08:54:21.721  2074  2256 D BluetoothOPPServiceJni: ops_state_cb(L223):  ops_state_cb state:0
07-27 08:54:21.721  2074  2256 D OppService: onOpsStateChange() :0
07-27 08:54:21.721  2074  2256 I bt-btif : HAL bt_fts_callbacks->operation_cmpl_cb
07-27 08:54:21.721  2074  2256 D BluetoothFTPServiceJni: operation_cmpl_callback(L192):  oper:3 status:0
07-27 08:54:21.721  2074  2237 D BluetoothAdapterService(340792543): isQuetModeEnabled() - Enabled = false
07-27 08:54:21.721  2074  2256 I BluetoothFTPService: onFtpServerEnabled: /storage
07-27 08:54:21.722  2074  2237 D BluetoothAdapterService(340792543): autoConnect() - Initiate auto connection on BT on...
07-27 08:54:21.722  2074  2237 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
07-27 08:54:21.722   862  1014 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 08:54:21.722  2074  2256 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-27 08:54:21.722  2074  2256 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
07-27 08:54:21.723  2074  2237 D LGBluetoothServiceAdapter: [BTUI] OnState
07-27 08:54:21.723  2074  2074 D OppService: Recieved MESSAGE_OPS_ENABLE
07-27 08:54:21.723  2074  2237 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3s-1
07-27 08:54:21.724  1787  1808 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 08:54:21.724  1787  1814 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 08:54:21.725  2074  2091 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-27 08:54:21.725   862  1014 D BluetoothA2dp: onBluetoothStateChange: up=true
07-27 08:54:21.735  2074  5927 D bt_h4   : vendor lib postload completed
,07-27 08:54:21.748  2074  2074 V BluetoothOppNotification: new notify threadi!
,07-27 08:54:21.748  2074  2074 V BluetoothOppNotification: send delay message
07-27 08:54:21.751  2074  5983 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
07-27 08:54:21.752  2074  5983 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ba4ccd8 on behalf of 
07-27 08:54:21.754  2074  5983 V BluetoothOppNotification: mUpdateCompleteNotification = true
07-27 08:54:21.755  2074  5983 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
07-27 08:54:21.756  2074  5983 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@12a53831 on behalf of 
07-27 08:54:21.757  2074  5983 V BluetoothOppNotification: outbound: succ-0  fail-0
07-27 08:54:21.757  2074  5983 I NotificationManager: com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
07-27 08:54:21.758  2074  5983 V BluetoothOppNotification: outbound notification was removed.
07-27 08:54:21.758  2074  5983 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
07-27 08:54:21.760  2074  5983 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2e5e0b16 on behalf of 
07-27 08:54:21.760  2074  5983 V BluetoothOppNotification: inbound: succ-0  fail-0
,07-27 08:54:21.765   862   881 I ActivityManager: Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=5984 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
07-27 08:54:21.767   862  1014 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
07-27 08:54:21.767  2074  2256 D BluetoothAdapterProperties: Scan Mode:21
07-27 08:54:21.767   862  1014 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
07-27 08:54:21.767  2074  2256 I bt-btif : HAL bt_hal_cbacks->adapter_properties_cb
07-27 08:54:21.767  2074  2256 D BluetoothAdapterProperties: Discoverable Timeout:120
07-27 08:54:21.767  2074  2237 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3s-1
07-27 08:54:21.794  2074  2237 D BluetoothAdapterService(340792543): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@20c384ad
07-27 08:54:21.794  2074  2237 D BluetoothAdapterService(340792543): isQuetModeEnabled() - Enabled = false
07-27 08:54:21.794  2074  2237 D BluetoothAdapterService(340792543): autoConnect() - Initiate auto connection on BT on...
07-27 08:54:21.794  2074  2237 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
07-27 08:54:21.794  1873  1873 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,07-27 08:54:21.798  2074  2090 D BluetoothAdapterService(340792543): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@20c384ad
07-27 08:54:21.798   862   862 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
07-27 08:54:21.798   862  1014 D BluetoothManagerService: Message: 40
07-27 08:54:21.798   862  1014 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
07-27 08:54:21.800  2074  2074 D BluetoothAdapterService(340792543): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@20c384ad
07-27 08:54:21.800  2074  2090 D BluetoothAdapterService(340792543): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@20c384ad
07-27 08:54:21.800  5716  5716 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
07-27 08:54:21.802  2074  2091 D BluetoothAdapterService(340792543): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@20c384ad
07-27 08:54:21.804  2074  2090 D BluetoothAdapterService(340792543): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@20c384ad
07-27 08:54:21.806  2074  2074 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-27 08:54:21.807  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.bluetooth.adapter.action.STATE_CHANGED at null
07-27 08:54:21.807  2074  2074 D BluetoothMapService: STATE_ON
07-27 08:54:21.807  1368  1368 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,07-27 08:54:21.811  5716  5716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 08:54:21.811  5716  5716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:54:21.811  5716  5716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 08:54:21.811  5716  5716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 08:54:21.811  5716  5716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 08:54:21.811  5716  5716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 08:54:21.811  5716  5716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 08:54:21.811  5716  5716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 08:54:21.813  2074  2090 D BluetoothAdapterService(340792543): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@20c384ad
07-27 08:54:21.814  5716  5716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-27 08:54:21.812  2074  5983 I NotificationManager: com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
07-27 08:54:21.817  2074  5983 V BluetoothOppNotification: inbound notification was removed.
07-27 08:54:21.817  2074  5983 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
07-27 08:54:21.818  2074  5983 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@e6f9c97 on behalf of 
,07-27 08:54:21.832  5885  5885 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,07-27 08:54:21.842  1873  2054 D LGBluetoothAPIService: Message: 1
07-27 08:54:21.842  1873  2054 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
,07-27 08:54:21.855  2074  2074 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@145014df
07-27 08:54:21.858  2074  2074 V BluetoothPbapService: Pbap Service onCreate
07-27 08:54:21.858  2074  2074 V BluetoothPbapService: Starting PBAP service
07-27 08:54:21.858  2074  2090 D BluetoothAdapterService(340792543): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@20c384ad
07-27 08:54:21.860  5885  5885 D LocalBluetoothProfileManager: Adding local A2DP profile
,07-27 08:54:21.865  2074  2074 D BluetoothAdapterService(340792543): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@20c384ad
07-27 08:54:21.866  2074  2074 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
07-27 08:54:21.868  2074  2074 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
07-27 08:54:21.868   862  1014 D BluetoothManagerService: Message: 30
07-27 08:54:21.870  1873  2054 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
07-27 08:54:21.871  5885  5885 D LocalBluetoothProfileManager: Adding local HEADSET profile
07-27 08:54:21.873  2074  2074 V BluetoothPbapService: state: 12
07-27 08:54:21.874  2074  2074 V BluetoothMapService: Handler(): got msg=1
07-27 08:54:21.874   862  1014 D BluetoothManagerService: Message: 30
,07-27 08:54:21.875  2074  2074 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
07-27 08:54:21.877  2074  2074 V BluetoothPbapReceiver: PbapReceiver onReceive 
07-27 08:54:21.877  2074  2074 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
07-27 08:54:21.877  2074  2074 V BluetoothPbapReceiver: ***********state = 12
07-27 08:54:21.878  2074  6003 D BluetoothMapMasInstance: MAS initSocket()
07-27 08:54:21.878  2074  2074 V BluetoothPbapService: Handler(): got msg=1
07-27 08:54:21.879  2074  6003 D BluetoothMapMasInstance:   masId = 00
07-27 08:54:21.879  2074  6003 D BluetoothMapMasInstance:   msgTypes = 0e
07-27 08:54:21.879  2074  6003 D BluetoothMapMasInstance:   masName = SMS/MMS
07-27 08:54:21.879  2074  6003 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
07-27 08:54:21.879  2074  2074 V BluetoothPbapService: Pbap Service startRfcommSocketListener
07-27 08:54:21.881   862  1923 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 08:54:21.883  2074  6004 V BluetoothPbapService: Pbap Service initSocket
07-27 08:54:21.883   862  2008 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-27 08:54:21.885  2074  2074 D LGBluetoothAPIServer: [BTUI] onCreate()
07-27 08:54:21.886  2074  2074 D LGBluetoothAPIServer: [BTUI] onBind()
07-27 08:54:21.887  1873  1873 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
07-27 08:54:21.888  1873  2054 D LGBluetoothAPIService: Message: 100
07-27 08:54:21.888  1873  2054 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
07-27 08:54:21.889   862  1014 D BluetoothManagerService: Message: 30
,07-27 08:54:21.892  2074  6003 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 08:54:21.893  2074  6003 I bt-btif : BTA_JvCreateRecordByUser
07-27 08:54:21.894  2074  5925 I bt-btif : BTA_JvRfcommStartServer
07-27 08:54:21.894  2074  6003 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=83 mFd=0
07-27 08:54:21.894  2074  6003 V BluetoothMapMasInstance: Succeed to create listening socket 
07-27 08:54:21.895  2074  6003 D BluetoothMapMasInstance: Accepting socket connection...
07-27 08:54:21.895  2074  6004 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 08:54:21.896  2074  6004 I bt-btif : BTA_JvCreateRecordByUser
07-27 08:54:21.896  2074  5925 I bt-btif : BTA_JvRfcommStartServer
07-27 08:54:21.897  2074  6004 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=85 mFd=83
07-27 08:54:21.897  2074  6004 V BluetoothPbapService: Succeed to create listening socket 
07-27 08:54:21.897   862  1014 D BluetoothManagerService: Message: 30
07-27 08:54:21.897  2074  6004 V BluetoothPbapService: Accepting socket connection...
07-27 08:54:21.900  5885  5885 D LocalBluetoothProfileManager: Adding local MAP profile
07-27 08:54:21.915  5885  5885 D BluetoothMap: Create BluetoothMap proxy object
,07-27 08:54:21.916   862  1014 D BluetoothManagerService: Message: 30
07-27 08:54:21.922   862  1014 D BluetoothManagerService: Message: 30
07-27 08:54:21.926  5885  5885 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
07-27 08:54:21.926  2074  2074 V BluetoothPbapService: Pbap Service onBind
07-27 08:54:21.935  5885  5885 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,07-27 08:54:21.939  5885  5885 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
07-27 08:54:21.948  5885  5885 D DockEventReceiver: finishStartingService: stopping service
,07-27 08:54:21.951  5885  5885 D BluetoothA2dp: Proxy object connected
07-27 08:54:21.952  5885  5885 D A2dpProfile: Bluetooth service connected
07-27 08:54:21.955  2074  2091 D BluetoothAdapterService(340792543): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@20c384ad
07-27 08:54:21.961  5885  5885 D BluetoothHeadset: Proxy object connected
07-27 08:54:21.962  5885  5885 D HeadsetProfile: Bluetooth service connected
07-27 08:54:21.964  2074  5993 D BluetoothAdapterService(340792543): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@20c384ad
07-27 08:54:21.965  5885  5885 D BluetoothInputDevice: Proxy object connected
07-27 08:54:21.966  5885  5885 D HidProfile: Bluetooth service connected
07-27 08:54:21.967  2074  2090 D BluetoothAdapterService(340792543): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@20c384ad
,07-27 08:54:21.968  5885  5885 D BluetoothPan: BluetoothPAN Proxy object connected
,07-27 08:54:21.969  5885  5885 D PanProfile: Bluetooth service connected
07-27 08:54:21.971  2074  2091 D BluetoothAdapterService(340792543): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@20c384ad
07-27 08:54:21.972  5885  5885 D BluetoothMap: Proxy object connected
07-27 08:54:21.973  5885  5885 D MapProfile: Bluetooth service connected
07-27 08:54:21.973  5885  5885 D BluetoothMap: getConnectedDevices()
07-27 08:54:21.974  2074  5993 D BluetoothAdapterService(340792543): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@20c384ad
07-27 08:54:21.975  2074  2091 V BluetoothMapService: getConnectedDevices()
07-27 08:54:21.976  5885  5885 D BluetoothPbap: Proxy object connected
07-27 08:54:21.977  5885  5885 D PbapServerProfile: Bluetooth service connected
07-27 08:54:21.980  5885  5885 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,07-27 08:54:21.986  5885  5885 D BluetoothPermissionRequest: onReceive
07-27 08:54:21.991  5885  5885 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
07-27 08:54:21.992  5885  5885 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
07-27 08:54:21.997  2074  2074 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,07-27 08:54:22.005  2074  2074 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
07-27 08:54:22.007  5984  5984 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
07-27 08:54:22.008  5984  5984 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-27 08:54:22.013  2074  2074 V BluetoothSapReceiver: [BTUI] checkServiceStart
07-27 08:54:22.015  5984  5984 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
07-27 08:54:22.015  2074  2074 D LGBluetoothStateChangeReceiver: [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
,07-27 08:54:22.018  5984  5984 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
07-27 08:54:22.024  1757  1757 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
07-27 08:54:22.025  5885  5885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 08:54:22.032  5984  6014 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
07-27 08:54:22.033  1757  6015 D EasyUnlockInitService: Handling intent for initializer IntentService.
07-27 08:54:22.035  5984  6014 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-27 08:54:22.035  1757  1757 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-27 08:54:22.041  5885  5885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 08:54:22.047  5984  6013 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
07-27 08:54:22.052  5931  5931 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,07-27 08:54:22.057  5931  5931 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
07-27 08:54:22.057  5931  5931 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
07-27 08:54:22.092   862  2370 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6019 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,07-27 08:54:22.144  5349  5475 D dur     : Opening database auth.proximity.permit_store...
,07-27 08:54:22.149  1757  6015 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-27 08:54:22.195  6019  6019 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-27 08:54:22.283   862  1014 D BluetoothManagerService: Message: 20
07-27 08:54:22.283   862  1014 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1e8722a2:true
,07-27 08:54:22.290  2074  2090 D BluetoothAdapterService(340792543): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@20c384ad
07-27 08:54:22.291  2074  2091 D BluetoothAdapterService(340792543): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@20c384ad
07-27 08:54:22.362   862   881 I ActivityManager: Process com.google.android.talk (pid 5601) has died
,07-27 08:54:22.369  5885  5885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 08:54:22.374  5885  5885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 08:54:22.409  5579  5579 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-27 08:54:22.409  5579  5579 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,07-27 08:54:22.424  5579  5579 V [BNRBootReceiver]: Boot Receiver Return
,07-27 08:54:22.427  5885  5885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-27 08:54:22.431  5885  5885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 08:54:22.455  5885  5885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,07-27 08:54:22.459  5885  5885 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
07-27 08:54:22.515   275   908 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
,07-27 08:54:22.516  5875  5875 I wpa_supplicant: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2447 MHz)
,07-27 08:54:22.540   862  2204 I ActivityManager: Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6045 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-27 08:54:22.558   862   862 D LocSvc_java: onReceive
,07-27 08:54:22.561   862   862 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:22.562   862   862 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:22.562   862   862 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-27 08:54:22.565  6019  6019 V LGMDMManager: Create singleton instance
07-27 08:54:22.565   862   862 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 08:54:22.565   862   862 D WifiServerServiceExt: setSupplicantStateASSOCIATING
07-27 08:54:22.566  1368  1368 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 08:54:22.568  1909  1909 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
07-27 08:54:22.569  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-27 08:54:22.569  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 08:54:22.569  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-27 08:54:22.569  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
07-27 08:54:22.569  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-27 08:54:22.569  1368  1368 I [SystemUI]QuickSettingsHandler: Remote
07-27 08:54:22.570  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-27 08:54:22.57 DNS addrs= 0.0.0.0, 0.0.0.0, 
07-27 08:54:22.570  1909  1909 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
,07-27 08:54:22.605   275   908 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
07-27 08:54:22.605   275   908 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
07-27 08:54:22.606   275   908 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
07-27 08:54:22.606  5875  5875 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
07-27 08:54:22.619  1368  1368 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,07-27 08:54:22.620   862   862 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 08:54:22.620   862   862 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
07-27 08:54:22.620   862   862 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:22.620   862   862 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:22.620   862   862 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
07-27 08:54:22.621  1909  1909 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
07-27 08:54:22.623  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-27 08:54:22.623 DNS addrs= 0.0.0.0, 0.0.0.0, 
07-27 08:54:22.623  1909  1909 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
07-27 08:54:22.625  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-27 08:54:22.625  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 08:54:22.625  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-27 08:54:22.625  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
07-27 08:54:22.625  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-27 08:54:22.625  1368  1368 I [SystemUI]QuickSettingsHandler: Remote
07-27 08:54:22.625  1368  1368 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 08:54:22.630  1909  1909 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
07-27 08:54:22.631  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-27 08:54:22.631 DNS addrs= 0.0.0.0, 0.0.0.0, 
07-27 08:54:22.631  1909  1909 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
07-27 08:54:22.632   862   862 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:22.633   862   862 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 08:54:22.633   862   862 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
07-27 08:54:22.637  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-27 08:54:22.637  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 08:54:22.637  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-27 08:54:22.637  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
07-27 08:54:22.637  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-27 08:54:22.637  1368  1368 I [SystemUI]QuickSettingsHandler: Remote
07-27 08:54:22.646  5875  5875 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-27 08:54:22.646  5875  5875 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
07-27 08:54:22.648   275   908 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
07-27 08:54:22.656   862  1307 I WifiServiceExtension: setVHTCapabilityType  : false
,07-27 08:54:22.677   862  1307 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
07-27 08:54:22.677   862  1307 I WifiServerServiceExt: setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,07-27 08:54:22.681   862  1307 I WifiServiceExtension: setSecurityType  : 2
07-27 08:54:22.681  6045  6045 D UEI.SmartControl: Quickset Services start...
07-27 08:54:22.692  1909  1909 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,07-27 08:54:22.692   862   862 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:22.693  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-27 08:54:22.693 DNS addrs= 0.0.0.0, 0.0.0.0, 
07-27 08:54:22.693  1909  1909 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
07-27 08:54:22.693  1368  1368 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 08:54:22.694  6045  6045 I UEI.SmartControl: Manufacture = LGE
07-27 08:54:22.695   862   862 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:22.695   862   862 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-27 08:54:22.696  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-27 08:54:22.696  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 08:54:22.696  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-27 08:54:22.696  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
07-27 08:54:22.697  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-27 08:54:22.697  1368  1368 I [SystemUI]QuickSettingsHandler: Remote
07-27 08:54:22.697  1368  1368 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 08:54:22.698  1909  1909 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
07-27 08:54:22.699  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-27 08:54:22.699 DNS addrs= 0.0.0.0, 0.0.0.0, 
07-27 08:54:22.700  1909  1909 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
07-27 08:54:22.700   862   862 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:22.700   862   862 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:22.700   862   862 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
07-27 08:54:22.701  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-27 08:54:22.701  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 08:54:22.702  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-27 08:54:22.702  1368  1368 I [SystemUI]QuickSettingsHandler: Go,t action android.net.wifi.STATE_CHANGE at null
07-27 08:54:22.702  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-27 08:54:22.702  1368  1368 I [SystemUI]QuickSettingsHandler: Remote
07-27 08:54:22.704  6045  6045 D UEI.SmartControl: File observer start...
07-27 08:54:22.707  6045  6045 E UEI.SmartControl: IR Port is disabled: false
,07-27 08:54:22.710  6045  6045 D UEI.SmartControl: Starting file observer...
07-27 08:54:22.710  6045  6045 D UEI.SmartControl: Extracting JNI libs...
07-27 08:54:22.712  6045  6045 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
07-27 08:54:22.716  6019  6019 I AudioManager: getMode name:com.lge.qremote
07-27 08:54:22.725   295   356 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 08:54:22.730   862  6068 D WifiExtManager: WifiExtManager service = com.lge.wifi.impl.IWifiExtManager$Stub$Proxy@1a1bc420
07-27 08:54:22.731   862  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
07-27 08:54:22.732   862  1313 D ConnectivityService: Got NetworkAgent Messenger
07-27 08:54:22.734   862  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
07-27 08:54:22.735   862  1313 D ConnectivityService: NetworkAgent connected
07-27 08:54:22.738  5885  5885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,07-27 08:54:22.744  5885  5885 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
07-27 08:54:22.746  5885  5885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-27 08:54:22.750  1873  1890 D WifiServiceExtension: isInternetCheckAvailable return false
07-27 08:54:22.750   862  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-27 08:54:22.754  5885  5885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 08:54:22.762   862  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-27 08:54:22.768  5885  5885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 08:54:22.772   275   908 I Netd    : M: Get netlink event, ifname: wlan0 action: 9
07-27 08:54:22.773   862  1012 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:22.773   862  1012 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:54:22.774   862  1307 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:22.774   862  1307 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-27 08:54:22.775   275   915 D CommandListener: Setting iface cfg
07-27 08:54:22.776  5885  5885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 08:54:22.781   862  6071 D DhcpStateMachine: StoppedState
,07-27 08:54:22.783   862  1307 E WifiStateMachine: Start Dhcp Watchdog 1
07-27 08:54:22.783   862  6071 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:22.783   862  6071 D DhcpStateMachine: WaitBeforeStartState
07-27 08:54:22.788   862   862 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 08:54:22.788   862   862 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
07-27 08:54:22.790  5885  5885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-27 08:54:22.796  1909  1909 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,07-27 08:54:22.797  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-48 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-07-27 08:54:22.797 DNS addrs= 0.0.0.0, 0.0.0.0, 
07-27 08:54:22.798  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-27 08:54:22.798  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 08:54:22.798  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-27 08:54:22.799  5885  5885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 08:54:22.805   862  1313 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
07-27 08:54:22.810  5885  5885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 08:54:22.815  5885  5885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 08:54:22.829  5885  5885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 08:54:22.835  5885  5885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 08:54:22.882   275   908 I Netd    : M: Get netlink event, ifname: p2p0 action: 6
07-27 08:54:22.883   862  1012 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:22.884   862  1012 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-27 08:54:22.891   862  1307 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
07-27 08:54:22.891   862  1307 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-27 08:54:22.891   862  1306 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1da88349 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:22.891   862  1306 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1da88349 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:22.892   862  6071 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:22.892   862  1307 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-27 08:54:22.892   862  1307 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700" is not exist.
07-27 08:54:22.893   862  6071 D DhcpStateMachine: DHCP Start wake lock is acquired.
07-27 08:54:22.893   862   862 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 08:54:22.893   862   862 D WifiServerServiceExt: setSupplicantStateCOMPLETED
07-27 08:54:22.895   862   862 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
07-27 08:54:22.895   862   862 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,07-27 08:54:22.969  6045  6045 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,07-27 08:54:22.970  6045  6045 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
07-27 08:54:22.970  6045  6045 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
07-27 08:54:23.008  6045  6045 I UEI.SmartControl: --- Selecting new region: 2
,07-27 08:54:23.010  6045  6045 I UEI.SmartControl: -- Running on KitKat(19) and above! JNI will be used.
07-27 08:54:23.018  6045  6045 D UEI.SmartControl: Platform has CIR...
07-27 08:54:23.019  6045  6045 D UEI.SmartControl: NO CIR support, need to check package...
07-27 08:54:23.020  6045  6045 I UEI.SmartControl: Model: LG-D722 uses JNI
,07-27 08:54:23.023  6045  6045 D UEI.SmartControl: QS Service created
07-27 08:54:23.046  6045  6045 E UEI.SmartControl: QS start get config
,07-27 08:54:23.096  6045  6045 D UEI.SmartControl: Loading JNI Libs...
,07-27 08:54:23.097   862  6071 D DhcpStateMachine: DHCPV4 request on wlan0
07-27 08:54:23.097   862  6071 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
07-27 08:54:23.097   862  6071 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
07-27 08:54:23.098  6045  6045 D UEI.SmartControl:  configuring local db...
07-27 08:54:23.114  6072  6072 I dhcpcd  : version 5.5.6 starting
,07-27 08:54:23.116  6072  6072 E dhcpcd  : get_duid: Read-only file system
07-27 08:54:23.185  6072  6072 I dhcpcd  : wlan0: rebinding lease of 192.168.1.105
,07-27 08:54:23.238  6072  6072 I dhcpcd  : wlan0: acknowledged 192.168.1.105 from 192.168.1.1
,07-27 08:54:23.314   279  1287 V AudioFlinger: thread 0xb5651000 type 0 TID 1287 going to sleep
,07-27 08:54:23.319   279  1290 V AudioFlinger: thread 0xb5735000 type 0 TID 1290 going to sleep
07-27 08:54:23.322  6072  6072 I dhcpcd  : wlan0: leased 192.168.1.105 for 172800 seconds
07-27 08:54:23.322   275   908 I Netd    : M: Get netlink event, ifname: wlan0 action: 6
07-27 08:54:23.323   862  1012 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:23.323   862  1012 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:54:23.324   279  1288 V AudioFlinger: thread 0xb56eb000 type 0 TID 1288 going to sleep
07-27 08:54:23.327   862  1313 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
07-27 08:54:23.343  6045  6045 D UEI.SmartControl:  ---- Has DB8: true
,07-27 08:54:23.351  6045  6045 D UEI.SmartControl: QS start statue = true Error code = 0
07-27 08:54:23.352  6045  6045 D UEI.SmartControl: QS version = v2.7.11.1_RC1
07-27 08:54:23.362  6045  6045 D UEI.SmartControl: QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
07-27 08:54:23.367  6045  6045 D UEI.SmartControl: IRRCDataComm has AudioManager!!!!.
,07-27 08:54:23.389  6045  6045 W irrc_jni: IRRCPlayer_nativeInit ++ 
,07-27 08:54:23.389  6045  6045 D irrcClient: IrrcClient ++ 
07-27 08:54:23.389  6045  6045 D irrcClient: getIrrcService ++ 
,07-27 08:54:23.391  6045  6045 D irrcClient: getIrrcService -- 
07-27 08:54:23.391  6045  6045 D irrcClient: IrrcClient -- 
07-27 08:54:23.391  6045  6045 W irrc_jni: IRRCPlayer_nativeInit -- 
07-27 08:54:23.399  6045  6045 D UEI.SmartControl: Services init done
07-27 08:54:23.400  6045  6096 I UEI.SmartControl: Device manager: loading config....
07-27 08:54:23.402  6045  6045 D UEI.SmartControl: QS Service init finished
,07-27 08:54:23.406  6045  6045 D UEI.SmartControl: QS Service version name: 0.1.73
07-27 08:54:23.407  6045  6045 D UEI.SmartControl: QS Service version code: 1073
07-27 08:54:23.409  6045  6045 D UEI.SmartControl: Service requested: Control
07-27 08:54:23.411  6045  6096 D UEI.SmartControl: Config is loaded...
07-27 08:54:23.448  6045  6095 D UEI.SmartControl:  ----- QS SDK is ready!!!
07-27 08:54:23.448  6045  6045 D UEI.SmartControl: Request IControl service: devices are loaded...
,07-27 08:54:23.452  6045  6095 I UEI.SmartControl: Notify AllClients services are ready: 0
07-27 08:54:23.453  6045  6060 D UEI.SmartControl: -----IControl: 11
07-27 08:54:23.454  6045  6045 D UEI.SmartControl: Internal service binding...
07-27 08:54:23.454  6045  6060 D UEI.SmartControl: Caller: com.lge.qremote
07-27 08:54:23.455  6045  6060 D UEI.SmartControl: ------------ IControl registerCallback...
07-27 08:54:23.456  6045  6060 I UEI.SmartControl: Registering callback...
07-27 08:54:23.457  6045  6061 D UEI.SmartControl: -----IControl: 19
07-27 08:54:23.458  6045  6061 D UEI.SmartControl: Caller: com.lge.qremote
07-27 08:54:23.459  6045  6061 I UEI.SmartControl: Registering Services Ready callback...
07-27 08:54:23.460  6045  6061 I UEI.SmartControl: Notify client services are ready...
07-27 08:54:23.463  6045  6060 D UEI.SmartControl: -----IControl: 8
,07-27 08:54:23.464  6045  6060 D UEI.SmartControl: Caller: com.lge.qremote
07-27 08:54:23.471  6019  6019 I AudioManager: getMode name:com.lge.qremote
07-27 08:54:23.477   862  1291 I ActivityManager: Killing 5499:com.google.android.gms:car/u0a6 (adj 15): empty #11
,07-27 08:54:23.593   862  1375 W libprocessgroup: failed to open /acct/uid_10006/pid_5499/cgroup.procs: No such file or directory
,07-27 08:54:23.596  6019  6019 I AudioManager: getMode name:com.lge.qremote
07-27 08:54:23.700   862  1946 I art     : Explicit concurrent mark sweep GC freed 52828(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 1.723ms total 185.562ms
,07-27 08:54:23.700   862  6071 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:23.700   862  6071 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:54:23.701   862  6071 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:23.701   862  6071 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:54:23.701   862  6071 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:23.701   862  6071 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:54:23.701   862  6071 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:23.701   862  6071 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:54:23.701   862  6071 D DhcpStateMachine: DHCPV4 succeeded on wlan0
07-27 08:54:23.703   862  6071 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 4
,07-27 08:54:23.703   862  6071 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
07-27 08:54:23.703   862  6071 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:23.704   862  6071 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:54:23.704   862  6071 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.105
07-27 08:54:23.704   862  6071 V LgDhcpStateMachineHelper: Add DhcpResults: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
07-27 08:54:23.704   862  6071 V DhcpStateMachine: Current State is mWaitBeforeStartState.
07-27 08:54:23.704   862  6071 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: true
07-27 08:54:23.706   862  1306 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:23.706   862  1306 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:23.706   862  6071 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
07-27 08:54:23.706   862  6071 D DhcpStateMachine: RunningState
07-27 08:54:23.711   862  1313 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
07-27 08:54:23.712   862  1307 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
07-27 08:54:23.713  6019  6019 I AudioManager: getMode name:com.lge.qremote
07-27 08:54:23.713   862  1313 D ConnectivityService: ignoring duplicate network state non-change
,07-27 08:54:23.716  1909  1909 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
07-27 08:54:23.717   862   862 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:23.717   862   862 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:23.717   862   862 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-27 08:54:23.718   862  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-27 08:54:23.723   862  1313 D ConnectivityService: Adding iface wlan0 to network 100
07-27 08:54:23.724  1873  1890 D WifiServiceExtension: isInternetCheckAvailable return false
07-27 08:54:23.727  1873  1889 D WifiServiceExtension: isInternetCheckAvailable return false
,07-27 08:54:23.732  1368  1368 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 08:54:23.736  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-27 08:54:23.736  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 08:54:23.736  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-27 08:54:23.736  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
07-27 08:54:23.736  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-27 08:54:23.736  1368  1368 I [SystemUI]QuickSettingsHandler: Remote
07-27 08:54:23.737  1368  1368 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
07-27 08:54:23.744   862  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-27 08:54:23.748   862   862 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:23.748   862   862 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:23.748   862   862 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
07-27 08:54:23.750   862   862 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-27 08:54:23.751   862   862 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:23.751   862   862 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:23.751   862   862 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
07-27 08:54:23.752   862   862 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
07-27 08:54:23.755   862   862 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:23.756   862   862 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:23.756   862   862 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,07-27 08:54:23.756  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
07-27 08:54:23.756  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 08:54:23.756  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
07-27 08:54:23.756  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
07-27 08:54:23.757  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-27 08:54:23.757  1368  1368 I [SystemUI]QuickSettingsHandler: Remote
07-27 08:54:23.759  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-48 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.105 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-07-27 08:54:23.758 DNS addrs= 192.168.1.1, 0.0.0.0, 
07-27 08:54:23.759  1909  1909 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.105 ipV6Addr=
07-27 08:54:23.759  1909  1909 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
07-27 08:54:23.761  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-48 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.105 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-07-27 08:54:23.76 DNS addrs= 192.168.1.1, 0.0.0.0, 
07-27 08:54:23.761  1909  1909 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.105 ipV6Addr=
07-27 08:54:23.761  1909  1909 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
07-27 08:54:23.763  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-48 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.105 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-07-27 08:54:23.762 DNS addrs= 192.168.1.1, 0.0.0.0, 
07-27 08:54:23.763  1909  1909 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.105 ipV6Addr=
07-27 08:54:23.763  1909  1909 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
07-27 08:54:23.766  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-48 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.105 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-07-27 08:54:23.766 DNS addrs= 192.168.1.1, 0.0.0.0, 
07-27 08:54:23.768  1909  1909 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.105 ipV6Addr=
,07-27 08:54:23.770  5885  5885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-27 08:54:23.773   862  1313 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-27 08:54:23.773   862  1313 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
07-27 08:54:23.774   275   915 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
07-27 08:54:23.774   275   915 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:54:23.774   275   915 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
07-27 08:54:23.774   275   915 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:54:23.775   862  1313 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
07-27 08:54:23.775   275   915 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
07-27 08:54:23.776   275   915 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:54:23.776   275   915 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
07-27 08:54:23.776   275   915 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:54:23.777   862  1313 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
07-27 08:54:23.777   275   915 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
07-27 08:54:23.777   275   915 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:54:23.780  1368  1368 I [SystemUI]StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
,07-27 08:54:23.784  5885  5885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 08:54:23.787   862  1313 D ConnectivityService: addLocalRoutetoDefaultNetwork
07-27 08:54:23.787   862  1313 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
07-27 08:54:23.788   862  1313 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
07-27 08:54:23.788   862  1313 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:23.788   862  1313 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:54:23.790   275   915 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
07-27 08:54:23.790   275   915 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:54:23.794  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-27 08:54:23.794  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 08:54:23.794  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
07-27 08:54:23.794   862  1313 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-27 08:54:23.795   862  1313 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
07-27 08:54:23.795   862  1313 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
07-27 08:54:23.795   862  1313 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
07-27 08:54:23.795   862  1313 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:54:23.795   862  1313 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 08:54:23.795   862  1313 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-27 08:54:23.796   862  1313 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:54:23.796   862  1313 D ConnectivityService:     satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:false
07-27 08:54:23.796   862  1313 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:54:23.796   862  1313 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
07-27 08:54:23.796   862  1313 D ConnectivityService: currentScore = 0, newScore = 20
07-27 08:54:23.796   862  1313 D ConnectivityService:    accepting network in place of null
07-27 08:54:23.796   862  1313 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:54:23.796   862  6068 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-27 08:54:23.796   862  6068 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
07-27 08:54:23.797  1368  1368 I, [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
07-27 08:54:23.797   862  6068 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,07-27 08:54:23.797   862  1307 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:54:23.797   862  1307 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:54:23.797  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-27 08:54:23.797  1368  1368 I [SystemUI]QuickSettingsHandler: Remote
07-27 08:54:23.799  1368  1368 I [SystemUI]StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
07-27 08:54:23.804   862  1313 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
07-27 08:54:23.808  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-27 08:54:23.809  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 08:54:23.809  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
,07-27 08:54:23.809  1787  1787 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:54:23.809  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
07-27 08:54:23.809  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
07-27 08:54:23.809  1368  1368 I [SystemUI]QuickSettingsHandler: Remote
07-27 08:54:23.810  1787  1787 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
07-27 08:54:23.817   862  1313 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
07-27 08:54:23.818   862  1313 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
07-27 08:54:23.819   862  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-27 08:54:23.823   862  1305 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:23.823   862  1305 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:54:23.824   862  1305 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:23.824   862  1305 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:54:23.824   275   910 E BandwidthController: [LG DATA] No such appUid: 1000
07-27 08:54:23.824   275   910 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
,07-27 08:54:23.826  1909  1909 W QCNEJ   : |CORE| No family connected
07-27 08:54:23.826  1909  1909 I QCNEJ   : |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
07-27 08:54:23.826   275  6115 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
07-27 08:54:23.827   275  6115 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:54:23.827   275  6115 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=0
07-27 08:54:23.828   275  6115 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-27 08:54:23.828   862  1014 D Tethering: MasterInitialState.processMessage what=3
07-27 08:54:23.829   275  6115 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-27 08:54:23.830   862  1012 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
07-27 08:54:23.832  1909  1909 I QCNEJ   : |CORE| sendDefaultNwMsg: default = 1
07-27 08:54:23.834   862  1313 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
07-27 08:54:23.834   862  1313 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
07-27 08:54:23.835   862  1313 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
07-27 08:54:23.836   862  6068 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] Start DNSResolver start to wait
,07-27 08:54:23.839   862  1313 D ConnectivityService: validation of new default Network = false
07-27 08:54:23.842   862  1313 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
07-27 08:54:23.842   862  1313 D DSQN    : enableDataServiceNotify 
07-27 08:54:23.842   862  1313 D DSQN    : start dsqn bin
07-27 08:54:23.845   862  6116 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] wait 500ms before dns check
07-27 08:54:23.848   862  1305 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
07-27 08:54:23.855  5885  5885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 08:54:23.861  5885  5885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 08:54:23.876  1368  1368 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,07-27 08:54:23.879  5885  5885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
07-27 08:54:23.884  1368  1368 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
07-27 08:54:23.886  5885  5885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 08:54:23.886  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-27 08:54:23.886  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 08:54:23.887  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
07-27 08:54:23.891  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-27 08:54:23.891  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 08:54:23.891  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
07-27 08:54:23.892  5931  5931 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,07-27 08:54:23.894   862  1313 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
07-27 08:54:23.894   862  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:54:23.894   862  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 08:54:23.899   862  1313 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 08:54:23.905  6117  6117 I DSQN    : DSQN samuel.seo ver 141203
07-27 08:54:23.905   862  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:54:23.905  6117  6117 E DSQN    : DSQN sock connect success to lgdatalistenerd
07-27 08:54:23.906  6117  6117 I DSQN    : created command queue thread
07-27 08:54:23.906  6117  6117 I DSQN    : Interface wlan0 address 192.168.1.105 0xc0a80169
07-27 08:54:23.906  6117  6117 I DSQN    : Interface wlan0 netmask 255.255.255.0 0xc0a80169
,07-27 08:54:23.906   862  1313 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:54:23.906  1368  1724 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-27 08:54:23.907  5349  5857 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-27 08:54:23.910  5931  5931 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
07-27 08:54:23.918  5885  5885 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,07-27 08:54:23.923  5885  5885 D WiFiOffLoadBroadcast: MCCMNC not supported: null
07-27 08:54:23.928  5931  5931 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
07-27 08:54:23.929  5931  5931 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
07-27 08:54:24.345   862  6116 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] DNSResolver start dns
07-27 08:54:24.345   862  6116 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:24.345   862  6116 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:54:24.345   862  6116 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=100; mark=0
07-27 08:54:24.345   862  6116 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:54:24.347   275   910 E BandwidthController: [LG DATA] No such appUid: 1000
07-27 08:54:24.347   275   910 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
,07-27 08:54:24.348   275  6126 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=983140
07-27 08:54:24.348   275  6126 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:54:24.348   275  6126 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-27 08:54:24.348   275  6126 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-27 08:54:24.398   275  6126 D libc-netbsd: res_queryN name = xxxxx succeed
07-27 08:54:24.400   862  6116 I System.out: propertyValue:false
,07-27 08:54:24.400   862  6116 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] DNSResolver end dns
07-27 08:54:24.405   862  6068 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
07-27 08:54:24.419   862  6068 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:24.420   862  6068 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-27 08:54:24.427  6117  6118 I DSQN    : first global connection report this to start monitoring at DSQM.
07-27 08:54:24.427  6117  6118 I DSQN    : restart monitoring
07-27 08:54:24.428  6117  6128 I DSQN    : dsqn report finish
07-27 08:54:24.428   275   914 D LGDataListener: argv[0]=dsqncommand
07-27 08:54:24.428   275   914 D LGDataListener: argv[1]=wlan0
07-27 08:54:24.428   275   914 D LGDataListener: argv[2]=1
07-27 08:54:24.428   275   914 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
07-27 08:54:24.429   862  1012 D DSQN    : DSQM DsqnNotification wlan0  1
07-27 08:54:24.430   862  1012 D DSQN    : start to monitor internet connection
07-27 08:54:24.437   862  6068 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 27 Jul 2016 06:54:25 GMT], X-Android-Received-Millis=[1469602464436], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1469602464429]}
,07-27 08:54:24.437   862  6068 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,07-27 08:54:24.442  1873  1889 D WifiServiceExtension: isInternetCheckAvailable return false
07-27 08:54:24.442   862  6068 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: [LWD] wifi && isInternetCheckAvailable is false
07-27 08:54:24.443   862  6068 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
07-27 08:54:24.443   862  1313 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
07-27 08:54:24.443   862  1313 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
07-27 08:54:24.444   862  1313 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:54:24.444   862  1313 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 08:54:24.444   862  1313 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
07-27 08:54:24.444   862  1313 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:54:24.444   862  1313 D ConnectivityService:     satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:false
07-27 08:54:24.444   862  1313 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
07-27 08:54:24.444   862  1313 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
07-27 08:54:24.444   862  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:54:24.444   862  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 08:54:24.445   862  1313 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 08:54:24.445   862   862 D WifiDataContinuityService: sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
07-27 08:54:24.447   862  1307 I WifiServerServiceExt: set CMD_CAPTIVE_CHECK_COMPLETED
07-27 08:54:24.448  1368  1724 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-27 08:54:24.449   862  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:54:24.449   862  1313 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:54:24.449  5349  5857 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-27 08:54:24.451   862  1313 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:54:24.451   862  1307 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:54:24.451   862  1307 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 08:54:24.451  1787  1787 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:54:24.452  1787  1787 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
07-27 08:54:24.454   862  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-27 08:54:24.471  1368  1368 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
07-,27 08:54:24.472  1368  1368 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
07-27 08:54:24.474  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-27 08:54:24.474  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 08:54:24.474  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
07-27 08:54:24.475  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,07-27 08:54:24.476  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 08:54:24.476  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
07-27 08:54:24.672   275   908 I Netd    : M: Get netlink event, ifname: wlan0 action: 6
,07-27 08:54:24.675   862  1012 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:24.675   862  1012 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:54:24.678   862  1313 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=true
07-27 08:54:24.678   862  1313 D ConnectivityService: identical MTU - not setting
07-27 08:54:24.678   862  1313 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
07-27 08:54:24.678   862  1313 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
07-27 08:54:24.678   862  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:54:24.678   862  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 08:54:24.679   862  1313 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 08:54:24.679  1368  1724 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
07-27 08:54:24.680   862  1313 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:54:24.681   862  1313 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 08:54:24.682  5349  5857 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
07-27 08:54:24.687  1909  1909 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
07-27 08:54:24.688  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-48 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.105 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-07-27 08:54:24.688 DNS addrs= 192.168.1.1, 0.0.0.0, 
07-27 08:54:24.689   862  1313 D ConnectivityService: Wi-Fi IP changed. Lp difference / No Route difference
07-27 08:54:24.689   862  1313 D DSQN    : enableDataServiceNotify 
07-27 08:54:24.689   862  1313 D DSQN    : start dsqn bin
,07-27 08:54:24.699   862  1313 D DSQN    : dsqn is running restart
07-27 08:54:24.717  6129  6129 I DSQN    : DSQN samuel.seo ver 141203
,07-27 08:54:24.720  6129  6129 E DSQN    : DSQN sock connect success to lgdatalistenerd
07-27 08:54:24.720  6129  6129 I DSQN    : created command queue thread
07-27 08:54:24.721  6129  6129 I DSQN    : Interface wlan0 address 192.168.1.105 0xc0a80169
07-27 08:54:24.721  6129  6129 I DSQN    : Interface wlan0 netmask 255.255.255.0 0xc0a80169
07-27 08:54:24.757  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-27 08:54:24.757  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 08:54:24.758  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,07-27 08:54:25.383   862  1017 I PowerManagerService: ALS enabled for SRE
07-27 08:54:25.383   862  1017 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (26351 ms ago)
,07-27 08:54:25.421   862  1346 D qdlights: set_light_backlight: 251
,07-27 08:54:25.435   862  1346 D qdlights: set_light_backlight: 248
,07-27 08:54:25.451   862  1346 D qdlights: set_light_backlight: 245
,07-27 08:54:25.468   862  1346 D qdlights: set_light_backlight: 241
,07-27 08:54:25.485   862  1346 D qdlights: set_light_backlight: 238
,07-27 08:54:25.501   862  1346 D qdlights: set_light_backlight: 235
,07-27 08:54:25.518   862  1346 D qdlights: set_light_backlight: 231
,07-27 08:54:25.535   862  1346 D qdlights: set_light_backlight: 228
,07-27 08:54:25.551   862  1346 D qdlights: set_light_backlight: 225
,07-27 08:54:25.568   862  1346 D qdlights: set_light_backlight: 221
,07-27 08:54:25.585   862  1346 D qdlights: set_light_backlight: 218
,07-27 08:54:25.601   862  1346 D qdlights: set_light_backlight: 215
,07-27 08:54:25.618   862  1346 D qdlights: set_light_backlight: 211
,07-27 08:54:25.635   862  1346 D qdlights: set_light_backlight: 208
,07-27 08:54:25.651   862  1346 D qdlights: set_light_backlight: 205
,07-27 08:54:25.668   862  1346 D qdlights: set_light_backlight: 201
,07-27 08:54:25.685   862  1346 D qdlights: set_light_backlight: 198
,07-27 08:54:25.701   862  1346 D qdlights: set_light_backlight: 195
,07-27 08:54:25.718   862  1346 D qdlights: set_light_backlight: 191
,07-27 08:54:25.735   862  1346 D qdlights: set_light_backlight: 188
,07-27 08:54:25.751   862  1346 D qdlights: set_light_backlight: 185
,07-27 08:54:25.759  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-27 08:54:25.759  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 08:54:25.759  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
07-27 08:54:25.768   862  1346 D qdlights: set_light_backlight: 181
07-27 08:54:25.785   862  1346 D qdlights: set_light_backlight: 178
,07-27 08:54:25.801   862  1346 D qdlights: set_light_backlight: 175
,07-27 08:54:25.816  1909  1909 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
07-27 08:54:25.818  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-48 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.105 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-07-27 08:54:25.818 DNS addrs= 192.168.1.1, 0.0.0.0, 
,07-27 08:54:25.819   862  1346 D qdlights: set_light_backlight: 171
07-27 08:54:25.822  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-27 08:54:25.823  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 08:54:25.823  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
07-27 08:54:25.835   862  1346 D qdlights: set_light_backlight: 168
,07-27 08:54:25.851   862  1346 D qdlights: set_light_backlight: 165
,07-27 08:54:25.868   862  1346 D qdlights: set_light_backlight: 161
,07-27 08:54:25.885   862  1346 D qdlights: set_light_backlight: 158
,07-27 08:54:25.901   862  1346 D qdlights: set_light_backlight: 155
,07-27 08:54:25.918   862  1346 D qdlights: set_light_backlight: 151
,07-27 08:54:25.935   862  1346 D qdlights: set_light_backlight: 148
,07-27 08:54:25.951   862  1346 D qdlights: set_light_backlight: 145
,07-27 08:54:25.968   862  1346 D qdlights: set_light_backlight: 141
,07-27 08:54:25.985   862  1346 D qdlights: set_light_backlight: 138
,07-27 08:54:26.001   862  1346 D qdlights: set_light_backlight: 135
,07-27 08:54:26.018   862  1346 D qdlights: set_light_backlight: 131
,07-27 08:54:26.035   862  1346 D qdlights: set_light_backlight: 128
,07-27 08:54:26.051   862  1346 D qdlights: set_light_backlight: 125
,07-27 08:54:26.068   862  1346 D qdlights: set_light_backlight: 121
,07-27 08:54:26.085   862  1346 D qdlights: set_light_backlight: 118
,07-27 08:54:26.101   862  1346 D qdlights: set_light_backlight: 115
,07-27 08:54:26.118   862  1346 D qdlights: set_light_backlight: 111
,07-27 08:54:26.135   862  1346 D qdlights: set_light_backlight: 108
,07-27 08:54:26.151   862  1346 D qdlights: set_light_backlight: 105
,07-27 08:54:26.168   862  1346 D qdlights: set_light_backlight: 101
,07-27 08:54:26.192   862  1346 D qdlights: set_light_backlight: 98
,07-27 08:54:26.201   862  1346 D qdlights: set_light_backlight: 95
07-27 08:54:26.218   862  1346 D qdlights: set_light_backlight: 91
,07-27 08:54:26.235   862  1346 D qdlights: set_light_backlight: 88
,07-27 08:54:26.251   862  1346 D qdlights: set_light_backlight: 85
,07-27 08:54:26.268   862  1346 D qdlights: set_light_backlight: 81
,07-27 08:54:26.285   862  1346 D qdlights: set_light_backlight: 78
,07-27 08:54:26.301   862  1346 D qdlights: set_light_backlight: 75
,07-27 08:54:26.318   862  1346 D qdlights: set_light_backlight: 71
,07-27 08:54:26.335   862  1346 D qdlights: set_light_backlight: 68
,07-27 08:54:26.351   862  1346 D qdlights: set_light_backlight: 65
,07-27 08:54:26.368   862  1346 D qdlights: set_light_backlight: 61
,07-27 08:54:26.385   862  1346 D qdlights: set_light_backlight: 58
,07-27 08:54:26.401   862  1346 D qdlights: set_light_backlight: 55
,07-27 08:54:26.418   862  1346 D qdlights: set_light_backlight: 51
,07-27 08:54:26.435   862  1346 D qdlights: set_light_backlight: 48
,07-27 08:54:26.451   862  1346 D qdlights: set_light_backlight: 45
,07-27 08:54:26.468   862  1346 D qdlights: set_light_backlight: 41
,07-27 08:54:26.485   862  1346 D qdlights: set_light_backlight: 38
,07-27 08:54:26.501   862  1346 D qdlights: set_light_backlight: 35
,07-27 08:54:26.518   862  1346 D qdlights: set_light_backlight: 31
,07-27 08:54:26.535   862  1346 D qdlights: set_light_backlight: 28
,07-27 08:54:26.551   862  1346 D qdlights: set_light_backlight: 25
,07-27 08:54:26.568   862  1346 D qdlights: set_light_backlight: 21
,07-27 08:54:26.585   862  1346 D qdlights: set_light_backlight: 18
,07-27 08:54:26.601   862  1346 D qdlights: set_light_backlight: 15
,07-27 08:54:26.618   862  1346 D qdlights: set_light_backlight: 11
,07-27 08:54:26.636   862  1346 D qdlights: set_light_backlight: 10
,07-27 08:54:26.751   862  1308 V WifiInternetCheck: Single check msg out of sync, ignoring.
,07-27 08:54:26.837   862  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-27 08:54:26.847  1368  1368 I [SystemUI]QuickSettingsHandler: Got action android.net.conn.CONNECTIVITY_CHANGE at null
,07-27 08:54:26.858   862   862 D LocSvc_java: onReceive
07-27 08:54:26.858   862   862 D LocSvc_java: got connectivity action
07-27 08:54:26.859  2074  5993 D BluetoothAdapterService(340792543): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@20c384ad
,07-27 08:54:26.859  5716  5716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 08:54:26.859  5716  5716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:54:26.859  5716  5716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 08:54:26.859  5716  5716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 08:54:26.859  5716  5716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 08:54:26.859  5716  5716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 08:54:26.859  5716  5716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 08:54:26.859  5716  5716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 08:54:26.860  2074  5993 D BluetoothAdapterService(340792543): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@20c384ad
07-27 08:54:26.863   862  1764 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:26.863   862  1764 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:54:26.863   862  1764 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:26.863   862  1764 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:54:26.863   275   910 E BandwidthController: [LG DATA] No such appUid: 1000
07-27 08:54:26.863   275   910 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
07-27 08:54:26.863  5716  5716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 08:54:26.865   275  6132 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-27 08:54:26.865   275  6132 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:54:26.865   275  6132 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-27 08:54:26.865   275  6132 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-27 08:54:26.872   862   862 D LocSvc_java: Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
07-27 08:54:26.872   862   862 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
,07-27 08:54:26.878   862   862 D LocSvc_java: getAGpsConnectionInfo connType - 4
07-27 08:54:26.895   862   901 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,07-27 08:54:26.898   862   902 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6133 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-27 08:54:26.899   862   862 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
07-27 08:54:26.899   862   862 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
07-27 08:54:26.899   862   862 D LocSvc_java: Sending msg: 5 arg1:0 arg2:1
07-27 08:54:26.904   275  6132 D libc-netbsd: res_queryN name = xxxxx succeed
07-27 08:54:26.906   862  1764 I System.out: propertyValue:false
07-27 08:54:26.906   862  6139 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:26.906   862  6139 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-27 08:54:26.940   862  6139 D LocSvc_java: NTP server returned: 1469602467528 (Wed Jul 27 08:54:27 GMT+02:00 2016) reference: 147890 certainty: 12 system time offset: 596
,07-27 08:54:26.954   862  1764 D AlarmManagerService: Setting time of day to sec=1469602467
,07-27 08:54:27.529   862  1764 W AlarmManagerService: Unable to set rtc to 1469602467: Invalid argument
07-27 08:54:27.534   862  6139 D LocSvc_java: Sending msg: 10 arg1:0 arg2:1
07-27 08:54:27.560  2023  2023 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-27 08:54:27.563  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 08:54:27.564  1368  1368 I [SystemUI]Clock: onReceive = android.intent.action.TIME_SET
07-27 08:54:27.569  1368  1368 I LgeClockWidgetControlView: time changed, timezoneChanged : false
07-27 08:54:27.578  2847  2847 D WeatherService: 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 8:54:27
,07-27 08:54:27.579  2847  2847 D WeatherService: 2 : requestRefreshAppWidget, isUpdateStart : false
07-27 08:54:27.583  2847  2847 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-27 08:54:27.583  2847  2847 D WeatherService: 2 : requestRefreshAppWidget, isUpdating : false
07-27 08:54:27.583  2847  2847 D WeatherAncestor: 2 : buildUpdate, appWidgetId: 2
07-27 08:54:27.588  2847  2847 D WeatherTheme: 2 : Current Theme Name: com.lge.launcher2.theme.optimus
07-27 08:54:27.588  2847  2847 D WeatherTheme: 2 : Fixed theme : optimus
07-27 08:54:27.602  2847  2847 D WeatherReflect: 2 : Map key string is -2
07-27 08:54:27.603   862   902 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.UpdateScheduleReceiver: pid=6162 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,07-27 08:54:27.629  2847  2847 D lim     : 2 : time = 08:54
,07-27 08:54:27.630   862  1375 W ActivityManager: getTasks: caller 10024 is using old GET_TASKS but privileged; allowing
07-27 08:54:27.634  2847  2847 I WeatherReflect: Model Name : LG-D722
07-27 08:54:27.634  2847  2847 D WeatherTheme: 2 : exactly same view!
07-27 08:54:27.634  2847  2847 D WeatherTheme: 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
07-27 08:54:27.634  2847  2847 D WeatherService: 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 8:54:27
07-27 08:54:27.661  1757  1757 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,07-27 08:54:27.681  1947  1947 I [LGHome]LGDateChangeReceiver: [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=27 currentDate=-1 dayofweek=4 currentDayOfWeek=-1
,07-27 08:54:27.713  6162  6162 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 08:54:27.713  6162  6162 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-27 08:54:27.714  6162  6162 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,07-27 08:54:27.734  1947  1947 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 27
07-27 08:54:27.734   862   901 I ActivityManager: Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=6181 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,07-27 08:54:27.742   862   901 I NotificationManager: android: cancelAsUser(716319171) by android
,07-27 08:54:27.785  1947  1947 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 27
07-27 08:54:27.800  1947  1947 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
,07-27 08:54:27.850   862   901 I ActivityManager: Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6199 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,07-27 08:54:27.855   862   901 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 08:54:27.929  6181  6181 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 08:54:27.931  6181  6181 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-27 08:54:27.931  6181  6181 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,07-27 08:54:28.031  1757  1757 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-27 08:54:28.042   862   901 E GpsLocationProvider: No APN found to select.
07-27 08:54:28.118  6162  6162 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,07-27 08:54:28.121  6199  6199 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 08:54:28.147  6162  6162 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,07-27 08:54:28.166   862  1851 I ActivityManager: Process com.android.vending (pid 5366) has died
,07-27 08:54:28.205  5349  6228 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,07-27 08:54:28.217   862  6227 D LgeGpsConstants: Can't find 'ext_gps.conf'!!
07-27 08:54:28.219   862  6227 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:28.221   862  6227 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-27 08:54:28.221   862  6227 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:28.221   862  6227 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:54:28.222   275   910 E BandwidthController: [LG DATA] No such appUid: 1000
07-27 08:54:28.222   275   910 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
07-27 08:54:28.222   275  6230 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-27 08:54:28.222   275  6230 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:54:28.223   275  6230 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-27 08:54:28.223   275  6230 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,07-27 08:54:28.230  6181  6181 I AppConfig: Total System Memory = 906309632
07-27 08:54:28.238  6181  6181 I GalleryUtils: Application Heap = 96 MB
,07-27 08:54:28.252  6181  6181 I AppConfig: App Tier : NOT_DEF
07-27 08:54:28.263  6181  6181 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,07-27 08:54:28.268   275  6230 D libc-netbsd: res_queryN name = xxxxx succeed
07-27 08:54:28.269   862  6227 I System.out: propertyValue:false
07-27 08:54:28.292   279   279 V AudioFlinger: 2865 died, releasing its sessions
07-27 08:54:28.292   279   279 V AudioFlinger:  pid 1787 @ 0
07-27 08:54:28.292   279   279 V AudioFlinger:  pid 3103 @ 1
,07-27 08:54:28.292   279   279 V AudioFlinger:  pid 3103 @ 2
07-27 08:54:28.300   862   901 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 37261, reason: UserStart, SyncResult: databaseError: true stats []
07-27 08:54:28.303  6133  6133 I MusicStore: Database version: 120
07-27 08:54:28.304   295   356 I ThermalEngine: Sensor:pa_therm0:32000 mC
07-27 08:54:28.305   862   901 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 181525, reason: UserStart
,07-27 08:54:28.307   862   901 I NotificationManager: android: cancelAsUser(716319171) by android
07-27 08:54:28.313   862  6227 D LgeGpsLocationProvider: NTP server: europe.pool.ntp.org
07-27 08:54:28.313   862  6227 D LgeGpsLocationProvider: NTP server returned: 1469602468332 (Wed Jul 27 08:54:28 GMT+02:00 2016) reference: 148697 certainty: 22 system time offset: 19
07-27 08:54:28.336  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-27 08:54:28.336  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 08:54:28.336  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,07-27 08:54:28.349   862  2204 I ActivityManager: Process com.lge.music (pid 2865) has died
,07-27 08:54:28.456   862   901 I NotificationManager: android: cancelAsUser(-1597574061) by android
,07-27 08:54:28.483   244   325 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-27 08:54:28.483   244   325 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
07-27 08:54:28.483   244   325 W Vold    : Returning OperationFailed - no handler for errno 0
07-27 08:54:28.507  6133  6133 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,07-27 08:54:28.540   862  1308 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:28.540   862  1308 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-27 08:54:28.540   862  1308 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:28.540   862  1308 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:54:28.540   275   910 E BandwidthController: [LG DATA] No such appUid: 1000
07-27 08:54:28.540   275   910 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
07-27 08:54:28.541   275  6243 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-27 08:54:28.542   275  6243 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:54:28.542   275  6243 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-27 08:54:28.549   275  6243 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
,07-27 08:54:28.577   862   901 I NotificationManager: android: cancelAsUser(353845882) by android
,07-27 08:54:28.585  1757  1757 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-27 08:54:28.586   275  6243 D libc-netbsd: res_queryN name = xxxxx succeed
07-27 08:54:28.587  1757  1757 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-27 08:54:28.590   862  1308 I System.out: propertyValue:false
07-27 08:54:28.598   862  1309 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:28.598   862  1309 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:54:28.600   862  1309 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:28.600   862  1309 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:54:28.603   275   910 E BandwidthController: [LG DATA] No such appUid: 1000
07-27 08:54:28.603   275   910 D DnsProxyListener: App 1000 tries DNS query. Accept family:0 protocol:0
07-27 08:54:28.603   275  6245 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-27 08:54:28.603   275  6245 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:54:28.604   275  6245 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-27 08:54:28.604   275  6245 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-27 08:54:28.604   275  6245 D libc-netbsd: res_queryN name = xxxxx succeed
07-27 08:54:28.606   862  1309 I System.out: propertyValue:false
,07-27 08:54:28.613  6129  6130 I DSQN    : first global connection report this to start monitoring at DSQM.
07-27 08:54:28.613  6129  6130 I DSQN    : restart monitoring
07-27 08:54:28.616  6129  6246 I DSQN    : dsqn report finish
07-27 08:54:28.616   275   914 D LGDataListener: argv[0]=dsqncommand
07-27 08:54:28.616   275   914 D LGDataListener: argv[1]=wlan0
07-27 08:54:28.616   275   914 D LGDataListener: argv[2]=1
07-27 08:54:28.616   275   914 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
07-27 08:54:28.618   862  1012 D DSQN    : DSQM DsqnNotification wlan0  1
,07-27 08:54:28.618   862  1012 D DSQN    : start to monitor internet connection
07-27 08:54:28.623   862  1309 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
07-27 08:54:28.686   862  1883 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=6252 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,07-27 08:54:28.795  5349  6222 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,07-27 08:54:28.835  1757  1757 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 08:54:28.843  5349  6266 V AccountUtils: 0 accounts found with uca feature
07-27 08:54:28.847  5349  6266 I GamesSyncAdapter: Starting sync for 3a3529a
,07-27 08:54:28.863   862   901 I NotificationManager: android: cancelAsUser(-591465577) by android
,07-27 08:54:28.892   244   325 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-27 08:54:28.892   244   325 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
07-27 08:54:28.892   244   325 W Vold    : Returning OperationFailed - no handler for errno 0
07-27 08:54:28.894  6133  6133 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,07-27 08:54:28.896   244   325 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-27 08:54:28.897   244   325 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
07-27 08:54:28.897   244   325 W Vold    : Returning OperationFailed - no handler for errno 0
07-27 08:54:28.897  6133  6133 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
07-27 08:54:28.930  6252  6274 D ALBootInit: ====action==>android.intent.action.TIME_SET
,07-27 08:54:28.936  6252  6274 D ALBootInit: Alarm ALBootInit: TIME_SET
07-27 08:54:28.938  6252  6274 D Alarms  : [setNextAlert] start
07-27 08:54:28.953  6252  6274 D Alarms  : [setNextAlert] (1)
,07-27 08:54:28.956  6252  6274 D Alarms  :  minTime  = 0
07-27 08:54:28.958  6252  6274 D Alarms  :  -- OK multi -- 0
07-27 08:54:28.959  6252  6274 E jeny.kim: [setNextAlert] setNextAlert  temp_Alarmlink + 
07-27 08:54:28.959  6252  6274 E jeny.kim: [setNextAlert]setNextAlert temp_AlarmLinkText + 
07-27 08:54:29.006  6045  6097 D UEI.SmartControl: Internal timer expired: 1
,07-27 08:54:29.086   862  2370 I ActivityManager: Process com.lge.lgdmsclient (pid 5984) has died
,07-27 08:54:29.107  6252  6274 I CommonUtil: BUILD Operator: OPEN
,07-27 08:54:29.109  6252  6274 D Alarms  : broadcastToWidgetProvider : false
07-27 08:54:29.115  5716  5809 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-27 08:54:29.115  5716  5809 I jxcore-log: 
07-27 08:54:29.116  6252  6274 D Alarms  : Enter formatDayAndTime(final Context context, long timeInMiliSec)
07-27 08:54:29.141   862  1291 V SettingsProvider: call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,07-27 08:54:29.144  6252  6252 I DigitalAppWidgetProvider: onReceive: android.intent.action.TIME_SET
07-27 08:54:29.158  6252  6252 V DigitalAppWidgetProvider: cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@124d1539
,07-27 08:54:29.164  6252  6252 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@124d1539
07-27 08:54:29.170  6252  6252 D QuickCoverProvider: onReceiver
,07-27 08:54:29.181  5385  5525 I art     : Explicit concurrent mark sweep GC freed 1669(62KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 978us total 69.544ms
07-27 08:54:29.221   862  1375 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6279 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-27 08:54:29.314  6133  6133 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-27 08:54:29.315  6133  6133 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-27 08:54:29.352  6279  6279 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-27 08:54:29.436  6279  6279 D CalendarApplication: CalendarApplication.onCreate()
,07-27 08:54:29.466  6279  6279 D PreferenceKeysParser: [debug_displayParseInfos] preference keys.size() = 44
,07-27 08:54:29.467  6279  6279 D PreferenceKeysParser: [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@10b85794, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@19a4923d, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@27cf0a32, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@1ceec383, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@b8d5900, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@124d1539, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@2a5f977e, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@145014df, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@fef052c, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@860cbf5, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@3d9ad8a, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@394b1ffb, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@3fdd4818, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@37bf3271, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@322d1856, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@321c0d7, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@1b6acdc4, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@20c384ad, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@107a63e2, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@31579373, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@2f290230, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@3440bea9, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@195edc2e, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@2e0df3cf, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@3d54115c, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@33d9c65, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@2008d3a, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@3a1ffdeb, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@dbee748, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@2e7099e1, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@39da4306, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@3efe8dc7, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@107f2ff4, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@117bf31d, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@1b478992, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@224c3f63, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@3f595760, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@25e9a419, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@18d0acde, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@37396ebf, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@29ec898c, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$Ke,yData@19e768
07-27 08:54:29.476  6279  6279 D GeneralPreferenceUtils: [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
07-27 08:54:29.484  6279  6279 D Config  : [init]
,07-27 08:54:29.498  6279  6279 I Config  : LGCalendar ver.4.40.17
07-27 08:54:29.498  6279  6279 I Config  : start check model
07-27 08:54:29.498  6279  6279 I Config  : start check native_ca
07-27 08:54:29.499  6279  6279 I Config  : Config Operator=OPEN, Country=EU
07-27 08:54:29.499  6279  6279 D Config  : [setDefaultValuesToPref]
07-27 08:54:29.499  6279  6279 D Config  : [parseProfiles]
07-27 08:54:29.503  6279  6279 D ProfilesParser: [debug_displayParseInfos] profile.country = null
07-27 08:54:29.503  6279  6279 D ProfilesParser: [debug_displayParseInfos] profile.operator = null
07-27 08:54:29.503  6279  6279 D Config  : [updateProfiletoCountryInfo]
07-27 08:54:29.504  6133  6133 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
07-27 08:54:29.506  6279  6279 D GeneralPreference: [checkAndMigrateOldPreference]
,07-27 08:54:29.533  6199  6199 I NotificationManager: com.google.android.apps.plus: cancel(10436) by com.google.android.apps.plus
,07-27 08:54:29.596   862  4426 I ActivityManager: Process com.lge.bnr (pid 5579) has died
,07-27 08:54:29.598  6133  6157 W art     : Suspending all threads took: 10.917ms
,07-27 08:54:29.624  6279  6279 E AgendaWidgetManager: [updateWidgets] 
,07-27 08:54:29.633  6279  6299 I InitNotificationRingtoneService: Start InitializeAlertRingtoneService.onHandleIntent
07-27 08:54:29.644  6279  6299 I AlertUtils: [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,07-27 08:54:29.677  1757  1757 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 08:54:29.693  6279  6299 I AlertUtils: [getCalendarNotiSoundURIFromCursor] getCount()= 21
,07-27 08:54:29.698  1757  6219 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:29.699  1757  6219 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:54:29.699  1757  6219 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:29.700  1757  6219 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:54:29.701   275   910 E BandwidthController: [LG DATA] No such appUid: 10006
07-27 08:54:29.701   275   910 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-27 08:54:29.701   275  6302 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-27 08:54:29.701   275  6302 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:54:29.702   275  6302 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-27 08:54:29.702   275  6302 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-27 08:54:29.709   862   901 I NotificationManager: android: cancelAsUser(2145784878) by android
,07-27 08:54:29.737  6133  6133 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
07-27 08:54:29.739  6133  6133 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2a43878f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,07-27 08:54:29.742  6133  6133 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
07-27 08:54:29.742  6133  6133 D AndroidMusic: GMSCore installation verified
07-27 08:54:29.747   275  6302 D libc-netbsd: res_queryN name = xxxxx succeed
07-27 08:54:29.748  1757  6219 I System.out: propertyValue:false
07-27 08:54:29.773  6133  6133 I ConfigStore: Config Database version: 1
,07-27 08:54:29.827  1757  6219 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:29.827  1757  6219 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-27 08:54:29.875   862   881 I art     : Explicit concurrent mark sweep GC freed 52959(2MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 23MB/35MB, paused 2.615ms total 197.003ms
,07-27 08:54:29.875   862  1853 I ActivityManager: Process com.android.settings (pid 5885) has died
07-27 08:54:29.881  6279  6299 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
07-27 08:54:29.891  6279  6299 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,07-27 08:54:29.898  6279  6299 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
07-27 08:54:29.902  6279  6299 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
07-27 08:54:29.917  6279  6299 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
07-27 08:54:29.923  6279  6299 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,07-27 08:54:29.927  6279  6299 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
07-27 08:54:29.933  6279  6299 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
07-27 08:54:29.933   862  1906 I NotificationManager: android: cancelAsUser(2) by android
07-27 08:54:29.939   862  2008 I ActivityManager: Start proc com.google.android.play.games.ui for service com.google.android.play.games/com.google.android.gms.games.service.PlayGamesBridgeService: pid=6304 uid=10085 gids={50085, 9997} abi=armeabi-v7a
,07-27 08:54:29.960  6279  6299 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,07-27 08:54:29.969  6279  6299 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
07-27 08:54:29.974  6279  6299 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
07-27 08:54:29.975  6279  6279 D MonthWidgetProvider: [onReceive]
07-27 08:54:29.975  6279  6279 D CalendarWidgetProvider: [onReceive]
07-27 08:54:29.975  6279  6279 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
07-27 08:54:29.977  6279  6279 D CalendarTypeController: [onUpdateAndInitCalendarTime]
,07-27 08:54:29.979  6279  6314 W HolidayIntentService: onHandleIntent
07-27 08:54:29.980  6279  6279 D WeekWidgetProvider: [onReceive]
07-27 08:54:29.980  6279  6279 D CalendarWidgetProvider: [onReceive]
07-27 08:54:29.980  6279  6279 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
07-27 08:54:29.981  6279  6279 D CalendarTypeController: [onUpdateAndInitCalendarTime]
07-27 08:54:29.982  6279  6314 D HolidayDataLoader: readJsonAsset : holiday.json
07-27 08:54:29.989  6279  6299 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
07-27 08:54:29.998  6279  6299 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,07-27 08:54:30.005  6279  6299 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
07-27 08:54:30.009  2847  2847 D WeatherAncestor: 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 8:54:30
07-27 08:54:30.013  2847  2847 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,07-27 08:54:30.020  2847  2847 D Weather_cast: 2 : set auto-update time : 7/27 11:54
07-27 08:54:30.022  6279  6299 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
07-27 08:54:30.022  6279  6299 I AlertUtils: [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
07-27 08:54:30.027  6279  6299 I AlertUtils: set default noti to content://media/internal/audio/media/38
07-27 08:54:30.029  5349  5496 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:30.029  5349  5496 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:54:30.029  5349  5496 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:30.029  5349  5496 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:54:30.030   275   910 E BandwidthController: [LG DATA] No such appUid: 10006
07-27 08:54:30.030   275   910 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-27 08:54:30.030   275  6325 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-27 08:54:30.030   275  6325 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,07-27 08:54:30.030   275  6325 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-27 08:54:30.030   275  6325 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-27 08:54:30.031   275  6325 D libc-netbsd: res_queryN name = xxxxx succeed
07-27 08:54:30.032  5349  5496 I System.out: propertyValue:false
07-27 08:54:30.037  2847  2847 D WeatherAncestor: 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 8:54:30
07-27 08:54:30.037  2847  2847 D WeatherService: 2 : onStartCommand, intent!=null, action: android.intent.action.TIME_SET
,07-27 08:54:30.048  6279  6299 I InitNotificationRingtoneService: End InitializeAlertRingtoneService.onHandleIntent
,07-27 08:54:30.096   862  1853 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6326 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
07-27 08:54:30.097  6279  6314 E HolidayIntentService: onHandleIntent:holiday data empty
,07-27 08:54:30.099   862  1938 W ActivityManager: getTasks: caller 10074 does not hold GET_TASKS; limiting output
07-27 08:54:30.099  2847  2847 D Weather.Utils: 2 : Utils getTopActivity com.lge.launcher2 / true
07-27 08:54:30.102   862   901 I NotificationManager: android: cancelAsUser(-591465577) by android
07-27 08:54:30.108  5716  5809 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-27 08:54:30.108  5716  5809 I jxcore-log: 
07-27 08:54:30.108   305   305 I art     : Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 329us total 24.694ms
,07-27 08:54:30.129  2847  2847 D WeatherService: 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
07-27 08:54:30.129  2847  2847 D WeatherService: 2 : shouldTimeTickRegistered : true - home screen widget is shown.
07-27 08:54:30.131   305   305 I art     : Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 22.111ms
07-27 08:54:30.140   862   901 I NotificationManager: android: cancelAsUser(353845882) by android
,07-27 08:54:30.170  5716  5809 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-27 08:54:30.170  5716  5809 I jxcore-log: 
07-27 08:54:30.179   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 325us total 22.311ms
,07-27 08:54:30.181  5716  5809 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-27 08:54:30.181  5716  5809 I jxcore-log: 
,07-27 08:54:30.216  6326  6326 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1469602470216
07-27 08:54:30.217  6326  6326 D         : TimeServiceNative: User Time to be set is 1469602470216
07-27 08:54:30.217  6326  6326 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
07-27 08:54:30.217  6326  6326 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
07-27 08:54:30.217  6326  6326 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1469602470216
07-27 08:54:30.217  6326  6326 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
07-27 08:54:30.219   323  1067 D QC-time-services: Daemon: Connection accepted:time_genoff
07-27 08:54:30.220   323  6343 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1469602470216
07-27 08:54:30.220   323  6343 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1469602470216, operation = 0
07-27 08:54:30.220   323  6343 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS11/8/70 10:55:6
07-27 08:54:30.220   323  6343 D QC-time-services: Daemon:Value read from RTC seconds = 29501706000
07-27 08:54:30.220   323  6343 D QC-time-services: Daemon:new time 1469602470216 
07-27 08:54:30.220   323  6343 D QC-time-services: Daemon: delta 1440100764216 genoff 1440100764216 
07-27 08:54:30.220   323  6343 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1440100764216 to memory
07-27 08:54:30.220   323  6343 D QC-time-services: Daemon:Opening File: /data/time/ats_2
07-27 08:54:30.220   323  6343 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
07-27 08:54:30.225   242   242 E lowmemorykiller: Error writing /proc/5955/oom_score_adj; errno=22
,07-27 08:54:30.225  5716  5809 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-27 08:54:30.225  5716  5809 I jxcore-log: 
,07-27 08:54:30.232   323  6343 D QC-time-services: Updating the TOD offset
07-27 08:54:30.232   323  6343 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1440100764216 to memory
07-27 08:54:30.232   323  6343 D QC-time-services: Daemon:Opening File: /data/time/ats_1
07-27 08:54:30.232   323  6343 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
07-27 08:54:30.237  5716  5809 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-27 08:54:30.237  5716  5809 I jxcore-log: 
,07-27 08:54:30.239   323  6343 E QC-time-services: Daemon:Update to modem bit set
07-27 08:54:30.239   323  6343 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
,07-27 08:54:30.239   323  6343 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1124135964216
07-27 08:54:30.240  6326  6326 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
07-27 08:54:30.243   323  1065 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
07-27 08:54:30.243   323  1067 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
07-27 08:54:30.346   862  1853 I ActivityManager: Process com.lge.settings.easy (pid 5955) has died
,07-27 08:54:30.376   862   901 I NotificationManager: android: cancelAsUser(-1597574061) by android
,07-27 08:54:30.484   862  2370 I NotificationManager: android: cancelAsUser(2) by android
,07-27 08:54:30.530  5349  6266 I GamesSyncAdapter: Sync duration for 3a3529a: 1686
,07-27 08:54:30.542  1757  6219 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,07-27 08:54:30.559  1757  6219 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,07-27 08:54:30.559  1757  6219 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:54:30.559  1757  6219 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:30.559  1757  6219 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:54:30.559   275   910 E BandwidthController: [LG DATA] No such appUid: 10006
07-27 08:54:30.559   275   910 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-27 08:54:30.560   275  6358 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-27 08:54:30.560   275  6358 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:54:30.560   275  6358 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-27 08:54:30.560   275  6358 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-27 08:54:30.592  6133  6133 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,07-27 08:54:30.596   275  6358 D libc-netbsd: res_queryN name = xxxxx succeed
07-27 08:54:30.597  1757  6219 I System.out: propertyValue:false
07-27 08:54:30.599  6199  6349 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 08:54:30.624  6133  6133 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,07-27 08:54:30.669  6133  6133 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,07-27 08:54:30.690  5349  6266 E PopupManager: No content view usable to display popups. Popups will not be displayed in response to this client's calls. Use setViewForPopups() to set your content view.
,07-27 08:54:30.718  5349  6352 I art     : Explicit concurrent mark sweep GC freed 28775(2MB) AllocSpace objects, 32(535KB) LOS objects, 24% free, 15MB/20MB, paused 3.289ms total 267.659ms
07-27 08:54:30.719  5349  5363 I art     : WaitForGcToComplete blocked for 50.385ms for cause Background
,07-27 08:54:30.727   862  1923 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=6367 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,07-27 08:54:30.776  5349  5349 D PlayCommon: [1] DfeRequest.deliverResponse: Not delivering second response for request=[[ ] https://android.clients.google.com/fdfe/api/experiments 0xe8d195d1 NORMAL 1]
,07-27 08:54:30.782  6304  6345 I NotificationManager: com.google.android.play.games: cancel(10436) by com.google.android.play.games
,07-27 08:54:30.824  6199  6364 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:30.824  6199  6364 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
07-27 08:54:30.824   275   910 E BandwidthController: [LG DATA] No such appUid: 10086
07-27 08:54:30.824   275   910 D DnsProxyListener: App 10086 tries DNS query. Accept family:2 protocol:0
07-27 08:54:30.824   275  6391 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-27 08:54:30.824   275  6391 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
07-27 08:54:30.825   275  6391 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-27 08:54:30.825   275  6391 D libc-netbsd: res_queryN name = xxxxx succeed
07-27 08:54:30.835  5349  6387 W GamesServiceBroker: Client connected with SDK 8487000, Services 9256236, and Games 37240036
,07-27 08:54:30.882  6133  6157 I art     : CheckpointMarkThreadRoots callback created = 0xb042d3f0
,07-27 08:54:30.894  6133  6133 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,07-27 08:54:30.929  6133  6157 I art     : CheckpointMarkThreadRoots callback created = 0xb042d3d0
,07-27 08:54:31.000  6367  6367 V [BNRBootReceiver]: boot receiver action = android.intent.action.TIME_SET
,07-27 08:54:31.011  6367  6367 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setHomeBadgeCount:192 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:225 
07-27 08:54:31.021  1368  1368 D KeyguardModel: mReceiver, received action: android.intent.action.BADGE_COUNT_UPDATE, sendingUserId:0
07-27 08:54:31.021  1368  1368 D KeyguardModel: ACTION_GENERAL_UPDATE_NOTIFICATION received! package: com.lge.bnr.launcher, class: com.lge.bnr.launcher.BNRLauncherActivity, unread_count: 0
,07-27 08:54:31.032  6133  6133 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
07-27 08:54:31.034  1329  1329 I QuickCircle: onReceive :Intent { act=android.intent.action.BADGE_COUNT_UPDATE flg=0x10 (has extras) }, sComponents:[com.coremobility.app.vnotes.CM_VnoteInbox, com.android.contacts.activities.DialtactsActivity, com.android.contacts.DialtactsRecentCallsEntryActivity, com.lge.vvm.authmanager.VvmAuthManagerActivity, com.lge.email.ui.setupwizard.Welcome, com.skt.prod.dialer.activities.main.MainActivity, com.android.mms.ui.ConversationList, com.lge.message.ui.ConversationList, com.lge.message.activity.MainMenuActivity, com.skt.skaf.A000Z00040.A000Z00040, com.lge.updatecenter.UpdateCenterPrfActivity, com.lge.bnr.launcher.BNRLauncherActivity]
07-27 08:54:31.047  1368  1368 D KeyguardModel: putThirdPartyNotificationIntoList Number: 0 Id: 12 UserId: 0
,07-27 08:54:31.062  6367  6367 I NotificationManager: com.lge.bnr: cancel(10) by com.lge.bnr
,07-27 08:54:31.064  6162  6162 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
07-27 08:54:31.066  6367  6367 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:230 com.lge.bnr.service.BNRBootReceiver.onReceive:121 
07-27 08:54:31.068  6367  6367 V [BNRBootReceiver]: Boot Receiver Return
07-27 08:54:31.069  6367  6367 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-27 08:54:31.085  6133  6133 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-27 08:54:31.112  5349  6366 I NotificationManager: com.google.android.gms: cancel(10436) by com.google.android.gms
,07-27 08:54:31.196   862  1906 I ActivityManager: Process com.lge.sync (pid 5931) has died
,07-27 08:54:31.281   862  4426 I ActivityManager: Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6401 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,07-27 08:54:31.359  6133  6232 I NotificationManager: com.google.android.music: cancel(1061) by com.google.android.music
,07-27 08:54:31.407  1757  1757 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 08:54:31.422  6162  6162 I HubEmail: JNI_OnLoad()
07-27 08:54:31.422  6162  6162 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-27 08:54:31.422  6162  6162 I HubEmail: registerNatives()
07-27 08:54:31.422  6162  6162 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-27 08:54:31.422  6162  6162 I HubEmail: registerNativeMethods()
07-27 08:54:31.422  6162  6162 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
07-27 08:54:31.422  6162  6162 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,07-27 08:54:31.436   862   901 I NotificationManager: android: cancelAsUser(-1548111331) by android
,07-27 08:54:31.441   862  1853 I ActivityManager: Killing 6045:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
07-27 08:54:31.442  6162  6420 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:31.470  5349  6419 W InstanceID/Rpc: Found 10006
,07-27 08:54:31.470  6019  6019 W System.err: android.os.DeadObjectException
07-27 08:54:31.478  6019  6019 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-27 08:54:31.478  6019  6019 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-27 08:54:31.478  6019  6019 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
07-27 08:54:31.478  6019  6019 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
07-27 08:54:31.478  6019  6019 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
07-27 08:54:31.478  6019  6019 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
07-27 08:54:31.478  6019  6019 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-27 08:54:31.478  6019  6019 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 08:54:31.478  6019  6019 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-27 08:54:31.478  6019  6019 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
07-27 08:54:31.478  6019  6019 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:54:31.478  6019  6019 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 08:54:31.478  6019  6019 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
07-27 08:54:31.478  6019  6019 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
07-27 08:54:31.478  6019  6019 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
07-27 08:54:31.479  6019  6019 W System.err: android.os.DeadObjectException
07-27 08:54:31.479  6019  6019 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
07-27 08:54:31.479  6019  6019 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
07-27 08:54:31.479  6019  6019 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
07-27 08:54:31.479  6019  6019 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
07-27 08:54:31.479  6019  6019 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
07-27 08:54:31.479  6019  6019 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
07-27 08:54:31.479  6019  6019 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-27 08:54:31.479  6019  6019 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 08:54:31.479  6019  6019 W System.err: 	at android.os.Looper.loop(Looper.java:135)
,07-27 08:54:31.479  6019  6019 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
07-27 08:54:31.479  6019  6019 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:54:31.479  6019  6019 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 08:54:31.479  6019  6019 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
07-27 08:54:31.479  6019  6019 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
07-27 08:54:31.479  6019  6019 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
07-27 08:54:31.688   862  1938 W libprocessgroup: failed to open /acct/uid_10089/pid_6045/cgroup.procs: No such file or directory
07-27 08:54:31.688   862  1938 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,07-27 08:54:31.694  6401  6401 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
07-27 08:54:31.697  6401  6401 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
07-27 08:54:31.700  6401  6401 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
07-27 08:54:31.747   862  1853 I ActivityManager: Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6425 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-27 08:54:31.750  6401  6401 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
07-27 08:54:31.832  6401  6441 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,07-27 08:54:31.838  6401  6441 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
07-27 08:54:31.846   862  2370 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6445 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,07-27 08:54:31.884   862  4426 I ActivityManager: Killing 6019:com.lge.qremote/u0a106 (adj 15): empty #11
,07-27 08:54:31.916  6401  6440 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,07-27 08:54:31.920  6401  6440 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
07-27 08:54:31.925  6425  6425 D UEI.SmartControl: Quickset Services start...
07-27 08:54:31.928  6425  6425 I UEI.SmartControl: Manufacture = LGE
07-27 08:54:31.935  6425  6425 D UEI.SmartControl: File observer start...
,07-27 08:54:31.938  6425  6425 E UEI.SmartControl: IR Port is disabled: false
07-27 08:54:31.938  6425  6425 D UEI.SmartControl: Starting file observer...
07-27 08:54:31.938  6425  6425 D UEI.SmartControl: Extracting JNI libs...
07-27 08:54:31.939  6425  6425 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
07-27 08:54:31.980  6425  6425 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
07-27 08:54:31.981  6425  6425 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
07-27 08:54:31.981  6425  6425 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,07-27 08:54:32.029  6425  6425 I UEI.SmartControl: --- Selecting new region: 2
07-27 08:54:32.030  6425  6425 I UEI.SmartControl: -- Running on KitKat(19) and above! JNI will be used.
,07-27 08:54:32.047  6425  6425 D UEI.SmartControl: Platform has CIR...
,07-27 08:54:32.052  6425  6425 D UEI.SmartControl: NO CIR support, need to check package...
07-27 08:54:32.054  6425  6425 I UEI.SmartControl: Model: LG-D722 uses JNI
07-27 08:54:32.057  6425  6425 D UEI.SmartControl: QS Service created
07-27 08:54:32.061   862  1851 W libprocessgroup: failed to open /acct/uid_10106/pid_6019/cgroup.procs: No such file or directory
,07-27 08:54:32.072  6401  6440 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
07-27 08:54:32.087  6401  6401 E LGDMClient: [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,07-27 08:54:32.099  6401  6401 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
07-27 08:54:32.100  6401  6401 D LGDMClient: [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,07-27 08:54:32.109  6401  6401 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
07-27 08:54:32.117  6401  6401 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,07-27 08:54:32.120   862   882 I ActivityManager: Killing 6252:com.lge.clock/u0a10 (adj 15): empty #11
07-27 08:54:32.150  6425  6425 E UEI.SmartControl: QS start get config
,07-27 08:54:32.160  6445  6445 I AppUp4:AppBoxCP: onCreate
07-27 08:54:32.161  6445  6445 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
07-27 08:54:32.186  6445  6445 I AppUp4:DB:  setFingerPrint start
,07-27 08:54:32.186  6445  6445 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
07-27 08:54:32.194  6425  6425 D UEI.SmartControl: Loading JNI Libs...
07-27 08:54:32.196  6445  6445 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
07-27 08:54:32.196  6445  6445 I AppUp4:DB:  SDK version = 21
07-27 08:54:32.196  6445  6445 I AppUp4:DB:  beforefinger == newfinger no write in DB
07-27 08:54:32.197  6425  6425 D UEI.SmartControl:  configuring local db...
07-27 08:54:32.237   862  1291 W libprocessgroup: failed to open /acct/uid_10010/pid_6252/cgroup.procs: No such file or directory
,07-27 08:54:32.240  6445  6445 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
07-27 08:54:32.250   862  1375 I ActivityManager: Killing 6279:com.android.calendar/u0a13 (adj 15): empty #11
,07-27 08:54:32.252  6445  6445 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
07-27 08:54:32.252  6445  6445 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
07-27 08:54:32.258  6445  6445 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
07-27 08:54:32.259  6445  6445 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,07-27 08:54:32.272   862   901 I NotificationManager: android: cancelAsUser(2145784878) by android
07-27 08:54:32.407   862  1970 W libprocessgroup: failed to open /acct/uid_10013/pid_6279/cgroup.procs: No such file or directory
,07-27 08:54:32.408  1757  6219 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
07-27 08:54:32.408   862  1970 I ActivityManager: Killing 6326:com.qualcomm.timeservice/1000 (adj 15): empty #11
07-27 08:54:32.427  6425  6425 D UEI.SmartControl:  ---- Has DB8: true
,07-27 08:54:32.435  6425  6425 D UEI.SmartControl: QS start statue = true Error code = 0
07-27 08:54:32.435  6425  6425 D UEI.SmartControl: QS version = v2.7.11.1_RC1
07-27 08:54:32.436  6425  6425 D UEI.SmartControl: QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
07-27 08:54:32.441  6425  6425 D UEI.SmartControl: IRRCDataComm has AudioManager!!!!.
,07-27 08:54:32.450  6425  6425 W irrc_jni: IRRCPlayer_nativeInit ++ 
07-27 08:54:32.450  6425  6425 D irrcClient: IrrcClient ++ 
07-27 08:54:32.450  6425  6425 D irrcClient: getIrrcService ++ 
07-27 08:54:32.451  6425  6425 D irrcClient: getIrrcService -- 
07-27 08:54:32.451  6425  6425 D irrcClient: IrrcClient -- 
07-27 08:54:32.451  6425  6425 W irrc_jni: IRRCPlayer_nativeInit -- 
,07-27 08:54:32.458  6425  6425 D UEI.SmartControl: Services init done
07-27 08:54:32.460  6425  6475 I UEI.SmartControl: Device manager: loading config....
07-27 08:54:32.466  6425  6475 D UEI.SmartControl: Config is loaded...
,07-27 08:54:32.513  6425  6474 D UEI.SmartControl:  ----- QS SDK is ready!!!
07-27 08:54:32.514  6425  6474 I UEI.SmartControl: Notify AllClients services are ready: 0
,07-27 08:54:32.539   862  1946 W libprocessgroup: failed to open /acct/uid_1000/pid_6326/cgroup.procs: No such file or directory
,07-27 08:54:32.544  6425  6425 D UEI.SmartControl: QS Service init finished
07-27 08:54:32.545  6425  6425 D UEI.SmartControl: QS Service version name: 0.1.73
07-27 08:54:32.546  6425  6425 D UEI.SmartControl: QS Service version code: 1073
07-27 08:54:32.547  6425  6425 D UEI.SmartControl: Service requested: Control
07-27 08:54:32.553  6425  6425 D UEI.SmartControl: Service.onUnbind: IControl
,07-27 08:54:32.557  6425  6425 D UEI.SmartControl: Service.onDestroy
07-27 08:54:32.557  6425  6425 D UEI.SmartControl: Shutdown IRRCPlayer... 
07-27 08:54:32.557  6445  6445 I AppUp4:CustModeStarterReceiver: onReceive
07-27 08:54:32.557  6445  6445 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
07-27 08:54:32.560  1757  6219 I PhenotypeSyncScheduler: Cancel all previously scheduled adaptive polling
07-27 08:54:32.574  6425  6425 W irrc_jni: IRRCPlayer_nativeFinalize ++ 
07-27 08:54:32.574  6425  6425 D irrcClient: ~IrrcClient ++ 
07-27 08:54:32.574  6425  6425 D irrcClient: ~IrrcClient -- 
07-27 08:54:32.574  6425  6425 W irrc_jni: IRRCPlayer_nativeFinalize -- 
07-27 08:54:32.574  6425  6425 D UEI.SmartControl: Blaster closed
07-27 08:54:32.574  6425  6425 D UEI.SmartControl: Blaster closed
07-27 08:54:32.574  6425  6425 D UEI.SmartControl: Shut down QS...
07-27 08:54:32.574  6425  6425 D UEI.SmartControl: Stopped file observer...
,07-27 08:54:32.579  6425  6425 I UEI.SmartControl: QS lib stop result = true
07-27 08:54:32.580  6425  6425 D UEI.SmartControl: QS shutdown complete
07-27 08:54:32.580  6425  6425 D UEI.SmartControl: QS Service created
07-27 08:54:32.588  6445  6445 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@b8d5900
07-27 08:54:32.588  6445  6445 D AppUp4:CustFacade: isCustomizationCompleted : false
07-27 08:54:32.597  6425  6425 E UEI.SmartControl: QS start get config
,07-27 08:54:32.619  6425  6425 D UEI.SmartControl:  configuring local db...
07-27 08:54:32.645  6445  6445 D AppUp4:CustFacade: isSimDevice : true
07-27 08:54:32.647  6445  6445 D AppUp4:CustModeStarterReceiver: begin check event
07-27 08:54:32.647  6445  6445 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
07-27 08:54:32.647  6445  6445 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,07-27 08:54:32.652  6445  6480 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
07-27 08:54:32.653  6445  6480 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
07-27 08:54:32.653  6445  6480 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
07-27 08:54:32.690  3103  3103 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
07-27 08:54:32.690  3103  3103 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,07-27 08:54:32.695  3103  3103 I LgeMiscReceiver: networkInfo.isConnected() = true
07-27 08:54:32.701  3103  3103 D PhoneState: setPdpRejectCasuse : false
07-27 08:54:32.739   862  1906 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6488 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,07-27 08:54:32.772   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 08:54:32.772   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 08:54:32.772   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 153165639530; DSPS: 5110498; Offset : -2804500461
,07-27 08:54:32.876  6425  6425 D UEI.SmartControl:  ---- Has DB8: true
07-27 08:54:32.886  6425  6425 D UEI.SmartControl: QS start statue = true Error code = 0
07-27 08:54:32.886  6425  6425 D UEI.SmartControl: QS version = v2.7.11.1_RC1
07-27 08:54:32.886  6425  6425 D UEI.SmartControl: QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
07-27 08:54:32.886  6425  6425 D UEI.SmartControl: IRRCDataComm has AudioManager!!!!.
07-27 08:54:32.886  6425  6425 W irrc_jni: IRRCPlayer_nativeInit ++ 
07-27 08:54:32.886  6425  6425 D irrcClient: IrrcClient ++ 
07-27 08:54:32.886  6425  6425 D irrcClient: getIrrcService ++ 
07-27 08:54:32.887  6425  6425 D irrcClient: getIrrcService -- 
07-27 08:54:32.887  6425  6425 D irrcClient: IrrcClient -- 
07-27 08:54:32.887  6425  6425 W irrc_jni: IRRCPlayer_nativeInit -- 
,07-27 08:54:32.887  6425  6425 D UEI.SmartControl: Services init done
07-27 08:54:32.889  6425  6425 D UEI.SmartControl: QS Service init finished
07-27 08:54:32.890  6425  6425 D UEI.SmartControl: QS Service version name: 0.1.73
07-27 08:54:32.890  6425  6425 D UEI.SmartControl: QS Service version code: 1073
07-27 08:54:32.890  6425  6425 D UEI.SmartControl: Service requested: Control
07-27 08:54:32.892   862  1970 I ActivityManager: Killing 6181:com.android.gallery3d/u0a23 (adj 15): empty #11
07-27 08:54:32.894  6425  6507 I UEI.SmartControl: Device manager: loading config....
07-27 08:54:32.896  6425  6507 D UEI.SmartControl: Config is loaded...
07-27 08:54:32.942  6425  6506 D UEI.SmartControl:  ----- QS SDK is ready!!!
07-27 08:54:32.942  6425  6506 I UEI.SmartControl: Notify AllClients services are ready: 0
,07-27 08:54:32.950   862  1017 I PowerManagerService: ALS enabled for SRE
07-27 08:54:32.950   862  1017 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (33344 ms ago)
07-27 08:54:32.953   862  1017 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,07-27 08:54:32.968   862  1017 I PowerManagerService: ALS enabled for SRE
07-27 08:54:32.969   862  1017 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (33363 ms ago)
,07-27 08:54:32.970  6488  6488 D PhoneMonitor: Register our PhoneStateListener
07-27 08:54:32.978   862  1017 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,07-27 08:54:33.043   862  2008 W libprocessgroup: failed to open /acct/uid_10023/pid_6181/cgroup.procs: No such file or directory
07-27 08:54:33.044  6425  6425 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@145014df that was originally bound here
07-27 08:54:33.044  6425  6425 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@145014df that was originally bound here
07-27 08:54:33.044  6425  6425 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
07-27 08:54:33.044  6425  6425 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
07-27 08:54:33.044  6425  6425 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
07-27 08:54:33.044  6425  6425 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
07-27 08:54:33.044  6425  6425 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
07-27 08:54:33.044  6425  6425 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
07-27 08:54:33.044  6425  6425 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
07-27 08:54:33.044  6425  6425 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
07-27 08:54:33.044  6425  6425 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
07-27 08:54:33.044  6425  6425 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
07-27 08:54:33.044  6425  6425 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
07-27 08:54:33.044  6425  6425 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:54:33.044  6425  6425 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
07-27 08:54:33.044  6425  6425 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
07-27 08:54:33.044  6425  6425 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:54:33.044  6425  6425 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 08:54:33.044  6425  6425 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
07-27 08:54:33.044  6425  6425 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,07-27 08:54:33.045  6425  6425 D UEI.SmartControl: Internal service binding...
07-27 08:54:33.051   862  1017 I PowerManagerService: Sleeping (uid 1000)...
07-27 08:54:33.051   862  1017 D LPWGController: [updateScreenState] screen on = false
07-27 08:54:33.054   862  1017 D LPWGController: disable proximity sensor
07-27 08:54:33.054   862  1017 D LPWGController: enable proximity sensor
,07-27 08:54:33.068   862  1017 I SensorManager: registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@93ba766] by com.android.server.power.ProximitySensorListener.enable():120
07-27 08:54:33.075   862  1017 I sensors_hal_Ctx: batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
07-27 08:54:33.075   862  1017 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
07-27 08:54:33.075   862  1017 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
07-27 08:54:33.075   862  1017 I sensors_hal_Ctx: activate: handle is 48, enable
07-27 08:54:33.075   862  1017 V sensors_hal_Ctx: activate sensors is 1400000000000
07-27 08:54:33.075   862  1017 D sensors_hal_Thresh: enable: handle=48
07-27 08:54:33.075   862  1017 I sensors_hal_SAM: sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
07-27 08:54:33.075   862  1017 D sensors_hal_Util: waitForResponse: timeout=1000
,07-27 08:54:33.080   862  1027 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
07-27 08:54:33.080   862  1027 D sensors_hal_Thresh: processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
07-27 08:54:33.080   862  1017 D sensors_hal_Thresh: enable: Received response: 0
07-27 08:54:33.082   862  1017 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (33476 ms ago)
07-27 08:54:33.112   862  1017 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-27 08:54:33.112   862  1017 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-27 08:54:33.112   862  1017 I Adreno-EGL: Build Date: 03/02/15 Mon
07-27 08:54:33.112   862  1017 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-27 08:54:33.112   862  1017 I Adreno-EGL: Remote Branch: 
07-27 08:54:33.112   862  1017 I Adreno-EGL: Local Patches: 
07-27 08:54:33.112   862  1017 I Adreno-EGL: Reconstruct Branch: 
,07-27 08:54:33.220   862   881 I art     : Explicit concurrent mark sweep GC freed 24042(1060KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.513ms total 162.010ms
,07-27 08:54:33.223   245  2354 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1523 us)
07-27 08:54:33.239  6488  6488 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,07-27 08:54:33.241  6488  6488 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
07-27 08:54:33.243   862  4426 I ActivityManager: Killing 6367:com.lge.bnr/1000 (adj 15): empty #11
,07-27 08:54:33.265  6488  6488 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
07-27 08:54:33.268  6488  6488 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
07-27 08:54:33.275  6488  6488 D TelephonyAutoProfiling: [parse] Load xml
,07-27 08:54:33.285  6488  6488 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
07-27 08:54:33.285  6488  6488 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,07-27 08:54:33.295  6488  6488 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
07-27 08:54:33.309   422  1018 I Sensors : sns_pwr.c(273):acquiring wakelock
07-27 08:54:33.309   295   356 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 08:54:33.310   862  1027 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
07-27 08:54:33.311   862  1027 I sensors_hal_SAM: SAMSensor_sensor1_cb: acquired wakelock sensor_ind
07-27 08:54:33.311   862  1027 D sensors_hal_Thresh: processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
07-27 08:54:33.311   862  1027 D sensors_hal_Thresh: processInd: handle 48, count=1
07-27 08:54:33.311   862  1027 V sensors_hal_Thresh: processInd:sensor android.sensor.proximity (wake_up)
07-27 08:54:33.311   862  1027 I sensors_hal_Thresh: processInd : proximity state changed - FAR
07-27 08:54:33.311   862  1054 D sensors_hal_Ctx: poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
07-27 08:54:33.311   862  1054 D sensors_hal_Ctx: poll: count: 256
07-27 08:54:33.311   862  1054 I sensors_hal_Ctx: poll: released wakelock sensor_ind
07-27 08:54:33.311   862  1054 D sensors_hal_Util: waitForResponse: timeout=0
07-27 08:54:33.341   862  2204 W libprocessgroup: failed to open /acct/uid_1000/pid_6367/cgroup.procs: No such file or directory
,07-27 08:54:33.355  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-27 08:54:33.355  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 08:54:33.356  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
,07-27 08:54:33.365   862  1017 D LPWGController: proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
07-27 08:54:33.366   862  1017 I LPWGController: current mode = 1  value = 1 1
07-27 08:54:33.367   862  1017 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
07-27 08:54:33.389  2709  2709 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,07-27 08:54:33.418  2709  2709 V DownloadManager: DownloadService onCreate
,07-27 08:54:33.424   862  1017 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
07-27 08:54:33.437  2709  6517 I DownloadManager: in removeSpuriousFiles
,07-27 08:54:33.439  2709  2709 I NotificationManager: com.android.providers.downloads: cancelAll by com.android.providers.downloads
07-27 08:54:33.448   862  1851 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6519 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
07-27 08:54:33.452  2709  6517 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,07-27 08:54:33.480  2709  2709 V DownloadManager: DownloadService onStartCommand
,07-27 08:54:33.482  2709  6517 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3336b8ea on behalf of 2709
07-27 08:54:33.484  2709  6518 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
07-27 08:54:33.488  2709  6518 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@29a037db on behalf of 2709
07-27 08:54:33.492  2709  6517 I DownloadManager: in trimDatabase
07-27 08:54:33.492  2709  6517 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
07-27 08:54:33.497  5349  6537 I CheckinService: Disabling old GoogleServicesFramework version
,07-27 08:54:33.547  2709  6517 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@189eb278 on behalf of 2709
,07-27 08:54:33.553  5349  6543 I CheckinChimeraService: Checking schedule, now: 1469602473553 next: 1469597737455
07-27 08:54:33.553  5349  6543 I CheckinChimeraService: active receiver: enabled
,07-27 08:54:33.573  5349  6543 I CheckinChimeraService: Preparing to send checkin request
07-27 08:54:33.574  5349  6543 I EventLogChimeraService: Accumulating logs since 1469601555805
,07-27 08:54:33.603  6519  6519 D DrmBroadcastReceiver: Receive CONNECTIVITY_ACTION
07-27 08:54:33.604  6519  6519 D DrmBroadcastReceiver: 1  network is available. Sync DRM Time with NTP
,07-27 08:54:33.612  2847  2847 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:54:33
07-27 08:54:33.614  6519  6519 V DrmService: Service onCreate
07-27 08:54:33.614  6519  6519 D DrmService: Received new request = 2
07-27 08:54:33.615  2847  2847 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-27 08:54:33.622  2847  2847 D WeatherAncestor: connectivity changed - connection : true
07-27 08:54:33.622  6519  6544 I DrmSntpClient: Start Sync process
07-27 08:54:33.622  6519  6544 D DrmSntpClient: Server : 0
07-27 08:54:33.627  2847  2847 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-27 08:54:33.627  2847  2847 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:54:33
,07-27 08:54:33.632  2847  2847 D WeatherService: 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
07-27 08:54:33.633  2847  2847 D WeatherService: 2 : shouldTimeTickRegistered : false
07-27 08:54:33.639  6519  6544 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:33.639  6519  6544 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:54:33.639  6519  6544 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:33.640  6519  6544 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:54:33.640   275   910 E BandwidthController: [LG DATA] No such appUid: 10051
07-27 08:54:33.640   275   910 D DnsProxyListener: App 10051 tries DNS query. Accept family:0 protocol:0
,07-27 08:54:33.640   275  6545 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-27 08:54:33.640   275  6545 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:54:33.641   275  6545 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-27 08:54:33.641   275  6545 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-27 08:54:33.649  2709  2709 V DownloadManager: DownloadService onDestroy
07-27 08:54:33.652  1757  6546 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,07-27 08:54:33.652  1757  6546 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:54:33.654  1757  6546 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:33.654  1757  6546 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:54:33.655   275   910 E BandwidthController: [LG DATA] No such appUid: 10006
07-27 08:54:33.655   275   910 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-27 08:54:33.655   275  6547 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
,07-27 08:54:33.655   275  6547 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:54:33.655   275  6547 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-27 08:54:33.656   275  6547 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-27 08:54:33.684  5349  6549 I iu.SyncManager: SYNC; picasa accounts
,07-27 08:54:33.706   275  6545 D libc-netbsd: res_queryN name = xxxxx succeed
,07-27 08:54:33.707  6519  6544 I System.out: propertyValue:false
07-27 08:54:33.709   275  6547 D libc-netbsd: res_queryN name = xxxxx succeed
07-27 08:54:33.710  1757  6546 I System.out: propertyValue:false
07-27 08:54:33.734  5349  5349 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,07-27 08:54:33.741  5349  5349 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-27 08:54:33.755  6519  6544 I LGDrmClient: _DRM_ServiceGet() : Bind lgdrm service
,07-27 08:54:33.763   284   284 V ILGDrmService: eDRM_SetDRMTime +++
07-27 08:54:33.769   862  1346 D qdlights: set_light_backlight: 0
,07-27 08:54:33.771   284   284 I LGDRM   : [DRM] SET TIME : YR=2016, MON=7, DAY=27
07-27 08:54:33.771   284   284 I LGDRM   : [DRM] SET TIME : HR=6, MIN=54, SEC=32
07-27 08:54:33.772  5349  6549 I iu.UploadsManager: num queued entries: 0
07-27 08:54:33.773  5349  6549 I iu.UploadsManager: num updated entries: 0
07-27 08:54:33.773  1757  6546 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:33.773  1757  6546 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:54:33.777  5349  6549 I iu.SyncManager: NEXT; no task
07-27 08:54:33.787   862  1017 I SensorManager: removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,07-27 08:54:33.793   862  1017 I sensors_hal_Ctx: activate: handle is 46, disable
07-27 08:54:33.793   862  1017 V sensors_hal_Ctx: activate sensors is 1000000000000
07-27 08:54:33.793   862  1017 D sensors_hal_LP2: enable: handle=46
07-27 08:54:33.793   862  1017 D sensors_hal_LP2: enable: Disabling sensor handle=46
07-27 08:54:33.793   862  1017 I sensors_hal_SAM: sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
07-27 08:54:33.798   245   245 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
07-27 08:54:33.799   245   245 D qdhwcomposer: hwc_blank: Blanking display: 0
,07-27 08:54:33.801   862  1015 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
07-27 08:54:33.801   862   862 V ActivityManager: Display changed displayId=0
07-27 08:54:33.803   284   284 V ILGDrmService: eDRM_SetDRMTime ---
07-27 08:54:33.811  6519  6544 I DrmSntpClient: Synched
,07-27 08:54:33.812  6519  6519 D DrmService: Completed !! request = 2
07-27 08:54:33.812  6519  6519 D DrmService: Request count = 0
07-27 08:54:33.819  6519  6519 V DrmService: Service onDestroy
,07-27 08:54:33.840  1787  1787 D DSDPConnection: Display #0 changed.
07-27 08:54:33.847   862  1050 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
07-27 08:54:33.847   862  1050 D sensors_hal_LP2: processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,07-27 08:54:33.857  1757  6546 I GCM     : GCM config loaded
07-27 08:54:33.890  5349  6543 I CheckinRequestBuilder: Checkin reason type: 8 attempt count: 1
,07-27 08:54:33.921   862  1375 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6558 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-27 08:54:33.923  5349  6543 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
07-27 08:54:33.994   245   245 D qdhwcomposer: hwc_blank: Done blanking display: 0
,07-27 08:54:33.995   862  1346 D SurfaceControl: Excessive delay in setPowerMode(): 195ms
07-27 08:54:33.997   862  1346 I QCOM PowerHAL: Got set_interactive hint
07-27 08:54:33.998   245   711 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
07-27 08:54:34.010  1368  1392 D KeyguardViewMediator: onScreenTurnedOff(3)
,07-27 08:54:34.014  5716  5716 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-27 08:54:34.014  5716  5716 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
07-27 08:54:34.027  1329  1345 D SmartCoverViewMediator: onScreenTurnedOff(3)
,07-27 08:54:34.031  5716  5716 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1b6acdc4 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@13f8c4c1, 16908290=android.view.AbsSavedState$1@13f8c4c1}, android:focusedViewId=100}]}]
07-27 08:54:34.031  5716  5716 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
07-27 08:54:34.033  5716  5716 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-27 08:54:34.033  5716  5716 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
07-27 08:54:34.035  1368  1392 D KeyguardViewMediator: notifyScreenOffLocked
07-27 08:54:34.044  1329  1345 D SmartCoverViewMediator: notifyScreenOffLocked
,07-27 08:54:34.044  1329  1329 D SmartCoverViewMediator: handleNotifyScreenOFF
07-27 08:54:34.051   862   862 D WifiServerServiceExt: sendKtScanInterval  mRtspPlay : false
07-27 08:54:34.054   862  1307 I WifiServerServiceExt: set CMD_KT_SCAN_INTERVAL
07-27 08:54:34.058   279  1298 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=on, calling pid 862
,07-27 08:54:34.059   279  1298 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
07-27 08:54:34.059   279  1298 V voice   : voice_set_parameters: enter: screen_state=on
07-27 08:54:34.059   279  1298 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=on
07-27 08:54:34.059   279  1298 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-27 08:54:34.059   279  1298 V voice   : voice_set_parameters: exit with code(0)
07-27 08:54:34.059   279  1298 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=on
07-27 08:54:34.059   279  1298 V msm8974_platform: platform_set_parameters: enter: screen_state=on
07-27 08:54:34.059   279  1298 V msm8974_platform: platform_set_parameters: exit with code(0)
07-27 08:54:34.059   279  1298 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-27 08:54:34.059   279  1298 E lge_audio_pcm_dump: lge_set_dump_config: exit dump_config : 0
07-27 08:54:34.059   279  1298 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
07-27 08:54:34.059   279  1298 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-27 08:54:34.062  1368  1392 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 1, timeout = 5000
07-27 08:54:34.062  1368  1368 D KeyguardViewMediator: handleNotifyScreenOff
,07-27 08:54:34.086  5385  5400 I art     : Explicit concurrent mark sweep GC freed 2725(110KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 423us total 84.459ms
,07-27 08:54:34.161  1368  1368 D ScreenTurnOffBySensor: unregisterProximitySensor
,07-27 08:54:34.166  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
07-27 08:54:34.166  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
07-27 08:54:34.166  6558  6558 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-27 08:54:34.166  1368  1368 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
07-27 08:54:34.176   862  1906 I ActivityManager: Process com.google.android.music:main (pid 6133) has died
,07-27 08:54:34.189  1368  1368 D StatusBarWindowView: onScreenTurnedOff why = 3
07-27 08:54:34.192  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 08:54:34.192  1368  1368 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_ON
,07-27 08:54:34.198   862   901 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
07-27 08:54:34.243   862  1970 D SplitWindow: check instance of lgWin Window{3adc1da2 u0 SearchPanel}
,07-27 08:54:34.249  1909  1909 I QCNEJ   : |CORE| sendScreenState: state:true
07-27 08:54:34.261  1873  2040 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
,07-27 08:54:34.266  1873  2040 D LEDService: stopPatternFlashing()
07-27 08:54:34.267  1873  2040 D qdlights: set_light_notifications: 0,0,0,0,3
07-27 08:54:34.268  1873  2040 I LEDService: getCurrentHighestLGLedRecord : size = 1
07-27 08:54:34.268  1873  2040 D qdlights: set_light_notifications: 0,0,0,0,3
07-27 08:54:34.270  5349  6576 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
07-27 08:54:34.270  5349  6576 D SchedPeriodicTask: Scheduled AdAttestation task.
07-27 08:54:34.270  1873  2040 I LEDService: updateLightsLocked : turn off led
07-27 08:54:34.270  1873  2040 D qdlights: set_light_notifications: 0,0,0,0,3
07-27 08:54:34.272   862  2204 D InputDispatcher: Window went away: Window{19a47ad6 u0 SearchPanel}
07-27 08:54:34.273  1873  2040 D LEDHandler: RESTART MSG
,07-27 08:54:34.277  1368  1368 I [SystemUI]Clock: onReceive = android.intent.action.SCREEN_ON
07-27 08:54:34.296  1368  1368 I LgeClockWidgetControlView: time changed, timezoneChanged : false
,07-27 08:54:34.306  1873  1873 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
07-27 08:54:34.307  1873  1873 D Cliptray Service: lockStatus = 0
07-27 08:54:34.316  1856  1856 D LNfcService: action : android.intent.action.SCREEN_ON
,07-27 08:54:34.333  1856  6579 D NfcServiceNXP: mScreenState : 3, mInProvisionMode : false
07-27 08:54:34.333  1856  6579 D NfcServiceNXP: Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
07-27 08:54:34.333  1856  6579 D LNfcService: isRequireNfcCRouting() return true
,07-27 08:54:34.333  1856  6579 D LNfcService: isHCERoutingtoHost() return : true
07-27 08:54:34.333  1856  6579 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
07-27 08:54:34.333  1856  6579 D NfcService: mEnableLPD: true
07-27 08:54:34.333  1856  6579 D NfcService: mEnableReader: false
07-27 08:54:34.333  1856  6579 D NfcService: mEnableHostRouting: true
07-27 08:54:34.333  1856  6579 D NfcService: newParams.techmask= mTechMask: default
07-27 08:54:34.333  1856  6579 D NfcService: mEnableLPD: true
07-27 08:54:34.333  1856  6579 D NfcService: mEnableReader: false
07-27 08:54:34.333  1856  6579 D NfcService: mEnableHostRouting: true
07-27 08:54:34.333  1856  6579 D NfcService: screenState= 3
07-27 08:54:34.333  1856  6579 D NfcService: Discovery configuration equal, not updating.
07-27 08:54:34.334   862   862 D Ulp_jni : JNI:system_update. Event-0
,07-27 08:54:34.348  1787  1787 V PhoneApp: onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,07-27 08:54:34.410  2847  2847 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 8:54:34
,07-27 08:54:34.413  2847  2847 D WeatherService: 2 : ACTION screen on
07-27 08:54:34.413  2847  2847 D WeatherService: 2 : shouldTimeTickRegistered : false
07-27 08:54:34.415  2847  2847 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
07-27 08:54:34.415  2847  2847 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 8:54:34
07-27 08:54:34.425  3870  3870 D AppCleanupService: android.intent.action.SCREEN_ON
,07-27 08:54:34.439   862   862 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:34.439   862   862 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:34.439   862   862 D WifiOffDelayIfNotUsed: ACTION_SCREEN_ON
,07-27 08:54:34.446   279  1321 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=off, calling pid 862
07-27 08:54:34.446   279  1321 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
07-27 08:54:34.447   279  1321 V voice   : voice_set_parameters: enter: screen_state=off
07-27 08:54:34.447   279  1321 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=off
07-27 08:54:34.447   279  1321 V compress_voip: voice_extn_compress_voip_set_parameters: exit
07-27 08:54:34.447   279  1321 V voice   : voice_set_parameters: exit with code(0)
07-27 08:54:34.447   279  1321 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=off
07-27 08:54:34.447   279  1321 V msm8974_platform: platform_set_parameters: enter: screen_state=off
07-27 08:54:34.447   279  1321 V msm8974_platform: platform_set_parameters: exit with code(0)
07-27 08:54:34.447   279  1321 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
07-27 08:54:34.447   279  1321 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
07-27 08:54:34.447   279  1321 V audio_hw_primary: adev_set_parameters: exit with code(0)
07-27 08:54:34.448   862  1312 D WifiController: CMD_SCREEN_OFF 
07-27 08:54:34.449   862  1312 D WifiController: shouldWifiStayAwake TRUE
,07-27 08:54:34.457  1368  1368 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_OFF
,07-27 08:54:34.459   862   901 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
07-27 08:54:34.535   862   881 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6583 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,07-27 08:54:34.573  1909  1909 I QCNEJ   : |CORE| sendScreenState: state:false
07-27 08:54:34.574  1873  2040 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
07-27 08:54:34.574  1873  2040 D LEDService: stopPatternFlashing()
07-27 08:54:34.575  1873  2040 D qdlights: set_light_notifications: 0,0,0,0,3
07-27 08:54:34.576  1873  2040 I LEDService: getCurrentHighestLGLedRecord : size = 1
07-27 08:54:34.576  1873  2040 D qdlights: set_light_notifications: 0,0,0,0,3
07-27 08:54:34.577  1873  1873 D VolumeVibrator: clear
07-27 08:54:34.578  1873  2040 I LEDService: updateLightsLocked : turn on led
07-27 08:54:34.579  1873  2040 E LEDService: parsePattern()::Unknown Pattern ID or invalid PatternFilePath
07-27 08:54:34.579  1873  2040 E LEDService: Can't handle this request of patternId:0
07-27 08:54:34.579  1873  2040 D LEDHandler: RESTART MSG
07-27 08:54:34.581  1873  1873 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
07-27 08:54:34.582  1856  1856 D LNfcService: action : android.intent.action.SCREEN_OFF
,07-27 08:54:34.595  1856  2214 D NfcServiceNXP: mScreenState : 1, mInProvisionMode : false
07-27 08:54:34.608  1947  1947 I [LGHome]EVENT: [Launcher.java:1711:onReceive()]Screen Off
,07-27 08:54:34.625  1787  1787 V PhoneApp: onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,07-27 08:54:34.632  2847  2847 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 8:54:34
07-27 08:54:34.632  2847  2847 D WeatherService: 2 : ACTION screen off
07-27 08:54:34.635  2847  2847 D WeatherService: 2 : TimeTick Receiver Unregister
07-27 08:54:34.635  2847  2847 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 8:54:34
07-27 08:54:34.642  3870  3870 D AppCleanupService: android.intent.action.SCREEN_OFF
07-27 08:54:34.644  3870  6602 D AppCleanupService: AppUsageStatsSaveTask
,07-27 08:54:34.659   862   862 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:34.659   862   862 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 08:54:34.659   862   862 D WifiOffDelayIfNotUsed: ACTION_SCREEN_OFF
,07-27 08:54:34.701  1856  2674 E NxpNfcJni: getReconnectState = 0x0
,07-27 08:54:34.705  1856  2214 D LCardEmulationManager: getHceAppCount hostAppNum : 0
07-27 08:54:34.705  1856  2214 D LCardEmulationManager: getDefaultRoute
07-27 08:54:34.707  1856  2214 D LNfcService: isRequireNfcCRouting() return true
07-27 08:54:34.707  1856  2214 D LNfcService: isHCERoutingtoHost() return : true
07-27 08:54:34.708  1856  2214 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
07-27 08:54:34.708  1856  2214 D NfcService: mEnableLPD: true
07-27 08:54:34.708  1856  2214 D NfcService: mEnableReader: false
07-27 08:54:34.708  1856  2214 D NfcService: mEnableHostRouting: true
07-27 08:54:34.708  1856  2214 D NfcService: newParams.techmask= mTechMask: 0
07-27 08:54:34.708  1856  2214 D NfcService: mEnableLPD: true
07-27 08:54:34.708  1856  2214 D NfcService: mEnableReader: false
07-27 08:54:34.708  1856  2214 D NfcService: mEnableHostRouting: true
07-27 08:54:34.708  1856  2214 D NfcService: screenState= 1
07-27 08:54:34.731  6583  6583 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-27 08:54:34.731  6583  6583 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-27 08:54:34.766  1856  2674 E NxpNfcJni: getReconnectState = 0x0
,07-27 08:54:34.780   862  2008 I ActivityManager: Process com.lge.email (pid 6162) has died
,07-27 08:54:34.790  6583  6583 I MultiDex: VM with version 2.1.0 has multidex support
07-27 08:54:34.790  6583  6583 I MultiDex: install
07-27 08:54:34.790  6583  6583 I MultiDex: VM has multidex support, MultiDex support library is disabled.
07-27 08:54:34.809   422   434 I Sensors : sns_pwr.c(301):releasing wakelock
,07-27 08:54:34.848  6583  6583 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-27 08:54:34.866  6558  6609 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
07-27 08:54:34.866  6558  6609 I Babel_SMS: MmsConfig.loadMmsSettings
07-27 08:54:34.869  6558  6609 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
07-27 08:54:34.869  6558  6609 I Babel_SMS: MmsConfig.loadFromDatabase
07-27 08:54:34.869  5716  5809 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-27 08:54:34.869  5716  5809 I jxcore-log: 
,07-27 08:54:34.890  5716  5809 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-27 08:54:34.890  5716  5809 I jxcore-log: 
,07-27 08:54:34.905  5716  5809 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-27 08:54:34.905  5716  5809 I jxcore-log: 
,07-27 08:54:34.913  6583  6583 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
07-27 08:54:34.914  6583  6583 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3324dd8d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
07-27 08:54:34.914  6583  6583 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
07-27 08:54:34.917  6583  6583 I NotificationManager: com.google.android.gms: cancel(10436) by com.google.android.gms
07-27 08:54:34.918  6583  6583 I NotificationManager: com.google.android.gms: cancel(39789) by com.google.android.gms
07-27 08:54:34.930  6583  6583 D ChimeraCfgMgr: Reading stored module config
,07-27 08:54:34.962  6558  6609 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
07-27 08:54:34.962  6558  6609 I Babel_SMS: MmsConfig.loadFromResources
07-27 08:54:34.965  6558  6609 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
07-27 08:54:34.971  6558  6609 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,07-27 08:54:35.046  6583  6598 W art     : Suspending all threads took: 10.467ms
,07-27 08:54:35.047  6558  6572 I art     : CheckpointMarkThreadRoots callback created = 0xb042d8a0
,07-27 08:54:35.077  6583  6598 I art     : Background sticky concurrent mark sweep GC freed 19066(936KB) AllocSpace objects, 3(183KB) LOS objects, 7% free, 10MB/11MB, paused 26.122ms total 96.737ms
07-27 08:54:35.078  6558  6572 I art     : CheckpointMarkThreadRoots callback created = 0xaae47db0
,07-27 08:54:35.124  6583  6583 I art     : Rejecting re-init on previously-failed class java.lang.Class<inz>
,07-27 08:54:35.126  6583  6583 I art     : Rejecting re-init on previously-failed class java.lang.Class<inz>
07-27 08:54:35.131  6583  6612 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,07-27 08:54:35.155  6558  6558 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
07-27 08:54:35.155  6558  6558 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
07-27 08:54:35.155  6558  6558 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
07-27 08:54:35.155  6558  6558 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
07-27 08:54:35.155  6558  6558 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
07-27 08:54:35.155  6558  6558 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
07-27 08:54:35.155  6558  6558 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
07-27 08:54:35.155  6558  6558 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
07-27 08:54:35.155  6558  6558 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
07-27 08:54:35.155  6558  6558 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
07-27 08:54:35.155  6558  6558 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
07-27 08:54:35.155  6558  6558 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
07-27 08:54:35.155  6558  6558 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
07-27 08:54:35.156  6558  6558 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
07-27 08:54:35.156  6558  6558 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
07-27 08:54:35.156  6558  6558 D SensorManager: found sensor: Motion Accel, handle=46
,07-27 08:54:35.176   862  1851 I ActivityManager: Process com.google.android.play.games.ui (pid 6304) has died
,07-27 08:54:35.231  6558  6558 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:54:35.234  6558  6558 I Babel_Crash: startup - clean
,07-27 08:54:35.252  6583  6598 I art     : CheckpointMarkThreadRoots callback created = 0xb042d370
,07-27 08:54:35.267  5716  5809 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-27 08:54:35.267  5716  5809 I jxcore-log: 
07-27 08:54:35.277   279  1298 D WVCdm   : Instantiating CDM.
07-27 08:54:35.278   279   279 I WVCdm   : CdmEngine::OpenSession
07-27 08:54:35.278   279   279 I WVCdm   : Level3 Library Dec 11 2014 16:13:16
,07-27 08:54:35.284  6583  6598 I art     : CheckpointMarkThreadRoots callback created = 0xb042d360
07-27 08:54:35.310  6558  6619 I Babel   : deleted: false for 0
,07-27 08:54:35.371   279   279 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
07-27 08:54:35.371   279   279 W WVCdm   : Properties::GetOEMCryptoPath: null. applies level3
07-27 08:54:35.371   279   279 W WVCdm   : L1 library not specified. Falling Back to L3
07-27 08:54:35.374  6583  6615 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:35.374  6583  6615 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:54:35.375  6583  6615 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:35.375  6583  6615 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:54:35.375   275   910 E BandwidthController: [LG DATA] No such appUid: 10006
07-27 08:54:35.375   275   910 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
,07-27 08:54:35.376   275  6622 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-27 08:54:35.376   275  6622 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:54:35.376   275  6622 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-27 08:54:35.377   275  6622 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-27 08:54:35.377   275  6622 D libc-netbsd: res_queryN name = xxxxx succeed
07-27 08:54:35.377  6583  6615 I System.out: propertyValue:false
07-27 08:54:35.470   279   279 I WVCdm   : CdmEngine::QueryKeyControlInfo
,07-27 08:54:35.471   279  1606 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
07-27 08:54:35.471   279  1606 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
07-27 08:54:35.471   279  1606 I WVCdm   : CdmEngine::GenerateKeyRequest
07-27 08:54:35.477   279  1606 D WVCdm   : PrepareKeyRequest: nonce=1087702317
07-27 08:54:35.527  6583  6615 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:35.527  6583  6615 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-27 08:54:35.673   279   279 I WVCdm   : CdmEngine::OpenSession
,07-27 08:54:35.700   862  1883 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6625 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-27 08:54:35.774  6558  6558 W AudioCapabilities: Unsupported mime audio/x-lg-flac
,07-27 08:54:35.792  6558  6558 W AudioCapabilities: Unsupported mime audio/adpcm
,07-27 08:54:35.793  6558  6558 W AudioCapabilities: Unsupported mime audio/g726
07-27 08:54:35.795  6558  6558 W AudioCapabilities: Unsupported mime audio/x-ms-wma
07-27 08:54:35.797  6558  6558 W AudioCapabilities: Unsupported mime audio/wma-voice
07-27 08:54:35.805  6558  6558 W VideoCapabilities: Unsupported mime video/mjpg
,07-27 08:54:35.835  6558  6558 W VideoCapabilities: Unsupported mime video/theora
,07-27 08:54:35.877  6558  6558 W AudioCapabilities: Unsupported mime audio/evrc
,07-27 08:54:35.882  6558  6558 W AudioCapabilities: Unsupported mime audio/qcelp
07-27 08:54:35.884  6558  6558 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-27 08:54:35.897  6558  6558 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
07-27 08:54:35.899  6558  6558 W AudioCapabilities: Unsupported mime audio/qcelp
,07-27 08:54:35.907  6558  6558 W AudioCapabilities: Unsupported mime audio/evrc
07-27 08:54:35.932  6558  6558 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,07-27 08:54:35.960  6558  6558 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-27 08:54:35.982  6558  6558 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-27 08:54:35.984  6558  6558 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-27 08:54:35.997  6558  6558 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-27 08:54:36.003  6558  6558 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-27 08:54:36.014  6558  6558 I vclib   : onServiceConnected
07-27 08:54:36.015  6558  6558 W Babel   : Attempted to change video mute state without an active call.
,07-27 08:54:36.060  6558  6558 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
,07-27 08:54:36.060  6558  6643 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:36.061  6558  6643 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:54:36.061  6558  6643 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:36.061  6558  6643 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:54:36.061   275   910 E BandwidthController: [LG DATA] No such appUid: 10061
07-27 08:54:36.061   275   910 D DnsProxyListener: App 10061 tries DNS query. Accept family:0 protocol:0
07-27 08:54:36.062   275  6646 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-27 08:54:36.062   275  6646 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:54:36.062   275  6646 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-27 08:54:36.062   275  6646 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-27 08:54:36.063   275  6646 D libc-netbsd: res_queryN name = xxxxx succeed
07-27 08:54:36.066  6558  6643 I System.out: propertyValue:false
07-27 08:54:36.087  6558  6643 I Babel   : connection state changed from UNKNOWN to CONNECTED
,07-27 08:54:36.124  6644  6644 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=47 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,07-27 08:54:36.221  6644  6644 I dex2oat : dex2oat took 92.911ms (threads: 4)
,07-27 08:54:36.236  6583  6615 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-27 08:54:36.236  6583  6615 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-27 08:54:36.236  6583  6615 I Adreno-EGL: Build Date: 03/02/15 Mon
07-27 08:54:36.236  6583  6615 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-27 08:54:36.236  6583  6615 I Adreno-EGL: Remote Branch: 
07-27 08:54:36.236  6583  6615 I Adreno-EGL: Local Patches: 
07-27 08:54:36.236  6583  6615 I Adreno-EGL: Reconstruct Branch: 
,07-27 08:54:36.357   862  1970 E libprocessgroup: failed to kill 1 processes for processgroup 6199
07-27 08:54:36.357   862  1970 I ActivityManager: Process com.google.android.apps.plus (pid 6199) has died
,07-27 08:54:36.430   244   325 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-27 08:54:36.430   244   325 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
07-27 08:54:36.430   244   325 W Vold    : Returning OperationFailed - no handler for errno 0
07-27 08:54:36.432  6625  6655 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
07-27 08:54:36.435   244   325 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-27 08:54:36.435   244   325 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
07-27 08:54:36.435   244   325 W Vold    : Returning OperationFailed - no handler for errno 0
07-27 08:54:36.435  6625  6655 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,07-27 08:54:36.451  6625  6625 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
07-27 08:54:36.451  6625  6625 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-27 08:54:36.451  6625  6625 I GAv4    :   adb logcat -s GAv4
07-27 08:54:36.473   244   325 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-27 08:54:36.473   244   325 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
07-27 08:54:36.473   244   325 W Vold    : Returning OperationFailed - no handler for errno 0
07-27 08:54:36.474  6625  6625 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
07-27 08:54:36.474  6625  6656 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,07-27 08:54:36.537   244   325 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
07-27 08:54:36.537   244   325 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
07-27 08:54:36.537   244   325 W Vold    : Returning OperationFailed - no handler for errno 0
07-27 08:54:36.538  6625  6656 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,07-27 08:54:36.548  6625  6625 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
07-27 08:54:36.558  6625  6658 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-27 08:54:36.722  6583  6615 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-27 08:54:36.722  6583  6615 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-27 08:54:36.722  6583  6615 I Adreno-EGL: Build Date: 03/02/15 Mon
07-27 08:54:36.722  6583  6615 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-27 08:54:36.722  6583  6615 I Adreno-EGL: Remote Branch: 
07-27 08:54:36.722  6583  6615 I Adreno-EGL: Local Patches: 
07-27 08:54:36.722  6583  6615 I Adreno-EGL: Reconstruct Branch: 
,07-27 08:54:36.781  6583  6615 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-27 08:54:36.781  6583  6615 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-27 08:54:36.781  6583  6615 I Adreno-EGL: Build Date: 03/02/15 Mon
07-27 08:54:36.781  6583  6615 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-27 08:54:36.781  6583  6615 I Adreno-EGL: Remote Branch: 
07-27 08:54:36.781  6583  6615 I Adreno-EGL: Local Patches: 
07-27 08:54:36.781  6583  6615 I Adreno-EGL: Reconstruct Branch: 
,07-27 08:54:36.974  5716  5809 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-27 08:54:36.974  5716  5809 I jxcore-log: 
,07-27 08:54:36.990  6425  6436 E UEI.SmartControl: file observer is disposed!
07-27 08:54:37.000  6625  6625 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,07-27 08:54:37.030  1757  6578 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:37.030  1757  6578 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:54:37.030  1757  6578 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,07-27 08:54:37.030  1757  6578 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,07-27 08:54:37.031   275   910 E BandwidthController: [LG DATA] No such appUid: 10006
07-27 08:54:37.031   275   910 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-27 08:54:37.031   275  6673 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-27 08:54:37.031   275  6673 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:54:37.031   275  6673 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-27 08:54:37.032   275  6673 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-27 08:54:37.032   275  6673 D libc-netbsd: res_queryN name = xxxxx succeed
07-27 08:54:37.032  1757  6578 I System.out: propertyValue:false
07-27 08:54:37.069  6625  6625 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 7461-7463)
07-27 08:54:37.070  6625  6625 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-27 08:54:37.082  5716  5809 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-27 08:54:37.082  5716  5809 I jxcore-log: 
07-27 08:54:37.087  6625  6625 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {10d543fd}
,07-27 08:54:37.088  6625  6625 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 08:54:37.089  6625  6625 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-27 08:54:37.094  5716  5809 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-27 08:54:37.094  5716  5809 I jxcore-log: 
07-27 08:54:37.105  6625  6625 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-27 08:54:37.114  6625  6625 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 08:54:37.117  6625  6625 E SysUtils: ApplicationContext is null in ApplicationStatus
07-27 08:54:37.117  1757  6578 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:37.117  1757  6578 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:54:37.176  6625  6625 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-27 08:54:37.187  6625  6625 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-27 08:54:37.187  6625  6625 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-27 08:54:37.188  6625  6625 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-27 08:54:37.188  6625  6625 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-27 08:54:37.188  6625  6625 I Adreno-EGL: Build Date: 03/02/15 Mon
07-27 08:54:37.188  6625  6625 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-27 08:54:37.188  6625  6625 I Adreno-EGL: Remote Branch: 
07-27 08:54:37.188  6625  6625 I Adreno-EGL: Local Patches: 
07-27 08:54:37.188  6625  6625 I Adreno-EGL: Reconstruct Branch: 
07-27 08:54:37.322  6625  6625 I NSApplication: Starting up...
,07-27 08:54:37.332   279  6642 V AudioPolicyService: registerClient() client 0xb3826de0, uid 10079
07-27 08:54:37.336  6625  6687 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-27 08:54:37.389   862  1851 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6692 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-27 08:54:37.479  5716  5809 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-27 08:54:37.479  5716  5809 I jxcore-log: 
,07-27 08:54:37.519  5716  5809 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-27 08:54:37.519  5716  5809 I jxcore-log: 
,07-27 08:54:37.526  5716  5809 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-27 08:54:37.526  5716  5809 I jxcore-log: 
07-27 08:54:37.534  5716  5809 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-27 08:54:37.534  5716  5809 I jxcore-log: 
,07-27 08:54:37.546   862  1923 I ActivityManager: Process com.lge.appbox.client (pid 6445) has died
,07-27 08:54:37.564  5716  5809 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-27 08:54:37.564  5716  5809 I jxcore-log: 
,07-27 08:54:37.602  5716  5809 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-27 08:54:37.602  5716  5809 I jxcore-log: 
,07-27 08:54:37.772  1757  3060 I art     : Explicit concurrent mark sweep GC freed 85780(5MB) AllocSpace objects, 48(789KB) LOS objects, 39% free, 14MB/24MB, paused 1.400ms total 108.927ms
,07-27 08:54:37.808  5716  5809 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-27 08:54:37.808  5716  5809 I jxcore-log: 
,07-27 08:54:37.817  5716  5809 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-27 08:54:37.817  5716  5809 I jxcore-log: 
07-27 08:54:37.868  5716  5809 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-27 08:54:37.868  5716  5809 I jxcore-log: 
,07-27 08:54:37.892  2074  5993 D BluetoothAdapterService(340792543): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@20c384ad
07-27 08:54:37.894  5716  5809 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,07-27 08:54:37.897  5716  5809 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
07-27 08:54:37.897  5716  5809 I jxcore-log: 
,07-27 08:54:37.915   279  6642 I WVCdm   : CdmEngine::CloseSession
07-27 08:54:37.935  6425  6508 D UEI.SmartControl: Internal timer expired: 2
07-27 08:54:37.938   862  1883 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6714 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,07-27 08:54:37.963   305   305 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 335us total 25.577ms
,07-27 08:54:37.984   305   305 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 20.823ms
,07-27 08:54:37.993   279   279 I WVCdm   : CdmEngine::QueryKeyControlInfo
07-27 08:54:37.997   279  1606 I WVCdm   : CdmEngine::OpenSession
,07-27 08:54:38.001   242   242 E lowmemorykiller: Error writing /proc/6401/oom_score_adj; errno=22
07-27 08:54:38.002  6425  6425 D UEI.SmartControl: Service.onUnbind: IControl
07-27 08:54:38.002  6425  6425 D UEI.SmartControl: Service.onDestroy
07-27 08:54:38.002  6425  6425 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@3fdd4818
07-27 08:54:38.004   279   279 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
07-27 08:54:38.004   279   279 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
07-27 08:54:38.004   279   279 I WVCdm   : CdmEngine::GenerateKeyRequest
07-27 08:54:38.005  6425  6425 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
07-27 08:54:38.005  6425  6425 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
07-27 08:54:38.005  6425  6425 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
07-27 08:54:38.005  6425  6425 W System.err: 	at com.uei.control.Service.c(Unknown Source)
07-27 08:54:38.005  6425  6425 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
07-27 08:54:38.005  6425  6425 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2983)
07-27 08:54:38.005  6425  6425 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:155)
07-27 08:54:38.005  6425  6425 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1426)
07-27 08:54:38.005  6425  6425 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:54:38.005  6425  6425 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-27 08:54:38.005  6425  6425 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
07-27 08:54:38.005  6425  6425 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:54:38.005  6425  6425 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 08:54:38.005  6425  6425 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
07-27 08:54:38.005  6425  6425 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
07-27 08:54:38.006  6425  6425 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@3fdd4818
07-27 08:54:38.006  6425  6425 D UEI.SmartControl: Shutdown IRRCPlayer... 
07-27 08:54:38.006  6425  6425 W irrc_jni: IRRCPlayer_nativeFinalize ++ 
07-27 08:54:38.006  6425  6425 D irrcClient: ~IrrcClient ++ 
07-27 08:54:38.006   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 20.997ms
07-27 08:54:38.006  6425  6425 D irrcClient: ~IrrcClient -- 
07-27 08:54:38.006  6425  6425 W irrc_jni: IRRCPlayer_nativeFinalize -- 
07-27 08:54:38.006  6425  6425 D UEI.SmartControl: Blaster closed
07-27 08:54:38.006  6425  6425 D UEI.SmartControl: Blaster closed
07-27 08:54:38.006  6425  6425 D UEI.SmartControl: Shut down QS...
07-27 08:54:38.007  6425  6425 I UEI.SmartControl: QS lib stop result = true
07-27 08:54:38.007  6425  6425 D UEI.SmartControl: QS shutdown complete
07-27 08:54:38.009   279   279 D WVCdm   : PrepareKeyRequest: nonce=2468841382
07-27 08:54:38.020  5716  5809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-27 08:54:38.020  5716  5809 I jxcore-log: 
07-27 08:54:38.022  5716  5809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 08:54:38.022  5716  5809 I jxcore-log: 
07-27 08:54:38.023  5716  5809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 08:54:38.023  5716  5809 I, jxcore-log: 
07-27 08:54:38.038   862  1291 I ActivityManager: Process com.lge.lgdmsclient (pid 6401) has died
07-27 08:54:38.061  1787  1787 I PhoneApp: onTrimMemory: 10
07-27 08:54:38.061  1787  1787 I PhoneApp: trim memory
,07-27 08:54:38.066  2023  2023 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
,07-27 08:54:38.130   279  1606 I WVCdm   : CdmEngine::QueryKeyControlInfo
,07-27 08:54:38.134   279  1298 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
07-27 08:54:38.134   279  1298 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
07-27 08:54:38.134   279  1298 I WVCdm   : CdmEngine::GenerateKeyRequest
07-27 08:54:38.189  5349  5349 I GAv4-SVC: Google Analytics 9.2.56 is starting up.
,07-27 08:54:38.273   862  1853 I art     : Explicit concurrent mark sweep GC freed 27902(1382KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 23MB/35MB, paused 1.932ms total 178.925ms
,07-27 08:54:38.313   295   356 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 08:54:38.321  6714  6714 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 08:54:38.443  1757  1757 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=c6d080e5-2a3c-4632-b90b-0410fdb648b0
,07-27 08:54:38.552  5385  5525 I art     : Explicit concurrent mark sweep GC freed 2880(115KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.537ms total 34.560ms
,07-27 08:54:38.603  1757  2463 W GCoreFlp: No location to return for getLastLocation()
,07-27 08:54:38.766   862  1883 I ActivityManager: Process com.uei.lg.quicksetsdk.lite (pid 6425) has died
,07-27 08:54:38.800  5349  6704 D UdcContextInitService: registered all accounts: true
07-27 08:54:38.801  1757  2384 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-27 08:54:38.812  1757  2361 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
07-27 08:54:38.868   862  1291 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6749 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,07-27 08:54:38.980  6749  6749 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-27 08:54:39.046   862  2204 I ActivityManager: Process com.google.android.setupwizard (pid 6488) has died
,07-27 08:54:39.052  1787  1787 I PhoneApp: onTrimMemory: 10
07-27 08:54:39.052  1787  1787 I PhoneApp: trim memory
07-27 08:54:39.053  2023  2023 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
07-27 08:54:39.057   862  1283 V AlarmManager: ELAPSED_WAKEUP set : Alarm{23771809 type 2 when 159433 com.android.systemui} when 159433
07-27 08:54:39.118   862  1014 D BluetoothManagerService: Message: 20
07-27 08:54:39.118   862  1014 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@242cbf41:true
,07-27 08:54:39.128  2074  2091 D BluetoothAdapterService(340792543): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@20c384ad
07-27 08:54:39.129  2074  5993 D BluetoothAdapterService(340792543): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@20c384ad
,07-27 08:54:39.191   862  2204 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6768 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,07-27 08:54:39.245   242   242 E lowmemorykiller: Error writing /proc/6558/oom_score_adj; errno=22
,07-27 08:54:39.279   242   242 E lowmemorykiller: Error writing /proc/6558/oom_score_adj; errno=22
07-27 08:54:39.286   242   242 E lowmemorykiller: Error writing /proc/6558/oom_score_adj; errno=22
,07-27 08:54:39.296  1757  2361 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:39.296  1757  2361 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:54:39.297  1757  2361 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:39.297  1757  2361 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:54:39.297   275   910 E BandwidthController: [LG DATA] No such appUid: 10006
07-27 08:54:39.297   275   910 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-27 08:54:39.298   275  6785 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-27 08:54:39.298   275  6785 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,07-27 08:54:39.298   275  6785 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-27 08:54:39.300   275  6785 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-27 08:54:39.300   275  6785 D libc-netbsd: res_queryN name = xxxxx succeed
07-27 08:54:39.302  1757  2361 I System.out: propertyValue:false
07-27 08:54:39.356   862  1906 I ActivityManager: Process com.google.android.talk (pid 6558) has died
,07-27 08:54:39.361  1757  2361 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:39.361  1757  2361 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:54:39.365  6714  6728 I art     : CheckpointMarkThreadRoots callback created = 0xb042d4c0
07-27 08:54:39.366  1787  1787 I PhoneApp: onTrimMemory: 10
07-27 08:54:39.366  1787  1787 I PhoneApp: trim memory
07-27 08:54:39.369  2023  2023 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
07-27 08:54:39.375  6768  6768 I DigitalAppWidgetProvider: onReceive: android.intent.action.ALARM_CHANGED
,07-27 08:54:39.387  2847  2847 D WeatherAncestor: 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 8:54:39
,07-27 08:54:39.392  2847  2847 D UpdateThreadPoolManager: 2 : This is isUpdating : false
07-27 08:54:39.394  2847  2847 D Weather_cast: 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
07-27 08:54:39.394  2847  2847 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 8:54:39
07-27 08:54:39.394  6714  6728 I art     : CheckpointMarkThreadRoots callback created = 0xb042d4b0
07-27 08:54:39.396  2847  2847 D WeatherService: 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
07-27 08:54:39.396  2847  2847 D WeatherService: 2 : shouldTimeTickRegistered : false
07-27 08:54:39.409  1947  1947 I [LGHome]LGNumberBadgeReceiver: [LGNumberBadgeReceiver.java:71:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = android.intent.action.BADGE_COUNT_UPDATE
,07-27 08:54:39.433  1947  2827 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
07-27 08:54:39.434  1947  2827 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
07-27 08:54:39.434  1947  2827 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
,07-27 08:54:39.451  1947  2827 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
07-27 08:54:39.452  1947  2827 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.bnr.launcher.BNRLauncherActivity = 0
,07-27 08:54:39.452   862  1291 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=6786 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,07-27 08:54:39.550   862   882 I NotificationManager: android: cancelAsUser(2) by android
,07-27 08:54:39.566  1757  6805 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-27 08:54:39.567  1757  6766 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
07-27 08:54:39.587  1757  2361 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,07-27 08:54:39.595  1757  6805 E CommitToConfigurationOperation: Malformed snapshot token (size): 
07-27 08:54:39.596  1757  6766 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
07-27 08:54:39.638  1757  6805 E CommitToConfigurationOperation: Malformed snapshot token (size): 
07-27 08:54:39.640  1757  6766 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
07-27 08:54:39.640  1757  6766 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,07-27 08:54:39.650  1757  6766 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
07-27 08:54:39.664  1757  2361 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-27 08:54:39.677  1757  2361 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,07-27 08:54:39.678  1757  2361 V BaseAppContext: GmsRequestQueue started.
07-27 08:54:39.680  6786  6786 V [BNRBootReceiver]: boot receiver action = com.lge.bnr.releasebadge
07-27 08:54:39.686  6786  6786 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setHomeBadgeCount:192 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:225 
07-27 08:54:39.688  1368  1368 D KeyguardModel: mReceiver, received action: android.intent.action.BADGE_COUNT_UPDATE, sendingUserId:0
07-27 08:54:39.688  1329  1329 I QuickCircle: onReceive :Intent { act=android.intent.action.BADGE_COUNT_UPDATE flg=0x10 (has extras) }, sComponents:[com.coremobility.app.vnotes.CM_VnoteInbox, com.android.contacts.activities.DialtactsActivity, com.android.contacts.DialtactsRecentCallsEntryActivity, com.lge.vvm.authmanager.VvmAuthManagerActivity, com.lge.email.ui.setupwizard.Welcome, com.skt.prod.dialer.activities.main.MainActivity, com.android.mms.ui.ConversationList, com.lge.message.ui.ConversationList, com.lge.message.activity.MainMenuActivity, com.skt.skaf.A000Z00040.A000Z00040, com.lge.updatecenter.UpdateCenterPrfActivity, com.lge.bnr.launcher.BNRLauncherActivity]
07-27 08:54:39.688  1368  1368 D KeyguardModel: ACTION_GENERAL_UPDATE_NOTIFICATION received! package: com.lge.bnr.launcher, class: com.lge.bnr.launcher.BNRLauncherActivity, unread_count: 0
07-27 08:54:39.688  1368  1368 D KeyguardModel: putThirdPartyNotificationIntoList Number: 0 Id: 12 UserId: 0
07-27 08:54:39.694  6786  6786 I NotificationManager: com.lge.bnr: cancel(10) by com.lge.bnr
07-27 08:54:39.694  6786  6786 V [BNRBootReceiver]: Boot Receiver Return
,07-27 08:54:39.696  6786  6786 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
07-27 08:54:39.703  1757  6810 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:39.703  1757  6810 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:54:39.704  1757  6810 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:39.704  1757  6810 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:54:39.705   275   910 E BandwidthController: [LG DATA] No such appUid: 10006
07-27 08:54:39.705   275   910 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-27 08:54:39.705   275  6812 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-27 08:54:39.705   275  6812 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:54:39.706   275  6812 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-27 08:54:39.706   275  6812 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-27 08:54:39.707   275  6812 D libc-netbsd: res_queryN name = xxxxx succeed
07-27 08:54:39.709  1757  6810 I System.out: propertyValue:false
07-27 08:54:39.720   862  1883 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-27 08:54:39.788   862  1375 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gms/.phenotype.service.PhenotypeCommitChimeraService (has extras) } U=0: not found
,07-27 08:54:39.804  1757  6766 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:39.804  1757  6766 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-27 08:54:39.805  1757  6766 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:39.805  1757  6766 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:54:39.805   275   910 E BandwidthController: [LG DATA] No such appUid: 10006
07-27 08:54:39.805   275   910 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-27 08:54:39.813   275  6814 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-27 08:54:39.813   275  6814 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:54:39.813   275  6814 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-27 08:54:39.813   275  6814 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-27 08:54:39.843   275  6814 D libc-netbsd: res_queryN name = xxxxx succeed
,07-27 08:54:39.845  1757  6766 I System.out: propertyValue:false
07-27 08:54:39.862   862  2204 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6818 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-27 08:54:39.929  5349  5475 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.ocr
,07-27 08:54:39.936  1757  6833 E CommitToConfigurationOperation: Malformed snapshot token (size): 
07-27 08:54:39.939  1757  2359 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.tapandpay failed, retrying
,07-27 08:54:39.951  1757  6833 E CommitToConfigurationOperation: Malformed snapshot token (size): 
07-27 08:54:39.953  1757  2359 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.tapandpay failed, retrying
,07-27 08:54:39.972  6818  6818 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-27 08:54:39.975  1757  6833 E CommitToConfigurationOperation: Malformed snapshot token (size): 
07-27 08:54:39.976  1757  2359 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.tapandpay failed, retrying
07-27 08:54:39.976  1757  2359 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.tapandpay
07-27 08:54:40.004  1757  2361 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,07-27 08:54:40.013  5349  6816 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
07-27 08:54:40.135   862  1906 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-27 08:54:40.203  6818  6844 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
07-27 08:54:40.204  6818  6844 I Babel_SMS: MmsConfig.loadMmsSettings
07-27 08:54:40.206  6818  6844 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
07-27 08:54:40.206  6818  6844 I Babel_SMS: MmsConfig.loadFromDatabase
,07-27 08:54:40.223  6818  6844 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
07-27 08:54:40.223  6818  6844 I Babel_SMS: MmsConfig.loadFromResources
07-27 08:54:40.229  6818  6844 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,07-27 08:54:40.230  6818  6844 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
07-27 08:54:40.331  6818  6818 D SensorManager: found sensor: LGE Accelerometer Sensor, handle=0
07-27 08:54:40.331  6818  6818 D SensorManager: found sensor: LGE Magnetometer Sensor, handle=10
07-27 08:54:40.331  6818  6818 D SensorManager: found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
07-27 08:54:40.331  6818  6818 D SensorManager: found sensor: LGE Proximity Sensor, handle=48
07-27 08:54:40.331  6818  6818 D SensorManager: found sensor: LGE Gravity Sensor, handle=29
07-27 08:54:40.331  6818  6818 D SensorManager: found sensor: LGE Linear Acceleration Sensor, handle=30
07-27 08:54:40.331  6818  6818 D SensorManager: found sensor: LGE Rotation Vector Sensor, handle=36
07-27 08:54:40.331  6818  6818 D SensorManager: found sensor: LGE Step Detector Sensor, handle=43
07-27 08:54:40.331  6818  6818 D SensorManager: found sensor: LGE Step Counter Sensor, handle=44
07-27 08:54:40.331  6818  6818 D SensorManager: found sensor: LGE Significant Motion Detector Sensor, handle=47
07-27 08:54:40.331  6818  6818 D SensorManager: found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
07-27 08:54:40.331  6818  6818 D SensorManager: found sensor: LGE Orientation Sensor, handle=49
07-27 08:54:40.332  6818  6818 D SensorManager: found sensor: LGE Tilt Detector Sensor, handle=55
07-27 08:54:40.332  6818  6818 D SensorManager: found sensor: LGE Absolute Motion Detector Sensor, handle=33
07-27 08:54:40.332  6818  6818 D SensorManager: found sensor: LGE Relative Motion Detector Sensor, handle=34
07-27 08:54:40.332  6818  6818 D SensorManager: found sensor: Motion Accel, handle=46
,07-27 08:54:40.358  6818  6832 I art     : CheckpointMarkThreadRoots callback created = 0xaaf5e2c0
,07-27 08:54:40.362   862  2008 I NotificationManager: android: cancelAsUser(2) by android
07-27 08:54:40.373  6818  6818 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 08:54:40.379  6818  6818 I Babel_Crash: startup - clean
07-27 08:54:40.395  6818  6832 I art     : CheckpointMarkThreadRoots callback created = 0xaaf5e2a0
,07-27 08:54:40.397  1757  6766 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
07-27 08:54:40.416  6818  6847 I Babel   : deleted: false for 0
,07-27 08:54:40.463   279  6642 I WVCdm   : CdmEngine::CloseSession
,07-27 08:54:40.472   279  1298 D WVCdm   : PrepareKeyRequest: nonce=2535698022
07-27 08:54:40.479  6583  6601 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-27 08:54:40.479  6583  6601 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-27 08:54:40.479  6583  6601 I Adreno-EGL: Build Date: 03/02/15 Mon
07-27 08:54:40.479  6583  6601 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-27 08:54:40.479  6583  6601 I Adreno-EGL: Remote Branch: 
07-27 08:54:40.479  6583  6601 I Adreno-EGL: Local Patches: 
07-27 08:54:40.479  6583  6601 I Adreno-EGL: Reconstruct Branch: 
,07-27 08:54:40.613  6583  6601 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-27 08:54:40.613  6583  6601 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-27 08:54:40.613  6583  6601 I Adreno-EGL: Build Date: 03/02/15 Mon
07-27 08:54:40.613  6583  6601 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-27 08:54:40.613  6583  6601 I Adreno-EGL: Remote Branch: 
07-27 08:54:40.613  6583  6601 I Adreno-EGL: Local Patches: 
07-27 08:54:40.613  6583  6601 I Adreno-EGL: Reconstruct Branch: 
,07-27 08:54:40.672  6583  6601 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
07-27 08:54:40.672  6583  6601 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
07-27 08:54:40.672  6583  6601 I Adreno-EGL: Build Date: 03/02/15 Mon
07-27 08:54:40.672  6583  6601 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
07-27 08:54:40.672  6583  6601 I Adreno-EGL: Remote Branch: 
07-27 08:54:40.672  6583  6601 I Adreno-EGL: Local Patches: 
07-27 08:54:40.672  6583  6601 I Adreno-EGL: Reconstruct Branch: 
,07-27 08:54:40.700   862  1291 E libprocessgroup: failed to kill 1 processes for processgroup 6625
07-27 08:54:40.700   862  1291 I ActivityManager: Process com.google.android.apps.magazines (pid 6625) has died
07-27 08:54:40.708  1787  1787 I PhoneApp: onTrimMemory: 10
07-27 08:54:40.708  1787  1787 I PhoneApp: trim memory
07-27 08:54:40.711  2023  2023 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
,07-27 08:54:40.718  1368  1368 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
07-27 08:54:40.738  1787  1808 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
,07-27 08:54:40.740   862  1291 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
07-27 08:54:40.745  1787  1808 D PhoneUtils: getPhoneCount() sPhoneCount = 1
07-27 08:54:40.745  1787  1808 D PhoneUtils: getPhoneCount() sPhoneCount = 1
07-27 08:54:40.750  1787  1808 V TelecomServiceImpl: getCallState : 0
,07-27 08:54:40.753  1787  2392 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
07-27 08:54:40.753  1787  2392 D PhoneUtils: getPhoneCount() sPhoneCount = 1
07-27 08:54:40.753  1787  2392 D PhoneUtils: getPhoneCount() sPhoneCount = 1
07-27 08:54:40.756  1368  1368 D KeyguardUpdateMonitor: isHdmiPluggedIn :false
07-27 08:54:40.757  1368  1368 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
07-27 08:54:40.759  6818  6818 W AudioCapabilities: Unsupported mime audio/x-lg-flac
07-27 08:54:40.763  6818  6818 W AudioCapabilities: Unsupported mime audio/adpcm
,07-27 08:54:40.767  6818  6818 W AudioCapabilities: Unsupported mime audio/g726
07-27 08:54:40.776  6818  6818 W AudioCapabilities: Unsupported mime audio/x-ms-wma
07-27 08:54:40.777  6818  6818 W AudioCapabilities: Unsupported mime audio/wma-voice
07-27 08:54:40.779  6818  6818 W VideoCapabilities: Unsupported mime video/mjpg
,07-27 08:54:40.788  6818  6818 W VideoCapabilities: Unsupported mime video/theora
07-27 08:54:40.808  6818  6818 W AudioCapabilities: Unsupported mime audio/evrc
,07-27 08:54:40.812  6818  6818 W AudioCapabilities: Unsupported mime audio/qcelp
07-27 08:54:40.813  6818  6818 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-27 08:54:40.819  6818  6818 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
07-27 08:54:40.820  6818  6818 W AudioCapabilities: Unsupported mime audio/qcelp
07-27 08:54:40.823  6818  6818 W AudioCapabilities: Unsupported mime audio/evrc
,07-27 08:54:40.843  6818  6818 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,07-27 08:54:40.857   862   881 I ActivityManager: Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6851 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-27 08:54:40.883  6749  6749 V LGMDMManager: Create singleton instance
,07-27 08:54:40.900  6818  6818 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-27 08:54:40.917  6818  6818 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-27 08:54:40.920  6818  6818 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-27 08:54:40.924  6818  6818 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-27 08:54:40.930  6818  6818 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-27 08:54:40.937  6818  6818 I vclib   : onServiceConnected
07-27 08:54:40.938  6818  6818 W Babel   : Attempted to change video mute state without an active call.
,07-27 08:54:40.955  6818  6818 I NotificationManager: com.google.android.talk: cancel(10436) by com.google.android.talk
,07-27 08:54:40.969  6749  6749 I AudioManager: getMode name:com.lge.qremote
07-27 08:54:40.978  1947  1947 I [LGHome]LGNumberBadgeReceiver: [LGNumberBadgeReceiver.java:71:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = android.intent.action.BADGE_COUNT_UPDATE
,07-27 08:54:40.982  6851  6851 D UEI.SmartControl: Quickset Services start...
07-27 08:54:40.982  1947  2123 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
07-27 08:54:40.982  1947  2123 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
07-27 08:54:40.982  1947  2123 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
07-27 08:54:40.983  1947  2123 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
07-27 08:54:40.983  1947  2123 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.bnr.launcher.BNRLauncherActivity = 0
07-27 08:54:40.984  6851  6851 I UEI.SmartControl: Manufacture = LGE
07-27 08:54:40.986  6851  6851 D UEI.SmartControl: File observer start...
07-27 08:54:40.988  6851  6851 E UEI.SmartControl: IR Port is disabled: false
07-27 08:54:40.988  6851  6851 D UEI.SmartControl: Starting file observer...
07-27 08:54:40.989  6851  6851 D UEI.SmartControl: Extracting JNI libs...
07-27 08:54:40.990  6851  6851 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
07-27 08:54:41.036  6851  6851 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,07-27 08:54:41.038  6851  6851 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
07-27 08:54:41.038  6851  6851 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
07-27 08:54:41.071  6851  6851 I UEI.SmartControl: --- Selecting new region: 2
,07-27 08:54:41.071  6851  6851 I UEI.SmartControl: -- Running on KitKat(19) and above! JNI will be used.
07-27 08:54:41.076  6851  6851 D UEI.SmartControl: Platform has CIR...
07-27 08:54:41.077  6851  6851 D UEI.SmartControl: NO CIR support, need to check package...
07-27 08:54:41.078  6851  6851 I UEI.SmartControl: Model: LG-D722 uses JNI
07-27 08:54:41.080  6851  6851 D UEI.SmartControl: QS Service created
07-27 08:54:41.105  6851  6851 E UEI.SmartControl: QS start get config
,07-27 08:54:41.134  5349  6543 I CheckinUtil: Classify the device as Phone.
,07-27 08:54:41.144   862  2370 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-27 08:54:41.167  6851  6851 D UEI.SmartControl: Loading JNI Libs...
,07-27 08:54:41.173  6851  6851 D UEI.SmartControl:  configuring local db...
07-27 08:54:41.211  5349  6543 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:41.211  5349  6543 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:54:41.211  5349  6543 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,07-27 08:54:41.211  5349  6543 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:54:41.212   275   910 E BandwidthController: [LG DATA] No such appUid: 10006
07-27 08:54:41.212   275   910 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-27 08:54:41.213   275  6872 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-27 08:54:41.213   275  6872 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:54:41.213   275  6872 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-27 08:54:41.213   275  6872 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-27 08:54:41.214   275  6872 D libc-netbsd: res_queryN name = xxxxx succeed
07-27 08:54:41.214  5349  6543 I System.out: propertyValue:false
07-27 08:54:41.288  5349  6543 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:54:41.288  5349  6543 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-27 08:54:41.358   862  1853 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-27 08:54:41.386  5349  6543 I CheckinTask: Sending checkin request (11409 bytes)
,07-27 08:54:41.387  6851  6851 D UEI.SmartControl:  ---- Has DB8: true
07-27 08:54:41.395  6851  6851 D UEI.SmartControl: QS start statue = true Error code = 0
07-27 08:54:41.396  6851  6851 D UEI.SmartControl: QS version = v2.7.11.1_RC1
07-27 08:54:41.397  6851  6851 D UEI.SmartControl: QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
07-27 08:54:41.402  6851  6851 D UEI.SmartControl: IRRCDataComm has AudioManager!!!!.
,07-27 08:54:41.414  6851  6851 W irrc_jni: IRRCPlayer_nativeInit ++ 
,07-27 08:54:41.414  6851  6851 D irrcClient: IrrcClient ++ 
07-27 08:54:41.414  6851  6851 D irrcClient: getIrrcService ++ 
,07-27 08:54:41.415  6851  6851 D irrcClient: getIrrcService -- 
,07-27 08:54:41.415  6851  6851 D irrcClient: IrrcClient -- 
07-27 08:54:41.415  6851  6851 W irrc_jni: IRRCPlayer_nativeInit -- 
07-27 08:54:41.423  6851  6851 D UEI.SmartControl: Services init done
07-27 08:54:41.423  6851  6874 I UEI.SmartControl: Device manager: loading config....
07-27 08:54:41.426  6851  6851 D UEI.SmartControl: QS Service init finished
,07-27 08:54:41.429  6851  6851 D UEI.SmartControl: QS Service version name: 0.1.73
07-27 08:54:41.429  6851  6874 D UEI.SmartControl: Config is loaded...
07-27 08:54:41.430  6851  6851 D UEI.SmartControl: QS Service version code: 1073
07-27 08:54:41.432  6851  6851 D UEI.SmartControl: Service requested: Control
07-27 08:54:41.435  6851  6851 D UEI.SmartControl: Internal service binding...
07-27 08:54:41.435  6851  6866 D UEI.SmartControl: -----IControl: 11
07-27 08:54:41.437  6851  6866 D UEI.SmartControl: Caller: com.lge.qremote
07-27 08:54:41.437  6851  6866 D UEI.SmartControl: ------------ IControl registerCallback...
07-27 08:54:41.438  6851  6866 I UEI.SmartControl: Registering callback...
,07-27 08:54:41.439  6851  6867 D UEI.SmartControl: -----IControl: 19
07-27 08:54:41.441  6851  6867 D UEI.SmartControl: Caller: com.lge.qremote
07-27 08:54:41.442  6851  6867 I UEI.SmartControl: Registering Services Ready callback...
07-27 08:54:41.443  6851  6867 I UEI.SmartControl: Notify client services are ready...
07-27 08:54:41.446  6851  6866 D UEI.SmartControl: -----IControl: 8
07-27 08:54:41.447  6851  6866 D UEI.SmartControl: Caller: com.lge.qremote
07-27 08:54:41.452  6749  6749 I AudioManager: getMode name:com.lge.qremote
,07-27 08:54:41.466  6851  6873 D UEI.SmartControl:  ----- QS SDK is ready!!!
07-27 08:54:41.467  6851  6873 I UEI.SmartControl: Notify AllClients services are ready: 0
,07-27 08:54:41.484  6749  6749 I AudioManager: getMode name:com.lge.qremote
,07-27 08:54:41.596   862  2008 I ActivityManager: Process com.lge.drmservice (pid 6519) has died
,07-27 08:54:41.609   862  1923 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-27 08:54:41.621  6749  6749 I AudioManager: getMode name:com.lge.qremote
,07-27 08:54:41.744  5349  6543 I CheckinRequestBuilder: Checkin reason type: 8 attempt count: 1
,07-27 08:54:41.745  5349  6543 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,07-27 08:54:41.854   862  2370 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-27 08:54:41.879  5349  6543 I art     : Explicit concurrent mark sweep GC freed 27147(1946KB) AllocSpace objects, 28(451KB) LOS objects, 24% free, 16MB/22MB, paused 1.195ms total 111.081ms
,07-27 08:54:41.930  1757  2361 I art     : Explicit concurrent mark sweep GC freed 56121(3MB) AllocSpace objects, 27(436KB) LOS objects, 39% free, 15MB/26MB, paused 2.028ms total 143.337ms
,07-27 08:54:42.101   862  2370 I art     : Explicit concurrent mark sweep GC freed 29071(1273KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.015ms total 170.470ms
,07-27 08:54:42.201  5349  6543 I CheckinUtil: Classify the device as Phone.
,07-27 08:54:42.216  1757  2361 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,07-27 08:54:42.222  5349  6543 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
07-27 08:54:42.238  5349  6543 I CheckinChimeraService: Checking schedule, now: 1469602482238 next: 1470129731222
07-27 08:54:42.238  5349  6543 I CheckinChimeraService: active receiver: disabled
,07-27 08:54:42.275  5349  5349 D CheckinChimeraService: Recording last checkin time for package unspecified as 1469602482275
07-27 08:54:42.321  5349  5475 V UdcCtxListenerSrv: handle intent
,07-27 08:54:42.348   862  1970 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6890 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,07-27 08:54:42.515  6890  6890 D PhoneMonitor: Register our PhoneStateListener
,07-27 08:54:42.562  5385  5406 I art     : Explicit concurrent mark sweep GC freed 3051(120KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 372us total 25.839ms
,07-27 08:54:42.566  6890  6890 V SetupWizard: Connected to Gservices successfully
,07-27 08:54:42.590   862  2370 I ActivityManager: Killing 6692:com.android.chrome/u0a48 (adj 15): empty #11
,07-27 08:54:42.593  6890  6890 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
07-27 08:54:42.596  6890  6890 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
07-27 08:54:42.597  6890  6890 D TelephonyAutoProfiling: [parse] Load xml
07-27 08:54:42.604  6890  6890 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,07-27 08:54:42.604  6890  6890 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
07-27 08:54:42.612  6890  6890 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
07-27 08:54:42.774   862  2204 W libprocessgroup: failed to open /acct/uid_10048/pid_6692/cgroup.procs: No such file or directory
,07-27 08:54:42.802  1757  6913 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,07-27 08:54:42.811   279  1606 I WVCdm   : CdmEngine::CloseSession
,07-27 08:54:42.815   279  1606 I WVCdm   : L3 Terminate.
,07-27 08:54:43.318   295   356 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-27 08:54:43.621  1368  1368 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,07-27 08:54:43.639  1909  1909 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,07-27 08:54:43.645  1368  1368 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
07-27 08:54:43.648  1947  1947 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
07-27 08:54:43.655  1947  1947 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,07-27 08:54:43.659  1947  1947 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
07-27 08:54:43.662   862  1285 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-27 08:54:43.666  1368  1368 W [SystemUI]QSlideLoader: Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
07-27 08:54:43.666  1368  1368 W [SystemUI]QSlideLoader: Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
07-27 08:54:43.667  1368  1368 W [SystemUI]QSlideLoader: Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
07-27 08:54:43.667  1368  1368 W [SystemUI]QSlideLoader: Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
07-27 08:54:43.667  1368  1368 W [SystemUI]QSlideLoader: Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
07-27 08:54:43.667  1368  1368 W [SystemUI]QSlideLoader: Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
07-27 08:54:43.667  1368  1368 W [SystemUI]QSlideLoader: Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
07-27 08:54:43.667  1368  1368 W [SystemUI]QSlideLoader: Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
07-27 08:54:43.667  1368  1368 W [SystemUI]QSlideLoader: Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
07-27 08:54:43.667  1368  1368 W [SystemUI]QSlideLoader: Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
,07-27 08:54:43.667  1368  1368 W [SystemUI]QSlideLoader: Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
07-27 08:54:43.667  1368  1368 W [SystemUI]QSlideLoader: Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
07-27 08:54:43.672  1368  1368 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
07-27 08:54:43.728  1947  1947 I [LGHome]Launcher: [Launcher.java:4023:setLoadOnResume()]setLoadOnResume
,07-27 08:54:43.765   862  1851 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6930 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,07-27 08:54:43.799  6818  6818 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-27 08:54:43.799  6818  6818 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-27 08:54:43.817  6818  6920 I NotificationManager: com.google.android.talk: cancel(8) by com.google.android.talk
,07-27 08:54:43.831   862   862 D administrator: Handling package changes for user 0
,07-27 08:54:43.897  6818  6818 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-27 08:54:43.901  6930  6930 I AppUp4:AppBoxCP: onCreate
07-27 08:54:43.907   862  2370 I ActivityManager: Process com.google.android.apps.plus (pid 6714) has died
07-27 08:54:43.909  6930  6930 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,07-27 08:54:43.924  6930  6930 I AppUp4:DB:  setFingerPrint start
,07-27 08:54:43.924  6930  6930 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
07-27 08:54:43.941  6930  6930 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
07-27 08:54:43.941  6930  6930 I AppUp4:DB:  SDK version = 21
07-27 08:54:43.941  6930  6930 I AppUp4:DB:  beforefinger == newfinger no write in DB
,07-27 08:54:43.944  6930  6930 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
07-27 08:54:43.973  6930  6930 I AppUp4:CustModeStarterReceiver: onReceive
07-27 08:54:43.974  6930  6930 I AppUp4:CustModeStarterReceiver: CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,07-27 08:54:43.983  6930  6930 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@19a4923d
07-27 08:54:43.984  6930  6930 D AppUp4:CustFacade: isCustomizationCompleted : false
07-27 08:54:43.992  6930  6930 D AppUp4:CustFacade: isSimDevice : true
07-27 08:54:43.995  6930  6930 D AppUp4:CustModeStarterReceiver: begin check event
07-27 08:54:43.995  6930  6930 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
,07-27 08:54:44.008  6818  6818 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,07-27 08:54:44.010  6818  6818 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
07-27 08:54:44.074   862  1946 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6955 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,07-27 08:54:44.096   862  1375 I ActivityManager: Process com.lge.clock (pid 6768) has died
,07-27 08:54:44.140  6955  6955 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 08:54:44.140  6955  6955 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-27 08:54:44.141  6955  6955 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,07-27 08:54:44.194   862   862 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,07-27 08:54:44.196   862   862 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
07-27 08:54:44.196   862   862 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
07-27 08:54:44.206   862   881 I ActivityManager: Process com.lge.qremote (pid 6749) has died
,07-27 08:54:44.219   862   862 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,07-27 08:54:44.229   862   901 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-27 08:54:44.258   862   862 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
07-27 08:54:44.258   862   862 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2dd81e54
07-27 08:54:44.333  6955  6955 I AppConfig: Total System Memory = 906309632
,07-27 08:54:44.336  6955  6955 I GalleryUtils: Application Heap = 96 MB
07-27 08:54:44.341  6955  6955 I AppConfig: App Tier : NOT_DEF
07-27 08:54:44.344   862   901 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,07-27 08:54:44.349  6955  6955 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
07-27 08:54:44.441   862  1906 I ActivityManager: Process com.uei.lg.quicksetsdk.lite (pid 6851) has died
,07-27 08:54:44.487   862  1853 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6979 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,07-27 08:54:44.498  1947  1947 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
07-27 08:54:44.519  1757  1757 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,07-27 08:54:44.546   862   901 D LocationProviderProxy: applying state to connected service
07-27 08:54:44.576  6979  6979 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 08:54:44.577  6979  6979 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
07-27 08:54:44.577  6979  6979 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,07-27 08:54:44.581  6979  6979 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
07-27 08:54:44.582  6979  6979 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
07-27 08:54:44.706  6979  6979 I SystemConfig: BUILD Country: EU
,07-27 08:54:44.707  6979  6979 I SystemConfig: BUILD Operator: OPEN
07-27 08:54:44.829   862  1375 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7001 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,07-27 08:54:44.841  6979  6996 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
07-27 08:54:44.841  6979  6996 I SystemConfig: existFile = false
07-27 08:54:44.841  6979  6996 I SystemConfig: canReadFile = false
07-27 08:54:44.845  6979  6996 I SystemConfig: systemFeature RCS result false
,07-27 08:54:44.845  6979  6996 D SystemConfig: refreshRcsSupport() :false
,07-27 08:54:44.902  7001  7001 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,07-27 08:54:44.928  7001  7001 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
07-27 08:54:44.928  7001  7001 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
07-27 08:54:44.928  7001  7001 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
07-27 08:54:44.929  7001  7001 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
07-27 08:54:44.929  7001  7001 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,07-27 08:54:44.949  5349  7019 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,07-27 08:54:45.015   862  4426 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7020 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,07-27 08:54:45.016   305   305 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 23.807ms
07-27 08:54:45.040   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 22.569ms
,07-27 08:54:45.065   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 282us total 22.198ms
07-27 08:54:45.090  5349  7019 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,07-27 08:54:45.106  7020  7020 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-27 08:54:45.117  5349  5475 I Icing   : updateResources: need to parse owf{com.google.android.gms}
,07-27 08:54:45.201  5349  7052 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-27 08:54:45.477  2023  7060 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,07-27 08:54:45.523   862  1906 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7065 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-27 08:54:45.572  2023  7060 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 94 ms] updated apps [took 94 ms] 
07-27 08:54:45.697   862  1291 I ActivityManager: Process com.lge.bnr (pid 6786) has died
,07-27 08:54:46.049   862  1946 I ActivityManager: Process com.google.android.setupwizard (pid 6890) has died
,07-27 08:54:46.061  2023  2023 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
07-27 08:54:46.064  1787  1787 I PhoneApp: onTrimMemory: 10
07-27 08:54:46.064  1787  1787 I PhoneApp: trim memory
,07-27 08:54:46.137  7065  7065 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(225): No need to run daily hygiene.
,07-27 08:54:46.166  7065  7065 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-27 08:54:46.167  7065  7065 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
07-27 08:54:46.174  7065  7065 I NotificationManager: com.android.vending: cancel(-1050172287) by com.android.vending
07-27 08:54:46.198  7065  7065 I Finsky  : [1] com.google.android.finsky.utils.bq.a(177): Enabling bucket experiment: factor=2.000, zeroDelta=0ms, forceNetwork=false
,07-27 08:54:46.214  2709  2725 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is notificationclass=?; selectionArgs[0] is com.google.android.finsky.download.DownloadBroadcastReceiver; sort is null.
,07-27 08:54:46.218  2709  2725 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@43f79b6 on behalf of 7065
07-27 08:54:46.231  7065  7065 I Finsky  : [1] com.google.android.finsky.utils.du.onTrimMemory(25): Memory trim requested to level 10
,07-27 08:54:46.236  7065  7065 I Finsky  : [1] com.google.android.finsky.receivers.j.a(1295): Installer kick - no action, not running yet
07-27 08:54:46.279  7065  7065 I Finsky  : [1] com.google.android.finsky.k.j.run(208): Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
07-27 08:54:46.280  7065  7065 I Finsky  : [1] com.google.android.finsky.k.j.run(214): Finished loading 1 libraries.
,07-27 08:54:46.298  1757  1757 D WearableService: callingUid 10006, callindPid: 1757
,07-27 08:54:46.301  7065  7065 I Finsky  : [1] com.google.android.finsky.c.l.a(270): result=false type=4
07-27 08:54:46.338  5349  5475 I Icing   : Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,07-27 08:54:46.346  7065  7065 I Finsky  : [1] com.google.android.finsky.services.bd.a(1052): Restore complete with 0 success and 0 failed.
07-27 08:54:46.356  7065  7065 E Finsky  : [1] com.google.android.finsky.wear.bo.a(837): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,07-27 08:54:46.356  7065  7065 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6394): Dropping command=send_installed_apps due to Gms not connected
07-27 08:54:46.376   862  2008 I ActivityManager: Process com.lge.appbox.client (pid 6930) has died
,07-27 08:54:46.459  5349  5475 I Icing   : Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,07-27 08:54:46.986   862  2370 I ActivityManager: Process com.android.gallery3d (pid 6955) has died
,07-27 08:54:47.009  5349  5360 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,07-27 08:54:48.322   295   356 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-27 08:54:52.773   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 08:54:52.773   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 08:54:52.773   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 173166471085; DSPS: 5765886; Offset : -2804524284
,07-27 08:54:53.327   295   356 I ThermalEngine: Sensor:pa_therm0:33000 mC
,07-27 08:54:53.552  5349  6537 I CheckinService: Done disabling old GoogleServicesFramework version
,07-27 08:54:57.854   862  1283 V AlarmManager: ELAPSED_WAKEUP set : Alarm{245f1b8b type 2 when 178235 android} when 178235
,07-27 08:54:57.928   862   862 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7117 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,07-27 08:54:58.073  7117  7117 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,07-27 08:54:58.207   862  1014 D BluetoothManagerService: Message: 20
07-27 08:54:58.207   862  1014 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@317123bd:true
,07-27 08:54:58.220  2074  2090 D BluetoothAdapterService(340792543): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@20c384ad
,07-27 08:54:58.222  2074  2091 D BluetoothAdapterService(340792543): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@20c384ad
07-27 08:54:58.332   295   356 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 08:54:58.354   862  1375 I ActivityManager: Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7158 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-27 08:54:58.386  7117  7117 V LGMDMManager: Create singleton instance
07-27 08:54:58.456  7117  7117 I AudioManager: getMode name:com.lge.qremote
,07-27 08:54:58.547   862  2008 I art     : Explicit concurrent mark sweep GC freed 25356(1227KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.238ms total 154.635ms
,07-27 08:54:58.577  7158  7158 D UEI.SmartControl: Quickset Services start...
,07-27 08:54:58.582  7158  7158 I UEI.SmartControl: Manufacture = LGE
07-27 08:54:58.584  7158  7158 D UEI.SmartControl: File observer start...
07-27 08:54:58.585  7158  7158 E UEI.SmartControl: IR Port is disabled: false
07-27 08:54:58.585  7158  7158 D UEI.SmartControl: Starting file observer...
07-27 08:54:58.585  7158  7158 D UEI.SmartControl: Extracting JNI libs...
07-27 08:54:58.586  7158  7158 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
07-27 08:54:58.805  7158  7158 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,07-27 08:54:58.808  7158  7158 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
07-27 08:54:58.808  7158  7158 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
07-27 08:54:58.841  7158  7158 I UEI.SmartControl: --- Selecting new region: 2
,07-27 08:54:58.842  7158  7158 I UEI.SmartControl: -- Running on KitKat(19) and above! JNI will be used.
07-27 08:54:58.848  7158  7158 D UEI.SmartControl: Platform has CIR...
07-27 08:54:58.849  7158  7158 D UEI.SmartControl: NO CIR support, need to check package...
07-27 08:54:58.850  7158  7158 I UEI.SmartControl: Model: LG-D722 uses JNI
07-27 08:54:58.852  7158  7158 D UEI.SmartControl: QS Service created
,07-27 08:54:58.873  7158  7158 E UEI.SmartControl: QS start get config
,07-27 08:54:58.920  7158  7158 D UEI.SmartControl: Loading JNI Libs...
,07-27 08:54:58.922  7158  7158 D UEI.SmartControl:  configuring local db...
07-27 08:54:59.109  7158  7158 D UEI.SmartControl:  ---- Has DB8: true
,07-27 08:54:59.116  7158  7158 D UEI.SmartControl: QS start statue = true Error code = 0
07-27 08:54:59.117  7158  7158 D UEI.SmartControl: QS version = v2.7.11.1_RC1
07-27 08:54:59.117  7158  7158 D UEI.SmartControl: QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
07-27 08:54:59.120  7158  7158 D UEI.SmartControl: IRRCDataComm has AudioManager!!!!.
,07-27 08:54:59.132  7158  7158 W irrc_jni: IRRCPlayer_nativeInit ++ 
07-27 08:54:59.132  7158  7158 D irrcClient: IrrcClient ++ 
07-27 08:54:59.132  7158  7158 D irrcClient: getIrrcService ++ 
,07-27 08:54:59.133  7158  7158 D irrcClient: getIrrcService -- 
07-27 08:54:59.133  7158  7158 D irrcClient: IrrcClient -- 
07-27 08:54:59.133  7158  7158 W irrc_jni: IRRCPlayer_nativeInit -- 
07-27 08:54:59.139  7158  7158 D UEI.SmartControl: Services init done
07-27 08:54:59.141  7158  7177 I UEI.SmartControl: Device manager: loading config....
07-27 08:54:59.142  7158  7158 D UEI.SmartControl: QS Service init finished
07-27 08:54:59.144  7158  7158 D UEI.SmartControl: QS Service version name: 0.1.73
,07-27 08:54:59.144  7158  7158 D UEI.SmartControl: QS Service version code: 1073
07-27 08:54:59.145  7158  7158 D UEI.SmartControl: Service requested: Control
07-27 08:54:59.148  7158  7177 D UEI.SmartControl: Config is loaded...
07-27 08:54:59.158  7158  7158 D UEI.SmartControl: Request IControl service: devices are loaded...
,07-27 08:54:59.161  7158  7158 D UEI.SmartControl: Internal service binding...
07-27 08:54:59.162  7158  7173 D UEI.SmartControl: -----IControl: 11
07-27 08:54:59.163  7158  7173 D UEI.SmartControl: Caller: com.lge.qremote
07-27 08:54:59.163  7158  7173 D UEI.SmartControl: ------------ IControl registerCallback...
,07-27 08:54:59.164  7158  7173 I UEI.SmartControl: Registering callback...
07-27 08:54:59.165  7158  7174 D UEI.SmartControl: -----IControl: 19
07-27 08:54:59.166  7158  7174 D UEI.SmartControl: Caller: com.lge.qremote
07-27 08:54:59.167  7158  7174 I UEI.SmartControl: Registering Services Ready callback...
07-27 08:54:59.167  7158  7174 I UEI.SmartControl: Notify client services are ready...
07-27 08:54:59.170  7158  7173 D UEI.SmartControl: -----IControl: 8
07-27 08:54:59.171  7158  7173 D UEI.SmartControl: Caller: com.lge.qremote
,07-27 08:54:59.178  7117  7117 I AudioManager: getMode name:com.lge.qremote
07-27 08:54:59.186  7158  7176 D UEI.SmartControl:  ----- QS SDK is ready!!!
07-27 08:54:59.187  7158  7176 I UEI.SmartControl: Notify AllClients services are ready: 0
,07-27 08:54:59.209  7117  7117 I AudioManager: getMode name:com.lge.qremote
,07-27 08:54:59.234  7117  7117 I AudioManager: getMode name:com.lge.qremote
,07-27 08:55:00.673  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 08:55:00.673  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
,07-27 08:55:00.684  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
07-27 08:55:00.688  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
,07-27 08:55:00.691  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
07-27 08:55:00.723  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
,07-27 08:55:00.727  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 08:55:03.336   295   356 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 08:55:04.142  7158  7178 D UEI.SmartControl: Internal timer expired: 1
,07-27 08:55:04.659   862  1283 D PowerManagerServiceEx: acquireWakeLockInternal: lock=566032396, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=862
,07-27 08:55:04.664   862  1283 V AlarmManager: ELAPSED_WAKEUP set : Alarm{11a69798 type 2 when 185039 com.google.android.gms} when 185039
,07-27 08:55:04.711   862   862 D PowerManagerServiceEx: releaseWakeLockInternal: lock=566032396 [*alarm*], flags=0x0
07-27 08:55:06.883  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,07-27 08:55:06.888   464   464 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-27 08:55:06.888  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 08:55:06.889  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 08:55:06.892  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 08:55:06.893  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
07-27 08:55:06.918  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-27 08:55:06.918  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,07-27 08:55:06.922  1873  2040 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 08:55:06.922  1873  2040 D LEDHandler: Battery Level Remaining: 100%
07-27 08:55:06.923  1873  2040 D LEDHandler: Battery Temp: 295, mChargingStatus=5, mChargingStop=false
07-27 08:55:06.923  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
07-27 08:55:06.924  1368  1368 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 08:55:06.936  2074  5905 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 08:55:06.942   862  1312 D WifiController: battery changed pluggedType: 2
07-27 08:55:06.943  1368  1368 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
07-27 08:55:06.943   862   862 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:55:06.943   862   862 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:55:06.956  1368  1368 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,07-27 08:55:08.341   295   356 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 08:55:12.773   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 08:55:12.774   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 08:55:12.774   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 193167276025; DSPS: 6421272; Offset : -2804511551
,07-27 08:55:13.345   295   356 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 08:55:18.350   295   356 I ThermalEngine: Sensor:pa_therm0:32000 mC
,07-27 08:55:23.354   295   356 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 08:55:27.945   862  1283 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1daf0bf1 type 2 when 208323 android} when 208323
,07-27 08:55:28.359   295   356 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 08:55:28.398  5349  7187 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,07-27 08:55:28.413   862   901 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 181525, reason: UserStart, SyncResult: databaseError: true stats []
,07-27 08:55:28.422   862   901 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 274478, reason: UserStart
07-27 08:55:28.422   862   901 I NotificationManager: android: cancelAsUser(716319171) by android
07-27 08:55:32.774   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 08:55:32.774   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 08:55:32.774   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 213168041174; DSPS: 7076657; Offset : -2804509707
,07-27 08:55:33.364   295   356 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 08:55:38.368   295   356 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 08:55:43.373   295   356 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 08:55:44.282  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 08:55:44.282  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 08:55:44.282  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 08:55:44.282  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-27 08:55:44.289  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 08:55:44.325   464   464 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-27 08:55:44.364  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 294
07-27 08:55:44.364  1368  1368 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 08:55:44.364  1368  1368 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 294
,07-27 08:55:44.367  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-27 08:55:44.369  1873  2040 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 08:55:44.369  1873  2040 D LEDHandler: Battery Level Remaining: 100%
07-27 08:55:44.369  1873  2040 D LEDHandler: Battery Temp: 294, mChargingStatus=5, mChargingStop=false
07-27 08:55:44.369  2074  5905 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 08:55:44.371  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-27 08:55:44.372   862   862 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:55:44.372   862   862 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:55:44.373   862  1312 D WifiController: battery changed pluggedType: 2
07-27 08:55:44.374  1368  1368 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 08:55:44.891   862  1283 V AlarmManager: ELAPSED_WAKEUP set : Alarm{194d3762 type 2 when 206008 android} when 206008
,07-27 08:55:48.377   295   356 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 08:55:52.775   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 08:55:52.775   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 08:55:52.775   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 233168704759; DSPS: 7732039; Offset : -2804517482
,07-27 08:55:53.382   295   356 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 08:55:57.964   862  1283 V AlarmManager: ELAPSED_WAKEUP set : Alarm{48ca0f3 type 2 when 238343 android} when 238343
,07-27 08:55:58.387   295   356 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 08:56:00.084  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 08:56:00.084  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 08:56:00.084  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
,07-27 08:56:00.089  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 08:56:00.089  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
07-27 08:56:00.090  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
07-27 08:56:00.090  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 08:56:03.391   295   356 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 08:56:07.026  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 08:56:07.026  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 08:56:07.026  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 08:56:07.026  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-27 08:56:07.029   464   464 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-27 08:56:07.030  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 08:56:07.068  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 293
07-27 08:56:07.069  1368  1368 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 08:56:07.069  1368  1368 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 293
,07-27 08:56:07.072  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-27 08:56:07.072  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-27 08:56:07.074  1873  2040 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 08:56:07.074  1873  2040 D LEDHandler: Battery Level Remaining: 100%
07-27 08:56:07.074  1873  2040 D LEDHandler: Battery Temp: 293, mChargingStatus=5, mChargingStop=false
07-27 08:56:07.076  1368  1368 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 08:56:07.078  2074  5905 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 08:56:07.080   862   862 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:56:07.081   862   862 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:56:07.082   862  1312 D WifiController: battery changed pluggedType: 2
,07-27 08:56:08.396   295   356 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 08:56:12.776   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 08:56:12.776   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 08:56:12.776   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 253169439387; DSPS: 8387423; Offset : -2804515354
,07-27 08:56:13.400   295   356 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 08:56:18.405   295   356 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 08:56:23.409   295   356 I ThermalEngine: Sensor:pa_therm0:31000 mC
,07-27 08:56:28.414   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:56:32.776   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 08:56:32.776   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 08:56:32.776   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 273170233443; DSPS: 9042809; Offset : -2804514885
,07-27 08:56:33.419   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:56:38.423   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:56:40.422  1757  4120 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-27 08:56:43.428   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:56:48.432   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:56:52.777   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 08:56:52.777   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 08:56:52.777   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 293170973643; DSPS: 9698193; Offset : -2804506534
,07-27 08:56:53.437   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:56:58.441   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:57:00.039  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 08:57:00.039  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 08:57:00.039  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
,07-27 08:57:00.043  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 08:57:00.043  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
07-27 08:57:00.044  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
07-27 08:57:00.044  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 08:57:03.446   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:57:07.186  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 08:57:07.186  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 08:57:07.186  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 08:57:07.186  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-27 08:57:07.189   464   464 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-27 08:57:07.190  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 08:57:07.228  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
07-27 08:57:07.229  1368  1368 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 08:57:07.229  1368  1368 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
,07-27 08:57:07.232  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-27 08:57:07.233  1873  2040 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 08:57:07.233  1873  2040 D LEDHandler: Battery Level Remaining: 100%
07-27 08:57:07.234  1873  2040 D LEDHandler: Battery Temp: 290, mChargingStatus=5, mChargingStop=false
07-27 08:57:07.234  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-27 08:57:07.236  1368  1368 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 08:57:07.238  2074  5905 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 08:57:07.240   862   862 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:57:07.240   862   862 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:57:07.242   862  1312 D WifiController: battery changed pluggedType: 2
,07-27 08:57:08.450   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:57:12.778   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 08:57:12.778   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 08:57:12.778   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 313171730406; DSPS: 10353578; Offset : -2804513127
,07-27 08:57:13.455   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:57:18.460   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:57:23.464   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:57:28.469   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:57:32.779   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 08:57:32.779   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 08:57:32.779   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 333172477847; DSPS: 11008962; Offset : -2804497848
,07-27 08:57:33.473   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:57:38.478   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:57:41.425   862  3146 I LocationManagerService: remove 1e04c23
,07-27 08:57:41.429   862  3146 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
07-27 08:57:41.429   862  3146 D LocationManagerService: getAllProviders()=[passive, gps, network]
07-27 08:57:41.429   862  3146 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
07-27 08:57:41.430   862  3146 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
07-27 08:57:41.430   862  3146 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
07-27 08:57:43.482   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:57:48.487   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:57:52.779   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 08:57:52.779   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 08:57:52.779   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 353173156172; DSPS: 11664345; Offset : -2804521349
,07-27 08:57:53.492   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:57:58.496   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:58:00.038  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 08:58:00.038  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 08:58:00.038  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
,07-27 08:58:00.042  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 08:58:00.042  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
07-27 08:58:00.043  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
07-27 08:58:00.044  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 08:58:03.501   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:58:07.346  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 08:58:07.346  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 08:58:07.347  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 08:58:07.347  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-27 08:58:07.350  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 08:58:07.353   464   464 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-27 08:58:08.505   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:58:12.780   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 08:58:12.780   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 08:58:12.780   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 373173925436; DSPS: 12319730; Offset : -2804515362
,07-27 08:58:13.510   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:58:18.519   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:58:23.523   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:58:28.528   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:58:32.781   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 08:58:32.781   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 08:58:32.781   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 393174686782; DSPS: 12975115; Offset : -2804516956
,07-27 08:58:33.532   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:58:38.537   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:58:43.542   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:58:48.546   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:58:52.782   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 08:58:52.782   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 08:58:52.782   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 413175371670; DSPS: 13630497; Offset : -2804503325
,07-27 08:58:53.551   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:58:58.555   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:59:00.001   862  1283 D PowerManagerServiceEx: acquireWakeLockInternal: lock=566032396, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=862
,07-27 08:59:00.022   862   862 D PowerManagerServiceEx: releaseWakeLockInternal: lock=566032396 [*alarm*], flags=0x0
,07-27 08:59:00.039  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 08:59:00.040  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 08:59:00.040  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
,07-27 08:59:00.044  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 08:59:00.044  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
07-27 08:59:00.045  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
07-27 08:59:00.046  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 08:59:03.560   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:59:07.511  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 08:59:07.511  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,07-27 08:59:07.514   464   464 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-27 08:59:07.514  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 08:59:07.515  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 08:59:07.515  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
07-27 08:59:07.547  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
,07-27 08:59:07.551  1368  1368 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 08:59:07.551  1368  1368 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
07-27 08:59:07.554  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-27 08:59:07.555  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-27 08:59:07.556  1873  2040 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 08:59:07.556  1873  2040 D LEDHandler: Battery Level Remaining: 100%
07-27 08:59:07.556  1873  2040 D LEDHandler: Battery Temp: 289, mChargingStatus=5, mChargingStop=false
07-27 08:59:07.559  2074  5905 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-27 08:59:07.564  1368  1368 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 08:59:07.567   862   862 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:59:07.567   862   862 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 08:59:07.568   862  1312 D WifiController: battery changed pluggedType: 2
07-27 08:59:08.565   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:59:12.782   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 08:59:12.782   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 08:59:12.783   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 433176249944; DSPS: 14285886; Offset : -2804510269
,07-27 08:59:13.569   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:59:18.574   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:59:23.578   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:59:28.583   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:59:31.293  1757  1757 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 08:59:31.308  1757  1757 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 08:59:31.312  1757  1757 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 08:59:31.398  1757  3060 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:59:31.398  1757  3060 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:59:31.399  1757  3060 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:59:31.399  1757  3060 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,07-27 08:59:31.402   275   910 E BandwidthController: [LG DATA] No such appUid: 10006
07-27 08:59:31.402   275   910 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-27 08:59:31.404   275  7229 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-27 08:59:31.405   275  7229 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:59:31.405   275  7229 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-27 08:59:31.406   275  7229 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-27 08:59:31.451   275  7229 D libc-netbsd: res_queryN name = xxxxx succeed
,07-27 08:59:31.455  1757  3060 I System.out: propertyValue:false
07-27 08:59:31.524  1757  3060 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:59:31.524  1757  3060 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-27 08:59:31.770   862  1938 I NotificationManager: android: cancelAsUser(2) by android
,07-27 08:59:31.791  1757  3060 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,07-27 08:59:31.801   862  2008 I NotificationManager: android: cancelAsUser(2) by android
07-27 08:59:31.837  5349  6399 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:59:31.837  5349  6399 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
07-27 08:59:31.838  5349  6399 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:59:31.838  5349  6399 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,07-27 08:59:31.841   275   910 E BandwidthController: [LG DATA] No such appUid: 10006
07-27 08:59:31.841   275   910 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
07-27 08:59:31.843   275  7231 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-27 08:59:31.843   275  7231 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:59:31.843   275  7231 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-27 08:59:31.844   275  7231 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-27 08:59:31.894   275  7231 D libc-netbsd: res_queryN name = xxxxx succeed
,07-27 08:59:31.898  5349  6399 I System.out: propertyValue:false
07-27 08:59:31.963  5349  6399 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:59:31.963  5349  6399 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-27 08:59:32.783   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 08:59:32.783   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 08:59:32.783   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 453177015665; DSPS: 14941271; Offset : -2804509076
,07-27 08:59:33.587   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:59:38.592   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:59:43.596   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:59:45.916  7065  7088 I PlayCommon: [834] com.google.android.play.a.al.e(730): Preparing logs for uploading
,07-27 08:59:45.935  1757  1757 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 08:59:45.947  1757  1757 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-27 08:59:45.949  1757  1757 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 08:59:45.997   862  1923 I NotificationManager: android: cancelAsUser(2) by android
,07-27 08:59:46.004  7065  7088 I PlayCommon: [834] com.google.android.play.a.al.a(870): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
07-27 08:59:46.014  7065  7088 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:59:46.014  7065  7088 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,07-27 08:59:46.018  7065  7088 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
07-27 08:59:46.018  7065  7088 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:59:46.018   275   910 E BandwidthController: [LG DATA] No such appUid: 10036
07-27 08:59:46.018   275   910 D DnsProxyListener: App 10036 tries DNS query. Accept family:0 protocol:0
07-27 08:59:46.020   275  7235 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
07-27 08:59:46.020   275  7235 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
07-27 08:59:46.021   275  7235 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
07-27 08:59:46.021   275  7235 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
07-27 08:59:46.021   275  7235 D libc-netbsd: res_queryN name = xxxxx succeed
07-27 08:59:46.023  7065  7088 I System.out: propertyValue:false
07-27 08:59:46.324  7065  7088 I PlayCommon: [834] com.google.android.play.a.al.a(945): Successfully uploaded logs.
,07-27 08:59:48.601   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:59:52.784   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 08:59:52.784   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 08:59:52.784   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 473177741595; DSPS: 15596655; Offset : -2804513823
,07-27 08:59:53.606   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 08:59:58.610   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:00:00.039  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:00:00.039  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:00:00.039  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:00:00.043  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:00:00.043  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:00:00.044  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:00:00.045  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:00:03.615   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:00:07.678   464   464 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-27 09:00:07.681  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 09:00:07.686  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:00:07.686  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 09:00:07.686  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
07-27 09:00:07.687  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 09:00:07.721  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
07-27 09:00:07.721  1368  1368 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:00:07.721  1368  1368 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
,07-27 09:00:07.725  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-27 09:00:07.725  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-27 09:00:07.727  1873  2040 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 09:00:07.727  1873  2040 D LEDHandler: Battery Level Remaining: 100%
07-27 09:00:07.727  1873  2040 D LEDHandler: Battery Temp: 288, mChargingStatus=5, mChargingStop=false
07-27 09:00:07.729  1368  1368 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:00:07.731  2074  5905 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 09:00:07.733   862   862 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:00:07.733   862   862 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:00:07.735   862  1312 D WifiController: battery changed pluggedType: 2
,07-27 09:00:08.619   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:00:12.785   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:00:12.785   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:00:12.785   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 493178585806; DSPS: 16252042; Offset : -2804493899
,07-27 09:00:13.624   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:00:18.628   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:00:23.633   295   356 I ThermalEngine: Sensor:pa_therm0:30000 mC
,07-27 09:00:28.638   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:00:32.785   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:00:32.786   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:00:32.786   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 513179340017; DSPS: 16907427; Offset : -2804502185
,07-27 09:00:33.642   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:00:38.647   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:00:43.651   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:00:48.656   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:00:52.786   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:00:52.786   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:00:52.786   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 533180111052; DSPS: 17562812; Offset : -2804494089
,07-27 09:00:53.660   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:00:58.665   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:01:00.039  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:01:00.039  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:01:00.039  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:01:00.043  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:01:00.043  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:01:00.044  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:01:00.045  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:01:03.669   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:01:07.826  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 09:01:07.826  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:01:07.826  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 09:01:07.826  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-27 09:01:07.829   464   464 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-27 09:01:07.830  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 09:01:07.868  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
07-27 09:01:07.868  1368  1368 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:01:07.868  1368  1368 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
,07-27 09:01:07.871  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-27 09:01:07.871  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-27 09:01:07.872  1873  2040 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 09:01:07.872  1873  2040 D LEDHandler: Battery Level Remaining: 100%
07-27 09:01:07.872  1873  2040 D LEDHandler: Battery Temp: 287, mChargingStatus=5, mChargingStop=false
07-27 09:01:07.876  1368  1368 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:01:07.878  2074  5905 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 09:01:07.880   862   862 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:01:07.880   862   862 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 09:01:07.884   862  1312 D WifiController: battery changed pluggedType: 2
07-27 09:01:08.674   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:01:12.787   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:01:12.787   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:01:12.787   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 553180860523; DSPS: 18218197; Offset : -2804509563
,07-27 09:01:13.679   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:01:18.683   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:01:23.688   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:01:28.692   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:01:32.788   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:01:32.788   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:01:32.788   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 573181635620; DSPS: 18873583; Offset : -2804525918
,07-27 09:01:33.697   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:01:38.701   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:01:43.706   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:01:48.711   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:01:52.789   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:01:52.789   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:01:52.789   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 593182401550; DSPS: 19528968; Offset : -2804522901
,07-27 09:01:53.715   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:01:58.720   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:02:00.039  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:02:00.039  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:02:00.039  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:02:00.043  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:02:00.043  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:02:00.044  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:02:00.045  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:02:03.724   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:02:07.986  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 09:02:07.986  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:02:07.986  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 09:02:07.986  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-27 09:02:07.989   464   464 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-27 09:02:07.990  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 09:02:08.729   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:02:12.789   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:02:12.789   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:02:12.789   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 613183149771; DSPS: 20184352; Offset : -2804507076
,07-27 09:02:13.734   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:02:18.738   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:02:23.743   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:02:28.747   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:02:32.790   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:02:32.790   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:02:32.790   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 633183837888; DSPS: 20839735; Offset : -2804522921
,07-27 09:02:33.752   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:02:38.756   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:02:43.761   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:02:48.766   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:02:52.791   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:02:52.791   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:02:52.791   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 653184635121; DSPS: 21495121; Offset : -2804517165
,07-27 09:02:53.770   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:02:58.775   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:03:00.040  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:03:00.040  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:03:00.040  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:03:00.044  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:03:00.044  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:03:00.045  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:03:00.046  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:03:03.779   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:03:08.146  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 09:03:08.146  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:03:08.146  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 09:03:08.146  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-27 09:03:08.149   464   464 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-27 09:03:08.150  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 09:03:08.188  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
07-27 09:03:08.188  1368  1368 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:03:08.188  1368  1368 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
,07-27 09:03:08.191  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-27 09:03:08.191  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-27 09:03:08.192  1873  2040 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 09:03:08.192  1873  2040 D LEDHandler: Battery Level Remaining: 100%
07-27 09:03:08.192  1873  2040 D LEDHandler: Battery Temp: 286, mChargingStatus=5, mChargingStop=false
07-27 09:03:08.196  1368  1368 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:03:08.198  2074  5905 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 09:03:08.200   862   862 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:03:08.200   862   862 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 09:03:08.204   862  1312 D WifiController: battery changed pluggedType: 2
07-27 09:03:08.784   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:03:12.794   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:03:12.794   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:03:12.794   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 673188024279; DSPS: 22150592; Offset : -2804517308
,07-27 09:03:13.788   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:03:18.793   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:03:23.797   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:03:28.802   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:03:32.795   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:03:32.795   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:03:32.795   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 693188692813; DSPS: 22805974; Offset : -2804518389
,07-27 09:03:33.809   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:03:38.813   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:03:43.818   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:03:48.822   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:03:52.795   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:03:52.796   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:03:52.796   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 713189358847; DSPS: 23461356; Offset : -2804523872
,07-27 09:03:53.827   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:03:58.832   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:04:00.039  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:04:00.039  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:04:00.039  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:04:00.043  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:04:00.043  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:04:00.044  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:04:00.045  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:04:03.836   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:04:08.307   464   464 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-27 09:04:08.310  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 09:04:08.310  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:04:08.310  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 09:04:08.310  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
07-27 09:04:08.311  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 09:04:08.841   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:04:12.796   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:04:12.796   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:04:12.797   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 733190347850; DSPS: 24116748; Offset : -2804512005
,07-27 09:04:13.845   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:04:18.850   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:04:23.854   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:04:28.859   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:04:32.797   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:04:32.797   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:04:32.797   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 753191003729; DSPS: 24772129; Offset : -2804496318
,07-27 09:04:33.864   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:04:38.868   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:04:43.873   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:04:48.877   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:04:52.798   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:04:52.798   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:04:52.798   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 773191773929; DSPS: 25427515; Offset : -2804519654
,07-27 09:04:53.882   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:04:58.887   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:05:00.038  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:05:00.038  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:05:00.038  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:05:00.042  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:05:00.042  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:05:00.043  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:05:00.044  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:05:03.891   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:05:08.465   464   464 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-27 09:05:08.469  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 09:05:08.475  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 09:05:08.475  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:05:08.475  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 09:05:08.475  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
07-27 09:05:08.508  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
07-27 09:05:08.508  1368  1368 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:05:08.508  1368  1368 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,07-27 09:05:08.511  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
07-27 09:05:08.511  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
07-27 09:05:08.513  1873  2040 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
07-27 09:05:08.513  1873  2040 D LEDHandler: Battery Level Remaining: 100%
07-27 09:05:08.513  1873  2040 D LEDHandler: Battery Temp: 285, mChargingStatus=5, mChargingStop=false
07-27 09:05:08.516  1368  1368 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
07-27 09:05:08.518  2074  5905 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-27 09:05:08.520   862   862 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 09:05:08.521   862   862 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 09:05:08.524   862  1312 D WifiController: battery changed pluggedType: 2
07-27 09:05:08.896   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:05:12.799   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:05:12.799   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:05:12.799   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 793192528452; DSPS: 26082899; Offset : -2804497161
,07-27 09:05:13.900   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:05:18.905   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:05:23.909   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:05:28.914   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:05:32.799   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:05:32.799   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:05:32.799   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 813193198028; DSPS: 26738281; Offset : -2804499311
,07-27 09:05:33.919   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:05:38.923   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:05:43.928   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:05:48.932   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:05:52.800   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:05:52.800   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:05:52.800   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 833193943385; DSPS: 27393666; Offset : -2804516763
,07-27 09:05:53.937   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:05:58.941   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:06:00.038  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:06:00.038  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:06:00.038  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:06:00.042  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:06:00.042  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:06:00.043  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:06:00.044  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:06:03.946   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:06:08.625   464   464 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,07-27 09:06:08.628  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 09:06:08.635  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 09:06:08.635  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:06:08.636  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 09:06:08.636  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
07-27 09:06:08.951   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:06:12.801   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:06:12.801   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:06:12.801   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 853194685200; DSPS: 28049050; Offset : -2804507423
,07-27 09:06:13.955   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:06:18.960   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:06:23.964   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:06:28.969   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:06:32.801   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:06:32.802   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:06:32.802   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 873195354464; DSPS: 28704432; Offset : -2804509622
,07-27 09:06:33.973   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:06:38.978   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:06:43.983   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:06:48.987   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:06:52.802   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:06:52.802   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:06:52.802   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 893196116174; DSPS: 29359817; Offset : -2804510878
,07-27 09:06:53.992   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:06:58.996   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:07:00.038  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:07:00.038  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:07:00.038  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:07:00.042  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:07:00.042  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:07:00.043  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:07:00.044  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:07:04.001   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:07:08.786  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 09:07:08.786  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:07:08.786  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 09:07:08.786  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-27 09:07:08.789   464   464 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-27 09:07:08.790  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 09:07:09.005   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:07:12.803   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:07:12.803   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:07:12.803   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 913196782105; DSPS: 30015199; Offset : -2804516698
,07-27 09:07:14.010   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:07:19.015   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:07:24.019   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:07:29.024   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:07:32.804   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:07:32.804   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:07:32.804   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 933197548451; DSPS: 30670584; Offset : -2804512901
,07-27 09:07:34.028   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:07:39.033   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:07:44.038   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:07:49.042   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:07:52.804   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:07:52.804   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:07:52.804   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 953198266464; DSPS: 31325967; Offset : -2804496715
,07-27 09:07:54.047   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:07:59.051   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:08:00.046  1368  1368 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
07-27 09:08:00.046  1368  1368 I KeyguardUpdateMonitor: called onTimeUpdated()
07-27 09:08:00.046  1368  1368 I [SystemUI]Clock: called onTimeUpdated()
,07-27 09:08:00.050  1368  1368 I LgeClockWidgetControlView: called onTimeUpdated()
07-27 09:08:00.050  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:08:00.051  1368  1368 I [SystemUI]DateView: called onTimeUpdated()
07-27 09:08:00.052  1368  1368 D KeyguardUpdateMonitor: handleTimeUpdate
07-27 09:08:04.056   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:08:08.946  1368  1368 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
07-27 09:08:08.946  1368  1368 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
07-27 09:08:08.946  1368  1368 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
07-27 09:08:08.946  1368  1368 I [SystemUI]LGPowerUI: On Skip Timer : true
,07-27 09:08:08.949   464   464 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
07-27 09:08:08.950  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
07-27 09:08:09.060   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,07-27 09:08:12.805   862  1026 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
07-27 09:08:12.805   862  1026 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
07-27 09:08:12.805   862  1026 D sensors_hal_Time: tsOffsetIs: Apps: 973198932446; DSPS: 31981349; Offset : -2804502666
,07-27 09:08:14.065   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC

```
