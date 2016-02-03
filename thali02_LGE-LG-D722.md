#### Test 5813565532fb33b_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
,I/Icing   ( 4937): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
I/Icing   ( 4937): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
D/AndroidRuntime( 5361): 
D/AndroidRuntime( 5361): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5361): CheckJNI is OFF
D/AndroidRuntime( 5361): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  842): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/art     (  842): Explicit concurrent mark sweep GC freed 14412(701KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 3.135ms total 142.122ms
D/ActivityManager(  842): setTaskToReturnTo : TaskRecord{e42df1c #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  842): setTaskToReturnTo : TaskRecord{e42df1c #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  842): AppWindowTokenEx init.. 
D/ContextHelper(  842): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  842): Focus left window: Window{3eccdb46 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5361): Shutting down VM
I/[LGHome]EVENT( 1880): [Launcher.java:986:onPause()]onPause
D/SplitWindow(  842): check instance of lgWin Window{2b0ca2c6 u0 Starting com.test.thalitest}
I/ActivityManager(  842): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5377 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1880): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/HotwordDetector( 1938): Closing mic
I/MicrophoneInputStream( 1938): mic_close com.google.android.apps.gsa.speech.audio.u@137c051e
V/AudioRecord( 1938): stop()
D/AudioRecord( 1938): AudioRecord->stop()
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
V/AudioFlinger(  278): processConfigEvents_l() DONE thread 0xb3846000
D/audio_hw_primary(  278): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
I/[LGHome]EVENT( 1880): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  842): Starting window displayed
I/SystemUI[Framework](  842): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1376): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  842): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  842): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  842): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  842): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@27bcf2cf,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  842): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1376): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1376):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1376): , Keyguard show=false, IME shown=false, Panel expanded=false
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
D/BarTransitions( 1376): draw background and invalidate : color = 15000000
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
D/BarTransitions( 1376): draw background and invalidate : color = 16161616
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
V/AudioFlinger(  278): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  278): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  278): in_set_parameters: exit: status(0)
V/AudioFlinger(  278): processConfigEvents_l() DONE thread 0xb3846000
V/AudioFlinger(  278): RecordThread: loop stopping
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
,V/AudioRecord( 1938): stop()
V/AudioRecord( 1938): stop()
V/AudioRecord( 1938): stop()
V/AudioFlinger(  278): RecordHandle::stop()
V/AudioFlinger(  278): RecordThread::stop
V/AudioPolicyManager(  278): releaseInput() 17
V/AudioPolicyManager(  278): closeInput(17)
V/AudioFlinger(  278): releasing 16 from 1938 for -1
V/AudioFlinger(  278):  decremented refcount to 0
V/AudioFlinger(  278): purging stale effects
V/AudioFlinger(  278): closeInput() 17
V/AudioSystem(  278): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1376): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2753): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  278): ThreadBase::exit
V/AudioSystem( 1753): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1938): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3104): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  278): RecordThread: loop starting
V/AudioFlinger(  278): RecordThread 0xb3846000 exiting
V/AudioSystem(  842): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  278): adev_close_input_stream: enter:stream_handle(0xb546e1a0)
D/audio_hw_primary(  278): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  278): in_standby: exit:  status(0)
V/AudioPolicyService(  278): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  278): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  278): AudioCommandThread() waking up
V/AudioPolicyService(  278): AudioCommandThread() processing update audio port list
V/AudioPolicyManager(  278): releaseInput() exit
V/AudioFlinger(  278): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  278): removeClient_l() pid 1938, calling pid 278
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
I/HotwordRecognitionRnr( 1938): Hotword detection finished
I/HotwordRecognitionRnr( 1938): Stopping hotword detection.
D/ContextHelper( 5377): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 5377): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5377): Time to load native libraries: 2 ms (timestamps 322-324)
I/LibraryLoader( 5377): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5377): Binding Chromium to main looper Looper (main, tid 1) {373017a1}
I/LibraryLoader( 5377): Expected native library version number "",actual native library version number ""
I/chromium( 5377): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5377): Initializing chromium process, singleProcess=true
W/art     ( 5377): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5377): ApplicationContext is null in ApplicationStatus
W/chromium( 5377): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 5377): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5377): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5377): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5377): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5377): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5377): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5377): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5377): Remote Branch: 
I/Adreno-EGL( 5377): Local Patches: 
I/Adreno-EGL( 5377): Reconstruct Branch: 
V/AudioPolicyService(  278): registerClient() client 0xb551c8c0, uid 10316
D/BluetoothManagerService(  842): Message: 20
D/BluetoothManagerService(  842): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a3a8c38:true
,D/BluetoothAdapter( 5377): 570851410: getState() :  mService = null. Returning STATE_OFF
W/art     ( 5377): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5377): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5377): CordovaWebView is running on device made by: LGE
,W/art     ( 5377): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5377): Attempt to remove local handle scope entry from IRT, ignoring
I/Activity( 5377): Activity.onPostResume() called 
,D/OpenGLRenderer( 5377): Render dirty regions requested: true
I/OpenGLRenderer( 5377): Initialized EGL, version 1.4
D/OpenGLRenderer( 5377): Enabling debug mode 0
,D/Atlas   ( 5377): Validating map...
,D/SplitWindow(  842): check instance of lgWin Window{1a857368 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5377): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  842): Focus entered window: Window{1a857368 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  842): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  842): Displayed com.test.thalitest/.MainActivity: +1s243ms
I/Timeline(  842): Timeline: Activity_windows_visible id: ActivityRecord{1e1bb725 u0 com.test.thalitest/.MainActivity t222} time:81082
,I/Timeline( 5377): Timeline: Activity_idle id: android.os.BinderProxy@b38674d time:81107
,I/ActivityManager(  842): Killing 5200:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  842): failed to open /acct/uid_10011/pid_5200/cgroup.procs: No such file or directory
,W/BindingManager( 5377): Cannot call determinedVisibility() - never saw a connection for the pid: 5377
,I/ActivityManager(  842): Killing 5220:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/libprocessgroup(  842): failed to open /acct/uid_10023/pid_5220/cgroup.procs: No such file or directory
,D/JsMessageQueue( 5377): Set native->JS mode to OnlineEventsBridgeMode
,D/UEI.SmartControl( 5166): Internal timer expired: 1
,D/jxcore_app_log( 5377): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426134016
,I/chromium( 5377): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/art     ( 5377): CheckpointMarkThreadRoots callback created = 0xb07e22d0
,I/art     ( 5377): CheckpointMarkThreadRoots callback created = 0xb07e22a0
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
D/charger_monitor(  468): init target 500000
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/WifiController(  842): battery changed pluggedType: 2
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
,D/charger_monitor(  468): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  842): battery changed pluggedType: 2
D/InitAlarmsService( 3584): Clearing and rescheduling alarms.
,I/ActivityManager(  842): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5474 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GAV2    ( 5298): Thread[GAThread,5,main]: No campaign data found.
,I/GAv4-SVC( 4937): Google Analytics 8.4.89 is starting up.
,W/ResourcesManager( 5474): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 5474): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@2c87a21c
,D/CalendarProvider2( 5474): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 5474): Created com.android.providers.calendar.CalendarAlarmManager@373017a1(com.android.providers.calendar.CalendarProvider2@2c87a21c)
D/CalendarProvider2( 5474): Scheduling check of next Alarm
D/CalendarProvider2( 5474): SCHEDULE_ALARM_REMOVE
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
I/ActivityManager(  842): Killing 3584:com.android.calendar/u0a13 (adj 15): empty #11
W/libprocessgroup(  842): failed to open /acct/uid_10013/pid_3584/cgroup.procs: No such file or directory
,W/jxcore-log( 5377): Initializing JXcore engine
,W/jxcore-log( 5377): JXcore engine is ready
W/Thread-642( 5467): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6386]" dev="sockfs" ino=6386 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-642( 5467): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-642( 5467): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6508]" dev="sockfs" ino=6508 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-642( 5467): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-642( 5467): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-642( 5467): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[25873]" dev="sockfs" ino=25873 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 5377): Starting JXcore engine
,W/jxcore-log( 5377): Platform android
W/jxcore-log( 5377): 
,W/jxcore-log( 5377): Process ARCH arm
W/jxcore-log( 5377): 
I/CalendarProvider2( 5474): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5474): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  842): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=5508 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  842): Killing 5248:com.android.contacts/u0a18 (adj 15): empty #11
,W/libprocessgroup(  842): failed to open /acct/uid_10018/pid_5248/cgroup.procs: No such file or directory
,W/ResourcesManager( 5508): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 5508): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 5508): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 5508): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@3cba6bfa, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@25a255ab, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@297ac408, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@373017a1, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@e334dc6, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1aaea187, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@6fc18b4, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@18158cdd, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@22068052, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@949cf23, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@99c0c20, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@23e319d9, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@10684f9e, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@36e03a7f, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@2c85ca4c, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@3b627a95, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@2e85c7aa, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@2947ff9b, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@106b3f38, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@83d2b11, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@550b476, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@239cfa77, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@2d3116e4, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@b38674d, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@290ba202, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@14dcc713, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@325abd50, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@12312b49, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@3d95dc4e, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1442c16f, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@2365e7c, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@11d83305, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@33776f5a, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@764058b, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@33c8e668, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@1f2dfa81, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@9ad2726, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@e0b6f67, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@77a0114, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@4bebdbd, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@20348fb2, lg_preferences_recent_t,imezones=com.android.calendar.adaptation.PreferenceKey$KeyData@fd59b03, lg
,D/GeneralPreferenceUtils( 5508): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 5508): [init]
,I/Config  ( 5508): LGCalendar ver.4.40.17
I/Config  ( 5508): start check model
I/Config  ( 5508): start check native_ca
I/Config  ( 5508): Config Operator=OPEN, Country=EU
D/Config  ( 5508): [setDefaultValuesToPref]
D/Config  ( 5508): [parseProfiles]
D/ProfilesParser( 5508): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 5508): [debug_displayParseInfos] profile.operator = null
D/Config  ( 5508): [updateProfiletoCountryInfo]
D/GeneralPreference( 5508): [checkAndMigrateOldPreference]
D/AlertReceiver( 5508): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,I/InitNotificationRingtoneService( 5508): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 5508): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,I/AlertUtils( 5508): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 5508): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
,I/AlertUtils( 5508): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 5508): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 5508): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 5508): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 5508): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/AlertUtils( 5508): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 5508): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 5508): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 5508): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 5508): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 5508): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 5508): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 5508): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 5508): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
,I/AlertUtils( 5508): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 5508): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 5508): End InitializeAlertRingtoneService.onHandleIntent
,W/HolidayIntentService( 5508): onHandleIntent
,D/HolidayDataLoader( 5508): readJsonAsset : holiday.json
D/AlertService( 5508): 0 Action = android.intent.action.PROVIDER_CHANGED
,E/AgendaWidgetManager( 5508): [updateWidgets] 
,D/MonthWidgetProvider( 5508): [onReceive]
D/CalendarWidgetProvider( 5508): [onReceive]
D/CalendarWidgetProvider( 5508): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 5508): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 5508): [onReceive]
D/CalendarWidgetProvider( 5508): [onReceive]
,D/CalendarWidgetProvider( 5508): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
I/jxcore-log( 5377): JXcore Cordova bridge is ready!
I/jxcore-log( 5377): 
W/jxcore-log( 5377): JXcore engine is started
D/CalendarTypeController( 5508): [onCreate] mContext.getPackageName() = com.android.calendar
E/HolidayIntentService( 5508): onHandleIntent:holiday data empty
,I/jxcore-log( 5377): Toggling radios to true
I/jxcore-log( 5377): 
,D/BluetoothManagerService(  842): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  842): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  842): Message: 1
D/BluetoothManagerService(  842): MESSAGE_ENABLE: mBluetooth = null
D/BluetoothAdapterService(404065501)( 1989): onBind()
,D/BluetoothManagerService(  842): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  842): Message: 40
D/BluetoothManagerService(  842): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/LocationManagerService(  842): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  842): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  842): JNI:system_update. Event-4
D/WifiServiceImplEx(  842): setWifiEnabled: true pid=5377, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService(  842): setWifiEnabled: true pid=5377, uid=10316
,D/LocationManagerService(  842): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  842): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  842): JNI:system_update. Event-4
,D/WifiServiceImplEx(  842): disconnect pid=5377, uid=10316, packageName=com.test.thalitest
D/WifiServiceImplEx(  842): reconnect pid=5377, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 5377): Radios toggled
I/jxcore-log( 5377): 
I/jxcore-log( 5377): My device name is: LGE-LG-D722
I/jxcore-log( 5377): 
I/bluedroid( 1989): config_hci_snoop_log
I/LGFTMITEM(  842): [GET_FTM][id=6], offset=12288
D/BluetoothManagerService(  842): Calling onBluetoothServiceUp callbacks
,E/WifiHW  (  842): Wifi MAC Address = a0:39:f7:70:12:80
D/BluetoothManagerService(  842): Broadcasting onBluetoothServiceUp() to 9 receivers.
E/WifiHW  (  842): wifi_check_config compare "cur_etheraddr=a0:39:f7:70:12:80
E/WifiHW  (  842): band=b
E/WifiHW  (  842): ": cur_etheraddr=a0:39:f7:70:12:80
V/LGMDMManagerInternal( 1989): Create singleton instance
D/SoftapController(  274): Softap fwReload - Ok
,D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  274): Setting iface cfg
D/CommandListener(  274): Trying to bring down wlan0
D/CommandListener(  274): Clearing all IP addresses on wlan0
E/WifiHW  (  842): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,I/wpa_supplicant( 5547): Successfully initialized wpa_supplicant
,D/WifiMonitor(  842): startMonitoring(wlan0) with mConnected = false
,I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
,I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 20:29:35.651 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
I/wpa_supplicant( 5547): rfkill: Cannot open RFKILL control device
I/wpa_supplicant( 5547): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/ActivityManager(  842): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=5559 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/WifiServerServiceExt(  842): WIFI_STATE_CHANGED_ACTION [2]
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
,I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.WIFI_STATE_CHANGED at null
D/BluetoothAdapterService(404065501)( 1989): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2947ff9b
D/BluetoothAdapterService(404065501)( 1989): enable() - Enable called with quiet mode status =  false
D/BluetoothAdapterState( 1989): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 1989): Setting state to 11
I/BluetoothAdapterState( 1989): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService(404065501)( 1989): updateAdapterState() - Broadcasting state to 1 receivers.
D/BluetoothManagerService(  842): Message: 60
,D/BluetoothAdapterService(404065501)( 1989): processStart()
D/BtSettings.ProfileConfig( 1989): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BluetoothManagerService(  842): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  842): Bluetooth State Change Intent: 10 -> 11
D/LGBluetoothAPIService( 1806): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/BtSettings.ProfileConfig( 1989): Unable to read settings
D/BtSettings.ProfileConfig( 1989): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1989): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 1989): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 1989): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 1989): 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:672)
D/BtSettings.ProfileConfig( 1989): 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
D/BtSettings.ProfileConfig( 1989): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 1989): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 1989): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 1989): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 1989): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/BluetoothAdapterService( 1989): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1989): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 1989): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 1989): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 1989): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 1989): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 1989): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 1989): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 1989): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 1989): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 1989): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 1989): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 1989): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 1989): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 1989): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 1989): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
,W/BluetoothAdapterService( 1989): isProfileEnabled(): profile not found com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 1989): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 1989): isProfileEnabled(): profile not found com.broadcom.bt.service.opp.OppService
,D/BluetoothAdapterService(404065501)( 1989): processStart() - Make Bond State Machine
D/BluetoothAdapterService(404065501)( 1989): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2947ff9b
D/BluetoothAdapterService(404065501)( 1989): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2947ff9b
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
D/BluetoothBondStateMachine( 1989): make
I/[SystemUI]BluetoothHandler( 1376): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,D/BluetoothAdapterService( 1989): setAdapterService() - set to: null
I/BluetoothBondStateMachine( 1989): StableState(): Entering Off State
D/BluetoothAdapterService( 1989): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18158cdd
D/LGBluetoothServiceAdapter( 1989): [BTUI] check adapter is available - true : set adapter available.
D/BluetoothAdapterService( 1989): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1989): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1989): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1989): Unable to read settings
D/BtSettings.ProfileConfig( 1989): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1989): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 1989): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 1989): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 1989): 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
D/BtSettings.ProfileConfig( 1989): 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:712)
D/BtSettings.ProfileConfig( 1989): 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
D/BtSettings.ProfileConfig( 1989): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 1989): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 1989): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 1989): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 1989): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BluetoothAdapterService( 1989): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService(404065501)( 1989): setProfileServiceState() - Starting service com.android.bluetooth.hfp.HeadsetService
,D/BluetoothAdapterService( 1989): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1989): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 1989): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 1989): Not skipping com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService(404065501)( 1989): setProfileServiceState() - Starting service com.android.bluetooth.a2dp.A2dpService
D/HeadsetService( 1989): Received start request. Starting profile...
D/BluetoothAdapterService( 1989): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1989): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 1989): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 1989): Not skipping com.android.bluetooth.hid.HidService
D/BluetoothAdapterService(404065501)( 1989): setProfileServiceState() - Starting service com.android.bluetooth.hid.HidService
,D/BluetoothHeadset( 1753): Proxy object connected
I/LGBluetoothHeadsetServiceJni( 1989): classInitNative: succeeds
D/BluetoothHeadset(  842): Proxy object connected
D/BluetoothAdapterService( 1989): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1989): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 1989): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 1989): Not skipping com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService(404065501)( 1989): setProfileServiceState() - Starting service com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 1989): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1989): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 1989): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 1989): Not skipping com.android.bluetooth.pan.PanService
D/BluetoothAdapterService(404065501)( 1989): setProfileServiceState() - Starting service com.android.bluetooth.pan.PanService
,D/BluetoothAdapterService(404065501)( 1989): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2947ff9b
D/BluetoothAdapterService( 1989): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1989): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 1989): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 1989): Not skipping com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(404065501)( 1989): setProfileServiceState() - Starting service com.android.bluetooth.gatt.GattService
D/LGBluetoothFeatureConfig( 1989): isPrivacyLogsEnabled : true
I/BluetoothHeadsetServiceJni( 1989): classInitNative: succeeds
D/BluetoothHeadset( 1753): Proxy object connected
D/HeadsetStateMachine( 1989): make
,D/BluetoothHeadset( 1753): Proxy object connected
D/BluetoothAdapterService( 1989): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1989): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 1989): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 1989): Not skipping com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService(404065501)( 1989): setProfileServiceState() - Starting service com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 1989): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1989): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 1989): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 1989): Not skipping com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(404065501)( 1989): setProfileServiceState() - Starting service com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 1989): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1989): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 1989): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 1989): Not skipping com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(404065501)( 1989): setProfileServiceState() - Starting service com.broadcom.bt.service.ftp.FTPService
W/ResourcesManager( 5559): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5559): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 5559): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothAdapterService( 1989): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1989): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
D/BtSettings.ProfileConfig( 1989): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 1989): Not skipping com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(404065501)( 1989): setProfileServiceState() - Starting service com.broadcom.bt.service.opp.OppService
V/LGMDMManager( 1989): Create singleton instance
W/ResourcesManager( 5559): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 5559): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/BluetoothAdapterState( 1989): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetStateMachine( 1989): max_hf_connections = 1
I/bluedroid( 1989): get_profile_interface handsfree
,I/bt-btif ( 1989): btif_hf_get_interface
I/bt-btif ( 1989): init
D/bt-btif ( 1989): max_hf_clients = 1
D/bt-btif ( 1989): btif_max_hf_clients = 1
D/bt-btif ( 1989): btif_enable_service: current services:0xa0688330
V/ToneGenerator( 1989): ToneGenerator constructor: streamType=8, volume=1.000000
V/AudioPolicyService(  278): registerClient() client 0xb57f11a0, uid 1002
V/AudioPolicyManager(  278): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  278): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  278): getOutput() returns output 2
V/AudioFlinger(  278): registerClient() client 0xb55627f0, pid 1989
V/AudioFlinger(  278): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  278): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  278): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  278): thread 0xb5735000 type 0 TID 1301 waking up
V/AudioSystem( 1989): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioFlinger(  278): thread 0xb5651000 type 0 TID 1298 waking up
V/AudioFlinger(  278): processConfigEvents_l() remaining events 1
V/AudioFlinger(  278): PlaybackThread::audioConfigChanged, thread 0xb5735000, event 0, param 0
V/AudioFlinger(  278): processConfigEvents_l() remaining events 1
V/AudioFlinger(  278): PlaybackThread::audioConfigChanged, thread 0xb5651000, event 0, param 0
V/AudioSystem(  278): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem(  278): ioConfigChanged() opening already existing output! 6
V/ToneGenerator( 1989): Create Track: 0xb4909480
V/AudioTrack( 1989): set(): streamType 8, sampleRate 48000, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 1989): set() streamType 8, sampleRate 48000, format 1, frameCount 0, flags 0004
V/AudioFlinger(  278): thread 0xb56eb000 type 0 TID 1299 waking up
V/AudioFlinger(  278): processConfigEvents_l() DONE thread 0xb5735000
I/AudioFlinger(  278): isAudioPlaybackHookOn() false
V/AudioFlinger(  278): processConfigEvents_l() remaining events 1
V/AudioFlinger(  278): PlaybackThread::audioConfigChanged, thread 0xb56eb000, event 0, param 0
V/AudioSystem( 1989): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem(  278): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  278): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1989): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 1152 latency 112
V/AudioSystem( 1989): ioConfigChanged() event 0, ioHandle 4
V/AudioFlinger(  278): processConfigEvents_l() DONE thread 0xb56eb000
V/AudioSystem( 1989): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
D/AudioTrack( 1989): TrackOffload: AudioTrack Offload disabled by property, returning false
V/AudioPolicyManager(  278): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  278): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  278): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  278): getOutput() returns output 2
V/AudioSystem(  842): ioConfigChanged() event 0, ioHandle 6
,V/AudioSystem(  842): ioConfigChanged() opening already existing output! 6
V/AudioSystem(  842): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  842): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1376): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1376): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1376): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1376): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1753): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1753): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1753): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1753): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1938): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1938): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1938): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1938): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 2753): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 2753): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 2753): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 2753): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3104): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 3104): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 3104): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3104): ioConfigChanged() opening already existing output! 4
V/AudioSystem(  278): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  278): ioConfigChanged() opening already existing output! 2
V/AudioFlinger(  278): processConfigEvents_l() DONE thread 0xb5651000
V/AudioSystem( 2753): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  842): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2753): ioConfigChanged() opening already existing output! 2
V/AudioSystem(  842): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1938): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1938): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3104): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3104): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1376): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1376): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1989): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1989): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/AudioSystem( 1753): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1753): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1989): getLatency() output 2, latency 50
V/AudioSystem( 1989): getFrameCount() output 2, frameCount 960
V/AudioTrack( 1989): createTrack_l() output 2 afLatency 50
V/AudioTrack( 1989): Create normal PCM 0x1 Track
V/AudioFlinger(  278): createTrack() lSessionId: 22
V/AudioFlinger(  278): AUDIO_OUTPUT_FLAG_FAST accepted: frameCount=480 mFrameCount=240
V/AudioFlinger(  278): sendConfigEvent_l() num events 1 event 1
V/AudioTrack( 1989): Flags here  0x4 
V/AudioTrack( 1989): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  278): acquiring 22 from 1989, for 1989
V/AudioFlinger(  278):  added new entry for 22
V/ToneGenerator( 1989): ToneGenerator INIT OK, time: 85451
D/BluetoothAdapterService( 1989): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18158cdd
D/HeadsetStateMachine( 1989): Enter Disconnected: -2, size: 0
D/HeadsetPhoneState( 1989): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 1989): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 1989): [BTUI] change sampling rate to 8000 when device is disconnected
D/BluetoothAdapterService( 1989): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18158cdd
V/AudioFlinger(  278): ,setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 1989
D/BluetoothA2dp(  842): Proxy object connected
D/audio_hw_primary(  278): adev_set_parameters: enter: bt_samplerate=8000
V/AudioFlinger(  278): processConfigEvents_l() remaining events 1
V/AudioFlinger(  278): processConfigEvents_l() DONE thread 0xb5651000
V/voice   (  278): voice_set_parameters: enter: bt_samplerate=8000
D/A2dpService( 1989): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 1989): classInitNative: succeeds
V/compress_voip(  278): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  278): voice_extn_compress_voip_set_parameters: exit
V/voice   (  278): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  278): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  278): platform_set_parameters: enter: bt_samplerate=8000
D/BluetoothAdapterService(404065501)( 1989): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2947ff9b
V/Avrcp   ( 1989): make
D/Avrcp   ( 1989): [BTUI] Use Native AVRCP : init jni
I/bluedroid( 1989): get_profile_interface avrcp
I/bt-btif ( 1989): btif_rc_get_interface
I/bt-btif ( 1989): ## init ##
I/LGBluetoothAvrcpServiceJni( 1989): classInitNative: succeeds
V/msm8974_platform(  278): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  278): lge_platform_set_loopback_parameters: enter: 
I/LGBluetoothAvrcpAdapter( 1989): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
I/LGBluetoothAvrcpServiceJni( 1989): initNative: succeeds
D/audio_hw_extn(  278): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  278): adev_set_parameters: exit with code(0)
I/BluetoothAvrcpBrcmAdapterJni( 1989): classInitBrcmNative
I/BluetoothAvrcpBrcmAdapterJni( 1989): initBrcmNative
V/ToneGenerator( 1989): ToneGenerator destructor
V/ToneGenerator( 1989): stopTone
V/ToneGenerator( 1989): Delete Track: 0xb4909480
,V/AudioTrack( 1989): ~AudioTrack, releasing session id from 1989 on behalf of 1989
V/AudioFlinger(  278): releasing 22 from 1989 for 1989
V/AudioFlinger(  278):  decremented refcount to 0
V/AudioFlinger(  278): purging stale effects
V/AudioFlinger(  278): remove track (4099) and delete from mixer
V/AudioPolicyService(  278): AudioCommandThread() adding release output 2
V/AudioPolicyService(  278): inserting command: 6 at index 0, num commands 0
V/AudioPolicyService(  278): AudioCommandThread() waking up
V/AudioPolicyService(  278): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  278): releaseOutput() 2
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
V/AudioFlinger(  278): PlaybackThread::Track destructor
V/AudioFlinger(  278): removeClient_l() pid 1989, calling pid 278
I/IndexDatabaseHelper( 5559): Using schema version: 115
,I/IndexDatabaseHelper( 5559): Index is fine
V/AudioService(  842): updateRemoteControllerOnExistingMediaPlayers: size of Player list: 0
,E/AudioService(  842): No RCC entry present to update
E/RemoteController( 1989): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 1989): classInitNative
I/BluetoothA2dpServiceJni( 1989): classInitNative: succeeds
D/A2dpStateMachine( 1989): make
I/bluedroid( 1989): get_profile_interface a2dp
I/bt-btif ( 1989): btif_av_get_src_interface
I/bt-btif ( 1989): init
D/bt-btif ( 1989): btif_enable_service: current services:0xa0688330
I/LGBluetoothA2dpServiceJni( 1989): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 1989): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/LGBluetoothPowerControlManager( 1989): [BTUI] getInstance
D/LGBluetoothPowerControlManager( 1989): [BTUI] init
D/LGBluetoothPowerControlManager( 1989): [BTUI] init : getProfileProxy
D/BluetoothManagerService(  842): Message: 30
,D/BluetoothAdapterService( 1989): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18158cdd
I/BluetoothHidServiceJni( 1989): classInitNative: succeeds
D/HidService( 1989): Received start request. Starting profile...
I/bluedroid( 1989): get_profile_interface hidhost
I/bt-btif ( 1989): btif_hh_get_interface
I/bt-btif ( 1989): init
D/bt-btif ( 1989): btif_enable_service: current services:0xa0688330
D/BluetoothAdapterService( 1989): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18158cdd
I/BluetoothHealthServiceJni( 1989): classInitNative: succeeds
D/HealthService( 1989): Received start request. Starting profile...
D/A2dpStateMachine( 1989): Enter Disconnected: -2
I/bluedroid( 1989): get_profile_interface health
I/bt-btif ( 1989): btif_hl_get_interface
I/bt-btif ( 1989): init
D/bt-btif ( 1989): Process name (droid.bluetooth)
D/bt-btif ( 1989): btif_hl_soc_thread_init
,D/bt-btif ( 1989): create_thread: entered
D/bt-btif ( 1989): create_thread: thread created successfully
D/bt-btif ( 1989): entered btif_hl_select_thread
D/bt-btif ( 1989): btif_hl_select_wakeup_init
D/bt-btif ( 1989): btif_hl_select_wakeup_init signal_fds[0]=55 signal_fds[1]=56
D/bt-btif ( 1989): max_s=55 
D/bt-btif ( 1989): set curr_set = org_set 
I/LGBluetoothHealthServiceJni( 1989): classInitNative: succeeds
D/BluetoothAdapterService( 1989): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18158cdd
I/BluetoothPanServiceJni( 1989): classInitNative(L105): succeeds
D/PanService( 1989): Received start request. Starting profile...
D/BluetoothPanServiceJni( 1989): initializeNative(L110): pan
I/bluedroid( 1989): get_profile_interface pan
D/bt-btif ( 1989): stack_initialized = 0, btpan_cb.enabled:0
,I/LGBluetoothPanAdapter( 1989): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 1989): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18158cdd
I/BtGatt.JNI( 1989): classInitNative(L901): classInitNative: Success!
D/BtGatt.DebugUtils( 1989): handleDebugAction() action=null
,D/BtGatt.GattService( 1989): Received start request. Starting profile...
D/BtGatt.GattService( 1989): start()
I/bluedroid( 1989): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 1989): advertise manager created
I/LGBluetoothGattAdapter( 1989): [BTUI] getInstance : create [LGBluetoothGattAdapter]
D/LGBluetoothGattAdapter( 1989): setGattService:  set to: null
D/BluetoothAdapterService( 1989): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18158cdd
D/BluetoothAdapterService( 1989): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18158cdd
I/LGBluetoothMapAdapter( 1989): [BTUI] getInstance : create [LGBluetoothMapAdapter]
,V/BluetoothMapService( 1989): BluetoothMapBinder()
D/BluetoothMapService( 1989): Received start request. Starting profile...
D/BluetoothMapService( 1989): start()
D/BluetoothMapEmailSettingsLoader( 1989): Found 0 applications
D/BluetoothMapEmailAppObserver( 1989): createReceiver()
D/BluetoothMapEmailAppObserver( 1989): initObservers()
D/BluetoothMapEmailAppObserver( 1989): getEnabledAccountItems()
,D/BluetoothAdapterService( 1989): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18158cdd
I/BluetoothSAPServiceJni( 1989): classInitNative(L170): succeeds
,D/SapService( 1989): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 1989): initializeNative(L175): sap
I/bluedroid( 1989): get_profile_interface sap
I/bt-btif ( 1989): btif_sc_get_interface
I/bt-btif ( 1989): init
D/bt-btif ( 1989): btif_enable_service: current services:0xa0688330
I/LGBluetoothSapAdapter( 1989): [BTUI] getInstance : create [LGBluetoothSapAdapter]
I/LGBluetoothSapAdapter( 1989): [BTUI] Create LGBluetoothSapManager Instance
V/WiFiOffLoadBroadcast( 5559): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/LGBluetoothSapManager( 1989): [BTUI] initSapManager
D/BluetoothAdapterService( 1989): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18158cdd
,D/LgeBluetoothSimManager( 1753): [BTUI] SAP_ENABLE_EVT
V/BluetoothFTPServiceJni( 1989): classInitNative
I/BluetoothFTPServiceJni( 1989): classInitNative(L271): succeeds
D/BluetoothAdapterService( 1989): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18158cdd
D/BluetoothFTPService( 1989): BluetoothFtpBinder()
,D/**BluetoothFTPService( 1989): Received start request. Starting profile...
V/BluetoothFTPService( 1989): FTP-Server Service start
D/BluetoothFTPServiceJni( 1989): initFtpNativeDataNative(L275): FTP
I/bluedroid( 1989): get_profile_interface ftp
I/bt-btif ( 1989): btif_fts_get_interface
I/bt-btif ( 1989): init
D/bt-btif ( 1989): btif_enable_service: current services:0xa0688330
D/BluetoothFTPServiceJni( 1989): initFtpNativeDataNative(L317): FTP init done
D/BluetoothAdapterService( 1989): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18158cdd
D/LGBluetoothFeatureConfig( 1989): isPrivacyLogsEnabled : true
E/BluetoothOPPServiceJni( 1989): classInitNative
I/BluetoothOPPServiceJni( 1989): classInitNative(L373): succeeds
V/OppService( 1989): Opp initBinder
D/**OppService( 1989): Received start request. Starting profile...
D/OppService( 1989): Starting OppService 
D/LGBluetoothOppAdapter( 1989): [BTUI] getInstance : create [LGBluetoothOppAdapter]
I/NotificationManager( 1989): com.android.bluetooth: cancelAll by com.android.bluetooth
,V/BluetoothOppNotification( 1989): send message
D/BluetoothOppPreference( 1989): Dumping Names:  
D/BluetoothOppPreference( 1989): {}
D/BluetoothOppPreference( 1989): Dumping Channels:  
D/BluetoothOppPreference( 1989): {}
D/OppService( 1989): Start()
W/BluetoothOPPServiceJni( 1989): initOppNative
D/BluetoothOPPServiceJni( 1989): initOppNative(L383): OPP
I/bluedroid( 1989): get_profile_interface opp
I/bt-btif ( 1989): btif_op_get_interface
D/BluetoothOPPServiceJni( 1989): initOppNative(L411): mOppCallbacksObj 2098426
D/BluetoothOPPServiceJni( 1989): initOppNative(L413): calling OPP init
I/bt-btif ( 1989): btif_opp_init
D/bt-btif ( 1989): btif_enable_service: current services:0xa0688330
,D/BluetoothOPPServiceJni( 1989): initOppNative(L429): OPC and OPS init Succesful
D/BluetoothOPPServiceJni( 1989): initOppNative(L430): mOppCallbacksObj 2098426
,V/OppService( 1989): setOppService(): set to: com.broadcom.bt.service.opp.OppService@25fb256b
D/BluetoothAdapterService( 1989): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18158cdd
V/OppService( 1989): pendingUpdate is :  true
D/HeadsetStateMachine( 1989): Proxy object connected
D/LGBluetoothHfpAdapter( 1989): [BTUI] queryPhoneState
D/BluetoothAdapterService(404065501)( 1989): handleMessage() - Message: 1
D/HeadsetStateMachine( 1989): Disconnected process message: 10, size: 0
D/BluetoothAdapterService(404065501)( 1989): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(404065501)( 1989): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
D/HeadsetPhoneState( 1989): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/BluetoothAdapterState( 1989): isTurningOnRadio()=false
D/BluetoothAdapterState( 1989): isTurningOffRadio()=false
D/HeadsetStateMachine( 1989): Disconnected process message: 11, size: 0
D/BluetoothAdapterState( 1989): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1989): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1989): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/BluetoothOppProvider( 1989): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
D/BluetoothAdapterService( 1989): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothA2dp( 1989): Proxy object connected
D/LGBluetoothPowerControlManager( 1989): [BTUI] onServiceConnected : Got BluetoothA2dp: android.bluetooth.BluetoothA2dp@364f3086
D/BluetoothAdapterService(404065501)( 1989): handleMessage() - Message: 1
D/BluetoothAdapterService(404065501)( 1989): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(404065501)( 1989): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
D/BluetoothAdapterState( 1989): isTurningOnRadio()=false
D/BluetoothAdapterState( 1989): isTurningOffRadio()=false
D/BluetoothAdapterState( 1989): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1989): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1989): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
,V/OppService( 1989): Deleted complete outbound shares, number =  0
V/OppService( 1989): Deleted complete inbound failed shares, number = 0
D/BluetoothAdapterService( 1989): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothOppProvider( 1989): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
D/BluetoothAdapterService(404065501)( 1989): handleMessage() - Message: 1
D/BluetoothAdapterService(404065501)( 1989): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(404065501)( 1989): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
D/BluetoothAdapterState( 1989): isTurningOnRadio()=false
D/BluetoothAdapterState( 1989): isTurningOffRadio()=false
D/BluetoothAdapterState( 1989): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1989): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1989): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/BluetoothOppProvider( 1989): created cursor android.database.sqlite.SQLiteCursor@e24ad47 on behalf of 
D/BluetoothAdapterService( 1989): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(404065501)( 1989): handleMessage() - Message: 1
D/BluetoothAdapterService(404065501)( 1989): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(404065501)( 1989): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
D/BluetoothAdapterState( 1989): isTurningOnRadio()=false
D/BluetoothAdapterState( 1989): isTurningOffRadio()=false
D/BluetoothAdapterState( 1989): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1989): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1989): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/BluetoothOppProvider( 1989): created cursor android.database.sqlite.SQLiteCursor@3e539974 on behalf of 
V/BluetoothOppNotification( 1989): update too frequent, put in queue
,D/BluetoothAdapterService( 1989): Profile still not running:com.broadcom.bt.service.opp.OppService
V/PanService( 1989): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService(404065501)( 1989): handleMessage() - Message: 1
D/BluetoothAdapterService(404065501)( 1989): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(404065501)( 1989): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
D/BluetoothAdapterState( 1989): isTurningOnRadio()=false
D/BluetoothAdapterState( 1989): isTurningOffRadio()=false
D/BluetoothAdapterState( 1989): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1989): isQuietModeServiceTurningOff()=false
V/OppService( 1989): pendingUpdate is :  false
E/OppService( 1989): UpdateThread is Completed
D/BluetoothAdapterService( 1989): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1989): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(404065501)( 1989): handleMessage() - Message: 1
D/BluetoothAdapterService(404065501)( 1989): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(404065501)( 1989): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=true
D/BluetoothAdapterState( 1989): isTurningOnRadio()=false
D/BluetoothAdapterState( 1989): isTurningOffRadio()=false
D/BluetoothAdapterState( 1989): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1989): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1989): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1989): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothPbapReceiver( 1989): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1989): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1989): ***********state = 11
V/BluetoothMapService( 1989): Handler(): got msg=1
D/BluetoothAdapterService(404065501)( 1989): handleMessage() - Message: 1
D/BluetoothAdapterService(404065501)( 1989): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(404065501)( 1989): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
D/BluetoothAdapterState( 1989): isTurningOnRadio()=false
D/BluetoothAdapterState( 1989): isTurningOffRadio()=false
D/BluetoothAdapterState( 1989): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1989): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1989): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
,D/BluetoothAdapterService( 1989): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(404065501)( 1989): handleMessage() - Message: 1
D/BluetoothAdapterService(404065501)( 1989): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(404065501)( 1989): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
D/BluetoothAdapterState( 1989): isTurningOnRadio()=false
D/BluetoothAdapterState( 1989): isTurningOffRadio()=false
D/BluetoothAdapterState( 1989): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1989): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1989): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1989): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(404065501)( 1989): handleMessage() - Message: 1
D/BluetoothAdapterService(404065501)( 1989): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(404065501)( 1989): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, doUpdate=true
D/BluetoothAdapterState( 1989): isTurningOnRadio()=false
D/BluetoothAdapterState( 1989): isTurningOffRadio()=false
D/BluetoothAdapterState( 1989): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1989): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1989): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 1989): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothOppNotification( 1989): new notify threadi!
V/BluetoothOppNotification( 1989): send delay message
D/BluetoothAdapterService(404065501)( 1989): handleMessage() - Message: 1
D/BluetoothAdapterService(404065501)( 1989): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(404065501)( 1989): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=12, doUpdate=true
D/BluetoothAdapterState( 1989): isTurningOnRadio()=false
D/BluetoothAdapterState( 1989): isTurningOffRadio()=false
D/BluetoothAdapterState( 1989): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1989): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1989): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService(404065501)( 1989): onProfileServiceStateChange() - All profile services started.
V/OppService( 1989): ContentObserver received notification
V/OppService( 1989): ContentObserver received notification
D/BluetoothAdapterState( 1989): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
V/BluetoothOppProvider( 1989): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
I/bluedroid( 1989): enable
I/bt-btif ( 1989): BTIF ENABLE BLUETOOTH :: current btif_core_radio_refcount: 0, btif_core_state: 0, btif_core_cb.dut_mode: 0
E/bt-btu  ( 1989): VERSION AFBT-LREL-30_00.06 (BTE: BTE0322_00.20.00)
,V/BluetoothOppProvider( 1989): created cursor android.database.sqlite.SQLiteCursor@2611de9d on behalf of 
V/OppService( 1989): pendingUpdate is :  true
V/BluetoothOppProvider( 1989): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
I/bt_hci_bdroid( 1989): init
I/bt_vendor( 1989): init
I/bt_vnd_conf( 1989): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 1989): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
I/bt-btif ( 1989): libbt-hci init returns 0
I/GKI_LINUX( 1989): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 1989): btu_task pending for preload complete event
V/BluetoothOppNotification( 1989): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 1989): created cursor android.database.sqlite.SQLiteCursor@31ddcf12 on behalf of 
V/BluetoothOppProvider( 1989): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/OppService( 1989): pendingUpdate is :  false
E/OppService( 1989): UpdateThread is Completed
,V/BluetoothOppProvider( 1989): created cursor android.database.sqlite.SQLiteCursor@a74d6e3 on behalf of 
V/BluetoothOppNotification( 1989): outbound: succ-0  fail-0
I/NotificationManager( 1989): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
V/BluetoothOppNotification( 1989): outbound notification was removed.
V/BluetoothOppProvider( 1989): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 1989): created cursor android.database.sqlite.SQLiteCursor@23cad8e0 on behalf of 
V/BluetoothOppNotification( 1989): inbound: succ-0  fail-0
I/NotificationManager( 1989): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
D/WiFiOffLoadUpdatePriority( 5559): remove : truetruefalse
V/BluetoothOppNotification( 1989): inbound notification was removed.
D/WiFiOffLoadUpdatePriority( 5559): remove2
V/WiFiOffLoadSharedPrefsUtils( 5559): save wifi state
V/WiFiOffLoadSharedPrefsUtils( 5559): save remove
D/WiFiOffLoadBroadcast( 5559): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 5559): S: false, R: true
,V/BluetoothOppProvider( 1989): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1989): created cursor android.database.sqlite.SQLiteCursor@28b2c799 on behalf of 
I/bt_userial_vendor( 1989): userial vendor open: opening /dev/ttyHS99
,D/bt_userial_vendor( 1989): userial_vendor_open():UART is setup
I/bt_userial_vendor( 1989): device fd = 67 open
,I/ActivityManager(  842): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5601 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/bt_hwcfg( 1989): hw_config_cback opcode:0x0c03
D/bt_hwcfg( 1989): hw_config_cback state=1
D/bt_hwcfg( 1989): hw_config_cback opcode:0x0c14
D/bt_hwcfg( 1989): hw_config_cback state=4
D/bt_hwcfg( 1989): Chipset Name: BCM4334B0
D/bt_hwcfg( 1989): Chipset BCM4334B0
D/bt_hwcfg( 1989): Target name = [BCM4334B0]
I/bt_hwcfg( 1989): Found patchfile: /system/bin//BCM4334B0_002.001.013.1820.2163.hcd
,D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc45
D/bt_hwcfg( 1989): hw_config_cback state=2
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc18
D/bt_hwcfg( 1989): hw_config_cback state=3
I/bt_hwcfg( 1989): bt vendor lib: set UART baud 4000000
I/ActivityManager(  842): Process com.android.vending (pid 4888) has died
,D/BluetoothPermissionRequest( 5559): onReceive
D/LGBluetoothFeatureConfig( 5559):  get() - isFeatureLoaded : false
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc2e
D/bt_hwcfg( 1989): hw_config_cback state=5
,D/BluetoothManagerService(  842): Message: 20
D/BluetoothManagerService(  842): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@472683b:true
,V/BluetoothSapReceiver( 1989): [BTUI] checkServiceStart
,D/LGBluetoothStateChangeReceiver( 1989): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/PCSuite ( 5601): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
,D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
,D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
,D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
,D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
,D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
,I/ActivityManager(  842): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=5621 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
,D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
,D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
I/ActivityManager(  842): Killing 5275:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
,D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
,D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
,D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
,D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
,D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
,D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
,D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
W/libprocessgroup(  842): failed to open /acct/uid_10069/pid_5275/cgroup.procs: No such file or directory
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/Tethering(  842): sendTetherStateChangedBroadcast 1, 0, 0
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
,D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
E/wpa_supplicant( 5547): USIM:  scard_init function
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
I/wpa_supplicant( 5547): rfkill: Cannot open RFKILL control device
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
I/Netd    (  274): M: Get netlink event, ifname: p2p0 action: 4
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
I/Netd    (  274): M: Get netlink event, ifname: p2p0 action: 9
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
I/Netd    (  274): M: Get netlink event, ifname: p2p0 action: 4
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
,D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
I/ActivityManager(  842): Process com.google.android.talk (pid 5100) has died
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
,D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/DSQN    (  842): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
,D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/UsbSettingsReceiver( 5559): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 5559): [AUTORUN] sys.usb.config = ptp_only,adb
D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/UsbSettingsReceiver( 5559): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 5559): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/UsbSettingsReceiver( 5559): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
,D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
,D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
,D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
,D/UsbSettingsControl( 5559): [AUTORUN] getUsbConnected() : connected=true
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/UsbSettingsReceiver( 5559): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 5559): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 5559): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 5559): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 5559): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/UsbSettingsControl( 5559): [AUTORUN] setTetherStatus() : status=false
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
,D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
,D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c,
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 1989): hw_config_cback state=6
I/wpa_supplicant( 5547): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
,D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
,D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 1989): hw_config_cback state=6
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc4e
D/bt_hwcfg( 1989): hw_config_cback state=6
I/wpa_supplicant( 5547): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiStateMachine(  842): MAC Addr from driver = a0:39:f7:70:12:80
D/WifiOffDelayIfNotUsed(  842): setPowerSaveActivated(false)
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 20:29:36.825 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.WIFI_STATE_CHANGED at null
I/WifiServerServiceExt(  842): WIFI_STATE_CHANGED_ACTION [3]
I/WifiServerServiceExt(  842): batteryPsActivateMsgHandler : state:0 event:3
E/WifiServerServiceExt(  842): sendAutoJoinStatus  LgeWifiConfig.mEnableAutoJoin : 0
V/WiFiOffLoadBroadcast( 5559): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,E/WifiConfigStore(  842): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiStateMachine(  842): enableVerboseLogging : level 2
D/WifiStateMachine(  842): Setting OUI to DA-A1-19
D/WfdsService( 1806): Supplicant Connection state is changed : true
D/WfdsService( 1806): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1806): Set the WFDS Monitor: true
D/WifiNative-HAL(  842): Setting external_sim to 1
I/WifiNative-HAL(  842): startHal
E/wifi    (  842): getStaticLongField sWifiHalHandle 0x9ab4f8ec
I/WifiHAL (  842): Initializing wifi
I/WifiHAL (  842): Creating socket
,D/WfdsMonitor( 1806): WfdsMonitorThread create
D/WfdsMonitor( 1806): WFDS Monitor is created and started
D/WfdsService( 1806): WiFi: Supplicant connection re-established
I/WifiHAL (  842): Initialized Wifi HAL Successfully; vendor cmd = 103
D/wifi    (  842): Did set static halHandle = 0xb07ae640
E/CtrlSupplicant( 1806): Access OK "@android:wpa_wlan0"
D/wifi    (  842): halHandle = 0xb07ae640, mVM = 0xb487c280, mCls = 0x90170a
E/wifi    (  842): getStaticLongField sWifiHalHandle 0x9ab4f89c
D/wifi    (  842): array field set
I/WifiNative-HAL(  842): interface[0] = wlan0
I/WifiNative-HAL(  842): interface[1] = p2p0
E/CtrlSupplicant( 1806): Succeed to open control connection
E/CtrlSupplicant( 1806): Succeed to open monitor connection
D/WfdsMonitor( 1806): Supplicant connection established
D/WiFiOffLoadUpdatePriority( 5559): remove : truetruetrue
D/WfdsService( 1806): Connected to the supplicant for wfds
D/wifi    (  842): setting scan oui 0x9c87e238
D/WifiHAL (  842): Sending mac address OUI
E/WifiHAL (  842): failed to set scanning mac OUI; result = -95
D/WifiStateMachine(  842): Setting OUI to DA-A1-19
I/WifiNative-HAL(  842): startHal
D/wifi    (  842): setting scan oui 0x9c87e238
D/WifiHAL (  842): Sending mac address OUI
E/WifiHAL (  842): failed to set scanning mac OUI; result = -95
I/WifiNative-HAL(  842): Waiting for HAL events mWifiHalHandle=-1334122944
D/wifi    (  842): waitForHalEvents called, vm = 0xb487c280, obj = 0x90170a, env = 0xaaf06ef0
E/wifi    (  842): getStaticLongField sWifiHalHandle 0x97c07b2c
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 20:29:36.882 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20(  842): hidePasspointNotification off =false
,W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  842): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiScanningService(  842): SCAN_AVAILABLE : 3
D/LGWifiP2pService(  842): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  842): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  842): startHal
D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/wifi    (  842): getting scan capabilities on interface[0] = 0x9c87e238
D/WifiHAL (  842): Creating message to get scan capablities; iface = 24
D/wifi    (  842): failed to get capabilities : -95
D/CommandListener(  274): Setting iface cfg
E/WifiScanningService(  842): could not get scan capabilities
D/CommandListener(  274): Trying to bring up p2p0
D/WifiMonitor(  842): startMonitoring(p2p0) with mConnected = true
D/RttService(  842): SCAN_AVAILABLE : 3
D/LGWifiP2pService(  842): P2pEnablingState
D/LGWifiP2pService(  842): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  842): P2p socket connection successful
D/LGWifiP2pService(  842): P2pEnabledState
I/WifiServerServiceExt(  842): set CMD_ADD_DEFAULT_PROFILE
D/RttService(  842): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  842): [LGE_P2P] initializeP2pSettings() check postfix
D/LGWifiP2pService(  842): before postfix = G3s-1
D/WifiServerServiceExt(  842): postfix byte check : 5
D/LGWifiP2pService(  842): after postfix = G3s-1
I/WifiServerServiceExt(  842): setWifiDualbandAPConnection band : 1
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
E/wpa_supplicant( 5547): nWIFIDualbandAPConnection: 1
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/WifiServerServiceExt(  842): set CMD_DISCONNECT_RSSI_LVL : -100
E/wpa_supplicant( 5547): disconnect_rssi_lvl: -100
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
I/WifiServerServiceExt(  842): set CMD_SET_FRAMEWORK_AUTO_JOIN 0
I/bt_hwcfg( 1989): bt vendor lib: set UART baud 115200
E/wpa_supplicant( 5547): wpa_supplicant_ctrl_iface_set_framework_auto_join: enable : 0
D/bt_hwcfg( 1989): Settlement delay -- 100 ms
I/bt_hwcfg( 1989): Setting fw settlement delay to 100 
D/WifiNative-HAL(  842): p2pGetDeviceAddress
D/WifiNative-HAL(  842): p2pGetDeviceAddress returning a2:39:f7:70:12:80
,D/LGWifiP2pService(  842): DeviceAddress: a2:39:f7:70:12:80
I/WifiServerServiceExt(  842): set CMD_UPDATE_DEFAULT_PROFILE
D/WfdsService( 1806): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
D/WfdsService( 1806): Update P2p Interface State: 3
,I/art     (  842): Explicit concurrent mark sweep GC freed 26752(1393KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 22MB/34MB, paused 8.826ms total 280.962ms
,D/LGWifiP2pService(  842): sending p2p persistent groups changed broadcast
D/LGWifiP2pService(  842): sending p2p connection changed broadcast
D/WfdsService( 1806): WifiP2pState is changed : true
D/LGWifiP2pService(  842): InactiveState
D/LGWifiP2pService(  842): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  842): P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  842): DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1806): Receive the WFDS_ENABLE Method
D/WfdsService( 1806): Set the WFDS Monitor: true
D/WfdsService( 1806): Connected to the supplicant for wfds
D/WfdsJNI ( 1806): doCommand: WFDS_SET TRUE
D/LGWifiP2pService(  842): InactiveState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  842): P2pEnabledState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  842): DefaultState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.p2p.STATE_CHANGED at null
D/WfdsService( 1806): WIFI_P2P_CONNECTION_CHANGED_ACTION
,E/WifiServerServiceExt(  842): No p2p device connected
D/LGWifiP2pService(  842): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  842): P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  842): DefaultState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1806): isConnected: false
D/WfdsService( 1806): GroupInfoAvailable: mGroupInfo is null
D/LGWifiP2pService(  842): InactiveState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  842): P2pEnabledState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  842): DefaultState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 5547): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,I/wpa_supplicant( 5547): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
I/wpa_supplicant( 5547): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WfdsJNI ( 1806): doCommand: WFDS_GET_MAC_ADDRESS
W/ResourcesManager( 5621): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/wpa_supplicant( 5547): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
,D/WfdsJNI ( 1806): doCommand: WFDS_CLEAR_PD_INFO
,I/wpa_supplicant( 5547): WFDS: wfds_supplicant_wfds_cmd: cmd = CLEAR_PD_INFO
D/WfdsJNI ( 1806): wfds_send_command: [WFDS_CLEAR_PD_INFO] failed
D/WfdsJNI ( 1806): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
D/WfdsService( 1806): selectPreferredScanChannel [6]
D/WfdsService( 1806): STATE : WfdsEnabledState - enter: this device mac a2:39:f7:70:12:80
W/WfdsService( 1806): DefaultState - msg [9441285] is not handled
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc45
,D/bt_hwcfg( 1989): hw_config_cback state=2
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 20:29:37.017 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc18
D/LGBluetoothProfileConnectionReceiver_EasySetting( 5621): [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information EasySettings
D/bt_hwcfg( 1989): hw_config_cback state=7
I/bt_hwcfg( 1989): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 1989): Setting local bd addr to F8:95:C7:87:85:54
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  842): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 5547): wlan0: Associated with c0:ff:d4:d3:aa:48
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
,D/AuthorizationBluetoothService( 1734): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/LocSvc_java(  842): onReceive
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  842): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 20:29:37.036 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  842): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/bt_hwcfg( 1989): hw_config_cback opcode:0xfc01
D/bt_hwcfg( 1989): hw_config_cback state=8
I/bt_hwcfg( 1989): vendor lib fwcfg completed
I/bt-btif ( 1989): HC preload_cb 0 [0:SUCCESS 1:FAIL]
I/bt-btu  ( 1989): btu_task received preload complete event
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 20:29:37.041 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
D/GONS    ( 1753): GONS isTestMode: false Country: 
,I/        ( 1989): BTE_InitTraceLevels -- TRC_HCI,2
I/        ( 1989): BTE_InitTraceLevels -- TRC_L2CAP,2
I/        ( 1989): BTE_InitTraceLevels -- TRC_RFCOMM,2
I/        ( 1989): BTE_InitTraceLevels -- TRC_OBEX,2
I/        ( 1989): BTE_InitTraceLevels -- TRC_AVCT,2
I/        ( 1989): BTE_InitTraceLevels -- TRC_AVDT,2
I/        ( 1989): BTE_InitTraceLevels -- TRC_AVRC,2
I/        ( 1989): BTE_InitTraceLevels -- TRC_AVDT_SCB,2
I/        ( 1989): BTE_InitTraceLevels -- TRC_A2D,2
I/        ( 1989): BTE_InitTraceLevels -- TRC_BNEP,2
I/        ( 1989): BTE_InitTraceLevels -- TRC_BTM,2
I/        ( 1989): BTE_InitTraceLevels -- TRC_GAP,2
I/        ( 1989): BTE_InitTraceLevels -- TRC_PAN,2
I/        ( 1989): BTE_InitTraceLevels -- TRC_SAP,2
I/        ( 1989): BTE_InitTraceLevels -- TRC_SDP,2
I/        ( 1989): BTE_InitTraceLevels -- TRC_GATT,2
I/        ( 1989): BTE_InitTraceLevels -- TRC_SMP,2
I/        ( 1989): BTE_InitTraceLevels -- TRC_BTAPP,3
I/        ( 1989): BTE_InitTraceLevels -- TRC_BTIF,3
I/        ( 1989): BTE_InitTraceLevels -- TRC_PROTOCOL,0
D/WiFiOffLoadUpdatePriority( 5559): remove1
,V/WiFiOffLoadSharedPrefsUtils( 5559): save remove
D/WifiServerServiceExt(  842): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  842): setSupplicantStateSCANNING
D/WifiServerServiceExt(  842): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  842): setSupplicantStateASSOCIATING
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  842): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
D/WiFiOffLoadBroadcast( 5559): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 5559): S: false, R: false
I/wpa_supplicant( 5547): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 5547): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 20:29:37.097 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 20:29:37.102 DNS addrs= 0.0.0.0, 0.0.0.0, 
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  842): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt(  842): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  842): setSupplicantStateASSOCIATED
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
I/WifiServiceExtension(  842): setVHTCapabilityType  : false
I/WifiServerServiceExt(  842): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  842): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,I/WifiServiceExtension(  842): setSecurityType  : 2
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 20:29:37.137 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  842): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 20:29:37.143 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  842): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
,D/ConnectivityService(  842): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  842): Got NetworkAgent Messenger
D/ConnectivityService(  842): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  842): NetworkAgent connected
D/WifiExtManager(  842): WifiExtManager service = com.lge.wifi.impl.IWifiExtManager$Stub$Proxy@8f582d2
D/WifiExtManager(  842): WifiExtManager service = com.lge.wifi.impl.IWifiExtManager$Stub$Proxy@2a2d095d
,D/WifiServiceExtension( 1806): isInternetCheckAvailable return false
E/WifiConfigStore(  842): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  842): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 9
,D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  274): Setting iface cfg
E/WifiStateMachine(  842): Start Dhcp Watchdog 1
D/DhcpStateMachine(  842): StoppedState
D/DhcpStateMachine(  842): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  842): WaitBeforeStartState
D/WifiServerServiceExt(  842): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  842): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WiFiOffLoadUpdatePriority( 5559): saved SSID: "NG700"
D/WifiServerServiceExt(  842): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  842): setSupplicantStateGROUP_HANDSHAKE
D/WiFiOffLoadUpdatePriority( 5559): connected SSID: null
,E/bt-btif ( 1989): bta_dm_ctrl_features_rd_cmpl_cback Ctrl BLE feature read failed: status :1
D/WiFiOffLoadUpdatePriority( 5559): private wpa: "NG700" 300
I/GKI_LINUX( 1989): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 1989): warning : media task started media_task_refcnt 1 
D/WifiServiceImplEx(  842): addOrUpdateNetwork pid=5559, uid=1000, packageName=android.uid.system:1000
D/BT_PROF_AUDIO( 1989): created moving average (N=100)
D/BT_PROF_AUDIO( 1989): reset rate average
W/bt-btif ( 1989): overflow 0, enter 0, exit 0
W/bt-smp  ( 1989): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1989): Plain text(LSB ~ MSB) = 10 27 42 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 1989): Encrypted text(LSB ~ MSB) = f4 8a 8a aa 67 55 47 0e 1e 30 68 33 46 31 33 0a 
W/bt-btm  ( 1989): Stopping oneshot timer
E/addOrUpdateNetwork(  842):  uid = 1000 SSID "NG700" nid=0
E/bt-btif ( 1989): Calling BTA_HhEnable
E/bt-btif ( 1989): btif_storage_get_adapter_property service_mask:0x1201c8
I/bt-btif ( 1989): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 1989): Address is:F8:95:C7:87:85:54
I/ActivityManager(  842): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=5651 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/BluetoothAdapterProperties( 1989): Name is: G3s-1
V/AlarmManager(  842): RTC_WAKEUP set : Alarm{307263d0 type 0 when 1454527777217 com.android.vending} when 1454527777217
D/BluetoothManagerService(  842): Bluetooth Adapter name changed to G3s-1
D/BluetoothManagerService(  842): Stored Bluetooth name: G3s-1
V/BluetoothOppNotification( 1989): new notify threadi!
V/BluetoothOppNotification( 1989): send delay message
D/ConnectivityService(  842): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
I/QCNEJ   ( 1842): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
D/BluetoothAdapterProperties( 1989): Scan Mode:20
D/BluetoothAdapterProperties( 1989): Discoverable Timeout:120
E/bt-btif ( 1989): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 1989): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
E/bt-btif ( 1989): btif_sock_init: !radio_req && !rfc_init
I/bt-btif ( 1989): BTA_JvEnable
E/bt-btif ( 1989): btsock_vendor_hci_init: !vhci_init
,D/bt-btif ( 1989): btsock_ctrl_hci_init(L191): poll handle:6
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-64 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 20:29:37.278 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
D/bt-btif ( 1989): init_hci_slots(L136): in
D/IOP_DB_BT( 1989): db_open: file /etc/bluetooth/iop_bt.db
D/IOP_DB_BT( 1989): db_open: db_open : handle 2691246044l, read 11046 bytes onto local cache
D/IOP_DB_BT( 1989): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 1989): db_query: result 1
I/        ( 1989): iop_db_open: iop_db_open status 0
E/bt-btif ( 1989): btif_sock_init, radio_req:0, rfc_init:1, vhci_init:1
D/bt-btif ( 1989): btsock_ctrl_hci_init(L191): poll handle:6
I/bt-btif ( 1989): bta_pan_co_init
D/bte_conf( 1989): Device ID record 1 : primary
D/bte_conf( 1989):   vendorId            = 00c4
D/bte_conf( 1989):   vendorIdSource      = 0001
D/bte_conf( 1989):   product             = 13a1
D/bte_conf( 1989):   version             = 1000
D/bte_conf( 1989):   clientExecutableURL = 
D/bte_conf( 1989):   serviceDescription  = 
D/bte_conf( 1989):   documentationURL    = 
D/bte_conf( 1989): bte_load_did_conf no section named DID2.
V/BluetoothOppProvider( 1989): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
I/bt-btif ( 1989): HAL bt_hal_cbacks->adapter_state_changed_cb
E/bt-btif ( 1989): btif_hf_upstreams_evt: wrong handle = 8240 
I/bt-btif ( 1989): HAL bt_op_callbacks->opc_state_cb
D/BluetoothOPPServiceJni( 1989): opc_state_cb(L140):  opc_state_cb state:0
D/BluetoothAdapterState( 1989): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 1989): ScanMode =  20
D/BluetoothAdapterProperties( 1989): State =  11
D/BluetoothAdapterProperties( 1989): mDiscoverableTimeout = 120
D/BluetoothAdapterProperties( 1989): Setting state to 12
I/BluetoothAdapterState( 1989): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService(404065501)( 1989): updateAdapterState() - Broadcasting state to 1 receivers.
D/OppService( 1989): onOpcStateChange()
I/bt-btif ( 1989): HAL bt_op_callbacks->ops_state_cb
D/BluetoothOPPServiceJni( 1989): ops_state_cb(L223):  ops_state_cb state:0
D/BluetoothManagerService(  842): Message: 60
D/BluetoothManagerService(  842): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/OppService( 1989): Recieved MESSAGE_OPC_ENABLE
D/BluetoothManagerService(  842): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothHeadset( 1753): onBluetoothStateChange: up=true
D/LGBluetoothFeatureConfig( 1989): isPrivacyLogsEnabled : true
I/BluetoothAdapterState( 1989): Entering On State
I/BluetoothAdapterState( 1989): Entering On State from state = 11
D/OppService( 1989): onOpsStateChange() :0
I/bt-btif ( 1989): HAL bt_fts_callbacks->operation_cmpl_cb
D/BluetoothFTPServiceJni( 1989): operation_cmpl_callback(L192):  oper:3 status:0
I/BluetoothFTPService( 1989): onFtpServerEnabled: /storage
D/BluetoothPanServiceJni( 1989): control_state_callback(L61): state:0, local_role:3, ifname:bt-,pan
I/bt-btif ( 1989): HAL bt_hal_cbacks->adapter_properties_cb
D/OppService( 1989): Recieved MESSAGE_OPS_ENABLE
,D/BluetoothAdapterService(404065501)( 1989): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2947ff9b
D/BluetoothAdapterService(404065501)( 1989): isQuetModeEnabled() - Enabled = false
D/BluetoothAdapterService(404065501)( 1989): autoConnect() - Initiate auto connection on BT on...
D/BluetoothAdapterService( 1989): [BTUI] autoConnect() : not allowed
D/BluetoothHeadset( 1753): onBluetoothStateChange: up=true
D/BluetoothAdapterProperties( 1989): Scan Mode:21
I/bt-btif ( 1989): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 1989): Discoverable Timeout:120
D/LGBluetoothServiceAdapter( 1989): [BTUI] OnState
D/LGBluetoothServiceAdapter( 1989): [BTUI]         global_name: G3s-1
D/LGBluetoothServiceAdapter( 1989): [BTUI]         local_name: G3s-1
D/BluetoothAdapterService(404065501)( 1989): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2947ff9b
D/BluetoothAdapterService(404065501)( 1989): isQuetModeEnabled() - Enabled = false
D/BluetoothAdapterService(404065501)( 1989): autoConnect() - Initiate auto connection on BT on...
D/BluetoothAdapterService( 1989): [BTUI] autoConnect() : not allowed
V/BluetoothOppProvider( 1989): created cursor android.database.sqlite.SQLiteCursor@645ca5e on behalf of 
D/BluetoothA2dp( 1989): onBluetoothStateChange: up=true
D/BluetoothHeadset(  842): onBluetoothStateChange: up=true
V/BluetoothOppNotification( 1989): mUpdateCompleteNotification = true
D/BluetoothA2dp(  842): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1753): onBluetoothStateChange: up=true
V/BluetoothOppProvider( 1989): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
E/BluetoothManagerService(  842): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService(  842): Bluetooth State Change Intent: 11 -> 12
V/BluetoothOppProvider( 1989): created cursor android.database.sqlite.SQLiteCursor@1213fe3f on behalf of 
D/BluetoothManagerService(  842): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  842): Message: 40
D/BluetoothManagerService(  842): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
V/BluetoothOppNotification( 1989): outbound: succ-0  fail-0
D/LGBluetoothAPIService( 1806): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/NotificationManager( 1989): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
D/BluetoothAdapterService(404065501)( 1989): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2947ff9b
V/BluetoothOppNotification( 1989): outbound notification was removed.
V/BluetoothOppProvider( 1989): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1989): created cursor android.database.sqlite.SQLiteCursor@2db4a30c on behalf of 
,D/LGBluetoothAPIService( 1806): Message: 1
V/BluetoothOppNotification( 1989): inbound: succ-0  fail-0
D/bt_h4   ( 1989): vendor lib postload completed
D/LGBluetoothAPIService( 1806): MESSAGE_BOOT_COMPLETED
D/BluetoothAdapterService(404065501)( 1989): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2947ff9b
I/BluetoothMapService( 1989): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 1989): STATE_ON
I/LGBluetoothAPIService( 1806): [BTUI] LGBluetoothAPIService Binding Success
D/BluetoothAdapterService(404065501)( 1989): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2947ff9b
,I/[SystemUI]QuickSettingsHandler( 1376): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
,I/[SystemUI]BluetoothHandler( 1376): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
D/BluetoothAdapterService( 1989): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@18158cdd
V/BluetoothPbapService( 1989): Pbap Service onCreate
V/BluetoothPbapService( 1989): Starting PBAP service
D/BluetoothAdapterService(404065501)( 1989): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2947ff9b
D/LGBluetoothPbapAdapter( 1989): [BTUI] getInstance : create
V/BluetoothMapService( 1989): Handler(): got msg=1
D/BluetoothMapMasInstance( 1989): Map Service startRfcommSocketListener
V/BluetoothPbapService( 1989): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 1989): state: 12
,D/LGBluetoothAPIServer( 1989): [BTUI] onCreate()
D/LGBluetoothAPIServer( 1989): [BTUI] onBind()
D/LGBluetoothAPIService( 1806): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1806): Message: 100
D/LGBluetoothAPIService( 1806): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
I/NotificationManager( 1989): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
D/BluetoothMapMasInstance( 1989): MAS initSocket()
D/BluetoothMapMasInstance( 1989):   masId = 00
D/BluetoothMapMasInstance( 1989):   msgTypes = 0e
D/BluetoothMapMasInstance( 1989):   masName = SMS/MMS
D/BluetoothMapMasInstance( 1989):   SDP string = 000eSMS/MMS
V/BluetoothPbapService( 1989): Handler(): got msg=1
D/BluetoothManagerService(  842): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothPbapService( 1989): Pbap Service startRfcommSocketListener
V/BluetoothOppNotification( 1989): inbound notification was removed.
V/BluetoothOppProvider( 1989): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
E/WifiStateMachine(  842): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
D/LGWifiP2pService(  842): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@380de1da target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  842): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@380de1da target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  842): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/DhcpStateMachine(  842): Current State is mWaitBeforeStartState.
,V/BluetoothPbapService( 1989): Pbap Service initSocket
D/BluetoothManagerService(  842): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/DhcpStateMachine(  842): DHCP Start wake lock is acquired.
W/BluetoothAdapter( 1989): getBluetoothService() called with no BluetoothManagerCallback
W/BluetoothAdapter( 1989): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1989): BTA_JvCreateRecordByUser
V/LgDhcpStateMachineHelper(  842): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper(  842): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
I/bt-btif ( 1989): BTA_JvRfcommStartServer
D/LGBluetoothServiceAdapter( 1989): [BTUI] createSocketChannel FD=83 mFd=0
V/BluetoothPbapService( 1989): Succeed to create listening socket 
V/BluetoothPbapService( 1989): Accepting socket connection...
V/BluetoothOppProvider( 1989): created cursor android.database.sqlite.SQLiteCursor@3c543f5b on behalf of 
I/bt-btif ( 1989): BTA_JvCreateRecordByUser
I/bt-btif ( 1989): BTA_JvRfcommStartServer
D/LGBluetoothServiceAdapter( 1989): [BTUI] createSocketChannel FD=86 mFd=83
V/BluetoothMapMasInstance( 1989): Succeed to create listening socket 
D/BluetoothMapMasInstance( 1989): Accepting socket connection...
D/WifiServerServiceExt(  842): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  842): setSupplicantStateCOMPLETED
E/WifiConfigStore(  842):  key="NG700"WPA_PSK netId=0 uid=0/1000
D/WifiServerServiceExt(  842): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  842): setSupplicantStateCOMPLETED
,E/WifiConfigStore(  842): Setting BSSID for "NG700"WPA_PSK to any
,D/WiFiOffLoadUpdatePriority( 5559):  ssid "NG700" prio 300
,D/WiFiOffLoadUpdatePriority( 5559): configuration updated: 0
I/WifiServerServiceExt(  842): set CMD_UPDATE_DEFAULT_PROFILE
D/WiFiOffLoadUpdatePriority( 5559): configuration saved: true
,D/PCSuite ( 5601): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/ContextImpl( 5559): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,I/ActivityManager(  842): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=5676 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,V/BluetoothPbapReceiver( 1989): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1989): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1989): ***********state = 12
,D/BluetoothAdapterService(404065501)( 1989): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2947ff9b
,D/LocalBluetoothProfileManager( 5559): Adding local A2DP profile
D/BluetoothManagerService(  842): Message: 30
D/LocalBluetoothProfileManager( 5559): Adding local HEADSET profile
,D/BluetoothManagerService(  842): Message: 30
D/DhcpStateMachine(  842): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper(  842): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  842): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/BluetoothManagerService(  842): Message: 30
,I/dhcpcd  ( 5694): version 5.5.6 starting
E/dhcpcd  ( 5694): get_duid: Read-only file system
D/BluetoothManagerService(  842): Message: 30
D/LocalBluetoothProfileManager( 5559): Adding local MAP profile
,D/BluetoothMap( 5559): Create BluetoothMap proxy object
D/BluetoothManagerService(  842): Message: 30
D/BluetoothManagerService(  842): Message: 30
D/LocalBluetoothProfileManager( 5559): LocalBluetoothProfileManager construction complete
V/BluetoothPbapService( 1989): Pbap Service onBind
D/LGBluetoothUserBindClient( 5559): [BTUI] initUserBindClient
,W/ContextImpl( 5559): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 5559): finishStartingService: stopping service
,D/BluetoothA2dp( 5559): Proxy object connected
D/A2dpProfile( 5559): Bluetooth service connected
D/BluetoothAdapterService(404065501)( 1989): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2947ff9b
D/BluetoothHeadset( 5559): Proxy object connected
D/HeadsetProfile( 5559): Bluetooth service connected
D/BluetoothAdapterService(404065501)( 1989): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2947ff9b
D/BluetoothInputDevice( 5559): Proxy object connected
D/HidProfile( 5559): Bluetooth service connected
D/BluetoothAdapterService(404065501)( 1989): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2947ff9b
D/BluetoothPan( 5559): BluetoothPAN Proxy object connected
D/PanProfile( 5559): Bluetooth service connected
D/BluetoothAdapterService(404065501)( 1989): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2947ff9b
,D/BluetoothMap( 5559): Proxy object connected
D/MapProfile( 5559): Bluetooth service connected
D/BluetoothMap( 5559): getConnectedDevices()
I/dhcpcd  ( 5694): wlan0: rebinding lease of 192.168.1.134
D/BluetoothAdapterService(404065501)( 1989): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2947ff9b
V/BluetoothMapService( 1989): getConnectedDevices()
D/BluetoothPbap( 5559): Proxy object connected
D/PbapServerProfile( 5559): Bluetooth service connected
D/LGBluetoothUserBindClient( 5559): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 5559): onReceive
,D/LGBluetoothFeatureConfig( 5559): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 5559): [BTUI] FileNotFound: readProperty
V/BluetoothOppReceiver( 1989): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
V/BluetoothOppManager( 1989): restoreApplicationData! falsefalsenullnull
,D/Finsky  ( 5651): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
V/BluetoothSapReceiver( 1989): [BTUI] checkServiceStart
D/LGBluetoothStateChangeReceiver( 1989): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
D/AuthorizationBluetoothService( 1734): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/LGDMClient( 5676): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 5676): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 5676): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 5676): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
V/WiFiOffLoadBroadcast( 5559): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LGDMClient( 5676): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 5676): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/WiFiOffLoadBroadcast( 5559): MCCMNC not supported: null
,D/LGDMClient( 5676): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/PCSuite ( 5601): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 5601): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 5601): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/ActivityManager(  842): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=5724 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 342us total 22.954ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 310us total 20.874ms
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 20.946ms
D/Finsky  ( 5651): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5651): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5651): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5651): com.android.vending: cancel(-1050172287) by com.android.vending
,I/ActivityManager(  842): Process com.google.android.gms (pid 4937) has died
,W/ActivityManager(  842): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 1000ms
V/DownloadManager( 3126): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,D/Ads     ( 5651): Skipping gmscore version check
V/DownloadManager( 3126): created cursor android.database.sqlite.SQLiteCursor@77a0114 on behalf of 5651
D/Finsky  ( 5651): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5651): [1] Libraries$2.run: Finished loading 1 libraries.
V/[BNRBootReceiver]( 5724): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/BNRAndroBeam( 5724): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
D/Finsky  ( 5651): [1] GmsCoreHelper.cleanupNlp: result=false type=4
V/[BNRBootReceiver]( 5724): Boot Receiver Return
W/MainApplication( 5724): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,I/ActivityManager(  842): Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=5755 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
V/WiFiOffLoadBroadcast( 5559): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5559): MCCMNC not supported: null
D/Finsky  ( 5651): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/WiFiOffLoadBroadcast( 5559): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 5559): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 5559): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 5559): MCCMNC not supported: null
,W/ResourcesManager( 5755): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5755): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/WiFiOffLoadBroadcast( 5559): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5559): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5559): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5559): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5559): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5559): MCCMNC not supported: null
I/MultiDex( 5755): VM with version 2.1.0 has multidex support
I/MultiDex( 5755): install
I/MultiDex( 5755): VM has multidex support, MultiDex support library is disabled.
,V/WiFiOffLoadBroadcast( 5559): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 5559): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5559): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WiFiOffLoadBroadcast( 5559): MCCMNC not supported: null
D/ConnectivityService(  842): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
I/ActivityManager(  842): Killing 4811:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  842): failed to open /acct/uid_10086/pid_4811/cgroup.procs: No such file or directory
,I/Netd    (  274): M: Get netlink event, ifname: p2p0 action: 6
D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Finsky  ( 5651): [670] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5651): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  842): Killing 5298:com.google.android.gm/u0a53 (adj 15): empty #11
I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,W/libprocessgroup(  842): failed to open /acct/uid_10053/pid_5298/cgroup.procs: No such file or directory
,V/AlarmManager(  842): ELAPSED_WAKEUP set : Alarm{2fda118c type 2 when 88029 com.android.providers.calendar} when 88029
D/CalendarProviderBroadcastReceiver( 5474): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 5474): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 5474): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 5474): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 5474): [getOrCreateCalendarAlarmManager]
V/JNIHelp ( 5755): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/CalendarProvider2( 5474): [IntentService] Release Lock
D/CalendarProvider2( 5474): CalendarProviderIntentService.onDestroy()
W/ActivityThread( 5755): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5755): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@28b2c799: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5755): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5755): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5755): com.google.android.gms: cancel(39789) by com.google.android.gms
I/dhcpcd  ( 5694): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/dhcpcd  ( 5694): wlan0: leased 192.168.1.134 for 86400 seconds
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  842): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,I/GAv4-SVC( 5755): Google Analytics 8.4.89 is starting up.
,V/AudioFlinger(  278): thread 0xb5735000 type 0 TID 1301 going to sleep
,V/AudioFlinger(  278): thread 0xb56eb000 type 0 TID 1299 going to sleep
V/AudioFlinger(  278): thread 0xb5651000 type 0 TID 1298 going to sleep
I/ActivityManager(  842): Killing 5621:com.lge.settings.easy/1000 (adj 15): empty #11
,D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  842): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  842): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  842): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  842): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  842): Add DhcpResults: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine(  842): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  842): bShouldSendDhcpAction Result: true
D/DhcpStateMachine(  842): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  842): RunningState
D/LGWifiP2pService(  842): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  842): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  842): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  842): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/ConnectivityService(  842): ignoring duplicate network state non-change
,D/NativeLibraryUtils( 5755): Install completed successfully. count=14 extracted=0
,I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  842): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,W/libprocessgroup(  842): failed to open /acct/uid_1000/pid_5621/cgroup.procs: No such file or directory
D/WifiServiceExtension( 1806): isInternetCheckAvailable return false
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-64 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-03 20:29:39.047 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
D/ConnectivityService(  842): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  842): Adding iface wlan0 to network 100
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,D/WifiServiceExtension( 1806): isInternetCheckAvailable return false
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  842): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-64 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-03 20:29:39.06 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
D/WearableService( 1734): callingUid 10006, callindPid: 1734
D/WifiHS20(  842): [PASSPOINT] passpointNotification: hs20AP list is checked
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine(  842): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  842): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  842): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-64 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-03 20:29:39.076 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  842): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-64 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-03 20:29:39.084 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
E/ConnectivityService(  842): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  842): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  842): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/MDM     ( 1734): [105] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/ConnectivityService(  842): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  842): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  842): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService(  842): Setting Dns servers for network 100 to [/192.168.1.1]
D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = true, mWifiLevel = 2
D/Nat464Xlat(  842): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  842): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  842): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  842): rematching NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  842): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  842): Connected
D/ConnectivityService(  842):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  842): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  842):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  842):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  842):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  842):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  842): currentScore = 0, newScore = 20
D/ConnectivityService(  842):    accepting network in place of null
D/ConnectivityService(  842): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  842): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
D/WIFI    (  842): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  842):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1753): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1753):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
E/ConnectivityService(  842): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  842): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
D/ConnectivityService(  842): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/[SystemUI]StatusBar.NetworkController( 1376): mWifiConnected = true, mWifiLevel = 2
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/ConnectivityService(  842): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at null
D/CSLegacyTypeTracker(  842): [e] list.add(nai) empty : false size: 1
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1376): Remote
D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
D/ConnectivityService(  842): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/Tethering(  842): MasterInitialState.processMessage what=3
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=0
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
W/QCNEJ   ( 1842): |CORE| No family connected
D/ConnectivityService(  842): validation of new default Network = false
I/QCNEJ   ( 1842): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/ConnectivityService(  842): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  842): enableDataServiceNotify 
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/DSQN    (  842): start dsqn bin
D/DSQN    (  842): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/QCNEJ   ( 1842): |CORE| sendDefaultNwMsg: default = 1
D/LocationInitializer( 5755): Restart initialization of location
,D/AuthorizationBluetoothService( 1734): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  842): [LWD] Start DNSResolver start to wait
V/NetworkPolicy(  842): [LG_RESTRICTED] checkMobilePolicy_type()
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  842): [LWD] wait 500ms before dns check
D/ConnectivityService(  842): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  842):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  842):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/DSQN    ( 5809): DSQN samuel.seo ver 141203
E/DSQN    ( 5809): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5809): created command queue thread
,I/DSQN    ( 5809): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5809): Interface wlan0 netmask 255.255.255.0 0xc0a80186
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ConnectivityService(  842): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
D/ConnectivityManager.CallbackHandler( 1376): CM callback handler got msg 524290
V/WiFiOffLoadBroadcast( 5559): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/TelephonyIcons( 1376): null signal icon name: drawable/stat_sys_signal_null
D/WiFiOffLoadBroadcast( 5559): MCCMNC not supported: null
I/[SystemUI]LGNetworkController( 1376): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
V/WiFiOffLoadBroadcast( 5559): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5559): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5559): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/art     ( 5755): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5755): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/WiFiOffLoadBroadcast( 5559): MCCMNC not supported: null
I/PCSuite ( 5601): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 5601): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 5559): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5559): MCCMNC not supported: null
I/PCSuite ( 5601): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 5601): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
I/art     ( 5755): CheckpointMarkThreadRoots callback created = 0xb042d3d0
,I/art     ( 5755): CheckpointMarkThreadRoots callback created = 0xb042d3b0
,I/art     ( 5755): Background partial concurrent mark sweep GC freed 4972(541KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 10MB/17MB, paused 5.357ms total 77.037ms
,I/ActivityManager(  842): Process com.lge.bnr (pid 5724) has died
,W/GCoreFlp( 1734): No location to return for getLastLocation()
W/FusedLocationProvider( 1734): location=null
W/IcingInternalCorpora( 5755): getNumBytesRead when not calculated.
,D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  842): [LWD] DNSResolver start dns
,D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=100; mark=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=983140
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out(  842): propertyValue:false
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  842): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  842): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/DSQN    ( 5809): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5809): restart monitoring
,I/DSQN    ( 5809): dsqn report finish
D/LGDataListener(  274): argv[0]=dsqncommand
D/LGDataListener(  274): argv[1]=wlan0
D/LGDataListener(  274): argv[2]=1
D/LGDataListener(  274): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  842): DSQM DsqnNotification wlan0  1
D/DSQN    (  842): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  842): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Feb 2016 19:29:39 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454527779772], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454527779758]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  842): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1806): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  842): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  842): Validated
D/ConnectivityService(  842): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  842): rematching NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  842):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  842):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  842):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  842): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  842): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  842):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  842):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  842): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  842): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  842): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  842): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  842):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1753): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1753):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WifiDataContinuityService(  842): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
I/WifiServerServiceExt(  842): set CMD_CAPTIVE_CHECK_COMPLETED
D/ConnectivityManager.CallbackHandler( 1376): CM callback handler got msg 524290
D/TelephonyIcons( 1376): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1376): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/AlertService( 5508): Beginning updateAlertNotification
,D/AlertService( 5508): No fired or scheduled alerts
,I/NotificationManager( 5508): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 5508): com.android.calendar: cancel(1) by com.android.calendar
,I/NotificationManager( 5508): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 5508): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 5508): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5508): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 5508): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 5508): com.android.calendar: cancel(7) by com.android.calendar
,I/NotificationManager( 5508): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 5508): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 5508): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 5508): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 5508): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 5508): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 5508): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 5508): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 5508): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 5508): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5508): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 5508): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 5508): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 5508): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,I/QCNEJ   ( 1842): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-03 20:29:40.277 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/AlarmScheduler( 5508): No events found starting within 1 week.
,I/NotificationManager( 1938): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,V/WifiInternetCheck(  842): Single check msg out of sync, ignoring.
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/ConnectivityService(  842): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  842): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1376): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,I/ActivityManager(  842): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5859 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/LocSvc_java(  842): onReceive
D/LocSvc_java(  842): got connectivity action
,D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/LocSvc_java(  842): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  842): Sending msg: 4 arg1:1 arg2:1
D/Finsky  ( 5651): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  842): RTC_WAKEUP set : Alarm{256004c1 type 0 when 1454527782196 com.android.vending} when 1454527782196
D/LocSvc_java(  842): getAGpsConnectionInfo connType - 4
D/NetworkChangeNotifierAutoDetect( 1938): Network connectivity changed, type is: 2
,D/LocSvc_java(  842): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  842): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  842): Sending msg: 5 arg1:0 arg2:1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out(  842): propertyValue:false
I/System.out(  842): propertyValue:false
D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/LocSvc_java(  842): NTP server returned: 1454527782028 (Wed Feb 03 20:29:42 GMT+01:00 2016) reference: 91800 certainty: 13 system time offset: -258
,D/LocSvc_java(  842): Sending msg: 10 arg1:0 arg2:1
D/AlarmManagerService(  842): Setting time of day to sec=1454527782
,W/AlarmManagerService(  842): Unable to set rtc to 1454527782: Invalid argument
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/[SystemUI]Clock( 1376): onReceive = android.intent.action.TIME_SET
,I/CalendarProvider2( 5474): onReceive() android.intent.action.TIME_SET
D/CalendarProvider2( 5474): Scheduling check of next Alarm
D/WeatherService( 2734): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 20:29:42
D/WeatherService( 2734): 2 : requestRefreshAppWidget, isUpdateStart : false
I/LgeClockWidgetControlView( 1376): time changed, timezoneChanged : false
D/UpdateThreadPoolManager( 2734): 2 : This is isUpdating : false
,D/WeatherService( 2734): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2734): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2734): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2734): 2 : Fixed theme : optimus
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
,D/WeatherReflect( 2734): 2 : Map key string is -2
I/ActivityManager(  842): Start proc com.lge.email for broadcast com.lge.email/.receiver.UpdateScheduleReceiver: pid=5893 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
W/ActivityManager(  842): getTasks: caller 10024 is using old GET_TASKS but privileged; allowing
,D/lim     ( 2734): 2 : time = 20:29
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WeatherReflect( 2734): Model Name : LG-D722
D/WeatherTheme( 2734): 2 : exactly same view!
D/WeatherTheme( 2734): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
D/WeatherService( 2734): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 20:29:42
,I/ActivityManager(  842): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=5910 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/[LGHome]LGDateChangeReceiver( 1880): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=3 currentDate=-1 dayofweek=4 currentDayOfWeek=-1
I/[LGHome]LGCalendarIcon( 1880): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 3
,I/[LGHome]LGCalendarIcon( 1880): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 3
,I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/GpsLocationProvider(  842): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/art     (  842): Explicit concurrent mark sweep GC freed 69680(3MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 3.763ms total 214.260ms
,W/ResourcesManager( 5910): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5910): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5910): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
E/GpsLocationProvider(  842): No APN found to select.
,W/ResourcesManager( 5893): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5893): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 5893): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/NotificationManager(  842): android: cancelAsUser(2) by android
,I/MusicStore( 5859): Database version: 120
,E/ActivityThread( 5755): Failed to find provider info for com.android.contacts.metadata
,D/LgeGpsConstants(  842): Can't find 'ext_gps.conf'!!
,D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/SyncManager(  842): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 37241, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  842): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 124810, reason: UserStart
I/NotificationManager(  842): android: cancelAsUser(716319171) by android
,I/NotificationManager(  842): android: cancelAsUser(-1816247584) by android
,I/AppConfig( 5910): Total System Memory = 906309632
I/GalleryUtils( 5910): Application Heap = 96 MB
,D/libc-netbsd( 5651): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5651): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/AppConfig( 5910): App Tier : NOT_DEF
D/libc-netbsd( 5651): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5651): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  274): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
,D/SystemHelper( 5910): region [EU], country [EU], operator [OPEN], sub-operator []
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 5651): propertyValue:false
,D/libc-netbsd( 5651): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5651): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out(  842): propertyValue:false
I/LGEmail ( 5893): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5859): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/LGEmail ( 5893): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,E/Auth.Api.Credentials( 5755): [CredentialSyncAdapter] Unknown sync event.
,I/NotificationManager(  842): android: cancelAsUser(-1597574061) by android
I/NotificationManager(  842): android: cancelAsUser(-591465577) by android
,D/libc-netbsd( 5651): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5651): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  842): Process com.android.calendar (pid 5508) has died
,I/NotificationManager(  842): android: cancelAsUser(-1816247584) by android
,I/NotificationManager(  842): android: cancelAsUser(-1597574061) by android
D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
,D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out(  842): propertyValue:false
,I/ActivityManager(  842): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=5958 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out(  842): propertyValue:false
E/ConnectivityChangeReceiver( 5755): Ignoring connectivity change
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5859): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5859): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,D/ConnectivityService(  842): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  842): dumpNetworkRequest
V/WifiInternetCheck(  842): isHttpConnectionAvailable - We got a valid response : 204
D/ConnectivityService(  842):     NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/ConnectivityService(  842):     Requests:
D/ConnectivityService(  842):         NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  842):         NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  842):     Lingered:
D/ConnectivityService(  842): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  842): apparently satisfied.  currentScore=60
,D/ConnectivityService(  842): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 5755): CM callback handler got msg 524290
I/ActivityManager(  842): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=5980 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,W/ResourcesManager( 5958): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5859): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5859): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,V/JNIHelp ( 5859): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  842): Process com.lge.lgdmsclient (pid 5676) has died
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  842): android: cancelAsUser(2) by android
,D/ALBootInit( 5980): ====action==>android.intent.action.TIME_SET
D/ALBootInit( 5980): Alarm ALBootInit: TIME_SET
D/Alarms  ( 5980): [setNextAlert] start
,D/Alarms  ( 5980): [setNextAlert] (1)
,D/Alarms  ( 5980):  minTime  = 0
D/Alarms  ( 5980):  -- OK multi -- 0
I/NotificationManager(  842): android: cancelAsUser(-591465577) by android
E/jeny.kim( 5980): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 5980): [setNextAlert]setNextAlert temp_AlarmLinkText + 
,I/CommonUtil( 5980): BUILD Operator: OPEN
D/Alarms  ( 5980): broadcastToWidgetProvider : false
,W/ActivityThread( 5859): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5859): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@33b420c2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5859): Installed default security provider GmsCore_OpenSSL
D/Alarms  ( 5980): Enter formatDayAndTime(final Context context, long timeInMiliSec)
D/AndroidMusic( 5859): GMSCore installation verified
,V/SettingsProvider(  842): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
I/DigitalAppWidgetProvider( 5980): onReceive: android.intent.action.TIME_SET
V/DigitalAppWidgetProvider( 5980): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1aaea187
,V/DigitalAppWidgetProvider( 5980): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1aaea187
I/qtaguid ( 5651): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5651): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5651): untagSocket(41) failed with errno -22
,I/ConfigStore( 5859): Config Database version: 1
D/QuickCoverProvider( 5980): onReceiver
D/Finsky  ( 5651): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/ActivityManager(  842): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=6003 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6003): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     ( 1734): Explicit concurrent mark sweep GC freed 32017(2MB) AllocSpace objects, 29(464KB) LOS objects, 39% free, 13MB/22MB, paused 1.917ms total 140.469ms
,I/ActivityManager(  842): Process com.android.providers.calendar (pid 5474) has died
I/ActivityManager(  842): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6026 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/CalendarApplication( 6003): CalendarApplication.onCreate()
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PreferenceKeysParser( 6003): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6003): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@3cba6bfa, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@25a255ab, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@297ac408, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@373017a1, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@e334dc6, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1aaea187, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@6fc18b4, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@18158cdd, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@22068052, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@949cf23, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@99c0c20, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@23e319d9, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@10684f9e, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@36e03a7f, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@2c85ca4c, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@3b627a95, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@2e85c7aa, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@2947ff9b, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@106b3f38, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@83d2b11, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@550b476, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@239cfa77, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@2d3116e4, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@b38674d, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@290ba202, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@14dcc713, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@325abd50, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@12312b49, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@3d95dc4e, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1442c16f, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@2365e7c, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@11d83305, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@33776f5a, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@764058b, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@33c8e668, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@1f2dfa81, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@9ad2726, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@e0b6f67, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@77a0114, lg_preference_defaultCalendar=com.android.calendar.adaptation.Preferenc,eKey$KeyData@4bebdbd, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@20348fb2, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@fd59b03, lg
,D/GeneralPreferenceUtils( 6003): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6003): [init]
,I/Config  ( 6003): LGCalendar ver.4.40.17
I/Config  ( 6003): start check model
I/Config  ( 6003): start check native_ca
I/Config  ( 6003): Config Operator=OPEN, Country=EU
D/Config  ( 6003): [setDefaultValuesToPref]
D/Config  ( 6003): [parseProfiles]
,D/ProfilesParser( 6003): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6003): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6003): [updateProfiletoCountryInfo]
D/GeneralPreference( 6003): [checkAndMigrateOldPreference]
I/NotificationManager(  842): android: cancelAsUser(2) by android
,E/AgendaWidgetManager( 6003): [updateWidgets] 
,W/ResourcesManager( 6026): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6026): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/art     ( 4869): Explicit concurrent mark sweep GC freed 1796(67KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 6.180ms total 93.682ms
,I/MultiDex( 6026): VM with version 2.1.0 has multidex support
I/MultiDex( 6026): install
I/MultiDex( 6026): VM has multidex support, MultiDex support library is disabled.
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 93945385175; DSPS: 3177154; Offset : -3014904218
I/qtaguid ( 5651): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5651): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5651): untagSocket(41) failed with errno -22
,I/MediaRouter( 5859): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,W/DriveInitializer( 5755): Awaiting to be initialized
W/DriveInitializer( 5755): Background init thread started
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5755): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
V/MusicLeanback( 5859): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
W/art     ( 5958): Attempt to remove local handle scope entry from IRT, ignoring
,I/jxcore-log( 5377): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5377): 
,I/art     (  842): Explicit concurrent mark sweep GC freed 24980(1185KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 2.755ms total 209.558ms
,I/NetworkMonitor( 5859): type=WIFI subType= reason=null isConnected=true
,I/InitNotificationRingtoneService( 6003): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 6003): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
W/HolidayIntentService( 6003): onHandleIntent
D/MonthWidgetProvider( 6003): [onReceive]
D/HolidayDataLoader( 6003): readJsonAsset : holiday.json
D/CalendarWidgetProvider( 6003): [onReceive]
D/CalendarWidgetProvider( 6003): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6003): [onUpdateAndInitCalendarTime]
I/ActivityManager(  842): Process com.android.settings (pid 5559) has died
D/WeekWidgetProvider( 6003): [onReceive]
D/CalendarWidgetProvider( 6003): [onReceive]
D/CalendarWidgetProvider( 6003): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
,D/CalendarTypeController( 6003): [onUpdateAndInitCalendarTime]
W/DriveInitializer( 5755): Background init thread ended
D/WeatherAncestor( 2734): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 20:29:44
,D/UpdateThreadPoolManager( 2734): 2 : This is isUpdating : false
D/Weather_cast( 2734): 2 : set auto-update time : 2/3 23:29
D/WeatherAncestor( 2734): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 20:29:44
,I/AlertUtils( 6003): [getCalendarNotiSoundURIFromCursor] getCount()= 21
D/WeatherService( 2734): 2 : onStartCommand, intent!=null, action: android.intent.action.TIME_SET
,I/AlertUtils( 6003): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6003): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,I/AlertUtils( 6003): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6003): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/ActivityManager(  842): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6076 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
W/ActivityManager(  842): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2734): 2 : Utils getTopActivity com.lge.launcher2 / true
E/HolidayIntentService( 6003): onHandleIntent:holiday data empty
,D/WeatherService( 2734): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2734): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/AlertUtils( 6003): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,I/AlertUtils( 6003): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6003): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
V/JNIHelp ( 6026): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/AlertUtils( 6003): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/NotificationManager( 5755): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/libc-netbsd( 5958): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5958): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
E/BandwidthController(  274): [LG DATA] No such appUid: 10086
D/DnsProxyListener(  274): App 10086 tries DNS query. Accept family:2 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
I/AlertUtils( 6003): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6003): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
,I/AlertUtils( 6003): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/NetworkMonitor( 5859): type=WIFI subType= reason=null isConnected=true
I/AlertUtils( 6003): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/AlertUtils( 6003): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6003): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,I/AlertUtils( 6003): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6003): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 6003): set default noti to content://media/internal/audio/media/38
D/TimeService( 6076): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454527784728
D/        ( 6076): TimeServiceNative: User Time to be set is 1454527784728
D/QC-time-services( 6076): Lib:time_genoff_operation: pargs->base = 2
,D/QC-time-services( 6076): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6076): Lib:time_genoff_operation: pargs->ts_val = 1454527784728
D/QC-time-services( 6076): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  353): Daemon: Connection accepted:time_genoff
D/QC-time-services(  353): Daemon:Received base = 2, unit = 1, operation = 0,value = 1454527784728
D/QC-time-services(  353): Daemon:genoff_opr: Base = 2, val = 1454527784728, operation = 0
D/QC-time-services(  353): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/16/70 23:31:15
,I/GHttpClientFactory( 5859): Using our fixed implementation of GMSCore's GoogleHttpClient
D/QC-time-services(  353): Daemon:Value read from RTC seconds = 14427075000
D/QC-time-services(  353): Daemon:new time 1454527784728 
D/QC-time-services(  353): Daemon: delta 1440100709728 genoff 1440100709728 
D/QC-time-services(  353): Daemon:genoff_persistent_update: Writing genoff = 1440100709728 to memory
D/QC-time-services(  353): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  353): Daemon:time_persistent_memory_opr:Genoff write operation 
I/InitNotificationRingtoneService( 6003): End InitializeAlertRingtoneService.onHandleIntent
I/GoogleURLConnFactory( 5859): Using platform SSLCertificateSocketFactory
,D/QC-time-services(  353): Updating the TOD offset
D/QC-time-services(  353): Daemon:genoff_persistent_update: Writing genoff = 1440100709728 to memory
D/QC-time-services(  353): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  353): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  353): Daemon:Update to modem bit set
D/QC-time-services(  353): Daemon:genoff_send_modem: Sending data to MODEM !
E/QC-time-services( 6076): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  353): Daemon: Base = 2, Value being sent to MODEM = 1124135909728
D/eas_req ( 5893): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,E/QC-time-services(  353): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  353): Daemon: Time-services: Waiting to acceptconnection
W/ActivityThread( 6026): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6026): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2845677b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6026): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 6026): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6026): com.google.android.gms: cancel(39789) by com.google.android.gms
I/ActivityManager(  842): Process com.lge.sync (pid 5601) has died
,I/NotificationManager(  842): android: cancelAsUser(353845882) by android
I/NotificationManager(  842): android: cancelAsUser(-1548111331) by android
,D/ChimeraCfgMgr( 6026): Reading stored module config
,I/ActivityManager(  842): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6108 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/art     ( 5651): CheckpointMarkThreadRoots callback created = 0xb042db90
,I/art     ( 5651): CheckpointMarkThreadRoots callback created = 0xb042db60
I/ActivityManager(  842): Process com.lge.qremote (pid 5143) has died
,D/UEI.SmartControl( 5166): Service.onUnbind: IControl
D/UEI.SmartControl( 5166): Service.onDestroy
I/BackgroundMemoryTrimmer( 1938): Trimming objects from memory, since app is in the background.
,I/HubEmail( 5893): JNI_OnLoad()
I/HubEmail( 5893): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5893): registerNatives()
I/HubEmail( 5893): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5893): registerNativeMethods()
I/HubEmail( 5893): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 5893): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/PhoneApp( 1753): onTrimMemory: 10
I/PhoneApp( 1753): trim memory
I/CheckinService( 5755): Checkin interval check for package: unspecified last checkin: 1454523161139 min interval config: 0 actual interval: 4624030
,D/ChimeraCfgMgr( 6026): Loading module com.google.android.gms.car from APK com.google.android.gms
,D/UEI.SmartControl( 5166): Shutdown IRRCPlayer... 
I/NotificationManager( 5859): com.google.android.music: cancel(1061) by com.google.android.music
,D/ChimeraCfgMgr( 5755): Reading stored module config
W/Settings( 5893): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ChimeraCfgMgr( 5755): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 5755): Loading module APK com.google.android.play.games
W/irrc_jni( 5166): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 5166): ~IrrcClient ++ 
D/irrcClient( 5166): ~IrrcClient -- 
W/irrc_jni( 5166): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 5166): Blaster closed
D/UEI.SmartControl( 5166): Blaster closed
D/UEI.SmartControl( 5166): Shut down QS...
D/UEI.SmartControl( 5166): Stopped file observer...
I/UEI.SmartControl( 5166): QS lib stop result = true
D/UEI.SmartControl( 5166): QS shutdown complete
,D/NativeLibraryUtils( 6026): Install completed successfully. count=14 extracted=0
,I/ActivityManager(  842): Process com.uei.lg.quicksetsdk.lite (pid 5166) has died
,D/LGDMClient( 6108): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6108): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6108): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 6108): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6108): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/ActivityManager(  842): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6139 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/LGDMClient( 6108): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6108): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 26.114ms
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 20.807ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 298us total 21.399ms
,I/LGDMClient( 6108): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NotificationManager(  842): android: cancelAsUser(353845882) by android
,D/CAR.SERVICE( 6026): Connecting to CarCallService...
,W/ContextImpl( 6108): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6108): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6108): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
,D/LGDMClient( 6108): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6108): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6108): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/art     ( 6026): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6026): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  842): Process com.lge.clock (pid 5980) has died
I/art     ( 5958): CheckpointMarkThreadRoots callback created = 0xb050dce0
,I/art     ( 5958): CheckpointMarkThreadRoots callback created = 0xb050dcb0
,I/jxcore-log( 5377): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5377): 
,D/CAR.SERVICE( 6026): com.google.android.projection.gearhead isn't installed.
I/AppUp4:AppBoxCP( 6139): onCreate
,W/AppUp4:DB( 6139):  [AppBoxDatabaseHelper] construct
D/CAR.TEL.Service( 6026): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 6026): Creating a new PhoneAdapter instance
,W/ActivityManager(  842): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6026): setListener: com.google.android.gms.car.dn@364f3086
,W/ActivityManager(  842): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6026): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6026): Starting CarCallService with initial phone null
I/AppUp4:DB( 6139):  setFingerPrint start
I/AppUp4:DB( 6139):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/NotificationManager( 6026): com.google.android.gms: cancel(10436) by com.google.android.gms
I/AppUp4:DB( 6139):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6139):  SDK version = 0
I/AppUp4:DB( 6139):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6139): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 6139): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6139): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6139): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6139): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6139): onReceive
I/AppUp4:CustModeStarterReceiver( 6139): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 6139): Context : android.app.ReceiverRestrictedContext@e334dc6
D/AppUp4:CustFacade( 6139): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6139): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6139): begin check event
I/AppUp4:CustModeStarterReceiver( 6139): Event For GoodConnectivity
I/jxcore-log( 5377): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5377): 
D/AppUp4:CustModeStarterReceiver( 6139): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6139): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6139): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6139): handleAsyncCustNotification do not startCustService
I/jxcore-log( 5377): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 5377): 
,I/LgeMiscReceiver( 3104): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3104): action = android.net.conn.CONNECTIVITY_CHANGE
D/CAR.SERVICE( 6026): Package validated; name: com.android.vending
I/LgeMiscReceiver( 3104): networkInfo.isConnected() = true
D/PhoneState( 3104): setPdpRejectCasuse : false
,I/ActivityManager(  842): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6168 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/jxcore-log( 5377): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 5377): 
,I/NotificationManager( 5651): com.android.vending: cancel(10436) by com.android.vending
V/Finsky  ( 5651): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,I/NotificationManager( 5958): com.google.android.apps.plus: cancel(10436) by com.google.android.apps.plus
I/jxcore-log( 5377): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 5377): 
,I/jxcore-log( 5377): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 5377): 
,I/jxcore-log( 5377): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5377): 
,I/NotificationManager(  842): android: cancelAsUser(2145784878) by android
D/PhoneMonitor( 6168): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6168): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6168): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  842): Killing 5910:com.android.gallery3d/u0a23 (adj 15): empty #11
W/libprocessgroup(  842): failed to open /acct/uid_10023/pid_5910/cgroup.procs: No such file or directory
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/DownloadManager( 3126): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
I/CheckinService( 5755): Checkin interval check for package: unspecified last checkin: 1454523161139 min interval config: 0 actual interval: 4625378
I/NotificationManager(  842): android: cancelAsUser(2) by android
D/PhoneMonitor( 6168): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/DownloadManager( 3126): DownloadService onCreate
V/TelephonyAutoProfiling( 6168): [loadFeatureFromXml] *** start feature loading from xml
I/DownloadManager( 3126): in removeSpuriousFiles
D/TelephonyAutoProfiling( 6168): [parse] Load xml
,I/NotificationManager( 3126): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3126): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/TelephonyAutoProfiling( 6168): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6168): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
V/DownloadManager( 3126): created cursor android.database.sqlite.SQLiteCursor@fd59b03 on behalf of 3126
,I/DownloadManager( 3126): in trimDatabase
V/DownloadManager( 3126): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3126): created cursor android.database.sqlite.SQLiteCursor@3a801a80 on behalf of 3126
D/PhoneMonitor( 6168): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/ActivityManager(  842): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6193 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/DownloadManager( 3126): DownloadService onStartCommand
V/DownloadManager( 3126): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3126): created cursor android.database.sqlite.SQLiteCursor@78ce45f on behalf of 3126
,V/DownloadManager( 3126): DownloadService onDestroy
,D/DrmBroadcastReceiver( 6193): Receive CONNECTIVITY_ACTION
,D/DrmBroadcastReceiver( 6193): 1  network is available. Sync DRM Time with NTP
I/art     ( 5755): Explicit concurrent mark sweep GC freed 25558(1901KB) AllocSpace objects, 29(464KB) LOS objects, 25% free, 12MB/16MB, paused 966us total 78.239ms
V/DrmService( 6193): Service onCreate
,D/DrmService( 6193): Received new request = 2
D/WeatherAncestor( 2734): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:29:46
D/UpdateThreadPoolManager( 2734): 2 : This is isUpdating : false
I/CheckinService( 5755): Disabling old GoogleServicesFramework version
D/WeatherAncestor( 2734): connectivity changed - connection : true
I/DrmSntpClient( 6193): Start Sync process
,D/DrmSntpClient( 6193): Server : 0
D/Weather_cast( 2734): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2734): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:29:46
D/WeatherService( 2734): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
D/libc-netbsd( 6193): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6193): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6193): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6193): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10051
D/DnsProxyListener(  274): App 10051 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  842): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6214 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  842): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2734): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2734): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2734): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out( 6193): propertyValue:false
I/ActivityManager(  842): Process com.google.android.music:main (pid 5859) has died
,I/LGDrmClient( 6193): _DRM_ServiceGet() : Bind lgdrm service
,V/ILGDrmService(  288): eDRM_SetDRMTime +++
I/CheckinService( 5755): Checking schedule, now: 1454527786908 next: 1454523191080
I/CheckinService( 5755): active receiver: enabled
,I/LGDRM   (  288): [DRM] SET TIME : YR=2016, MON=2, DAY=3
I/LGDRM   (  288): [DRM] SET TIME : HR=19, MIN=29, SEC=45
,V/ILGDrmService(  288): eDRM_SetDRMTime ---
I/DrmSntpClient( 6193): Synched
I/CheckinService( 5755): Preparing to send checkin request
D/DrmService( 6193): Completed !! request = 2
D/DrmService( 6193): Request count = 0
,I/EventLogService( 5755): Accumulating logs since 1454527753514
V/DrmService( 6193): Service onDestroy
W/ResourcesManager( 6214): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/qtaguid ( 5651): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5651): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5651): untagSocket(41) failed with errno -22
,I/ActivityManager(  842): Process com.lge.email (pid 5893) has died
,V/AlarmManager(  842): ELAPSED_WAKEUP set : Alarm{6439a73 type 2 when 96970 com.android.providers.calendar} when 96970
,I/CheckinRequestBuilder( 5755): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5755): Failed to find provider info for com.google.android.wearable.settings
,I/art     ( 4869): Explicit concurrent mark sweep GC freed 2718(108KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 412us total 29.269ms
W/ResourcesManager( 5651): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5651): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5651): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     (  842): Explicit concurrent mark sweep GC freed 20321(951KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 3.247ms total 171.556ms
I/art     (  842): WaitForGcToComplete blocked for 163.350ms for cause HeapTrim
,D/Finsky  ( 5651): [1] DailyHygiene.access$600: Logging device features
V/AlarmManager(  842): RTC_WAKEUP set : Alarm{23e1b03a type 0 when 1454527787568 com.android.vending} when 1454527787568
,I/art     ( 6214): CheckpointMarkThreadRoots callback created = 0xb042d370
,I/Babel_SMS( 6214): MmsConfig: mnc/mcc: 0/0
D/DeviceConnectionService( 1734): client connected with version: 8296000
,I/Babel_SMS( 6214): MmsConfig.loadMmsSettings
,D/WearableService( 1734): callingUid 10006, callindPid: 1734
I/Babel_SMS( 6214): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6214): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6214): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6214): MmsConfig.loadFromResources
E/Babel_SMS( 6214): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6214): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/Finsky  ( 5651): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/art     ( 6214): CheckpointMarkThreadRoots callback created = 0xb042d350
D/Finsky  ( 5651): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
D/SensorManager( 6214): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6214): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6214): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6214): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6214): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6214): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6214): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6214): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6214): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6214): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6214): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6214): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6214): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6214): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6214): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6214): found sensor: Motion Accel, handle=46
,W/Settings( 6214): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6214): startup - clean
,I/ActivityManager(  842): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6247 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
I/Babel   ( 6214): deleted: false for 0
,W/ResourcesManager( 6247): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6247): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6247): VM with version 2.1.0 has multidex support
,I/MultiDex( 6247): install
I/MultiDex( 6247): VM has multidex support, MultiDex support library is disabled.
I/ActivityManager(  842): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6265 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 6214): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6214): Unsupported mime audio/adpcm
W/AudioCapabilities( 6214): Unsupported mime audio/g726
V/JNIHelp ( 6247): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/AudioCapabilities( 6214): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6214): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6214): Unsupported mime video/mjpg
,W/VideoCapabilities( 6214): Unsupported mime video/theora
,W/AudioCapabilities( 6214): Unsupported mime audio/evrc
,W/AudioCapabilities( 6214): Unsupported mime audio/qcelp
W/VideoCapabilities( 6214): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6214): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6214): Unsupported mime audio/qcelp
W/AudioCapabilities( 6214): Unsupported mime audio/evrc
W/ActivityThread( 6247): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6247): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2845677b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6247): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 6247): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6247): com.google.android.gms: cancel(39789) by com.google.android.gms
I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,W/VideoCapabilities( 6214): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 6214): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6214): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6214): Unrecognized profile 2130706433 for video/avc
I/art     ( 6247): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6247): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
W/VideoCapabilities( 6214): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6214): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6214): onServiceConnected
W/Babel   ( 6214): Attempted to change video mute state without an active call.
,I/NotificationManager( 6214): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6214): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6214): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6214): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6214): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  274): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 6214): propertyValue:false
,D/NativeLibraryUtils( 6247): Install completed successfully. count=14 extracted=0
,I/Babel   ( 6214): connection state changed from UNKNOWN to CONNECTED
I/ActivityManager(  842): Killing 6003:com.android.calendar/u0a13 (adj 15): empty #11
W/libprocessgroup(  842): failed to open /acct/uid_10013/pid_6003/cgroup.procs: No such file or directory
,D/WVCdm   (  278): Instantiating CDM.
,I/WVCdm   (  278): CdmEngine::OpenSession
I/WVCdm   (  278): Level3 Library Dec 11 2014 16:13:16
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6265): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6265): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6265): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 6265): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6265):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6265):   adb logcat -s GAv4
W/WVCdm   (  278): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  278): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  278): L1 library not specified. Falling Back to L3
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6265): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 6265): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 6265): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6265): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  278): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  278): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  278): PrepareKeyRequest: nonce=3672514155
I/WebViewFactory( 6265): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/WVCdm   (  278): CdmEngine::OpenSession
,I/LibraryLoader( 6265): Time to load native libraries: 2 ms (timestamps 9083-9085)
I/LibraryLoader( 6265): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6265): Binding Chromium to main looper Looper (main, tid 1) {25fb256b}
,I/LibraryLoader( 6265): Expected native library version number "",actual native library version number ""
I/chromium( 6265): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6265): Initializing chromium process, singleProcess=true
,W/art     ( 6265): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6265): ApplicationContext is null in ApplicationStatus
W/chromium( 6265): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6265): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6265): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6265): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6265): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6265): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6265): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6265): Remote Branch: 
I/Adreno-EGL( 6265): Local Patches: 
I/Adreno-EGL( 6265): Reconstruct Branch: 
,V/AudioPolicyService(  278): registerClient() client 0xb57f1160, uid 10079
,W/AudioManagerAndroid( 6265): Requires BLUETOOTH permission
I/NSApplication( 6265): Starting up...
I/ActivityManager(  842): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6330 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  842): Killing 6076:com.qualcomm.timeservice/1000 (adj 15): empty #11
W/libprocessgroup(  842): failed to open /acct/uid_1000/pid_6076/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  842): Killing 6108:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  842): failed to open /acct/uid_1000/pid_6108/cgroup.procs: No such file or directory
,I/iu.SyncManager( 5755): SYNC; picasa accounts
,D/NetworkLogImpl( 5755): Loaded NetworkSpeedPredictor
,I/iu.Environment( 5755): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 5755): num queued entries: 0
,I/iu.UploadsManager( 5755): num updated entries: 0
I/iu.SyncManager( 5755): NEXT; no task
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
,I/ActivityManager(  842): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6358 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 1734): propertyValue:false
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/GCM     ( 1734): GCM config loaded
,I/DigitalAppWidgetProvider( 6358): onReceive: android.intent.action.ALARM_CHANGED
,I/ActivityManager(  842): Killing 6139:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  842): failed to open /acct/uid_10011/pid_6139/cgroup.procs: No such file or directory
D/WeatherAncestor( 2734): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 20:29:50
,D/UpdateThreadPoolManager( 2734): 2 : This is isUpdating : false
D/Weather_cast( 2734): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2734): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 20:29:50
D/WeatherService( 2734): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
W/ActivityManager(  842): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2734): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2734): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2734): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/LocationInitializer( 5755): Restart initialization of location
D/AuthorizationBluetoothService( 1734): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/MDM     ( 1734): [117] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 6247): CheckpointMarkThreadRoots callback created = 0xb04ccef0
I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
,I/art     ( 6247): CheckpointMarkThreadRoots callback created = 0xb04ccee0
I/ActivityManager(  842): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6384 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1734): No location to return for getLastLocation()
,W/FusedLocationProvider( 1734): location=null
,W/ResourcesManager( 6384): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6384): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@2c87a21c
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/CalendarProvider2( 6384): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 6384): Created com.android.providers.calendar.CalendarAlarmManager@373017a1(com.android.providers.calendar.CalendarProvider2@2c87a21c)
D/CalendarProviderBroadcastReceiver( 6384): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6384): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 6384): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 6384): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6384): [getOrCreateCalendarAlarmManager]
D/Finsky  ( 5651): [680] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,E/MDM     ( 1734): [130] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1734): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 5755): Restart initialization of location
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1734): No location to return for getLastLocation()
,W/FusedLocationProvider( 1734): location=null
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/WVCdm   (  278): CdmEngine::CloseSession
I/NotificationManager(  842): android: cancelAsUser(2) by android
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  278): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  278): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
D/WVCdm   (  278): PrepareKeyRequest: nonce=2423549452
I/ActivityManager(  842): Process com.google.android.setupwizard (pid 6168) has died
,I/BackgroundMemoryTrimmer( 1938): Trimming objects from memory, since app is in the background.
I/PhoneApp( 1753): onTrimMemory: 10
I/PhoneApp( 1753): trim memory
D/CalendarProvider2( 6384): [IntentService] Release Lock
D/CalendarProvider2( 6384): CalendarProviderIntentService.onDestroy()
,D/libc-netbsd( 5651): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5651): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5651): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5651): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  274): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  274): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out( 5651): propertyValue:false
D/CAR.SERVICE( 6026): mConnectedToCar = false, abort
,E/ActivityThread( 6026): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@11e999ae that was originally bound here
E/ActivityThread( 6026): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@11e999ae that was originally bound here
E/ActivityThread( 6026): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6026): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6026): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6026): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6026): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6026): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6026): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6026): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6026): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6026): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6026): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6026): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6026): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6026): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6026): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6026): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6026): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6026): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6026): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6026): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6026): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6026): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6026): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6026): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@16cd61 that was originally bound here
E/ActivityThread( 6026): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@16cd61 that was originally bound here
E/ActivityThread( 6026): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6026): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6026): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6026): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6026): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6026): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6026): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6026): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6026): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6026): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6026): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6026): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6026): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6026): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6026): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6026): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6026): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6026): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6026): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6026): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6026): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6026): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  842): Unbind failed: could not find connection for android.os.BinderProxy@2e0cb238
D/LgeGpsLocationProvider(  842): requestTime failed
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/rmt_storage(  271): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
,I/rmt_storage(  271): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  271): wakelock acquired: 1, error no: 42
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  271): 
,I/rmt_storage(  271): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/WVCdm   (  278): CdmEngine::CloseSession
,I/WVCdm   (  278): L3 Terminate.
I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/dex2oat ( 6429): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=40 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 6429): dex2oat took 104.739ms (threads: 4)
,I/Adreno-EGL( 6247): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6247): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6247): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6247): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6247): Remote Branch: 
I/Adreno-EGL( 6247): Local Patches: 
I/Adreno-EGL( 6247): Reconstruct Branch: 
,I/Adreno-EGL( 6247): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6247): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6247): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6247): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6247): Remote Branch: 
I/Adreno-EGL( 6247): Local Patches: 
I/Adreno-EGL( 6247): Reconstruct Branch: 
,I/Adreno-EGL( 6247): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6247): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6247): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6247): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6247): Remote Branch: 
I/Adreno-EGL( 6247): Local Patches: 
I/Adreno-EGL( 6247): Reconstruct Branch: 
,I/CheckinRequestBuilder( 5755): Classify the device as Phone.
,D/libc-netbsd( 5755): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5755): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5755): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5755): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 5755): propertyValue:false
D/libc-netbsd( 5755): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5755): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5755): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5755): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5755): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5755): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/CheckinTask( 5755): Sending checkin request (9793 bytes)
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/CheckinRequestBuilder( 5755): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 5755): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 5755): Classify the device as Phone.
,I/CheckinTask( 5755): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5755): Checking schedule, now: 1454527795163 next: 1455055044158
I/CheckinService( 5755): active receiver: disabled
,D/CheckinService( 5755): Recording last checkin time for package unspecified as 1454527795192
I/ActivityManager(  842): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6453 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6453): Register our PhoneStateListener
,V/SetupWizard( 6453): Connected to Gservices successfully
,I/ActivityManager(  842): Killing 6193:com.lge.drmservice/u0a51 (adj 15): empty #11
,D/PhoneMonitor( 6453): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6453): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6453): [parse] Load xml
,V/TelephonyAutoProfiling( 6453): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6453): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6453): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  842): failed to open /acct/uid_10051/pid_6193/cgroup.procs: No such file or directory
,D/GCM     ( 1734): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/jxcore-log( 5377): Test app app.js loaded
I/jxcore-log( 5377): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5377): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5377): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5377): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5377): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5377): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5377): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5377): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5377): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5377): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5377): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a7be523 added. We now have 1 listener(s)
D/BluetoothAdapterService(404065501)( 1989): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2947ff9b
I/jxcore-log( 5377): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5377): 
,I/chromium( 5377): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager(  842): Killing 6330:com.android.chrome/u0a48 (adj 15): empty #11
,I/ActivityManager(  842): Killing 6265:com.google.android.apps.magazines/u0a79 (adj 15): empty #12
,W/libprocessgroup(  842): failed to open /acct/uid_10048/pid_6330/cgroup.procs: No such file or directory
,W/libprocessgroup(  842): failed to open /acct/uid_10079/pid_6265/cgroup.procs: No such file or directory
I/[SystemUI]QPairHandler( 1376): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1842): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QSlideListController( 1376): onReceive = android.intent.action.PACKAGE_CHANGED
I/InputReader(  842): Reconfiguring input devices.  changes=0x00000010
,W/[SystemUI]QSlideLoader( 1376): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1376): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1376): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1376): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1376): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1376): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1376): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1376): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1376): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1376): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1376): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1376): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1376): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/ActivityManager(  842): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6502 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/administrator(  842): Handling package changes for user 0
I/art     (  842): Explicit concurrent mark sweep GC freed 24891(1191KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 2.708ms total 179.817ms
,I/NotificationManager( 6214): com.google.android.talk: cancel(8) by com.google.android.talk
W/ResourcesManager( 6214): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6214): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/AppUp4:AppBoxCP( 6502): onCreate
W/AppUp4:DB( 6502):  [AppBoxDatabaseHelper] construct
,V/JNIHelp ( 6214): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppUp4:DB( 6502):  setFingerPrint start
I/AppUp4:DB( 6502):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6502):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6502):  SDK version = 0
I/AppUp4:DB( 6502):  beforefinger == newfinger no write in DB
W/System  ( 6214): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6214): Installed default security provider GmsCore_OpenSSL
I/NotificationService(  842): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  842): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  842): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/ActivityManager(  842): Process com.google.android.apps.plus (pid 5958) has died
,D/AppUp4:AppBoxApplication( 6502): AppBoxApplication onCreate()
W/ResourcesManager(  842): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  842): Process com.lge.clock (pid 6358) has died
,I/BackupManagerService(  842): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/AppUp4:CustModeStarterReceiver( 6502): onReceive
I/AppUp4:CustModeStarterReceiver( 6502): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,V/BackupManagerService(  842): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  842): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@98db158
D/AppUp4:CustFacade( 6502): Context : android.app.ReceiverRestrictedContext@25a255ab
D/AppUp4:CustFacade( 6502): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6502): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6502): begin check event
I/AppUp4:CustModeStarterReceiver( 6502): Event For Nothing, skip.
,I/ActivityManager(  842): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6526 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
D/LCardEmulationManager( 1788): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1788): getDefaultRoute
W/ResourceType(  842): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 21.261ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 20.926ms
,I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 21.049ms
,W/ResourcesManager( 6526): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6526): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6526): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/GCoreNlp( 1734): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  842): applying state to connected service
,I/ActivityManager(  842): Process com.android.vending (pid 5651) has died
,I/AppConfig( 6526): Total System Memory = 906309632
,I/GalleryUtils( 6526): Application Heap = 96 MB
I/AppConfig( 6526): App Tier : NOT_DEF
,D/SystemHelper( 6526): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager(  842): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6546 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ResourcesManager( 6546): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6546): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6546): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6546): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6546): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 6546): BUILD Country: EU
,I/SystemConfig( 6546): BUILD Operator: OPEN
I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  842): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6571 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 6546): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6546): existFile = false
I/SystemConfig( 6546): canReadFile = false
I/SystemConfig( 6546): systemFeature RCS result false
D/SystemConfig( 6546): refreshRcsSupport() :false
,I/LockScreenSettings( 6571): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6571): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6571): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,D/LockScreenSettings( 6571): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6571): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6571): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  842): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6588 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6588): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1938): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  842): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6613 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  842): Killing 6384:com.android.providers.calendar/u0a14 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1938): UpdateCorporaTask done [took 152 ms] updated apps [took 152 ms] 
,W/libprocessgroup(  842): failed to open /acct/uid_10014/pid_6384/cgroup.procs: No such file or directory
,D/Finsky  ( 6613): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6613): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6613): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6613): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6613): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3126): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3126): created cursor android.database.sqlite.SQLiteCursor@3024e775 on behalf of 6613
D/Ads     ( 6613): Skipping gmscore version check
,D/Finsky  ( 6613): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6613): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 6613): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 6613): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PackageBroadcastService( 5755): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 5755): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 5755): Storage manager: low false usage 1.69MB avail 2.37GB capacity 4.06GB
,I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
,I/ActivityManager(  842): Process com.google.android.gms.unstable (pid 6247) has died
,I/Icing   ( 5755): updateResources: need to parse f{com.google.android.gms}
,D/PowerManagerServiceEx(  842): acquireWakeLockInternal: lock=970463215, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=842
,D/WeatherService( 2734): 2 : TimeTick Intent has been received, Time(hour:min:sec) 20:30:0
D/WeatherService( 2734): 2 : TimeTick Intent And Screen On
D/WeatherService( 2734): 2 : SDK version : 21
W/ActivityManager(  842): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2734): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2734): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2734): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2734): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2734): 2 : This is isUpdating : false
D/WeatherService( 2734): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2734): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2734): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2734): 2 : Fixed theme : optimus
D/WeatherReflect( 2734): 2 : Map key string is -2
,D/lim     ( 2734): 2 : time = 20:30
I/WeatherReflect( 2734): Model Name : LG-D722
D/WeatherTheme( 2734): 2 : Different view - status_min_formatted : 29 != 30
D/WeatherTheme( 2734): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2734): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2734): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2734): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2734): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2734): currentPackage=com.lge.sizechangable.weather.theme.optimus
,I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
D/Weather4x2_optimus( 2734): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2734): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2734): forecast size is 0
,D/Theme   ( 2734): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2734): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2734): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2734): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2734): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2734): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2734): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2734): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2734): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2734): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2734): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2734): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2734): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2734): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2734): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2734): url is : null
D/Theme   ( 2734): strTheme: com.lge.launcher2.theme.optimus
,D/Theme   ( 2734): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2734): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2734): 2 : update view, appWidgetId: 2
D/WeatherService( 2734): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 20:30:0
,D/PowerManagerServiceEx(  842): releaseWakeLockInternal: lock=970463215 [*alarm*], flags=0x0
,W/ContextImpl( 3402): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/Icing   ( 5755): Internal init done: storage state 0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/Icing   ( 5755): Post-init done
I/Icing   ( 5755): updateResources: need to parse f{com.google.android.gms}
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/AlarmManager(  842): RTC_WAKEUP set : Alarm{3d49d01 type 0 when 1454527801226 com.android.vending} when 1454527801226
,D/Finsky  ( 6613): [810] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6613): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/Icing   ( 5755): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/Icing   ( 5755): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 5755): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/ActivityManager(  842): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6721 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/DigitalAppWidgetProvider( 6721): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 6721): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@25a255ab
I/ActivityManager(  842): Killing 6026:com.google.android.gms:car/u0a6 (adj 15): empty #11
W/libprocessgroup(  842): failed to open /acct/uid_10006/pid_6026/cgroup.procs: No such file or directory
,I/ActivityManager(  842): Killing 6453:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  842): failed to open /acct/uid_10038/pid_6453/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 113948366366; DSPS: 3832612; Offset : -3014912004
,I/MusicWidget( 2675): mDelayedStopHandler : unbind
,I/MusicBrowser( 2753): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2753): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2753): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2753): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2753): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2753): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2753): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2753): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,I/MediaFocusControl(  842):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@239cfa77com.lge.music.MediaPlaybackService$6@2d3116e4
D/MusicBrowser( 2753): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
,I/MusicBrowser( 2753): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2753): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2753): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2753): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@22068052
I/MusicBrowser( 2753): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2753): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2753): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2753): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2753): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2753): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2753): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2753): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2753): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2753): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2753): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2753): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2753): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2753): reset
,V/MediaPlayer[Native]( 2753): setListener
,V/MediaPlayer[Native]( 2753): disconnect
V/MediaPlayer[Native]( 2753): destructor
V/AudioFlinger(  278): releasing 19 from 2753 for -1
V/AudioFlinger(  278):  decremented refcount to 0
V/AudioFlinger(  278): purging stale effects
V/MediaPlayer[Native]( 2753): disconnect
D/MusicBrowser( 2753): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2753): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2753): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2753): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2753): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2753): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2753): [SmartShareManagerClient] unregisterListener: 188245837
W/SmartShareClient( 2753): [SmartShareManagerClient] unregisterListener invalid listener: 188245837
I/SmartShareClient( 2753): [SmartShareManagerClient] terminate service: 2753/MediaPlaybackService/695911432
E/HomeCloudIF( 2753): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2753): [SmartShareManagerClient] unbindService context:android.app.Application@290ba202
V/CloudHub( 2753): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2753): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2753): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
,I/MusicBrowser( 2753): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2753): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  842): Killing 6214:com.google.android.talk/u0a61 (adj 15): empty #11
I/CloudHub( 2753): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29990
W/libprocessgroup(  842): failed to open /acct/uid_10061/pid_6214/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/CheckinService( 5755): Done disabling old GoogleServicesFramework version
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,V/AlarmManager(  842): ELAPSED_WAKEUP set : Alarm{192357a6 type 2 when 122044 android} when 122044
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/CloudHub( 2753): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19989
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/charger_monitor(  468): init target 500000
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
D/charger_monitor(  468): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 288, mChargingStatus=5, mChargingStop=false
,I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  842): battery changed pluggedType: 2
,W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1989): Disconnected process message: 10, size: 0
I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 133949039846; DSPS: 4487995; Offset : -3014940064
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/AlarmManager(  842): ELAPSED_WAKEUP set : Alarm{292515e7 type 2 when 134684 com.google.android.gms} when 134684
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1734): Vacuum at: now=1454527825107 tag=VacuumService
,W/InstanceID/Rpc( 5755): Found 10006
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/CloudHub( 2753): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
I/CloudHub( 2753): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  842): ALS enabled for SRE
D/PowerManagerServiceEx(  842): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (27797 ms ago)
,D/qdlights(  842): set_light_backlight: 253
,D/qdlights(  842): set_light_backlight: 250
D/qdlights(  842): set_light_backlight: 246
,D/qdlights(  842): set_light_backlight: 243
,D/qdlights(  842): set_light_backlight: 240
,D/qdlights(  842): set_light_backlight: 236
,D/qdlights(  842): set_light_backlight: 233
,D/qdlights(  842): set_light_backlight: 230
,D/qdlights(  842): set_light_backlight: 226
,D/qdlights(  842): set_light_backlight: 223
,D/qdlights(  842): set_light_backlight: 220
,D/qdlights(  842): set_light_backlight: 216
,D/qdlights(  842): set_light_backlight: 213
,D/qdlights(  842): set_light_backlight: 210
,D/qdlights(  842): set_light_backlight: 206
,D/qdlights(  842): set_light_backlight: 203
,D/qdlights(  842): set_light_backlight: 200
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
D/qdlights(  842): set_light_backlight: 196
,D/qdlights(  842): set_light_backlight: 193
,D/qdlights(  842): set_light_backlight: 190
,D/qdlights(  842): set_light_backlight: 186
,D/qdlights(  842): set_light_backlight: 183
,D/qdlights(  842): set_light_backlight: 180
,D/qdlights(  842): set_light_backlight: 176
,D/qdlights(  842): set_light_backlight: 173
,D/qdlights(  842): set_light_backlight: 170
,D/qdlights(  842): set_light_backlight: 166
,D/qdlights(  842): set_light_backlight: 163
,D/qdlights(  842): set_light_backlight: 160
,D/qdlights(  842): set_light_backlight: 156
,D/qdlights(  842): set_light_backlight: 153
,D/qdlights(  842): set_light_backlight: 150
,D/qdlights(  842): set_light_backlight: 146
,D/qdlights(  842): set_light_backlight: 143
,D/qdlights(  842): set_light_backlight: 140
,D/qdlights(  842): set_light_backlight: 136
,D/qdlights(  842): set_light_backlight: 133
,D/qdlights(  842): set_light_backlight: 130
,D/qdlights(  842): set_light_backlight: 126
,D/qdlights(  842): set_light_backlight: 123
,D/qdlights(  842): set_light_backlight: 120
,D/qdlights(  842): set_light_backlight: 116
,D/qdlights(  842): set_light_backlight: 113
,D/qdlights(  842): set_light_backlight: 110
,D/qdlights(  842): set_light_backlight: 106
,D/qdlights(  842): set_light_backlight: 103
,D/qdlights(  842): set_light_backlight: 100
,D/qdlights(  842): set_light_backlight: 96
,D/qdlights(  842): set_light_backlight: 93
,D/qdlights(  842): set_light_backlight: 90
,D/qdlights(  842): set_light_backlight: 86
,D/qdlights(  842): set_light_backlight: 83
,D/qdlights(  842): set_light_backlight: 80
,D/qdlights(  842): set_light_backlight: 76
,D/qdlights(  842): set_light_backlight: 73
,D/qdlights(  842): set_light_backlight: 70
,D/qdlights(  842): set_light_backlight: 66
,D/qdlights(  842): set_light_backlight: 63
,D/qdlights(  842): set_light_backlight: 60
,D/qdlights(  842): set_light_backlight: 56
,D/qdlights(  842): set_light_backlight: 53
,D/qdlights(  842): set_light_backlight: 50
,D/qdlights(  842): set_light_backlight: 46
,D/qdlights(  842): set_light_backlight: 43
,D/qdlights(  842): set_light_backlight: 40
,D/qdlights(  842): set_light_backlight: 36
,D/qdlights(  842): set_light_backlight: 33
,D/qdlights(  842): set_light_backlight: 30
,D/qdlights(  842): set_light_backlight: 26
,D/qdlights(  842): set_light_backlight: 23
,D/qdlights(  842): set_light_backlight: 20
,D/qdlights(  842): set_light_backlight: 16
,D/qdlights(  842): set_light_backlight: 13
,D/qdlights(  842): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/AlarmManager(  842): ELAPSED_WAKEUP set : Alarm{1f1b532c type 2 when 152060 android} when 152060
,E/ActivityThread( 5755): Failed to find provider info for com.android.contacts.metadata
D/SyncManager(  842): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 124810, reason: UserStart, SyncResult: databaseError: true stats []
D/SyncManager(  842): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 217644, reason: UserStart
I/NotificationManager(  842): android: cancelAsUser(716319171) by android
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 153949713278; DSPS: 5143377; Offset : -3014937940
,I/PowerManagerService(  842): ALS enabled for SRE
D/PowerManagerServiceEx(  842): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (34790 ms ago)
,I/PowerManagerService(  842): Going to sleep due to screen timeout (uid 1000)...
I/PowerManagerService(  842): ALS enabled for SRE
D/PowerManagerServiceEx(  842): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (34806 ms ago)
,W/ContextImpl(  842): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  842): Sleeping (uid 1000)...
D/LPWGController(  842): [updateScreenState] screen on = false
D/LPWGController(  842): disable proximity sensor
,D/LPWGController(  842): enable proximity sensor
I/SensorManager(  842): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@193dc871] by com.android.server.power.ProximitySensorListener.enable():120
I/sensors_hal_Ctx(  842): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  842): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
,D/sensors_hal_SAM(  842): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  842): activate: handle is 48, enable
V/sensors_hal_Ctx(  842): activate sensors is 1400000000000
D/sensors_hal_Thresh(  842): enable: handle=48
I/sensors_hal_SAM(  842): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  842): waitForResponse: timeout=1000
V/sensors_hal_SAM(  842): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  842): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  842): enable: Received response: 0
D/PowerManagerServiceEx(  842): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (34844 ms ago)
I/Adreno-EGL(  842): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  842): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  842): Build Date: 03/02/15 Mon
I/Adreno-EGL(  842): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  842): Remote Branch: 
I/Adreno-EGL(  842): Local Patches: 
I/Adreno-EGL(  842): Reconstruct Branch: 
,D/PermissionCache(  245): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1034 us)
,I/Sensors (  420): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  842): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  842): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  842): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  842): processInd: handle 48, count=1
V/sensors_hal_Thresh(  842): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  842): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  842): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  842): poll: count: 256
I/sensors_hal_Ctx(  842): poll: released wakelock sensor_ind
D/sensors_hal_Util(  842): waitForResponse: timeout=0
D/LPWGController(  842): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  842): current mode = 1  value = 1 1
I/LPWGController(  842): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  842): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  842): set_light_backlight: 0
,I/SensorManager(  842): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  842): activate: handle is 46, disable
V/sensors_hal_Ctx(  842): activate sensors is 1000000000000
D/sensors_hal_LP2(  842): enable: handle=46
D/sensors_hal_LP2(  842): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  842): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
,D/SurfaceFlinger(  245): Set power mode=0, type=0 flinger=0xb6482000
,D/qdhwcomposer(  245): hwc_blank: Blanking display: 0
V/sensors_hal_SAM(  842): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  842): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
I/DisplayManagerService(  842): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  842): Display changed displayId=0
,D/DSDPConnection( 1753): Display #0 changed.
,D/qdhwcomposer(  245): hwc_blank: Done blanking display: 0
D/SurfaceControl(  842): Excessive delay in setPowerMode(): 239ms
I/qdhwcomposer(  245): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  842): Got set_interactive hint
,D/KeyguardViewMediator( 1376): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1335): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1335): notifyScreenOffLocked
D/KeyguardViewMediator( 1376): notifyScreenOffLocked
D/SmartCoverViewMediator( 1335): handleNotifyScreenOFF
W/ProcessCpuTracker(  842): Skipping unknown process pid 6802
,D/KeyguardViewMediator( 1376): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1376): handleNotifyScreenOff
,D/WifiServerServiceExt(  842): sendKtScanInterval  mRtspPlay : false
,D/ScreenTurnOffBySensor( 1376): unregisterProximitySensor
,V/AudioFlinger(  278): setParameters(): io 0, keyvalue screen_state=on, calling pid 842
D/audio_hw_primary(  278): adev_set_parameters: enter: screen_state=on
V/voice   (  278): voice_set_parameters: enter: screen_state=on
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/compress_voip(  278): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  278): voice_extn_compress_voip_set_parameters: exit
V/voice   (  278): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  278): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  278): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  278): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  278): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  278): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  278): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  278): adev_set_parameters: exit with code(0)
D/StatusBarWindowView( 1376): onScreenTurnedOff why = 3
,I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1376): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/WifiServerServiceExt(  842): set CMD_KT_SCAN_INTERVAL
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
,D/GpsLocationProvider(  842): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1842): |CORE| sendScreenState: state:true
I/LEDService( 1806): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1806): stopPatternFlashing()
I/Cliptray Service( 1806): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
D/Cliptray Service( 1806): lockStatus = 0
I/LEDService( 1806): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
I/LEDService( 1806): updateLightsLocked : turn off led
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1806): RESTART MSG
D/SplitWindow(  842): check instance of lgWin Window{3e12dbc4 u0 SearchPanel}
,D/LNfcService( 1788): action : android.intent.action.SCREEN_ON
D/NfcServiceNXP( 1788): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1788): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
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
,D/InputDispatcher(  842): Window went away: Window{3b528c08 u0 SearchPanel}
I/[SystemUI]Clock( 1376): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1376): time changed, timezoneChanged : false
,D/Ulp_jni (  842): JNI:system_update. Event-0
,V/PhoneApp( 1753): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
D/WeatherService( 2734): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 20:30:46
,D/WeatherService( 2734): 2 : ACTION screen on
D/WeatherService( 2734): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2734): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2734): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 20:30:46
D/AppCleanupService( 3883): android.intent.action.SCREEN_ON
,W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  842): ACTION_SCREEN_ON
,V/AudioFlinger(  278): setParameters(): io 0, keyvalue screen_state=off, calling pid 842
D/audio_hw_primary(  278): adev_set_parameters: enter: screen_state=off
,V/voice   (  278): voice_set_parameters: enter: screen_state=off
V/compress_voip(  278): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  278): voice_extn_compress_voip_set_parameters: exit
V/voice   (  278): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  278): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  278): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  278): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  278): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  278): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  278): adev_set_parameters: exit with code(0)
D/WifiController(  842): CMD_SCREEN_OFF 
D/WifiController(  842): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  842): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1842): |CORE| sendScreenState: state:false
,I/LEDService( 1806): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1806): stopPatternFlashing()
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
I/LEDService( 1806): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1806): clear
I/Cliptray Service( 1806): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/LEDService( 1806): updateLightsLocked : turn on led
E/LEDService( 1806): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1806): Can't handle this request of patternId:0
D/LEDHandler( 1806): RESTART MSG
D/LNfcService( 1788): action : android.intent.action.SCREEN_OFF
,D/NfcServiceNXP( 1788): mScreenState : 1, mInProvisionMode : false
I/[LGHome]EVENT( 1880): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1753): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
D/WeatherService( 2734): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 20:30:46
D/WeatherService( 2734): 2 : ACTION screen off
,D/WeatherService( 2734): 2 : TimeTick Receiver Unregister
I/ActivityManager(  842): Process com.android.contacts (pid 6546) has died
E/NxpNfcJni( 1788): getReconnectState = 0x0
,D/WeatherService( 2734): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 20:30:46
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
D/AppCleanupService( 3883): android.intent.action.SCREEN_OFF
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/AppCleanupService( 3883): AppUsageStatsSaveTask
D/WifiOffDelayIfNotUsed(  842): ACTION_SCREEN_OFF
,E/NxpNfcJni( 1788): getReconnectState = 0x0
,I/Sensors (  420): sns_pwr.c(301):releasing wakelock
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,D/KeyguardViewMediator( 1376): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  842): ELAPSED_WAKEUP set : Alarm{2a957aad type 2 when 160741 com.android.systemui} when 160741
,D/PhoneUtils( 1753): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1753): getCallState : 0
,D/PhoneUtils( 1753): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1376): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1376): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 173950739260; DSPS: 5798770; Offset : -3014919689
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/PowerManagerServiceEx(  842): acquireWakeLockInternal: lock=970463215, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=842
,V/AlarmManager(  842): ELAPSED_WAKEUP set : Alarm{3bd421e2 type 2 when 181693 android} when 181693
D/PowerManagerServiceEx(  842): releaseWakeLockInternal: lock=970463215 [*alarm*], flags=0x0
,V/AlarmManager(  842): ELAPSED_WAKEUP set : Alarm{32717973 type 2 when 182725 android} when 182725
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ClearcutLoggerApiImpl( 1734): disconnect managed GoogleApiClient
,V/AlarmManager(  842): ELAPSED_WAKEUP set : Alarm{2f43f030 type 2 when 186157 com.google.android.gms} when 186157
,I/art     (  842): Explicit concurrent mark sweep GC freed 63359(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 23MB/35MB, paused 3.241ms total 231.782ms
,I/PhenotypeConfigurator( 1734): Scheduling Phenotype for one-off execution 5732 seconds from now (1454527876901)
,D/GetConfigurationSnapshotOperation( 1734): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1734): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1734): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  842): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 1734): propertyValue:false
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/charger_monitor(  468): init target 500000
D/charger_monitor(  468): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,D/HeadsetStateMachine( 1989): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  842): battery changed pluggedType: 2
D/LocationManagerService(  842): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  842): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/LocationManagerService(  842): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/art     ( 1734): Background sticky concurrent mark sweep GC freed 101224(5MB) AllocSpace objects, 31(519KB) LOS objects, 27% free, 16MB/22MB, paused 5.795ms total 114.324ms
,I/art     ( 1734): Explicit concurrent mark sweep GC freed 52527(2MB) AllocSpace objects, 0(0B) LOS objects, 40% free, 13MB/22MB, paused 1.952ms total 95.285ms
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LocationManagerService(  842): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  842): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  842): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 193951453628; DSPS: 6454153; Offset : -3014907252
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  468): init target 500000
,D/charger_monitor(  468): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
,I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1989): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
,W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  842): battery changed pluggedType: 2
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1989): Disconnected process message: 10, size: 0
,D/WifiController(  842): battery changed pluggedType: 2
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 213952127578; DSPS: 7109536; Offset : -3014934555
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 233952949862; DSPS: 7764923; Offset : -3014936637
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  468): init target 500000
,D/charger_monitor(  468): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
,D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1989): Disconnected process message: 10, size: 0
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  842): battery changed pluggedType: 2
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 253953703657; DSPS: 8420307; Offset : -3014915497
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 273954376878; DSPS: 9075689; Offset : -3014913324
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
D/charger_monitor(  468): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  468): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1989): Disconnected process message: 10, size: 0
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  842): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1989): Disconnected process message: 10, size: 0
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  842): battery changed pluggedType: 2
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
,D/charger_monitor(  468): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1376): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1376): called onTimeUpdated()
I/[SystemUI]Clock( 1376): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
I/[SystemUI]DateView( 1376): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1376): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 293955139214; DSPS: 9731074; Offset : -3014914032
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  468): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1376): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1376): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1376): On Skip Timer : true
D/KeyguardUpdateMonitor( 1376): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1376): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1376): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
,I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1376): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1989): Disconnected process message: 10, size: 0
,W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  842): battery changed pluggedType: 2
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 5377): --= Surplus to requirements =--
I/jxcore-log( 5377): 
I/jxcore-log( 5377): ****TEST TOOK:  ms ****
I/jxcore-log( 5377): 
I/jxcore-log( 5377): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5377): 
,D/AndroidRuntime( 6909): 
D/AndroidRuntime( 6909): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6909): CheckJNI is OFF
,D/AndroidRuntime( 6909): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  842): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  842): Killing 5377:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
,I/WindowState(  842): WIN DEATH: Window{1a857368 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/InputDispatcher(  842): Focus left window: Window{1a857368 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  842): Window went away: Window{1a857368 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/PackageSettings(  842): Skipping PackageSetting{2c64540b com.example.hello/10317} due to missing metadata
,I/ActivityManager(  842):   Force finishing activity ActivityRecord{1e1bb725 u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  842): Display changed displayId=0
,D/DSDPConnection( 1753): Display #0 changed.
W/ActivityManager(  842): Spurious death for ProcessRecord{b0bc560 5377:com.test.thalitest/u0a316}, curProc for 5377: null
I/ActivityManager(  842): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
,I/ActivityManager(  842):   Force finishing activity ActivityRecord{1e1bb725 u0 com.test.thalitest/.MainActivity t222 f}
W/ActivityManager(  842): Duplicate finish request for ActivityRecord{1e1bb725 u0 com.test.thalitest/.MainActivity t222 f}
,D/KeyguardModel( 1376): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/InputReader(  842): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1734): Ignoring removeGeofence because network location is disabled.
,I/QCNEJ   ( 1842): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/System.err( 3402): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
I/ActivityManager(  842): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6941 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/System.err( 3402): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3402): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3402): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3402): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3402): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3402): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3402): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3402): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3402): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3402): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3402): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/[LGHome]EVENT( 1880): [Launcher.java:5203:onStart()]onStart
I/[LGHome]EVENT( 1880): [Launcher.java:776:onResume()]onResume
,I/art     ( 1938): Explicit concurrent mark sweep GC freed 7931(483KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 12MB/20MB, paused 3.981ms total 130.922ms
,I/[LGHome]EVENT( 1880): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[SystemUI]QSlideListController( 1376): onReceive = android.intent.action.PACKAGE_REMOVED
,I/[LGHome]Launcher.Model( 1880): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/KeyguardModel( 1376): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1376): createShortcutInfo...
I/[LGHome]LGActivityUtil( 1880): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/KeyguardModel( 1376): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1376): createShortcutInfo...
I/[LGHome]EVENT( 1880): [Launcher.java:929:onResume()]onResume end
,I/Activity( 1880): Activity.onPostResume() called 
W/ResourceType( 1376): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1376): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/[LGHome]EVENT( 1880): [Launcher.java:986:onPause()]onPause
D/KeyguardModel( 1376): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1376): createShortcutInfo...
W/ResourceType( 1376): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1376): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1376): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1376): createShortcutInfo...
,W/ResourceType( 1376): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1376): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1376): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1376): createShortcutInfo...
W/[LGHome]LGWallpaperInfo( 1880): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1880): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1376): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1376): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/KeyguardModel( 1376): handleShortcutListChanged...
,I/SystemUI[Framework](  842): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  842): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  842): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  842): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  842): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@27bcf2cf,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  842): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  842): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
,W/PhoneWindowManagerEx(  842): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  842): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  842): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  842): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@27bcf2cf,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  842): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher(  842): Focus entered window: Window{3eccdb46 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/KeyguardModel( 1376): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1376): createShortcutInfo...
D/KeyguardModel( 1376): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1376): createShortcutInfo...
,W/ResourceType( 1376): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1376): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/art     (  842): Explicit concurrent mark sweep GC freed 20589(1340KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 17.946ms total 241.098ms
I/art     (  842): WaitForGcToComplete blocked for 225.535ms for cause Explicit
D/KeyguardModel( 1376): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1376): createShortcutInfo...
,I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
W/ResourceType( 1376): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1376): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/[LGHome]EVENT( 1880): [Launcher.java:5214:onStop()]onStop
D/KeyguardModel( 1376): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1376): createShortcutInfo...
,W/ResourceType( 1376): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1376): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/[LGHome]EVENT( 1880): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1880): [setNavigationBarColor] color=0x 0
,D/KeyguardModel( 1376): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1376): createShortcutInfo...
D/KeyguardModel( 1376): handleShortcutListChanged...
,D/administrator(  842): Handling package changes for user 0
,W/ResourcesManager( 6941): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6941): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6941): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/NotificationService(  842): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  842): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  842): Receieved: android.intent.action.PACKAGE_REMOVED
D/PhoneStatusBar( 1376): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/PhoneStatusBar( 1376): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
D/TaskPersister(  842): removeObsoleteFile: deleting file=222_task.xml
I/[SystemUI]NavigationThemeResource( 1376): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1376):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1376): , Keyguard show=false, IME shown=false, Panel expanded=false
,I/LGEmail ( 6941): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,W/InputMethodManagerService(  842): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  842): Got RemoteException sending setActive(false) notification to pid 5377 uid 10316
D/LGEmail ( 6941): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/art     (  842): Explicit concurrent mark sweep GC freed 7080(404KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 13.672ms total 341.931ms
,I/[LGHome]Launcher.Model( 1880): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/Timeline(  842): Timeline: Activity_windows_visible id: ActivityRecord{305c2cc3 u0 com.lge.launcher2/.Launcher t221} time:312466
W/IInputConnectionWrapper( 1880): getTextBeforeCursor on inactive InputConnection
,I/[LGHome]Launcher.Model( 1880): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1605): Unable to connect to the editor to retrieve text... will retry later
D/LCardEmulationManager( 1788): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1788): getDefaultRoute
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1880): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1880): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
D/AndroidRuntime( 6909): Shutting down VM
,I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1880): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1880): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
,W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
,W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
,W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
W/ResourcesManager(  842): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/PackageChangeReceiver( 6941): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,W/ResourceType(  842): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
D/AppUp4:PreloadHelper( 6502): added Exclude : com.test.thalitest
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/ActivityManager(  842): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6967 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
,I/[LGHome]Launcher.Model( 1880): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/Timeline( 1880): Timeline: Activity_idle id: android.os.BinderProxy@ca47a4 time:312987

```
