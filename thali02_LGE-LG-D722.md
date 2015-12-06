#### Test 502422853393492_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
D/Alarms  ( 3503):  minTime  = 0
D/Alarms  ( 3503):  -- OK multi -- 0
E/jeny.kim( 3503): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 3503): [setNextAlert]setNextAlert temp_AlarmLinkText + 
I/CommonUtil( 3503): BUILD Operator: OPEN
D/Alarms  ( 3503): broadcastToWidgetProvider : false
D/Alarms  ( 3503): Enter formatDayAndTime(final Context context, long timeInMiliSec)
V/SettingsProvider(  850): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
--------- beginning of system
W/BackupManagerService(  850): dataChanged but no participant pkg='com.android.providers.settings' uid=10010
D/CommonUtil( 3503): Enter deleteUnnecessaryToneItem() enter excepted tone uri value is null, preferparent value is  ALARM
D/CommonUtil( 3503): deleteUnnecessaryToneItem() -> Alarm Surviv Count is 0
D/CommonUtil( 3503): Exit deleteUnnecessaryToneItem()
I/CommonUtil( 3503): BUILD Country: EU
I/TimerReceiver( 3503): onReceiveIntent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.lge.clock/.timer.TimerReceiver (has extras) }
D/TimerReceiver( 3503): onReceive() : android.intent.action.BOOT_COMPLETED
I/TimerReceiver( 3503): setTimerDone
D/TimerObj( 3503): --------------------- getTimersFromSharedPrefs
V/TimerObj( 3503): --------------------- timers list is empty
,I/ActivityManager(  850): Start proc com.lge.appbox.client:SingleBinaryService for broadcast com.lge.appbox.client/com.lge.appbox.singlebinary.SimChangeReceiver: pid=3536 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  850): Killing 3272:com.lge.eula/1000 (adj 15): empty #11
W/libprocessgroup(  850): failed to open /acct/uid_1000/pid_3272/cgroup.procs: No such file or directory
D/AppUp4:AppBoxApplication( 3536): AppBoxApplication onCreate()
D/AppUp4:SingleBinary( 3536): /cust/OPEN_EU/config/app-enabled-conf.json is selected!!
D/AppUp4:SingleBinary( 3536):  Starting isFingerChanged 
I/ActivityManager(  850): Start proc com.lge.appbox.client for content provider com.lge.appbox.client/com.lge.appbox.databases.AppBoxContentProvider: pid=3555 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/AppUp4:AppBoxCP( 3555): onCreate
W/AppUp4:DB( 3555):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 3555):  setFingerPrint start
I/AppUp4:DB( 3555):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 3555):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 3555):  SDK version = 0
I/AppUp4:DB( 3555):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 3555): AppBoxApplication onCreate()
D/AppUp4:SingleBinary( 3536):  The value of isFingerChanged null
D/AppUp4:SingleBinary( 3536): Device : jagnm
D/AppUp4:SingleBinary( 3536): First Boot - ignore boot completed
D/AppUp4:NTCodeSingleBinary( 3536): Starting isFingerChanged 
D/AppUp4:NTCodeSingleBinary( 3536): The value of isFingerChanged lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
D/AppUp4:SingleBinary( 3536): Device : jagnm
D/AppUp4:SingleBinary( 3536): Config file is not exist - nothing
I/ActivityManager(  850): Killing 3200:com.android.contacts/u0a18 (adj 15): empty #11
D/AndroidRuntime( 3553): 
D/AndroidRuntime( 3553): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3553): CheckJNI is OFF
W/libprocessgroup(  850): failed to open /acct/uid_10018/pid_3200/cgroup.procs: No such file or directory
I/AppUp4:SDKReflector( 3555): +myUserId : 0
D/AppUp4:BootUpPollingReceiver( 3555): onReceive on user ID : 0
V/AppUp4:FotaPlusService( 3555):  isFotaPlusTriedOnce : true
D/AppUp4:BootUpPollingReceiver( 3555): Starting getSdkVersion 
D/AppUp4:BootUpPollingReceiver( 3555): SDK version is : 0
D/AppUp4:BootUpPollingReceiver( 3555): currentSdkVersion : 0
D/AppUp4:BootUpPollingReceiver( 3555): isSdkVersionChanged : true
V/AppUp4:FotaPlusService( 3555):  setFotaPlusCompleted : false
D/AppUp4:BootUpPollingReceiver( 3555): isFotaPlusNeeded : true
D/AppUp4:BootUpPollingReceiver( 3555): Fota Plus already tried once, show notification
V/NotificationService(  850): enqueueNotificationInternal: pkg=com.lge.appbox.client id=22319582 notification=Notification(pri=0 contentView=null vibrate=default sound=default defaults=0x3 flags=0x2 color=0x00000000 vis=PRIVATE)
D/ZenLog  (  850): intercepted: 0|com.lge.appbox.client|22319582|null|10011,none
V/NotificationService(  850): pkg=com.lge.appbox.client canInterrupt=false intercept=true
I/NotificationServiceEx(  850): LED remove() : mLights=0|com.lge.appbox.client|22319582|null|10011
D/NotificationServiceEx(  850): updateLightListLocked :r=0|com.lge.appbox.client|22319582|null|10011, action=2
D/NotificationServiceEx(  850): notification=Notification(pri=0 contentView=null vibrate=default sound=default defaults=0x3 flags=0x2 color=0x00000000 vis=PRIVATE)
D/AppUp4:BootUpPollingReceiver( 3555): isFotaPlusRunning after : true
D/AppUp4:BootUpPollingReceiver( 3555):  installPreloadedValuePackIfNeeded 
D/AppUp4:BootUpPollingReceiver( 3555):  file is : /system/apps/bootup
D/AppUp4:BootUpPollingReceiver( 3555): file false
D/AppUp4:BootUpPollingReceiver( 3555): [BootUpPollingReceiver] No preload installation.
D/SmartCoverUpdateMonitor( 1339): onNotificationPosted() : StatusBarNotification(pkg=com.lge.appbox.client user=UserHandle{0} id=22319582 tag=null score=0 key=0|com.lge.appbox.client|22319582|null|10011: Notification(pri=0 contentView=com.lge.appbox.client/0x1090079 vibrate=default sound=default defaults=0x3 flags=0x2 color=0x00000000 vis=PRIVATE))
D/SmartCoverUpdateMonitor( 1339): onNotificationPosted() !qcn.isEnableToShowNotification()
D/AppUp4:dwnld( 3555): [removeAllIncompletedDownload] ... 
V/AppUp4:BootUpPollingReceiver( 3555): [BootUpPollingReceiver] start bootup Polling.
D/AppUp4  ( 3555): getUpdatePollingPeriod
D/AppUp4  ( 3555): getUpdatePollingPeriod
D/AppUp4:BackgroundPollingService ( 3555): register polling alarm when : 2015/12/10 21:31:58
D/AppUp4:LightWeightPollingService ( 3555):  [buildRemotePollingIntent]
D/AppUp4:LightWeightPollingService ( 3555): This means remote config is N, so skip it
I/ActivityManager(  850): Killing 3299:com.android.keychain/1000 (adj 15): empty #11
W/libprocessgroup(  850): failed to open /acct/uid_1000/pid_3299/cgroup.procs: No such file or directory
I/CalendarProvider2( 3458): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 3458): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  850): Killing 3225:com.lge.hiddenmenu/1000 (adj 15): empty #11
D/AndroidRuntime( 3553): Calling main entry com.android.commands.am.Am
W/libprocessgroup(  850): failed to open /acct/uid_1000/pid_3225/cgroup.procs: No such file or directory
I/ActivityManager(  850): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=3595 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  850): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/[SystemUI]PhoneStatusBar( 1383): updateMediaMetaData(false): mMediaMetadata = null
I/art     (  850): Explicit concurrent mark sweep GC freed 13149(648KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/33MB, paused 2.321ms total 138.842ms
D/ActivityManager(  850): setTaskToReturnTo : TaskRecord{2f89bec4 #220 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  850): setTaskToReturnTo : TaskRecord{2f89bec4 #220 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  850): AppWindowTokenEx init.. 
D/ContextHelper(  850): convertTheme. context->name=com.example.hello themeResourceId=16973833
D/InputDispatcher(  850): Focus left window: Window{22fdad6 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 3553): Shutting down VM
I/[LGHome]EVENT( 1885): [Launcher.java:986:onPause()]onPause
D/MmsConfig( 3140): isNotAllowedSms: currentUser:0
D/MmsConfig( 3140): isNotAllowedSms: UserHandle.myUserId():0
D/MmsConfig( 3140): isUserMode:false
D/SmsReceiverService( 3140): handleMessage isUserMode:false
D/SplitWindow(  850): check instance of lgWin Window{b5e452e u0 Starting com.example.hello}
W/ResourcesManager( 3140): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
V/SmsReceiverService( 3140): handleMessage action: android.intent.action.BOOT_COMPLETED error: 0
I/ActivityManager(  850): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3614 uid=10030 gids={50030, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/art     (  310): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 291us total 23.800ms
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 35.927ms
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 21.599ms
I/[LGHome]EVENT( 1885): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/WindowStateAnimator(  850): Starting window displayed
I/SystemUI[Framework](  850): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.example.hello
W/PhoneWindowManagerEx(  850): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  850): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  850): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  850): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3209674,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  850): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1383): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
I/[SystemUI]NavigationThemeResource( 1383): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1383):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1383): , Keyguard show=false, IME shown=false, Panel expanded=false
I/MicrophoneInputStream( 1945): mic_close com.google.android.apps.gsa.speech.audio.u@1c0232c0
V/AudioRecord( 1945): stop()
D/AudioRecord( 1945): AudioRecord->stop()
V/AudioFlinger(  286): RecordHandle::stop()
V/AudioFlinger(  286): RecordThread::stop
I/[LGHome]EVENT( 1885): [Launcher.java:5214:onStop()]onStop
I/HotwordDetector( 1945): Closing mic
V/AudioFlinger(  286): Record stopped OK
V/AudioPolicyManager(  286): stopInput() input 17
V/AudioPolicyService(  286): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  286): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  286): AudioCommandThread() waking up
V/AudioPolicyService(  286): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  286): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  286): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  286): ThreadBase::setParameters() routing=0
V/AudioFlinger(  286): sendConfigEvent_l() num events 1 event 2
W/ActivityThread( 1885): Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 1885): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 1885): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3407)
W/ActivityThread( 1885): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3496)
W/ActivityThread( 1885): 	at android.app.ActivityThread.access$1100(ActivityThread.java:155)
W/ActivityThread( 1885): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1352)
W/ActivityThread( 1885): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ActivityThread( 1885): 	at android.os.Looper.loop(Looper.java:135)
W/ActivityThread( 1885): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/ActivityThread( 1885): 	at java.lang.reflect.Method.invoke(Native Method)
W/ActivityThread( 1885): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ActivityThread( 1885): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/ActivityThread( 1885): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/BarTransitions( 1383): draw background and invalidate : color = 11000000
V/AudioFlinger(  286): processConfigEvents_l() remaining events 1
V/AudioFlinger(  286): processConfigEvents_l() DONE thread 0xb42d9000
D/audio_hw_primary(  286): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
D/BarTransitions( 1383): draw background and invalidate : color = 16161616
W/ResourcesManager( 3595): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/ContextHelper( 3614): convertTheme. context->name=com.example.hello themeResourceId=16973833
,V/audio_hw_primary(  286): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  286): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  286): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  286): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  286): disable_audio_route: exit
E/audio_hw_primary(  286): disable_snd_device: enter 144
D/hardware_info(  286): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  286): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  286): stop_input_stream: exit: status(0)
V/audio_hw_primary(  286): in_standby: exit:  status(0)
V/AudioFlinger(  286): RecordThread: loop stopping
V/AudioPolicyService(  286): AudioCommandThread() going to sleep
V/AudioPolicyManager(  286): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  286): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  286): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  286): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  286): AudioCommandThread() waking up
V/AudioPolicyService(  286): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  286): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  286): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  286): AudioCommandThread() going to sleep
V/AudioPolicyService(  286): AudioCommandThread() waking up
V/AudioPolicyService(  286): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  286): setParameters(): io 17, keyvalue hotword_active=0, calling pid 286
V/AudioFlinger(  286): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  286): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  286): RecordThread: loop starting
V/AudioFlinger(  286): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  286): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  286): in_set_parameters: exit: status(0)
V/AudioFlinger(  286): processConfigEvents_l() DONE thread 0xb42d9000
V/AudioFlinger(  286): RecordThread: loop stopping
V/AudioPolicyService(  286): AudioCommandThread() going to sleep
V/AudioRecord( 1945): stop()
I/ActivityManager(  850): Activity reported stop, but no longer stopping: ActivityRecord{2f2a5d24 u0 com.lge.launcher2/.Launcher t219}
V/AudioRecord( 1945): stop()
V/AudioRecord( 1945): stop()
V/AudioFlinger(  286): releasing 16 from 1945 for -1
V/AudioFlinger(  286):  decremented refcount to 0
V/AudioFlinger(  286): purging stale effects
V/AudioFlinger(  286): RecordHandle::stop()
V/AudioFlinger(  286): RecordThread::stop
V/AudioPolicyManager(  286): releaseInput() 17
V/AudioPolicyManager(  286): closeInput(17)
V/AudioFlinger(  286): closeInput() 17
V/AudioSystem(  286): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1383): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  286): ThreadBase::exit
V/AudioSystem( 2686): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  286): RecordThread: loop starting
V/AudioSystem( 3140): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  286): RecordThread 0xb42d9000 exiting
V/AudioSystem(  850): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  286): adev_close_input_stream: enter:stream_handle(0xb4036520)
D/audio_hw_primary(  286): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  286): in_standby: exit:  status(0)
V/AudioPolicyService(  286): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  286): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  286): AudioCommandThread() waking up
V/AudioPolicyService(  286): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  286): AudioCommandThread() going to sleep
V/AudioPolicyManager(  286): releaseInput() exit
V/AudioFlinger(  286): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  286): removeClient_l() pid 1945, calling pid 286
V/AudioSystem( 1945): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1758): ioConfigChanged() event 4, ioHandle 17
I/HotwordRecognitionRnr( 1945): Stopping hotword detection.
I/HotwordRecognitionRnr( 1945): Hotword detection finished
D/CalendarApplication( 3595): CalendarApplication.onCreate()
I/WebViewFactory( 3614): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
D/PreferenceKeysParser( 3595): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 3595): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@38d36f2f, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@b40d93c, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@d34f6c5, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@241b481a, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@db1cf4b, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@20e04d28, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@2bf33a41, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@2195cbe6, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@acc1527, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@a8113d4, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@36f8397d, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3ce2c072, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@d5adcc3, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@20c59940, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@3053f079, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@1d9871be, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@384821f, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@220b096c, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@111a1b35, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@3c65ebca, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@2d79213b, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@33555058, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@15de35b1, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@3bdefa96, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@144e9617, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@3fb1a04, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@16ef7bed, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@2082a22, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@129c7cb3, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@11d270, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@2854e9e9, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@1ea2c66e, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@ad8310f, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@3d99a59c, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@3d893ba5, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@a38db7a, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2770cf2b, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@10697f88, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@cf6ed21, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@9e93546, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@ab3307, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@30db0c34, lg_pr
D/GeneralPreferenceUtils( 3595): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 3595): [init]
I/Config  ( 3595): LGCalendar ver.4.40.17
I/Config  ( 3595): start check model
I/Config  ( 3595): start check native_ca
I/Config  ( 3595): Config Operator=OPEN, Country=EU
D/Config  ( 3595): [setDefaultValuesToPref]
D/Config  ( 3595): [parseProfiles]
D/ProfilesParser( 3595): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 3595): [debug_displayParseInfos] profile.operator = null
D/Config  ( 3595): [updateProfiletoCountryInfo]
D/GeneralPreference( 3595): [checkAndMigrateOldPreference]
I/LibraryLoader( 3614): Time to load native libraries: 2 ms (timestamps 9847-9849)
I/LibraryLoader( 3614): Expected native library version number "",actual native library version number ""
D/AlertReceiver( 3595): onReceive: a=android.intent.action.BOOT_COMPLETED Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.calendar/.alerts.AlertReceiver (has extras) }
I/InitNotificationRingtoneService( 3595): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 3595): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
V/WebViewChromiumFactoryProvider( 3614): Binding Chromium to main looper Looper (main, tid 1) {241b481a}
I/LibraryLoader( 3614): Expected native library version number "",actual native library version number ""
I/chromium( 3614): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/ActivityManager(  850): Start proc com.android.settings for broadcast com.android.settings/.lockscreen.LockSettingsReceiver: pid=3643 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/BrowserStartupController( 3614): Initializing chromium process, singleProcess=true
W/art     ( 3614): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3614): ApplicationContext is null in ApplicationStatus
W/chromium( 3614): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 3614): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3614): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3614): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3614): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 3614): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 3614): Build Date: 03/02/15 Mon
I/Adreno-EGL( 3614): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 3614): Remote Branch: 
I/Adreno-EGL( 3614): Local Patches: 
I/Adreno-EGL( 3614): Reconstruct Branch: 
I/AlertUtils( 3595): [getCalendarNotiSoundURIFromCursor] getCount()= 21
W/ResourcesManager( 3643): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3643): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 3643): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 3643): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 3643): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/AlertUtils( 3595): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 3595): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 3595): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 3595): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 3595): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 3595): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 3595): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 3595): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 3595): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 3595): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 3595): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 3595): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
V/AudioPolicyService(  286): registerClient() client 0xb3c2b500, uid 10030
D/BluetoothManagerService(  850): Message: 20
D/BluetoothManagerService(  850): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@124e63bf:true
I/AlertUtils( 3595): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
D/BluetoothAdapter( 3614): 176231380: getState() :  mService = null. Returning STATE_OFF
I/AlertUtils( 3595): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 3595): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3595): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/IndexDatabaseHelper( 3643): Using schema version: 115
I/IndexDatabaseHelper( 3643): Index is fine
I/AlertUtils( 3595): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 3595): End InitializeAlertRingtoneService.onHandleIntent
,D/UsbSettingsReceiver( 3643): [AUTORUN] onReceive() : action = android.intent.action.BOOT_COMPLETED
,D/UsbSettingsReceiver( 3643): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 3643): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 3643): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 3643): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 3643): [AUTORUN] setTetherStatus() : status=false
D/UsbSettingsReceiver( 3643): [AUTORUN] onReceive() : android.intent.action.BOOT_COMPLETED
D/UsbSettingsReceiver( 3643): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 3643): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 3643): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,W/art     ( 3614): Attempt to remove local handle scope entry from IRT, ignoring
D/StoreModeReceiver( 3643): intent.getAction() : android.intent.action.BOOT_COMPLETED
D/StoreModeReceiver( 3643): sim state :null
D/StoreModeReceiver( 3643): Back LED don't supported.
V/SettingsProvider(  850): call_put(system:emotional_led_back_led=0) for 0 calling package = com.android.settings
,V/SettingsProvider(  850): call_put(system:emotional_led_back_incoming_call=0) for 0 calling package = com.android.settings
W/AwContents( 3614): onDetachedFromWindow called when already detached. Ignoring
V/SettingsProvider(  850): call_put(system:emotional_led_back_alarm=0) for 0 calling package = com.android.settings
V/SettingsProvider(  850): call_put(system:emotional_led_back_missed_call=0) for 0 calling package = com.android.settings
V/SettingsProvider(  850): call_put(system:emotional_led_back_missed_messages=0) for 0 calling package = com.android.settings
V/SettingsProvider(  850): call_put(system:emotional_led_back_missed_emails=0) for 0 calling package = com.android.settings
V/SettingsProvider(  850): call_put(system:emotional_led_back_calendar_noti=0) for 0 calling package = com.android.settings
V/SettingsProvider(  850): call_put(system:emotional_led_back_voice_recording=0) for 0 calling package = com.android.settings
V/SettingsProvider(  850): call_put(system:emotional_led_back_camera_timer_noti=0) for 0 calling package = com.android.settings
V/SettingsProvider(  850): call_put(system:emotional_led_back_camera_face_detecting_noti=0) for 0 calling package = com.android.settings
V/SettingsProvider(  850): call_put(system:notification_light_pulse_back=0) for 0 calling package = com.android.settings
,D/StoreModeReceiver( 3643): SystemProperty Default brightness value [0-255] : 143
D/StoreModeReceiver( 3643): Default brightness[0-255] : 143
W/ResourcesManager( 3643): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/StoreModeReceiver( 3643): Default Screen off timeout value : 30000
D/StoreModeReceiver( 3643): SystemProperty Default brightness Mode value[true/false] : false
D/StoreModeReceiver( 3643): BRIGHTNESS_MODE - 0
D/StoreModeReceiver( 3643): Default brightness Mode [0/1] : 0
D/StoreModeReceiver( 3643): Default NIGHT_MODE : 0
D/StoreModeReceiver( 3643): Set MaxBrightness : 255
E/PhoneInterfaceManager( 1758): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/StoreModeReceiver( 3643): getPhoneNumber is empty
D/StoreModeReceiver( 3643): go to StoreModeCheck()
D/StoreModeReceiver( 3643): isStoremode not null
D/PhoneInterfaceManager( 1758): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
D/SystemWebViewEngine( 3614): CordovaWebView is running on device made by: LGE
V/SettingsProvider(  850): call_put(system:shop_mode_check=1) for 0 calling package = com.android.settings
,W/art     ( 3614): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3614): Attempt to remove local handle scope entry from IRT, ignoring
D/StoreModeReceiver( 3643): product_name : jagnm_global_com
,D/StoreModeReceiver( 3643): Store mode start!
V/SettingsProvider(  850): call_put(system:shop_mode=1) for 0 calling package = com.android.settings
V/SettingsProvider(  850): call_put(system:shop_mode_check=1) for 0 calling package = com.android.settings
I/PowerManagerService(  850): ALS enabled for SRE
D/PowerManagerServiceEx(  850): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x1, nextTimeout=120000 (in 69588 ms)
D/StoreModeReceiver( 3643): setBrightness() : NoMultiALC=255
W/ContextImpl( 3643): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.StoreModeReceiver.sendBroadcast:500 com.android.settings.StoreModeReceiver.setMode:473 
,V/SettingsProvider(  850): call_put(system:screen_brightness_mode=0) for 0 calling package = com.android.settings
D/SettingsProvider(  850): Set screen_off_timeout in entry value : 120000
V/SettingsProvider(  850): call_put(system:screen_off_timeout=120000) for 0 calling package = com.android.settings
V/SettingsProvider(  850): call_put(system:screen_brightness=255) for 0 calling package = com.android.settings
V/SettingsProvider(  850): call_put(system:check_night_mode=0) for 0 calling package = com.android.settings
,D/SettingBootReceiver( 3643): onReceive
D/SettingBootReceiver( 3643): Boot Completed intent received, action=android.intent.action.BOOT_COMPLETED
I/ActivityManager(  850): Killing 3336:com.google.android.onetimeinitializer/u0a8 (adj 15): empty #11
D/SettingBootReceiver( 3643): com.lge.appwidget.settings.powercontrol is not installed.(Successfully Removed)
,D/SettingBootReceiver( 3643): com.lge.appwidget.settings.powercontrol is not installed.(Successfully Removed)
D/SettingBootReceiver( 3643): com.lge.appwidget.settings.powercontrol is not installed.(Successfully Removed)
D/SettingBootReceiver( 3643): setStyle()
D/SettingBootReceiver( 3643): SettingStyle=1
D/SettingBootReceiver( 3643): setAccountMenu()
,D/TAG     ( 3643): setKidsMode
D/TAG     ( 3643): mIsOwner, setKidsMode
D/SettingBootReceiver( 3643): setAccountMenu()
D/YSY     ( 3643): not support Quiet mode notification
,W/libprocessgroup(  850): failed to open /acct/uid_10008/pid_3336/cgroup.procs: No such file or directory
,W/HolidayIntentService( 3595): onHandleIntent
I/[SystemUI]LGBootReceiver( 1383): onReceive = android.intent.action.BOOT_COMPLETED
I/Activity( 3614): Activity.onPostResume() called 
I/[SystemUI]LGPowerUI( 1383): onReceive = com.lge.statusbar.bootcompleted
I/[SystemUI]PhoneStatusBar( 1383): got ACTION_STICKY_BOOT_COMPLETED
I/BOOT    ( 1383): got ACTION_STICKY_BOOT_COMPLETED
D/HolidayDataLoader( 3595): readJsonAsset : holiday.json
D/OpenGLRenderer( 3614): Render dirty regions requested: true
,I/OpenGLRenderer( 3614): Initialized EGL, version 1.4
D/AlertService( 3595): 0 Action = android.intent.action.BOOT_COMPLETED
D/AlertService( 3595): [Widget]com.android.calendar.widget.CalendarAppWidgetProvider enabled
D/OpenGLRenderer( 3614): Enabling debug mode 0
D/Feature ( 3595): MemoryLevel - 5:NOT_DEF:Not UI4.2 LOS
D/AlertService( 3595): [Widget]com.android.calendar.widget.MonthWidgetProvider enabled
V/SettingsProvider(  850): call_put(system:gentle_vibration_status=1) for 0 calling package = com.android.settings
D/AlertService( 3595): [Widget]com.android.calendar.widget.WeekWidgetProvider enabled
,D/AlertService( 3595): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/Atlas   ( 3614): Validating map...
,D/SplitWindow(  850): check instance of lgWin Window{3db3febc u0 com.example.hello/com.example.hello.MainActivity}
,V/SettingsProvider(  850): call_put(system:smart_ringtone=0) for 0 calling package = com.android.settings
,D/SettingBootReceiver( 3643): timezoneID is null
I/SettingBootReceiver( 3643): disable au
E/HolidayIntentService( 3595): onHandleIntent:holiday data empty
,I/ActivityManager(  850): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3692 uid=10111 gids={50111, 9997, 1028, 3003} abi=armeabi-v7a
I/TAG     ( 3643): disable WirelessSettingsActivity
W/chromium( 3614): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/TAG     ( 3643): disable SKTPhoneMode
,D/AlarmScheduler( 3595): No events found starting within 1 week.
,D/InputDispatcher(  850): Focus entered window: Window{3db3febc u0 com.example.hello/com.example.hello.MainActivity}
,D/SettingBootReceiver( 3643): [Nightmode] Enter receiver
,D/SettingBootReceiver( 3643): [Nightmode] BOOT_COMPLETED
D/NightModeInfo( 3643): [Nightmode] setNightNodeTabSettings
D/NightModeInfo( 3643): [Nightmode] getAlreadyNightModeDB() : 0
D/NightModeInfo( 3643): [Nightmode] getUserBrightnessChange() : 0
,D/NightModeInfo( 3643): [Nightmode] getUserBrightnessChangeNoNight() : 0
V/SettingsProvider(  850): call_put(system:already_night_mode=0) for 0 calling package = com.android.settings
V/SettingsProvider(  850): call_put(system:user_change_brightness=0) for 0 calling package = com.android.settings
V/SettingsProvider(  850): call_put(system:user_change_brightness_no_night=0) for 0 calling package = com.android.settings
V/SettingsProvider(  850): call_put(system:night_mode_enabled=0) for 0 calling package = com.android.settings
D/NightModeInfo( 3643): [Nightmode] setTabNightCheck : 0
,V/SettingsProvider(  850): call_put(system:save_tab_night_check=0) for 0 calling package = com.android.settings
W/InputMethodManagerService(  850): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
I/ActivityManager(  850): Displayed com.example.hello/.MainActivity: +1s232ms
I/Timeline(  850): Timeline: Activity_windows_visible id: ActivityRecord{55e21ad u0 com.example.hello/.MainActivity t220} time:50705
,D/NightModeInfo( 3643): [Nightmode] cancelPendingIntent
D/NightModeInfo( 3643): [Nightmode] requestPendingIntent
D/NightModeInfo( 3643): [Nightmode] setAlarmStart~!!~!!~!!
,D/NightModeInfo( 3643): [Nightmode] currentHour > 6
D/NightModeInfo( 3643): [Nightmode] currentHour > 6
I/Timeline( 3614): Timeline: Activity_idle id: android.os.BinderProxy@3bdefa96 time:50729
I/NightModeInfo( 3643): JW getStartTime201512070000
D/NightModeInfo( 3643): [Nightmode] setAlarmEnd~!!~!!~!!
D/NightModeInfo( 3643): [Nightmode] currentHour > 6
D/NightModeInfo( 3643): [Nightmode] currentHour > 6
I/NightModeInfo( 3643): JW getEndTime201512070600
D/NightModeInfo( 3643): [Nightmode] currentHour > 6
I/NightModeInfo( 3643): getStartTime201512070000
D/NightModeInfo( 3643): [Nightmode] currentHour > 6
I/NightModeInfo( 3643): getEndTime201512070600
D/jw      ( 3643): Only VZW Supported end return
I/ActivityManager(  850): Killing 3355:com.android.cellbroadcastreceiver/u0a16 (adj 15): empty #11
,W/libprocessgroup(  850): failed to open /acct/uid_10016/pid_3355/cgroup.procs: No such file or directory
,V/DownloadManager( 2722): Received broadcast intent for android.intent.action.BOOT_COMPLETED
,V/DownloadManager( 2722): DownloadService onCreate
W/BindingManager( 3614): Cannot call determinedVisibility() - never saw a connection for the pid: 3614
I/DownloadManager( 2722): in removeSpuriousFiles
,I/NotificationManager( 2722): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 2722): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 2722): created cursor android.database.sqlite.SQLiteCursor@2d79213b on behalf of 2722
V/DownloadManager( 2722): DownloadService onStartCommand
I/DownloadManager( 2722): in trimDatabase
V/DownloadManager( 2722): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 2722): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 2722): created cursor android.database.sqlite.SQLiteCursor@3bdefa96 on behalf of 2722
D/MediaScannerReceiver( 2722): [MediaScanner] ACTION_BOOT_COMPLETED scan INTERNAL_VOLUME, EXTERNAL_VOLUME
D/MediaScannerService( 2722): [MediaScanner] start scanning volume internal: [/system/media, /oem/media, /cust/OPEN_EU/media]
,V/LGMediaProvider( 2722): insertInternal: content://media/none/media_scanner, initValues=volume=internal
D/MediaScannerService( 2722): [MediaScanner] scan() ACTION_MEDIA_SCANNER_STARTED uri : file:///system/media
,I/chromium( 3614): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
V/DownloadManager( 2722): created cursor android.database.sqlite.SQLiteCursor@3fb1a04 on behalf of 2722
,I/MusicBrowser( 2686): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_STARTED dat=file:///system/media flg=0x10 }}
I/MusicBrowser( 2686): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 2686): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_STARTED
D/WiseScreenService( 1828): [OnBootReceiver.java:24:onReceive()] iKeepScreenOn: 0
D/WiseScreenService( 1828): [OnBootReceiver.java:28:onReceive()] iSmartVideo: 0
W/ContextImpl( 1828): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1804 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.lge.keepscreenon.OnBootReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2663 
,D/MtpService( 2722): updating state; isCurrentUser=true, mMtpLocked=false
D/MediaScannerEx( 2722): [MediaScanner] scanDirectories()[0] = /system/media
D/MediaScannerEx( 2722): [MediaScanner] scanDirectories()[1] = /oem/media
D/MediaScannerEx( 2722): [MediaScanner] scanDirectories()[2] = /cust/OPEN_EU/media
,D/MtpService( 2722): addStorageLocked 65537 /storage/emulated/0
E/MtpStorageEx( 2722): setAccessCapability false
I/ActivityManager(  850): Start proc com.lge.voicerecorder for broadcast com.lge.voicerecorder/.bookmarkdb.BootCompletedReceiver: pid=3720 uid=10034 gids={50034, 9997, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,D/MtpService( 2722): updating state; isCurrentUser=true, mMtpLocked=false
,D/JsMessageQueue( 3614): Set native->JS mode to OnlineEventsBridgeMode
I/art     ( 2722): Thread[1,tid=2722,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31f8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
,E/MediaProfilesEx-JNI( 2722): register_com_lge_media_MediaProfilesEx
,E/MediaRecorderEx-JNI( 2722): register_com_lge_media_MediaRecorderEx
V/MediaScannerClient( 2722): [MediaScanner]setLocale: = en_US
D/AudioSystemEx( 2722): register_com_lge_media_LGAudioSystem
E/SurfaceControlEx( 2722): register_com_lge_view_SurfaceControlEx
I/art     ( 2722): Thread[1,tid=2722,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31f8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
D/LGMtpDatabaseJNI( 2722): register_android_mtp_LGMtpDatabase
D/LGMtpServerJNI( 2722): register_android_mtp_LGMtpServer
I/art     ( 2722): Thread[1,tid=2722,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31f8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
E/MediaPlayerEx-jni( 2722): register_com_lge_view_MediaPlayerEx
I/art     ( 2722): Thread[1,tid=2722,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31f8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
D/        ( 2722): register_com_lge_emoji_EmojiUtil
E/LGMtpDatabaseJNI( 2722): android_mtp_LGMtpDatabase_setup
D/MtpService( 2722): starting MTP server in PTP mode
D/LGMtpServer( 2722): LGMtpServer
D/LGMtpServerJNI( 2722): android_mtp_LGMtpServer_setup
,D/MtpService( 2722): addStorageLocked 65537 /storage/emulated/0
E/MtpStorageEx( 2722): setAccessCapability false
D/MtpServerEx( 2722): ANR FIX - addStorage!
D/LGMtpServerJNI( 2722): android_mtp_LGMtpServer_run
V/DownloadManager( 2722): DownloadService onDestroy
,E/MediaFileEx( 2722): Duplicate type = AVI
E/MediaFileEx( 2722): Duplicate type = ASF
E/AndroidProtocolHandler( 3614): Unable to open asset URL: file:///android_asset/www/jxcore.js
,V/MediaScannerClient( 2722): [MediaScanner]setLocale: = en_US
W/MediaScanner( 2722): Error opening directory '/oem/media/', skipping: No such file or directory.
V/MediaScannerClient( 2722): [MediaScanner]setLocale: = en_US
W/MediaScanner( 2722): Error opening directory '/cust/OPEN_EU/media/', skipping: No such file or directory.
D/LGMediaProvider( 2722): [MediaScanner] delete() uri = content://media/internal/file
D/LGMediaProvider( 2722): [MediaScanner] delete() completed notifyChange, uri = content://media/internal
V/MediaScannerEx( 2722): [MediaScanner] isInternalStorage : true
V/MediaScannerEx( 2722): [MediaScanner] isInternalStorage : true
,V/MediaScannerEx( 2722): [MediaScanner] isInternalStorage : true
D/MediaScanner( 2722): [MediaScanner] prescan time: 110ms
D/MediaScanner( 2722): [MediaScanner] scan time: 45ms
D/MediaScanner( 2722): [MediaScanner] postscan time: 9ms
D/MediaScanner( 2722): [MediaScanner] total time: 164ms
D/LGMediaProvider( 2722): [MediaScanner] delete() uri = content://media/none/media_scanner
I/VRBookmarkProvider( 3720): [BookmarkProvider.java:76:<init>()-[Thread:Other] BookmarkProvider
,I/VRBookmarkProvider( 3720): [BookmarkProvider.java:254:onCreate()-[Thread:Other] onCreate
I/VRBookmarkProvider( 3720): [BookmarkProvider.java:504:registerObservers()-[Thread:Other] registerObservers : content://media/external/audio/media
D/VRBootCompletedReceiver( 3720): [BootCompletedReceiver.java:25:onReceive()-[Thread:Other] Controller has been started on Boot complete
D/VRBootCompletedReceiver( 3720): [BootCompletedReceiver.java:47:onReceive()-[Thread:Other] Voice Recorder launcher enable(1)/disable(2) : 1
,I/ActivityManager(  850): Killing 3378:com.lge.email/u0a21 (adj 15): empty #11
D/MediaScannerService( 2722): [MediaScanner] scan() Send Intent ACTION_MEDIA_SCANNER_FINISHED uri : file:///system/media
,W/libprocessgroup(  850): failed to open /acct/uid_10021/pid_3378/cgroup.procs: No such file or directory
,D/MediaScannerService( 2722): [MediaScanner] done scanning volume internal
I/ActivityManager(  850): Waited long enough for: ServiceRecord{f69bb28 u0 com.lge.sizechangable.musicwidget.widget/.service.MusicWidgetUpdater}
I/MusicBrowser( 2686): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///system/media flg=0x10 }}
D/LGMediaProvider( 2722): [MediaScanner] mUnmountReceiver ACTION_MEDIA_SCANNER_FINISHED : uri = file:///system/media, path = /system/media
D/MediaScannerService( 2722): [MediaScanner] start scanning volume external: [/storage/emulated/0, /storage/external_SD]
V/LGMediaProvider( 2722): insertInternal: content://media/none/media_scanner, initValues=volume=external
I/MusicBrowser( 2686): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 2686): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_FINISHED
D/MediaScannerService( 2722): [MediaScanner] scan() ACTION_MEDIA_SCANNER_STARTED uri : file:///storage/emulated/0
D/LGBootCompleteReceiver( 1758): onReceive : android.intent.action.BOOT_COMPLETED
D/ConfigUtils( 1758): setUsimOperator() : card operator = 
D/ConfigUtils( 1758): setUsimOperator() : result = null
,V/LGMediaProvider( 2722): insertInternal: content://media/, initValues=name=external
D/ConfigUtils( 1758): setUsimOperator() : simOperator = 
D/ConfigUtils( 1758): setUsimOperator() : usimoperator = 0
D/ConfigUtils( 1758): setSupportedUsimMobilityForVoLTE() : false
I/MusicWidget( 2644): _mediaDataObserver onChange()
D/MediaScannerEx( 2722): [MediaScanner] scanDirectories()[0] = /storage/emulated/0
D/MediaScannerEx( 2722): [MediaScanner] scanDirectories()[1] = /storage/external_SD
I/MusicBrowser( 2686): [MediaPlaybackService.java:reloadQueue()] oooooo 
D/MusicBrowser( 2686): [MediaPlaybackService.java:reloadQueue()] oooooo id=-1
D/MusicBrowser( 2686): [MediaPlaybackService.java:reloadQueue()] oooooo mCardId=-1
D/MusicBrowser( 2686): [MediaPlaybackService.java:reloadQueue()] oooooo mPreferences.id=-1
D/MusicBrowser( 2686): [MediaPlaybackService.java:reloadQueue()] oooooo q=
D/MusicBrowser( 2686): [MediaPlaybackService.java:reloadQueue()] oooooo q.length=0
W/VRBookmarkProvider( 3720): [BookmarkProvider.java:546:onChange()-[Thread:Other] Data Change!! false url : content://media/
,D/MusicBrowser( 2686): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.queuechanged}
I/MusicBrowser( 2686): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
I/MusicWidget( 2644): beingMusicWidget_4x2() result::false
D/MusicBrowser( 2686): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
D/MusicBrowser( 2686): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/ConfigUtils( 1758): This Model Voice Clarity Support : false
D/MusicBrowser( 2686): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2686): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
,D/MusicBrowser( 2686): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2686): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2686): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2686): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
I/MusicWidget( 2644): intentReceiver onReceive() action::com.lge.music.queuechanged
I/MusicWidget( 2644): beingMusicWidget_4x2() result::false
I/MusicBrowser( 2686): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicWidget( 2644): beingMusicWidget_Quick() result::false
I/MusicWidget( 2644): beingMusicWidget_4x1() result::true
I/MusicBrowser( 2686): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
,D/LGBootCompleteReceiver( 1758): onReceive : updateCallrejectNotify rejectCallOption : 1
I/MusicWidget( 2644): send mDelayedStopHandler
D/MusicBrowser( 2686): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
I/MusicWidget( 2644): performViewUpdater handleMessage() msg.what::3
D/MusicBrowser( 2686): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2686): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicWidget( 2644): beingMusicWidget_Quick() result::false
D/MusicBrowser( 2686): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.metachanged}
I/MusicBrowser( 2686): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
D/MusicBrowser( 2686): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
D/MusicBrowser( 2686): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2686): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2686): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2686): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2686): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2686): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2686): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
I/MusicBrowser( 2686): [MediaPlaybackService.java:3426:notifyChange()] oooooo mRemoteControlClient.editMetadata :: META_CHANGED 
,I/MusicWidget( 2644): intentReceiver onReceive() action::com.lge.music.metachanged
I/MusicWidget( 2644): beingMusicWidget_4x2() result::false
I/MusicWidget( 2644): beingMusicWidget_Quick() result::false
D/CallRejectInfoToNotify( 1758): update : tPhoneMode : false
I/NotificationManager( 1758): com.android.phone: cancel(2131493582) by com.android.phone
I/MusicWidget( 2644): beingMusicWidget_4x1() result::true
I/MusicWidget( 2644): send mDelayedStopHandler
I/MusicWidget( 2644): performViewUpdater handleMessage() msg.what::3
I/MusicBrowser( 2686): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=false}
I/MusicWidget( 2644): beingMusicWidget_Quick() result::false
I/MusicBrowser( 2686): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
I/PhoneApp( 1758): saveDefaultRingtoneUriOfOwner = content://media/internal/audio/media/55
D/MusicBrowser( 2686): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2686): [MediaPlaybackService.java:9999:run()] oooooo AlbumImageUpdater() run :: Start
I/MusicBrowser( 2686): [MediaPlaybackService.java:10051:run()] oooooo AlbumImageUpdater() run :: End
I/MusicBrowser( 2686): [MediaPlaybackService.java:updateGroupIndexData()] oooooo 
I/MusicBrowser( 2686): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2686): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2686): [GroupIndexApi.java:groupingIndexDataProviderStart()] oooooo 
,I/MusicBrowser( 2686): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_STARTED dat=file:///storage/emulated/0 flg=0x10 }}
I/MusicBrowser( 2686): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 2686): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_STARTED
I/MusicBrowser( 2686): [GroupingIndexDataProvider.java:101:doInBackground()] oooooo mIsMusicPickerMode = false
I/ActivityManager(  850): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=3743 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,W/MusicBrowser( 2686): - Start trace [MusicUtils.query]---------------------------------------------------------------
W/MusicBrowser( 2686): [Line 003751] MusicUtils.java, query() : MusicUtils.query
W/MusicBrowser( 2686): [Line 003761] MusicUtils.java, isMediaScannerScanning() : MusicUtils.query
W/MusicBrowser( 2686): [Line 001991] MediaPlaybackService.java, onChange() : MusicUtils.query
W/MusicBrowser( 2686): [Line 000130] ContentObserver.java, onChange() : MusicUtils.query
W/MusicBrowser( 2686): - End   trace [MusicUtils.query]---------------------------------------------------------------
V/MediaScannerClient( 2722): [MediaScanner]setLocale: = en_US
,I/MusicWidget( 2644): performViewUpdater handleMessage() msg.what::0
,I/MusicWidget( 2644): beingMusicWidget_4x1() result::true
I/MusicWidget( 2644): performUpdate()_4x1
I/MusicWidget( 2644): defaultAppWidget()_4x1
I/MusicWidget( 2644): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2644): 4x1_currentTheme :: null
I/MusicWidget( 2644): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2644): setDefaultViewLayoutId()_4x1
V/DrmBroadcastReceiver( 3743): Receive ACTION_BOOT_COMPLETED
,I/MusicWidget( 2644): appWidgetViewUpdate()_4x1
I/MusicWidget( 2644): linkButtons()_4x1
V/DrmService( 3743): Service onCreate
D/DrmService( 3743): Received new request = 4
D/DrmServiceHandler( 3743): updateDrmPushNotification() : No notification
,D/DrmService( 3743): Completed !! request = 4
D/DrmService( 3743): Request count = 0
D/MediaScannerEx( 2722): [MediaScanner] beginFile() path = /storage/emulated/0/QuicksetLite Setup/data
,I/ActivityManager(  850): Start proc com.lge.cloudhub for broadcast com.lge.cloudhub/.service.CloudHubReceiver: pid=3760 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/MediaScannerClient( 2722): [MediaScanner]setLocale: = en_US
W/MediaScanner( 2722): Error opening directory '/storage/external_SD/', skipping: Permission denied.
,D/LGMediaProvider( 2722): [MediaScanner] delete() uri = content://media/external/file
W/VRBookmarkProvider( 3720): [BookmarkProvider.java:546:onChange()-[Thread:Other] Data Change!! false url : content://media/external
V/DrmService( 3743): Service onDestroy
W/VRBookmarkProvider( 3720): [BookmarkProvider.java:563:onChange()-[Thread:Other] EXTERNAL Change!!
W/MusicBrowser( 2686): - Start trace [MusicUtils.query]---------------------------------------------------------------
W/MusicBrowser( 2686): [Line 003751] MusicUtils.java, query() : MusicUtils.query
W/MusicBrowser( 2686): [Line 003761] MusicUtils.java, isMediaScannerScanning() : MusicUtils.query
D/LGMediaProvider( 2722): [MediaScanner] delete() completed notifyChange, uri = content://media/external
W/MusicBrowser( 2686): [Line 001991] MediaPlaybackService.java, onChange() : MusicUtils.query
W/MusicBrowser( 2686): [Line 000130] ContentObserver.java, onChange() : MusicUtils.query
W/MusicBrowser( 2686): - End   trace [MusicUtils.query]---------------------------------------------------------------
I/MusicWidget( 2644): pushUpdate()_4x1
I/ActivityManager(  850): Killing 2397:com.android.defcontainer/u0a4 (adj 15): empty #11
I/MusicWidget( 2644): performViewUpdater handleMessage() msg.what::1
,I/MusicWidget( 2644): beingMusicWidget_4x2() result::false
I/MusicWidget( 2644): _mediaDataObserver onChange()
I/MusicWidget( 2644): beingMusicWidget_4x2() result::false
V/MediaScanner( 2722): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@ad8310f
,V/MediaScanner( 2722): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@ad8310f
,D/MediaScanner( 2722): [MediaScanner] prescan time: 116ms
D/MediaScanner( 2722): [MediaScanner] scan time: 116ms
D/MediaScanner( 2722): [MediaScanner] postscan time: 69ms
D/MediaScanner( 2722): [MediaScanner] total time: 301ms
D/LGMediaProvider( 2722): [MediaScanner] delete() uri = content://media/none/media_scanner
I/[LgeWidgetLib]LgeAppWidgetHostView( 1885): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,D/MediaScannerService( 2722): [MediaScanner] scan() Send Intent ACTION_MEDIA_SCANNER_FINISHED uri : file:///storage/emulated/0
W/libprocessgroup(  850): failed to open /acct/uid_10004/pid_2397/cgroup.procs: No such file or directory
,I/MusicBrowser( 2686): [MediaPlaybackService.java:1995:onChange()] oooooo 
D/LGMediaProvider( 2722): [MediaScanner] mUnmountReceiver ACTION_MEDIA_SCANNER_FINISHED : uri = file:///storage/emulated/0, path = /storage/emulated/0
V/MusicBrowser( 2686): [MediaPlaybackService.java:5808:getPath()] oooooo {mFileToPlay=null}
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1885): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/MusicBrowser( 2686): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///storage/emulated/0 flg=0x10 }}
I/MusicBrowser( 2686): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 2686): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_FINISHED
D/jxcore_app_log( 3614): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426131456
D/JX-Cordova( 3614): jxcore cordova android initializing
D/MediaScannerService( 2722): [MediaScanner] done scanning volume external
,I/MusicBrowser( 2686): [MediaPlaybackService.java:reloadQueue()] oooooo 
D/MusicBrowser( 2686): [MediaPlaybackService.java:reloadQueue()] oooooo id=-1
D/MusicBrowser( 2686): [MediaPlaybackService.java:reloadQueue()] oooooo mCardId=-1
D/MusicBrowser( 2686): [MediaPlaybackService.java:reloadQueue()] oooooo mPreferences.id=-1
D/MusicBrowser( 2686): [MediaPlaybackService.java:reloadQueue()] oooooo q=
D/MusicBrowser( 2686): [MediaPlaybackService.java:reloadQueue()] oooooo q.length=0
D/MusicBrowser( 2686): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.queuechanged}
I/MusicBrowser( 2686): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
D/MusicBrowser( 2686): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
D/MusicBrowser( 2686): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2686): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2686): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2686): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2686): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2686): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2686): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
,I/MusicWidget( 2644): intentReceiver onReceive() action::com.lge.music.queuechanged
I/MusicWidget( 2644): beingMusicWidget_4x2() result::false
I/MusicWidget( 2644): beingMusicWidget_Quick() result::false
I/MusicWidget( 2644): beingMusicWidget_4x1() result::true
I/MusicWidget( 2644): send mDelayedStopHandler
I/MusicWidget( 2644): performViewUpdater handleMessage() msg.what::3
I/MusicWidget( 2644): beingMusicWidget_Quick() result::false
I/MusicBrowser( 2686): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2686): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2686): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2686): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2686): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
D/MusicBrowser( 2686): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.metachanged}
I/MusicBrowser( 2686): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
D/MusicBrowser( 2686): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
D/MusicBrowser( 2686): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2686): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2686): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2686): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2686): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2686): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2686): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
I/MusicBrowser( 2686): [MediaPlaybackService.java:3426:notifyChange()] oooooo mRemoteControlClient.editMetadata :: META_CHANGED 
I/MusicWidget( 2644): intentReceiver onReceive() action::com.lge.music.metachanged
I/MusicBrowser( 2686): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=false}
I/MusicBrowser( 2686): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
I/MusicWidget( 2644): beingMusicWidget_4x2() result::false
I/MusicWidget( 2644): beingMusicWidget_Quick() result::false
I/MusicWidget( 2644): beingMusicWidget_4x1() result::true
,I/MusicWidget( 2644): send mDelayedStopHandler
I/MusicWidget( 2644): performViewUpdater handleMessage() msg.what::3
I/MusicWidget( 2644): beingMusicWidget_Quick() result::false
D/MusicBrowser( 2686): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2686): [MediaPlaybackService.java:updateGroupIndexData()] oooooo 
I/MusicBrowser( 2686): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2686): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2686): [GroupIndexApi.java:groupingIndexDataProviderStart()] oooooo 
I/MusicBrowser( 2686): [MediaPlaybackService.java:9999:run()] oooooo AlbumImageUpdater() run :: Start
,I/MusicBrowser( 2686): [MediaPlaybackService.java:10051:run()] oooooo AlbumImageUpdater() run :: End
I/MusicBrowser( 2686): [GroupingIndexDataProvider.java:101:doInBackground()] oooooo mIsMusicPickerMode = false
I/VRBookmarkProvider( 3720): [BookmarkProvider.java:530:handleMessage()-[Thread:Other] -- syncTable() START --
,W/jxcore-log( 3614): Initializing JXcore engine
W/jxcore-log( 3614): JXcore engine is ready
W/jxcore-log( 3614): Starting JXcore engine
,I/VRBookmarkProvider( 3720): [BookmarkProvider.java:532:handleMessage()-[Thread:Other] -- syncTable() END --
V/CloudHub( 3760): [DATABASE][DBConnection|open] open database
E/CloudHub( 3760): [DATABASE][DBConnection|getUserId] User id: 0
,E/CloudHub( 3760): [DATABASE][DBConnection|getDatabasePath] Database path: /data/user/0/com.lge.cloudhub/databases/cloudhub.db
V/CloudHub( 3760): [SERVICE][CloudHubReceiver|queryUploadCount] # of contents to upload: 0
,V/DownloadManager( 2722): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 2722): created cursor android.database.sqlite.SQLiteCursor@3d99a59c on behalf of 3760
V/CloudHub( 3760): [SERVICE][CloudHubReceiver|queryDownloadCount] # of contents to download: 0
,I/ActivityManager(  850): Start proc com.lge.gnss.airtest for broadcast com.lge.gnss.airtest/.GnssAirTestReceiver: pid=3780 uid=10054 gids={50054, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  850): Killing 3419:com.google.android.partnersetup/u0a9 (adj 15): empty #11
I/MusicWidget( 2644): performViewUpdater handleMessage() msg.what::0
W/m.example.hello( 3614): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6724]" dev="sockfs" ino=6724 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 3614): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 3614): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6829]" dev="sockfs" ino=6829 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 3614): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/m.example.hello( 3614): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/m.example.hello( 3614): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[18855]" dev="sockfs" ino=18855 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
I/MusicWidget( 2644): beingMusicWidget_4x1() result::true
I/MusicWidget( 2644): performUpdate()_4x1
,I/MusicWidget( 2644): defaultAppWidget()_4x1
I/MusicWidget( 2644): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2644): 4x1_currentTheme :: null
I/MusicWidget( 2644): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2644): setDefaultViewLayoutId()_4x1
I/MusicWidget( 2644): appWidgetViewUpdate()_4x1
I/MusicWidget( 2644): linkButtons()_4x1
W/libprocessgroup(  850): failed to open /acct/uid_10009/pid_3419/cgroup.procs: No such file or directory
,I/MusicWidget( 2644): pushUpdate()_4x1
I/MusicWidget( 2644): performViewUpdater handleMessage() msg.what::1
,I/MusicWidget( 2644): beingMusicWidget_4x2() result::false
D/AirTest ( 3780): Set airtest_enable to false
,I/ActivityManager(  850): Killing 3481:com.lge.lgdmsclient/1000 (adj 15): empty #11
I/[LgeWidgetLib]LgeAppWidgetHostView( 1885): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1885): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,W/jxcore-log( 3614): Platform android
W/jxcore-log( 3614): 
W/jxcore-log( 3614): Process ARCH arm
W/jxcore-log( 3614): 
W/libprocessgroup(  850): failed to open /acct/uid_1000/pid_3481/cgroup.procs: No such file or directory
,I/ActivityManager(  850): Waited long enough for: ServiceRecord{3a05e319 u0 com.lge.sizechangable.weather/.service.WeatherService}
V/LGSC    ( 2769): [104] 401
I/jxcore-log( 3614): JXcore Cordova bridge is ready!
I/jxcore-log( 3614): 
W/jxcore-log( 3614): JXcore engine is started
,I/ActivityManager(  850): Start proc com.lge.lgfota.permission for broadcast com.lge.lgfota.permission/.DmcTargetValidationReceiver: pid=3798 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
E/jxcore-log( 3614): >> LGE-LG-D722
E/jxcore-log( 3614): 
,I/jxcore-log( 3614): Total memory 906309632
I/jxcore-log( 3614): 
I/jxcore-log( 3614): Free memory 32063488
I/jxcore-log( 3614): 
I/jxcore-log( 3614): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3614): 
I/jxcore-log( 3614): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3614): 
I/jxcore-log( 3614): userPath [ 'www' ]
I/jxcore-log( 3614): 
I/jxcore-log( 3614): Size 720 1196
I/jxcore-log( 3614): 
,I/jxcore-log( 3614): Screen Brightness 255
I/jxcore-log( 3614): 
E/jxcore-log( 3614): Dummy Error Log.
E/jxcore-log( 3614): 
,D/TARGETVALIDLATION_RECEIVER( 3798): TargetValidationReceiver_ACTION_BOOT_COMPLETETED Received
D/TARGETVALIDLATION_RECEIVER( 3798): updateFlag = new File(TARGET_FLAG_PATH)
,D/TARGETVALIDLATION_RECEIVER( 3798): Do Not display result dialog. it is not used Update Tool!!
I/ActivityManager(  850): Killing 3503:com.lge.clock/u0a10 (adj 15): empty #11
V/LGSC    ( 1758): [101] 102, action=android.intent.action.BOOT_COMPLETED, iccState=null
,W/libprocessgroup(  850): failed to open /acct/uid_10010/pid_3503/cgroup.procs: No such file or directory
W/ContextImpl( 2860): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.qualcomm.atfwd.AtFwdAutoboot.onReceive:24 android.app.ActivityThread.handleReceiver:2663 
E/AtFwd AutoBoot( 2860): AtFwd Auto Boot Started Successfully
I/GoogleHttpClient( 2013): GMS http client unavailable, use old client
,I/ActivityManager(  850): Start proc com.lge.defaultaccount for broadcast com.lge.defaultaccount/.receiver.ReceiverBootUp: pid=3817 uid=10062 gids={50062, 9997} abi=armeabi-v7a
,I/InsertAccount( 3817): The account already exists
,I/ActivityManager(  850): Start proc com.lge.hiddenmenu for broadcast com.lge.hiddenmenu/.kddi_only.sms_setting.AssistReceiver: pid=3838 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  850): Killing 3536:com.lge.appbox.client:SingleBinaryService/u0a11 (adj 15): empty #11
W/libprocessgroup(  850): failed to open /acct/uid_10011/pid_3536/cgroup.procs: No such file or directory
,I/InsertAccount( 3817): The account info in contact DB already exists
,I/InsertAccount( 3817): The account info in calendar DB already exists
I/Process ( 3817): Sending signal. PID: 3817 SIG: 9
,W/ResourcesManager( 3838): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 3838): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/[SMS_AD]( 3838): Intent action: android.intent.action.BOOT_COMPLETED
,I/ActivityManager(  850): Process com.lge.defaultaccount (pid 3817) has died
I/[SMS_AD]( 3838): Intent action: android.intent.action.BOOT_COMPLETED
,D/WeatherAncestor( 2680): 2 : onReceive, action: android.intent.action.BOOT_COMPLETED, Time(hour:min:sec) 15:59:23
,D/UpdateThreadPoolManager( 2680): 2 : This is isUpdating : false
I/MusicBrowser( 2686): [MediaPlaybackService.java:2010:handleMessage()] oooooo mGroupIndexHandler msg.what : 0
I/MusicBrowser( 2686): [MediaPlaybackService.java:updateGroupIndexData()] oooooo 
I/MusicBrowser( 2686): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2686): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2686): [GroupIndexApi.java:groupingIndexDataProviderStart()] oooooo 
,I/MusicBrowser( 2686): [GroupingIndexDataProvider.java:101:doInBackground()] oooooo mIsMusicPickerMode = false
I/jxcore-log( 3614): getBuffer is called!!!!
I/jxcore-log( 3614): 
D/Weather_cast( 2680): 2 : set auto-update time : 12/6 18:59
D/WeatherAncestor( 2680): 2 : onReceive has processed, action: android.intent.action.BOOT_COMPLETED, Time(hour:min:sec) 15:59:23
D/WeatherService( 2680): 2 : onStartCommand, intent!=null, action: android.intent.action.BOOT_COMPLETED
I/ActivityManager(  850): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.LockSettingsReceiver: pid=3857 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
W/ActivityManager(  850): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2680): 2 : Utils getTopActivity com.lge.launcher2 / true
I/art     (  850): Explicit concurrent mark sweep GC freed 15398(723KB) AllocSpace objects, 3(237KB) LOS objects, 33% free, 22MB/33MB, paused 2.504ms total 178.275ms
D/WeatherService( 2680): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2680): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/LockScreenSettings( 3857): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/LockScreenSettings( 3857): Received Broadcast : android.intent.action.BOOT_COMPLETED
I/ActivityManager(  850): Start proc com.lge.springcleaning for broadcast com.lge.springcleaning/.receiver.BootCompleteReceiver: pid=3880 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  850): Killing 3555:com.lge.appbox.client/u0a11 (adj 15): empty #11
I/art     (  310): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 299us total 22.546ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 21.048ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 20.906ms
,W/libprocessgroup(  850): failed to open /acct/uid_10011/pid_3555/cgroup.procs: No such file or directory
,D/BootCompleteReceiver( 3880): hasclipTray = true
W/ContextImpl( 3880): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.springcleaning.receiver.BootCompleteReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2663 
,I/ActivityManager(  850): Start proc com.lge.springcleaning:AppCleanupService for service com.lge.springcleaning/.service.AppCleanupService: pid=3898 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  850): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3915 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  850): Killing 3643:com.android.settings/1000 (adj 15): empty #11
,W/libprocessgroup(  850): failed to open /acct/uid_1000/pid_3643/cgroup.procs: No such file or directory
V/AppCleanupService( 3898): registerAlarm
,V/AlarmManager(  850): ELAPSED_WAKEUP set : Alarm{258d8b1c type 2 when 53133 com.android.providers.calendar} when 53133
,D/AppCleanupService( 3898): noticeInterval = 2678399999
D/AppCleanupService( 3898): notiDateStr = 2015-12-20 22:35:42
D/AppCleanupService( 3898): noticeStart = 2015-12-20 22:35:42
D/AppCleanupService( 3898): noticeStart = 1450647342000
,D/AppUsageDbAdapter( 3898): initPreloadedAppToTheDB() : row count = 129
,E/UpdateRequestReceiver( 3915): ignoring update request
,E/UpdateRequestReceiver( 3915): ignoring update request
E/UpdateRequestReceiver( 3915): ignoring update request
E/UpdateRequestReceiver( 3915): ignoring update request
,E/UpdateRequestReceiver( 3915): ignoring update request
E/UpdateRequestReceiver( 3915): ignoring update request
I/ActivityManager(  850): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseSIMObserver: pid=3951 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  850): Killing 3458:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/libprocessgroup(  850): failed to open /acct/uid_10014/pid_3458/cgroup.procs: No such file or directory
,D/sensors_hal_Time(  850): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  850): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  850): tsOffsetIs: Apps: 53419227848; DSPS: 1841661; Offset : -2797773539
,D/SIMObserver( 3951): action:android.intent.action.BOOT_COMPLETED
D/SIMObserver( 3951): handle ACTION_BOOT_COMPLETED
I/ActivityManager(  850): Killing 3692:com.android.managedprovisioning/u0a111 (adj 15): empty #11
,W/libprocessgroup(  850): failed to open /acct/uid_10111/pid_3692/cgroup.procs: No such file or directory
,E/QcrilMsgTunnelAutoboot( 2296): Received Intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelAutoboot (has extras) } canStartService = false
,D/PhoneInterfaceManager( 1758): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
D/PhoneInterfaceManager( 1758): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ActivityManager(  850): Start proc com.google.android.gms for broadcast com.google.android.gms/.chimera.container.GmsModuleFinder$Receiver: pid=3970 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 3970): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3970): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 3970): VM with version 2.1.0 has multidex support
I/MultiDex( 3970): install
I/MultiDex( 3970): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3970): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 3970): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 3970): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@23072f32: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3970): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 3970): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 3970): com.google.android.gms: cancel(39789) by com.google.android.gms
D/NativeLibraryUtils( 3970): Install completed successfully. count=13 extracted=0
,W/InstanceID/Rpc( 3970): Found 10006
,D/FileApkUtils( 3970): Spent 55ms computing apk sha1.
,D/FileApkUtils( 3970): Module already staged or being staged:chimera-modules/MapsModule.apk
I/art     ( 3970): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-d93aca1818df11c4cd5bccf493ad94e2b544d57a@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
D/DexOptUtils( 3970): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk is already optimized. Bailing.
D/FileApkUtils( 3970): Keeping up-to-date module: module-d93aca1818df11c4cd5bccf493ad94e2b544d57a
D/GmsModuleFndr( 3970): Beginning GMS chimera module scan
,D/GmsModuleFndr( 3970): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
,I/ActivityManager(  850): Waited long enough for: ServiceRecord{272ab7ef u0 com.google.android.gms/.gcm.GcmService}
D/ChimeraCfgMgr( 3970): Beginning module configuration check
D/ChimeraCfgMgr( 3970): Module APKs unchanged, check complete
I/CheckinService( 3970): Checkin interval check for package: unspecified last checkin: 1449218666795 min interval config: 0 actual interval: 195298527
,D/GCM     ( 3970): COMPAT: Multi user not supported
I/CheckinService( 3970): Disabling old GoogleServicesFramework version
D/GCM     ( 2013): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,I/GCoreUlr( 3970): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/GCoreUlr( 1739): DispatchingService.onCreate()
I/art     ( 3970): CheckpointMarkThreadRoots callback created = 0xb04b54f0
D/SystemUpdateService( 3970): onCreate
,D/SystemUpdateService( 3970): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/art     ( 3970): CheckpointMarkThreadRoots callback created = 0xb04b54d0
V/AuthZen ( 3970): Handling intent: android.intent.action.BOOT_COMPLETED
,W/art     ( 3970): Suspending all threads took: 9.017ms
,V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 3970): Background partial concurrent mark sweep GC freed 16264(1144KB) AllocSpace objects, 8(128KB) LOS objects, 39% free, 10MB/16MB, paused 41.217ms total 125.612ms
I/SystemUpdateService( 3970): cancelUpdate (empty URL)
I/SystemUpdateService( 3970): active receiver: disabled
,D/AuthZenEventHandler( 3970): Handling event: android.intent.action.BOOT_COMPLETED
I/art     ( 3970): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
I/art     ( 3970): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,I/NotificationManager( 3970): com.google.android.gms: cancel(2130838130) by com.google.android.gms
I/NotificationManager( 3970): com.google.android.gms: cancel(2130838131) by com.google.android.gms
,I/CheckinService( 3970): Checking schedule, now: 1449413965555 next: 1449745915752
,I/CheckinService( 3970): active receiver: disabled
W/BaseAppContext( 3970): Using Auth Proxy for data requests.
,D/ChimeraCfgMgr( 3970): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/art     ( 1739): Explicit concurrent mark sweep GC freed 15431(986KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 11MB/18MB, paused 1.449ms total 113.494ms
,D/ChimeraCfgMgr( 3970): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 3970): onDestroy
,W/GCoreFlp( 1739): No location to return for getLastLocation()
,W/FusedLocationProvider( 3970): location=null
W/Auth    ( 2013): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GCoreFlp( 1739): No location to return for getLastLocation()
W/FusedLocationProvider( 3970): location=null
I/AuthZen ( 3970): Fetching signing key...
,I/GCoreUlr( 1739): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
W/Kids    ( 3970): [AbstractKidsOperation] Invalid device state 3
,I/Kids    ( 3970): [KidAccountFixer] No network connection
,I/AuthZen ( 3970): Signing key fetched successfully!
W/BaseAppContext( 3970): Using Auth Proxy for data requests.
,I/art     ( 2013): Explicit concurrent mark sweep GC freed 5841(343KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 11MB/18MB, paused 13.464ms total 121.775ms
,D/a       ( 3970): Opening database auth.proximity.permit_store...
D/AuthZenTransactionCache( 3970): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 3970): Clearing transaction cache
V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 3970): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
D/PersistentNotificationBroadcastReceiver( 2013): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/ActivityManager(  850): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4056 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/GCoreUlr( 1739): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1739): Unbound from all location providers
W/ResourcesManager( 4056): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/GCoreUlr( 1739): DispatchingService.onDestroy()
I/GCoreUlr( 1739): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 1739): Unbound from all location providers
,I/Babel_SMS( 4056): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 4056): MmsConfig.loadMmsSettings
I/Babel_SMS( 4056): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 4056): MmsConfig.loadFromDatabase
,E/Babel_SMS( 4056): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4056): MmsConfig.loadFromResources
E/Babel_SMS( 4056): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 4056): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 4056): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 4056): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 4056): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 4056): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 4056): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 4056): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 4056): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 4056): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 4056): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 4056): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 4056): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 4056): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 4056): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 4056): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 4056): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 4056): found sensor: Motion Accel, handle=46
,I/art     ( 4056): CheckpointMarkThreadRoots callback created = 0xb042d870
,W/Settings( 4056): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 4056): startup - clean
I/art     ( 4056): CheckpointMarkThreadRoots callback created = 0xb042d850
I/Babel   ( 4056): deleted: false for 0
,W/AudioCapabilities( 4056): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 4056): Unsupported mime audio/adpcm
W/AudioCapabilities( 4056): Unsupported mime audio/g726
W/AudioCapabilities( 4056): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 4056): Unsupported mime audio/wma-voice
W/VideoCapabilities( 4056): Unsupported mime video/mjpg
,W/VideoCapabilities( 4056): Unsupported mime video/theora
W/AudioCapabilities( 4056): Unsupported mime audio/evrc
,W/AudioCapabilities( 4056): Unsupported mime audio/qcelp
W/VideoCapabilities( 4056): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 4056): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 4056): Unsupported mime audio/qcelp
W/AudioCapabilities( 4056): Unsupported mime audio/evrc
W/VideoCapabilities( 4056): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 4056): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4056): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4056): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4056): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4056): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 4056): onServiceConnected
W/Babel   ( 4056): Attempted to change video mute state without an active call.
,I/NotificationManager( 4056): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/ActivityManager(  850): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4087 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  850): Killing 3720:com.lge.voicerecorder/u0a34 (adj 15): empty #11
W/libprocessgroup(  850): failed to open /acct/uid_10034/pid_3720/cgroup.procs: No such file or directory
,I/art     (  850): Explicit concurrent mark sweep GC freed 16378(821KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 22MB/33MB, paused 1.651ms total 143.606ms
,W/ResourcesManager( 4087): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4087): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4087): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/System  ( 4087): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4087): Installed default security provider GmsCore_OpenSSL
,W/CursorWrapperInner( 3760): Cursor finalized without prior close()
,W/ResourcesManager( 4087): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4087): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/art     ( 4087): CheckpointMarkThreadRoots callback created = 0xb042dba0
,I/art     ( 4087): CheckpointMarkThreadRoots callback created = 0xb4958de0
,E/YouTube MDX( 4087): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/libc-netbsd( 4087): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4087): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/dex2oat ( 4132): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-443722464.jar --oat-fd=28 --oat-location=/data/data/com.google.android.youtube/cache/ads-443722464.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4087): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
I/dex2oat ( 4132): dex2oat took 87.470ms (threads: 4)
,I/NotificationManager( 4087): com.google.android.youtube: cancel(2) by com.google.android.youtube
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4087): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4087): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4087): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
W/InstanceID/Rpc( 4087): Found 10006
,D/BluetoothManagerService(  850): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  850): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  850): Message: 2
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4087): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,D/WifiServiceImplEx(  850): setWifiEnabled: false pid=3614, uid=10030, package= com.example.hello, App Lable : HelloWorld
D/WifiService(  850): setWifiEnabled: false pid=3614, uid=10030
I/jxcore-log( 3614): ****TEST TOOK:  5058  ms ****
I/jxcore-log( 3614): 
I/jxcore-log( 3614): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3614): 
,I/ActivityManager(  850): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4192 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/NotificationManager( 4087): com.google.android.youtube: cancel(10436) by com.google.android.youtube
,I/ActivityManager(  850): Killing 3743:com.lge.drmservice/u0a51 (adj 15): empty #11
,D/AndroidRuntime( 4189): 
D/AndroidRuntime( 4189): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4189): CheckJNI is OFF
W/libprocessgroup(  850): failed to open /acct/uid_10051/pid_3743/cgroup.procs: No such file or directory
,W/ActivityManager(  850): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/AndroidRuntime( 4189): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  850): Force stopping com.example.hello appid=10030 user=-1: uninstall pkg
,I/ActivityManager(  850): Killing 3614:com.example.hello/u0a30 (adj 0): stop com.example.hello
I/Gmail   ( 4192): getAccountsCursor
I/WindowState(  850): WIN DEATH: Window{3db3febc u0 com.example.hello/com.example.hello.MainActivity}
,D/InputDispatcher(  850): Focus left window: Window{3db3febc u0 com.example.hello/com.example.hello.MainActivity}
D/InputDispatcher(  850): Window went away: Window{3db3febc u0 com.example.hello/com.example.hello.MainActivity}
W/PackageSettings(  850): Skipping PackageSetting{37c3eef0 com.test.thalitest/10316} due to missing metadata
,W/ActivityManager(  850): Force removing ActivityRecord{55e21ad u0 com.example.hello/.MainActivity t220}: app died, no saved state
,W/ActivityManager(  850): Spurious death for ProcessRecord{28a910be 3614:com.example.hello/u0a30}, curProc for 3614: null
I/ActivityManager(  850): Force stopping com.example.hello appid=10030 user=0: pkg removed
,W/ActivityManager(  850): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/KeyguardModel( 1383): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 1885): [Launcher.java:5203:onStart()]onStart
,W/GeofencerStateMachine( 1739): Ignoring removeGeofence because network location is disabled.
,W/System.err( 3402): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
W/System.err( 3402): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
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
,I/[LGHome]EVENT( 1885): [Launcher.java:776:onResume()]onResume
I/QCNEJ   ( 1846): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[SystemUI]QSlideListController( 1383): onReceive = android.intent.action.PACKAGE_REMOVED
,I/[LGHome]LGActivityUtil( 1885): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/KeyguardModel( 1383): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1383): createShortcutInfo...
I/[LGHome]EVENT( 1885): [Launcher.java:929:onResume()]onResume end
I/Activity( 1885): Activity.onPostResume() called 
I/InputReader(  850): Reconfiguring input devices.  changes=0x00000010
D/KeyguardModel( 1383): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1383): createShortcutInfo...
W/ResourceType( 1383): No package identifier when getting value for resource number 0x00000000
,W/PackageManager( 1383): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1383): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1383): createShortcutInfo...
,W/[LGHome]LGWallpaperInfo( 1885): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1885): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
W/ResourceType( 1383): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1383): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1383): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1383): createShortcutInfo...
I/SystemUI[Framework](  850): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  850): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  850): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  850): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  850): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3209674,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  850): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
W/ActivityManager(  850): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/InputDispatcher(  850): Focus entered window: Window{22fdad6 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/ResourceType( 1383): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1383): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1383): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1383): createShortcutInfo...
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1383): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 1383): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/Gmail   ( 4192): Observing account changes for notifications
,D/KeyguardModel( 1383): handleShortcutListChanged...
I/[LGHome]EVENT( 1885): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/administrator(  850): Handling package changes for user 0
I/art     ( 1793): CheckpointMarkThreadRoots callback created = 0xaaf1eb80
I/[LGHome]LGPlusHomeDBManager( 1885): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1885): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
I/[LGHome]EVENT( 1885): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1885): [setNavigationBarColor] color=0x 0
D/KeyguardModel( 1383): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1383): createShortcutInfo...
,D/KeyguardModel( 1383): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1383): createShortcutInfo...
W/GAV2    ( 4192): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/art     ( 1793): CheckpointMarkThreadRoots callback created = 0xb042d700
,W/ResourceType( 1383): No package identifier when getting value for resource number 0x00000000
,W/PackageManager( 1383): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1383): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1383): createShortcutInfo...
W/ResourceType( 1383): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1383): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1383): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1383): createShortcutInfo...
W/ResourceType( 1383): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1383): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1383): package = com.lge.camera, class = com.lge.camera.CameraApp
,D/KeyguardModel( 1383): createShortcutInfo...
D/KeyguardModel( 1383): handleShortcutListChanged...
,W/ActivityManager(  850): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 4192): Error finding the version of the Email provider.....
E/Gmail   ( 4192): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4192): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4192): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4192): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4192): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4192): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4192): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 4192): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 4192): We do not support migrating this version of the Email provider.
,W/InputMethodManagerService(  850): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,W/InputMethodManagerService(  850): Got RemoteException sending setActive(false) notification to pid 3614 uid 10030
W/ActivityManager(  850): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  850): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/ActivityThread( 4192): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@ab3307 that was originally bound here
E/ActivityThread( 4192): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@ab3307 that was originally bound here
E/ActivityThread( 4192): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 4192): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 4192): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 4192): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 4192): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4192): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4192): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4192): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4192): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4192): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4192): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4192): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4192): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4192): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4192): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 4192): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/art     (  850): Explicit concurrent mark sweep GC freed 16502(1104KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 22MB/34MB, paused 2.851ms total 377.239ms
I/Timeline( 1885): Timeline: Activity_idle id: android.os.BinderProxy@1a7f1518 time:58329
,I/SystemUI[Framework](  850): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/ActivityManager(  850): Unbind failed: could not find connection for android.os.BinderProxy@2e7b8da6
W/PhoneWindowManagerEx(  850): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  850): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  850): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  850): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3209674,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  850): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/VelvetNetworkClient( 1945): Network connection not availble
,I/HotwordRecognitionRnr( 1945): Starting hotword detection.
,I/MicrophoneInputStream( 1945): mic_starting com.google.android.apps.gsa.speech.audio.u@2188bac6
V/AudioRecord( 1945): set(): inputSource 1999, sampleRate 16000, format 0x1, channelMask 0x10, frameCount 128000, notificationFrames 0, sessionId 0, transferType 0, flags 0
V/AudioRecord( 1945): set(): mSessionId 22
V/AudioPolicyManager(  286): getInput() inputSource 1999, samplingRate 16000, format 1, channelMask 10, session 22, flags 0
V/AudioPolicyManager(  286): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  286): isPlaybackThread 0,isRecordThread 1
D/audio_hw_primary(  286): adev_open_input_stream: enter: sample_rate(16000) channel_mask(0x10) devices(0x80000004)        stream_handle(0xb546e240)
V/audio_hw_primary(  286): adev_open_input_stream: exit
V/AudioFlinger(  286): openInput_l() openInputStream returned input 0xb546e240, SamplingRate 16000, Format 0x1, Channels 10, flags 0, status 0
V/AudioFlinger(  286): openInput_l() created record thread: ID 23 thread 0xb3c7b000
V/AudioSystem(  286): ioConfigChanged() event 3, ioHandle 23
V/AudioPolicyService(  286): AudioCommandThread() adding update audio port list
V/AudioSystem( 1758): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 3140): ioConfigChanged() event 3, ioHandle 23
V/AudioPolicyService(  286): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  286): AudioCommandThread() waking up
V/AudioPolicyService(  286): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  286): AudioCommandThread() going to sleep
V/AudioSystem(  850): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 1383): ioConfigChanged() event 3, ioHandle 23
,V/AudioSystem( 2686): ioConfigChanged() event 3, ioHandle 23
I/AudioFlinger(  286): AudioFlinger's thread 0xb3c7b000 ready to run
D/audio_hw_primary(  286): in_standby: enter: stream (0xb546e240) usecase(7: audio-record)
V/audio_hw_primary(  286): in_standby: exit:  status(0)
V/AudioSystem( 1945): ioConfigChanged() event 3, ioHandle 23
D/audio_hw_primary(  286): in_standby: enter: stream (0xb546e240) usecase(7: audio-record)
V/audio_hw_primary(  286): in_standby: exit:  status(0)
V/AudioFlinger(  286): RecordThread: loop stopping
V/AudioFlinger(  286): openRecord() lSessionId: 22 input 23
V/AudioFlinger(  286): getOrphanEffectChain_l session 22 index -2
V/AudioFlinger(  286): acquiring 22 from 1945, for -1
V/AudioFlinger(  286):  added new entry for 22
V/AudioRecord( 1945): start, sync event 0 trigger session 0
V/AudioRecord( 1945): mAudioRecord->start()
V/AudioFlinger(  286): RecordHandle::start()
V/AudioFlinger(  286): RecordThread::start event 0, triggerSession 0
V/AudioPolicyManager(  286): startInput() module primary->input primary(23)
V/AudioPolicyManager(  286): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  286): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  286): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  286): DeviceVector::getDevicesFromType() for type 80000004 found 0xb547b280
V/AudioPolicyService(  286): AudioCommandThread() adding create patch delay 0
V/AudioPolicyService(  286): inserting command: 7 at index 0, num commands 0
V/AudioPolicyService(  286): AudioCommandThread() waking up
V/AudioPolicyService(  286): AudioCommandThread() processing create audio patch
V/AudioFlinger::PatchPanel(  286): createAudioPatch() num_sources 1 num_sinks 1 handle 0
V/AudioFlinger::PatchPanel(  286): createAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters input_source=6;routing=-2147483644
V/AudioFlinger(  286): ThreadBase::setParameters() input_source=6;routing=-2147483644
V/AudioFlinger(  286): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  286): RecordThread: loop starting
V/AudioFlinger(  286): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  286): in_set_parameters: enter: kvpairs=input_source=6;routing=-2147483644
V/audio_hw_primary(  286): in_set_parameters: exit: status(0)
,V/AudioFlinger(  286): processConfigEvents_l() DONE thread 0xb3c7b000
V/AudioFlinger::PatchPanel(  286): createAudioPatch() status 0
V/AudioFlinger::PatchPanel(  286): createAudioPatch() added new patch handle 24 halHandle 0
V/AudioPolicyService(  286): AudioCommandThread() going to sleep
V/AudioPolicyManager(  286): setInputDevice() createAudioPatch returned 0 patchHandle 24
V/AudioPolicyManager(  286): addAudioPatch() handle 20 af handle 0 num_sources 1 num_sinks 1 source handle 10sink handle 19
V/AudioPolicyService(  286): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  286): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  286): AudioCommandThread() waking up
V/AudioPolicyService(  286): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  286): AudioCommandThread() adding set parameter string hotword_active=1, io 23 ,delay 0
V/AudioPolicyService(  286): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  286): AudioCommandThread() waking up
V/AudioPolicyService(  286): AudioCommandThread() processing set parameters string hotword_active=1, io 23
V/AudioFlinger(  286): setParameters(): io 23, keyvalue hotword_active=1, calling pid 286
V/AudioFlinger(  286): ThreadBase::setParameters() hotword_active=1
V/AudioFlinger(  286): sendConfigEvent_l() num events 1 event 2
V/AudioPolicyService(  286): AudioCommandThread() going to sleep
I/ActivityManager(  850): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=4253 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
V/AudioFlinger(  286): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  286): in_set_parameters: enter: kvpairs=hotword_active=1
V/audio_hw_primary(  286): in_set_parameters: exit: status(0)
V/AudioFlinger(  286): processConfigEvents_l() DONE thread 0xb3c7b000
V/AudioPolicyService(  286): AudioCommandThread() going to sleep
V/AudioPolicyManager(  286): AudioPolicyManager::startInput() input source = 1999
V/msm8974_platform(  286): platform_update_usecase_from_source: input source :6
D/audio_hw_primary(  286): start_input_stream: enter: stream(0xb546e240)usecase(7: audio-record)
V/voice   (  286): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  286): start_input_stream: usecase(7)
,E/audio_hw_primary(  286): select_devices: enter and usecase(7)
V/msm8974_platform(  286): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  286): platform_get_input_snd_device: exit: in_snd_device(voice-rec-mic)
V/msm8974_platform_lge(  286): LGE_platform_get_input_snd_device: exit: in_snd_device(lg-vr-handset-mic)
V/audio_hw_lge_primary(  286): LGE_exeption_scenario: enter and out: 0, in: 144
D/audio_hw_primary(  286): select_devices: out_snd_device(0: ) in_snd_device(144: lg-vr-handset-mic)
E/audio_hw_primary(  286): enable_snd_device: enter  144
D/hardware_info(  286): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  286): enable_snd_device: snd_device(144: lg-vr-handset-mic)
V/msm8974_platform_lge(  286): LGE_platform_send_audio_calibration: sending audio calibration for snd_Device(144) acdb_id(65)
D/ACDB-LOADER(  286): ACDB -> send_audio_cal, acdb_id = 65, path =  1
D/ACDB-LOADER(  286): ACDB -> send_adm_topology
D/ACDB-LOADER(  286): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/ACDB-LOADER(  286): ACDB -> send_asm_topology
D/ACDB-LOADER(  286): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  286): ACDB -> send_audtable
D/ACDB-LOADER(  286): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/ACDB-LOADER(  286): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  286): ACDB -> send_audvoltable
D/ACDB-LOADER(  286): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  286): Failed to fetch the lookup information of the device 00000041 
E/ACDB-LOADER(  286): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  286): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  286): ACDB -> AUDIO_SET_AFE_CAL
V/audio_hw_primary(  286): enable_audio_route: enter: usecase(7)
,V/msm8974_platform_lge(  286): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  286): enable_audio_route: apply mixer and update path: audio-record
V/audio_hw_primary(  286): enable_audio_route: exit
D/audio_hw_primary(  286): select_devices: done
V/audio_hw_primary(  286): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
V/audio_hw_primary(  286): start_input_stream: exit
I/MicrophoneInputStream( 1945): mic_started com.google.android.apps.gsa.speech.audio.u@2188bac6
,D/AndroidRuntime( 4189): Shutting down VM
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
I/NotificationService(  850): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  850): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/LCardEmulationManager( 1793): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1793): getDefaultRoute
D/JobSchedulerService(  850): Receieved: android.intent.action.PACKAGE_REMOVED
I/HotwordWorker( 1945): onReady
,D/PhoneStatusBar( 1383): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
I/[SystemUI]NavigationThemeResource( 1383): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1383):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1383): , Keyguard show=false, IME shown=false, Panel expanded=false
D/TaskPersister(  850): removeObsoleteFile: deleting file=220_task.xml
D/BarTransitions( 1383): draw background and invalidate : color = f9000000
D/BarTransitions( 1383): draw background and invalidate : color = f6ececec
,I/Timeline(  850): Timeline: Activity_windows_visible id: ActivityRecord{2f2a5d24 u0 com.lge.launcher2/.Launcher t219} time:58591
D/PowerService( 1810): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1383): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,I/[SystemUI]LGPowerUI( 1383): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1383): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1383): On Skip Timer : true
I/Gmail   ( 4192): getAccountsCursor
V/GLSActivity( 2013): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/[BNRBootReceiver]( 4253): boot receiver action = android.intent.action.BOOT_COMPLETED
,V/[BNRBootReceiver]( 4253): set property sys.lge.bnrd = 1
W/ResourcesManager(  850): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/[BNRBootCompletedThread]( 4253): run
V/[BNRBootReceiver]( 4253): End of BootComplted IF
V/[BNRBootReceiver]( 4253): Boot Receiver Return
W/linker  ( 4275): /system/bin/bnrd has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/bnrd    ( 4275): BNRD > wait starting [4275-3058102400] <
E/bnrd    ( 4275): /data/data/.bnr_fifo_req
V/[BNRBootCompletedThread]( 4253): End of BNRProcess
,V/[BNRBootCompletedThread]( 4253): End of BNRViaWifiProcess
I/ActivityManager(  850): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4281 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/[BNRBootCompletedThread]( 4253): End of SpriteProcess
V/[BNRBootCompletedThread]( 4253): exit
I/ActivityManager(  850): Killing 3760:com.lge.cloudhub/u0a49 (adj 15): empty #11
W/libprocessgroup(  850): failed to open /acct/uid_10049/pid_3760/cgroup.procs: No such file or directory
,W/ResourceType(  850): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1885): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/Gmail   ( 4192): notifyAccountChanged
,I/Gmail   ( 4192): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 4192): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4192): calculateUnknownSyncRationalesAndPurgeInBackground: running
,E/SQLiteDatabase( 2013): Failed to open database '/data/data/com.google.android.gms/databases/google_account_history.db'.
E/SQLiteDatabase( 2013): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2013): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2013): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/SQLiteDatabase( 2013): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/SQLiteDatabase( 2013): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/SQLiteDatabase( 2013): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/SQLiteDatabase( 2013): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2013): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/SQLiteDatabase( 2013): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/SQLiteDatabase( 2013): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/SQLiteDatabase( 2013): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 2013): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 2013): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2013): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2013): 	at com.google.android.gms.auth.be.p.e(SourceFile:221)
E/SQLiteDatabase( 2013): 	at com.google.android.gms.auth.be.p.a(SourceFile:120)
E/SQLiteDatabase( 2013): 	at com.google.android.gms.auth.be.o.a(SourceFile:618)
E/SQLiteDatabase( 2013): 	at com.google.android.gms.auth.be.n.a(SourceFile:450)
E/SQLiteDatabase( 2013): 	at com.google.android.gms.auth.firstparty.dataservice.aj.a(SourceFile:438)
E/SQLiteDatabase( 2013): 	at com.google.android.gms.auth.firstparty.dataservice.x.a(SourceFile:577)
E/SQLiteDatabase( 2013): 	at com.google.android.gms.auth.n.a(SourceFile:453)
E/SQLiteDatabase( 2013): 	at com.google.android.b.b.onTransact(SourceFile:107)
E/SQLiteDatabase( 2013): 	at android.os.Binder.execTransact(Binder.java:446)
,W/Auth    ( 2013): [GoogleAccountHistoryStore] error getting writeable database
W/Auth    ( 2013): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/Auth    ( 2013): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/Auth    ( 2013): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
W/Auth    ( 2013): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
W/Auth    ( 2013): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
W/Auth    ( 2013): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
W/Auth    ( 2013): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/Auth    ( 2013): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
W/Auth    ( 2013): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
W/Auth    ( 2013): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
W/Auth    ( 2013): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
W/Auth    ( 2013): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
W/Auth    ( 2013): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/Auth    ( 2013): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/Auth    ( 2013): 	at com.google.android.gms.auth.be.p.e(SourceFile:221)
W/Auth    ( 2013): 	at com.google.android.gms.auth.be.p.a(SourceFile:120)
W/Auth    ( 2013): 	at com.google.android.gms.auth.be.o.a(SourceFile:618)
W/Auth    ( 2013): 	at com.google.android.gms.auth.be.n.a(SourceFile:450)
W/Auth    ( 2013): 	at com.google.android.gms.auth.firstparty.dataservice.aj.a(SourceFile:438)
W/Auth    ( 2013): 	at com.google.android.gms.auth.firstparty.dataservice.x.a(SourceFile:577)
W/Auth    ( 2013): 	at com.google.android.gms.auth.n.a(SourceFile:453)
W/Auth    ( 2013): 	at com.google.android.b.b.onTransact(SourceFile:107)
W/Auth    ( 2013): 	at android.os.Binder.execTransact(Binder.java:446)
E/SQLiteDatabase( 2013): Failed to open database '/data/data/com.google.android.gms/databases/google_account_history.db'.
E/SQLiteDatabase( 2013): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2013): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2013): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/SQLiteDatabase( 2013): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/SQLiteDatabase( 2013): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/SQLiteDatabase( 2013): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/SQLiteDatabase( 2013): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2013): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/SQLiteDatabase( 2013): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/SQLiteDatabase( 2013): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/SQLiteDatabase( 2013): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 2013): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 2013): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2013): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2013): 	at com.google.android.gms.auth.be.p.e(SourceFile:221)
E/SQLiteDatabase( 2013): 	at com.google.android.gms.auth.be.p.a(SourceFile:120)
E/SQLiteDatabase( 2013): 	a,t com.google.android.gms.auth.be.o.a(SourceFile:618)
E/SQLiteDatabase( 2013): 	at com.google.android.gms.auth.be.n.a(SourceFile:450)
E/SQLiteDatabase( 2013): 	at com.google.android.gms.auth.firstparty.dataservice.aj.a(SourceFile:438)
E/SQLiteDatabase( 2013): 	at com.google.android.gms.auth.firstparty.dataservice.x.a(SourceFile:577)
E/SQLiteDatabase( 2013): 	at com.google.android.gms.auth.n.a(SourceFile:453)
E/SQLiteDatabase( 2013): 	at com.google.android.b.b.onTransact(SourceFile:107)
E/SQLiteDatabase( 2013): 	at android.os.Binder.execTransact(Binder.java:446)
W/Auth    ( 2013): [GoogleAccountHistoryStore] error getting writeable database
W/Auth    ( 2013): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/Auth    ( 2013): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/Auth    ( 2013): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
W/Auth    ( 2013): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
W/Auth    ( 2013): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
W/Auth    ( 2013): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
W/Auth    ( 2013): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/Auth    ( 2013): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
W/Auth    ( 2013): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
W/Auth    ( 2013): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
W/Auth    ( 2013): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
W/Auth    ( 2013): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
W/Auth    ( 2013): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/Auth    ( 2013): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/Auth    ( 2013): 	at com.google.android.gms.auth.be.p.e(SourceFile:221)
W/Auth    ( 2013): 	at com.google.android.gms.auth.be.p.a(SourceFile:120)
W/Auth    ( 2013): 	at com.google.android.gms.auth.be.o.a(SourceFile:618)
W/Auth    ( 2013): 	at com.google.android.gms.auth.be.n.a(SourceFile:450)
W/Auth    ( 2013): 	at com.google.android.gms.auth.firstparty.dataservice.aj.a(SourceFile:438)
W/Auth    ( 2013): 	at com.google.android.gms.auth.firstparty.dataservice.x.a(SourceFile:577)
W/Auth    ( 2013): 	at com.google.android.gms.auth.n.a(SourceFile:453)
W/Auth    ( 2013): 	at com.google.android.b.b.onTransact(SourceFile:107)
W/Auth    ( 2013): 	at android.os.Binder.execTransact(Binder.java:446)

```
