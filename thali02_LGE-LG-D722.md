#### Test 50650278eab32a5_thali02_LGE-LG-D722 Logs


```
--------- beginning of system
W/ProcessCpuTracker(  969): Skipping unknown process pid 5274
,--------- beginning of main
D/AlertService( 5238): Beginning updateAlertNotification
D/AlertService( 5238): No fired or scheduled alerts
I/NotificationManager( 5238): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 5238): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 5238): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 5238): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 5238): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5238): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 5238): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 5238): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 5238): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 5238): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 5238): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 5238): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 5238): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 5238): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 5238): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 5238): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 5238): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 5238): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5238): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 5238): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 5238): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 5238): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AlarmScheduler( 5238): No events found starting within 1 week.
I/ActivityManager(  969): Killing 5098:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
W/libprocessgroup(  969): failed to open /acct/uid_10069/pid_5098/cgroup.procs: No such file or directory
D/AndroidRuntime( 5279): 
D/AndroidRuntime( 5279): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5279): CheckJNI is OFF
D/AndroidRuntime( 5279): Calling main entry com.android.commands.am.Am
I/ActivityManager(  969): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  969): setTaskToReturnTo : TaskRecord{365cba6 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  969): setTaskToReturnTo : TaskRecord{365cba6 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  969): AppWindowTokenEx init.. 
D/ContextHelper(  969): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/SplitWindow(  969): check instance of lgWin Window{3398cd83 u0 Starting com.test.thalitest}
I/[LGHome]EVENT( 1971): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  969): Focus left window: Window{2b66e6b u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5279): Shutting down VM
I/ActivityManager(  969): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5308 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1971): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/art     (  311): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 34.475ms
I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 814us total 23.732ms
I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 354us total 31.876ms
I/HotwordDetector( 2049): Closing mic
I/MicrophoneInputStream( 2049): mic_close com.google.android.apps.gsa.speech.audio.u@2b6213f9
V/AudioRecord( 2049): stop()
D/AudioRecord( 2049): AudioRecord->stop()
V/AudioFlinger(  282): RecordHandle::stop()
V/AudioFlinger(  282): RecordThread::stop
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
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb3a6a000
D/audio_hw_primary(  282): in_standby: enter: stream (0xb546e420) usecase(7: audio-record)
,I/[LGHome]EVENT( 1971): [Launcher.java:5214:onStop()]onStop
V/audio_hw_primary(  282): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  282): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  282): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  282): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  282): disable_audio_route: exit
E/audio_hw_primary(  282): disable_snd_device: enter 144
D/hardware_info(  282): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  282): disable_snd_device: snd_device(144: lg-vr-handset-mic)
I/WindowStateAnimator(  969): Starting window displayed
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
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyService(  282): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  282): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  282): setParameters(): io 17, keyvalue hotword_active=0, calling pid 282
V/AudioFlinger(  282): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  282): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  282): RecordThread: loop starting
V/AudioFlinger(  282): processConfigEvents_l() remaining events 1
I/SystemUI[Framework](  969): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/audio_hw_primary(  282): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  282): in_set_parameters: exit: status(0)
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb3a6a000
V/AudioFlinger(  282): RecordThread: loop stopping
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
W/PhoneWindowManagerEx(  969): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  969): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  969): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PhoneStatusBar( 1375): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
I/SystemUI[Framework](  969): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@17543b6a,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  969): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1375): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1375):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1375): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1375): draw background and invalidate : color = e000000
D/BarTransitions( 1375): draw background and invalidate : color = b0b0b0b
V/AudioRecord( 2049): stop()
V/AudioRecord( 2049): stop()
V/AudioRecord( 2049): stop()
V/AudioFlinger(  282): releasing 16 from 2049 for -1
V/AudioFlinger(  282):  decremented refcount to 0
V/AudioFlinger(  282): purging stale effects
V/AudioFlinger(  282): RecordHandle::stop()
V/AudioFlinger(  282): RecordThread::stop
V/AudioPolicyManager(  282): releaseInput() 17
V/AudioPolicyManager(  282): closeInput(17)
V/AudioFlinger(  282): closeInput() 17
V/AudioSystem(  282): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): ThreadBase::exit
V/AudioFlinger(  282): RecordThread: loop starting
V/AudioSystem( 2109): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  969): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3072): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): RecordThread 0xb3a6a000 exiting
V/AudioSystem( 1844): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  282): adev_close_input_stream: enter:stream_handle(0xb546e420)
D/audio_hw_primary(  282): in_standby: enter: stream (0xb546e420) usecase(7: audio-record)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioSystem( 2049): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  282): AudioCommandThread() adding update audio port list
V/AudioSystem( 1375): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  282): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyManager(  282): releaseInput() exit
V/AudioFlinger(  282): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  282): removeClient_l() pid 2049, calling pid 282
I/HotwordRecognitionRnr( 2049): Stopping hotword detection.
I/HotwordRecognitionRnr( 2049): Hotword detection finished
V/AlarmManager(  969): RTC_WAKEUP set : Alarm{25ec69fb type 0 when 1449668677858 com.android.vending} when 1449668677858
D/ContextHelper( 5308): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 5308): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
D/Finsky  ( 4892): [570] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 4892): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/LibraryLoader( 5308): Time to load native libraries: 2 ms (timestamps 2216-2218)
I/LibraryLoader( 5308): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5308): Binding Chromium to main looper Looper (main, tid 1) {34ce0241}
I/LibraryLoader( 5308): Expected native library version number "",actual native library version number ""
I/chromium( 5308): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5308): Initializing chromium process, singleProcess=true
W/art     ( 5308): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5308): ApplicationContext is null in ApplicationStatus
W/chromium( 5308): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 5308): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5308): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5308): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5308): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5308): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5308): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5308): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5308): Remote Branch: 
I/Adreno-EGL( 5308): Local Patches: 
I/Adreno-EGL( 5308): Reconstruct Branch: 
V/AudioPolicyService(  282): registerClient() client 0xb551c860, uid 10316
,D/BluetoothManagerService(  969): Message: 20
D/BluetoothManagerService(  969): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2aafc430:true
D/BluetoothAdapter( 5308): 112689533: getState() :  mService = null. Returning STATE_OFF
,I/art     ( 2009): Explicit concurrent mark sweep GC freed 12638(756KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 11MB/19MB, paused 1.834ms total 60.465ms
,W/art     ( 5308): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5308): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5308): CordovaWebView is running on device made by: LGE
,W/art     ( 5308): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5308): Attempt to remove local handle scope entry from IRT, ignoring
,I/Activity( 5308): Activity.onPostResume() called 
,D/OpenGLRenderer( 5308): Render dirty regions requested: true
I/OpenGLRenderer( 5308): Initialized EGL, version 1.4
D/OpenGLRenderer( 5308): Enabling debug mode 0
,D/Atlas   ( 5308): Validating map...
,D/SplitWindow(  969): check instance of lgWin Window{33149960 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5308): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  969): Focus entered window: Window{33149960 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  969): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  969): Displayed com.test.thalitest/.MainActivity: +1s265ms
I/Timeline(  969): Timeline: Activity_windows_visible id: ActivityRecord{1ec879e7 u0 com.test.thalitest/.MainActivity t220} time:92927
I/Timeline( 5308): Timeline: Activity_idle id: android.os.BinderProxy@1910c3ed time:92947
,W/BindingManager( 5308): Cannot call determinedVisibility() - never saw a connection for the pid: 5308
,D/JsMessageQueue( 5308): Set native->JS mode to OnlineEventsBridgeMode
,I/ThermalEngine(  301): Sensor:pa_therm0:30000 mC
,W/PluginManager( 5308): THREAD WARNING: exec() call to CoreAndroid.show blocked the main thread for 17ms. Plugin should use CordovaInterface.getThreadPool().
,D/jxcore_app_log( 5308): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622757376
D/JX-Cordova( 5308): jxcore cordova android initializing
,I/art     ( 5308): CheckpointMarkThreadRoots callback created = 0x9a5993f0
,I/art     ( 5308): CheckpointMarkThreadRoots callback created = 0x9a5993c0
,I/art     (  969): Explicit concurrent mark sweep GC freed 15705(736KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/34MB, paused 2.343ms total 185.802ms
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 95023281166; DSPS: 3211645; Offset : -2990115587
,W/jxcore-log( 5308): Initializing JXcore engine
,W/jxcore-log( 5308): JXcore engine is ready
W/jxcore-log( 5308): Starting JXcore engine
,W/.test.thalitest( 5308): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6551]" dev="sockfs" ino=6551 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5308): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 5308): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6743]" dev="sockfs" ino=6743 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 5308): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 5308): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 5308): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[25270]" dev="sockfs" ino=25270 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 5308): Platform android
W/jxcore-log( 5308): 
,W/jxcore-log( 5308): Process ARCH arm
W/jxcore-log( 5308): 
I/jxcore-log( 5308): JXcore Cordova bridge is ready!
I/jxcore-log( 5308): 
,W/jxcore-log( 5308): JXcore engine is started
I/Choreographer( 5308): Skipped 195 frames!  The application may be doing too much work on its main thread.
I/chromium( 5308): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
E/jxcore  ( 5308): Error!: missing ) after argument list
E/jxcore  ( 5308): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 5308): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,D/InputDispatcher(  969): Focus left window: Window{33149960 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/PermissionCache(  246): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (937 us)
,W/PluginManager( 5308): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 32ms. Plugin should use CordovaInterface.getThreadPool().
I/[LGHome]EVENT( 1971): [Launcher.java:5203:onStart()]onStart
,I/[LGHome]EVENT( 1971): [Launcher.java:776:onResume()]onResume
,I/[LGHome]LGActivityUtil( 1971): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1971): [Launcher.java:929:onResume()]onResume end
I/Activity( 1971): Activity.onPostResume() called 
D/WeatherAncestor( 2652): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 14:44:43
D/UpdateThreadPoolManager( 2652): 2 : This is isUpdating : false
,I/SystemUI[Framework](  969): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  969): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  969): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  969): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  969): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@17543b6a,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  969): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1375): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/InputDispatcher(  969): Focus entered window: Window{2b66e6b u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/[LGHome]LGWallpaperInfo( 1971): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1971): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
D/WeatherService( 2652): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2652): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherAncestor( 2652): 2 : shouldTimeTickRegistered().........
D/WeatherAncestor( 2652): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 14:44:43
D/WeatherService( 2652): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
,W/ActivityManager(  969): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2652): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2652): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2652): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2652): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
D/WeatherService( 2652): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2652): 2 : This is isUpdating : false
D/WeatherService( 2652): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2652): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2652): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2652): 2 : Fixed theme : optimus
I/[LGHome]EVENT( 1971): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1971): [setNavigationBarColor] color=0x 0
D/WeatherReflect( 2652): 2 : Map key string is -2
W/InputMethodManagerService(  969): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,W/IInputConnectionWrapper( 5308): showStatusIcon on inactive InputConnection
D/lim     ( 2652): 2 : time = 14:44
I/WeatherReflect( 2652): Model Name : LG-D722
D/WeatherTheme( 2652): 2 : exactly same view!
D/WeatherTheme( 2652): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
W/ActivityManager(  969): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2652): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2652): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2652): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/Timeline( 1971): Timeline: Activity_idle id: android.os.BinderProxy@2179b9d7 time:97308
,I/SystemUI[Framework](  969): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
D/PhoneStatusBar( 1375): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1375): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1375):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1375): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx(  969): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  969): setLGSystemUiVisibility(0x0)
,D/StatusBarManagerServiceEx(  969): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  969): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@17543b6a,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  969): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/BarTransitions( 1375): draw background and invalidate : color = f2000000
D/BarTransitions( 1375): draw background and invalidate : color = eee5e5e5
I/HotwordRecognitionRnr( 2049): Starting hotword detection.
,I/MicrophoneInputStream( 2049): mic_starting com.google.android.apps.gsa.speech.audio.u@366aee62
V/AudioRecord( 2049): set(): inputSource 1999, sampleRate 16000, format 0x1, channelMask 0x10, frameCount 128000, notificationFrames 0, sessionId 0, transferType 0, flags 0
,V/AudioRecord( 2049): set(): mSessionId 22
,V/AudioPolicyManager(  282): getInput() inputSource 1999, samplingRate 16000, format 1, channelMask 10, session 22, flags 0
V/AudioPolicyManager(  282): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  282): isPlaybackThread 0,isRecordThread 1
D/audio_hw_primary(  282): adev_open_input_stream: enter: sample_rate(16000) channel_mask(0x10) devices(0x80000004)        stream_handle(0xb546e420)
V/audio_hw_primary(  282): adev_open_input_stream: exit
V/AudioFlinger(  282): openInput_l() openInputStream returned input 0xb546e420, SamplingRate 16000, Format 0x1, Channels 10, flags 0, status 0
V/AudioFlinger(  282): openInput_l() created record thread: ID 23 thread 0xb3a6a000
V/AudioSystem(  282): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 2049): ioConfigChanged() event 3, ioHandle 23
V/AudioPolicyService(  282): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  282): inserting command: 9 at index 0, num commands 0
V/AudioSystem( 1375): ioConfigChanged() event 3, ioHandle 23
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioSystem( 1844): ioConfigChanged() event 3, ioHandle 23
,V/AudioSystem( 2109): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 3072): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem(  969): ioConfigChanged() event 3, ioHandle 23
I/AudioFlinger(  282): AudioFlinger's thread 0xb3a6a000 ready to run
V/AudioFlinger(  282): openRecord() lSessionId: 22 input 23
D/audio_hw_primary(  282): in_standby: enter: stream (0xb546e420) usecase(7: audio-record)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioFlinger(  282): getOrphanEffectChain_l session 22 index -2
D/audio_hw_primary(  282): in_standby: enter: stream (0xb546e420) usecase(7: audio-record)
,V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioFlinger(  282): RecordThread: loop stopping
V/AudioFlinger(  282): acquiring 22 from 2049, for -1
V/AudioFlinger(  282):  added new entry for 22
V/AudioRecord( 2049): start, sync event 0 trigger session 0
V/AudioRecord( 2049): mAudioRecord->start()
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
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb3a6a000
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
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyService(  282): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing set parameters string hotword_active=1, io 23
V/AudioFlinger(  282): setParameters(): io 23, keyvalue hotword_active=1, calling pid 282
V/AudioFlinger(  282): ThreadBase::setParameters() hotword_active=1
V/AudioFlinger(  282): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  282): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  282): in_set_parameters: enter: kvpairs=hotword_active=1
V/audio_hw_primary(  282): in_set_parameters: exit: status(0)
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb3a6a000
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyManager(  282): AudioPolicyManager::startInput() input source = 1999
,I/MicrophoneInputStream( 2049): mic_started com.google.android.apps.gsa.speech.audio.u@366aee62
V/msm8974_platform(  282): platform_update_usecase_from_source: input source :6
D/audio_hw_primary(  282): start_input_stream: enter: stream(0xb546e420)usecase(7: audio-record)
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
V/audio_hw_primary(  282): enable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  282): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  282): enable_audio_route: apply mixer and update path: audio-record
V/audio_hw_primary(  282): enable_audio_route: exit
D/audio_hw_primary(  282): select_devices: done
V/audio_hw_primary(  282): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
V/audio_hw_primary(  282): start_input_stream: exit
,I/HotwordWorker( 2049): onReady
,I/Timeline(  969): Timeline: Activity_windows_visible id: ActivityRecord{2768e16d u0 com.lge.launcher2/.Launcher t219} time:97591
,I/ActivityManager(  969): Killing 4817:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  969): failed to open /acct/uid_10086/pid_4817/cgroup.procs: No such file or directory
,D/InputDispatcher(  969): Window went away: Window{33149960 u0 com.test.thalitest/com.test.thalitest.MainActivity EXITING}
,W/OpenGLRenderer( 1971): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
W/OpenGLRenderer( 1971): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,I/ThermalEngine(  301): Sensor:pa_therm0:30000 mC
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1971): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1971): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1971): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1971): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1971): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1971): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,I/ThermalEngine(  301): Sensor:pa_therm0:30000 mC
,I/rmt_storage(  276): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
,I/rmt_storage(  276): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  276): wakelock acquired: 1, error no: 42
I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  276): 
I/rmt_storage(  276): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/ThermalEngine(  301): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:30000 mC
,D/PowerManagerServiceEx(  969): acquireWakeLockInternal: lock=850467472, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=969
,D/WeatherService( 2652): 2 : TimeTick Intent has been received, Time(hour:min:sec) 14:45:0
D/WeatherService( 2652): 2 : TimeTick Intent And Screen On
D/WeatherService( 2652): 2 : SDK version : 21
W/ActivityManager(  969): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2652): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2652): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2652): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2652): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 2652): 2 : This is isUpdating : false
D/WeatherService( 2652): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2652): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2652): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2652): 2 : Fixed theme : optimus
D/WeatherReflect( 2652): 2 : Map key string is -2
D/lim     ( 2652): 2 : time = 14:45
I/WeatherReflect( 2652): Model Name : LG-D722
D/WeatherTheme( 2652): 2 : Different view - status_min_formatted : 44 != 45
D/WeatherTheme( 2652): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
,D/WeatherReflect( 2652): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2652): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2652): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2652): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2652): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
,I/[SystemUI]Clock( 1375): called onTimeUpdated()
I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
,D/Weather4x2_optimus( 2652): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2652): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2652): forecast size is 0
D/Theme   ( 2652): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2652): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2652): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2652): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2652): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2652): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2652): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2652): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2652): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2652): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2652): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2652): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2652): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2652): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2652): setTouchIntent, appWidgetId: 2
,V/AlarmManager(  969): ELAPSED_WAKEUP set : Alarm{26e05f89 type 2 when 114215 com.google.android.gms} when 114215
D/libc-netbsd( 2009): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2009): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 2009): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2009): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  969): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/Theme_WeatherAncestor_optimus( 2652): url is : null
,D/Theme   ( 2652): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2652): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2652): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2652): 2 : update view, appWidgetId: 2
D/WeatherService( 2652): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 14:45:0
,D/PowerManagerServiceEx(  969): releaseWakeLockInternal: lock=850467472 [*alarm*], flags=0x0
W/ContextImpl( 3366): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1971): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1971): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 115025932615; DSPS: 3867092; Offset : -2990118777
,I/MusicWidget( 2618): mDelayedStopHandler : unbind
,I/MusicBrowser( 2109): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2109): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2109): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2109): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2109): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2109): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2109): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2109): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,I/MediaFocusControl(  969):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@216c9e17com.lge.music.MediaPlaybackService$6@30348204
,D/MusicBrowser( 2109): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2109): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2109): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2109): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2109): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@29446872
I/MusicBrowser( 2109): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2109): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2109): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2109): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2109): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2109): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2109): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2109): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2109): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2109): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2109): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,I/MusicBrowser( 2109): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2109): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2109): reset
V/MediaPlayer[Native]( 2109): setListener
V/MediaPlayer[Native]( 2109): disconnect
V/MediaPlayer[Native]( 2109): destructor
,V/AudioFlinger(  282): releasing 19 from 2109 for -1
V/AudioFlinger(  282):  decremented refcount to 0
V/AudioFlinger(  282): purging stale effects
V/MediaPlayer[Native]( 2109): disconnect
D/MusicBrowser( 2109): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2109): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2109): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2109): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2109): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2109): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2109): [SmartShareManagerClient] unregisterListener: 420529133
W/SmartShareClient( 2109): [SmartShareManagerClient] unregisterListener invalid listener: 420529133
I/SmartShareClient( 2109): [SmartShareManagerClient] terminate service: 2109/MediaPlaybackService/1019819304
E/HomeCloudIF( 2109): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2109): [SmartShareManagerClient] unbindService context:android.app.Application@3e23d222
,V/CloudHub( 2109): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2109): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2109): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2109): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2109): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
,I/ActivityManager(  969): Killing 5002:com.google.android.gms:car/u0a6 (adj 15): empty #11
I/CloudHub( 2109): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29992
W/libprocessgroup(  969): failed to open /acct/uid_10006/pid_5002/cgroup.procs: No such file or directory
,I/ThermalEngine(  301): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:30000 mC
,I/CloudHub( 2109): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19969
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/PowerService( 1896): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
,I/QCNEJ   ( 1933): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1896): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1896): Battery Level Remaining: 100%
D/LEDHandler( 1896): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1933): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/WifiController(  969): battery changed pluggedType: 2
,I/ThermalEngine(  301): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time(  969): tsOffsetIs: Apps: 135029436150; DSPS: 4522566; Offset : -2990095912
I/ThermalEngine(  301): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:30000 mC
,I/CloudHub( 2109): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
I/CloudHub( 2109): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,I/PowerManagerService(  969): ALS enabled for SRE
,D/PowerManagerServiceEx(  969): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (28361 ms ago)
D/qdlights(  969): set_light_backlight: 253
,D/qdlights(  969): set_light_backlight: 249
D/qdlights(  969): set_light_backlight: 246
,D/qdlights(  969): set_light_backlight: 243
,D/qdlights(  969): set_light_backlight: 239
,D/qdlights(  969): set_light_backlight: 236
,D/qdlights(  969): set_light_backlight: 233
,D/qdlights(  969): set_light_backlight: 229
,D/qdlights(  969): set_light_backlight: 226
,D/qdlights(  969): set_light_backlight: 223
,D/qdlights(  969): set_light_backlight: 219
,D/qdlights(  969): set_light_backlight: 216
,D/qdlights(  969): set_light_backlight: 213
,D/qdlights(  969): set_light_backlight: 209
,D/qdlights(  969): set_light_backlight: 206
,D/qdlights(  969): set_light_backlight: 203
,D/qdlights(  969): set_light_backlight: 199
,D/qdlights(  969): set_light_backlight: 196
,D/qdlights(  969): set_light_backlight: 193
,D/qdlights(  969): set_light_backlight: 189
,D/qdlights(  969): set_light_backlight: 186
,I/ThermalEngine(  301): Sensor:pa_therm0:30000 mC
D/qdlights(  969): set_light_backlight: 183
,D/qdlights(  969): set_light_backlight: 179
,D/qdlights(  969): set_light_backlight: 176
,D/qdlights(  969): set_light_backlight: 173
,D/qdlights(  969): set_light_backlight: 169
,D/qdlights(  969): set_light_backlight: 166
,D/qdlights(  969): set_light_backlight: 163
,D/qdlights(  969): set_light_backlight: 159
,D/qdlights(  969): set_light_backlight: 156
,D/qdlights(  969): set_light_backlight: 153
,D/qdlights(  969): set_light_backlight: 149
,D/qdlights(  969): set_light_backlight: 146
,D/qdlights(  969): set_light_backlight: 143
,D/qdlights(  969): set_light_backlight: 139
,D/qdlights(  969): set_light_backlight: 136
,D/qdlights(  969): set_light_backlight: 133
,D/qdlights(  969): set_light_backlight: 129
,D/qdlights(  969): set_light_backlight: 126
,D/qdlights(  969): set_light_backlight: 123
,D/qdlights(  969): set_light_backlight: 119
,D/qdlights(  969): set_light_backlight: 116
,D/qdlights(  969): set_light_backlight: 113
,D/qdlights(  969): set_light_backlight: 109
,D/qdlights(  969): set_light_backlight: 106
,D/qdlights(  969): set_light_backlight: 103
,D/qdlights(  969): set_light_backlight: 99
,D/qdlights(  969): set_light_backlight: 96
,D/qdlights(  969): set_light_backlight: 93
,D/qdlights(  969): set_light_backlight: 89
,D/qdlights(  969): set_light_backlight: 86
,D/qdlights(  969): set_light_backlight: 83
,D/qdlights(  969): set_light_backlight: 79
,D/qdlights(  969): set_light_backlight: 76
,D/qdlights(  969): set_light_backlight: 73
,D/qdlights(  969): set_light_backlight: 69
,D/qdlights(  969): set_light_backlight: 66
,D/qdlights(  969): set_light_backlight: 63
,D/qdlights(  969): set_light_backlight: 59
,D/qdlights(  969): set_light_backlight: 56
,D/qdlights(  969): set_light_backlight: 53
,D/qdlights(  969): set_light_backlight: 49
,D/qdlights(  969): set_light_backlight: 46
,D/qdlights(  969): set_light_backlight: 43
,D/qdlights(  969): set_light_backlight: 39
,D/qdlights(  969): set_light_backlight: 36
,D/qdlights(  969): set_light_backlight: 33
,D/qdlights(  969): set_light_backlight: 29
,D/qdlights(  969): set_light_backlight: 26
,D/qdlights(  969): set_light_backlight: 23
,D/qdlights(  969): set_light_backlight: 19
,D/qdlights(  969): set_light_backlight: 16
,D/qdlights(  969): set_light_backlight: 13
,D/qdlights(  969): set_light_backlight: 10
,V/AlarmManager(  969): ELAPSED_WAKEUP set : Alarm{179a9b8e type 2 when 129277 com.google.android.gms} when 129277
,D/libc-netbsd(  969): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  969): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  969): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  969): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  278): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  969): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  301): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 155030748799; DSPS: 5177970; Offset : -2990124370
,I/PowerManagerService(  969): ALS enabled for SRE
D/PowerManagerServiceEx(  969): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (35332 ms ago)
I/PowerManagerService(  969): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  969): ALS enabled for SRE
D/PowerManagerServiceEx(  969): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (35343 ms ago)
W/ContextImpl(  969): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  969): Sleeping (uid 1000)...
D/LPWGController(  969): [updateScreenState] screen on = false
D/LPWGController(  969): disable proximity sensor
D/LPWGController(  969): enable proximity sensor
I/SensorManager(  969): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@60dafaf] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  969): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  969): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  969): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  969): activate: handle is 48, enable
V/sensors_hal_Ctx(  969): activate sensors is 1400000000000
D/sensors_hal_Thresh(  969): enable: handle=48
I/sensors_hal_SAM(  969): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  969): waitForResponse: timeout=1000
,V/sensors_hal_SAM(  969): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  969): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  969): enable: Received response: 0
D/PowerManagerServiceEx(  969): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (35377 ms ago)
I/Adreno-EGL(  969): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  969): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  969): Build Date: 03/02/15 Mon
I/Adreno-EGL(  969): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  969): Remote Branch: 
I/Adreno-EGL(  969): Local Patches: 
I/Adreno-EGL(  969): Reconstruct Branch: 
,I/Sensors (  430): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  969): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,I/sensors_hal_SAM(  969): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  969): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  969): processInd: handle 48, count=1
V/sensors_hal_Thresh(  969): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  969): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  969): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  969): poll: count: 256
I/sensors_hal_Ctx(  969): poll: released wakelock sensor_ind
D/sensors_hal_Util(  969): waitForResponse: timeout=0
D/LPWGController(  969): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  969): current mode = 1  value = 1 1
I/LPWGController(  969): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  969): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  969): set_light_backlight: 0
,I/SensorManager(  969): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
I/sensors_hal_Ctx(  969): activate: handle is 46, disable
V/sensors_hal_Ctx(  969): activate sensors is 1000000000000
D/sensors_hal_LP2(  969): enable: handle=46
D/sensors_hal_LP2(  969): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  969): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
,D/SurfaceFlinger(  246): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  246): hwc_blank: Blanking display: 0
I/DisplayManagerService(  969): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  969): Display changed displayId=0
,V/sensors_hal_SAM(  969): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  969): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1844): Display #0 changed.
,D/qdhwcomposer(  246): hwc_blank: Done blanking display: 0
D/SurfaceControl(  969): Excessive delay in setPowerMode(): 179ms
,I/qdhwcomposer(  246): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  969): Got set_interactive hint
I/[LGHome]EVENT( 1971): [Launcher.java:986:onPause()]onPause
I/[LGHome]EVENT( 1971): [Launcher.java:5214:onStop()]onStop
D/KeyguardViewMediator( 1375): onScreenTurnedOff(3)
I/HotwordDetector( 2049): Closing mic
I/MicrophoneInputStream( 2049): mic_close com.google.android.apps.gsa.speech.audio.u@366aee62
V/AudioRecord( 2049): stop()
D/AudioRecord( 2049): AudioRecord->stop()
,V/AudioFlinger(  282): RecordHandle::stop()
V/AudioFlinger(  282): RecordThread::stop
D/SmartCoverViewMediator( 1336): onScreenTurnedOff(3)
V/AudioFlinger(  282): Record stopped OK
V/AudioPolicyManager(  282): stopInput() input 23
V/AudioPolicyService(  282): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  282): inserting command: 8 at index 0, num commands 0
D/audio_hw_primary(  282): in_standby: enter: stream (0xb546e420) usecase(7: audio-record)
,V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  282): releaseAudioPatch handle 24
V/AudioFlinger::PatchPanel(  282): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  282): ThreadBase::setParameters() routing=0
D/KeyguardViewMediator( 1375): notifyScreenOffLocked
D/SmartCoverViewMediator( 1336): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1336): handleNotifyScreenOFF
D/KeyguardViewMediator( 1375): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1375): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1375): unregisterProximitySensor
,D/StatusBarWindowView( 1375): onScreenTurnedOff why = 3
,D/WifiServerServiceExt(  969): sendKtScanInterval  mRtspPlay : false
V/audio_hw_primary(  282): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  282): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  282): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  282): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  282): disable_audio_route: exit
E/audio_hw_primary(  282): disable_snd_device: enter 144
D/hardware_info(  282): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  282): disable_snd_device: snd_device(144: lg-vr-handset-mic)
,V/AudioFlinger(  282): setParameters(): io 0, keyvalue screen_state=on, calling pid 969
V/audio_hw_primary(  282): stop_input_stream: exit: status(0)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioFlinger(  282): RecordThread: loop stopping
V/AudioFlinger(  282): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  282): RecordThread: loop starting
V/AudioFlinger(  282): processConfigEvents_l() remaining events 1
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb3a6a000
V/AudioFlinger(  282): RecordThread: loop stopping
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyManager(  282): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  282): removeAudioPatch() handle 20 af handle 24
V/AudioPolicyService(  282): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  282): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() adding set parameter string hotword_active=0, io 23 ,delay 0
V/AudioPolicyService(  282): inserting command: 3 at index 0, num commands 0
D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=on
V/voice   (  282): voice_set_parameters: enter: screen_state=on
V/compress_voip(  282): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  282): voice_extn_compress_voip_set_parameters: exit
V/voice   (  282): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  282): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  282): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  282): platform_set_parameters: exit with code(0)
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing set parameters string hotword_active=0, io 23
V/AudioPolicyService(  282): AudioCommandThread() processing update audio patch list
V/AudioFlinger(  282): setParameters(): io 23, keyvalue hotword_active=0, calling pid 282
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/lge_audio_loopback(  282): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  282): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  282): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  282): adev_set_parameters: exit with code(0)
V/AudioFlinger(  282): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  282): sendConfigEvent_l() num events 1 event 2
,V/AudioFlinger(  282): RecordThread: loop starting
V/AudioFlinger(  282): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  282): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  282): in_set_parameters: exit: status(0)
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb3a6a000
V/AudioFlinger(  282): RecordThread: loop stopping
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioRecord( 2049): stop()
V/AudioRecord( 2049): stop()
V/AudioRecord( 2049): stop()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
V/AudioFlinger(  282): RecordHandle::stop()
V/AudioFlinger(  282): RecordThread::stop
,V/AudioPolicyManager(  282): releaseInput() 23
V/AudioFlinger(  282): releasing 22 from 2049 for -1
V/AudioPolicyManager(  282): closeInput(23)
V/AudioFlinger(  282):  decremented refcount to 0
V/AudioFlinger(  282): purging stale effects
V/AudioFlinger(  282): closeInput() 23
V/AudioSystem(  282): ioConfigChanged() event 4, ioHandle 23
V/AudioFlinger(  282): ThreadBase::exit
V/AudioSystem( 3072): ioConfigChanged() event 4, ioHandle 23
V/AudioFlinger(  282): RecordThread: loop starting
V/AudioFlinger(  282): RecordThread 0xb3a6a000 exiting
D/audio_hw_primary(  282): adev_close_input_stream: enter:stream_handle(0xb546e420)
D/audio_hw_primary(  282): in_standby: enter: stream (0xb546e420) usecase(7: audio-record)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioPolicyService(  282): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  282): inserting command: 9 at index 0, num commands 0
V/AudioSystem(  969): ioConfigChanged() event 4, ioHandle 23
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioSystem( 1375): ioConfigChanged() event 4, ioHandle 23
V/AudioSystem( 1844): ioConfigChanged() event 4, ioHandle 23
,V/AudioSystem( 2049): ioConfigChanged() event 4, ioHandle 23
V/AudioPolicyManager(  282): releaseInput() exit
V/AudioFlinger(  282): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  282): removeClient_l() pid 2049, calling pid 282
V/AudioSystem( 2109): ioConfigChanged() event 4, ioHandle 23
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.SCREEN_ON
I/HotwordRecognitionRnr( 2049): Stopping hotword detection.
I/HotwordRecognitionRnr( 2049): Hotword detection finished
D/GpsLocationProvider(  969): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/SplitWindow(  969): check instance of lgWin Window{428e29a u0 SearchPanel}
,I/QCNEJ   ( 1933): |CORE| sendScreenState: state:true
D/InputDispatcher(  969): Window went away: Window{167357c4 u0 SearchPanel}
,I/[SystemUI]Clock( 1375): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1375): time changed, timezoneChanged : false
,I/LEDService( 1896): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1896): stopPatternFlashing()
D/qdlights( 1896): set_light_notifications: 0,0,0,0,3
I/LEDService( 1896): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1896): set_light_notifications: 0,0,0,0,3
I/LEDService( 1896): updateLightsLocked : turn off led
D/qdlights( 1896): set_light_notifications: 0,0,0,0,3
I/Cliptray Service( 1896): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/LEDHandler( 1896): RESTART MSG
D/Cliptray Service( 1896): lockStatus = 0
D/LNfcService( 1879): action : android.intent.action.SCREEN_ON
D/NfcServiceNXP( 1879): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1879): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1879): isRequireNfcCRouting() return true
D/LNfcService( 1879): isHCERoutingtoHost() return : true
D/NfcService( 1879): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1879): mEnableLPD: true
D/NfcService( 1879): mEnableReader: false
D/NfcService( 1879): mEnableHostRouting: true
D/NfcService( 1879): newParams.techmask= mTechMask: default
D/NfcService( 1879): mEnableLPD: true
D/NfcService( 1879): mEnableReader: false
D/NfcService( 1879): mEnableHostRouting: true
D/NfcService( 1879): screenState= 3
D/NfcService( 1879): Discovery configuration equal, not updating.
D/Ulp_jni (  969): JNI:system_update. Event-0
,V/PhoneApp( 1844): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2652): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:45:42
,D/WeatherService( 2652): 2 : ACTION screen on
D/WeatherService( 2652): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2652): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2652): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:45:42
D/AppCleanupService( 3800): android.intent.action.SCREEN_ON
,V/AudioFlinger(  282): setParameters(): io 0, keyvalue screen_state=off, calling pid 969
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
D/WifiController(  969): CMD_SCREEN_OFF 
,D/WifiController(  969): shouldWifiStayAwake TRUE
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.SCREEN_OFF
D/GpsLocationProvider(  969): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1933): |CORE| sendScreenState: state:false
I/LEDService( 1896): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1896): stopPatternFlashing()
D/qdlights( 1896): set_light_notifications: 0,0,0,0,3
,I/LEDService( 1896): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1896): set_light_notifications: 0,0,0,0,3
I/LEDService( 1896): updateLightsLocked : turn on led
E/LEDService( 1896): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1896): Can't handle this request of patternId:0
D/LEDHandler( 1896): RESTART MSG
D/VolumeVibrator( 1896): clear
I/Cliptray Service( 1896): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1879): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1879): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1971): [Launcher.java:1711:onReceive()]Screen Off
W/ActivityManager(  969): getTasks: caller 10024 is using old GET_TASKS but privileged; allowing
V/PhoneApp( 1844): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2652): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:45:42
D/WeatherService( 2652): 2 : ACTION screen off
D/WeatherService( 2652): 2 : TimeTick Receiver Unregister
D/WeatherService( 2652): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:45:42
D/AppCleanupService( 3800): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 3800): AppUsageStatsSaveTask
E/NxpNfcJni( 1879): getReconnectState = 0x0
,D/LCardEmulationManager( 1879): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1879): getDefaultRoute
D/LNfcService( 1879): isRequireNfcCRouting() return true
D/LNfcService( 1879): isHCERoutingtoHost() return : true
D/NfcService( 1879): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1879): mEnableLPD: true
D/NfcService( 1879): mEnableReader: false
D/NfcService( 1879): mEnableHostRouting: true
D/NfcService( 1879): newParams.techmask= mTechMask: 0
D/NfcService( 1879): mEnableLPD: true
D/NfcService( 1879): mEnableReader: false
D/NfcService( 1879): mEnableHostRouting: true
D/NfcService( 1879): screenState= 1
E/NxpNfcJni( 1879): getReconnectState = 0x0
,I/Sensors (  430): sns_pwr.c(301):releasing wakelock
,I/ThermalEngine(  301): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  969): ELAPSED_WAKEUP set : Alarm{178f97cb type 2 when 161185 com.android.systemui} when 161185
,D/KeyguardViewMediator( 1375): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/PhoneUtils( 1844): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1844): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1844): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1844): getCallState : 0
,D/PhoneUtils( 1844): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1844): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1844): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1375): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1375): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  301): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 175033293168; DSPS: 5833413; Offset : -2990112907
,I/ThermalEngine(  301): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/ClearcutLoggerApiImpl( 1806): disconnect managed GoogleApiClient
,D/PowerManagerServiceEx(  969): acquireWakeLockInternal: lock=850467472, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=969
,V/AlarmManager(  969): ELAPSED_WAKEUP set : Alarm{3a65aba8 type 2 when 186947 com.google.android.gms} when 186947
D/PowerManagerServiceEx(  969): releaseWakeLockInternal: lock=850467472 [*alarm*], flags=0x0
,I/NotificationManager( 2049): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/PowerService( 1896): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/QCNEJ   ( 1933): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1933): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
D/WifiController(  969): battery changed pluggedType: 2
D/LEDHandler( 1896): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1896): Battery Level Remaining: 100%
D/LEDHandler( 1896): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 195035855086; DSPS: 6488857; Offset : -2990114493
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,V/AlarmManager(  969): ELAPSED_WAKEUP set : Alarm{3cd3bdfd type 2 when 174081 com.google.android.gms} when 174081
,V/AlarmManager(  969): ELAPSED_WAKEUP set : Alarm{18b92af2 type 2 when 188709 com.google.android.gms} when 188709
D/libc-netbsd(  969): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  969): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  969): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  969): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  278): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  969): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/libc-netbsd( 2009): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2009): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 2009): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2009): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  969): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 215038397055; DSPS: 7144300; Offset : -2990105483
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,V/AlarmManager(  969): ELAPSED_WAKEUP set : Alarm{1b193543 type 2 when 188671 android} when 188671
,V/AlarmManager(  969): RTC_WAKEUP set : Alarm{2cc847c0 type 0 when 1449668811580 com.google.android.gms} when 1449668811580
I/EventLogService( 3869): Aggregate from 1449667011483 (log), 1449667011483 (data)
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 235040963561; DSPS: 7799744; Offset : -2990102427
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/PowerService( 1896): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
,I/QCNEJ   ( 1933): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1933): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1896): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1896): Battery Level Remaining: 100%
D/LEDHandler( 1896): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  969): battery changed pluggedType: 2
I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 255043505116; DSPS: 8455187; Offset : -2990094039
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1896): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1896): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
,I/QCNEJ   ( 1933): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1933): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1896): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1896): Battery Level Remaining: 100%
D/LEDHandler( 1896): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  969): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
,I/QCNEJ   ( 1933): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1933): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1896): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1896): Battery Level Remaining: 100%
D/LEDHandler( 1896): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  969): battery changed pluggedType: 2
I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/PowerService( 1896): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 275046041826; DSPS: 9110630; Offset : -2990090158
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 295047539992; DSPS: 9766040; Offset : -2990117792
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/PowerService( 1896): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
,I/QCNEJ   ( 1933): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1933): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1896): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1896): Battery Level Remaining: 100%
D/LEDHandler( 1896): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  969): battery changed pluggedType: 2
I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 315050410979; DSPS: 10421494; Offset : -2990115511
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 335052951334; DSPS: 11076937; Offset : -2990108270
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/LocationManagerService(  969): remove 33c113b5
,D/LocationManagerService(  969): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  969): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  969): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  969): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  969): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  969): acquireWakeLockInternal: lock=850467472, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=969
,V/AlarmManager(  969): ELAPSED_WAKEUP set : Alarm{2d51afb5 type 2 when 329694 com.google.android.gms} when 329694
D/PowerManagerServiceEx(  969): releaseWakeLockInternal: lock=850467472 [*alarm*], flags=0x0
,D/libc-netbsd( 2009): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2009): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 2009): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2009): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=0, netid=0
,D/DSQN    (  969): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 355055488984; DSPS: 11732380; Offset : -2990103658
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/PowerService( 1896): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
,I/QCNEJ   ( 1933): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1933): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1896): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1896): Battery Level Remaining: 100%
D/LEDHandler( 1896): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  969): battery changed pluggedType: 2
I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,V/GLSActivity( 2009): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2009): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2009): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  969): android: cancelAsUser(2) by android
,D/libc-netbsd( 4892): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4892): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4892): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4892): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  278): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  278): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=0, netid=0
,D/DSQN    (  969): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 375058070016; DSPS: 12387825; Offset : -2990116489
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 395060610582; DSPS: 13043268; Offset : -2990108909
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 415063016928; DSPS: 13698707; Offset : -2990113451
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1896): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
,I/QCNEJ   ( 1933): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1933): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1896): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1896): Battery Level Remaining: 100%
D/LEDHandler( 1896): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  969): battery changed pluggedType: 2
I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 435064908384; DSPS: 14354129; Offset : -2990113850
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 455067457642; DSPS: 15009572; Offset : -2990097786
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 475069994874; DSPS: 15665015; Offset : -2990093148
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,D/PowerService( 1896): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
,I/QCNEJ   ( 1933): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1933): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1896): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1896): Battery Level Remaining: 100%
D/LEDHandler( 1896): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
D/WifiController(  969): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 495072532419; DSPS: 16320459; Offset : -2990119445
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 515075069337; DSPS: 16975902; Offset : -2990115486
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 535077087769; DSPS: 17631328; Offset : -2990111291
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/PowerService( 1896): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
,I/QCNEJ   ( 1933): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1896): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1896): Battery Level Remaining: 100%
D/LEDHandler( 1896): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1933): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  969): battery changed pluggedType: 2
I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 555079627813; DSPS: 18286771; Offset : -2990104102
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 575082039525; DSPS: 18942210; Offset : -2990103253
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1896): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
,I/QCNEJ   ( 1933): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1933): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1896): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1896): Battery Level Remaining: 100%
D/LEDHandler( 1896): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  969): battery changed pluggedType: 2
I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 595084578216; DSPS: 19597653; Offset : -2990097574
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1896): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
,I/QCNEJ   ( 1933): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1933): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1896): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1896): Battery Level Remaining: 100%
D/LEDHandler( 1896): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  969): battery changed pluggedType: 2
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 615087117165; DSPS: 20253096; Offset : -2990091610
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 635089656220; DSPS: 20908540; Offset : -2990116031
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/PowerManagerServiceEx(  969): acquireWakeLockInternal: lock=850467472, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=969
,V/AlarmManager(  969): ELAPSED_WAKEUP set : Alarm{3b5d20f0 type 2 when 590896 com.google.android.gms} when 590896
D/PowerManagerServiceEx(  969): releaseWakeLockInternal: lock=850467472 [*alarm*], flags=0x0
,D/libc-netbsd( 2009): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2009): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 2009): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2009): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  969): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 655092198296; DSPS: 21563983; Offset : -2990106836
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/PowerService( 1896): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
,D/LEDHandler( 1896): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1896): Battery Level Remaining: 100%
D/LEDHandler( 1896): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1933): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1933): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/WifiController(  969): battery changed pluggedType: 2
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,V/GLSActivity( 2009): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2009): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2009): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  969): android: cancelAsUser(2) by android
,D/libc-netbsd( 4892): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4892): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4892): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4892): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  278): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  969): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 675093833288; DSPS: 22219397; Offset : -2990119454
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 695096373436; DSPS: 22874840; Offset : -2990112630
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 715098901293; DSPS: 23530283; Offset : -2990117706
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1896): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 271
,I/QCNEJ   ( 1933): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1933): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1896): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1896): Battery Level Remaining: 100%
D/LEDHandler( 1896): Battery Temp: 271, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  969): battery changed pluggedType: 2
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 735101778473; DSPS: 24185737; Offset : -2990109257
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 755104321018; DSPS: 24841180; Offset : -2990099645
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 775106859812; DSPS: 25496623; Offset : -2990093732
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1896): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
,I/QCNEJ   ( 1933): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1933): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1896): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1896): Battery Level Remaining: 100%
D/LEDHandler( 1896): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  969): battery changed pluggedType: 2
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ClearcutLoggerApiImpl( 2009): disconnect managed GoogleApiClient
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time(  969): tsOffsetIs: Apps: 795109400793; DSPS: 26152067; Offset : -2990116331
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 815111942504; DSPS: 26807510; Offset : -2990107605
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 835114494059; DSPS: 27462954; Offset : -2990119501
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/PowerService( 1896): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 855117027911; DSPS: 28118397; Offset : -2990118608
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 875119567899; DSPS: 28773840; Offset : -2990111709
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 895122113256; DSPS: 29429283; Offset : -2990099181
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1896): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 915124655434; DSPS: 30084726; Offset : -2990089936
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 935127199281; DSPS: 30740170; Offset : -2990109591
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 955129733857; DSPS: 31395613; Offset : -2990107974
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/PowerService( 1896): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 269
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 269
,I/QCNEJ   ( 1933): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1933): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1896): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1896): Battery Level Remaining: 100%
D/LEDHandler( 1896): Battery Temp: 269, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  969): battery changed pluggedType: 2
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,V/GLSActivity( 2009): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2009): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2009): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  969): android: cancelAsUser(2) by android
,D/libc-netbsd( 4892): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4892): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4892): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4892): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  278): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=0, netid=0
,D/DSQN    (  969): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 975140183383; DSPS: 32051315; Offset : -2990095564
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 995142722541; DSPS: 32706759; Offset : -2990119675
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1015144748887; DSPS: 33362185; Offset : -2990107410
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1896): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1035147027897; DSPS: 34017620; Offset : -2990117219
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1055149574809; DSPS: 34673063; Offset : -2990103422
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1075151966054; DSPS: 35328501; Offset : -2990092548
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1896): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 268
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 268
,I/QCNEJ   ( 1933): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1933): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1896): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1896): Battery Level Remaining: 100%
D/LEDHandler( 1896): Battery Temp: 268, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  969): battery changed pluggedType: 2
I/art     ( 1375): Background partial concurrent mark sweep GC freed 18532(818KB) AllocSpace objects, 43(8MB) LOS objects, 40% free, 22MB/37MB, paused 2.297ms total 145.874ms
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1095153777816; DSPS: 35983921; Offset : -2990111789
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1115156310149; DSPS: 36639364; Offset : -2990112415
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/PowerManagerServiceEx(  969): acquireWakeLockInternal: lock=850467472, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=969
,V/AlarmManager(  969): ELAPSED_WAKEUP set : Alarm{37e8fd11 type 2 when 1130267 com.google.android.gms} when 1130267
D/PowerManagerServiceEx(  969): releaseWakeLockInternal: lock=850467472 [*alarm*], flags=0x0
,D/libc-netbsd( 2009): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2009): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 2009): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2009): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=0, netid=0
,D/DSQN    (  969): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1135158851082; DSPS: 37294807; Offset : -2990104571
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/PowerService( 1896): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1155160678470; DSPS: 37950227; Offset : -2990108185
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1175162599973; DSPS: 38605650; Offset : -2990109290
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1195165003090; DSPS: 39261089; Offset : -2990117036
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/PowerService( 1896): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 267
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 267
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
I/QCNEJ   ( 1933): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1933): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1896): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1896): Battery Level Remaining: 100%
D/LEDHandler( 1896): Battery Temp: 267, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  969): battery changed pluggedType: 2
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1215167403292; DSPS: 39916527; Offset : -2990097049
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/UsageStatsService(  969): User[0] Flushing usage stats to disk
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1235169937920; DSPS: 40571970; Offset : -2990095172
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1255172476399; DSPS: 41227414; Offset : -2990120507
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1896): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 267
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 267
,I/QCNEJ   ( 1933): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1933): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1896): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1896): Battery Level Remaining: 100%
D/LEDHandler( 1896): Battery Temp: 267, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  969): battery changed pluggedType: 2
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1275178542120; DSPS: 41882972; Offset : -2990097710
,V/GLSActivity( 2009): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2009): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2009): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  969): android: cancelAsUser(2) by android
,D/libc-netbsd( 4892): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4892): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4892): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4892): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  278): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  969): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1295181082530; DSPS: 42538415; Offset : -2990089894
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1315183162211; DSPS: 43193844; Offset : -2990115900
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1896): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 266
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 266
,I/QCNEJ   ( 1933): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1933): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1896): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1896): Battery Level Remaining: 100%
D/LEDHandler( 1896): Battery Temp: 266, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  969): battery changed pluggedType: 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1335185812254; DSPS: 43849291; Offset : -2990120912
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1355188078757; DSPS: 44504725; Offset : -2990112502
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1375190510469; DSPS: 45160164; Offset : -2990091807
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/PowerService( 1896): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1395192144994; DSPS: 45815578; Offset : -2990105077
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1415194688941; DSPS: 46471021; Offset : -2990094219
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1435197220758; DSPS: 47126464; Offset : -2990095464
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/PowerService( 1896): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 266
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 266
,I/QCNEJ   ( 1933): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1933): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1896): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1896): Battery Level Remaining: 100%
D/LEDHandler( 1896): Battery Temp: 266, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  969): battery changed pluggedType: 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1455199755543; DSPS: 47781907; Offset : -2990093455
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1475202289077; DSPS: 48437350; Offset : -2990093089
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1495204832974; DSPS: 49092794; Offset : -2990112669
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/PowerService( 1896): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 266
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 266
,I/QCNEJ   ( 1933): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1933): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1896): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1896): Battery Level Remaining: 100%
D/LEDHandler( 1896): Battery Temp: 266, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  969): battery changed pluggedType: 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1515207371561; DSPS: 49748237; Offset : -2990106963
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1535209914210; DSPS: 50403680; Offset : -2990097117
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1555212449772; DSPS: 51059123; Offset : -2990094670
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/PowerService( 1896): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 265
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 265
,I/QCNEJ   ( 1933): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1933): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1896): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1896): Battery Level Remaining: 100%
D/LEDHandler( 1896): Battery Temp: 265, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  969): battery changed pluggedType: 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1575214990914; DSPS: 51714567; Offset : -2990117005
,V/GLSActivity( 2009): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2009): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2009): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  969): android: cancelAsUser(2) by android
,D/libc-netbsd( 4892): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4892): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4892): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4892): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  278): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  278): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  969): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1595217525957; DSPS: 52370010; Offset : -2990114973
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1615220398086; DSPS: 53025464; Offset : -2990111183
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/PowerService( 1896): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1635222936777; DSPS: 53680907; Offset : -2990105686
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1655225478435; DSPS: 54336350; Offset : -2990097038
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1675228018896; DSPS: 54991794; Offset : -2990120027
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1896): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1695230548109; DSPS: 55647236; Offset : -2990093283
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1715232186017; DSPS: 56302650; Offset : -2990103297
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1735234730904; DSPS: 56958093; Offset : -2990091396
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1896): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1755236372878; DSPS: 57613507; Offset : -2990097136
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1775238913966; DSPS: 58268951; Offset : -2990119734
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1795240558016; DSPS: 58924364; Offset : -2990093167
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1896): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1815243099624; DSPS: 59579808; Offset : -2990115036
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1835245640136; DSPS: 60235251; Offset : -2990107483
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1855248037682; DSPS: 60890689; Offset : -2990090334
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/PowerService( 1896): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1875250769394; DSPS: 61546139; Offset : -2990104943
,V/GLSActivity( 2009): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  969): Prepared write state in 11ms
,V/GLSActivity( 2009): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2009): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  969): android: cancelAsUser(2) by android
,D/libc-netbsd( 4892): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4892): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4892): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4892): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  278): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  969): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ProcessStatsService(  969): Pruning old procstats: /data/system/procstats/state-2015-12-08-19-10-54.bin
,I/ActivityManager(  969): Killing 4940:com.lge.qremote/u0a106 (adj 15): empty for 1800s
,I/ActivityManager(  969): Killing 4835:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty for 1800s
,I/ActivityManager(  969): Killing 5121:com.google.android.gm/u0a53 (adj 15): empty for 1802s
,W/libprocessgroup(  969): failed to open /acct/uid_10106/pid_4940/cgroup.procs: No such file or directory
E/lowmemorykiller(  243): Error opening /proc/4835/oom_score_adj; errno=2
,W/ActivityManager(  969): Exception when unbinding service com.uei.lg.quicksetsdk.lite/com.uei.control.Service
W/ActivityManager(  969): android.os.DeadObjectException
W/ActivityManager(  969): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  969): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  969): 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
W/ActivityManager(  969): 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1788)
W/ActivityManager(  969): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2174)
W/ActivityManager(  969): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15220)
W/ActivityManager(  969): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:5064)
W/ActivityManager(  969): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:5234)
W/ActivityManager(  969): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1234)
W/ActivityManager(  969): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:553)
W/ActivityManager(  969): Exception when destroying service com.uei.lg.quicksetsdk.lite/com.uei.control.Service
W/ActivityManager(  969): android.os.DeadObjectException
W/ActivityManager(  969): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  969): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  969): 	at android.app.ApplicationThreadProxy.scheduleStopService(ApplicationThreadNative.java:946)
W/ActivityManager(  969): 	at com.android.server.am.ActiveServices.bringDownServiceLocked(ActiveServices.java:1693)
W/ActivityManager(  969): 	at com.android.server.am.ActiveServices.bringDownServiceIfNeededLocked(ActiveServices.java:1605)
W/ActivityManager(  969): 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1805)
W/ActivityManager(  969): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2174)
W/ActivityManager(  969): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15220)
W/ActivityManager(  969): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:5064)
W/ActivityManager(  969): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:5234)
W/ActivityManager(  969): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1234)
W/ActivityManager(  969): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:553)
,W/libprocessgroup(  969): failed to open /acct/uid_10053/pid_5121/cgroup.procs: No such file or directory
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  969): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  969): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  969): tsOffsetIs: Apps: 1895252393553; DSPS: 62201552; Offset : -2990098425
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 5822): 
D/AndroidRuntime( 5822): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5822): CheckJNI is OFF
D/AndroidRuntime( 5822): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  969): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  969): Killing 5308:com.test.thalitest/u0a316 (adj 13): stop com.test.thalitest
W/PackageSettings(  969): Skipping PackageSetting{13739eee com.example.hello/10030} due to missing metadata
I/ActivityManager(  969): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/art     ( 1971): Explicit concurrent mark sweep GC freed 8580(491KB) AllocSpace objects, 4(645KB) LOS objects, 40% free, 15MB/25MB, paused 1.273ms total 42.415ms
I/art     ( 2049): Explicit concurrent mark sweep GC freed 2417(158KB) AllocSpace objects, 2(689KB) LOS objects, 39% free, 12MB/21MB, paused 1.225ms total 63.257ms
W/ActivityManager(  969): Spurious death for ProcessRecord{386657f1 5308:com.test.thalitest/u0a316}, curProc for 5308: null
D/KeyguardModel( 1375): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 1971): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1971): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1971): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
I/InputReader(  969): Reconfiguring input devices.  changes=0x00000010
I/QCNEJ   ( 1933): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/GeofencerStateMachine( 1806): Ignoring removeGeofence because network location is disabled.
W/System.err( 3366): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3366): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3366): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3366): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3366): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3366): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3366): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3366): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3366): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3366): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3366): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3366): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/ActivityManager(  969): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=5852 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/ActivityManager(  969): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=5858 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/art     (  969): Explicit concurrent mark sweep GC freed 59416(3MB) AllocSpace objects, 18(391KB) LOS objects, 33% free, 23MB/35MB, paused 2.162ms total 198.437ms
I/art     (  969): WaitForGcToComplete blocked for 182.042ms for cause Explicit
I/[SystemUI]QSlideListController( 1375): onReceive = android.intent.action.PACKAGE_REMOVED
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1375): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1375): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/LockScreenSettings( 5858): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
W/ResourcesManager( 5852): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5852): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/KeyguardModel( 1375): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1375): createShortcutInfo...
W/ResourcesManager( 5852): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/KeyguardModel( 1375): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1375): createShortcutInfo...
W/ResourcesManager( 1375): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1375): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1375): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1375): createShortcutInfo...
D/administrator(  969): Handling package changes for user 0
W/ResourcesManager( 1375): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1375): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1375): createShortcutInfo...
W/ResourcesManager( 1375): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1375): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1375): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1375): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1375): createShortcutInfo...
D/KeyguardModel( 1375): handleShortcutListChanged...
D/KeyguardModel( 1375): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1375): createShortcutInfo...
D/KeyguardModel( 1375): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1375): createShortcutInfo...
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1375): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1375): createShortcutInfo...
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1375): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1375): createShortcutInfo...
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1375): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1375): createShortcutInfo...
I/ActivityManager(  969): Killing 5238:com.android.calendar/u0a13 (adj 15): empty for 1818s
I/NotificationService(  969): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  969): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  969): Receieved: android.intent.action.PACKAGE_REMOVED
W/libprocessgroup(  969): failed to open /acct/uid_10013/pid_5238/cgroup.procs: No such file or directory
D/KeyguardModel( 1375): handleShortcutListChanged...
D/TaskPersister(  969): removeObsoleteFile: deleting file=220_task.xml
D/TaskPersister(  969): removeObsoleteFile: deleting file=220_task_thumbnail.png
I/art     (  969): Explicit concurrent mark sweep GC freed 8406(471KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 8.204ms total 296.835ms
I/LGEmail ( 5852): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 5852): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
D/AndroidRuntime( 5822): Shutting down VM
W/ResourcesManager(  969): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType(  969): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 1971): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/LCardEmulationManager( 1879): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1879): getDefaultRoute
I/PackageChangeReceiver( 5852): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/ActivityManager(  969): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5893 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  969): Killing 5208:com.android.providers.calendar/u0a14 (adj 15): empty for 1815s
W/libprocessgroup(  969): failed to open /acct/uid_10014/pid_5208/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 5893): onCreate
W/AppUp4:DB( 5893):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 5893):  setFingerPrint start
I/AppUp4:DB( 5893):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 5893):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5893):  SDK version = 0
I/AppUp4:DB( 5893):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 5893): AppBoxApplication onCreate()
D/AppUp4:PreloadHelper( 5893): added Exclude : com.test.thalitest
I/ActivityManager(  969): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=5912 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  969): Killing 4892:com.android.vending/u0a36 (adj 15): empty for 1813s
W/libprocessgroup(  969): failed to open /acct/uid_10036/pid_4892/cgroup.procs: No such file or directory

```
