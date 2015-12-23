#### Test 543122980a88295_thali02_LGE-LG-D722 Logs


```
--------- beginning of system
,W/ActivityManager(  818): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
--------- beginning of main
I/Gmail   ( 5990): getAccountsCursor
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 5990): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ActivityManager(  818): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/ActivityManager(  818): Killing 5830:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
W/libprocessgroup(  818): failed to open /acct/uid_10069/pid_5830/cgroup.procs: No such file or directory
W/ActivityManager(  818): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
E/Gmail   ( 5990): Error finding the version of the Email provider.....
E/Gmail   ( 5990): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5990): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5990): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5990): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5990): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5990): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5990): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5990): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5990): We do not support migrating this version of the Email provider.
I/Gmail   ( 5990): getAccountsCursor
W/ActivityManager(  818): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5990): Observing account changes for notifications
I/ActivityManager(  818): Killing 5559:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  818): failed to open /acct/uid_10086/pid_5559/cgroup.procs: No such file or directory
I/ActivityManager(  818): Killing 5292:com.google.android.talk/u0a61 (adj 15): empty #11
D/AndroidRuntime( 6020): 
D/AndroidRuntime( 6020): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6020): CheckJNI is OFF
W/libprocessgroup(  818): failed to open /acct/uid_10061/pid_5292/cgroup.procs: No such file or directory
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  818): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=6049 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ResourcesManager( 6049): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/Gmail   ( 5990): notifyAccountChanged
I/Gmail   ( 5990): getAccountsCursor
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5990): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5990): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5990): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5990): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/AndroidRuntime( 6020): Calling main entry com.android.commands.am.Am
D/UEI.SmartControl( 5716): Internal timer expired: 1
I/ActivityManager(  818): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  818): setTaskToReturnTo : TaskRecord{2eff8f05 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  818): setTaskToReturnTo : TaskRecord{2eff8f05 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  818): AppWindowTokenEx init.. 
D/ContextHelper(  818): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  818): Focus left window: Window{19a860df u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 6020): Shutting down VM
I/[LGHome]EVENT( 1876): [Launcher.java:986:onPause()]onPause
D/SplitWindow(  818): check instance of lgWin Window{1983bb2 u0 Starting com.test.thalitest}
I/art     ( 3956): Explicit concurrent mark sweep GC freed 3038(121KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 421us total 32.066ms
I/ActivityManager(  818): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6076 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/art     (  312): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 21.863ms
I/[LGHome]EVENT( 1876): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 21.579ms
I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 383us total 24.792ms
I/[LGHome]EVENT( 1876): [Launcher.java:5214:onStop()]onStop
I/art     ( 6049): CheckpointMarkThreadRoots callback created = 0xb042d4e0
I/HotwordDetector( 1939): Closing mic
I/MicrophoneInputStream( 1939): mic_close com.google.android.apps.gsa.speech.audio.u@154e5aca
V/AudioRecord( 1939): stop()
D/AudioRecord( 1939): AudioRecord->stop()
,V/AudioFlinger(  283): RecordHandle::stop()
V/AudioFlinger(  283): RecordThread::stop
I/WindowStateAnimator(  818): Starting window displayed
V/AudioFlinger(  283): Record stopped OK
I/SystemUI[Framework](  818): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
V/AudioPolicyManager(  283): stopInput() input 16
V/AudioPolicyService(  283): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  283): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  283): releaseAudioPatch handle 17
V/AudioFlinger::PatchPanel(  283): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  283): ThreadBase::setParameters() routing=0
V/AudioFlinger(  283): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  283): processConfigEvents_l() remaining events 1
V/AudioFlinger(  283): processConfigEvents_l() DONE thread 0xb3827000
I/Babel_SMS( 6049): MmsConfig: mnc/mcc: 0/0
D/audio_hw_primary(  283): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
I/Babel_SMS( 6049): MmsConfig.loadMmsSettings
D/PhoneStatusBar( 1365): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  818): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  818): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  818): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  818): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3513898d,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  818): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1365): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1365):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1365): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1365): draw background and invalidate : color = c000000
D/BarTransitions( 1365): draw background and invalidate : color = 7070707
I/Babel_SMS( 6049): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6049): MmsConfig.loadFromDatabase
V/audio_hw_primary(  283): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  283): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  283): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  283): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  283): disable_audio_route: exit
E/audio_hw_primary(  283): disable_snd_device: enter 144
D/hardware_info(  283): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  283): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  283): stop_input_stream: exit: status(0)
V/audio_hw_primary(  283): in_standby: exit:  status(0)
V/AudioFlinger(  283): RecordThread: loop stopping
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioPolicyManager(  283): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  283): removeAudioPatch() handle 18 af handle 17
V/AudioPolicyService(  283): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  283): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioPolicyService(  283): AudioCommandThread() adding set parameter string hotword_active=0, io 16 ,delay 0
V/AudioPolicyService(  283): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing set parameters string hotword_active=0, io 16
V/AudioFlinger(  283): setParameters(): io 16, keyvalue hotword_active=0, calling pid 283
V/AudioFlinger(  283): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  283): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  283): RecordThread: loop starting
V/AudioFlinger(  283): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  283): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  283): in_set_parameters: exit: status(0)
V/AudioFlinger(  283): processConfigEvents_l() DONE thread 0xb3827000
V/AudioFlinger(  283): RecordThread: loop stopping
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
I/art     ( 6049): CheckpointMarkThreadRoots callback created = 0xb042d4c0
V/AudioRecord( 1939): stop()
V/AudioRecord( 1939): stop()
V/AudioRecord( 1939): stop()
V/AudioFlinger(  283): RecordHandle::stop()
V/AudioFlinger(  283): RecordThread::stop
V/AudioPolicyManager(  283): releaseInput() 16
V/AudioFlinger(  283): releasing 15 from 1939 for -1
V/AudioFlinger(  283):  decremented refcount to 0
V/AudioPolicyManager(  283): closeInput(16)
V/AudioFlinger(  283): purging stale effects
V/AudioFlinger(  283): closeInput() 16
V/AudioSystem(  283): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem(  818): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  283): ThreadBase::exit
V/AudioSystem( 1939): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  283): RecordThread: loop starting
V/AudioSystem( 3181): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1365): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  283): RecordThread 0xb3827000 exiting
V/AudioSystem( 1750): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1976): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 2016): ioConfigChanged() event 4, ioHandle 16
D/audio_hw_primary(  283): adev_close_input_stream: enter:stream_handle(0xb546e1a0)
D/audio_hw_primary(  283): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  283): in_standby: exit:  status(0)
V/AudioPolicyService(  283): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  283): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  283): releaseInput() exit
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing update audio port list
V/AudioFlinger(  283): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  283): removeClient_l() pid 1939, calling pid 283
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
E/Babel_SMS( 6049): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6049): MmsConfig.loadFromResources
I/HotwordRecognitionRnr( 1939): Hotword detection finished
I/HotwordRecognitionRnr( 1939): Stopping hotword detection.
E/Babel_SMS( 6049): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6049): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Gmail   ( 5990): getAccountsCursor
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ContextHelper( 6076): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/SensorManager( 6049): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6049): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6049): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6049): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6049): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6049): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6049): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6049): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6049): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6049): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6049): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6049): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6049): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6049): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6049): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6049): found sensor: Motion Accel, handle=46
W/Settings( 6049): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6049): startup - clean
I/WebViewFactory( 6076): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/Babel   ( 6049): deleted: false for 0
I/LibraryLoader( 6076): Time to load native libraries: 2 ms (timestamps 3702-3704)
I/LibraryLoader( 6076): Expected native library version number "",actual native library version number ""
I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
V/WebViewChromiumFactoryProvider( 6076): Binding Chromium to main looper Looper (main, tid 1) {2bac00fd}
I/LibraryLoader( 6076): Expected native library version number "",actual native library version number ""
I/chromium( 6076): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/ActivityManager(  818): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6106 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/BrowserStartupController( 6076): Initializing chromium process, singleProcess=true
W/art     ( 6076): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6076): ApplicationContext is null in ApplicationStatus
W/AudioCapabilities( 6049): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6049): Unsupported mime audio/adpcm
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
W/AudioCapabilities( 6049): Unsupported mime audio/g726
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/AudioCapabilities( 6049): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6049): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6049): Unsupported mime video/mjpg
W/VideoCapabilities( 6049): Unsupported mime video/theora
W/chromium( 6076): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
W/ResourcesManager( 6106): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/AudioCapabilities( 6049): Unsupported mime audio/evrc
W/AudioCapabilities( 6049): Unsupported mime audio/qcelp
E/libEGL  ( 6076): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6076): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6076): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6076): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6076): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6076): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6076): Remote Branch: 
I/Adreno-EGL( 6076): Local Patches: 
I/Adreno-EGL( 6076): Reconstruct Branch: 
W/VideoCapabilities( 6049): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6049): Unsupported mime audio/amr-wb-plus
,D/CalendarApplication( 6106): CalendarApplication.onCreate()
W/AudioCapabilities( 6049): Unsupported mime audio/qcelp
W/AudioCapabilities( 6049): Unsupported mime audio/evrc
D/PreferenceKeysParser( 6106): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6106): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@2af6a566, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@44db0a7, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@9114954, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@2bac00fd, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@137b1f2, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@101ab043, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@13e3a6c0, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@d3caff9, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@340afb3e, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@112e0d9f, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@bc6eec, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@308f52b5, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@5378d4a, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@36efe4bb, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@1f778dd8, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@202f6531, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@19e93416, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@352e1197, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@1fc3af84, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@29e4236d, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@2c3c7ba2, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@4b83033, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@1b8e3ff0, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@36ac8969, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@98aafee, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@11bb9c8f, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@1c2f6b1c, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@267b5325, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@2975dcfa, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@33df72ab, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@6561d08, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@2bb2fca1, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@29b4cec6, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@c208e87, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@18b401b4, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@2261c1dd, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@3a9f1152, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@246d8c23, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@29698520, lg_preference_defaultCalendar=com.an,droid.calendar.adaptation.PreferenceKey$KeyData@1f3d9ed9, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@878f09e, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@2d02c77f, 
V/AudioPolicyService(  283): registerClient() client 0xb4027060, uid 10316
D/GeneralPreferenceUtils( 6106): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/BluetoothManagerService(  818): Message: 20
D/BluetoothManagerService(  818): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@31761c86:true
D/BluetoothAdapterService(222081017)( 1976): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@352e1197
D/Config  ( 6106): [init]
,I/Config  ( 6106): LGCalendar ver.4.40.17
I/Config  ( 6106): start check model
I/Config  ( 6106): start check native_ca
I/Config  ( 6106): Config Operator=OPEN, Country=EU
D/Config  ( 6106): [setDefaultValuesToPref]
D/Config  ( 6106): [parseProfiles]
D/ProfilesParser( 6106): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6106): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6106): [updateProfiletoCountryInfo]
D/GeneralPreference( 6106): [checkAndMigrateOldPreference]
,W/VideoCapabilities( 6049): Unsupported mime video/mp4v-esdp
D/AlertReceiver( 6106): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,I/InitNotificationRingtoneService( 6106): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 6106): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,I/VideoCapabilities( 6049): Unsupported profile 4 for video/mp4v-es
,I/AlertUtils( 6106): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6106): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6106): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6106): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,W/VideoCapabilities( 6049): Unrecognized profile 2130706433 for video/avc
I/AlertUtils( 6106): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
W/VideoCapabilities( 6049): Unrecognized profile 2130706433 for video/avc
I/AlertUtils( 6106): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
W/VideoCapabilities( 6049): Unrecognized profile 2130706433 for video/avc
I/AlertUtils( 6106): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,W/VideoCapabilities( 6049): Unrecognized profile 2130706433 for video/avc
I/AlertUtils( 6106): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6106): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6106): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,I/AlertUtils( 6106): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 6106): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
W/art     ( 6076): Attempt to remove local handle scope entry from IRT, ignoring
,I/AlertUtils( 6106): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6106): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
W/AwContents( 6076): onDetachedFromWindow called when already detached. Ignoring
I/AlertUtils( 6106): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,I/AlertUtils( 6106): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6106): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 6106): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 6106): End InitializeAlertRingtoneService.onHandleIntent
D/SystemWebViewEngine( 6076): CordovaWebView is running on device made by: LGE
,W/art     ( 6076): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6076): Attempt to remove local handle scope entry from IRT, ignoring
W/HolidayIntentService( 6106): onHandleIntent
,D/HolidayDataLoader( 6106): readJsonAsset : holiday.json
I/vclib   ( 6049): onServiceConnected
W/Babel   ( 6049): Attempted to change video mute state without an active call.
,D/AlertService( 6106): 0 Action = android.intent.action.PROVIDER_CHANGED
,E/AgendaWidgetManager( 6106): [updateWidgets] 
D/MonthWidgetProvider( 6106): [onReceive]
D/CalendarWidgetProvider( 6106): [onReceive]
D/CalendarWidgetProvider( 6106): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
I/Activity( 6076): Activity.onPostResume() called 
,D/CalendarTypeController( 6106): [onCreate] mContext.getPackageName() = com.android.calendar
D/OpenGLRenderer( 6076): Render dirty regions requested: true
I/OpenGLRenderer( 6076): Initialized EGL, version 1.4
D/OpenGLRenderer( 6076): Enabling debug mode 0
,D/WeekWidgetProvider( 6106): [onReceive]
D/CalendarWidgetProvider( 6106): [onReceive]
D/CalendarWidgetProvider( 6106): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
W/art     ( 6049): Suspending all threads took: 5.699ms
D/CalendarTypeController( 6106): [onCreate] mContext.getPackageName() = com.android.calendar
I/AudioManager( 5100): getMode name:com.lge.qremote
,W/ResourcesManager( 6049): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6049): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Atlas   ( 6076): Validating map...
,D/SplitWindow(  818): check instance of lgWin Window{2b2f30e u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 6076): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,E/MDM     ( 1732): [148] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 4177): Restart initialization of location
,D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/InputDispatcher(  818): Focus entered window: Window{2b2f30e u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
E/HolidayIntentService( 6106): onHandleIntent:holiday data empty
,I/AudioManager( 5100): getMode name:com.lge.qremote
,W/GCoreFlp( 1732): No location to return for getLastLocation()
,W/FusedLocationProvider( 1732): location=null
I/AudioManager( 5100): getMode name:com.lge.qremote
W/InputMethodManagerService(  818): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  818): Displayed com.test.thalitest/.MainActivity: +1s238ms
I/Timeline(  818): Timeline: Activity_windows_visible id: ActivityRecord{3419b5a u0 com.test.thalitest/.MainActivity t220} time:94455
D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 94460546584; DSPS: 3193482; Offset : -3003809449
V/JNIHelp ( 6049): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Timeline( 6076): Timeline: Activity_idle id: android.os.BinderProxy@1b8e3ff0 time:94483
W/System  ( 6049): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6049): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 6049): com.google.android.talk: cancel(10436) by com.google.android.talk
,W/BindingManager( 6076): Cannot call determinedVisibility() - never saw a connection for the pid: 6076
I/ActivityManager(  818): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6174 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/NotificationManager( 6049): com.google.android.talk: cancel(8) by com.google.android.talk
,I/NotificationManager( 6049): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/CAR.SERVICE( 5811): mConnectedToCar = false, abort
,E/ActivityThread( 5811): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@30bf605a that was originally bound here
E/ActivityThread( 5811): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@30bf605a that was originally bound here
E/ActivityThread( 5811): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5811): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5811): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5811): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5811): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5811): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5811): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5811): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5811): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5811): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 5811): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 5811): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 5811): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 5811): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 5811): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 5811): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 5811): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5811): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5811): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5811): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5811): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5811): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5811): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 5811): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2f4972bd that was originally bound here
E/ActivityThread( 5811): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2f4972bd that was originally bound here
E/ActivityThread( 5811): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5811): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5811): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5811): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5811): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5811): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5811): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5811): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 5811): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 5811): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 5811): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 5811): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 5811): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 5811): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 5811): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 5811): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5811): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5811): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5811): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5811): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5811): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5811): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  818): Unbind failed: could not find connection for android.os.BinderProxy@34855ca
D/JsMessageQueue( 6076): Set native->JS mode to OnlineEventsBridgeMode
I/AppUp4:AppBoxCP( 6174): onCreate
W/AppUp4:DB( 6174):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6174):  setFingerPrint start
I/AppUp4:DB( 6174):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6174):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6174):  SDK version = 0
I/AppUp4:DB( 6174):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6174): AppBoxApplication onCreate()
,I/AppUp4:CustModeStarterReceiver( 6174): onReceive
I/AppUp4:CustModeStarterReceiver( 6174): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 6174): Context : android.app.ReceiverRestrictedContext@44db0a7
D/AppUp4:CustFacade( 6174): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6174): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6174): begin check event
I/AppUp4:CustModeStarterReceiver( 6174): Event For Nothing, skip.
I/ActivityManager(  818): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6196 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/art     ( 6049): Attempt to remove local handle scope entry from IRT, ignoring
,W/ResourcesManager( 6196): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6196): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/libc-netbsd( 6049): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6049): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
E/BandwidthController(  279): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  279): App 10061 tries DNS query. Accept family:2 protocol:0
W/ResourcesManager( 6196): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/AppConfig( 6196): Total System Memory = 906309632
,I/GalleryUtils( 6196): Application Heap = 96 MB
I/AppConfig( 6196): App Tier : NOT_DEF
D/SystemHelper( 6196): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  818): Process com.android.vending (pid 5623) has died
,I/ActivityManager(  818): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6225 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,D/jxcore_app_log( 6076): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622850048
D/JX-Cordova( 6076): jxcore cordova android initializing
,W/ResourcesManager( 6225): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6225): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6225): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6225): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6225): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/SystemConfig( 6225): BUILD Country: EU
I/SystemConfig( 6225): BUILD Operator: OPEN
,I/art     ( 6076): CheckpointMarkThreadRoots callback created = 0x9a4a2bb0
,I/SystemConfig( 6225): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6225): existFile = false
I/SystemConfig( 6225): canReadFile = false
I/SystemConfig( 6225): systemFeature RCS result false
D/SystemConfig( 6225): refreshRcsSupport() :false
,I/art     ( 6076): CheckpointMarkThreadRoots callback created = 0x9a4a2b80
,I/ActivityManager(  818): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6244 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  818): Killing 5862:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,E/Babel   ( 6049): Invalid server experiment type 3 for BabelExperiment{id='dd8c17d9', experimentType=0, defaultBoolean=null, defaultLong=null}
,E/Babel   ( 6049): Invalid server experiment type 3 for BabelExperiment{id='6412be77', experimentType=0, defaultBoolean=null, defaultLong=null}
W/libprocessgroup(  818): failed to open /acct/uid_10009/pid_5862/cgroup.procs: No such file or directory
,I/LockScreenSettings( 6244): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6244): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6244): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6244): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6244): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6244): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  818): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6267 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  818): Killing 5893:com.google.android.configupdater/u0a3 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/libprocessgroup(  818): failed to open /acct/uid_10003/pid_5893/cgroup.procs: No such file or directory
,W/ResourcesManager( 6267): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     ( 6049): Note: end time exceeds epoch: 
,I/art     (  818): Explicit concurrent mark sweep GC freed 25902(1359KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 11.453ms total 180.371ms
,I/UpdateIcingCorporaServi( 1939): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  818): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6302 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1939): UpdateCorporaTask done [took 50 ms] updated apps [took 50 ms] 
I/ActivityManager(  818): Killing 5811:com.google.android.gms:car/u0a6 (adj 15): empty #11
,W/libprocessgroup(  818): failed to open /acct/uid_10006/pid_5811/cgroup.procs: No such file or directory
,I/ActivityManager(  818): Process com.google.android.gm (pid 5990) has died
,D/Finsky  ( 6302): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6302): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6302): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6302): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 6302): com.android.vending: cancel(-1050172287) by com.android.vending
,D/Finsky  ( 6302): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6302): [1] Libraries$2.run: Finished loading 1 libraries.
V/DownloadManager( 3226): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3226): created cursor android.database.sqlite.SQLiteCursor@19c35011 on behalf of 6302
D/Ads     ( 6302): Skipping gmscore version check
D/PackageBroadcastService( 4177): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4177): Null package name or gms related package.  Ignoreing.
D/Finsky  ( 6302): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/Icing   ( 4177): updateResources: need to parse f{com.google.android.gms}
D/Finsky  ( 6302): [775] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,I/ActivityManager(  818): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6357 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Finsky  ( 6302): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  818): Process com.lge.qremote (pid 5100) has died
,D/UEI.SmartControl( 5716): Service.onUnbind: IControl
I/NotificationManager(  818): android: cancelAsUser(2) by android
,D/UEI.SmartControl( 5716): Service.onDestroy
D/UEI.SmartControl( 5716): Shutdown IRRCPlayer... 
W/irrc_jni( 5716): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 5716): ~IrrcClient ++ 
D/irrcClient( 5716): ~IrrcClient -- 
W/irrc_jni( 5716): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 5716): Blaster closed
D/UEI.SmartControl( 5716): Blaster closed
D/UEI.SmartControl( 5716): Shut down QS...
,D/UEI.SmartControl( 5716): Stopped file observer...
I/UEI.SmartControl( 5716): QS lib stop result = true
W/ResourcesManager( 6357): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/UEI.SmartControl( 5716): QS shutdown complete
D/CalendarProvider2( 6357): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@34902aa8
,D/CalendarProvider2( 6357): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 6357): Created com.android.providers.calendar.CalendarAlarmManager@2bac00fd(com.android.providers.calendar.CalendarProvider2@34902aa8)
D/CalendarProviderBroadcastReceiver( 6357): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6357): [IntentService] WakeLock acquire, start IntentSerivce
,D/libc-netbsd( 6302): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6302): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6302): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6302): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  279): App 10036 tries DNS query. Accept family:0 protocol:0
D/CalendarProvider2( 6357): CalendarProviderIntentService.onCreate()
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/CalendarProvider2( 6357): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/CalendarProvider2( 6357): [getOrCreateCalendarAlarmManager]
I/ActivityManager(  818): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6380 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 6302): propertyValue:false
D/CalendarProvider2( 6357): [IntentService] Release Lock
D/CalendarProvider2( 6357): CalendarProviderIntentService.onDestroy()
,W/jxcore-log( 6076): Initializing JXcore engine
,W/jxcore-log( 6076): JXcore engine is ready
W/jxcore-log( 6076): Starting JXcore engine
,W/ActivityManager(  818): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/.test.thalitest( 6076): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6282]" dev="sockfs" ino=6282 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6076): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 6076): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7774]" dev="sockfs" ino=7774 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6076): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6076): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6076): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[29924]" dev="sockfs" ino=29924 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
I/Gmail   ( 6380): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 6380): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/jxcore-log( 6076): Platform android
W/jxcore-log( 6076): 
W/jxcore-log( 6076): Process ARCH arm
W/jxcore-log( 6076): 
,I/ActivityManager(  818): Process com.uei.lg.quicksetsdk.lite (pid 5716) has died
,W/ActivityManager(  818): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager(  818): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6380): Observing account changes for notifications
W/ActivityManager(  818): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/Gmail   ( 6380): Error finding the version of the Email provider.....
E/Gmail   ( 6380): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6380): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6380): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6380): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6380): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6380): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6380): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6380): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6380): We do not support migrating this version of the Email provider.
,I/Gmail   ( 6380): getAccountsCursor
I/ActivityManager(  818): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6414 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 6414): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/ActivityManager(  818): Process com.android.contacts (pid 6225) has died
,I/Gmail   ( 6380): notifyAccountChanged
,I/Gmail   ( 6380): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/BluetoothManagerService(  818): Message: 20
D/BluetoothManagerService(  818): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3a082206:true
I/Gmail   ( 6380): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/BluetoothAdapterService(222081017)( 1976): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@352e1197
D/BluetoothAdapterService(222081017)( 1976): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@352e1197
I/Gmail   ( 6380): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/AudioManager( 6414): getMode name:com.lge.qremote
I/Gmail   ( 6380): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6380): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/AudioManager( 6414): getMode name:com.lge.qremote
,I/Icing   ( 4177): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/Icing   ( 4177): Loaded CLD2 Version V2.0 - 20141016
,I/Gmail   ( 6380): getAccountsCursor
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 4177): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,V/AlarmManager(  818): RTC_WAKEUP set : Alarm{34857851 type 0 when 1450833976603 com.google.android.googlequicksearchbox} when 1450833976603
,I/ActivityManager(  818): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6442 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  312): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 303us total 26.050ms
,V/LGMDMManager( 6414): Create singleton instance
I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 21.304ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 21.165ms
,I/AudioManager( 6414): getMode name:com.lge.qremote
D/UEI.SmartControl( 6442): Quickset Services start...
,I/UEI.SmartControl( 6442): Manufacture = LGE
D/UEI.SmartControl( 6442): File observer start...
E/UEI.SmartControl( 6442): IR Port is disabled: false
D/UEI.SmartControl( 6442): Starting file observer...
D/UEI.SmartControl( 6442): Extracting JNI libs...
D/UEI.SmartControl( 6442): --- this system supports 32-bit or 64-bit only
I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/UEI.SmartControl( 6442): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6442): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6442): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6442): --- Selecting new region: 2
,I/UEI.SmartControl( 6442): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6442): Platform has CIR...
D/UEI.SmartControl( 6442): NO CIR support, need to check package...
I/UEI.SmartControl( 6442): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6442): QS Service created
E/UEI.SmartControl( 6442): QS start get config
,I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/UEI.SmartControl( 6442): Loading JNI Libs...
D/UEI.SmartControl( 6442):  configuring local db...
,I/jxcore-log( 6076): JXcore Cordova bridge is ready!
I/jxcore-log( 6076): 
,W/jxcore-log( 6076): JXcore engine is started
I/Choreographer( 6076): Skipped 215 frames!  The application may be doing too much work on its main thread.
I/chromium( 6076): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/UEI.SmartControl( 6442):  ---- Has DB8: true
,D/UEI.SmartControl( 6442): QS start statue = true Error code = 0
D/UEI.SmartControl( 6442): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6442): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6442): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6442): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6442): IrrcClient ++ 
D/irrcClient( 6442): getIrrcService ++ 
D/irrcClient( 6442): getIrrcService -- 
D/irrcClient( 6442): IrrcClient -- 
W/irrc_jni( 6442): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 6442): Services init done
I/UEI.SmartControl( 6442): Device manager: loading config....
D/UEI.SmartControl( 6442): QS Service init finished
D/UEI.SmartControl( 6442): QS Service version name: 0.1.73
D/UEI.SmartControl( 6442): Config is loaded...
D/UEI.SmartControl( 6442): QS Service version code: 1073
D/UEI.SmartControl( 6442): Service requested: Control
,D/UEI.SmartControl( 6442): -----IControl: 11
D/UEI.SmartControl( 6442): Caller: com.lge.qremote
D/UEI.SmartControl( 6442): ------------ IControl registerCallback...
D/UEI.SmartControl( 6442): Internal service binding...
I/UEI.SmartControl( 6442): Registering callback...
D/UEI.SmartControl( 6442): -----IControl: 19
D/UEI.SmartControl( 6442): Caller: com.lge.qremote
I/UEI.SmartControl( 6442): Registering Services Ready callback...
I/UEI.SmartControl( 6442): Notify client services are ready...
D/UEI.SmartControl( 6442): -----IControl: 8
D/UEI.SmartControl( 6442): Caller: com.lge.qremote
,I/AudioManager( 6414): getMode name:com.lge.qremote
I/ActivityManager(  818): Killing 5960:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,D/UEI.SmartControl( 6442):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6442): Notify AllClients services are ready: 0
,W/libprocessgroup(  818): failed to open /acct/uid_10038/pid_5960/cgroup.procs: No such file or directory
,I/AudioManager( 6414): getMode name:com.lge.qremote
I/AudioManager( 6414): getMode name:com.lge.qremote
D/AlertService( 6106): Beginning updateAlertNotification
,W/PackageSettings(  818): Skipping PackageSetting{3c1e0f46 com.example.hello/10317} due to missing metadata
,D/AlertService( 6106): No fired or scheduled alerts
,I/NotificationManager( 6106): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6106): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6106): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6106): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6106): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6106): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6106): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6106): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6106): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6106): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6106): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6106): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6106): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6106): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6106): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6106): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6106): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6106): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6106): com.android.calendar: cancel(18) by com.android.calendar
,I/NotificationManager( 6106): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6106): com.android.calendar: cancel(20) by com.android.calendar
I/ActivityManager(  818): Killing 6174:com.lge.appbox.client/u0a11 (adj 15): empty #11
,D/AlertService( 6106): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
W/libprocessgroup(  818): failed to open /acct/uid_10011/pid_6174/cgroup.procs: No such file or directory
,D/AlarmScheduler( 6106): No events found starting within 1 week.
,I/ActivityManager(  818): Killing 6106:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  818): failed to open /acct/uid_10013/pid_6106/cgroup.procs: No such file or directory
,I/jxcore-log( 6076): Toggling radios to true
I/jxcore-log( 6076): 
,D/BluetoothAdapter( 6076): enable(): BT is already enabled..!
D/WifiServiceImplEx(  818): setWifiEnabled: true pid=6076, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  818): setWifiEnabled: true pid=6076, uid=10316
D/WifiServiceImplEx(  818): disconnect pid=6076, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  818): reconnect pid=6076, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 6076): Radios toggled
I/jxcore-log( 6076): 
D/BluetoothManagerService(  818): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 6076): Got Device Bluetooth address: F8:95:C7:87:85:54
I/jxcore-log( 6076): 
,I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
I/jxcore-log( 6076): Perf Test app loaded loaded
I/jxcore-log( 6076): 
I/Choreographer( 6076): Skipped 115 frames!  The application may be doing too much work on its main thread.
,I/wpa_supplicant( 2759): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/jxcore-log( 6076): check test folder
I/jxcore-log( 6076): 
I/jxcore-log( 6076): found test : ./testFindPeers.js
I/jxcore-log( 6076): 
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2759): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine(  818): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  818): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/jxcore-log( 6076): found test : ./testSendData.js
I/jxcore-log( 6076): 
D/WfdsMonitor( 1802): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/LGWifiP2pService(  818): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  818): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  818): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  279): Clearing all IP addresses on wlan0
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 7
,I/jxcore-log( 6076): found test : ./testSendData2.js
I/jxcore-log( 6076): 
,V/NativeCrypto( 1732): Read error: ssl=0xb045bc00: I/O error during system call, Connection timed out
,D/libc-netbsd(  818): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  818): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1732): SSL shutdown failed: ssl=0xb045bc00: I/O error during system call, Broken pipe
,D/ConnectivityService(  818): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  818): ignoring duplicate network state non-change
D/WifiHS20(  818): hidePasspointNotification off =false
W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  818): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService(  818): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-23 02:26:19.299 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1365): mWifiConnected = false, mWifiLevel = 0
D/libc-netbsd(  818): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  818): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  818): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  818): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/ConnectivityService(  818): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1365): Got action android.net.wifi.STATE_CHANGE at null
,I/[SystemUI]QuickSettingsHandler( 1365): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1365): Remote
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  818): ValidatedState{ when=-1ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  818): DefaultState{ when=-14ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  818): Forcing reevaluation
I/ActivityManager(  818): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6489 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,E/WifiStateMachine(  818): Start Disconnecting Watchdog 1
D/WifiHS20(  818): hidePasspointNotification off =false
W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  818): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGWifiP2pService(  818): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  818): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2759): wlan0: CTRL-EVENT-SCAN-STARTED 
I/[SystemUI]StatusBar.NetworkController( 1365): mWifiConnected = false, mWifiLevel = 0
,I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-23 02:26:19.366 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1365): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1365): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1365): Remote
I/ActivityManager(  818): Killing 6196:com.android.gallery3d/u0a23 (adj 15): empty #11
,D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
D/CommandListener(  279): Clearing all IP addresses on wlan0
,D/ConnectivityService(  818): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  818): disableDataServiceNotify
D/DSQN    (  818): stop dsqn bin
I/chromium( 6076): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/ConnectivityService(  818): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,W/libprocessgroup(  818): failed to open /acct/uid_10023/pid_6196/cgroup.procs: No such file or directory
D/ConnectivityService(  818):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  818):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  818): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityManager.CallbackHandler( 1365): CM callback handler got msg 524292
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-23 02:26:19.433 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiHS20(  818): hidePasspointNotification off =false
W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  818): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/Nat464Xlat(  818): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  818): ValidatedState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  818): DefaultState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  818): Disconnected - quitting
I/[SystemUI]StatusBar.NetworkController( 1365): mWifiConnected = false, mWifiLevel = 0
D/CSLegacyTypeTracker(  818): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  818): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1365): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1365): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1365): Remote
D/ConnectivityService(  818): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WifiNetworkAgent(  818): NetworkAgent: NetworkAgent channel lost
D/ConnectivityService(  818): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  818): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/QCNEJ   ( 1838): |CORE| No family connected
V/NetworkPolicy(  818): [LG_RESTRICTED] !!!isConnected  type  :1
D/WifiHS20(  818): hidePasspointNotification off =false
D/Tethering(  818): MasterInitialState.processMessage what=3
W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  818): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-23 02:26:19.445 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-23 02:26:19.448 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  818): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/ConnectivityService(  818): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  818): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  818): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Tethering(  818): MasterInitialState.processMessage what=3
V/NetworkPolicy(  818): [LG_RESTRICTED] !!!isConnected  type  :1
D/WifiServerServiceExt(  818): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  818): setSupplicantStateDISCONNECTED
W/QCNEJ   ( 1838): |CORE| No family connected
I/QCNEJ   ( 1838): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1838): |CORE| sendDefaultNwMsg: default = -1
D/TelephonyNetworkFactory-1( 1750): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1750):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/NetworkManagementService(  818): Removing idletimer
,W/Settings(  818): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WIFI    (  818): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiServerServiceExt(  818): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  818): setSupplicantStateSCANNING
D/WIFI    (  818):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/DhcpStateMachine(  818): StoppedState
D/DhcpStateMachine(  818): StoppedState{ when=-126ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyIcons( 1365): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1365): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1365): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1365): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1365): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1365): Remote
I/[SystemUI]StatusBar.NetworkController( 1365): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1365): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1365): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1365): Remote
D/TelephonyIcons( 1365): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1365): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  818): Process com.google.android.talk (pid 6049) has died
,W/ResourcesManager( 6489): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6489): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6489): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6489): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6489): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/IndexDatabaseHelper( 6489): Using schema version: 115
,I/IndexDatabaseHelper( 6489): Index is fine
,I/art     (  818): Explicit concurrent mark sweep GC freed 36700(1974KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 1.809ms total 153.498ms
,V/WiFiOffLoadBroadcast( 6489): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6489): MCCMNC not supported: null
I/ActivityManager(  818): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6517 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/PCSuite ( 6517): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6517): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6517): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6489): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6489): MCCMNC not supported: null
I/PCSuite ( 6517): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6517): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6517): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/charger_monitor(  490): init target 500000
,I/ActivityManager(  818): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6540 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  818): Killing 6244:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
D/charger_monitor(  490): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2759): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,W/libprocessgroup(  818): failed to open /acct/uid_10069/pid_6244/cgroup.procs: No such file or directory
D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1365): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1365): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1365): On Skip Timer : true
D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1365): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1365): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
,D/HeadsetStateMachine( 1976): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  818): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1365): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/LocSvc_java(  818): onReceive
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-23 02:26:20.516 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1365): mWifiConnected = false, mWifiLevel = 0
W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  818): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  818): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServerServiceExt(  818): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  818): setSupplicantStateASSOCIATING
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-23 02:26:20.522 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1365): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1365): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1365): Remote
I/[SystemUI]StatusBar.NetworkController( 1365): mWifiConnected = false, mWifiLevel = 0
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2759): wlan0: Associated with c0:ff:d4:d3:aa:48
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1365): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1365): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1365): Remote
W/ResourcesManager( 6540): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/wpa_supplicant( 2759): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2759): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
,I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 4
D/WifiServerServiceExt(  818): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  818): setSupplicantStateGROUP_HANDSHAKE
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1365): mWifiConnected = false, mWifiLevel = 0
W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  818): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-23 02:26:20.579 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/WifiServiceExtension(  818): setVHTCapabilityType  : false
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1365): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1365): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1365): Remote
W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  818): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/[SystemUI]StatusBar.NetworkController( 1365): mWifiConnected = false, mWifiLevel = 0
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-23 02:26:20.584 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1365): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1365): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1365): Remote
I/WifiServerServiceExt(  818): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  818): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  818): setSecurityType  : 2
,I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1365): mWifiConnected = false, mWifiLevel = 0
W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  818): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-23 02:26:20.611 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1365): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1365): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1365): Remote
W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  818): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/[SystemUI]StatusBar.NetworkController( 1365): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-23 02:26:20.619 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1365): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1365): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1365): Remote
,D/ConnectivityService(  818): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  818): Got NetworkAgent Messenger
D/ConnectivityService(  818): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  818): NetworkAgent connected
D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
E/WifiConfigStore(  818): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  818): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 9
,D/libc-netbsd(  818): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  818): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  818): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  818): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  279): Setting iface cfg
D/DhcpStateMachine(  818): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  818): Start Dhcp Watchdog 2
D/DhcpStateMachine(  818): WaitBeforeStartState
D/ConnectivityService(  818): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,E/WifiStateMachine(  818): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  818): Current State is mWaitBeforeStartState.
,D/LGWifiP2pService(  818): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3ef71912 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  818): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3ef71912 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper(  818): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  818): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  818): DHCP Start wake lock is acquired.
D/CommandListener(  279): Setting iface cfg
I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  818): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  818): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  279): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  818): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  818): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  818): setSupplicantStateCOMPLETED
D/ConnectivityService(  818): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  818): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  818): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  818): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  818): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  818): ignoring duplicate network state non-change
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1365): mWifiConnected = false, mWifiLevel = 0
D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1365): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1365): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1365): Remote
W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  818): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-51 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-23 02:26:20.782 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
E/WifiStateMachine(  818): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService(  818): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  818): Adding iface wlan0 to network 101
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1365): mWifiConnected = false, mWifiLevel = 0
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  818): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-51 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-23 02:26:20.792 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1365): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1365): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1365): Remote
,I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/WifiHS20(  818): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1365): mWifiConnected = true, mWifiLevel = 3
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-51 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-23 02:26:20.806 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,E/ConnectivityService(  818): Unexpected mtu value: 0, wlan0
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
D/ConnectivityService(  818): Adding Route [fe80::/64 -> :: wlan0] to network 101
W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/WifiOffDelayIfNotUsed(  818): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WifiHS20(  818): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  818): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-51 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-23 02:26:20.814 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  279): netlink response contains error (File exists)
D/ConnectivityService(  818): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  818): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  818): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  818): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  818): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  818): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  818): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]QuickSettingsHandler( 1365): Got action android.net.wifi.STATE_CHANGE at null
D/Nat464Xlat(  818): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  818): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  818): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/Connectivit,yService(  818): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  818):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  818):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  818):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  818):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  818):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  818): currentScore = 0, newScore = 20
D/ConnectivityService(  818):    accepting network in place of null
D/ConnectivityService(  818): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  818): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  818): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  818): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WIFI    (  818): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  818):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  818): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  818): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  818): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  818): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  818): [e] list.add(nai) empty : false size: 1
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  818): [LWD] Start DNSResolver start to wait
D/ConnectivityService(  818): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/Tethering(  818): MasterInitialState.processMessage what=3
D/TelephonyNetworkFactory-1( 1750): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1750):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
W/QCNEJ   ( 1838): |CORE| No family connected
I/QCNEJ   ( 1838): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1838): |CORE| sendDefaultNwMsg: default = 1
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  818): [LWD] wait 500ms before dns check
D/ConnectivityService(  818): validation of new default Network = false
D/ConnectivityService(  818): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  818): enableDataServiceNotify 
D/DSQN    (  818): start dsqn bin
I/[SystemUI]QuickSettingsHandler( 1365): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1365): Remote
I/[SystemUI]StatusBar.NetworkController( 1365): mWifiConnected = true, mWifiLevel = 3
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1365): Got action android.net.wifi.STATE_CHANGE at null
I/Babel_SMS( 6540): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6540): MmsConfig.loadMmsSettings
I/[SystemUI]QuickSettingsHandler( 1365): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1365): Remote
D/ConnectivityService(  818): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
I/Babel_SMS( 6540): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
V/NetworkPolicy(  818): [LG_RESTRICTED] checkMobilePolicy_type()
D/ConnectivityService(  818):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  818):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/Babel_SMS( 6540): MmsConfig.loadFromDatabase
D/ConnectivityService(  818): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1365): CM callback handler got msg 524290
I/DSQN    ( 6581): DSQN samuel.seo ver 141203
E/DSQN    ( 6581): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6581): created command queue thread
I/DSQN    ( 6581): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6581): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/TelephonyIcons( 1365): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1365): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
,E/Babel_SMS( 6540): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6540): MmsConfig.loadFromResources
E/Babel_SMS( 6540): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6540): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/GAV2    ( 6380): Thread[GAThread,5,main]: No campaign data found.
,D/DhcpStateMachine(  818): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper(  818): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  818): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/dhcpcd  ( 6586): version 5.5.6 starting
E/dhcpcd  ( 6586): get_duid: Read-only file system
,I/art     ( 6540): CheckpointMarkThreadRoots callback created = 0xb042d550
D/SensorManager( 6540): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6540): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6540): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6540): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6540): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6540): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6540): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6540): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6540): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6540): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6540): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6540): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6540): found sensor: LGE Tilt Detector Sensor, handle=55
,D/SensorManager( 6540): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6540): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6540): found sensor: Motion Accel, handle=46
I/ActivityManager(  818): Process com.android.vending (pid 6302) has died
I/art     ( 6540): CheckpointMarkThreadRoots callback created = 0xb042d540
,W/Settings( 6540): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6540): startup - clean
I/dhcpcd  ( 6586): wlan0: rebinding lease of 192.168.1.134
,I/Babel   ( 6540): deleted: false for 0
,V/WiFiOffLoadBroadcast( 6489): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6489): MCCMNC not supported: null
W/AudioCapabilities( 6540): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6540): Unsupported mime audio/adpcm
I/PCSuite ( 6517): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6517): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6517): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/AudioCapabilities( 6540): Unsupported mime audio/g726
W/AudioCapabilities( 6540): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6540): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 6540): Unsupported mime video/mjpg
V/WiFiOffLoadBroadcast( 6489): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6489): MCCMNC not supported: null
W/VideoCapabilities( 6540): Unsupported mime video/theora
,I/PCSuite ( 6517): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6517): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6517): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6489): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6489): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 6489): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,W/AudioCapabilities( 6540): Unsupported mime audio/evrc
D/WiFiOffLoadBroadcast( 6489): Not supported operator for automatic switch
W/AudioCapabilities( 6540): Unsupported mime audio/qcelp
V/WiFiOffLoadBroadcast( 6489): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/VideoCapabilities( 6540): Unrecognized profile 2130706433 for video/avc
D/WiFiOffLoadBroadcast( 6489): MCCMNC not supported: null
,W/AudioCapabilities( 6540): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6540): Unsupported mime audio/qcelp
W/AudioCapabilities( 6540): Unsupported mime audio/evrc
V/WiFiOffLoadBroadcast( 6489): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6489): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6489): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/VideoCapabilities( 6540): Unsupported mime video/mp4v-esdp
D/WiFiOffLoadBroadcast( 6489): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6489): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6489): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6489): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/VideoCapabilities( 6540): Unsupported profile 4 for video/mp4v-es
D/WiFiOffLoadBroadcast( 6489): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6489): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/VideoCapabilities( 6540): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6540): Unrecognized profile 2130706433 for video/avc
,D/WiFiOffLoadBroadcast( 6489): MCCMNC not supported: null
W/VideoCapabilities( 6540): Unrecognized profile 2130706433 for video/avc
V/WiFiOffLoadBroadcast( 6489): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/VideoCapabilities( 6540): Unrecognized profile 2130706433 for video/avc
D/WiFiOffLoadBroadcast( 6489): MCCMNC not supported: null
,I/vclib   ( 6540): onServiceConnected
W/Babel   ( 6540): Attempted to change video mute state without an active call.
I/NotificationManager( 6540): com.google.android.talk: cancel(10436) by com.google.android.talk
,V/WiFiOffLoadBroadcast( 6489): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6489): MCCMNC not supported: null
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  818): [LWD] DNSResolver start dns
D/libc-netbsd(  818): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  818): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  818): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  818): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  279): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
V/WiFiOffLoadBroadcast( 6489): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6489): MCCMNC not supported: null
I/PCSuite ( 6517): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6517): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6489): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6489): MCCMNC not supported: null
I/PCSuite ( 6517): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6517): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
,I/System.out(  818): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  818): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  818): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  818): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  818): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/DSQN    ( 6581): first global connection report this to start monitoring at DSQM.
,I/DSQN    ( 6581): restart monitoring
D/LGDataListener(  279): argv[0]=dsqncommand
D/LGDataListener(  279): argv[1]=wlan0
D/LGDataListener(  279): argv[2]=1
D/LGDataListener(  279): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 6581): dsqn report finish
D/DSQN    (  818): DSQM DsqnNotification wlan0  1
D/DSQN    (  818): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  818): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 23 Dec 2015 01:26:21 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450833981434], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450833981412]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  818): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  818): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  818): Validated
D/ConnectivityService(  818): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  818): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  818):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  818):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  818):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  818): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  818): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  818):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  818):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WifiDataContinuityService(  818): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
D/ConnectivityService(  818): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  818): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1365): CM callback handler got msg 524290
D/ConnectivityService(  818): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory-1( 1750): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1750):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/WifiServerServiceExt(  818): set CMD_CAPTIVE_CHECK_COMPLETED
D/WIFI    (  818): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  818):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyIcons( 1365): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1365): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/rmt_storage(  275): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
,I/rmt_storage(  275): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  275): wakelock acquired: 1, error no: 42
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/ConnectivityService(  818): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/Netd    (  279): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  818): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  818): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  818): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  818): identical MTU - not setting
D/Nat464Xlat(  818): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  818): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  818):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  818):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  818): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  818): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  818): enableDataServiceNotify 
D/DSQN    (  818): start dsqn bin
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-51 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-23 02:26:21.888 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/ConnectivityManager.CallbackHandler( 1365): CM callback handler got msg 524295
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  275): 
I/rmt_storage(  275): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
D/DSQN    (  818): dsqn is running restart
,I/DSQN    ( 6605): DSQN samuel.seo ver 141203
,E/DSQN    ( 6605): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6605): created command queue thread
I/DSQN    ( 6605): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6605): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,I/dhcpcd  ( 6586): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/dhcpcd  ( 6586): wlan0: leased 192.168.1.134 for 86400 seconds
,D/UEI.SmartControl( 6442): Internal timer expired: 1
,D/libc-netbsd(  818): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  818): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  818): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  818): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  818): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  818): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  818): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  818): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  818): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  818): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  818): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  818): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  818): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  818): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  818): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  818): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  818): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  818): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  818): RunningState
D/ConnectivityService(  818): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1365): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/ConnectivityService(  818): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  818): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java(  818): onReceive
D/LocSvc_java(  818): got connectivity action
D/LocSvc_java(  818): broadcast - no network connections
D/LocSvc_java(  818): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  818): Sending msg: 4 arg1:0 arg2:1
,D/LocSvc_java(  818): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  818): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  818): ignore wifi update if we are not in OPENING or CLOSING
I/ActivityManager(  818): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6631 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/GpsLocationProvider(  818): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider(  818): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  818): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LocSvc_java(  818): onReceive
D/LocSvc_java(  818): got connectivity action
D/LocSvc_java(  818): broadcast - no network connections
D/LocSvc_java(  818): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  818): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  818): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  818): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  818): ignore wifi update if we are not in OPENING or CLOSING
I/[SystemUI]QuickSettingsHandler( 1365): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,I/MusicStore( 6631): Database version: 120
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6631): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6631): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6631): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/ActivityManager(  818): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6674 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  818): RTC_WAKEUP set : Alarm{bf2ecd9 type 0 when 1450833982982 com.android.vending} when 1450833982982
,W/ResourcesManager( 6631): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6631): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  818): Process com.google.android.apps.plus (pid 6267) has died
,V/JNIHelp ( 6631): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/Finsky  ( 6674): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/ActivityThread( 6631): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6631): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@38e8faae: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6631): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6631): GMSCore installation verified
,I/ActivityManager(  818): Process com.android.providers.calendar (pid 6357) has died
,I/ConfigStore( 6631): Config Database version: 1
,D/Finsky  ( 6674): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6674): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6674): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 6674): com.android.vending: cancel(-1050172287) by com.android.vending
,D/Finsky  ( 6674): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6674): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 6674): Skipping gmscore version check
V/DownloadManager( 3226): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3226): created cursor android.database.sqlite.SQLiteCursor@38b47576 on behalf of 6674
I/MediaRouter( 6631): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6631): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6631): type=WIFI subType= reason=null isConnected=true
I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-50 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-23 02:26:23.687 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/Finsky  ( 6674): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/NetworkMonitor( 6631): type=WIFI subType= reason=null isConnected=true
,D/Finsky  ( 6674): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  818): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6731 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,E/lowmemorykiller(  243): Error opening /proc/6380/oom_score_adj; errno=2
V/WifiInternetCheck(  818): Single check msg out of sync, ignoring.
,I/ActivityManager(  818): Process com.google.android.gm (pid 6380) has died
D/UEI.SmartControl( 6442): Service.onTrimMemory: 80
E/UEI.SmartControl( 6442): Setup service releasing memory...
,I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/ConnectivityService(  818): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/BackgroundMemoryTrimmer( 1939): Trimming objects from memory, since app is in the background.
I/PhoneApp( 1750): onTrimMemory: 10
I/PhoneApp( 1750): trim memory
D/LocSvc_java(  818): onReceive
D/LocSvc_java(  818): got connectivity action
D/LocSvc_java(  818): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  818): Sending msg: 4 arg1:1 arg2:1
I/[SystemUI]QuickSettingsHandler( 1365): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/LocSvc_java(  818): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  818): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  818): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  818): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/GHttpClientFactory( 6631): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6631): Using platform SSLCertificateSocketFactory
D/GpsLocationProvider(  818): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/art     ( 6442): Explicit concurrent mark sweep GC freed 152(17KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 563us total 71.997ms
,I/NetworkMonitor( 6631): type=WIFI subType= reason=null isConnected=true
,W/ResourcesManager( 6731): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6731): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6731): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/NotificationManager( 6631): com.google.android.music: cancel(1061) by com.google.android.music
,D/Finsky  ( 6674): [815] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 6674): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  818): Process com.google.android.talk (pid 6540) has died
,I/LGEmail ( 6731): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6731): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/BluetoothAdapterService(222081017)( 1976): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@352e1197
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6076): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6076): setDiscoveryMode: Mode set to WIFI
I/jxcore-log( 6076): BLE supported!!
I/jxcore-log( 6076): 
,D/eas_req ( 6731): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  818): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6762 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6731): JNI_OnLoad()
I/HubEmail( 6731): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6731): registerNatives()
I/HubEmail( 6731): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6731): registerNativeMethods()
I/HubEmail( 6731): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6731): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6731): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 6762): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6762): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6762): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6762): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6762): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6762): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6762): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/ActivityManager(  818): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6784 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/LGDMClient( 6762): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
W/ContextImpl( 6762): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 6762): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6762): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6762): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6762): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 6762): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/AppUp4:AppBoxCP( 6784): onCreate
,W/AppUp4:DB( 6784):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6784):  setFingerPrint start
,I/AppUp4:DB( 6784):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6784):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6784):  SDK version = 0
I/AppUp4:DB( 6784):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6784): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6784): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6784): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6784): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6784): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6784): onReceive
I/AppUp4:CustModeStarterReceiver( 6784): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6784): Context : android.app.ReceiverRestrictedContext@137b1f2
D/AppUp4:CustFacade( 6784): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6784): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6784): begin check event
I/AppUp4:CustModeStarterReceiver( 6784): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6784): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6784): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6784): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6784): handleAsyncCustNotification do not startCustService
,I/ActivityManager(  818): Killing 6489:com.android.settings/1000 (adj 15): empty #11
W/libprocessgroup(  818): failed to open /acct/uid_1000/pid_6489/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3181): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3181): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3181): networkInfo.isConnected() = false
I/ActivityManager(  818): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6805 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6805): Register our PhoneStateListener
,I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/MobileConnectivityChangeReceiver( 6805): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6805): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  818): Killing 6517:com.lge.sync/1000 (adj 15): empty #11
,D/PhoneMonitor( 6805): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6805): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6805): [parse] Load xml
V/TelephonyAutoProfiling( 6805): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6805): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6805): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  818): failed to open /acct/uid_1000/pid_6517/cgroup.procs: No such file or directory
,V/DownloadManager( 3226): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,I/CheckinService( 4177): Checkin interval check for package: unspecified last checkin: 1450833958636 min interval config: 0 actual interval: 26263
V/DownloadManager( 3226): DownloadService onCreate
I/NotificationManager( 3226): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3226): in removeSpuriousFiles
V/DownloadManager( 3226): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3226): created cursor android.database.sqlite.SQLiteCursor@25353fe4 on behalf of 3226
,I/DownloadManager( 3226): in trimDatabase
V/DownloadManager( 3226): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3226): created cursor android.database.sqlite.SQLiteCursor@1f7bdc4d on behalf of 3226
I/ActivityManager(  818): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6828 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3226): DownloadService onStartCommand
I/CheckinService( 4177): Checking schedule, now: 1450833984944 next: 1450833988549
I/CheckinService( 4177): active receiver: disabled
V/DownloadManager( 3226): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3226): created cursor android.database.sqlite.SQLiteCursor@2e9c413 on behalf of 3226
,V/DownloadManager( 3226): DownloadService onDestroy
,D/libc-netbsd(  818): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  818): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  818): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  818): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  279): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  818): Killing 6442:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 6414): android.os.DeadObjectException
,W/System.err( 6414): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6414): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6414): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6414): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 6414): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6414): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6414): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6414): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6414): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6414): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6414): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6414): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6414): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6414): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6414): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6414): android.os.DeadObjectException
W/System.err( 6414): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6414): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6414): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6414): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 6414): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6414): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6414): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6414): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6414): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6414): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6414): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6414): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6414): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6414): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6414): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out(  818): propertyValue:false
,D/libc-netbsd(  818): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  818): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  818): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  818): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  279): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out(  818): propertyValue:false
I/DSQN    ( 6605): first global connection report this to start monitoring at DSQM.
,I/DSQN    ( 6605): restart monitoring
D/LGDataListener(  279): argv[0]=dsqncommand
D/LGDataListener(  279): argv[1]=wlan0
D/LGDataListener(  279): argv[2]=1
D/LGDataListener(  279): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 6605): dsqn report finish
D/DSQN    (  818): DSQM DsqnNotification wlan0  1
D/DSQN    (  818): start to monitor internet connection
W/libprocessgroup(  818): failed to open /acct/uid_10089/pid_6442/cgroup.procs: No such file or directory
W/ActivityManager(  818): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,V/WifiInternetCheck(  818): isHttpConnectionAvailable - We got a valid response : 204
D/WeatherAncestor( 2625): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 2:26:25
,I/ActivityManager(  818): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6861 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/UpdateThreadPoolManager( 2625): 2 : This is isUpdating : false
D/WeatherAncestor( 2625): connectivity changed - connection : true
D/Weather_cast( 2625): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2625): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 2:26:25
D/WeatherService( 2625): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/art     (  312): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 332us total 26.121ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 21.901ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 20.812ms
,I/ActivityManager(  818): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6878 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  818): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2625): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2625): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2625): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6878): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6861): Quickset Services start...
I/UEI.SmartControl( 6861): Manufacture = LGE
D/UEI.SmartControl( 6861): File observer start...
E/UEI.SmartControl( 6861): IR Port is disabled: false
D/UEI.SmartControl( 6861): Starting file observer...
D/UEI.SmartControl( 6861): Extracting JNI libs...
D/UEI.SmartControl( 6861): --- this system supports 32-bit or 64-bit only
,I/Babel_SMS( 6878): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6878): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6878): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6878): MmsConfig.loadFromDatabase
D/UEI.SmartControl( 6861): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6861): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6861): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,E/Babel_SMS( 6878): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6878): MmsConfig.loadFromResources
E/Babel_SMS( 6878): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6878): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6878): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6878): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6878): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6878): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6878): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6878): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6878): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6878): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6878): found sensor: LGE Step Counter Sensor, handle=44
,D/SensorManager( 6878): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6878): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6878): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6878): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6878): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6878): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6878): found sensor: Motion Accel, handle=46
I/UEI.SmartControl( 6861): --- Selecting new region: 2
I/UEI.SmartControl( 6861): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6861): Platform has CIR...
D/UEI.SmartControl( 6861): NO CIR support, need to check package...
I/UEI.SmartControl( 6861): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6861): QS Service created
,W/Settings( 6878): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6878): startup - clean
E/UEI.SmartControl( 6861): QS start get config
I/art     ( 6878): CheckpointMarkThreadRoots callback created = 0xb042d900
,D/UEI.SmartControl( 6861): Loading JNI Libs...
D/UEI.SmartControl( 6861):  configuring local db...
I/Babel   ( 6878): deleted: false for 0
,I/art     ( 6878): CheckpointMarkThreadRoots callback created = 0xb042d8e0
,I/art     (  818): Explicit concurrent mark sweep GC freed 69981(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.298ms total 159.401ms
,D/UEI.SmartControl( 6861):  ---- Has DB8: true
D/UEI.SmartControl( 6861): QS start statue = true Error code = 0
,D/UEI.SmartControl( 6861): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6861): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6861): IRRCDataComm has AudioManager!!!!.
I/ActivityManager(  818): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6917 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/irrc_jni( 6861): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6861): IrrcClient ++ 
D/irrcClient( 6861): getIrrcService ++ 
D/irrcClient( 6861): getIrrcService -- 
D/irrcClient( 6861): IrrcClient -- 
W/irrc_jni( 6861): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6861): Services init done
,V/AlarmManager(  818): ELAPSED_WAKEUP set : Alarm{35b4ddc3 type 2 when 107793 com.google.android.gms} when 107793
I/UEI.SmartControl( 6861): Device manager: loading config....
D/UEI.SmartControl( 6861): QS Service init finished
,D/UEI.SmartControl( 6861): Config is loaded...
D/UEI.SmartControl( 6861): QS Service version name: 0.1.73
W/AudioCapabilities( 6878): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6878): Unsupported mime audio/adpcm
W/AudioCapabilities( 6878): Unsupported mime audio/g726
W/AudioCapabilities( 6878): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6878): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6878): Unsupported mime video/mjpg
W/VideoCapabilities( 6878): Unsupported mime video/theora
,D/UEI.SmartControl( 6861): QS Service version code: 1073
,D/UEI.SmartControl( 6861): Service requested: Control
W/AudioCapabilities( 6878): Unsupported mime audio/evrc
I/ActivityManager(  818): Killing 6414:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 6861): -----IControl: 11
D/UEI.SmartControl( 6861): Caller: com.lge.qremote
D/UEI.SmartControl( 6861): ------------ IControl registerCallback...
W/AudioCapabilities( 6878): Unsupported mime audio/qcelp
I/UEI.SmartControl( 6861): Registering callback...
W/VideoCapabilities( 6878): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6878): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6878): Unsupported mime audio/qcelp
W/AudioCapabilities( 6878): Unsupported mime audio/evrc
W/VideoCapabilities( 6878): Unsupported mime video/mp4v-esdp
,D/UEI.SmartControl( 6861):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6861): Notify AllClients services are ready: 0
I/VideoCapabilities( 6878): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6878): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6878): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6878): Unrecognized profile 2130706433 for video/avc
,W/libprocessgroup(  818): failed to open /acct/uid_10106/pid_6414/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6861): Internal service binding...
W/VideoCapabilities( 6878): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6878): onServiceConnected
,W/Babel   ( 6878): Attempted to change video mute state without an active call.
I/NotificationManager( 6878): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 6878): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6878): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6878): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6878): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  279): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 6878): propertyValue:false
I/Babel   ( 6878): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  818): Killing 6674:com.android.vending/u0a36 (adj 15): empty #11
W/libprocessgroup(  818): failed to open /acct/uid_10036/pid_6674/cgroup.procs: No such file or directory
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6917): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6917): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6917): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 6917): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6917):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6917):   adb logcat -s GAv4
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6917): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 6917): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6917): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6917): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 6917): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6917): Time to load native libraries: 2 ms (timestamps 8554-8556)
I/LibraryLoader( 6917): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6917): Binding Chromium to main looper Looper (main, tid 1) {34f7dc67}
I/LibraryLoader( 6917): Expected native library version number "",actual native library version number ""
I/chromium( 6917): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6917): Initializing chromium process, singleProcess=true
,W/art     ( 6917): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6917): ApplicationContext is null in ApplicationStatus
W/chromium( 6917): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6917): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6917): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6917): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6917): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6917): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6917): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6917): Remote Branch: 
I/Adreno-EGL( 6917): Local Patches: 
I/Adreno-EGL( 6917): Reconstruct Branch: 
V/AudioPolicyService(  283): registerClient() client 0xb40278a0, uid 10079
,W/AudioManagerAndroid( 6917): Requires BLUETOOTH permission
I/NSApplication( 6917): Starting up...
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  818): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6986 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  818): Killing 6631:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  818): failed to open /acct/uid_10081/pid_6631/cgroup.procs: No such file or directory
,I/ActivityManager(  818): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7005 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  818): Killing 6731:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  818): failed to open /acct/uid_10021/pid_6731/cgroup.procs: No such file or directory
,W/ResourcesManager( 7005): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  818): Killing 6762:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  818): failed to open /acct/uid_1000/pid_6762/cgroup.procs: No such file or directory
,I/ActivityManager(  818): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7029 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/MusicStore( 7029): Database version: 120
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7029): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7029): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7029): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7029): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7029): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7029): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7029): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7029): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@38e8faae: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7029): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7029): GMSCore installation verified
I/ConfigStore( 7029): Config Database version: 1
,I/MediaRouter( 7029): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7029): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7029): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7029): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  818): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7057 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7029): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7029): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 7057): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7057): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7057): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/ActivityManager(  818): Killing 6784:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  818): failed to open /acct/uid_10011/pid_6784/cgroup.procs: No such file or directory
,I/LGEmail ( 7057): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/NotificationManager( 7029): com.google.android.music: cancel(1061) by com.google.android.music
D/LGEmail ( 7057): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7057): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/AlarmManager(  818): RTC_WAKEUP set : Alarm{157fc38c type 0 when 1450833988549 com.google.android.gms} when 1450833988549
,V/AlarmManager(  818): RTC_WAKEUP set : Alarm{177d82ea type 0 when 1450833988848 com.google.android.googlequicksearchbox} when 1450833988848
I/ActivityManager(  818): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7084 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7057): JNI_OnLoad()
I/HubEmail( 7057): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7057): registerNatives()
I/HubEmail( 7057): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7057): registerNativeMethods()
I/HubEmail( 7057): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7057): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  818): Killing 6805:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  818): failed to open /acct/uid_10038/pid_6805/cgroup.procs: No such file or directory
,W/Settings( 7057): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 7084): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7084): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7084): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7084): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7084): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7084): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7084): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 7084): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  818): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7108 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7084): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 7084): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7084): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7084): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7084): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 7084): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  818): Killing 6828:com.lge.drmservice/u0a51 (adj 15): empty #11
,I/AppUp4:AppBoxCP( 7108): onCreate
,W/AppUp4:DB( 7108):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7108):  setFingerPrint start
I/AppUp4:DB( 7108):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,W/libprocessgroup(  818): failed to open /acct/uid_10051/pid_6828/cgroup.procs: No such file or directory
I/AppUp4:DB( 7108):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7108):  SDK version = 0
I/AppUp4:DB( 7108):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7108): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7108): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7108): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7108): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 7108): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7108): onReceive
I/AppUp4:CustModeStarterReceiver( 7108): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7108): Context : android.app.ReceiverRestrictedContext@137b1f2
D/AppUp4:CustFacade( 7108): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7108): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7108): begin check event
I/AppUp4:CustModeStarterReceiver( 7108): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7108): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7108): call method handleAsyncCustNotification.
,D/AppUp4:CustModeStarterReceiver( 7108): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7108): handleAsyncCustNotification do not startCustService
I/ActivityManager(  818): Killing 6861:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
I/LgeMiscReceiver( 3181): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3181): action = android.net.conn.CONNECTIVITY_CHANGE
W/libprocessgroup(  818): failed to open /acct/uid_10089/pid_6861/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3181): networkInfo.isConnected() = false
,I/ActivityManager(  818): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7135 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7135): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7135): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7135): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  818): Killing 6878:com.google.android.talk/u0a61 (adj 15): empty #11
D/PhoneMonitor( 7135): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 7135): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7135): [parse] Load xml
V/TelephonyAutoProfiling( 7135): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7135): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7135): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  818): failed to open /acct/uid_10061/pid_6878/cgroup.procs: No such file or directory
V/DownloadManager( 3226): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3226): DownloadService onCreate
,I/NotificationManager( 3226): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3226): in removeSpuriousFiles
V/DownloadManager( 3226): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3226): created cursor android.database.sqlite.SQLiteCursor@1fb6f049 on behalf of 3226
I/DownloadManager( 3226): in trimDatabase
V/DownloadManager( 3226): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3226): created cursor android.database.sqlite.SQLiteCursor@1f90bd4e on behalf of 3226
,I/ActivityManager(  818): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7157 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3226): DownloadService onStartCommand
I/CheckinService( 4177): Checkin interval check for package: unspecified last checkin: 1450833958636 min interval config: 0 actual interval: 31012
V/DownloadManager( 3226): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3226): created cursor android.database.sqlite.SQLiteCursor@32754805 on behalf of 3226
,I/CheckinService( 4177): Checking schedule, now: 1450833989661 next: 1450833988549
I/CheckinService( 4177): active receiver: enabled
,I/CheckinService( 4177): Preparing to send checkin request
I/EventLogService( 4177): Accumulating logs since 1450833950678
V/DownloadManager( 3226): DownloadService onDestroy
,D/WeatherAncestor( 2625): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 2:26:29
D/UpdateThreadPoolManager( 2625): 2 : This is isUpdating : false
D/WeatherAncestor( 2625): connectivity changed - connection : true
D/Weather_cast( 2625): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2625): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 2:26:29
D/WeatherService( 2625): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  818): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7176 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  818): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2625): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2625): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2625): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/art     (  312): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 303us total 25.195ms
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/CheckinRequestBuilder( 4177): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 4177): Failed to find provider info for com.google.android.wearable.settings
I/art     (  312): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 26.592ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 316us total 23.110ms
,W/ResourcesManager( 7176): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     (  818): Explicit concurrent mark sweep GC freed 16326(866KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.374ms total 138.327ms
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel_SMS( 7176): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7176): MmsConfig.loadMmsSettings
,I/ActivityManager(  818): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7214 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/Babel_SMS( 7176): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7176): MmsConfig.loadFromDatabase
,D/SensorManager( 7176): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7176): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7176): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7176): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7176): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7176): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7176): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7176): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7176): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7176): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7176): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7176): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7176): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7176): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7176): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7176): found sensor: Motion Accel, handle=46
,E/Babel_SMS( 7176): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7176): MmsConfig.loadFromResources
E/Babel_SMS( 7176): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7176): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
W/ResourcesManager( 7214): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7214): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/Settings( 7176): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/art     ( 7176): CheckpointMarkThreadRoots callback created = 0xb042d8c0
I/Babel_Crash( 7176): startup - clean
I/art     ( 7176): CheckpointMarkThreadRoots callback created = 0xb042d8a0
,I/Babel   ( 7176): deleted: false for 0
,W/AudioCapabilities( 7176): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7176): Unsupported mime audio/adpcm
W/AudioCapabilities( 7176): Unsupported mime audio/g726
I/MultiDex( 7214): VM with version 2.1.0 has multidex support
W/AudioCapabilities( 7176): Unsupported mime audio/x-ms-wma
I/MultiDex( 7214): install
I/MultiDex( 7214): VM has multidex support, MultiDex support library is disabled.
W/AudioCapabilities( 7176): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 7176): Unsupported mime video/mjpg
V/MusicLeanback( 7029): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
W/VideoCapabilities( 7176): Unsupported mime video/theora
,D/LGDMClient( 7084): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7084): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7084): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 7084): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/Settings( 7057): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/NetworkStateForAutoUpdateMonitor( 7108): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7108): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7108): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7108): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7108): onReceive
I/AppUp4:CustModeStarterReceiver( 7108): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7108): Context : android.app.ReceiverRestrictedContext@137b1f2
D/AppUp4:CustFacade( 7108): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7108): isSimDevice : true
D/LGDMClient( 7084): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
D/AppUp4:CustModeStarterReceiver( 7108): begin check event
I/AppUp4:CustModeStarterReceiver( 7108): Event For GoodConnectivity, noConnectivity : false, but skip! 
,I/LgeMiscReceiver( 3181): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3181): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3181): networkInfo.isConnected() = true
I/LGDMClient( 7084): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/PhoneState( 3181): setPdpRejectCasuse : false
D/MobileConnectivityChangeReceiver( 7135): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7135): onReceive CONNECTIVITY_CHANGE networkType=1
D/LGDMClient( 7084): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7084): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3226): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3226): DownloadService onCreate
,W/ContextImpl( 7084): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
D/WeatherAncestor( 2625): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 2:26:30
E/LGDMClient( 7084): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/UpdateThreadPoolManager( 2625): 2 : This is isUpdating : false
D/WeatherAncestor( 2625): connectivity changed - connection : true
D/Weather_cast( 2625): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2625): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 2:26:30
D/WeatherService( 2625): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
W/ActivityManager(  818): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2625): 2 : Utils getTopActivity com.lge.launcher2 / true
D/LGDMClient( 7084): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/WeatherService( 2625): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/LGDMClient( 7084): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/WeatherService( 2625): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/NotificationManager( 3226): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3226): in removeSpuriousFiles
D/LGDMClient( 7084): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
V/DownloadManager( 3226): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/JNIHelp ( 7214): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/LGDMClient( 7084): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,V/DownloadManager( 3226): created cursor android.database.sqlite.SQLiteCursor@3073a28b on behalf of 3226
,W/AudioCapabilities( 7176): Unsupported mime audio/evrc
V/DownloadManager( 3226): DownloadService onStartCommand
I/DownloadManager( 3226): in trimDatabase
V/DownloadManager( 3226): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3226): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
W/AudioCapabilities( 7176): Unsupported mime audio/qcelp
V/DownloadManager( 3226): created cursor android.database.sqlite.SQLiteCursor@32032826 on behalf of 3226
W/VideoCapabilities( 7176): Unrecognized profile 2130706433 for video/avc
V/DownloadManager( 3226): created cursor android.database.sqlite.SQLiteCursor@34f7dc67 on behalf of 3226
,W/AudioCapabilities( 7176): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7176): Unsupported mime audio/qcelp
W/AudioCapabilities( 7176): Unsupported mime audio/evrc
,V/DownloadManager( 3226): DownloadService onDestroy
,W/VideoCapabilities( 7176): Unsupported mime video/mp4v-esdp
W/ActivityThread( 7214): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7214): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2fe42777: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7214): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 7214): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7214): com.google.android.gms: cancel(39789) by com.google.android.gms
I/VideoCapabilities( 7176): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7176): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7176): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7176): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7176): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 7176): onServiceConnected
,W/Babel   ( 7176): Attempted to change video mute state without an active call.
I/art     ( 7214): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7214): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7005): CheckpointMarkThreadRoots callback created = 0xb042d490
D/libc-netbsd( 7176): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7176): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7176): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7176): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  279): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
,D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 7176): propertyValue:false
I/NotificationManager( 7176): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Babel   ( 7176): connection state changed from UNKNOWN to CONNECTED
I/art     ( 7005): CheckpointMarkThreadRoots callback created = 0xb042d460
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
I/CheckinService( 4177): Checkin interval check for package: unspecified last checkin: 1450833958636 min interval config: 0 actual interval: 32181
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 1732): propertyValue:false
D/WearableService( 1732): callingUid 10006, callindPid: 1732
,I/ActivityManager(  818): Killing 7029:com.google.android.music:main/u0a81 (adj 15): empty #11
E/MDM     ( 1732): [125] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/NativeLibraryUtils( 7214): Install completed successfully. count=14 extracted=0
W/libprocessgroup(  818): failed to open /acct/uid_10081/pid_7029/cgroup.procs: No such file or directory
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 4177): Restart initialization of location
,D/WVCdm   (  283): Instantiating CDM.
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/WVCdm   (  283): CdmEngine::OpenSession
I/WVCdm   (  283): Level3 Library Dec 11 2014 16:13:16
I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
,W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
,W/WVCdm   (  283): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  283): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  283): L1 library not specified. Falling Back to L3
,I/WVCdm   (  283): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  283): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  283): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  283): CdmEngine::GenerateKeyRequest
D/WVCdm   (  283): PrepareKeyRequest: nonce=256333951
I/art     ( 7214): CheckpointMarkThreadRoots callback created = 0xb042d630
,I/art     ( 7214): CheckpointMarkThreadRoots callback created = 0xb042d620
,I/dex2oat ( 7266): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7266): dex2oat took 98.483ms (threads: 4)
,I/Adreno-EGL( 7214): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7214): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7214): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7214): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7214): Remote Branch: 
I/Adreno-EGL( 7214): Local Patches: 
I/Adreno-EGL( 7214): Reconstruct Branch: 
,W/ContextImpl( 3596): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/Adreno-EGL( 7214): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7214): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7214): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7214): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7214): Remote Branch: 
I/Adreno-EGL( 7214): Local Patches: 
I/Adreno-EGL( 7214): Reconstruct Branch: 
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/Adreno-EGL( 7214): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7214): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7214): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7214): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7214): Remote Branch: 
I/Adreno-EGL( 7214): Local Patches: 
I/Adreno-EGL( 7214): Reconstruct Branch: 
,I/WVCdm   (  283): CdmEngine::OpenSession
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 114461424806; DSPS: 3848871; Offset : -3003816758
,I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/WVCdm   (  283): CdmEngine::CloseSession
,I/WVCdm   (  283): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  283): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  283): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  283): CdmEngine::GenerateKeyRequest
D/WVCdm   (  283): PrepareKeyRequest: nonce=3095076427
V/AlarmManager(  818): ELAPSED_WAKEUP set : Alarm{28fe7138 type 2 when 115447 com.google.android.gms} when 115447
,I/WVCdm   (  283): CdmEngine::CloseSession
,I/WVCdm   (  283): L3 Terminate.
I/MusicWidget( 2570): mDelayedStopHandler : unbind
,I/MusicBrowser( 2016): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2016): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2016): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2016): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2016): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2016): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2016): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
,I/MusicBrowser( 2016): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  818):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@1b8e3ff0com.lge.music.MediaPlaybackService$6@36ac8969
,D/MusicBrowser( 2016): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2016): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2016): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2016): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2016): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@340afb3e
I/MusicBrowser( 2016): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2016): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2016): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2016): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2016): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2016): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2016): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2016): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2016): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2016): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2016): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2016): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2016): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2016): reset
,V/MediaPlayer[Native]( 2016): setListener
V/MediaPlayer[Native]( 2016): disconnect
V/MediaPlayer[Native]( 2016): destructor
V/AudioFlinger(  283): releasing 18 from 2016 for -1
V/AudioFlinger(  283):  decremented refcount to 0
V/AudioFlinger(  283): purging stale effects
V/MediaPlayer[Native]( 2016): disconnect
D/MusicBrowser( 2016): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
,I/SmartShareClient( 2016): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2016): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2016): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2016): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2016): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2016): [SmartShareManagerClient] unregisterListener: 160083950
W/SmartShareClient( 2016): [SmartShareManagerClient] unregisterListener invalid listener: 160083950
I/SmartShareClient( 2016): [SmartShareManagerClient] terminate service: 2016/MediaPlaybackService/152127828
E/HomeCloudIF( 2016): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2016): [SmartShareManagerClient] unbindService context:android.app.Application@11bb9c8f
,V/CloudHub( 2016): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2016): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2016): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
,I/MusicBrowser( 2016): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2016): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  818): Killing 7057:com.lge.email/u0a21 (adj 15): empty #11
I/CloudHub( 2016): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29994
W/libprocessgroup(  818): failed to open /acct/uid_10021/pid_7057/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/ProcessCpuTracker(  818): Skipping unknown process pid 7299
,W/ProcessCpuTracker(  818): Skipping unknown process pid 7302
I/CheckinRequestBuilder( 4177): Classify the device as Phone.
,D/libc-netbsd( 4177): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4177): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4177): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4177): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 4177): propertyValue:false
,D/libc-netbsd( 4177): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4177): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4177): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4177): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4177): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4177): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 4177): Sending checkin request (9944 bytes)
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/CheckinRequestBuilder( 4177): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4177): Failed to find provider info for com.google.android.wearable.settings
I/art     ( 3956): Explicit concurrent mark sweep GC freed 2262(88KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 366us total 56.128ms
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinRequestBuilder( 4177): Classify the device as Phone.
,I/CheckinTask( 4177): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4177): Checking schedule, now: 1450833997252 next: 1451361246248
I/CheckinService( 4177): active receiver: disabled
,I/CheckinService( 4177): Checking schedule, now: 1450833997286 next: 1451361246248
I/CheckinService( 4177): active receiver: disabled
,D/CheckinService( 4177): Recording last checkin time for package unspecified as 1450833997297
,I/ActivityManager(  818): Killing 7108:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  818): failed to open /acct/uid_10011/pid_7108/cgroup.procs: No such file or directory
,V/SetupWizard( 7135): Connected to Gservices successfully
I/ActivityManager(  818): Killing 7157:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  818): failed to open /acct/uid_10051/pid_7157/cgroup.procs: No such file or directory
,D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]QPairHandler( 1365): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1838): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[SystemUI]QSlideListController( 1365): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader(  818): Reconfiguring input devices.  changes=0x00000010
,W/[SystemUI]QSlideLoader( 1365): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1365): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1365): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1365): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1365): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1365): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1365): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1365): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1365): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1365): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
,W/[SystemUI]QSlideLoader( 1365): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1365): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1365): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
D/administrator(  818): Handling package changes for user 0
,I/ActivityManager(  818): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7351 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/NotificationManager( 7176): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 7176): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7176): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/AppUp4:AppBoxCP( 7351): onCreate
,W/AppUp4:DB( 7351):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7351):  setFingerPrint start
I/AppUp4:DB( 7351):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7351):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7351):  SDK version = 0
I/AppUp4:DB( 7351):  beforefinger == newfinger no write in DB
,V/JNIHelp ( 7176): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/NotificationService(  818): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  818): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  818): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/System  ( 7176): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7176): Installed default security provider GmsCore_OpenSSL
,W/ResourcesManager(  818): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  818): Process com.google.android.apps.magazines (pid 6917) has died
,D/AppUp4:AppBoxApplication( 7351): AppBoxApplication onCreate()
I/BackupManagerService(  818): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
V/BackupManagerService(  818): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  818): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2614413b
I/AppUp4:CustModeStarterReceiver( 7351): onReceive
I/AppUp4:CustModeStarterReceiver( 7351): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 7351): Context : android.app.ReceiverRestrictedContext@44db0a7
D/AppUp4:CustFacade( 7351): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7351): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7351): begin check event
I/AppUp4:CustModeStarterReceiver( 7351): Event For Nothing, skip.
W/ResourceType(  818): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  818): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7374 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1732): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
W/ResourcesManager( 7374): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7374): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7374): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/art     ( 1732): Explicit concurrent mark sweep GC freed 31572(2MB) AllocSpace objects, 25(400KB) LOS objects, 40% free, 14MB/23MB, paused 1.754ms total 110.026ms
,D/LocationProviderProxy(  818): applying state to connected service
,I/AppConfig( 7374): Total System Memory = 906309632
,I/GalleryUtils( 7374): Application Heap = 96 MB
I/AppConfig( 7374): App Tier : NOT_DEF
D/SystemHelper( 7374): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager(  818): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7397 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ResourcesManager( 7397): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7397): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7397): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7397): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7397): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7397): BUILD Country: EU
,I/SystemConfig( 7397): BUILD Operator: OPEN
I/ActivityManager(  818): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7419 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  818): Killing 7084:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  818): failed to open /acct/uid_1000/pid_7084/cgroup.procs: No such file or directory
I/SystemConfig( 7397): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7397): existFile = false
I/SystemConfig( 7397): canReadFile = false
I/SystemConfig( 7397): systemFeature RCS result false
D/SystemConfig( 7397): refreshRcsSupport() :false
I/LockScreenSettings( 7419): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/art     (  818): Explicit concurrent mark sweep GC freed 28088(1388KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.562ms total 176.547ms
,D/LockScreenSettings( 7419): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7419): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7419): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7419): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7419): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/UpdateIcingCorporaServi( 1939): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  818): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7440 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  818): Killing 6986:com.android.chrome/u0a48 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1939): UpdateCorporaTask done [took 107 ms] updated apps [took 107 ms] 
,W/libprocessgroup(  818): failed to open /acct/uid_10048/pid_6986/cgroup.procs: No such file or directory
,D/Finsky  ( 7440): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7440): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7440): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7440): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7440): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3226): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3226): created cursor android.database.sqlite.SQLiteCursor@2f4972bd on behalf of 7440
D/Finsky  ( 7440): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7440): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 7440): Skipping gmscore version check
I/ActivityManager(  818): Killing 2016:com.lge.music/u0a28 (adj 15): empty #11
,V/AudioFlinger(  283): 2016 died, releasing its sessions
V/AudioFlinger(  283):  pid 1750 @ 0
V/AudioFlinger(  283):  pid 3181 @ 1
V/AudioFlinger(  283):  pid 3181 @ 2
,W/libprocessgroup(  818): failed to open /acct/uid_10028/pid_2016/cgroup.procs: No such file or directory
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
D/Finsky  ( 7440): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 4177): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 4177): Null package name or gms related package.  Ignoreing.
,D/Finsky  ( 7440): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 4177): updateResources: need to parse f{com.google.android.gms}
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/ProcessCpuTracker(  818): Skipping unknown process pid 7497
,W/ProcessCpuTracker(  818): Skipping unknown process pid 7498
W/ProcessCpuTracker(  818): Skipping unknown process pid 7504
W/ProcessCpuTracker(  818): Skipping unknown process pid 7505
W/ProcessCpuTracker(  818): Skipping unknown process pid 7516
I/Icing   ( 4177): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4177): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,D/charger_monitor(  490): init target 500000
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1365): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1365): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1365): On Skip Timer : true
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1976): Disconnected process message: 10, size: 0
I/[SystemUI]LGPowerUI( 1365): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1365): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
D/WifiController(  818): battery changed pluggedType: 2
,W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]BatterySaverHandler( 1365): onReceive = android.intent.action.BATTERY_CHANGED
I/ActivityManager(  818): Killing 7135:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  818): failed to open /acct/uid_10038/pid_7135/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 134462204120; DSPS: 4504257; Offset : -3003830537
,I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/PowerManagerServiceEx(  818): acquireWakeLockInternal: lock=67613646, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=818
,D/WeatherService( 2625): 2 : TimeTick Intent has been received, Time(hour:min:sec) 2:27:0
,D/WeatherService( 2625): 2 : TimeTick Intent And Screen On
D/WeatherService( 2625): 2 : SDK version : 21
W/ActivityManager(  818): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2625): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2625): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2625): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2625): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2625): 2 : This is isUpdating : false
D/WeatherService( 2625): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2625): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2625): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2625): 2 : Fixed theme : optimus
D/WeatherReflect( 2625): 2 : Map key string is -2
,D/lim     ( 2625): 2 : time = 02:27
I/WeatherReflect( 2625): Model Name : LG-D722
D/WeatherTheme( 2625): 2 : Different view - status_min_formatted : 26 != 27
D/WeatherTheme( 2625): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
,D/WeatherReflect( 2625): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2625): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2625): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2625): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2625): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/[SystemUI]TimeTickManager( 1365): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1365): called onTimeUpdated()
,D/Weather4x2_optimus( 2625): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2625): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2625): forecast size is 0
,D/Theme   ( 2625): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2625): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2625): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/[SystemUI]Clock( 1365): called onTimeUpdated()
I/LgeClockWidgetControlView( 1365): called onTimeUpdated()
D/Theme   ( 2625): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2625): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2625): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/[SystemUI]DateView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1365): handleTimeUpdate
D/Theme   ( 2625): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2625): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2625): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2625): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2625): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2625): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2625): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2625): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2625): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2625): url is : null
D/Theme   ( 2625): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2625): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2625): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
,D/WeatherAncestor( 2625): 2 : update view, appWidgetId: 2
D/WeatherService( 2625): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 2:27:0
D/PowerManagerServiceEx(  818): releaseWakeLockInternal: lock=67613646 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/AlarmManager(  818): ELAPSED_WAKEUP set : Alarm{2f6482ef type 2 when 146957 com.google.android.gms} when 146957
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/VacuumService( 1732): Vacuum at: now=1450834025325 tag=VacuumService
,I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PowerManagerService(  818): ALS enabled for SRE
D/PowerManagerServiceEx(  818): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (29223 ms ago)
,D/qdlights(  818): set_light_backlight: 251
,D/qdlights(  818): set_light_backlight: 248
,D/qdlights(  818): set_light_backlight: 245
,D/qdlights(  818): set_light_backlight: 241
,D/qdlights(  818): set_light_backlight: 238
,D/qdlights(  818): set_light_backlight: 235
,D/qdlights(  818): set_light_backlight: 231
,D/qdlights(  818): set_light_backlight: 228
,D/qdlights(  818): set_light_backlight: 225
,D/qdlights(  818): set_light_backlight: 221
,D/qdlights(  818): set_light_backlight: 218
,D/qdlights(  818): set_light_backlight: 215
,D/qdlights(  818): set_light_backlight: 211
,D/qdlights(  818): set_light_backlight: 208
,D/qdlights(  818): set_light_backlight: 205
,D/qdlights(  818): set_light_backlight: 201
,D/qdlights(  818): set_light_backlight: 198
,D/qdlights(  818): set_light_backlight: 195
,D/qdlights(  818): set_light_backlight: 191
,D/qdlights(  818): set_light_backlight: 188
,D/qdlights(  818): set_light_backlight: 185
,D/qdlights(  818): set_light_backlight: 181
,D/qdlights(  818): set_light_backlight: 178
,D/qdlights(  818): set_light_backlight: 175
,D/qdlights(  818): set_light_backlight: 171
,D/qdlights(  818): set_light_backlight: 168
,D/qdlights(  818): set_light_backlight: 165
,D/qdlights(  818): set_light_backlight: 161
,D/qdlights(  818): set_light_backlight: 158
,D/qdlights(  818): set_light_backlight: 155
,D/qdlights(  818): set_light_backlight: 151
,D/qdlights(  818): set_light_backlight: 148
,D/qdlights(  818): set_light_backlight: 145
,D/qdlights(  818): set_light_backlight: 141
,D/qdlights(  818): set_light_backlight: 138
,D/qdlights(  818): set_light_backlight: 135
,D/qdlights(  818): set_light_backlight: 131
,D/qdlights(  818): set_light_backlight: 128
,D/qdlights(  818): set_light_backlight: 125
,D/qdlights(  818): set_light_backlight: 121
,D/qdlights(  818): set_light_backlight: 118
,D/qdlights(  818): set_light_backlight: 115
,D/qdlights(  818): set_light_backlight: 111
,D/qdlights(  818): set_light_backlight: 108
,D/qdlights(  818): set_light_backlight: 105
,D/qdlights(  818): set_light_backlight: 101
,D/qdlights(  818): set_light_backlight: 98
,D/qdlights(  818): set_light_backlight: 95
,D/qdlights(  818): set_light_backlight: 91
,D/qdlights(  818): set_light_backlight: 88
,D/qdlights(  818): set_light_backlight: 85
,D/qdlights(  818): set_light_backlight: 81
,D/qdlights(  818): set_light_backlight: 78
,D/qdlights(  818): set_light_backlight: 75
,D/qdlights(  818): set_light_backlight: 71
,D/qdlights(  818): set_light_backlight: 68
,D/qdlights(  818): set_light_backlight: 65
,I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
D/qdlights(  818): set_light_backlight: 61
,D/qdlights(  818): set_light_backlight: 58
,D/qdlights(  818): set_light_backlight: 55
,D/qdlights(  818): set_light_backlight: 51
,D/qdlights(  818): set_light_backlight: 48
,D/qdlights(  818): set_light_backlight: 45
,D/qdlights(  818): set_light_backlight: 41
,D/qdlights(  818): set_light_backlight: 38
,D/qdlights(  818): set_light_backlight: 35
,D/qdlights(  818): set_light_backlight: 31
,D/qdlights(  818): set_light_backlight: 28
,D/qdlights(  818): set_light_backlight: 25
,D/qdlights(  818): set_light_backlight: 21
,D/qdlights(  818): set_light_backlight: 18
,D/qdlights(  818): set_light_backlight: 15
,D/qdlights(  818): set_light_backlight: 11
,D/qdlights(  818): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 154463003592; DSPS: 5159643; Offset : -3003824495
,I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1365): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  818): ALS enabled for SRE
D/PowerManagerServiceEx(  818): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (36223 ms ago)
I/PowerManagerService(  818): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  818): ALS enabled for SRE
D/PowerManagerServiceEx(  818): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (36240 ms ago)
W/ContextImpl(  818): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  818): Sleeping (uid 1000)...
D/LPWGController(  818): [updateScreenState] screen on = false
D/LPWGController(  818): disable proximity sensor
,D/LPWGController(  818): enable proximity sensor
I/SensorManager(  818): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@19875494] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  818): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  818): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  818): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  818): activate: handle is 48, enable
V/sensors_hal_Ctx(  818): activate sensors is 1400000000000
D/sensors_hal_Thresh(  818): enable: handle=48
I/sensors_hal_SAM(  818): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  818): waitForResponse: timeout=1000
,V/sensors_hal_SAM(  818): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  818): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  818): enable: Received response: 0
D/PowerManagerServiceEx(  818): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (36289 ms ago)
I/Adreno-EGL(  818): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  818): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  818): Build Date: 03/02/15 Mon
I/Adreno-EGL(  818): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  818): Remote Branch: 
I/Adreno-EGL(  818): Local Patches: 
I/Adreno-EGL(  818): Reconstruct Branch: 
,D/PermissionCache(  246): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1081 us)
,I/Sensors (  413): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  818): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  818): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  818): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  818): processInd: handle 48, count=1
V/sensors_hal_Thresh(  818): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  818): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  818): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  818): poll: count: 256
I/sensors_hal_Ctx(  818): poll: released wakelock sensor_ind
D/sensors_hal_Util(  818): waitForResponse: timeout=0
D/LPWGController(  818): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  818): current mode = 1  value = 1 1
I/LPWGController(  818): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  818): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  818): set_light_backlight: 0
,I/SensorManager(  818): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  818): activate: handle is 46, disable
V/sensors_hal_Ctx(  818): activate sensors is 1000000000000
D/sensors_hal_LP2(  818): enable: handle=46
D/sensors_hal_LP2(  818): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  818): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  246): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  246): hwc_blank: Blanking display: 0
I/DisplayManagerService(  818): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  818): Display changed displayId=0
V/sensors_hal_SAM(  818): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  818): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1750): Display #0 changed.
,D/qdhwcomposer(  246): hwc_blank: Done blanking display: 0
D/SurfaceControl(  818): Excessive delay in setPowerMode(): 205ms
,I/qdhwcomposer(  246): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  818): Got set_interactive hint
D/KeyguardViewMediator( 1365): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1333): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1365): notifyScreenOffLocked
D/SmartCoverViewMediator( 1333): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1333): handleNotifyScreenOFF
,D/KeyguardViewMediator( 1365): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1365): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1365): unregisterProximitySensor
,D/StatusBarWindowView( 1365): onScreenTurnedOff why = 3
D/WifiServerServiceExt(  818): sendKtScanInterval  mRtspPlay : false
V/AudioFlinger(  283): setParameters(): io 0, keyvalue screen_state=on, calling pid 818
,D/audio_hw_primary(  283): adev_set_parameters: enter: screen_state=on
V/voice   (  283): voice_set_parameters: enter: screen_state=on
V/compress_voip(  283): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  283): voice_extn_compress_voip_set_parameters: exit
V/voice   (  283): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  283): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  283): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  283): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  283): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  283): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  283): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  283): adev_set_parameters: exit with code(0)
D/KeyguardUpdateMonitor( 1365): handleTimeUpdate
,I/WifiServerServiceExt(  818): set CMD_KT_SCAN_INTERVAL
,D/GpsLocationProvider(  818): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1365): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1838): |CORE| sendScreenState: state:true
I/LEDService( 1802): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1802): stopPatternFlashing()
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
I/Cliptray Service( 1802): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/LEDService( 1802): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
I/LEDService( 1802): updateLightsLocked : turn off led
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
D/Cliptray Service( 1802): lockStatus = 0
D/LNfcService( 1785): action : android.intent.action.SCREEN_ON
,D/LEDHandler( 1802): RESTART MSG
D/NfcServiceNXP( 1785): mScreenState : 3, mInProvisionMode : false
,D/NfcServiceNXP( 1785): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1785): isRequireNfcCRouting() return true
D/LNfcService( 1785): isHCERoutingtoHost() return : true
D/NfcService( 1785): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1785): mEnableLPD: true
D/NfcService( 1785): mEnableReader: false
D/NfcService( 1785): mEnableHostRouting: true
D/NfcService( 1785): newParams.techmask= mTechMask: default
D/NfcService( 1785): mEnableLPD: true
D/NfcService( 1785): mEnableReader: false
D/NfcService( 1785): mEnableHostRouting: true
D/NfcService( 1785): screenState= 3
D/NfcService( 1785): Discovery configuration equal, not updating.
D/SplitWindow(  818): check instance of lgWin Window{2213a483 u0 SearchPanel}
,D/Ulp_jni (  818): JNI:system_update. Event-0
,D/InputDispatcher(  818): Window went away: Window{270c09eb u0 SearchPanel}
I/[SystemUI]Clock( 1365): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1365): time changed, timezoneChanged : false
,V/PhoneApp( 1750): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2625): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 2:27:16
,D/WeatherService( 2625): 2 : ACTION screen on
D/WeatherService( 2625): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2625): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2625): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 2:27:16
W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  818): ACTION_SCREEN_ON
D/AppCleanupService( 4051): android.intent.action.SCREEN_ON
I/Sensors (  413): sns_pwr.c(301):releasing wakelock
,V/AudioFlinger(  283): setParameters(): io 0, keyvalue screen_state=off, calling pid 818
D/audio_hw_primary(  283): adev_set_parameters: enter: screen_state=off
V/voice   (  283): voice_set_parameters: enter: screen_state=off
V/compress_voip(  283): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  283): voice_extn_compress_voip_set_parameters: exit
V/voice   (  283): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  283): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  283): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  283): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  283): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  283): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  283): adev_set_parameters: exit with code(0)
D/WifiController(  818): CMD_SCREEN_OFF 
D/WifiController(  818): shouldWifiStayAwake TRUE
,D/GpsLocationProvider(  818): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,I/[SystemUI]LGPowerUI( 1365): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1838): |CORE| sendScreenState: state:false
,I/LEDService( 1802): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1802): stopPatternFlashing()
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1802): clear
I/LEDService( 1802): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
I/Cliptray Service( 1802): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1785): action : android.intent.action.SCREEN_OFF
I/LEDService( 1802): updateLightsLocked : turn on led
E/LEDService( 1802): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1802): Can't handle this request of patternId:0
D/LEDHandler( 1802): RESTART MSG
D/NfcServiceNXP( 1785): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1876): [Launcher.java:1711:onReceive()]Screen Off
V/PhoneApp( 1750): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2625): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 2:27:16
D/WeatherService( 2625): 2 : ACTION screen off
D/WeatherService( 2625): 2 : TimeTick Receiver Unregister
D/WeatherService( 2625): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 2:27:16
W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  818): ACTION_SCREEN_OFF
D/AppCleanupService( 4051): android.intent.action.SCREEN_OFF
D/AppCleanupService( 4051): AppUsageStatsSaveTask
,E/NxpNfcJni( 1785): getReconnectState = 0x0
,D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
D/LNfcService( 1785): isRequireNfcCRouting() return true
D/LNfcService( 1785): isHCERoutingtoHost() return : true
D/NfcService( 1785): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1785): mEnableLPD: true
D/NfcService( 1785): mEnableReader: false
D/NfcService( 1785): mEnableHostRouting: true
D/NfcService( 1785): newParams.techmask= mTechMask: 0
D/NfcService( 1785): mEnableLPD: true
D/NfcService( 1785): mEnableReader: false
D/NfcService( 1785): mEnableHostRouting: true
D/NfcService( 1785): screenState= 1
E/NxpNfcJni( 1785): getReconnectState = 0x0
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  818): ELAPSED_WAKEUP set : Alarm{3ecf2600 type 2 when 162135 com.android.systemui} when 162135
,D/KeyguardViewMediator( 1365): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/PhoneUtils( 1750): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1750): getCallState : 0
,D/PhoneUtils( 1750): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1365): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1365): doKeyguard: not showing because lockscreen is off
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1365): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1365): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1365): On Skip Timer : true
D/charger_monitor(  490): init target 500000
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 1976): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1365): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1365): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1365): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  818): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1365): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1365): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1976): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1365): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  818): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 174463833116; DSPS: 5815030; Offset : -3003818843
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  490): init target 500000
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1365): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1365): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1365): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1976): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1365): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1365): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
I/[SystemUI]BatterySaverHandler( 1365): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  818): battery changed pluggedType: 2
I/ClearcutLoggerApiImpl( 1732): disconnect managed GoogleApiClient
,V/AlarmManager(  818): ELAPSED_WAKEUP set : Alarm{3fc75e39 type 2 when 188125 com.google.android.gms} when 188125
,I/PhenotypeConfigurator( 1732): Scheduling Phenotype for one-off execution 3571 seconds from now (1450834066616)
,D/GetConfigurationSnapshotOperation( 1732): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1732): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1732): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  818): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
,I/System.out( 1732): propertyValue:false
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LocationManagerService(  818): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
I/System.out( 1732): propertyValue:false
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager(  818): android: cancelAsUser(2) by android
,I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
,V/AlarmManager(  818): ELAPSED_WAKEUP set : Alarm{f80f30 type 2 when 189931 android} when 189931
,D/LocationManagerService(  818): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  818): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  818): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  818): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  818): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  818): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 194464550556; DSPS: 6470414; Offset : -3003834163
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1365): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1365): called onTimeUpdated()
I/[SystemUI]Clock( 1365): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1365): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 214465231537; DSPS: 7125796; Offset : -3003824125
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 234465906374; DSPS: 7781178; Offset : -3003820883
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  490): init target 500000
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1365): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1365): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1365): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/[SystemUI]LGPowerUI( 1365): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1365): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
I/[SystemUI]BatterySaverHandler( 1365): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1976): Disconnected process message: 10, size: 0
W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  818): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 254466586626; DSPS: 8436560; Offset : -3003811836
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1365): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1365): called onTimeUpdated()
I/[SystemUI]Clock( 1365): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1365): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 274467260420; DSPS: 9091942; Offset : -3003809428
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 294468121038; DSPS: 9747331; Offset : -3003833976
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  490): init target 500000
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1365): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1365): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1365): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1976): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1365): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1365): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/[SystemUI]BatterySaverHandler( 1365): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  818): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 314468790561; DSPS: 10402713; Offset : -3003835554
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1365): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1365): called onTimeUpdated()
I/[SystemUI]Clock( 1365): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1365): handleTimeUpdate
D/PowerManagerServiceEx(  818): acquireWakeLockInternal: lock=67613646, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=818
,I/ActivityManager(  818): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7659 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/DigitalAppWidgetProvider( 7659): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7659): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@44db0a7
I/ActivityManager(  818): Killing 7214:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
D/PowerManagerServiceEx(  818): releaseWakeLockInternal: lock=67613646 [*alarm*], flags=0x0
W/libprocessgroup(  818): failed to open /acct/uid_10006/pid_7214/cgroup.procs: No such file or directory
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 334469554148; DSPS: 11058098; Offset : -3003835400
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6076): Connected to the server!
I/jxcore-log( 6076): 
,I/chromium( 6076): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/LocationManagerService(  818): remove 1cb169e8
D/LocationManagerService(  818): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  818): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  818): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  818): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  818): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 354470586432; DSPS: 11713491; Offset : -3003810119
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  490): init target 500000
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1365): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1365): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1365): On Skip Timer : true
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/HeadsetStateMachine( 1976): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1365): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1365): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/[SystemUI]BatterySaverHandler( 1365): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  818): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 374471248039; DSPS: 12368873; Offset : -3003819639
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1365): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1365): called onTimeUpdated()
I/[SystemUI]Clock( 1365): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1365): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 394471936417; DSPS: 13024256; Offset : -3003833217
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1365): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1365): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1365): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1365): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1365): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1365): On Skip Timer : true
D/HeadsetStateMachine( 1976): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1365): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1365): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/[SystemUI]BatterySaverHandler( 1365): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  818): battery changed pluggedType: 2
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 414472699378; DSPS: 13679641; Offset : -3003833403
,D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1365): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1365): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1365): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 1976): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1365): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1365): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/[SystemUI]BatterySaverHandler( 1365): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  818): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1365): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1365): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1365): On Skip Timer : true
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 434473448954; DSPS: 14335025; Offset : -3003816223
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1365): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1365): called onTimeUpdated()
I/[SystemUI]Clock( 1365): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1365): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 454474198113; DSPS: 14990410; Offset : -3003829691
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6076): --- start :testSendData2.js---
I/jxcore-log( 6076): 
,E/jxcore  ( 6076): Error!: self.tests[testData.testName] is not a constructor
E/jxcore  ( 6076): Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"146","_columnNumber":"24","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:146:24"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onevent","_lineNumber":"254","_columnNumber":"5","_msg":"    at Socket.prototype.onevent@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:254:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onpacket","_lineNumber":"212","_columnNumber":"7","_msg":"    at Socket.prototype.onpacket@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:212:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondecoded","_lineNumber":"301","_columnNumber":"3","_msg":"    at Manager.prototype.ondecoded@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:301:3"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"}]
I/chromium( 6076): [INFO:CONSOLE(63)] "logCallback --- start :testSendData2.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 474474874459; DSPS: 15645792; Offset : -3003824915
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1365): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1365): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1365): On Skip Timer : true
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1976): Disconnected process message: 10, size: 0
,D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1365): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1365): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
I/[SystemUI]BatterySaverHandler( 1365): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  818): battery changed pluggedType: 2
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 494475638514; DSPS: 16301177; Offset : -3003823669
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1365): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1365): called onTimeUpdated()
I/[SystemUI]Clock( 1365): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1365): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 514476361007; DSPS: 16956561; Offset : -3003833936
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6076): Connected to the server!
I/jxcore-log( 6076): 
,I/chromium( 6076): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 534477103239; DSPS: 17611945; Offset : -3003824073
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1365): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1365): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1365): On Skip Timer : true
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1976): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1365): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1365): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
I/[SystemUI]BatterySaverHandler( 1365): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  818): battery changed pluggedType: 2
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 554477886825; DSPS: 18267331; Offset : -3003835637
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1365): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1365): called onTimeUpdated()
I/[SystemUI]Clock( 1365): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1365): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 574478554421; DSPS: 18922712; Offset : -3003806905
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6076): teardown
I/jxcore-log( 6076): 
,E/jxcore  ( 6076): Error!: self.currentTest is undefined
E/jxcore  ( 6076): Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"159","_columnNumber":"5","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:159:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onevent","_lineNumber":"254","_columnNumber":"5","_msg":"    at Socket.prototype.onevent@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:254:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onpacket","_lineNumber":"212","_columnNumber":"7","_msg":"    at Socket.prototype.onpacket@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:212:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondecoded","_lineNumber":"301","_columnNumber":"3","_msg":"    at Manager.prototype.ondecoded@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:301:3"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"}]
I/chromium( 6076): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 594479230559; DSPS: 19578095; Offset : -3003832568
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1365): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1365): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1365): On Skip Timer : true
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1365): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1365): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
D/HeadsetStateMachine( 1976): Disconnected process message: 10, size: 0
W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  818): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1365): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 614479916385; DSPS: 20233477; Offset : -3003818467
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1365): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1365): called onTimeUpdated()
I/[SystemUI]Clock( 1365): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1365): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 634480890388; DSPS: 20888869; Offset : -3003821522
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 654481536891; DSPS: 21544250; Offset : -3003815419
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6076): Connected to the server!
I/jxcore-log( 6076): 
,I/chromium( 6076): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1365): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1365): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1365): On Skip Timer : true
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1976): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1365): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1365): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1365): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  818): battery changed pluggedType: 2
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 674482314019; DSPS: 22199636; Offset : -3003831383
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1365): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1365): called onTimeUpdated()
I/[SystemUI]Clock( 1365): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1365): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 694482987604; DSPS: 22855018; Offset : -3003829498
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 714483711503; DSPS: 23510401; Offset : -3003807372
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1365): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1365): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1365): On Skip Timer : true
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1976): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1365): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1365): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/[SystemUI]BatterySaverHandler( 1365): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  818): battery changed pluggedType: 2
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 734484495870; DSPS: 24165787; Offset : -3003816436
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1365): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1365): called onTimeUpdated()
I/[SystemUI]Clock( 1365): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1365): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 754485249197; DSPS: 24821172; Offset : -3003826466
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 774486008720; DSPS: 25476557; Offset : -3003829466
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1365): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1365): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1365): On Skip Timer : true
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 794486683243; DSPS: 26131939; Offset : -3003826511
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1365): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1365): called onTimeUpdated()
I/[SystemUI]Clock( 1365): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1365): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 814487348028; DSPS: 26787321; Offset : -3003833373
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 834488097135; DSPS: 27442705; Offset : -3003816272
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1365): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1365): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1365): On Skip Timer : true
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 854488774054; DSPS: 28098087; Offset : -3003810844
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1365): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1365): called onTimeUpdated()
I/[SystemUI]Clock( 1365): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1365): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 874489532484; DSPS: 28753472; Offset : -3003815276
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 894490385445; DSPS: 29408860; Offset : -3003816989
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1365): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1365): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1365): On Skip Timer : true
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 914491166271; DSPS: 30064245; Offset : -3003799571
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1365): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1365): called onTimeUpdated()
I/[SystemUI]Clock( 1365): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1365): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 934494557461; DSPS: 30719717; Offset : -3003826245
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  818): acquireWakeLockInternal: lock=67613646, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=818
,V/AlarmManager(  818): ELAPSED_WAKEUP set : Alarm{2f1d312e type 2 when 952993 com.android.bluetooth} when 952993
D/PowerManagerServiceEx(  818): releaseWakeLockInternal: lock=67613646 [*alarm*], flags=0x0
,W/bt-smp  ( 1976): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1976): Plain text(LSB ~ MSB) = d5 ae 44 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 1976): Encrypted text(LSB ~ MSB) = f8 24 08 eb 08 51 e9 65 5f c1 25 14 b2 5c 55 c0 
W/bt-btm  ( 1976): Stopping oneshot timer
D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time(  818): tsOffsetIs: Apps: 954495149432; DSPS: 31375096; Offset : -3003813952
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1365): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1365): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1365): On Skip Timer : true
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1976): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1365): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1365): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
I/[SystemUI]BatterySaverHandler( 1365): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  818): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 974495833174; DSPS: 32030479; Offset : -3003832115
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1365): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1365): called onTimeUpdated()
I/[SystemUI]Clock( 1365): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1365): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 994496504626; DSPS: 32685861; Offset : -3003831867
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  818): acquireWakeLockInternal: lock=67613646, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=818
,V/AlarmManager(  818): ELAPSED_WAKEUP set : Alarm{2bfe24cf type 2 when 1012920 com.google.android.gms} when 1012920
D/PowerManagerServiceEx(  818): releaseWakeLockInternal: lock=67613646 [*alarm*], flags=0x0
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1014497174358; DSPS: 33341243; Offset : -3003833444
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1365): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1365): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1365): On Skip Timer : true
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1034497849558; DSPS: 33996625; Offset : -3003829968
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1365): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1365): called onTimeUpdated()
I/[SystemUI]Clock( 1365): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1365): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1054498572987; DSPS: 34652008; Offset : -3003808262
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1074499347251; DSPS: 35307394; Offset : -3003827220
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1365): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1365): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1365): On Skip Timer : true
D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1094500343859; DSPS: 35962786; Offset : -3003807279
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1365): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1365): called onTimeUpdated()
I/[SystemUI]Clock( 1365): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1365): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1114501092444; DSPS: 36618171; Offset : -3003821738
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1365): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1365): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1365): On Skip Timer : true
D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1976): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1365): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1365): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
I/[SystemUI]BatterySaverHandler( 1365): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  818): battery changed pluggedType: 2
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1134501769208; DSPS: 37273553; Offset : -3003816412
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1365): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1365): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1365): On Skip Timer : true
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1365): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1365): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
D/HeadsetStateMachine( 1976): Disconnected process message: 10, size: 0
W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  818): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1365): onReceive = android.intent.action.BATTERY_CHANGED
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1154502449825; DSPS: 37928935; Offset : -3003807390
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1365): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1365): called onTimeUpdated()
I/[SystemUI]Clock( 1365): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1365): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1174503124921; DSPS: 38584318; Offset : -3003833808
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1194503785279; DSPS: 39239699; Offset : -3003813797
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  818): acquireWakeLockInternal: lock=67613646, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=818
,V/AlarmManager(  818): ELAPSED_WAKEUP set : Alarm{3186ee5c type 2 when 1208842 android} when 1208842
D/PowerManagerServiceEx(  818): releaseWakeLockInternal: lock=67613646 [*alarm*], flags=0x0
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1365): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1365): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1365): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/NotificationManager(  818): android: cancelAsUser(-1548111331) by android
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
,D/LEDHandler( 1802): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1976): Disconnected process message: 10, size: 0
W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1365): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1365): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
D/WifiController(  818): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1365): onReceive = android.intent.action.BATTERY_CHANGED
I/NotificationManager(  818): android: cancelAsUser(2145784878) by android
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1214504547354; DSPS: 39895084; Offset : -3003815054
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1365): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1365): called onTimeUpdated()
I/[SystemUI]Clock( 1365): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1365): handleTimeUpdate
I/UsageStatsService(  818): User[0] Flushing usage stats to disk
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1234505303336; DSPS: 40550469; Offset : -3003822166
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  818): acquireWakeLockInternal: lock=67613646, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=818
,V/AlarmManager(  818): ELAPSED_WAKEUP set : Alarm{23a5ce92 type 2 when 1239787 android} when 1239787
I/DigitalAppWidgetProvider( 7659): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7659): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@44db0a7
D/PowerManagerServiceEx(  818): releaseWakeLockInternal: lock=67613646 [*alarm*], flags=0x0
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1254506071922; DSPS: 41205854; Offset : -3003816312
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1365): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1365): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1365): On Skip Timer : true
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1274506734465; DSPS: 41861236; Offset : -3003825234
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1365): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1365): called onTimeUpdated()
I/[SystemUI]Clock( 1365): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1365): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1294507511491; DSPS: 42516621; Offset : -3003812788
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1314508148774; DSPS: 43172002; Offset : -3003815176
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1365): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1365): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1365): On Skip Timer : true
D/HeadsetStateMachine( 1976): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
I/[SystemUI]LGPowerUI( 1365): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1365): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
I/[SystemUI]BatterySaverHandler( 1365): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  818): battery changed pluggedType: 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1334509023506; DSPS: 43827391; Offset : -3003825194
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1365): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1365): called onTimeUpdated()
I/[SystemUI]Clock( 1365): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1365): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1354509863551; DSPS: 44482778; Offset : -3003809228
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1374510675888; DSPS: 45138165; Offset : -3003820605
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1365): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1365): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1365): On Skip Timer : true
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1394511427547; DSPS: 45793550; Offset : -3003831912
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1365): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1365): called onTimeUpdated()
I/[SystemUI]Clock( 1365): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1365): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1414512179883; DSPS: 46448934; Offset : -3003812543
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1434512925448; DSPS: 47104319; Offset : -3003829189
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1365): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1365): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1365): On Skip Timer : true
D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1454513681430; DSPS: 47759704; Offset : -3003836797
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1365): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1365): called onTimeUpdated()
I/[SystemUI]Clock( 1365): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1365): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1474514437516; DSPS: 48415088; Offset : -3003812873
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1494515100268; DSPS: 49070470; Offset : -3003821247
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1365): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1365): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1365): On Skip Timer : true
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1514515819218; DSPS: 49725854; Offset : -3003835058
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1365): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1365): called onTimeUpdated()
I/[SystemUI]Clock( 1365): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1365): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1534516651295; DSPS: 50381241; Offset : -3003826903
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1554517313162; DSPS: 51036623; Offset : -3003836397
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1365): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1365): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1365): On Skip Timer : true
D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1574517989717; DSPS: 51692005; Offset : -3003831359
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1365): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1365): called onTimeUpdated()
I/[SystemUI]Clock( 1365): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1365): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1594518760177; DSPS: 52347390; Offset : -3003823578
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1614519394961; DSPS: 53002771; Offset : -3003829689
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1365): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1365): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1365): On Skip Timer : true
D/HeadsetStateMachine( 1976): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 271, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
I/[SystemUI]LGPowerUI( 1365): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1365): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 271
I/[SystemUI]BatterySaverHandler( 1365): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  818): battery changed pluggedType: 2
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1634520287247; DSPS: 53658160; Offset : -3003822282
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1365): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1365): called onTimeUpdated()
I/[SystemUI]Clock( 1365): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1365): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1654521050312; DSPS: 54313545; Offset : -3003822835
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1674521704158; DSPS: 54968926; Offset : -3003809233
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1365): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1365): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1365): On Skip Timer : true
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1694522376441; DSPS: 55624308; Offset : -3003808363
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1365): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1365): called onTimeUpdated()
I/[SystemUI]Clock( 1365): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1365): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1714523031850; DSPS: 56279690; Offset : -3003824678
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1734523781270; DSPS: 56935075; Offset : -3003837808
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1365): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1365): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1365): On Skip Timer : true
D/HeadsetStateMachine( 1976): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 271, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
I/[SystemUI]LGPowerUI( 1365): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1365): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 271
I/[SystemUI]BatterySaverHandler( 1365): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  818): battery changed pluggedType: 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1754524468241; DSPS: 57590457; Offset : -3003822170
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1365): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1365): called onTimeUpdated()
I/[SystemUI]Clock( 1365): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1365): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1774525141256; DSPS: 58245839; Offset : -3003820621
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1794525887446; DSPS: 58901223; Offset : -3003806670
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1365): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1365): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1365): On Skip Timer : true
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1976): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 271, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
I/[SystemUI]LGPowerUI( 1365): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1365): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 271
I/[SystemUI]BatterySaverHandler( 1365): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  818): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  818): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  818): battery changed pluggedType: 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1814526644522; DSPS: 59556608; Offset : -3003812795
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1365): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1365): called onTimeUpdated()
I/[SystemUI]Clock( 1365): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1365): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1834527302482; DSPS: 60211990; Offset : -3003826429
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  818): acquireWakeLockInternal: lock=67613646, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=818
,V/AlarmManager(  818): ELAPSED_WAKEUP set : Alarm{d85a460 type 2 when 1853136 com.android.bluetooth} when 1853136
,W/bt-smp  ( 1976): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1976): Plain text(LSB ~ MSB) = fc d0 55 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 1976): Encrypted text(LSB ~ MSB) = 50 79 8a 7c 22 b8 0a 5c 04 29 e6 a8 c4 ea a9 3c 
W/bt-btm  ( 1976): Stopping oneshot timer
I/ProcessStatsService(  818): Prepared write state in 20ms
,D/PowerManagerServiceEx(  818): releaseWakeLockInternal: lock=67613646 [*alarm*], flags=0x0
,I/ProcessStatsService(  818): Prepared write state in 16ms
,I/ProcessStatsService(  818): Prepared write state in 33ms
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1854528076953; DSPS: 60867375; Offset : -3003815159
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,V/AlarmManager(  818): RTC_WAKEUP set : Alarm{3c3c6d19 type 0 when 1450835319367 com.google.android.gms} when 1450835319367
,I/EventLogService( 4177): Aggregate from 1450833989743 (log), 1450833519251 (data)
,D/LocationManagerService(  818): getAllProviders()=[passive, gps, network]
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  279): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  279): res_queryN name = xxxxx succeed
,I/System.out( 1732): propertyValue:false
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager(  818): android: cancelAsUser(2) by android
,I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
,I/art     (  818): Explicit concurrent mark sweep GC freed 88732(4MB) AllocSpace objects, 17(442KB) LOS objects, 33% free, 23MB/35MB, paused 2.711ms total 188.986ms
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1365): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1365): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1365): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1365): On Skip Timer : true
D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1874528813561; DSPS: 61522759; Offset : -3003810686
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1365): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1365): called onTimeUpdated()
I/[SystemUI]Clock( 1365): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
I/[SystemUI]DateView( 1365): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1365): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  818): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  818): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  818): tsOffsetIs: Apps: 1894529559230; DSPS: 62178144; Offset : -3003827800
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 8015): 
D/AndroidRuntime( 8015): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8015): CheckJNI is OFF
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
D/AndroidRuntime( 8015): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  818): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  818): Killing 6076:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
W/PackageSettings(  818): Skipping PackageSetting{3c1e0f46 com.example.hello/10317} due to missing metadata
I/WindowState(  818): WIN DEATH: Window{2b2f30e u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  818): Focus left window: Window{2b2f30e u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  818): Window went away: Window{2b2f30e u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  818):   Force finishing activity ActivityRecord{3419b5a u0 com.test.thalitest/.MainActivity t220}
V/ActivityManager(  818): Display changed displayId=0
D/DSDPConnection( 1750): Display #0 changed.
W/ActivityManager(  818): Spurious death for ProcessRecord{2c4e36af 6076:com.test.thalitest/u0a316}, curProc for 6076: null
I/ActivityManager(  818): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/art     ( 1939): Explicit concurrent mark sweep GC freed 9543(535KB) AllocSpace objects, 3(72KB) LOS objects, 40% free, 12MB/21MB, paused 1.616ms total 73.977ms
I/QCNEJ   ( 1838): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/InputReader(  818): Reconfiguring input devices.  changes=0x00000010
W/System.err( 3596): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
D/KeyguardModel( 1365): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
W/GeofencerStateMachine( 1732): Ignoring removeGeofence because network location is disabled.
W/System.err( 3596): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3596): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3596): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3596): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3596): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3596): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3596): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3596): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3596): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3596): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3596): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/art     ( 4177): Explicit concurrent mark sweep GC freed 22063(1296KB) AllocSpace objects, 6(96KB) LOS objects, 24% free, 14MB/19MB, paused 934us total 107.352ms
I/ActivityManager(  818): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8056 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1876): [Launcher.java:5203:onStart()]onStart
I/[SystemUI]QSlideListController( 1365): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 1876): [Launcher.java:776:onResume()]onResume
I/[LGHome]EVENT( 1876): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
I/art     (  818): Explicit concurrent mark sweep GC freed 9395(774KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 8.790ms total 213.398ms
I/[LGHome]LGActivityUtil( 1876): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/art     (  818): WaitForGcToComplete blocked for 127.684ms for cause Explicit
I/[LGHome]EVENT( 1876): [Launcher.java:929:onResume()]onResume end
I/Activity( 1876): Activity.onPostResume() called 
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1365): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1365): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
W/ResourcesManager( 8056): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8056): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8056): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1876): [Launcher.java:986:onPause()]onPause
D/KeyguardModel( 1365): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1365): createShortcutInfo...
D/KeyguardModel( 1365): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1365): createShortcutInfo...
W/ResourceType( 1365): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1365): Failure retrieving resources for com.android.mms: Resource ID #0x0
W/[LGHome]LGWallpaperInfo( 1876): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1876): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
D/KeyguardModel( 1365): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1365): createShortcutInfo...
D/administrator(  818): Handling package changes for user 0
I/SystemUI[Framework](  818): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
D/InputDispatcher(  818): Focus entered window: Window{19a860df u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/PhoneWindowManagerEx(  818): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  818): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  818): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  818): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3513898d,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  818): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  818): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  818): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  818): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  818): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  818): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3513898d,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  818): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
W/ResourcesManager( 1365): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1365): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1365): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1365): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1365): createShortcutInfo...
W/ResourceType( 1365): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1365): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1365): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1365): createShortcutInfo...
I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/KeyguardModel( 1365): handleShortcutListChanged...
I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
D/KeyguardModel( 1365): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1365): createShortcutInfo...
D/KeyguardModel( 1365): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1365): createShortcutInfo...
W/ResourceType( 1365): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1365): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/[LGHome]EVENT( 1876): [Launcher.java:5214:onStop()]onStop
D/KeyguardModel( 1365): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1365): createShortcutInfo...
W/ResourceType( 1365): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1365): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1365): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1365): createShortcutInfo...
I/[LGHome]EVENT( 1876): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
W/ResourceType( 1365): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1365): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/PhoneWindow( 1876): [setNavigationBarColor] color=0x 0
D/KeyguardModel( 1365): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1365): createShortcutInfo...
D/KeyguardModel( 1365): handleShortcutListChanged...
I/LGEmail ( 8056): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 8056): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/art     (  818): Explicit concurrent mark sweep GC freed 4117(236KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.086ms total 265.816ms
W/InputMethodManagerService(  818): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  818): Got RemoteException sending setActive(false) notification to pid 6076 uid 10316
I/NotificationService(  818): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  818): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/AndroidRuntime( 8015): Shutting down VM
D/JobSchedulerService(  818): Receieved: android.intent.action.PACKAGE_REMOVED
I/PackageChangeReceiver( 8056): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
D/PhoneStatusBar( 1365): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/TaskPersister(  818): removeObsoleteFile: deleting file=220_task.xml
D/PhoneStatusBar( 1365): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1365): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1365):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1365): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
D/AppUp4:PreloadHelper( 7351): added Exclude : com.test.thalitest
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/ActivityManager(  818): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8080 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  818): Killing 7176:com.google.android.talk/u0a61 (adj 15): empty #11
W/IInputConnectionWrapper( 1876): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1579): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1876): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1876): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
W/libprocessgroup(  818): failed to open /acct/uid_10061/pid_7176/cgroup.procs: No such file or directory
D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1876): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/Timeline(  818): Timeline: Activity_windows_visible id: ActivityRecord{33d53f u0 com.lge.launcher2/.Launcher t219} time:1906628
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
W/ResourcesManager(  818): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/ResourceType(  818): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
W/ResourcesManager( 8080): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.

```
