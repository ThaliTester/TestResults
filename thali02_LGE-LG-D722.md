#### Test 50388019809f971_thali02_LGE-LG-D722 Logs


```
--------- beginning of system
I/ActivityManager(  849): Start proc com.lge.appbox.client for content provider com.lge.appbox.client/com.lge.appbox.databases.AppBoxContentProvider: pid=3563 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
--------- beginning of main
I/AppUp4:AppBoxCP( 3563): onCreate
W/AppUp4:DB( 3563):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 3563):  setFingerPrint start
I/AppUp4:DB( 3563):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 3563):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 3563):  SDK version = 0
I/AppUp4:DB( 3563):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 3563): AppBoxApplication onCreate()
D/AppUp4:SingleBinary( 3544):  The value of isFingerChanged null
D/AppUp4:SingleBinary( 3544): Device : jagnm
D/AppUp4:SingleBinary( 3544): First Boot - ignore boot completed
D/AppUp4:NTCodeSingleBinary( 3544): Starting isFingerChanged 
D/AppUp4:NTCodeSingleBinary( 3544): The value of isFingerChanged lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
D/AppUp4:SingleBinary( 3544): Device : jagnm
D/AppUp4:SingleBinary( 3544): Config file is not exist - nothing
I/ActivityManager(  849): Killing 3216:com.android.contacts/u0a18 (adj 15): empty #11
W/libprocessgroup(  849): failed to open /acct/uid_10018/pid_3216/cgroup.procs: No such file or directory
I/AppUp4:SDKReflector( 3563): +myUserId : 0
D/AppUp4:BootUpPollingReceiver( 3563): onReceive on user ID : 0
V/AppUp4:FotaPlusService( 3563):  isFotaPlusTriedOnce : true
D/AppUp4:BootUpPollingReceiver( 3563): Starting getSdkVersion 
D/AppUp4:BootUpPollingReceiver( 3563): SDK version is : 0
D/AppUp4:BootUpPollingReceiver( 3563): currentSdkVersion : 0
D/AppUp4:BootUpPollingReceiver( 3563): isSdkVersionChanged : true
V/AppUp4:FotaPlusService( 3563):  setFotaPlusCompleted : false
D/AppUp4:BootUpPollingReceiver( 3563): isFotaPlusNeeded : true
D/AppUp4:BootUpPollingReceiver( 3563): Fota Plus already tried once, show notification
V/NotificationService(  849): enqueueNotificationInternal: pkg=com.lge.appbox.client id=22319582 notification=Notification(pri=0 contentView=null vibrate=default sound=default defaults=0x3 flags=0x2 color=0x00000000 vis=PRIVATE)
D/AppUp4:BootUpPollingReceiver( 3563): isFotaPlusRunning after : true
D/AppUp4:BootUpPollingReceiver( 3563):  installPreloadedValuePackIfNeeded 
D/ZenLog  (  849): intercepted: 0|com.lge.appbox.client|22319582|null|10011,none
D/AppUp4:BootUpPollingReceiver( 3563):  file is : /system/apps/bootup
D/AppUp4:BootUpPollingReceiver( 3563): file false
V/NotificationService(  849): pkg=com.lge.appbox.client canInterrupt=false intercept=true
D/AppUp4:BootUpPollingReceiver( 3563): [BootUpPollingReceiver] No preload installation.
I/NotificationServiceEx(  849): LED remove() : mLights=0|com.lge.appbox.client|22319582|null|10011
D/NotificationServiceEx(  849): updateLightListLocked :r=0|com.lge.appbox.client|22319582|null|10011, action=2
D/NotificationServiceEx(  849): notification=Notification(pri=0 contentView=null vibrate=default sound=default defaults=0x3 flags=0x2 color=0x00000000 vis=PRIVATE)
D/AppUp4:dwnld( 3563): [removeAllIncompletedDownload] ... 
D/SmartCoverUpdateMonitor( 1330): onNotificationPosted() : StatusBarNotification(pkg=com.lge.appbox.client user=UserHandle{0} id=22319582 tag=null score=0 key=0|com.lge.appbox.client|22319582|null|10011: Notification(pri=0 contentView=com.lge.appbox.client/0x1090079 vibrate=default sound=default defaults=0x3 flags=0x2 color=0x00000000 vis=PRIVATE))
D/SmartCoverUpdateMonitor( 1330): onNotificationPosted() !qcn.isEnableToShowNotification()
V/AppUp4:BootUpPollingReceiver( 3563): [BootUpPollingReceiver] start bootup Polling.
I/CalendarProvider2( 3461): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
D/AppUp4  ( 3563): getUpdatePollingPeriod
W/ContentResolver( 3461): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
D/AppUp4  ( 3563): getUpdatePollingPeriod
D/AppUp4:BackgroundPollingService ( 3563): register polling alarm when : 2015/12/03 21:30:18
D/AppUp4:LightWeightPollingService ( 3563):  [buildRemotePollingIntent]
D/AppUp4:LightWeightPollingService ( 3563): This means remote config is N, so skip it
I/ActivityManager(  849): Killing 3322:com.android.keychain/1000 (adj 15): empty #11
W/libprocessgroup(  849): failed to open /acct/uid_1000/pid_3322/cgroup.procs: No such file or directory
I/ActivityManager(  849): Killing 3239:com.lge.hiddenmenu/1000 (adj 15): empty #11
W/libprocessgroup(  849): failed to open /acct/uid_1000/pid_3239/cgroup.procs: No such file or directory
D/AndroidRuntime( 3587): 
D/AndroidRuntime( 3587): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3587): CheckJNI is OFF
I/art     (  849): Explicit concurrent mark sweep GC freed 14638(772KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 22MB/33MB, paused 2.622ms total 167.288ms
I/ActivityManager(  849): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=3615 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/MmsConfig( 3139): isNotAllowedSms: currentUser:0
D/MmsConfig( 3139): isNotAllowedSms: UserHandle.myUserId():0
D/MmsConfig( 3139): isUserMode:false
D/SmsReceiverService( 3139): handleMessage isUserMode:false
I/[SystemUI]PhoneStatusBar( 1369): updateMediaMetaData(false): mMediaMetadata = null
W/ResourcesManager( 3139): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
V/SmsReceiverService( 3139): handleMessage action: android.intent.action.BOOT_COMPLETED error: 0
W/ResourcesManager( 3615): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/AndroidRuntime( 3587): Calling main entry com.android.commands.am.Am
I/ActivityManager(  849): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  849): setTaskToReturnTo : TaskRecord{3efa9aa8 #220 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  849): setTaskToReturnTo : TaskRecord{3efa9aa8 #220 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  849): AppWindowTokenEx init.. 
D/InputDispatcher(  849): Focus left window: Window{908f5c2 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 3587): Shutting down VM
D/ContextHelper(  849): convertTheme. context->name=com.example.hello themeResourceId=16973833
I/[LGHome]EVENT( 1877): [Launcher.java:986:onPause()]onPause
D/SplitWindow(  849): check instance of lgWin Window{ecea1f2 u0 Starting com.example.hello}
I/ActivityManager(  849): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3635 uid=10030 gids={50030, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/CalendarApplication( 3615): CalendarApplication.onCreate()
I/art     (  300): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 333us total 22.866ms
I/[LGHome]EVENT( 1877): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/HotwordDetector( 1949): Closing mic
I/MicrophoneInputStream( 1949): mic_close com.google.android.apps.gsa.speech.audio.u@1ef46f4c
V/AudioRecord( 1949): stop()
D/AudioRecord( 1949): AudioRecord->stop()
V/AudioFlinger(  282): RecordHandle::stop()
V/AudioFlinger(  282): RecordThread::stop
I/art     (  300): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 23.789ms
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
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb42a5000
D/audio_hw_primary(  282): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
I/art     (  300): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 295us total 22.353ms
I/[LGHome]EVENT( 1877): [Launcher.java:5214:onStop()]onStop
D/PreferenceKeysParser( 3615): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 3615): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@a5eab7a, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@1cea5f2b, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@3f0bcf88, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@3c72fd21, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2e9c0546, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@3c2dc307, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@2f525c34, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@2614a5d, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@9032fd2, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@1d5988a3, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@17d307a0, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@36ed2f59, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@1f40771e, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@31f20bff, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@9f0fdcc, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@b86815, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@1378e72a, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@1565691b, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@28162ab8, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@14c47091, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@13164bf6, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@21e77bf7, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@f5f3a64, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@1cae84cd, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@26533182, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@370de093, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@300798d0, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@4aba0c9, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@2c86e3ce, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@e2bf2ef, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@9571fc, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@2d448085, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@11316eda, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@386ecf0b, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@37c5b1e8, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@3cd1a001, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@5c79ea6, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@22b950e7, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@39380494, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@cb73b3d, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@c3eff32, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@3b401483, lg
D/GeneralPreferenceUtils( 3615): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
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
D/audio_hw_primary(  282): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  282): in_set_parameters: exit: status(0)
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb42a5000
V/AudioFlinger(  282): RecordThread: loop stopping
D/Config  ( 3615): [init]
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
I/WindowStateAnimator(  849): Starting window displayed
I/Config  ( 3615): LGCalendar ver.4.40.17
I/Config  ( 3615): start check model
I/Config  ( 3615): start check native_ca
I/Config  ( 3615): Config Operator=OPEN, Country=EU
D/Config  ( 3615): [setDefaultValuesToPref]
D/Config  ( 3615): [parseProfiles]
V/AudioRecord( 1949): stop()
I/SystemUI[Framework](  849): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.example.hello
W/PhoneWindowManagerEx(  849): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  849): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  849): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  849): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1c068e7a,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  849): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
V/AudioRecord( 1949): stop()
V/AudioRecord( 1949): stop()
D/PhoneStatusBar( 1369): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
I/[SystemUI]NavigationThemeResource( 1369): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1369):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1369): , Keyguard show=false, IME shown=false, Panel expanded=false
V/AudioFlinger(  282): RecordHandle::stop()
V/AudioFlinger(  282): RecordThread::stop
V/AudioPolicyManager(  282): releaseInput() 17
V/AudioPolicyManager(  282): closeInput(17)
V/AudioFlinger(  282): closeInput() 17
V/AudioSystem(  282): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1949): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): ThreadBase::exit
V/AudioSystem( 1748): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2700): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): releasing 16 from 1949 for -1
V/AudioFlinger(  282):  decremented refcount to 0
V/AudioSystem( 3139): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): purging stale effects
V/AudioSystem( 1369): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  849): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): RecordThread: loop starting
V/AudioFlinger(  282): RecordThread 0xb42a5000 exiting
D/audio_hw_primary(  282): adev_close_input_stream: enter:stream_handle(0xb4036520)
D/audio_hw_primary(  282): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioPolicyService(  282): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  282): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyManager(  282): releaseInput() exit
V/AudioFlinger(  282): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  282): removeClient_l() pid 1949, calling pid 282
I/HotwordRecognitionRnr( 1949): Hotword detection finished
I/HotwordRecognitionRnr( 1949): Stopping hotword detection.
D/BarTransitions( 1369): draw background and invalidate : color = 14000000
D/BarTransitions( 1369): draw background and invalidate : color = 15141414
D/ProfilesParser( 3615): [debug_displayParseInfos] profile.country = null
,D/ProfilesParser( 3615): [debug_displayParseInfos] profile.operator = null
D/Config  ( 3615): [updateProfiletoCountryInfo]
D/GeneralPreference( 3615): [checkAndMigrateOldPreference]
D/AlertReceiver( 3615): onReceive: a=android.intent.action.BOOT_COMPLETED Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.calendar/.alerts.AlertReceiver (has extras) }
I/InitNotificationRingtoneService( 3615): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 3615): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
I/ActivityManager(  849): Start proc com.android.settings for broadcast com.android.settings/.lockscreen.LockSettingsReceiver: pid=3656 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
D/ContextHelper( 3635): convertTheme. context->name=com.example.hello themeResourceId=16973833
W/ResourcesManager( 3656): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3656): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 3656): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 3656): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 3656): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/WebViewFactory( 3635): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/AlertUtils( 3615): [getCalendarNotiSoundURIFromCursor] getCount()= 21
I/AlertUtils( 3615): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 3615): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 3615): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 3615): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 3615): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/IndexDatabaseHelper( 3656): Using schema version: 115
I/IndexDatabaseHelper( 3656): Index is fine
I/AlertUtils( 3615): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 3615): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/LibraryLoader( 3635): Time to load native libraries: 2 ms (timestamps 9939-9941)
I/LibraryLoader( 3635): Expected native library version number "",actual native library version number ""
I/AlertUtils( 3615): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 3615): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 3615): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 3615): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 3615): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
V/WebViewChromiumFactoryProvider( 3635): Binding Chromium to main looper Looper (main, tid 1) {3c72fd21}
I/LibraryLoader( 3635): Expected native library version number "",actual native library version number ""
I/chromium( 3635): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/AlertUtils( 3615): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 3615): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 3615): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3615): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 3615): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 3615): End InitializeAlertRingtoneService.onHandleIntent
I/BrowserStartupController( 3635): Initializing chromium process, singleProcess=true
W/art     ( 3635): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3635): ApplicationContext is null in ApplicationStatus
W/chromium( 3635): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 3635): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3635): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3635): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3635): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 3635): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 3635): Build Date: 03/02/15 Mon
I/Adreno-EGL( 3635): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 3635): Remote Branch: 
I/Adreno-EGL( 3635): Local Patches: 
I/Adreno-EGL( 3635): Reconstruct Branch: 
D/UsbSettingsReceiver( 3656): [AUTORUN] onReceive() : action = android.intent.action.BOOT_COMPLETED
D/UsbSettingsReceiver( 3656): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 3656): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 3656): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 3656): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 3656): [AUTORUN] setTetherStatus() : status=false
D/UsbSettingsReceiver( 3656): [AUTORUN] onReceive() : android.intent.action.BOOT_COMPLETED
D/UsbSettingsReceiver( 3656): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 3656): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 3656): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/StoreModeReceiver( 3656): intent.getAction() : android.intent.action.BOOT_COMPLETED
D/StoreModeReceiver( 3656): sim state :null
D/StoreModeReceiver( 3656): Back LED don't supported.
V/AudioPolicyService(  282): registerClient() client 0xb4027820, uid 10030
V/SettingsProvider(  849): call_put(system:emotional_led_back_led=0) for 0 calling package = com.android.settings
V/SettingsProvider(  849): call_put(system:emotional_led_back_incoming_call=0) for 0 calling package = com.android.settings
V/SettingsProvider(  849): call_put(system:emotional_led_back_alarm=0) for 0 calling package = com.android.settings
D/BluetoothManagerService(  849): Message: 20
D/BluetoothManagerService(  849): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@24886033:true
V/SettingsProvider(  849): call_put(system:emotional_led_back_missed_call=0) for 0 calling package = com.android.settings
V/SettingsProvider(  849): call_put(system:emotional_led_back_missed_messages=0) for 0 calling package = com.android.settings
V/SettingsProvider(  849): call_put(system:emotional_led_back_missed_emails=0) for 0 calling package = com.android.settings
V/SettingsProvider(  849): call_put(system:emotional_led_back_calendar_noti=0) for 0 calling package = com.android.settings
V/SettingsProvider(  849): call_put(system:emotional_led_back_voice_recording=0) for 0 calling package = com.android.settings
D/BluetoothAdapter( 3635): 151203794: getState() :  mService = null. Returning STATE_OFF
V/SettingsProvider(  849): call_put(system:emotional_led_back_camera_timer_noti=0) for 0 calling package = com.android.settings
V/SettingsProvider(  849): call_put(system:emotional_led_back_camera_face_detecting_noti=0) for 0 calling package = com.android.settings
V/SettingsProvider(  849): call_put(system:notification_light_pulse_back=0) for 0 calling package = com.android.settings
D/StoreModeReceiver( 3656): SystemProperty Default brightness value [0-255] : 143
D/StoreModeReceiver( 3656): Default brightness[0-255] : 143
W/HolidayIntentService( 3615): onHandleIntent
W/ResourcesManager( 3656): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/StoreModeReceiver( 3656): Default Screen off timeout value : 30000
D/StoreModeReceiver( 3656): SystemProperty Default brightness Mode value[true/false] : false
D/HolidayDataLoader( 3615): readJsonAsset : holiday.json
D/StoreModeReceiver( 3656): BRIGHTNESS_MODE - 0
D/StoreModeReceiver( 3656): Default brightness Mode [0/1] : 0
D/StoreModeReceiver( 3656): Default NIGHT_MODE : 0
D/StoreModeReceiver( 3656): Set MaxBrightness : 255
E/PhoneInterfaceManager( 1748): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
D/StoreModeReceiver( 3656): getPhoneNumber is empty
D/StoreModeReceiver( 3656): go to StoreModeCheck()
D/StoreModeReceiver( 3656): isStoremode not null
D/PhoneInterfaceManager( 1748): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
V/SettingsProvider(  849): call_put(system:shop_mode_check=1) for 0 calling package = com.android.settings
D/AlertService( 3615): 0 Action = android.intent.action.BOOT_COMPLETED
D/AlertService( 3615): [Widget]com.android.calendar.widget.CalendarAppWidgetProvider enabled
D/Feature ( 3615): MemoryLevel - 5:NOT_DEF:Not UI4.2 LOS
D/AlertService( 3615): [Widget]com.android.calendar.widget.MonthWidgetProvider enabled
D/AlertService( 3615): [Widget]com.android.calendar.widget.WeekWidgetProvider enabled
,D/StoreModeReceiver( 3656): product_name : jagnm_global_com
D/StoreModeReceiver( 3656): Store mode start!
V/SettingsProvider(  849): call_put(system:shop_mode=1) for 0 calling package = com.android.settings
V/SettingsProvider(  849): call_put(system:shop_mode_check=1) for 0 calling package = com.android.settings
,I/PowerManagerService(  849): ALS enabled for SRE
D/PowerManagerServiceEx(  849): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x1, nextTimeout=120000 (in 69767 ms)
D/StoreModeReceiver( 3656): setBrightness() : NoMultiALC=255
D/AlertService( 3615): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
W/ContextImpl( 3656): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.StoreModeReceiver.sendBroadcast:500 com.android.settings.StoreModeReceiver.setMode:473 
V/SettingsProvider(  849): call_put(system:screen_brightness_mode=0) for 0 calling package = com.android.settings
,D/SettingsProvider(  849): Set screen_off_timeout in entry value : 120000
V/SettingsProvider(  849): call_put(system:screen_off_timeout=120000) for 0 calling package = com.android.settings
V/SettingsProvider(  849): call_put(system:screen_brightness=255) for 0 calling package = com.android.settings
V/SettingsProvider(  849): call_put(system:check_night_mode=0) for 0 calling package = com.android.settings
,D/SettingBootReceiver( 3656): onReceive
D/SettingBootReceiver( 3656): Boot Completed intent received, action=android.intent.action.BOOT_COMPLETED
D/SettingBootReceiver( 3656): setStyle()
,D/SettingBootReceiver( 3656): SettingStyle=1
I/[SystemUI]LGBootReceiver( 1369): onReceive = android.intent.action.BOOT_COMPLETED
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.statusbar.bootcompleted
D/SettingBootReceiver( 3656): com.lge.appwidget.settings.powercontrol is not installed.(Successfully Removed)
D/AlarmScheduler( 3615): No events found starting within 1 week.
D/SettingBootReceiver( 3656): com.lge.appwidget.settings.powercontrol is not installed.(Successfully Removed)
D/SettingBootReceiver( 3656): setAccountMenu()
D/SettingBootReceiver( 3656): com.lge.appwidget.settings.powercontrol is not installed.(Successfully Removed)
,D/TAG     ( 3656): setKidsMode
D/TAG     ( 3656): mIsOwner, setKidsMode
D/SettingBootReceiver( 3656): setAccountMenu()
E/HolidayIntentService( 3615): onHandleIntent:holiday data empty
I/[SystemUI]PhoneStatusBar( 1369): got ACTION_STICKY_BOOT_COMPLETED
I/BOOT    ( 1369): got ACTION_STICKY_BOOT_COMPLETED
D/YSY     ( 3656): not support Quiet mode notification
,I/ActivityManager(  849): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3701 uid=10111 gids={50111, 9997, 1028, 3003} abi=armeabi-v7a
,I/ActivityManager(  849): Killing 3351:com.google.android.onetimeinitializer/u0a8 (adj 15): empty #11
W/libprocessgroup(  849): failed to open /acct/uid_10008/pid_3351/cgroup.procs: No such file or directory
,W/art     ( 3635): Attempt to remove local handle scope entry from IRT, ignoring
,V/SettingsProvider(  849): call_put(system:gentle_vibration_status=1) for 0 calling package = com.android.settings
,W/AwContents( 3635): onDetachedFromWindow called when already detached. Ignoring
V/SettingsProvider(  849): call_put(system:smart_ringtone=0) for 0 calling package = com.android.settings
,D/SettingBootReceiver( 3656): timezoneID is null
D/SystemWebViewEngine( 3635): CordovaWebView is running on device made by: LGE
I/SettingBootReceiver( 3656): disable au
I/TAG     ( 3656): disable WirelessSettingsActivity
,W/art     ( 3635): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3635): Attempt to remove local handle scope entry from IRT, ignoring
I/TAG     ( 3656): disable SKTPhoneMode
I/ActivityManager(  849): Killing 3370:com.android.cellbroadcastreceiver/u0a16 (adj 15): empty #11
,D/SettingBootReceiver( 3656): [Nightmode] Enter receiver
D/SettingBootReceiver( 3656): [Nightmode] BOOT_COMPLETED
D/NightModeInfo( 3656): [Nightmode] setNightNodeTabSettings
,D/NightModeInfo( 3656): [Nightmode] getAlreadyNightModeDB() : 0
D/NightModeInfo( 3656): [Nightmode] getUserBrightnessChange() : 0
D/NightModeInfo( 3656): [Nightmode] getUserBrightnessChangeNoNight() : 0
V/SettingsProvider(  849): call_put(system:already_night_mode=0) for 0 calling package = com.android.settings
V/SettingsProvider(  849): call_put(system:user_change_brightness=0) for 0 calling package = com.android.settings
V/SettingsProvider(  849): call_put(system:user_change_brightness_no_night=0) for 0 calling package = com.android.settings
,V/SettingsProvider(  849): call_put(system:night_mode_enabled=0) for 0 calling package = com.android.settings
D/NightModeInfo( 3656): [Nightmode] setTabNightCheck : 0
V/SettingsProvider(  849): call_put(system:save_tab_night_check=0) for 0 calling package = com.android.settings
,D/NightModeInfo( 3656): [Nightmode] cancelPendingIntent
W/libprocessgroup(  849): failed to open /acct/uid_10016/pid_3370/cgroup.procs: No such file or directory
,I/Activity( 3635): Activity.onPostResume() called 
D/NightModeInfo( 3656): [Nightmode] requestPendingIntent
D/NightModeInfo( 3656): [Nightmode] setAlarmStart~!!~!!~!!
D/NightModeInfo( 3656): [Nightmode] currentHour > 6
V/DownloadManager( 2737): Received broadcast intent for android.intent.action.BOOT_COMPLETED
D/NightModeInfo( 3656): [Nightmode] currentHour > 6
D/OpenGLRenderer( 3635): Render dirty regions requested: true
I/OpenGLRenderer( 3635): Initialized EGL, version 1.4
,V/DownloadManager( 2737): DownloadService onCreate
I/NightModeInfo( 3656): JW getStartTime201511290000
D/NightModeInfo( 3656): [Nightmode] setAlarmEnd~!!~!!~!!
D/NightModeInfo( 3656): [Nightmode] currentHour > 6
D/NightModeInfo( 3656): [Nightmode] currentHour > 6
I/NightModeInfo( 3656): JW getEndTime201511290600
D/NightModeInfo( 3656): [Nightmode] currentHour > 6
I/NightModeInfo( 3656): getStartTime201511290000
D/OpenGLRenderer( 3635): Enabling debug mode 0
D/NightModeInfo( 3656): [Nightmode] currentHour > 6
I/DownloadManager( 2737): in removeSpuriousFiles
I/NotificationManager( 2737): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/NightModeInfo( 3656): getEndTime201511290600
D/jw      ( 3656): Only VZW Supported end return
V/DownloadManager( 2737): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 2737): created cursor android.database.sqlite.SQLiteCursor@13164bf6 on behalf of 2737
,I/DownloadManager( 2737): in trimDatabase
V/DownloadManager( 2737): DownloadService onStartCommand
V/DownloadManager( 2737): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/MediaScannerReceiver( 2737): [MediaScanner] ACTION_BOOT_COMPLETED scan INTERNAL_VOLUME, EXTERNAL_VOLUME
V/DownloadManager( 2737): created cursor android.database.sqlite.SQLiteCursor@1cae84cd on behalf of 2737
V/DownloadManager( 2737): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 2737): created cursor android.database.sqlite.SQLiteCursor@26533182 on behalf of 2737
D/Atlas   ( 3635): Validating map...
,D/SplitWindow(  849): check instance of lgWin Window{1609434c u0 com.example.hello/com.example.hello.MainActivity}
D/MediaScannerService( 2737): [MediaScanner] start scanning volume internal: [/system/media, /oem/media, /cust/OPEN_EU/media]
W/chromium( 3635): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/LGMediaProvider( 2737): insertInternal: content://media/none/media_scanner, initValues=volume=internal
D/MediaScannerService( 2737): [MediaScanner] scan() ACTION_MEDIA_SCANNER_STARTED uri : file:///system/media
I/MusicBrowser( 2700): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_STARTED dat=file:///system/media flg=0x10 }}
,I/MusicBrowser( 2700): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 2700): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_STARTED
D/MtpService( 2737): updating state; isCurrentUser=true, mMtpLocked=false
D/WiseScreenService( 1821): [OnBootReceiver.java:24:onReceive()] iKeepScreenOn: 0
,D/MtpService( 2737): addStorageLocked 65537 /storage/emulated/0
E/MtpStorageEx( 2737): setAccessCapability false
D/WiseScreenService( 1821): [OnBootReceiver.java:28:onReceive()] iSmartVideo: 0
D/MtpService( 2737): updating state; isCurrentUser=true, mMtpLocked=false
W/ContextImpl( 1821): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1804 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.lge.keepscreenon.OnBootReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2663 
D/InputDispatcher(  849): Focus entered window: Window{1609434c u0 com.example.hello/com.example.hello.MainActivity}
,D/MediaScannerEx( 2737): [MediaScanner] scanDirectories()[0] = /system/media
D/MediaScannerEx( 2737): [MediaScanner] scanDirectories()[1] = /oem/media
D/MediaScannerEx( 2737): [MediaScanner] scanDirectories()[2] = /cust/OPEN_EU/media
,I/art     ( 2737): Thread[1,tid=2737,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31f8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
I/ActivityManager(  849): Start proc com.lge.voicerecorder for broadcast com.lge.voicerecorder/.bookmarkdb.BootCompletedReceiver: pid=3731 uid=10034 gids={50034, 9997, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
E/MediaProfilesEx-JNI( 2737): register_com_lge_media_MediaProfilesEx
E/MediaRecorderEx-JNI( 2737): register_com_lge_media_MediaRecorderEx
,D/AudioSystemEx( 2737): register_com_lge_media_LGAudioSystem
E/SurfaceControlEx( 2737): register_com_lge_view_SurfaceControlEx
I/art     ( 2737): Thread[1,tid=2737,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31f8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
D/LGMtpDatabaseJNI( 2737): register_android_mtp_LGMtpDatabase
D/LGMtpServerJNI( 2737): register_android_mtp_LGMtpServer
I/art     ( 2737): Thread[1,tid=2737,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31f8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
E/MediaPlayerEx-jni( 2737): register_com_lge_view_MediaPlayerEx
I/art     ( 2737): Thread[1,tid=2737,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31f8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
D/        ( 2737): register_com_lge_emoji_EmojiUtil
E/LGMtpDatabaseJNI( 2737): android_mtp_LGMtpDatabase_setup
D/MtpService( 2737): starting MTP server in PTP mode
D/LGMtpServer( 2737): LGMtpServer
D/LGMtpServerJNI( 2737): android_mtp_LGMtpServer_setup
,W/InputMethodManagerService(  849): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
D/MtpService( 2737): addStorageLocked 65537 /storage/emulated/0
E/MtpStorageEx( 2737): setAccessCapability false
D/MtpServerEx( 2737): ANR FIX - addStorage!
I/ActivityManager(  849): Displayed com.example.hello/.MainActivity: +1s306ms
I/Timeline(  849): Timeline: Activity_windows_visible id: ActivityRecord{31c339c1 u0 com.example.hello/.MainActivity t220} time:50773
,I/Timeline( 3635): Timeline: Activity_idle id: android.os.BinderProxy@1cae84cd time:50775
D/LGMtpServerJNI( 2737): android_mtp_LGMtpServer_run
V/DownloadManager( 2737): DownloadService onDestroy
,I/ActivityManager(  849): Waited long enough for: ServiceRecord{15f11a5e u0 com.lge.sizechangable.musicwidget.widget/.service.MusicWidgetUpdater}
,V/MediaScannerClient( 2737): [MediaScanner]setLocale: = en_US
E/MediaFileEx( 2737): Duplicate type = AVI
E/MediaFileEx( 2737): Duplicate type = ASF
,V/MediaScannerClient( 2737): [MediaScanner]setLocale: = en_US
W/MediaScanner( 2737): Error opening directory '/oem/media/', skipping: No such file or directory.
,V/MediaScannerClient( 2737): [MediaScanner]setLocale: = en_US
W/MediaScanner( 2737): Error opening directory '/cust/OPEN_EU/media/', skipping: No such file or directory.
D/LGMediaProvider( 2737): [MediaScanner] delete() uri = content://media/internal/file
I/VRBookmarkProvider( 3731): [BookmarkProvider.java:76:<init>()-[Thread:Other] BookmarkProvider
D/LGMediaProvider( 2737): [MediaScanner] delete() completed notifyChange, uri = content://media/internal
V/MediaScannerEx( 2737): [MediaScanner] isInternalStorage : true
,I/VRBookmarkProvider( 3731): [BookmarkProvider.java:254:onCreate()-[Thread:Other] onCreate
V/MediaScannerEx( 2737): [MediaScanner] isInternalStorage : true
I/VRBookmarkProvider( 3731): [BookmarkProvider.java:504:registerObservers()-[Thread:Other] registerObservers : content://media/external/audio/media
V/MediaScannerEx( 2737): [MediaScanner] isInternalStorage : true
D/MediaScanner( 2737): [MediaScanner] prescan time: 133ms
D/MediaScanner( 2737): [MediaScanner] scan time: 37ms
D/MediaScanner( 2737): [MediaScanner] postscan time: 26ms
D/MediaScanner( 2737): [MediaScanner] total time: 196ms
D/LGMediaProvider( 2737): [MediaScanner] delete() uri = content://media/none/media_scanner
D/VRBootCompletedReceiver( 3731): [BootCompletedReceiver.java:25:onReceive()-[Thread:Other] Controller has been started on Boot complete
,D/VRBootCompletedReceiver( 3731): [BootCompletedReceiver.java:47:onReceive()-[Thread:Other] Voice Recorder launcher enable(1)/disable(2) : 1
I/ActivityManager(  849): Killing 3389:com.lge.email/u0a21 (adj 15): empty #11
W/BindingManager( 3635): Cannot call determinedVisibility() - never saw a connection for the pid: 3635
,W/libprocessgroup(  849): failed to open /acct/uid_10021/pid_3389/cgroup.procs: No such file or directory
D/LGBootCompleteReceiver( 1748): onReceive : android.intent.action.BOOT_COMPLETED
,D/ConfigUtils( 1748): setUsimOperator() : card operator = 
D/ConfigUtils( 1748): setUsimOperator() : result = null
D/ConfigUtils( 1748): setUsimOperator() : simOperator = 
D/ConfigUtils( 1748): setUsimOperator() : usimoperator = 0
D/ConfigUtils( 1748): setSupportedUsimMobilityForVoLTE() : false
D/MediaScannerService( 2737): [MediaScanner] scan() Send Intent ACTION_MEDIA_SCANNER_FINISHED uri : file:///system/media
D/LGMediaProvider( 2737): [MediaScanner] mUnmountReceiver ACTION_MEDIA_SCANNER_FINISHED : uri = file:///system/media, path = /system/media
I/MusicBrowser( 2700): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///system/media flg=0x10 }}
D/ConfigUtils( 1748): This Model Voice Clarity Support : false
D/MediaScannerService( 2737): [MediaScanner] done scanning volume internal
D/MediaScannerService( 2737): [MediaScanner] start scanning volume external: [/storage/emulated/0, /storage/external_SD]
,D/LGBootCompleteReceiver( 1748): onReceive : updateCallrejectNotify rejectCallOption : 1
V/LGMediaProvider( 2737): insertInternal: content://media/none/media_scanner, initValues=volume=external
D/MediaScannerService( 2737): [MediaScanner] scan() ACTION_MEDIA_SCANNER_STARTED uri : file:///storage/emulated/0
I/MusicBrowser( 2700): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 2700): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_FINISHED
V/LGMediaProvider( 2737): insertInternal: content://media/, initValues=name=external
I/MusicWidget( 2601): _mediaDataObserver onChange()
W/VRBookmarkProvider( 3731): [BookmarkProvider.java:546:onChange()-[Thread:Other] Data Change!! false url : content://media/
,I/MusicWidget( 2601): beingMusicWidget_4x2() result::false
D/CallRejectInfoToNotify( 1748): update : tPhoneMode : false
I/NotificationManager( 1748): com.android.phone: cancel(2131493582) by com.android.phone
I/PhoneApp( 1748): saveDefaultRingtoneUriOfOwner = content://media/internal/audio/media/55
I/MusicBrowser( 2700): [MediaPlaybackService.java:reloadQueue()] oooooo 
D/MusicBrowser( 2700): [MediaPlaybackService.java:reloadQueue()] oooooo id=-1
,D/MusicBrowser( 2700): [MediaPlaybackService.java:reloadQueue()] oooooo mCardId=-1
D/MusicBrowser( 2700): [MediaPlaybackService.java:reloadQueue()] oooooo mPreferences.id=-1
D/MusicBrowser( 2700): [MediaPlaybackService.java:reloadQueue()] oooooo q=
D/MusicBrowser( 2700): [MediaPlaybackService.java:reloadQueue()] oooooo q.length=0
D/MusicBrowser( 2700): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.queuechanged}
D/MediaScannerEx( 2737): [MediaScanner] scanDirectories()[0] = /storage/emulated/0
I/MusicBrowser( 2700): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
D/MediaScannerEx( 2737): [MediaScanner] scanDirectories()[1] = /storage/external_SD
D/MusicBrowser( 2700): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
D/MusicBrowser( 2700): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2700): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2700): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2700): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2700): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2700): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
I/chromium( 3635): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/MusicBrowser( 2700): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
I/ActivityManager(  849): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=3755 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/MusicBrowser( 2700): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2700): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
I/MusicWidget( 2601): intentReceiver onReceive() action::com.lge.music.queuechanged
I/MusicWidget( 2601): beingMusicWidget_4x2() result::false
,I/MusicWidget( 2601): beingMusicWidget_Quick() result::false
D/MusicBrowser( 2700): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2700): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2700): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
D/MusicBrowser( 2700): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.metachanged}
I/MusicBrowser( 2700): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
D/MusicBrowser( 2700): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
D/MusicBrowser( 2700): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2700): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2700): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2700): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2700): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2700): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2700): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
I/MusicWidget( 2601): beingMusicWidget_4x1() result::true
I/MusicWidget( 2601): send mDelayedStopHandler
I/MusicWidget( 2601): intentReceiver onReceive() action::com.lge.music.metachanged
,I/MusicWidget( 2601): beingMusicWidget_4x2() result::false
I/MusicWidget( 2601): beingMusicWidget_Quick() result::false
I/MusicWidget( 2601): beingMusicWidget_4x1() result::true
I/MusicBrowser( 2700): [MediaPlaybackService.java:3426:notifyChange()] oooooo mRemoteControlClient.editMetadata :: META_CHANGED 
I/MusicWidget( 2601): send mDelayedStopHandler
I/MusicWidget( 2601): performViewUpdater handleMessage() msg.what::3
I/MusicWidget( 2601): beingMusicWidget_Quick() result::false
I/MusicBrowser( 2700): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=false}
I/MusicBrowser( 2700): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2700): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2700): [MediaPlaybackService.java:updateGroupIndexData()] oooooo 
I/MusicBrowser( 2700): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2700): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2700): [GroupIndexApi.java:groupingIndexDataProviderStart()] oooooo 
I/MusicBrowser( 2700): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_STARTED dat=file:///storage/emulated/0 flg=0x10 }}
I/MusicBrowser( 2700): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 2700): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_STARTED
I/MusicBrowser( 2700): [MediaPlaybackService.java:9999:run()] oooooo AlbumImageUpdater() run :: Start
I/MusicBrowser( 2700): [MediaPlaybackService.java:10051:run()] oooooo AlbumImageUpdater() run :: End
,I/MusicBrowser( 2700): [GroupingIndexDataProvider.java:101:doInBackground()] oooooo mIsMusicPickerMode = false
W/MusicBrowser( 2700): - Start trace [MusicUtils.query]---------------------------------------------------------------
W/MusicBrowser( 2700): [Line 003751] MusicUtils.java, query() : MusicUtils.query
W/MusicBrowser( 2700): [Line 003761] MusicUtils.java, isMediaScannerScanning() : MusicUtils.query
W/MusicBrowser( 2700): [Line 001991] MediaPlaybackService.java, onChange() : MusicUtils.query
W/MusicBrowser( 2700): [Line 000130] ContentObserver.java, onChange() : MusicUtils.query
W/MusicBrowser( 2700): - End   trace [MusicUtils.query]---------------------------------------------------------------
,D/JsMessageQueue( 3635): Set native->JS mode to OnlineEventsBridgeMode
,V/MediaScannerClient( 2737): [MediaScanner]setLocale: = en_US
V/DrmBroadcastReceiver( 3755): Receive ACTION_BOOT_COMPLETED
,V/DrmService( 3755): Service onCreate
D/DrmService( 3755): Received new request = 4
I/iu.UploadsManager( 2292): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
,E/AndroidProtocolHandler( 3635): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/DrmServiceHandler( 3755): updateDrmPushNotification() : No notification
D/DrmService( 3755): Completed !! request = 4
D/DrmService( 3755): Request count = 0
,I/MusicWidget( 2601): performViewUpdater handleMessage() msg.what::0
I/MusicWidget( 2601): beingMusicWidget_4x1() result::true
I/MusicWidget( 2601): performUpdate()_4x1
I/MusicWidget( 2601): defaultAppWidget()_4x1
,I/ActivityManager(  849): Start proc com.lge.cloudhub for broadcast com.lge.cloudhub/.service.CloudHubReceiver: pid=3778 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/DrmService( 3755): Service onDestroy
,I/ActivityManager(  849): Killing 2086:com.android.defcontainer/u0a4 (adj 15): empty #11
I/MusicWidget( 2601): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2601): 4x1_currentTheme :: null
I/MusicWidget( 2601): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2601): setDefaultViewLayoutId()_4x1
I/MusicWidget( 2601): appWidgetViewUpdate()_4x1
I/MusicWidget( 2601): linkButtons()_4x1
,W/libprocessgroup(  849): failed to open /acct/uid_10004/pid_2086/cgroup.procs: No such file or directory
,I/MusicWidget( 2601): pushUpdate()_4x1
,D/MediaScannerEx( 2737): [MediaScanner] beginFile() path = /storage/emulated/0/QuicksetLite Setup/data
I/MusicWidget( 2601): performViewUpdater handleMessage() msg.what::1
I/MusicWidget( 2601): beingMusicWidget_4x2() result::false
,V/MediaScannerClient( 2737): [MediaScanner]setLocale: = en_US
,W/MediaScanner( 2737): Error opening directory '/storage/external_SD/', skipping: Permission denied.
D/LGMediaProvider( 2737): [MediaScanner] delete() uri = content://media/external/file
W/MusicBrowser( 2700): - Start trace [MusicUtils.query]---------------------------------------------------------------
W/MusicBrowser( 2700): [Line 003751] MusicUtils.java, query() : MusicUtils.query
,W/VRBookmarkProvider( 3731): [BookmarkProvider.java:546:onChange()-[Thread:Other] Data Change!! false url : content://media/external
I/iu.UploadsManager( 2292): End new media; added: 0, uploading: 0, time: 178 ms
I/MusicWidget( 2601): _mediaDataObserver onChange()
W/VRBookmarkProvider( 3731): [BookmarkProvider.java:563:onChange()-[Thread:Other] EXTERNAL Change!!
I/MusicWidget( 2601): beingMusicWidget_4x2() result::false
W/MusicBrowser( 2700): [Line 003761] MusicUtils.java, isMediaScannerScanning() : MusicUtils.query
W/MusicBrowser( 2700): [Line 001991] MediaPlaybackService.java, onChange() : MusicUtils.query
W/MusicBrowser( 2700): [Line 000130] ContentObserver.java, onChange() : MusicUtils.query
W/MusicBrowser( 2700): - End   trace [MusicUtils.query]---------------------------------------------------------------
D/LGMediaProvider( 2737): [MediaScanner] delete() completed notifyChange, uri = content://media/external
I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/ActivityManager(  849): Killing 3433:com.google.android.partnersetup/u0a9 (adj 15): empty #11
V/MediaScanner( 2737): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@386ecf0b
,V/MediaScanner( 2737): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@386ecf0b
D/MediaScanner( 2737): [MediaScanner] prescan time: 144ms
D/MediaScanner( 2737): [MediaScanner] scan time: 204ms
D/MediaScanner( 2737): [MediaScanner] postscan time: 50ms
D/MediaScanner( 2737): [MediaScanner] total time: 398ms
D/LGMediaProvider( 2737): [MediaScanner] delete() uri = content://media/none/media_scanner
E/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,D/MediaScannerService( 2737): [MediaScanner] scan() Send Intent ACTION_MEDIA_SCANNER_FINISHED uri : file:///storage/emulated/0
W/libprocessgroup(  849): failed to open /acct/uid_10009/pid_3433/cgroup.procs: No such file or directory
,D/LGMediaProvider( 2737): [MediaScanner] mUnmountReceiver ACTION_MEDIA_SCANNER_FINISHED : uri = file:///storage/emulated/0, path = /storage/emulated/0
I/MusicBrowser( 2700): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///storage/emulated/0 flg=0x10 }}
I/MusicBrowser( 2700): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 2700): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_FINISHED
D/MediaScannerService( 2737): [MediaScanner] done scanning volume external
I/MusicBrowser( 2700): [MediaPlaybackService.java:reloadQueue()] oooooo 
D/MusicBrowser( 2700): [MediaPlaybackService.java:reloadQueue()] oooooo id=-1
D/MusicBrowser( 2700): [MediaPlaybackService.java:reloadQueue()] oooooo mCardId=-1
D/MusicBrowser( 2700): [MediaPlaybackService.java:reloadQueue()] oooooo mPreferences.id=-1
D/MusicBrowser( 2700): [MediaPlaybackService.java:reloadQueue()] oooooo q=
D/MusicBrowser( 2700): [MediaPlaybackService.java:reloadQueue()] oooooo q.length=0
D/MusicBrowser( 2700): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.queuechanged}
I/MusicBrowser( 2700): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
D/MusicBrowser( 2700): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
D/MusicBrowser( 2700): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2700): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2700): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2700): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2700): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2700): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2700): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
I/MusicWidget( 2601): intentReceiver onReceive() action::com.lge.music.queuechanged
,I/MusicWidget( 2601): beingMusicWidget_4x2() result::false
I/MusicWidget( 2601): beingMusicWidget_Quick() result::false
I/MusicBrowser( 2700): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicWidget( 2601): beingMusicWidget_4x1() result::true
I/MusicBrowser( 2700): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
I/MusicWidget( 2601): send mDelayedStopHandler
I/MusicWidget( 2601): performViewUpdater handleMessage() msg.what::3
I/MusicWidget( 2601): beingMusicWidget_Quick() result::false
D/MusicBrowser( 2700): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2700): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2700): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
D/MusicBrowser( 2700): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.metachanged}
I/MusicBrowser( 2700): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
D/MusicBrowser( 2700): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
D/MusicBrowser( 2700): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2700): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2700): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2700): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2700): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2700): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2700): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
I/MusicWidget( 2601): intentReceiver onReceive() action::com.lge.music.metachanged
I/MusicBrowser( 2700): [MediaPlaybackService.java:3426:notifyChange()] oooooo mRemoteControlClient.editMetadata :: META_CHANGED 
I/MusicWidget( 2601): beingMusicWidget_4x2() result::false
I/MusicBrowser( 2700): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=false}
I/MusicWidget( 2601): beingMusicWidget_Quick() result::false
I/MusicBrowser( 2700): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
I/MusicWidget( 2601): beingMusicWidget_4x1() result::true
I/MusicBrowser( 2700): [MediaPlaybackService.java:9999:run()] oooooo AlbumImageUpdater() run :: Start
I/MusicWidget( 2601): send mDelayedStopHandler
I/MusicWidget( 2601): performViewUpdater handleMessage() msg.what::3
D/MusicBrowser( 2700): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicWidget( 2601): beingMusicWidget_Quick() result::false
I/MusicBrowser( 2700): [MediaPlaybackService.java:10051:run()] oooooo AlbumImageUpdater() run :: End
I/MusicBrowser( 2700): [MediaPlaybackService.java:updateGroupIndexData()] oooooo 
I/MusicBrowser( 2700): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2700): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2700): [GroupIndexApi.java:groupingIndexDataProviderStart()] oooooo 
I/MusicBrowser( 2700): [GroupingIndexDataProvider.java:101:doInBackground()] oooooo mIsMusicPickerMode = false
,V/CloudHub( 3778): [DATABASE][DBConnection|open] open database
E/CloudHub( 3778): [DATABASE][DBConnection|getUserId] User id: 0
E/CloudHub( 3778): [DATABASE][DBConnection|getDatabasePath] Database path: /data/user/0/com.lge.cloudhub/databases/cloudhub.db
V/CloudHub( 3778): [SERVICE][CloudHubReceiver|queryUploadCount] # of contents to upload: 0
,V/DownloadManager( 2737): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 2737): created cursor android.database.sqlite.SQLiteCursor@37c5b1e8 on behalf of 3778
,V/CloudHub( 3778): [SERVICE][CloudHubReceiver|queryDownloadCount] # of contents to download: 0
,I/ActivityManager(  849): Start proc com.lge.gnss.airtest for broadcast com.lge.gnss.airtest/.GnssAirTestReceiver: pid=3797 uid=10054 gids={50054, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  849): Killing 3461:com.android.providers.calendar/u0a14 (adj 15): empty #11
I/MusicWidget( 2601): performViewUpdater handleMessage() msg.what::0
,I/VRBookmarkProvider( 3731): [BookmarkProvider.java:530:handleMessage()-[Thread:Other] -- syncTable() START --
I/MusicWidget( 2601): beingMusicWidget_4x1() result::true
I/MusicWidget( 2601): performUpdate()_4x1
I/MusicWidget( 2601): defaultAppWidget()_4x1
I/MusicWidget( 2601): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2601): 4x1_currentTheme :: null
I/MusicWidget( 2601): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2601): setDefaultViewLayoutId()_4x1
I/MusicWidget( 2601): appWidgetViewUpdate()_4x1
,I/MusicWidget( 2601): linkButtons()_4x1
W/libprocessgroup(  849): failed to open /acct/uid_10014/pid_3461/cgroup.procs: No such file or directory
,I/MusicWidget( 2601): pushUpdate()_4x1
,I/MusicWidget( 2601): performViewUpdater handleMessage() msg.what::1
,I/MusicWidget( 2601): beingMusicWidget_4x2() result::false
I/VRBookmarkProvider( 3731): [BookmarkProvider.java:532:handleMessage()-[Thread:Other] -- syncTable() END --
D/jxcore_app_log( 3635): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426105344
D/JX-Cordova( 3635): jxcore cordova android initializing
,D/AirTest ( 3797): Set airtest_enable to false
,I/ActivityManager(  849): Killing 3496:com.lge.lgdmsclient/1000 (adj 15): empty #11
I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
W/jxcore-log( 3635): Initializing JXcore engine
W/jxcore-log( 3635): JXcore engine is ready
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
W/jxcore-log( 3635): Starting JXcore engine
W/libprocessgroup(  849): failed to open /acct/uid_1000/pid_3496/cgroup.procs: No such file or directory
,V/LGSC    ( 2767): [104] 401
W/m.example.hello( 3635): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6407]" dev="sockfs" ino=6407 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 3635): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/m.example.hello( 3635): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6026]" dev="sockfs" ino=6026 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 3635): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/m.example.hello( 3635): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/m.example.hello( 3635): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[17114]" dev="sockfs" ino=17114 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
I/ActivityManager(  849): Start proc com.lge.lgfota.permission for broadcast com.lge.lgfota.permission/.DmcTargetValidationReceiver: pid=3815 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,D/TARGETVALIDLATION_RECEIVER( 3815): TargetValidationReceiver_ACTION_BOOT_COMPLETETED Received
D/TARGETVALIDLATION_RECEIVER( 3815): updateFlag = new File(TARGET_FLAG_PATH)
D/TARGETVALIDLATION_RECEIVER( 3815): Do Not display result dialog. it is not used Update Tool!!
,I/ActivityManager(  849): Killing 3515:com.lge.clock/u0a10 (adj 15): empty #11
W/jxcore-log( 3635): Platform android
W/jxcore-log( 3635): 
W/jxcore-log( 3635): Process ARCH arm
W/jxcore-log( 3635): 
,V/LGSC    ( 1748): [101] 102, action=android.intent.action.BOOT_COMPLETED, iccState=null
,W/libprocessgroup(  849): failed to open /acct/uid_10010/pid_3515/cgroup.procs: No such file or directory
W/ContextImpl( 2919): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.qualcomm.atfwd.AtFwdAutoboot.onReceive:24 android.app.ActivityThread.handleReceiver:2663 
E/AtFwd AutoBoot( 2919): AtFwd Auto Boot Started Successfully
I/jxcore-log( 3635): JXcore Cordova bridge is ready!
I/jxcore-log( 3635): 
,W/jxcore-log( 3635): JXcore engine is started
I/GoogleHttpClient( 2043): GMS http client unavailable, use old client
,I/ActivityManager(  849): Start proc com.lge.defaultaccount for broadcast com.lge.defaultaccount/.receiver.ReceiverBootUp: pid=3834 uid=10062 gids={50062, 9997} abi=armeabi-v7a
,E/jxcore-log( 3635): >> LGE-LG-D722
E/jxcore-log( 3635): 
I/jxcore-log( 3635): Total memory 906309632
I/jxcore-log( 3635): 
,I/jxcore-log( 3635): Free memory 31350784
I/jxcore-log( 3635): 
I/jxcore-log( 3635): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3635): 
I/jxcore-log( 3635): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3635): 
I/jxcore-log( 3635): userPath [ 'www' ]
I/jxcore-log( 3635): 
I/jxcore-log( 3635): Size 720 1196
I/jxcore-log( 3635): 
,I/jxcore-log( 3635): Screen Brightness 255
I/jxcore-log( 3635): 
E/jxcore-log( 3635): Dummy Error Log.
E/jxcore-log( 3635): 
,I/InsertAccount( 3834): The account already exists
,I/ActivityManager(  849): Start proc com.lge.hiddenmenu for broadcast com.lge.hiddenmenu/.kddi_only.sms_setting.AssistReceiver: pid=3852 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  849): Killing 3544:com.lge.appbox.client:SingleBinaryService/u0a11 (adj 15): empty #11
W/libprocessgroup(  849): failed to open /acct/uid_10011/pid_3544/cgroup.procs: No such file or directory
,I/InsertAccount( 3834): The account info in contact DB already exists
,W/ResourcesManager( 3852): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 3852): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[SMS_AD]( 3852): Intent action: android.intent.action.BOOT_COMPLETED
,I/ActivityManager(  849): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3870 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  849): Waited long enough for: ServiceRecord{20a06087 u0 com.lge.sizechangable.weather/.service.WeatherService}
I/[SMS_AD]( 3852): Intent action: android.intent.action.BOOT_COMPLETED
,I/ActivityManager(  849): Killing 3563:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  849): failed to open /acct/uid_10011/pid_3563/cgroup.procs: No such file or directory
,I/ActivityManager(  849): Killing 3656:com.android.settings/1000 (adj 15): empty #11
D/WeatherAncestor( 2658): 2 : onReceive, action: android.intent.action.BOOT_COMPLETED, Time(hour:min:sec) 12:15:36
W/libprocessgroup(  849): failed to open /acct/uid_1000/pid_3656/cgroup.procs: No such file or directory
,D/UpdateThreadPoolManager( 2658): 2 : This is isUpdating : false
W/ResourcesManager( 3870): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/art     (  849): Explicit concurrent mark sweep GC freed 16420(771KB) AllocSpace objects, 3(237KB) LOS objects, 33% free, 22MB/34MB, paused 2.632ms total 175.600ms
D/Weather_cast( 2658): 2 : set auto-update time : 11/28 15:15
,D/WeatherAncestor( 2658): 2 : onReceive has processed, action: android.intent.action.BOOT_COMPLETED, Time(hour:min:sec) 12:15:36
D/WeatherService( 2658): 2 : onStartCommand, intent!=null, action: android.intent.action.BOOT_COMPLETED
D/CalendarProvider2( 3870): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@1fb6f59c
,I/ActivityManager(  849): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.LockSettingsReceiver: pid=3890 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  849): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2658): 2 : Utils getTopActivity com.lge.launcher2 / true
I/art     (  300): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 20.720ms
,D/CalendarProvider2( 3870): [getOrCreateCalendarAlarmManager]
I/jxcore-log( 3635): getBuffer is called!!!!
I/jxcore-log( 3635): 
I/CalendarProvider2( 3870): Created com.android.providers.calendar.CalendarAlarmManager@3c72fd21(com.android.providers.calendar.CalendarProvider2@1fb6f59c)
D/WeatherService( 2658): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2658): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/InsertAccount( 3834): The account info in calendar DB already exists
I/art     (  300): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 20.861ms
I/Process ( 3834): Sending signal. PID: 3834 SIG: 9
I/art     (  300): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 20.363ms
,I/LockScreenSettings( 3890): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/ActivityManager(  849): Process com.lge.defaultaccount (pid 3834) has died
,I/LockScreenSettings( 3890): Received Broadcast : android.intent.action.BOOT_COMPLETED
I/ActivityManager(  849): Start proc com.lge.springcleaning for broadcast com.lge.springcleaning/.receiver.BootCompleteReceiver: pid=3909 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,V/AlarmManager(  849): ELAPSED_WAKEUP set : Alarm{1b21215f type 2 when 52894 com.android.providers.calendar} when 52894
,D/BootCompleteReceiver( 3909): hasclipTray = true
W/ContextImpl( 3909): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.springcleaning.receiver.BootCompleteReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2663 
,I/ActivityManager(  849): Start proc com.lge.springcleaning:AppCleanupService for service com.lge.springcleaning/.service.AppCleanupService: pid=3926 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  849): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3943 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  849): Killing 3701:com.android.managedprovisioning/u0a111 (adj 15): empty #11
,W/libprocessgroup(  849): failed to open /acct/uid_10111/pid_3701/cgroup.procs: No such file or directory
V/AppCleanupService( 3926): registerAlarm
,D/AppCleanupService( 3926): noticeInterval = 2592000000
D/AppCleanupService( 3926): notiDateStr = 2015-12-20 22:35:42
D/AppCleanupService( 3926): noticeStart = 2015-12-20 22:35:42
D/AppCleanupService( 3926): noticeStart = 1450647342000
,D/AppUsageDbAdapter( 3926): initPreloadedAppToTheDB() : row count = 112
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,E/UpdateRequestReceiver( 3943): ignoring update request
,E/UpdateRequestReceiver( 3943): ignoring update request
E/UpdateRequestReceiver( 3943): ignoring update request
E/UpdateRequestReceiver( 3943): ignoring update request
,E/UpdateRequestReceiver( 3943): ignoring update request
E/UpdateRequestReceiver( 3943): ignoring update request
D/sensors_hal_Time(  849): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  849): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  849): tsOffsetIs: Apps: 53309766026; DSPS: 1838654; Offset : -2810634967
,I/ActivityManager(  849): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseSIMObserver: pid=3974 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  849): Killing 3731:com.lge.voicerecorder/u0a34 (adj 15): empty #11
W/libprocessgroup(  849): failed to open /acct/uid_10034/pid_3731/cgroup.procs: No such file or directory
,D/SIMObserver( 3974): action:android.intent.action.BOOT_COMPLETED
D/SIMObserver( 3974): handle ACTION_BOOT_COMPLETED
,I/ActivityManager(  849): Killing 2292:com.google.android.gms/u0a6 (adj 15): empty #11
,W/libprocessgroup(  849): failed to open /acct/uid_10006/pid_2292/cgroup.procs: No such file or directory
,E/QcrilMsgTunnelAutoboot( 2320): Received Intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelAutoboot (has extras) } canStartService = false
D/PhoneInterfaceManager( 1748): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
D/PhoneInterfaceManager( 1748): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
I/ActivityManager(  849): Start proc com.google.android.gms for broadcast com.google.android.gms/.chimera.container.GmsModuleFinder$Receiver: pid=3992 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 3992): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3992): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 3992): VM with version 2.1.0 has multidex support
I/MultiDex( 3992): install
I/MultiDex( 3992): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3992): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 3992): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3992): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1e8e5d19: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3992): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 3992): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 3992): com.google.android.gms: cancel(39789) by com.google.android.gms
,I/art     ( 1730): Explicit concurrent mark sweep GC freed 12394(779KB) AllocSpace objects, 7(112KB) LOS objects, 40% free, 11MB/18MB, paused 2.452ms total 102.955ms
,D/NativeLibraryUtils( 3992): Install completed successfully. count=13 extracted=0
,W/InstanceID/Rpc( 3992): Found 10006
,D/FileApkUtils( 3992): Spent 51ms computing apk sha1.
,D/FileApkUtils( 3992): Module already staged or being staged:chimera-modules/MapsModule.apk
I/art     ( 3992): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-d93aca1818df11c4cd5bccf493ad94e2b544d57a@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
D/DexOptUtils( 3992): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 3992): Keeping up-to-date module: module-d93aca1818df11c4cd5bccf493ad94e2b544d57a
D/GmsModuleFndr( 3992): Beginning GMS chimera module scan
,D/GCM     ( 3992): COMPAT: Multi user not supported
,D/GCM     ( 2043): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,I/CheckinService( 3992): Checkin interval check for package: unspecified last checkin: 1448626259145 min interval config: 0 actual interval: 83079353
D/GmsModuleFndr( 3992): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
D/ChimeraCfgMgr( 3992): Beginning module configuration check
D/ChimeraCfgMgr( 3992): Module APKs unchanged, check complete
I/GCoreUlr( 3992): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/CheckinService( 3992): Disabling old GoogleServicesFramework version
I/GCoreUlr( 1730): DispatchingService.onCreate()
I/art     ( 3992): CheckpointMarkThreadRoots callback created = 0xb04be500
,D/SystemUpdateService( 3992): onCreate
,D/SystemUpdateService( 3992): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/art     ( 3992): CheckpointMarkThreadRoots callback created = 0xb04be4f0
V/AuthZen ( 3992): Handling intent: android.intent.action.BOOT_COMPLETED
,I/SystemUpdateService( 3992): cancelUpdate (empty URL)
,I/SystemUpdateService( 3992): active receiver: disabled
D/AuthZenEventHandler( 3992): Handling event: android.intent.action.BOOT_COMPLETED
,W/art     ( 3992): Suspending all threads took: 8.500ms
,I/GCoreUlr( 1730): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,V/GLSActivity( 2043): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 3992): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
I/art     ( 3992): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,V/GLSActivity( 2043): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 3992): Background partial concurrent mark sweep GC freed 16418(1154KB) AllocSpace objects, 8(128KB) LOS objects, 39% free, 10MB/17MB, paused 24.039ms total 125.823ms
,I/NotificationManager( 3992): com.google.android.gms: cancel(2130838130) by com.google.android.gms
I/NotificationManager( 3992): com.google.android.gms: cancel(2130838131) by com.google.android.gms
,I/CheckinService( 3992): Checking schedule, now: 1448709338699 next: 1449153508109
I/CheckinService( 3992): active receiver: disabled
,D/ChimeraCfgMgr( 3992): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/art     ( 2043): Explicit concurrent mark sweep GC freed 5401(318KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 11MB/18MB, paused 2.329ms total 60.543ms
,W/BaseAppContext( 3992): Using Auth Proxy for data requests.
D/ChimeraCfgMgr( 3992): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/GLSActivity( 2043): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  849): Waited long enough for: ServiceRecord{63cc3c7 u0 com.google.android.gms/.gcm.GcmService}
V/GLSActivity( 2043): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 3992): [AbstractKidsOperation] Invalid device state 3
,I/AuthZen ( 3992): Fetching signing key...
D/SystemUpdateService( 3992): onDestroy
I/Kids    ( 3992): [KidAccountFixer] No network connection
W/GCoreFlp( 1730): No location to return for getLastLocation()
,W/FusedLocationProvider( 3992): location=null
I/NotificationManager( 3992): com.google.android.gms: cancel(10436) by com.google.android.gms
I/GCoreUlr( 1730): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
W/Auth    ( 2043): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
W/GCoreFlp( 1730): No location to return for getLastLocation()
,I/AuthZen ( 3992): Signing key fetched successfully!
W/FusedLocationProvider( 3992): location=null
I/GCoreUlr( 1730): Unbound from all location providers
V/GLSActivity( 2043): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/BaseAppContext( 3992): Using Auth Proxy for data requests.
,V/GmsCoreStatsServiceLauncher( 3992): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
D/PersistentNotificationBroadcastReceiver( 2043): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,D/a       ( 3992): Opening database auth.proximity.permit_store...
D/AuthZenTransactionCache( 3992): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 3992): Clearing transaction cache
I/ActivityManager(  849): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4080 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/GCoreUlr( 1730): DispatchingService.onDestroy()
I/GCoreUlr( 1730): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1730): Unbound from all location providers
,W/ResourcesManager( 4080): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 4080): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 4080): MmsConfig.loadMmsSettings
I/Babel_SMS( 4080): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 4080): MmsConfig.loadFromDatabase
,E/Babel_SMS( 4080): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4080): MmsConfig.loadFromResources
E/Babel_SMS( 4080): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 4080): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 4080): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 4080): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 4080): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 4080): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 4080): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 4080): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 4080): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 4080): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 4080): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 4080): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 4080): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 4080): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 4080): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 4080): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 4080): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 4080): found sensor: Motion Accel, handle=46
,W/Settings( 4080): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 4080): startup - clean
I/art     ( 4080): CheckpointMarkThreadRoots callback created = 0xb042d850
,I/Babel   ( 4080): deleted: false for 0
,I/art     ( 4080): CheckpointMarkThreadRoots callback created = 0xb042d830
,W/AudioCapabilities( 4080): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 4080): Unsupported mime audio/adpcm
W/AudioCapabilities( 4080): Unsupported mime audio/g726
W/AudioCapabilities( 4080): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 4080): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 4080): Unsupported mime video/mjpg
W/VideoCapabilities( 4080): Unsupported mime video/theora
,W/AudioCapabilities( 4080): Unsupported mime audio/evrc
,W/AudioCapabilities( 4080): Unsupported mime audio/qcelp
W/VideoCapabilities( 4080): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 4080): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 4080): Unsupported mime audio/qcelp
W/AudioCapabilities( 4080): Unsupported mime audio/evrc
W/VideoCapabilities( 4080): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 4080): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4080): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4080): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4080): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4080): Unrecognized profile 2130706433 for video/avc
I/art     (  849): Explicit concurrent mark sweep GC freed 16774(844KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 22MB/34MB, paused 1.623ms total 134.004ms
,I/vclib   ( 4080): onServiceConnected
W/Babel   ( 4080): Attempted to change video mute state without an active call.
,I/NotificationManager( 4080): com.google.android.talk: cancel(10436) by com.google.android.talk
I/ActivityManager(  849): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4118 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  849): Killing 3755:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  849): failed to open /acct/uid_10051/pid_3755/cgroup.procs: No such file or directory
,W/ResourcesManager( 4118): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4118): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4118): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/CursorWrapperInner( 3778): Cursor finalized without prior close()
,W/System  ( 4118): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 4118): Installed default security provider GmsCore_OpenSSL
W/ResourcesManager( 4118): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4118): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 4118): CheckpointMarkThreadRoots callback created = 0xb042dbd0
E/YouTube MDX( 4118): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/art     ( 4118): CheckpointMarkThreadRoots callback created = 0xb4958de0
D/libc-netbsd( 4118): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4118): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4118): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
I/dex2oat ( 4158): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads1108444942.jar --oat-fd=28 --oat-location=/data/data/com.google.android.youtube/cache/ads1108444942.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 4158): dex2oat took 120.253ms (threads: 4)
,I/NotificationManager( 4118): com.google.android.youtube: cancel(2) by com.google.android.youtube
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4118): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4118): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4118): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
W/InstanceID/Rpc( 4118): Found 10006
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4118): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,D/BluetoothManagerService(  849): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  849): disable(): mBluetooth = null mBinding = false
D/BluetoothManagerService(  849): Message: 2
,I/ActivityManager(  849): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4213 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/WifiServiceImplEx(  849): setWifiEnabled: false pid=3635, uid=10030, package= com.example.hello, App Lable : HelloWorld
D/WifiService(  849): setWifiEnabled: false pid=3635, uid=10030
I/jxcore-log( 3635): ****TEST TOOK:  5104  ms ****
I/jxcore-log( 3635): 
I/jxcore-log( 3635): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3635): 
I/NotificationManager( 4118): com.google.android.youtube: cancel(10436) by com.google.android.youtube
,I/ActivityManager(  849): Killing 3778:com.lge.cloudhub/u0a49 (adj 15): empty #11
,W/libprocessgroup(  849): failed to open /acct/uid_10049/pid_3778/cgroup.procs: No such file or directory
D/AndroidRuntime( 4231): 
D/AndroidRuntime( 4231): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4231): CheckJNI is OFF
,W/ActivityManager(  849): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 4213): getAccountsCursor
,V/GLSActivity( 2043): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 4213): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  849): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 4213): Error finding the version of the Email provider.....
E/Gmail   ( 4213): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4213): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4213): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4213): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4213): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4213): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4213): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 4213): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 4213): We do not support migrating this version of the Email provider.
,D/AndroidRuntime( 4231): Calling main entry com.android.commands.pm.Pm
I/Gmail   ( 4213): getAccountsCursor
V/GLSActivity( 2043): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2043): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  849): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 4213): Observing account changes for notifications
,I/ActivityManager(  849): Force stopping com.example.hello appid=10030 user=-1: uninstall pkg
I/ActivityManager(  849): Killing 3635:com.example.hello/u0a30 (adj 0): stop com.example.hello
I/WindowState(  849): WIN DEATH: Window{1609434c u0 com.example.hello/com.example.hello.MainActivity}
,D/InputDispatcher(  849): Focus left window: Window{1609434c u0 com.example.hello/com.example.hello.MainActivity}
D/InputDispatcher(  849): Window went away: Window{1609434c u0 com.example.hello/com.example.hello.MainActivity}
,W/PackageSettings(  849): Skipping PackageSetting{38fd596f com.test.thalitest/10316} due to missing metadata
,V/GLSActivity( 2043): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/SearchBackgroundTaskFac( 1949): refreshing internal icing corpora
,I/SearchBackgroundTaskFac( 1949): Checking for language pack updates
,I/VelvetNetworkClient( 1949): Network connection not availble
I/Gmail   ( 4213): notifyAccountChanged
I/Gmail   ( 4213): getAccountsCursor
I/Gmail   ( 4213): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4213): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 4213): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4213): calculateUnknownSyncRationalesAndPurgeInBackground: running
W/ActivityManager(  849): Force removing ActivityRecord{31c339c1 u0 com.example.hello/.MainActivity t220}: app died, no saved state
,W/ActivityManager(  849): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  849): Spurious death for ProcessRecord{2aa5d1c4 3635:com.example.hello/u0a30}, curProc for 3635: null
I/ActivityManager(  849): Force stopping com.example.hello appid=10030 user=0: pkg removed
I/VelvetNetworkClient( 1949): Network connection not availble
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/KeyguardModel( 1369): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/InputReader(  849): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1730): Ignoring removeGeofence because network location is disabled.
W/System.err( 3416): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
W/System.err( 3416): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3416): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3416): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/ActivityManager(  849): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/System.err( 3416): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3416): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3416): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3416): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3416): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3416): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3416): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3416): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/[LGHome]EVENT( 1877): [Launcher.java:5203:onStart()]onStart
W/ActivityManager(  849): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/[SystemUI]QSlideListController( 1369): onReceive = android.intent.action.PACKAGE_REMOVED
,D/KeyguardModel( 1369): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1369): createShortcutInfo...
I/GservicesUpdateTask( 1949): Updating Gservices keys
,I/[LGHome]EVENT( 1877): [Launcher.java:776:onResume()]onResume
,D/KeyguardModel( 1369): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1369): createShortcutInfo...
,I/ActivityManager(  849): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=4298 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/administrator(  849): Handling package changes for user 0
I/VelvetNetworkClient( 1949): Network connection not availble
D/KeyguardModel( 1369): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1369): createShortcutInfo...
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,D/KeyguardModel( 1369): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1369): createShortcutInfo...
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1369): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1369): createShortcutInfo...
I/VelvetNetworkClient( 1949): Network connection not availble
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1369): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 1369): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/[LGHome]LGActivityUtil( 1877): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/KeyguardModel( 1369): handleShortcutListChanged...
I/[LGHome]EVENT( 1877): [Launcher.java:929:onResume()]onResume end
I/Activity( 1877): Activity.onPostResume() called 
D/KeyguardModel( 1369): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1369): createShortcutInfo...
,D/KeyguardModel( 1369): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1369): createShortcutInfo...
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1369): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1369): createShortcutInfo...
W/[LGHome]LGWallpaperInfo( 1877): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1877): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
I/SystemUI[Framework](  849): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
W/PhoneWindowManagerEx(  849): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  849): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  849): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  849): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1c068e7a,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  849): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/KeyguardModel( 1369): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1369): createShortcutInfo...
E/ActivityThread( 4213): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@245590fb that was originally bound here
E/ActivityThread( 4213): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@245590fb that was originally bound here
E/ActivityThread( 4213): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 4213): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 4213): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 4213): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 4213): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4213): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4213): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4213): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4213): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4213): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4213): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4213): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4213): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4213): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4213): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 4213): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ActivityManager(  849): Unbind failed: could not find connection for android.os.BinderProxy@34d4dcea
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,D/InputDispatcher(  849): Focus entered window: Window{908f5c2 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/KeyguardModel( 1369): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1369): createShortcutInfo...
I/art     ( 1783): CheckpointMarkThreadRoots callback created = 0xb042d280
D/KeyguardModel( 1369): handleShortcutListChanged...
,I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
I/[LGHome]EVENT( 1877): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1877): [setNavigationBarColor] color=0x 0
I/ActivityManager(  849): Killing 3797:com.lge.gnss.airtest/u0a54 (adj 15): empty #11
,I/art     ( 1783): CheckpointMarkThreadRoots callback created = 0xaaf73550
,W/InputMethodManagerService(  849): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,W/InputMethodManagerService(  849): Got RemoteException sending setActive(false) notification to pid 3635 uid 10030
W/libprocessgroup(  849): failed to open /acct/uid_10054/pid_3797/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 1949): Updating corpora: APPS=MAYBE, CONTACTS=MAYBE
V/[BNRBootReceiver]( 4298): boot receiver action = android.intent.action.BOOT_COMPLETED
,V/[BNRBootReceiver]( 4298): set property sys.lge.bnrd = 1
V/[BNRBootReceiver]( 4298): End of BootComplted IF
V/[BNRBootReceiver]( 4298): Boot Receiver Return
I/NotificationManager( 1949): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
W/linker  ( 4328): /system/bin/bnrd has text relocations. This is wasting memory and prevents security hardening. Please fix.
V/[BNRBootCompletedThread]( 4298): run
,W/bnrd    ( 4328): BNRD > wait starting [4328-3058102400] <
E/bnrd    ( 4328): /data/data/.bnr_fifo_req
I/SystemUI[Framework](  849): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
,I/HotwordRecognitionRnr( 1949): Starting hotword detection.
I/MicrophoneInputStream( 1949): mic_starting com.google.android.apps.gsa.speech.audio.u@9e8bc6c
V/AudioRecord( 1949): set(): inputSource 1999, sampleRate 16000, format 0x1, channelMask 0x10, frameCount 128000, notificationFrames 0, sessionId 0, transferType 0, flags 0
V/AudioRecord( 1949): set(): mSessionId 22
I/Timeline( 1877): Timeline: Activity_idle id: android.os.BinderProxy@6f577b7 time:58716
W/PhoneWindowManagerEx(  849): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  849): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  849): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  849): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1c068e7a,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  849): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,I/ActivityManager(  849): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4336 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  849): Killing 3815:com.lge.lgfota.permission/1000 (adj 15): empty #11
V/AudioPolicyManager(  282): getInput() inputSource 1999, samplingRate 16000, format 1, channelMask 10, session 22, flags 0
V/AudioPolicyManager(  282): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  282): isPlaybackThread 0,isRecordThread 1
D/audio_hw_primary(  282): adev_open_input_stream: enter: sample_rate(16000) channel_mask(0x10) devices(0x80000004)        stream_handle(0xb4036520)
,V/audio_hw_primary(  282): adev_open_input_stream: exit
V/AudioFlinger(  282): openInput_l() openInputStream returned input 0xb4036520, SamplingRate 16000, Format 0x1, Channels 10, flags 0, status 0
V/AudioFlinger(  282): openInput_l() created record thread: ID 23 thread 0xb42a5000
V/AudioSystem(  282): ioConfigChanged() event 3, ioHandle 23
I/AudioFlinger(  282): AudioFlinger's thread 0xb42a5000 ready to run
D/audio_hw_primary(  282): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioPolicyService(  282): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  282): inserting command: 9 at index 0, num commands 0
V/AudioSystem(  849): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 1369): ioConfigChanged() event 3, ioHandle 23
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioSystem( 1949): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 3139): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 1748): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 2700): ioConfigChanged() event 3, ioHandle 23
V/AudioFlinger(  282): openRecord() lSessionId: 22 input 23
W/libprocessgroup(  849): failed to open /acct/uid_1000/pid_3815/cgroup.procs: No such file or directory
V/AudioFlinger(  282): getOrphanEffectChain_l session 22 index -2
D/audio_hw_primary(  282): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioFlinger(  282): RecordThread: loop stopping
,V/AudioFlinger(  282): acquiring 22 from 1949, for -1
V/AudioFlinger(  282):  added new entry for 22
V/AudioRecord( 1949): start, sync event 0 trigger session 0
V/AudioRecord( 1949): mAudioRecord->start()
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
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb42a5000
V/AudioFlinger::PatchPanel(  282): createAudioPatch() status 0
V/AudioFlinger::PatchPanel(  282): createAudioPatch() added new patch handle 24 halHandle 0
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyManager(  282): setInputDevice() createAudioPatch returned 0 patchHandle 24
V/AudioPolicyManager(  282): addAudioPatch() handle 20 af handle 0 num_sources 1 num_sinks 1 source handle 10sink handle 19
V/AudioPolicyService(  282): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  282): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyService(  282): AudioCommandThread() adding set parameter string hotword_active=1, io 23 ,delay 0
V/AudioPolicyService(  282): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing set parameters string hotword_active=1, io 23
V/AudioFlinger(  282): setParameters(): io 23, keyvalue hotword_active=1, calling pid 282
V/AudioFlinger(  282): ThreadBase::setParameters() hotword_active=1
V/AudioFlinger(  282): sendConfigEvent_l() num events 1 event 2
,V/AudioFlinger(  282): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  282): in_set_parameters: enter: kvpairs=hotword_active=1
V/audio_hw_primary(  282): in_set_parameters: exit: status(0)
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb42a5000
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyManager(  282): AudioPolicyManager::startInput() input source = 1999
I/MicrophoneInputStream( 1949): mic_started com.google.android.apps.gsa.speech.audio.u@9e8bc6c
V/msm8974_platform(  282): platform_update_usecase_from_source: input source :6
D/audio_hw_primary(  282): start_input_stream: enter: stream(0xb4036520)usecase(7: audio-record)
V/voice   (  282): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  282): start_input_stream: usecase(7)
E/audio_hw_primary(  282): select_devices: enter and usecase(7)
V/msm8974_platform(  282): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  282): platform_get_input_snd_device: exit: in_snd_device(voice-rec-mic)
V/msm8974_platform_lge(  282): LGE_platform_get_input_snd_device: exit: in_snd_device(lg-vr-handset-mic)
,V/audio_hw_lge_primary(  282): LGE_exeption_scenario: enter and out: 0, in: 144
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
V/[BNRBootCompletedThread]( 4298): End of BNRProcess
V/audio_hw_primary(  282): enable_audio_route: exit
D/audio_hw_primary(  282): select_devices: done
V/audio_hw_primary(  282): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
V/[BNRBootCompletedThread]( 4298): End of BNRViaWifiProcess
,V/audio_hw_primary(  282): start_input_stream: exit
V/[BNRBootCompletedThread]( 4298): End of SpriteProcess
V/[BNRBootCompletedThread]( 4298): exit
,I/art     (  849): Explicit concurrent mark sweep GC freed 20836(1297KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 18.985ms total 575.360ms
,I/UpdateIcingCorporaServi( 1949): UpdateCorporaTask done [took 296 ms] updated apps [took 295 ms] 
D/AndroidRuntime( 4231): Shutting down VM
,D/libc-netbsd( 2043): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 2043): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 2043): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2043): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 2043): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2043): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd( 2043): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2043): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  849): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/DSQN    (  849): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/Search.LoginHelper( 1949): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1949): java.io.IOException: NetworkError
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 1949): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
W/Search.LoginHelper( 1949): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1949): java.io.IOException: NetworkError
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 1949): 	,at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 1949): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
I/WebViewFactory( 1949): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/Gmail   ( 4213): getAccountsCursor
V/GLSActivity( 2043): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Timeline(  849): Timeline: Activity_windows_visible id: ActivityRecord{e4f8b31 u0 com.lge.launcher2/.Launcher t219} time:59039
D/libc-netbsd( 2043): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2043): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 2043): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2043): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Search.LoginHelper( 1949): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1949): java.io.IOException: NetworkError
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 1949): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
W/Search.LoginHelper( 1949): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1949): java.io.IOException: NetworkError
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 1949): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,I/NotificationService(  849): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  849): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  849): Receieved: android.intent.action.PACKAGE_REMOVED
D/libc-netbsd( 2043): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2043): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2043): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 2043): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Search.LoginHelper( 1949): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1949): java.io.IOException: NetworkError
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 1949): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
W/Search.LoginHelper( 1949): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1949): java.io.IOException: NetworkError
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 1949): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
D/TaskPersister(  849): removeObsoleteFile: deleting file=220_task.xml
D/PhoneStatusBar( 1369): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/PhoneStatusBar( 1369): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1369): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1369):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1369): , Keyguard show=false, IME shown=false, Panel expanded=false
D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/BarTransitions( 1369): draw background and invalidate : color = ef000000
,D/BarTransitions( 1369): draw background and invalidate : color = ede3e3e3
W/OpenGLRenderer( 1877): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
W/OpenGLRenderer( 1877): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
W/ResourcesManager(  849): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
I/ActivityManager(  849): Waited long enough for: ServiceRecord{27e22c3f u0 com.android.mms/.service.SwitchedService}
D/libc-netbsd( 2043): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2043): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 2043): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2043): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Search.LoginHelper( 1949): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1949): java.io.IOException: NetworkError
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 1949): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
W/Search.LoginHelper( 1949): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1949): java.io.IOException: NetworkError
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 1949): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,I/LibraryLoader( 1949): Time to load native libraries: 2 ms (timestamps 9220-9222)
I/LibraryLoader( 1949): Expected native library version number "",actual native library version number ""
,D/LCardEmulationManager( 1783): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1783): getDefaultRoute
,W/art     ( 1949): Attempt to remove local handle scope entry from IRT, ignoring
W/ResourceType(  849): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)

```
