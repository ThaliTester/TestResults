#### Test 5198634075bb434_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
D/GCM     ( 1962): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ChimeraCfgMgr( 4202): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/GCM     ( 1962): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/AppUp4:CustModeStarterReceiver( 5894): onReceive
I/AppUp4:CustModeStarterReceiver( 5894): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 5894): Context : android.app.ReceiverRestrictedContext@3949dc71
D/AppUp4:CustFacade( 5894): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5894): isSimDevice : true
V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AppUp4:CustModeStarterReceiver( 5894): begin check event
I/AppUp4:CustModeStarterReceiver( 5894): Event For Nothing, skip.
V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 5863): com.google.android.talk: cancel(8) by com.google.android.talk
D/LockScreenSettings( 5965): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5965): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5965): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5965): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5965): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/art     ( 1962): Explicit concurrent mark sweep GC freed 11416(653KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 11MB/19MB, paused 1.215ms total 62.132ms
D/PackageBroadcastService( 4202): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/PackageBroadcastService( 4202): Null package name or gms related package.  Ignoreing.
V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/UpdateIcingCorporaServi( 1937): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/Icing   ( 4202): updateResources: need to parse f{com.google.android.gms}
I/UpdateIcingCorporaServi( 1937): UpdateCorporaTask done [took 54 ms] updated apps [took 54 ms] 
--------- beginning of system
I/ActivityManager(  861): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6107 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/QcrilMsgTunnelSocket( 2286): readRilMessage: Buffer = [B@34c739fb HexData = [010000000404000011000000514f454d484f4f4bef0308000100000003]
D/QcrilMsgTunnelSocket( 2286): Rcvd UNSOL response with 28 bytes data for SUB0
D/QcrilMsgTunnelSocket( 2286): Response ID 525295 is not served in this process.
D/QcrilMsgTunnelSocket( 2286): To broadcast an Intent via the notifier to external apps
D/QcrilMsgTunnelIfaceManager( 2286): handleMessage what = 0
D/QcrilMsgTunnelIfaceManager( 2286): Broadcasting intent ACTION_UNSOL_RESPONSE_OEM_HOOK_RAW
D/QC_RIL_OEM_HOOK( 1750): Received Broadcast Intent ACTION_UNSOL_RESPONSE_OEM_HOOK_RAW
D/QC_RIL_OEM_HOOK( 1750): Oem ID in QCRILHOOK UNSOL RESP is QOEMHOOK
V/TelephonyAutoProfiling( 1750): [getValue] PROFILE key : HOME_NETWORK, value : null, phoneId : 0
D/PhoneInterfaceManager( 1750): [PhoneIntfMgr] handleMessage : 2
D/PhoneInterfaceManager( 1750): [PhoneIntfMgr] handleMessage : 3
V/AlarmManager(  861): ELAPSED_WAKEUP set : Alarm{3a043552 type 2 when 92123 com.android.providers.calendar} when 92123
W/ActivityManager(  861): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 6107): getAccountsCursor
V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 6107): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ActivityManager(  861): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
D/AndroidRuntime( 6103): 
D/AndroidRuntime( 6103): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6103): CheckJNI is OFF
W/ActivityManager(  861): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 6107): Observing account changes for notifications
W/ActivityManager(  861): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/Gmail   ( 6107): Error finding the version of the Email provider.....
E/Gmail   ( 6107): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6107): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6107): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6107): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6107): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6107): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6107): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6107): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6107): We do not support migrating this version of the Email provider.
I/Gmail   ( 6107): getAccountsCursor
V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  861): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6155 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  861): Killing 6015:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  861): failed to open /acct/uid_10081/pid_6015/cgroup.procs: No such file or directory
V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 6155): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/CalendarApplication( 6155): CalendarApplication.onCreate()
D/PreferenceKeysParser( 6155): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6155): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@3fa05a18, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@3949dc71, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@16037a56, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@23457ad7, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@94cffc4, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@14ecead, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@1854e5e2, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@28fced73, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@1dfc5430, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@3336a8a9, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@115f7e2e, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3aeedcf, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@1b0a835c, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@2ca82665, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@16694f3a, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@21d697eb, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@356a7948, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@4f9c3e1, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@190d2506, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@1484c7c7, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@3c51e1f4, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@186dbd1d, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@37c68b92, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@2fc1963, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@1aa52960, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@b2e0e19, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@b3dcede, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@3c0ce8bf, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@3237b8c, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@872d5, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@3c53faea, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@13151db, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@3352c478, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@3eea6751, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@2eeedbb6, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@276930b7, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@392bb024, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@71d278d, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@d84fd42, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@29d62153, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@2785aa90, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@941af89, lg_
D/GeneralPreferenceUtils( 6155): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6155): [init]
I/Config  ( 6155): LGCalendar ver.4.40.17
I/Config  ( 6155): start check model
I/Config  ( 6155): start check native_ca
I/Config  ( 6155): Config Operator=OPEN, Country=EU
D/Config  ( 6155): [setDefaultValuesToPref]
D/Config  ( 6155): [parseProfiles]
D/ProfilesParser( 6155): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6155): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6155): [updateProfiletoCountryInfo]
D/GeneralPreference( 6155): [checkAndMigrateOldPreference]
D/AlertReceiver( 6155): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
I/InitNotificationRingtoneService( 6155): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 6155): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
I/art     (  861): Explicit concurrent mark sweep GC freed 11717(532KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 4.729ms total 172.640ms
D/AndroidRuntime( 6103): Calling main entry com.android.commands.am.Am
I/Gmail   ( 6107): notifyAccountChanged
I/ActivityManager(  861): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/AlertUtils( 6155): [getCalendarNotiSoundURIFromCursor] getCount()= 21
I/AlertUtils( 6155): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6155): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6155): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6155): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6155): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/Gmail   ( 6107): getAccountsCursor
I/AlertUtils( 6155): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/Gmail   ( 6107): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/AlertUtils( 6155): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6155): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/Gmail   ( 6107): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/AlertUtils( 6155): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6155): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 6155): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6155): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6155): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/Gmail   ( 6107): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 6107): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/AlertUtils( 6155): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6155): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6155): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
D/ActivityManager(  861): setTaskToReturnTo : TaskRecord{11d6045a #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  861): setTaskToReturnTo : TaskRecord{11d6045a #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  861): AppWindowTokenEx init.. 
D/ContextHelper(  861): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  861): Focus left window: Window{2576a96c u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 6103): Shutting down VM
V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AlertUtils( 6155): set default noti to content://media/internal/audio/media/38
I/[LGHome]EVENT( 1877): [Launcher.java:986:onPause()]onPause
W/HolidayIntentService( 6155): onHandleIntent
D/HolidayDataLoader( 6155): readJsonAsset : holiday.json
D/SplitWindow(  861): check instance of lgWin Window{226279fe u0 Starting com.test.thalitest}
I/InitNotificationRingtoneService( 6155): End InitializeAlertRingtoneService.onHandleIntent
E/AgendaWidgetManager( 6155): [updateWidgets] 
D/AlertService( 6155): 0 Action = android.intent.action.PROVIDER_CHANGED
I/ActivityManager(  861): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6192 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1877): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
D/MonthWidgetProvider( 6155): [onReceive]
D/CalendarWidgetProvider( 6155): [onReceive]
D/CalendarWidgetProvider( 6155): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6155): [onCreate] mContext.getPackageName() = com.android.calendar
E/HolidayIntentService( 6155): onHandleIntent:holiday data empty
D/WeekWidgetProvider( 6155): [onReceive]
D/CalendarWidgetProvider( 6155): [onReceive]
D/CalendarWidgetProvider( 6155): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6155): [onCreate] mContext.getPackageName() = com.android.calendar
I/AudioManager( 5824): getMode name:com.lge.qremote
I/HotwordDetector( 1937): Closing mic
I/AudioManager( 5824): getMode name:com.lge.qremote
I/MicrophoneInputStream( 1937): mic_close com.google.android.apps.gsa.speech.audio.u@2f3c6912
V/AudioRecord( 1937): stop()
D/AudioRecord( 1937): AudioRecord->stop()
I/AudioManager( 5824): getMode name:com.lge.qremote
V/AudioFlinger(  276): RecordHandle::stop()
V/AudioFlinger(  276): RecordThread::stop
I/[LGHome]EVENT( 1877): [Launcher.java:5214:onStop()]onStop
V/AudioFlinger(  276): Record stopped OK
V/AudioPolicyManager(  276): stopInput() input 16
V/AudioPolicyService(  276): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  276): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  276): AudioCommandThread() waking up
V/AudioPolicyService(  276): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  276): releaseAudioPatch handle 17
V/AudioFlinger::PatchPanel(  276): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  276): ThreadBase::setParameters() routing=0
V/AudioFlinger(  276): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  276): processConfigEvents_l() remaining events 1
V/AudioFlinger(  276): processConfigEvents_l() DONE thread 0xb383c000
D/audio_hw_primary(  276): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
I/WindowStateAnimator(  861): Starting window displayed
I/SystemUI[Framework](  861): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
W/PhoneWindowManagerEx(  861): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  861): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  861): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  861): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2988b3ce,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  861): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,D/PhoneStatusBar( 1374): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
I/[SystemUI]NavigationThemeResource( 1374): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1374):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1374): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1374): draw background and invalidate : color = 19000000
D/BarTransitions( 1374): draw background and invalidate : color = 19181818
V/audio_hw_primary(  276): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  276): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  276): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  276): disable_audio_route: reset and update mixer path: audio-record
I/AudioManager( 5824): getMode name:com.lge.qremote
V/audio_hw_primary(  276): disable_audio_route: exit
E/audio_hw_primary(  276): disable_snd_device: enter 144
D/hardware_info(  276): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  276): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  276): stop_input_stream: exit: status(0)
V/audio_hw_primary(  276): in_standby: exit:  status(0)
V/AudioFlinger(  276): RecordThread: loop stopping
V/AudioPolicyService(  276): AudioCommandThread() going to sleep
V/AudioPolicyManager(  276): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  276): removeAudioPatch() handle 18 af handle 17
V/AudioPolicyService(  276): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  276): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  276): AudioCommandThread() waking up
V/AudioPolicyService(  276): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  276): AudioCommandThread() adding set parameter string hotword_active=0, io 16 ,delay 0
V/AudioPolicyService(  276): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  276): AudioCommandThread() waking up
V/AudioPolicyService(  276): AudioCommandThread() processing set parameters string hotword_active=0, io 16
V/AudioFlinger(  276): setParameters(): io 16, keyvalue hotword_active=0, calling pid 276
V/AudioFlinger(  276): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  276): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  276): RecordThread: loop starting
V/AudioPolicyService(  276): AudioCommandThread() going to sleep
V/AudioFlinger(  276): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  276): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  276): in_set_parameters: exit: status(0)
V/AudioFlinger(  276): processConfigEvents_l() DONE thread 0xb383c000
V/AudioFlinger(  276): RecordThread: loop stopping
V/AudioPolicyService(  276): AudioCommandThread() going to sleep
V/AudioRecord( 1937): stop()
V/AudioRecord( 1937): stop()
V/AudioRecord( 1937): stop()
V/AudioFlinger(  276): releasing 15 from 1937 for -1
V/AudioFlinger(  276):  decremented refcount to 0
V/AudioFlinger(  276): purging stale effects
V/AudioFlinger(  276): RecordHandle::stop()
V/AudioFlinger(  276): RecordThread::stop
V/AudioPolicyManager(  276): releaseInput() 16
V/AudioPolicyManager(  276): closeInput(16)
V/AudioFlinger(  276): closeInput() 16
V/AudioSystem(  276): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1750): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1937): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1985): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1374): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 2645): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  276): ThreadBase::exit
V/AudioSystem( 3177): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  276): RecordThread: loop starting
V/AudioFlinger(  276): RecordThread 0xb383c000 exiting
V/AudioSystem(  861): ioConfigChanged() event 4, ioHandle 16
D/audio_hw_primary(  276): adev_close_input_stream: enter:stream_handle(0xb546dd40)
D/audio_hw_primary(  276): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/audio_hw_primary(  276): in_standby: exit:  status(0)
V/AudioPolicyService(  276): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  276): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  276): AudioCommandThread() waking up
V/AudioPolicyService(  276): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  276): AudioCommandThread() going to sleep
V/AudioPolicyManager(  276): releaseInput() exit
V/AudioFlinger(  276): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  276): removeClient_l() pid 1937, calling pid 276
I/HotwordRecognitionRnr( 1937): Stopping hotword detection.
I/HotwordRecognitionRnr( 1937): Hotword detection finished
I/AudioManager( 5824): getMode name:com.lge.qremote
I/Gmail   ( 6107): getAccountsCursor
V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AudioManager( 5824): getMode name:com.lge.qremote
I/ActivityManager(  861): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6211 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ContextHelper( 6192): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
W/ResourcesManager( 6211): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/WebViewFactory( 6192): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
D/CalendarProvider2( 6211): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@31adef8a
D/CalendarProvider2( 6211): [getOrCreateCalendarAlarmManager]
I/LibraryLoader( 6192): Time to load native libraries: 6 ms (timestamps 3390-3396)
I/CalendarProvider2( 6211): Created com.android.providers.calendar.CalendarAlarmManager@23457ad7(com.android.providers.calendar.CalendarProvider2@31adef8a)
I/LibraryLoader( 6192): Expected native library version number "",actual native library version number ""
D/CalendarProviderBroadcastReceiver( 6211): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6211): [IntentService] WakeLock acquire, start IntentSerivce
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/CalendarProvider2( 6211): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 6211): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6211): [getOrCreateCalendarAlarmManager]
I/AudioManager( 5824): getMode name:com.lge.qremote
V/WebViewChromiumFactoryProvider( 6192): Binding Chromium to main looper Looper (main, tid 1) {23457ad7}
I/AudioManager( 5824): getMode name:com.lge.qremote
I/LibraryLoader( 6192): Expected native library version number "",actual native library version number ""
I/chromium( 6192): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
D/CalendarProvider2( 6211): [IntentService] Release Lock
D/CalendarProvider2( 6211): CalendarProviderIntentService.onDestroy()
I/BrowserStartupController( 6192): Initializing chromium process, singleProcess=true
W/art     ( 6192): Attempt to remove local handle scope entry from IRT, ignoring
I/ActivityManager(  861): Killing 6067:com.google.android.setupwizard/u0a38 (adj 15): empty #11
E/SysUtils( 6192): ApplicationContext is null in ApplicationStatus
W/libprocessgroup(  861): failed to open /acct/uid_10038/pid_6067/cgroup.procs: No such file or directory
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
W/chromium( 6192): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6192): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6192): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6192): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6192): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6192): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6192): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6192): Remote Branch: 
I/Adreno-EGL( 6192): Local Patches: 
I/Adreno-EGL( 6192): Reconstruct Branch: 
V/AudioPolicyService(  276): registerClient() client 0xb40277a0, uid 10316
,D/BluetoothManagerService(  861): Message: 20
D/BluetoothManagerService(  861): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@35dc836a:true
D/BluetoothAdapterService(687664499)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@4f9c3e1
,W/art     ( 6192): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6192): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6192): CordovaWebView is running on device made by: LGE
,W/art     ( 6192): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6192): Attempt to remove local handle scope entry from IRT, ignoring
,I/Activity( 6192): Activity.onPostResume() called 
,D/OpenGLRenderer( 6192): Render dirty regions requested: true
I/OpenGLRenderer( 6192): Initialized EGL, version 1.4
D/OpenGLRenderer( 6192): Enabling debug mode 0
,D/Atlas   ( 6192): Validating map...
,D/SplitWindow(  861): check instance of lgWin Window{2ed49b1a u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 6192): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  861): Focus entered window: Window{2ed49b1a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  861): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  861): Displayed com.test.thalitest/.MainActivity: +1s237ms
,I/Timeline(  861): Timeline: Activity_windows_visible id: ActivityRecord{50f768b u0 com.test.thalitest/.MainActivity t220} time:94127
I/Timeline( 6192): Timeline: Activity_idle id: android.os.BinderProxy@37c68b92 time:94138
W/BindingManager( 6192): Cannot call determinedVisibility() - never saw a connection for the pid: 6192
,D/JsMessageQueue( 6192): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  861): Process com.android.contacts (pid 5946) has died
,I/ActivityManager(  861): Process com.android.gallery3d (pid 5921) has died
,D/jxcore_app_log( 6192): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622834688
,D/JX-Cordova( 6192): jxcore cordova android initializing
D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 95156411686; DSPS: 3216027; Offset : -2989839059
,I/art     ( 6192): CheckpointMarkThreadRoots callback created = 0x9c5d8630
,I/art     ( 6192): CheckpointMarkThreadRoots callback created = 0x9c5d8600
,W/jxcore-log( 6192): Initializing JXcore engine
,W/jxcore-log( 6192): JXcore engine is ready
W/jxcore-log( 6192): Starting JXcore engine
,W/.test.thalitest( 6192): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6284]" dev="sockfs" ino=6284 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6192): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6192): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7884]" dev="sockfs" ino=7884 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6192): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
,W/.test.thalitest( 6192): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6192): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[27949]" dev="sockfs" ino=27949 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
D/Finsky  ( 5723): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/AlarmManager(  861): RTC_WAKEUP set : Alarm{33a154be type 0 when 1449063128967 com.android.vending} when 1449063128967
,I/GAV2    ( 6107): Thread[GAThread,5,main]: No campaign data found.
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/jxcore-log( 6192): Platform android
W/jxcore-log( 6192): 
W/jxcore-log( 6192): Process ARCH arm
W/jxcore-log( 6192): 
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/NotificationManager(  861): android: cancelAsUser(2) by android
,D/libc-netbsd( 5723): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5723): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5723): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5723): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  272): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
I/System.out( 5723): propertyValue:false
D/libc-netbsd( 5723): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5723): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5723): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5723): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  861): android: cancelAsUser(2) by android
,D/AlertService( 6155): Beginning updateAlertNotification
,D/AlertService( 6155): No fired or scheduled alerts
I/NotificationManager( 6155): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6155): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6155): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6155): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6155): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6155): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6155): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6155): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6155): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6155): com.android.calendar: cancel(9) by com.android.calendar
,I/NotificationManager( 6155): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6155): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6155): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6155): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6155): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6155): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6155): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6155): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6155): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6155): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6155): com.android.calendar: cancel(20) by com.android.calendar
,D/AlertService( 6155): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
I/qtaguid ( 5723): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5723): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5723): untagSocket(41) failed with errno -22
,D/AlarmScheduler( 6155): No events found starting within 1 week.
,D/Finsky  ( 5723): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430000] >= Server Version [-1]
,V/AlarmManager(  861): RTC_WAKEUP set : Alarm{10623846 type 0 when 1449063129677 com.google.android.googlequicksearchbox} when 1449063129677
,I/ActivityManager(  861): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6316 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/art     ( 1937): Verification of void com.google.android.apps.gsa.extradex.attemptedsearchhistory.d.run() took 167.916ms
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  861): android: cancelAsUser(2) by android
,I/qtaguid ( 5723): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5723): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5723): untagSocket(41) failed with errno -22
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/art     (  861): Explicit concurrent mark sweep GC freed 15612(719KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.590ms total 179.206ms
I/jxcore-log( 6192): JXcore Cordova bridge is ready!
I/jxcore-log( 6192): 
,W/jxcore-log( 6192): JXcore engine is started
I/chromium( 6192): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/Choreographer( 6192): Skipped 204 frames!  The application may be doing too much work on its main thread.
W/ResourcesManager( 6316): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6316): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/MultiDex( 6316): VM with version 2.1.0 has multidex support
I/MultiDex( 6316): install
I/MultiDex( 6316): VM has multidex support, MultiDex support library is disabled.
,I/jxcore-log( 6192): Toggling radios to true
I/jxcore-log( 6192): 
D/BluetoothAdapter( 6192): enable(): BT is already enabled..!
V/JNIHelp ( 6316): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/WifiServiceImplEx(  861): setWifiEnabled: true pid=6192, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService(  861): setWifiEnabled: true pid=6192, uid=10316
,D/WifiServiceImplEx(  861): disconnect pid=6192, uid=10316, packageName=com.test.thalitest
D/WifiServiceImplEx(  861): reconnect pid=6192, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 6192): Radios toggled
I/jxcore-log( 6192): 
,I/art     ( 5723): CheckpointMarkThreadRoots callback created = 0xaafd9ea0
,I/wpa_supplicant( 2809): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2809): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 4
,E/WifiStateMachine(  861): WifiStateMachine: Leaving Connected state
D/WfdsMonitor( 1803): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiConfigStore(  861): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/ActivityThread( 6316): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6316): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@6c2c6c1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6316): Installed default security provider GmsCore_OpenSSL
,D/LGWifiP2pService(  861): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  861): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/NotificationManager( 6316): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6316): com.google.android.gms: cancel(39789) by com.google.android.gms
I/art     ( 5723): CheckpointMarkThreadRoots callback created = 0xaafd9e70
,D/DhcpStateMachine(  861): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  272): Clearing all IP addresses on wlan0
I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 7
D/WearableService( 1731): callingUid 10006, callindPid: 1731
E/MDM     ( 1731): [80] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/NativeCrypto( 1962): Read error: ssl=0xb049c200: I/O error during system call, Connection timed out
V/NativeCrypto( 1962): SSL shutdown failed: ssl=0xb049c200: I/O error during system call, Broken pipe
,D/libc-netbsd(  861): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  861): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 7
I/QCNEJ   ( 1830): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1830): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-02 14:32:10.42 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1830): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20(  861): hidePasspointNotification off =false
D/ConnectivityService(  861): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  861): ignoring duplicate network state non-change
E/WifiStateMachine(  861): Start Disconnecting Watchdog 1
I/wpa_supplicant( 2809): wlan0: CTRL-EVENT-SCAN-STARTED 
,I/QCNEJ   ( 1830): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  861): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
I/QCNEJ   ( 1830): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-02 14:32:10.436 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1830): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  861): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  861): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  861): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20(  861): hidePasspointNotification off =false
W/Settings(  861): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  861): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  861): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGWifiP2pService(  861): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  861): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  272): Clearing all IP addresses on wlan0
D/libc-netbsd(  861): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  861): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  861): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  861): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WifiHS20(  861): hidePasspointNotification off =false
W/Settings(  861): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  861): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  861): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1830): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1830): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-02 14:32:10.449 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1830): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/ConnectivityService(  861): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
D/WifiNetworkAgent(  861): NetworkAgent: NetworkAgent channel lost
,D/WifiHS20(  861): hidePasspointNotification off =false
I/QCNEJ   ( 1830): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1830): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-02 14:32:10.464 DNS addrs= 0.0.0.0, 0.0.0.0, 
W/Settings(  861): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  861): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  861): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1830): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  861): ValidatedState{ when=-3ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  861): DefaultState{ when=-12ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  861): Forcing reevaluation
W/Settings(  861): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  861): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  861): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1830): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1830): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-02 14:32:10.469 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1830): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiServerServiceExt(  861): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  861): setSupplicantStateDISCONNECTED
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
,D/WifiServerServiceExt(  861): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  861): setSupplicantStateSCANNING
D/GCM     ( 1962): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1962): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 4202): Restart initialization of location
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/NotificationManager( 1962): com.google.android.gms: cancel(0) by com.google.android.gms
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
,V/GmsCoreStatsServiceLauncher( 4202): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/ConnectivityService(  861): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  861): disableDataServiceNotify
,D/DhcpStateMachine(  861): StoppedState
D/DhcpStateMachine(  861): StoppedState{ when=-147ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/DSQN    (  861): stop dsqn bin
I/ActivityManager(  861): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6357 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/ConnectivityService(  861): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  861):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  861):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  861): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  861): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  861): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  861): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  861): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  861): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  861): Disconnected - quitting
D/ConnectivityService(  861): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  861): MasterInitialState.processMessage what=3
D/ConnectivityService(  861): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  861): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  861): MasterInitialState.processMessage what=3
V/NetworkPolicy(  861): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy(  861): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService(  861): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  861): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  861): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkManagementService(  861): Removing idletimer
D/WIFI    (  861): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  861):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524292
D/TelephonyNetworkFactory-1( 1750): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/QCNEJ   ( 1830): |CORE| No family connected
W/GCoreFlp( 1731): No location to return for getLastLocation()
D/TelephonyNetworkFactory-1( 1750):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
W/FusedLocationProvider( 1962): location=null
W/QCNEJ   ( 1830): |CORE| No family connected
I/QCNEJ   ( 1830): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1830): |CORE| sendDefaultNwMsg: default = -1
,W/Settings(  861): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/NativeLibraryUtils( 6316): Install completed successfully. count=13 extracted=0
,I/ActivityManager(  861): Process com.google.android.talk (pid 5863) has died
,W/ResourcesManager( 6357): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6357): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6357): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6357): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6357): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/IndexDatabaseHelper( 6357): Using schema version: 115
I/IndexDatabaseHelper( 6357): Index is fine
,I/art     ( 6316): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
I/art     ( 6316): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
I/ActivityManager(  861): Process com.lge.appbox.client (pid 5894) has died
,I/NotificationManager( 6316): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 5723): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 5723): [1] GearheadStateMonitor.access$100: mIsProjecting:false
V/WiFiOffLoadBroadcast( 6357): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6357): MCCMNC not supported: null
I/ActivityManager(  861): Process com.lge.lockscreensettings (pid 5965) has died
,I/ActivityManager(  861): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6382 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  861): android: cancelAsUser(2) by android
,I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2809): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
I/ElegantRequestDirector( 5723): I/O exception (javax.net.ssl.SSLException) caught when processing request: Write error: ssl=0xaaf92a00: I/O error during system call, Broken pipe
I/ElegantRequestDirector( 5723): Retrying request
D/libc-netbsd( 5723): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5723): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5723): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5723): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  272): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  861): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/Finsky  ( 5723): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 5723): [1] WearSupportService.startHygiene: disabled
I/PCSuite ( 6382): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
I/QCNEJ   ( 1830): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1830): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-02 14:32:11.575 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1830): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
D/LocSvc_java(  861): onReceive
W/Settings(  861): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  861): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  861): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/Finsky  ( 5723): [1] DailyHygiene.access$600: Logging device features
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
W/Settings(  861): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  861): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  861): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1830): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1830): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-02 14:32:11.586 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1830): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
D/WifiServerServiceExt(  861): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  861): setSupplicantStateASSOCIATING
D/PCSuite ( 6382): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6382): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
,V/AlarmManager(  861): RTC_WAKEUP set : Alarm{c50858a type 0 when 1449063131628 com.android.vending} when 1449063131628
,I/wpa_supplicant( 2809): wlan0: Associated with c0:ff:d4:d3:aa:48
I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 4
D/WifiServerServiceExt(  861): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  861): setSupplicantStateASSOCIATED
V/WiFiOffLoadBroadcast( 6357): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6357): MCCMNC not supported: null
D/Finsky  ( 5723): [1] DailyHygiene.reschedule: Scheduling new run in 27 minutes (failures=2)
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
W/Settings(  861): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  861): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  861): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1830): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  861): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1830): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-02 14:32:11.667 DNS addrs= 0.0.0.0, 0.0.0.0, 
W/Settings(  861): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  861): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/QCNEJ   ( 1830): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
D/WifiServerServiceExt(  861): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  861): setSupplicantStateFOUR_WAY_HANDSHAKE
I/QCNEJ   ( 1830): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/QCNEJ   ( 1830): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-02 14:32:11.669 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/QCNEJ   ( 1830): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/PCSuite ( 6382): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6382): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6382): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/wpa_supplicant( 2809): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2809): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 4
D/WifiServerServiceExt(  861): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  861): setSupplicantStateGROUP_HANDSHAKE
I/WifiServiceExtension(  861): setVHTCapabilityType  : false
,V/WiFiOffLoadBroadcast( 6357): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/WifiServerServiceExt(  861): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  861): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  861): setSecurityType  : 2
,D/WiFiOffLoadBroadcast( 6357): MCCMNC not supported: null
I/PCSuite ( 6382): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6382): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6382): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/Settings(  861): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  861): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  861): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1830): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1830): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-02 14:32:11.716 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1830): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/QCNEJ   ( 1830): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  861): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  861): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  861): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1830): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-02 14:32:11.724 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1830): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/ConnectivityService(  861): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  861): Got NetworkAgent Messenger
D/ConnectivityService(  861): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  861): NetworkAgent connected
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
E/WifiConfigStore(  861): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/art     ( 1731): Explicit concurrent mark sweep GC freed 16237(992KB) AllocSpace objects, 15(240KB) LOS objects, 39% free, 11MB/18MB, paused 1.297ms total 125.578ms
D/DeviceConnectionService( 1731): client connected with version: 8296000
,E/WifiConfigStore(  861): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
V/WiFiOffLoadBroadcast( 6357): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  861): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  861): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  861): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  861): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  272): Setting iface cfg
E/WifiStateMachine(  861): Start Dhcp Watchdog 2
D/WiFiOffLoadBroadcast( 6357): MCCMNC not supported: null
D/DhcpStateMachine(  861): StoppedState{ when=-4ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  861): WaitBeforeStartState
,D/ConnectivityService(  861): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/WifiServerServiceExt(  861): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  861): setSupplicantStateCOMPLETED
D/WifiServerServiceExt(  861): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  861): setSupplicantStateCOMPLETED
I/PCSuite ( 6382): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6382): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6382): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6357): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6357): MCCMNC not supported: null
I/ActivityManager(  861): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6408 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,E/WifiStateMachine(  861): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  861): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  861): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2d75cae target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  861): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2d75cae target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  861): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,V/LgDhcpStateMachineHelper(  861): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  861): DHCP Start wake lock is acquired.
D/CommandListener(  272): Setting iface cfg
I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  861): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  861): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  272): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  861): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/ConnectivityService(  861): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  861): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  861): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  861): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  861): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  861): ignoring duplicate network state non-change
W/Settings(  861): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  861): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  861): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService(  861): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  861): Adding iface wlan0 to network 101
,W/Settings(  861): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  861): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  861): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20(  861): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  861): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  861): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  861): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/QCNEJ   ( 1830): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine(  861): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/QCNEJ   ( 1830): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-61 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-02 14:32:11.923 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1830): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.109 ipV6Addr=
I/QCNEJ   ( 1830): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
,D/WifiHS20(  861): [PASSPOINT] passpointNotification: hs20AP list is checked
E/ConnectivityService(  861): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  861): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Settings(  861): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  861): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  861): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityService(  861): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1830): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-61 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-02 14:32:11.933 DNS addrs= 192.168.1.1, 0.0.0.0, 
E/Netd    (  272): netlink response contains error (File exists)
I/QCNEJ   ( 1830): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.109 ipV6Addr=
I/QCNEJ   ( 1830): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  861): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  861): addLocalRoutetoDefaultNetwork
I/QCNEJ   ( 1830): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-61 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-02 14:32:11.941 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/ConnectivityService(  861): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  861): Setting Dns servers for network 101 to [/192.168.1.1]
I/QCNEJ   ( 1830): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.109 ipV6Addr=
I/QCNEJ   ( 1830): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  861): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  861): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1830): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-61 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-02 14:32:11.943 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1830): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.109 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui,:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
D/Nat464Xlat(  861): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  861): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  861): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  861): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  861): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  861): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  861): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  861):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  861):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  861):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  861):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  861):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  861): [LWD] Start DNSResolver start to wait
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
D/ConnectivityService(  861): currentScore = 0, newScore = 20
D/ConnectivityService(  861):    accepting network in place of null
D/ConnectivityService(  861): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1750): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1750):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = true, mWifiLevel = 2
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  861): [LWD] wait 500ms before dns check
D/WIFI    (  861): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  861):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  861): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  861): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  861): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  861): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1830): |CORE| No family connected
I/QCNEJ   ( 1830): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/ConnectivityService(  861): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  861): [e] list.add(nai) empty : false size: 1
D/ConnectivityService(  861): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  861): validation of new default Network = false
D/ConnectivityService(  861): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  861): enableDataServiceNotify 
D/DSQN    (  861): start dsqn bin
I/QCNEJ   ( 1830): |CORE| sendDefaultNwMsg: default = 1
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = true, mWifiLevel = 2
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
,D/ConnectivityService(  861): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  861):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  861):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  861): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524290
V/NetworkPolicy(  861): [LG_RESTRICTED] checkMobilePolicy_type()
I/DSQN    ( 6430): DSQN samuel.seo ver 141203
E/DSQN    ( 6430): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6430): created command queue thread
I/DSQN    ( 6430): Interface wlan0 address 192.168.1.109 0xc0a8016d
I/DSQN    ( 6430): Interface wlan0 netmask 255.255.255.0 0xc0a8016d
D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
W/ResourcesManager( 6408): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/DhcpStateMachine(  861): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper(  861): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  861): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/dhcpcd  ( 6433): version 5.5.6 starting
E/dhcpcd  ( 6433): get_duid: Read-only file system
,I/dhcpcd  ( 6433): wlan0: rebinding lease of 192.168.1.109
,I/dhcpcd  ( 6433): wlan0: acknowledged 192.168.1.109 from 192.168.1.1
,I/Babel_SMS( 6408): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6408): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6408): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6408): MmsConfig.loadFromDatabase
I/dhcpcd  ( 6433): wlan0: leased 192.168.1.109 for 86400 seconds
,E/Babel_SMS( 6408): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6408): MmsConfig.loadFromResources
E/Babel_SMS( 6408): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6408): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6408): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6408): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6408): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6408): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6408): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6408): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6408): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6408): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6408): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6408): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6408): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6408): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6408): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6408): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6408): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6408): found sensor: Motion Accel, handle=46
,W/Settings( 6408): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6408): startup - clean
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  861): [LWD] DNSResolver start dns
D/libc-netbsd(  861): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  861): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  861): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  861): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  272): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
,I/art     ( 6408): CheckpointMarkThreadRoots callback created = 0xaaf427e0
,D/libc-netbsd(  272): res_queryN name = xxxxx succeed
,I/System.out(  861): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  861): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  861): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  861): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  861): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Babel   ( 6408): deleted: false for 0
,I/DSQN    ( 6430): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6430): restart monitoring
I/DSQN    ( 6430): dsqn report finish
D/LGDataListener(  272): argv[0]=dsqncommand
D/LGDataListener(  272): argv[1]=wlan0
D/LGDataListener(  272): argv[2]=1
D/LGDataListener(  272): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  861): DSQM DsqnNotification wlan0  1
D/DSQN    (  861): start to monitor internet connection
,I/art     ( 6408): CheckpointMarkThreadRoots callback created = 0xaaf427c0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  861): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 02 Dec 2015 13:32:12 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449063132562], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449063132543]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  861): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  861): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  861): Validated
D/ConnectivityService(  861): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  861): rematching NetworkAgentInfo [WIFI () - 101]
D/WifiDataContinuityService(  861): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
D/ConnectivityService(  861):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  861):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  861):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  861): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  861): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  861):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  861):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  861): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  861): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  861): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524290
I/WifiServerServiceExt(  861): set CMD_CAPTIVE_CHECK_COMPLETED
D/WIFI    (  861): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  861):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1750): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1750):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
V/WiFiOffLoadBroadcast( 6357): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6357): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6357): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6357): MCCMNC not supported: null
W/AudioCapabilities( 6408): Unsupported mime audio/x-lg-flac
,V/WiFiOffLoadBroadcast( 6357): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/AudioCapabilities( 6408): Unsupported mime audio/adpcm
W/AudioCapabilities( 6408): Unsupported mime audio/g726
D/WiFiOffLoadBroadcast( 6357): MCCMNC not supported: null
W/AudioCapabilities( 6408): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6408): Unsupported mime audio/wma-voice
,V/WiFiOffLoadBroadcast( 6357): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/VideoCapabilities( 6408): Unsupported mime video/mjpg
D/WiFiOffLoadBroadcast( 6357): MCCMNC not supported: null
D/libc-netbsd(  861): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  861): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  861): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  861): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  861): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  861): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  861): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  861): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  861): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper(  861): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  861): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  861): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  861): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  861): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.109
V/LgDhcpStateMachineHelper(  861): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  861): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  861): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  861): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  861): RunningState
W/VideoCapabilities( 6408): Unsupported mime video/theora
D/Finsky  ( 5723): [700] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
V/WiFiOffLoadBroadcast( 6357): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6357): MCCMNC not supported: null
V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/WiFiOffLoadBroadcast( 6357): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/NotificationManager(  861): android: cancelAsUser(2) by android
D/WiFiOffLoadBroadcast( 6357): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6357): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6357): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6357): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/AudioCapabilities( 6408): Unsupported mime audio/evrc
W/AudioCapabilities( 6408): Unsupported mime audio/qcelp
W/VideoCapabilities( 6408): Unrecognized profile 2130706433 for video/avc
D/WiFiOffLoadBroadcast( 6357): MCCMNC not supported: null
,W/AudioCapabilities( 6408): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6408): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6408): Unsupported mime audio/evrc
V/WiFiOffLoadBroadcast( 6357): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6357): MCCMNC not supported: null
W/VideoCapabilities( 6408): Unsupported mime video/mp4v-esdp
,V/WiFiOffLoadBroadcast( 6357): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6357): MCCMNC not supported: null
I/PCSuite ( 6382): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/libc-netbsd( 5723): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5723): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/PCSuite ( 6382): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/libc-netbsd( 5723): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5723): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  272): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
I/VideoCapabilities( 6408): Unsupported profile 4 for video/mp4v-es
V/WiFiOffLoadBroadcast( 6357): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6357): MCCMNC not supported: null
,W/VideoCapabilities( 6408): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6408): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6408): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6408): Unrecognized profile 2130706433 for video/avc
,D/libc-netbsd(  272): res_queryN name = xxxxx succeed
I/System.out( 5723): propertyValue:false
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  861): Process com.google.android.apps.plus (pid 5983) has died
I/PCSuite ( 6382): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6382): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,I/vclib   ( 6408): onServiceConnected
W/Babel   ( 6408): Attempted to change video mute state without an active call.
I/NotificationManager( 6408): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/ConnectivityService(  861): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  861): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  861): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  861): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  861): identical MTU - not setting
D/Nat464Xlat(  861): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  861): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  861):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  861):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  861): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524295
D/ConnectivityService(  861): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  861): enableDataServiceNotify 
D/DSQN    (  861): start dsqn bin
I/QCNEJ   ( 1830): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
,I/QCNEJ   ( 1830): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-61 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-02 14:32:13.509 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/DSQN    (  861): dsqn is running restart
,I/DSQN    ( 6483): DSQN samuel.seo ver 141203
E/DSQN    ( 6483): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6483): created command queue thread
I/DSQN    ( 6483): Interface wlan0 address 192.168.1.109 0xc0a8016d
I/DSQN    ( 6483): Interface wlan0 netmask 255.255.255.0 0xc0a8016d
,D/ConnectivityService(  861): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/ConnectivityService(  861): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  861): onReceive
D/LocSvc_java(  861): got connectivity action
,D/LocSvc_java(  861): broadcast - no network connections
D/LocSvc_java(  861): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  861): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  861): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  861): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  861): ignore wifi update if we are not in OPENING or CLOSING
I/ActivityManager(  861): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6486 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  305): Explicit concurrent mark sweep GC freed 703(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 22.818ms
D/LocSvc_java(  861): onReceive
D/LocSvc_java(  861): got connectivity action
D/LocSvc_java(  861): broadcast - no network connections
D/LocSvc_java(  861): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  861): Sending msg: 4 arg1:0 arg2:1
D/GpsLocationProvider(  861): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/LocSvc_java(  861): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  861): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  861): ignore wifi update if we are not in OPENING or CLOSING
I/art     (  305): Explicit concurrent mark sweep GC freed 8(256B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 291us total 40.653ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 335us total 21.272ms
,D/GpsLocationProvider(  861): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  861): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider(  861): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  861): Process com.google.android.talk (pid 6408) has died
,I/MusicStore( 6486): Database version: 120
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6486): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6486): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6486): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6486): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6486): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6486): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 6486): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6486): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@31d33620: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6486): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6486): GMSCore installation verified
I/ConfigStore( 6486): Config Database version: 1
D/BluetoothManagerService(  861): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 6192): Got Device Bluetooth address: F8:95:C7:87:85:54
I/jxcore-log( 6192): 
I/jxcore-log( 6192): my name is : LGE-LG-D722_PT7950
I/jxcore-log( 6192): 
,I/jxcore-log( 6192): attempting to connect to test coordinator
I/jxcore-log( 6192): 
,I/jxcore-log( 6192): check test folder
I/jxcore-log( 6192): 
I/jxcore-log( 6192): found test : ./testFindPeers.js
I/jxcore-log( 6192): 
I/jxcore-log( 6192): found test : ./testReConnect.js
I/jxcore-log( 6192): 
,I/MediaRouter( 6486): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
V/MusicLeanback( 6486): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/jxcore-log( 6192): found test : ./testSendData.js
I/jxcore-log( 6192): 
,I/NetworkMonitor( 6486): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6486): type=WIFI subType= reason=null isConnected=true
,I/jxcore-log( 6192): Test app app.js loaded
I/jxcore-log( 6192): 
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
I/ActivityManager(  861): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6529 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/chromium( 6192): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager(  861): Process com.android.calendar (pid 6155) has died
,I/art     ( 1962): Explicit concurrent mark sweep GC freed 12231(740KB) AllocSpace objects, 2(32KB) LOS objects, 39% free, 11MB/19MB, paused 3.083ms total 129.261ms
,I/GHttpClientFactory( 6486): Using our fixed implementation of GMSCore's GoogleHttpClient
,W/ResourcesManager( 6529): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6529): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6529): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/GoogleURLConnFactory( 6486): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  861): Process com.android.providers.calendar (pid 6211) has died
,I/QCNEJ   ( 1830): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1830): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-02 14:32:14.824 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/rmt_storage(  267): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  267): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  267): wakelock acquired: 1, error no: 42
,I/rmt_storage(  267): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
E/lowmemorykiller(  244): Error writing /proc/6316/oom_score_adj; errno=22
,I/NotificationManager( 6486): com.google.android.music: cancel(1061) by com.google.android.music
V/WifiInternetCheck(  861): Single check msg out of sync, ignoring.
I/ActivityManager(  861): Process com.google.android.gms:car (pid 6316) has died
W/ActivityManager(  861): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 1000ms
,D/ConnectivityService(  861): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  861): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java(  861): onReceive
D/LocSvc_java(  861): got connectivity action
D/LocSvc_java(  861): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  861): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  861): getAGpsConnectionInfo connType - 4
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  861): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  861): ignore wifi update if we are not in OPENING or CLOSING
I/NetworkMonitor( 6486): type=WIFI subType= reason=null isConnected=true
I/rmt_storage(  267): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  267): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  267): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  267): 
I/rmt_storage(  267): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
,D/GpsLocationProvider(  861): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NotificationManager( 1937): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/LGEmail ( 6529): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6529): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,D/eas_req ( 6529): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  861): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6566 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6529): JNI_OnLoad()
I/HubEmail( 6529): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/HubEmail( 6529): registerNatives()
I/HubEmail( 6529): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6529): registerNativeMethods()
I/HubEmail( 6529): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6529): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 6529): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 6566): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6566): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6566): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6566): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6566): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6566): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6566): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6566): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  861): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6590 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6566): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6566): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6566): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6566): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6566): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 6566): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/AppUp4:AppBoxCP( 6590): onCreate
,W/AppUp4:DB( 6590):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6590):  setFingerPrint start
I/AppUp4:DB( 6590):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6590):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6590):  SDK version = 0
I/AppUp4:DB( 6590):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 6590): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6590): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6590): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6590): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6590): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6590): onReceive
I/AppUp4:CustModeStarterReceiver( 6590): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 6590): Context : android.app.ReceiverRestrictedContext@94cffc4
D/AppUp4:CustFacade( 6590): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6590): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6590): begin check event
I/AppUp4:CustModeStarterReceiver( 6590): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6590): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6590): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6590): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6590): handleAsyncCustNotification do not startCustService
I/ActivityManager(  861): Killing 6107:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  861): failed to open /acct/uid_10053/pid_6107/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3177): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3177): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3177): networkInfo.isConnected() = false
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ActivityManager(  861): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6612 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6612): Register our PhoneStateListener
,I/ActivityManager(  861): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6629 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
D/MobileConnectivityChangeReceiver( 6612): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6612): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  861): Killing 5723:com.android.vending/u0a36 (adj 15): empty #11
,D/PhoneMonitor( 6612): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6612): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 6612): [parse] Load xml
V/TelephonyAutoProfiling( 6612): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6612): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6612): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,V/DownloadManager( 3246): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/libc-netbsd(  861): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  861): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  861): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  861): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  272): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
,I/System.out(  861): propertyValue:false
D/libc-netbsd(  861): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  861): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  861): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  861): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  272): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
I/System.out(  861): propertyValue:false
I/DSQN    ( 6483): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6483): restart monitoring
D/LGDataListener(  272): argv[0]=dsqncommand
D/LGDataListener(  272): argv[1]=wlan0
D/LGDataListener(  272): argv[2]=1
D/LGDataListener(  272): notifyDSQN DSQN STARTMONITOR wlan0 1
,I/DSQN    ( 6483): dsqn report finish
D/DSQN    (  861): DSQM DsqnNotification wlan0  1
D/DSQN    (  861): start to monitor internet connection
V/WifiInternetCheck(  861): isHttpConnectionAvailable - We got a valid response : 204
,I/art     (  861): Explicit concurrent mark sweep GC freed 79502(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 3.894ms total 199.301ms
,W/libprocessgroup(  861): failed to open /acct/uid_10036/pid_5723/cgroup.procs: No such file or directory
V/DownloadManager( 3246): DownloadService onCreate
,I/NotificationManager( 3246): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3246): in removeSpuriousFiles
V/DownloadManager( 3246): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3246): created cursor android.database.sqlite.SQLiteCursor@4ed6a54 on behalf of 3246
I/DownloadManager( 3246): in trimDatabase
V/DownloadManager( 3246): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3246): created cursor android.database.sqlite.SQLiteCursor@740dfd on behalf of 3246
,W/ResourcesManager( 6629): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,I/ActivityManager(  861): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6655 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
W/ResourcesManager( 6629): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/DownloadManager( 3246): DownloadService onStartCommand
I/CheckinService( 4202): Checkin interval check for package: unspecified last checkin: 1449063112147 min interval config: 0 actual interval: 24178
,V/DownloadManager( 3246): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3246): created cursor android.database.sqlite.SQLiteCursor@7e0d7c0 on behalf of 3246
,I/CheckinService( 4202): Checking schedule, now: 1449063136369 next: 1449063142113
I/CheckinService( 4202): active receiver: disabled
,I/MultiDex( 6629): VM with version 2.1.0 has multidex support
I/MultiDex( 6629): install
I/MultiDex( 6629): VM has multidex support, MultiDex support library is disabled.
,V/DownloadManager( 3246): DownloadService onDestroy
I/ActivityManager(  861): Killing 6357:com.android.settings/1000 (adj 15): empty #11
,W/libprocessgroup(  861): failed to open /acct/uid_1000/pid_6357/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2624): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:32:16
D/UpdateThreadPoolManager( 2624): 2 : This is isUpdating : false
D/WeatherAncestor( 2624): connectivity changed - connection : true
D/Weather_cast( 2624): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2624): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:32:16
D/WeatherService( 2624): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
W/ActivityManager(  861): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2624): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2624): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2624): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
V/JNIHelp ( 6629): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/ChimeraCfgMgr( 4202): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/ChimeraCfgMgr( 4202): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  861): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6686 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityThread( 6629): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6629): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@6c2c6c1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6629): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6629): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 6629): com.google.android.gms: cancel(39789) by com.google.android.gms
V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 6686): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/NativeLibraryUtils( 6629): Install completed successfully. count=13 extracted=0
,I/Babel_SMS( 6686): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6686): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6686): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6686): MmsConfig.loadFromDatabase
E/Babel_SMS( 6686): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6686): MmsConfig.loadFromResources
,E/Babel_SMS( 6686): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6686): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6686): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6686): found sensor: LGE Magnetometer Sensor, handle=10
,D/SensorManager( 6686): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6686): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6686): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6686): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6686): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6686): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6686): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6686): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6686): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6686): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6686): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6686): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6686): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6686): found sensor: Motion Accel, handle=46
I/art     ( 6629): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,I/art     ( 6629): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
W/Settings( 6686): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6686): startup - clean
,I/NotificationManager( 6629): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/art     ( 6686): CheckpointMarkThreadRoots callback created = 0xb042d4c0
,I/art     ( 6686): CheckpointMarkThreadRoots callback created = 0xb042d4a0
,I/Babel   ( 6686): deleted: false for 0
I/ActivityManager(  861): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6723 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 6686): Unsupported mime audio/x-lg-flac
,I/ActivityManager(  861): Killing 5510:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/AudioCapabilities( 6686): Unsupported mime audio/adpcm
W/AudioCapabilities( 6686): Unsupported mime audio/g726
,W/AudioCapabilities( 6686): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6686): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6686): Unsupported mime video/mjpg
W/VideoCapabilities( 6686): Unsupported mime video/theora
W/System.err( 5824): android.os.DeadObjectException
W/System.err( 5824): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5824): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5824): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5824): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5824): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5824): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5824): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5824): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5824): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5824): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5824): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5824): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5824): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5824): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5824): IControl.unregisterCallback error: android.os.DeadObjectException
,W/System.err( 5824): android.os.DeadObjectException
W/System.err( 5824): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5824): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5824): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5824): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5824): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5824): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5824): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5824): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5824): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5824): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5824): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5824): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5824): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5824): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5824): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/AudioCapabilities( 6686): Unsupported mime audio/evrc
,W/AudioCapabilities( 6686): Unsupported mime audio/qcelp
W/VideoCapabilities( 6686): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6686): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6686): Unsupported mime audio/qcelp
W/AudioCapabilities( 6686): Unsupported mime audio/evrc
W/VideoCapabilities( 6686): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6686): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6686): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6686): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6686): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6686): Unrecognized profile 2130706433 for video/avc
W/libprocessgroup(  861): failed to open /acct/uid_10089/pid_5510/cgroup.procs: No such file or directory
,W/ActivityManager(  861): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
V/AlarmManager(  861): ELAPSED_WAKEUP set : Alarm{2e687455 type 2 when 105654 com.google.android.gms} when 105654
I/vclib   ( 6686): onServiceConnected
W/Babel   ( 6686): Attempted to change video mute state without an active call.
,I/NotificationManager( 6686): com.google.android.talk: cancel(10436) by com.google.android.talk
I/ActivityManager(  861): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6741 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd( 6686): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6686): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6686): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6686): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  272): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
I/System.out( 6686): propertyValue:false
,I/Babel   ( 6686): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  861): Killing 6382:com.lge.sync/1000 (adj 15): empty #11
,W/libprocessgroup(  861): failed to open /acct/uid_1000/pid_6382/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 6741): Quickset Services start...
I/UEI.SmartControl( 6741): Manufacture = LGE
,D/UEI.SmartControl( 6741): File observer start...
E/UEI.SmartControl( 6741): IR Port is disabled: false
D/UEI.SmartControl( 6741): Starting file observer...
D/UEI.SmartControl( 6741): Extracting JNI libs...
D/UEI.SmartControl( 6741): --- this system supports 32-bit or 64-bit only
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6723): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6723): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6723): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6723): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6723): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6723):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6723):   adb logcat -s GAv4
,W/GAv4    ( 6723): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/UEI.SmartControl( 6741): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6741): --- Checking lib: libqs_armeabi-v7a.zip
,D/UEI.SmartControl( 6741): --- Extracting JNI libs: libqs_armeabi-v7a.zip
W/GAv4    ( 6723): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 6723): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/UEI.SmartControl( 6741): --- Selecting new region: 2
I/UEI.SmartControl( 6741): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6741): Platform has CIR...
,D/UEI.SmartControl( 6741): NO CIR support, need to check package...
I/UEI.SmartControl( 6741): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6741): QS Service created
E/UEI.SmartControl( 6741): QS start get config
,D/UEI.SmartControl( 6741): Loading JNI Libs...
D/UEI.SmartControl( 6741):  configuring local db...
,I/WebViewFactory( 6723): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/ActivityManager(  861): Process com.google.android.music:main (pid 6486) has died
,I/LibraryLoader( 6723): Time to load native libraries: 1 ms (timestamps 6498-6499)
,I/LibraryLoader( 6723): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6723): Binding Chromium to main looper Looper (main, tid 1) {33e9e231}
I/LibraryLoader( 6723): Expected native library version number "",actual native library version number ""
I/chromium( 6723): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6723): Initializing chromium process, singleProcess=true
W/art     ( 6723): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6723): ApplicationContext is null in ApplicationStatus
I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
D/UEI.SmartControl( 6741):  ---- Has DB8: true
,D/UEI.SmartControl( 6741): QS start statue = true Error code = 0
W/chromium( 6723): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,D/UEI.SmartControl( 6741): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6741): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
E/libEGL  ( 6723): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6723): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6723): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6723): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6723): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6723): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6723): Remote Branch: 
I/Adreno-EGL( 6723): Local Patches: 
I/Adreno-EGL( 6723): Reconstruct Branch: 
D/UEI.SmartControl( 6741): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6741): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6741): IrrcClient ++ 
D/irrcClient( 6741): getIrrcService ++ 
,D/irrcClient( 6741): getIrrcService -- 
D/irrcClient( 6741): IrrcClient -- 
W/irrc_jni( 6741): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6741): Services init done
D/UEI.SmartControl( 6741): QS Service init finished
I/UEI.SmartControl( 6741): Device manager: loading config....
,D/UEI.SmartControl( 6741): QS Service version name: 0.1.73
D/UEI.SmartControl( 6741): QS Service version code: 1073
D/UEI.SmartControl( 6741): Service requested: Control
D/UEI.SmartControl( 6741): Config is loaded...
D/UEI.SmartControl( 6741):  ----- QS SDK is ready!!!
,V/AudioPolicyService(  276): registerClient() client 0xb383bd60, uid 10079
W/AudioManagerAndroid( 6723): Requires BLUETOOTH permission
I/UEI.SmartControl( 6741): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6741): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 6741): Internal service binding...
D/UEI.SmartControl( 6741): -----IControl: 11
D/UEI.SmartControl( 6741): Caller: com.lge.qremote
D/UEI.SmartControl( 6741): ------------ IControl registerCallback...
I/UEI.SmartControl( 6741): Registering callback...
D/UEI.SmartControl( 6741): -----IControl: 19
I/NSApplication( 6723): Starting up...
,D/UEI.SmartControl( 6741): Caller: com.lge.qremote
I/UEI.SmartControl( 6741): Registering Services Ready callback...
I/UEI.SmartControl( 6741): Notify client services are ready...
D/UEI.SmartControl( 6741): -----IControl: 8
D/UEI.SmartControl( 6741): Caller: com.lge.qremote
I/ActivityManager(  861): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6807 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  861): Killing 5824:com.lge.qremote/u0a106 (adj 15): empty #11
W/libprocessgroup(  861): failed to open /acct/uid_10106/pid_5824/cgroup.procs: No such file or directory
,I/ActivityManager(  861): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6829 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  861): Killing 6529:com.lge.email/u0a21 (adj 15): empty #11
,I/art     (  305): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 357us total 27.634ms
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 322us total 24.305ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 315us total 24.372ms
,W/libprocessgroup(  861): failed to open /acct/uid_10021/pid_6529/cgroup.procs: No such file or directory
W/ResourcesManager( 6829): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  861): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6853 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  861): Killing 6566:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/libprocessgroup(  861): failed to open /acct/uid_1000/pid_6566/cgroup.procs: No such file or directory
,I/MusicStore( 6853): Database version: 120
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6853): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/BluetoothAdapterService(687664499)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@4f9c3e1
,I/jxcore-log( 6192): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 6192): 
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6853): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6853): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6853): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6853): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6853): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 6853): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6853): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@31d33620: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6853): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6853): GMSCore installation verified
I/ConfigStore( 6853): Config Database version: 1
,I/MediaRouter( 6853): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6853): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6853): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6853): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  861): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6881 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6853): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6853): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  861): Killing 6590:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/ResourcesManager( 6881): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6881): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6881): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  861): failed to open /acct/uid_10011/pid_6590/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/NotificationManager( 6853): com.google.android.music: cancel(1061) by com.google.android.music
V/AlarmManager(  861): RTC_WAKEUP set : Alarm{3ebc2400 type 0 when 1449063140017 com.google.android.googlequicksearchbox} when 1449063140017
,I/LGEmail ( 6881): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6881): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/art     (  861): Explicit concurrent mark sweep GC freed 17798(906KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.786ms total 137.467ms
,D/eas_req ( 6881): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  861): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6917 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6881): JNI_OnLoad()
I/HubEmail( 6881): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6881): registerNatives()
I/HubEmail( 6881): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6881): registerNativeMethods()
I/HubEmail( 6881): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/art     ( 6881): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 6881): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  861): Killing 6612:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  861): failed to open /acct/uid_10038/pid_6612/cgroup.procs: No such file or directory
D/LGDMClient( 6917): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6917): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6917): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6917): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6917): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6917): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6917): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6917): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  861): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6941 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6917): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6917): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6917): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6917): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6917): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 6917): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  861): Killing 6629:com.google.android.gms:car/u0a6 (adj 15): empty #11
,W/libprocessgroup(  861): failed to open /acct/uid_10006/pid_6629/cgroup.procs: No such file or directory
W/SQLiteConnectionPool( 4202): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/AppUp4:AppBoxCP( 6941): onCreate
,W/AppUp4:DB( 6941):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6941):  setFingerPrint start
I/AppUp4:DB( 6941):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6941):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6941):  SDK version = 0
,I/AppUp4:DB( 6941):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 6941): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6941): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6941): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6941): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6941): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6941): onReceive
I/AppUp4:CustModeStarterReceiver( 6941): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6941): Context : android.app.ReceiverRestrictedContext@94cffc4
D/AppUp4:CustFacade( 6941): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6941): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6941): begin check event
I/AppUp4:CustModeStarterReceiver( 6941): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6941): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6941): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6941): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6941): handleAsyncCustNotification do not startCustService
I/ActivityManager(  861): Killing 6655:com.lge.drmservice/u0a51 (adj 15): empty #11
I/LgeMiscReceiver( 3177): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,W/libprocessgroup(  861): failed to open /acct/uid_10051/pid_6655/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3177): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3177): networkInfo.isConnected() = false
I/ActivityManager(  861): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6965 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/PhoneMonitor( 6965): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6965): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6965): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  861): Killing 6686:com.google.android.talk/u0a61 (adj 15): empty #11
D/PhoneMonitor( 6965): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6965): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6965): [parse] Load xml
V/TelephonyAutoProfiling( 6965): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6965): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6965): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  861): failed to open /acct/uid_10061/pid_6686/cgroup.procs: No such file or directory
V/DownloadManager( 3246): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3246): DownloadService onCreate
I/NotificationManager( 3246): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3246): in removeSpuriousFiles
V/DownloadManager( 3246): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3246): created cursor android.database.sqlite.SQLiteCursor@302db29f on behalf of 3246
I/DownloadManager( 3246): in trimDatabase
V/DownloadManager( 3246): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3246): created cursor android.database.sqlite.SQLiteCursor@35dbafec on behalf of 3246
I/ActivityManager(  861): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6987 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/DownloadManager( 3246): DownloadService onStartCommand
,V/DownloadManager( 3246): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3246): created cursor android.database.sqlite.SQLiteCursor@3e23364a on behalf of 3246
I/CheckinService( 4202): Checkin interval check for package: unspecified last checkin: 1449063112147 min interval config: 0 actual interval: 28982
I/CheckinService( 4202): Checking schedule, now: 1449063141142 next: 1449063142113
I/CheckinService( 4202): active receiver: disabled
V/DownloadManager( 3246): DownloadService onDestroy
,I/ActivityManager(  861): Killing 6723:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,W/libprocessgroup(  861): failed to open /acct/uid_10079/pid_6723/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2624): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:32:21
D/UpdateThreadPoolManager( 2624): 2 : This is isUpdating : false
D/WeatherAncestor( 2624): connectivity changed - connection : true
D/Weather_cast( 2624): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2624): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:32:21
D/WeatherService( 2624): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
W/ActivityManager(  861): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2624): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2624): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2624): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/ChimeraCfgMgr( 4202): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4202): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/ActivityManager(  861): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7007 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 7007): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7007): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7007): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7007): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7007): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7007): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7007): MmsConfig.loadFromResources
E/Babel_SMS( 7007): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7007): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 7007): found sensor: LGE Accelerometer Sensor, handle=0
,D/SensorManager( 7007): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7007): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7007): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7007): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7007): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7007): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7007): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7007): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7007): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7007): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7007): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7007): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7007): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7007): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7007): found sensor: Motion Accel, handle=46
W/Settings( 7007): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7007): startup - clean
I/Babel   ( 7007): deleted: false for 0
,I/art     ( 7007): CheckpointMarkThreadRoots callback created = 0xb042d900
,I/art     ( 7007): CheckpointMarkThreadRoots callback created = 0xb042d8d0
,I/ActivityManager(  861): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7042 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 7007): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 7007): Unsupported mime audio/adpcm
,W/AudioCapabilities( 7007): Unsupported mime audio/g726
W/AudioCapabilities( 7007): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7007): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7007): Unsupported mime video/mjpg
W/VideoCapabilities( 7007): Unsupported mime video/theora
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/AudioCapabilities( 7007): Unsupported mime audio/evrc
,W/AudioCapabilities( 7007): Unsupported mime audio/qcelp
W/VideoCapabilities( 7007): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7007): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7007): Unsupported mime audio/qcelp
W/AudioCapabilities( 7007): Unsupported mime audio/evrc
W/VideoCapabilities( 7007): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7007): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7007): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7007): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7007): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7007): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7007): onServiceConnected
,W/Babel   ( 7007): Attempted to change video mute state without an active call.
D/libc-netbsd( 7007): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7007): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7007): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7007): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  272): App 10061 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
I/System.out( 7007): propertyValue:false
I/NotificationManager( 7007): com.google.android.talk: cancel(10436) by com.google.android.talk
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7042): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/GAv4    ( 7042): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7042):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7042):   adb logcat -s GAv4
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7042): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7042): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
W/GAv4    ( 7042): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7042): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/Babel   ( 7007): connection state changed from UNKNOWN to CONNECTED
I/ActivityManager(  861): Killing 6741:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/GAv4    ( 7042): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7042): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/libprocessgroup(  861): failed to open /acct/uid_10089/pid_6741/cgroup.procs: No such file or directory
,I/WebViewFactory( 7042): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7042): Time to load native libraries: 2 ms (timestamps 977-979)
I/LibraryLoader( 7042): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7042): Binding Chromium to main looper Looper (main, tid 1) {33e9e231}
I/LibraryLoader( 7042): Expected native library version number "",actual native library version number ""
I/chromium( 7042): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7042): Initializing chromium process, singleProcess=true
,W/art     ( 7042): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7042): ApplicationContext is null in ApplicationStatus
W/chromium( 7042): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7042): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7042): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7042): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7042): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7042): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7042): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7042): Remote Branch: 
I/Adreno-EGL( 7042): Local Patches: 
I/Adreno-EGL( 7042): Reconstruct Branch: 
V/AudioPolicyService(  276): registerClient() client 0xb4027140, uid 10079
,W/AudioManagerAndroid( 7042): Requires BLUETOOTH permission
I/NSApplication( 7042): Starting up...
V/MusicLeanback( 6853): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/LGDMClient( 6917): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6917): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6917): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6917): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
I/NetworkStateForAutoUpdateMonitor( 6941): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6941): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6941): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6941): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 6941): onReceive
I/AppUp4:CustModeStarterReceiver( 6941): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6941): Context : android.app.ReceiverRestrictedContext@94cffc4
W/Settings( 6881): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/AppUp4:CustFacade( 6941): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6941): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6941): begin check event
I/AppUp4:CustModeStarterReceiver( 6941): Event For GoodConnectivity, noConnectivity : false, but skip! 
I/LgeMiscReceiver( 3177): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3177): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3177): networkInfo.isConnected() = true
D/LGDMClient( 6917): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6917): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,D/PhoneState( 3177): setPdpRejectCasuse : false
D/LGDMClient( 6917): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6917): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/MobileConnectivityChangeReceiver( 6965): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6965): onReceive CONNECTIVITY_CHANGE networkType=1
V/DownloadManager( 3246): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3246): DownloadService onCreate
W/ContextImpl( 6917): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,D/WeatherAncestor( 2624): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:32:22
E/LGDMClient( 6917): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6917): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6917): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6917): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6917): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/NotificationManager( 3246): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,D/UpdateThreadPoolManager( 2624): 2 : This is isUpdating : false
D/WeatherAncestor( 2624): connectivity changed - connection : true
D/Weather_cast( 2624): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2624): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:32:22
D/WeatherService( 2624): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DownloadManager( 3246): in removeSpuriousFiles
V/DownloadManager( 3246): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
W/ActivityManager(  861): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2624): 2 : Utils getTopActivity com.lge.launcher2 / true
V/DownloadManager( 3246): created cursor android.database.sqlite.SQLiteCursor@2dc9ded8 on behalf of 3246
D/WeatherService( 2624): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2624): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
V/DownloadManager( 3246): DownloadService onStartCommand
V/DownloadManager( 3246): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 3246): in trimDatabase
V/DownloadManager( 3246): created cursor android.database.sqlite.SQLiteCursor@15dd5697 on behalf of 3246
V/DownloadManager( 3246): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3246): created cursor android.database.sqlite.SQLiteCursor@f6a1084 on behalf of 3246
,D/ChimeraCfgMgr( 4202): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/ChimeraCfgMgr( 4202): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/DownloadManager( 3246): DownloadService onDestroy
,I/art     ( 6829): CheckpointMarkThreadRoots callback created = 0xb042d500
V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 6829): CheckpointMarkThreadRoots callback created = 0xb042d4d0
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ChimeraCfgMgr( 4202): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/GCM     ( 1962): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WearableService( 1731): callingUid 10006, callindPid: 1731
V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/MDM     ( 1731): [82] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/GCM     ( 1962): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/LocationInitializer( 4202): Restart initialization of location
D/AuthorizationBluetoothService( 1962): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GmsCoreStatsServiceLauncher( 4202): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/NotificationManager( 1962): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1731): No location to return for getLastLocation()
W/FusedLocationProvider( 1962): location=null
D/libc-netbsd( 1962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  272): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  861): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7138 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,D/libc-netbsd(  272): res_queryN name = xxxxx succeed
,I/System.out( 1962): propertyValue:false
,W/ResourcesManager( 7138): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/libc-netbsd( 1962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,D/BluetoothManagerService(  861): Message: 20
D/BluetoothManagerService(  861): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cecb4ae:true
,D/BluetoothAdapterService(687664499)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@4f9c3e1
D/BluetoothAdapterService(687664499)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@4f9c3e1
,I/ActivityManager(  861): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7162 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/LGMDMManager( 7138): Create singleton instance
,I/art     ( 1962): Explicit concurrent mark sweep GC freed 12168(990KB) AllocSpace objects, 25(400KB) LOS objects, 40% free, 11MB/19MB, paused 1.359ms total 60.867ms
,I/AudioManager( 7138): getMode name:com.lge.qremote
,D/UEI.SmartControl( 7162): Quickset Services start...
,I/UEI.SmartControl( 7162): Manufacture = LGE
D/UEI.SmartControl( 7162): File observer start...
E/UEI.SmartControl( 7162): IR Port is disabled: false
D/UEI.SmartControl( 7162): Starting file observer...
D/UEI.SmartControl( 7162): Extracting JNI libs...
D/UEI.SmartControl( 7162): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7162): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7162): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7162): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 7162): --- Selecting new region: 2
,I/UEI.SmartControl( 7162): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7162): Platform has CIR...
D/UEI.SmartControl( 7162): NO CIR support, need to check package...
I/UEI.SmartControl( 7162): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7162): QS Service created
I/art     (  861): Explicit concurrent mark sweep GC freed 18088(781KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.595ms total 170.411ms
,D/ChimeraCfgMgr( 4202): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4202): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/GCM     ( 1962): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,E/UEI.SmartControl( 7162): QS start get config
V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AudioManager( 7138): getMode name:com.lge.qremote
,D/UEI.SmartControl( 7162): Loading JNI Libs...
D/UEI.SmartControl( 7162):  configuring local db...
D/UEI.SmartControl( 7162):  ---- Has DB8: true
,D/UEI.SmartControl( 7162): QS start statue = true Error code = 0
D/UEI.SmartControl( 7162): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7162): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7162): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7162): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7162): IrrcClient ++ 
D/irrcClient( 7162): getIrrcService ++ 
D/irrcClient( 7162): getIrrcService -- 
D/irrcClient( 7162): IrrcClient -- 
W/irrc_jni( 7162): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7162): Services init done
,I/UEI.SmartControl( 7162): Device manager: loading config....
D/UEI.SmartControl( 7162): QS Service init finished
D/UEI.SmartControl( 7162): QS Service version name: 0.1.73
D/UEI.SmartControl( 7162): QS Service version code: 1073
D/UEI.SmartControl( 7162): Config is loaded...
D/UEI.SmartControl( 7162): Service requested: Control
D/UEI.SmartControl( 7162): -----IControl: 11
,D/UEI.SmartControl( 7162): Caller: com.lge.qremote
D/UEI.SmartControl( 7162): ------------ IControl registerCallback...
I/UEI.SmartControl( 7162): Registering callback...
D/UEI.SmartControl( 7162): Internal service binding...
D/UEI.SmartControl( 7162): -----IControl: 19
D/UEI.SmartControl( 7162): Caller: com.lge.qremote
I/UEI.SmartControl( 7162): Registering Services Ready callback...
I/UEI.SmartControl( 7162): Notify client services are ready...
D/UEI.SmartControl( 7162): -----IControl: 8
D/UEI.SmartControl( 7162): Caller: com.lge.qremote
,I/AudioManager( 7138): getMode name:com.lge.qremote
I/ActivityManager(  861): Killing 6881:com.lge.email/u0a21 (adj 15): empty #11
,D/UEI.SmartControl( 7162):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7162): Notify AllClients services are ready: 0
I/ActivityManager(  861): Killing 6853:com.google.android.music:main/u0a81 (adj 15): empty #12
,W/libprocessgroup(  861): failed to open /acct/uid_10021/pid_6881/cgroup.procs: No such file or directory
,W/libprocessgroup(  861): failed to open /acct/uid_10081/pid_6853/cgroup.procs: No such file or directory
I/AudioManager( 7138): getMode name:com.lge.qremote
I/AudioManager( 7138): getMode name:com.lge.qremote
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,V/AlarmManager(  861): RTC_WAKEUP set : Alarm{129d17d1 type 0 when 1449063142113 com.google.android.gms} when 1449063142113
,I/CheckinService( 4202): Checkin interval check for package: unspecified last checkin: 1449063112147 min interval config: 0 actual interval: 33940
,I/CheckinService( 4202): Checking schedule, now: 1449063146118 next: 1449063142113
I/CheckinService( 4202): active receiver: enabled
,W/ContextImpl( 3643): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/CheckinService( 4202): Preparing to send checkin request
I/EventLogService( 4202): Accumulating logs since 1449063104826
,I/ActivityManager(  861): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7221 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  861): RTC_WAKEUP set : Alarm{1e8a600d type 0 when 1449063146235 com.android.vending} when 1449063146235
I/CheckinRequestBuilder( 4202): Checkin reason type: 8 attempt count: 1
I/art     (  305): Explicit concurrent mark sweep GC freed 705(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 24.922ms
,E/ActivityThread( 4202): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  305): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 25.229ms
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 21.183ms
,I/ActivityManager(  861): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7250 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/Finsky  ( 7221): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/ResourcesManager( 7250): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7250): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7250): VM with version 2.1.0 has multidex support
I/MultiDex( 7250): install
I/MultiDex( 7250): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7250): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 7250): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7250): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@6c2c6c1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7250): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 7250): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7250): com.google.android.gms: cancel(39789) by com.google.android.gms
E/MDM     ( 1731): [88] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 7221): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 115157108710; DSPS: 3871410; Offset : -2989843365
,D/GCM     ( 1962): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1962): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 4202): Restart initialization of location
I/art     ( 7250): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
I/art     ( 7250): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1962): com.google.android.gms: cancel(0) by com.google.android.gms
W/Settings( 7221): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7221): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7221): com.android.vending: cancel(-1050172287) by com.android.vending
,W/GCoreFlp( 1731): No location to return for getLastLocation()
W/FusedLocationProvider( 1962): location=null
,D/Ads     ( 7221): Skipping gmscore version check
,D/Finsky  ( 7221): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7221): [1] Libraries$2.run: Finished loading 1 libraries.
V/DownloadManager( 3246): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3246): created cursor android.database.sqlite.SQLiteCursor@2fd444a2 on behalf of 7221
D/NativeLibraryUtils( 7250): Install completed successfully. count=13 extracted=0
,D/Finsky  ( 7221): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/GmsCoreStatsServiceLauncher( 4202): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/WVCdm   (  276): Instantiating CDM.
,I/WVCdm   (  276): CdmEngine::OpenSession
I/WVCdm   (  276): Level3 Library Dec 11 2014 16:13:16
D/Finsky  ( 7221): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/WVCdm   (  276): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  276): Properties::GetOEMCryptoPath: null. applies level3
,W/WVCdm   (  276): L1 library not specified. Falling Back to L3
D/Finsky  ( 7221): [900] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 7221): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  861): Killing 6941:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/WVCdm   (  276): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  276): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  276): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  276): CdmEngine::GenerateKeyRequest
D/WVCdm   (  276): PrepareKeyRequest: nonce=3033194967
I/art     ( 7250): Background sticky concurrent mark sweep GC freed 25444(1505KB) AllocSpace objects, 2(32KB) LOS objects, 8% free, 10MB/11MB, paused 13.137ms total 64.067ms
,W/libprocessgroup(  861): failed to open /acct/uid_10011/pid_6941/cgroup.procs: No such file or directory
I/dex2oat ( 7297): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7297): dex2oat took 92.272ms (threads: 4)
,I/art     ( 7250): CheckpointMarkThreadRoots callback created = 0xb05400b0
I/Adreno-EGL( 7250): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7250): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7250): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7250): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7250): Remote Branch: 
I/Adreno-EGL( 7250): Local Patches: 
I/Adreno-EGL( 7250): Reconstruct Branch: 
,I/art     ( 7250): CheckpointMarkThreadRoots callback created = 0xb05400a0
I/Adreno-EGL( 7250): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7250): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7250): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7250): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7250): Remote Branch: 
I/Adreno-EGL( 7250): Local Patches: 
I/Adreno-EGL( 7250): Reconstruct Branch: 
,I/ActivityManager(  861): Process com.google.android.apps.magazines (pid 7042) has died
,I/WVCdm   (  276): CdmEngine::OpenSession
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/UEI.SmartControl( 7162): Internal timer expired: 1
,I/WVCdm   (  276): CdmEngine::CloseSession
,I/WVCdm   (  276): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  276): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  276): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  276): CdmEngine::GenerateKeyRequest
D/WVCdm   (  276): PrepareKeyRequest: nonce=1898582328
I/MusicWidget( 2502): mDelayedStopHandler : unbind
,I/MusicBrowser( 2645): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
I/MusicBrowser( 2645): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
,I/MusicBrowser( 2645): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2645): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2645): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2645): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2645): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2645): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  861):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@186dbd1dcom.lge.music.MediaPlaybackService$6@37c68b92
,D/MusicBrowser( 2645): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2645): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2645): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2645): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2645): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@1dfc5430
,I/MusicBrowser( 2645): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2645): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2645): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2645): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2645): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2645): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2645): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2645): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2645): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2645): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2645): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2645): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2645): [MediaPlaybackService.java:6706:stop()] oooooo 
,I/MediaPlayer[Native]( 2645): reset
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/MediaPlayer[Native]( 2645): setListener
V/MediaPlayer[Native]( 2645): disconnect
V/MediaPlayer[Native]( 2645): destructor
V/AudioFlinger(  276): releasing 18 from 2645 for -1
V/AudioFlinger(  276):  decremented refcount to 0
V/AudioFlinger(  276): purging stale effects
V/MediaPlayer[Native]( 2645): disconnect
D/MusicBrowser( 2645): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2645): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2645): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2645): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2645): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2645): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2645): [SmartShareManagerClient] unregisterListener: 50076003
W/SmartShareClient( 2645): [SmartShareManagerClient] unregisterListener invalid listener: 50076003
I/SmartShareClient( 2645): [SmartShareManagerClient] terminate service: 2645/MediaPlaybackService/369326678
,E/HomeCloudIF( 2645): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2645): [SmartShareManagerClient] unbindService context:android.app.Application@1aa52960
V/CloudHub( 2645): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2645): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2645): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2645): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2645): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/CloudHub( 2645): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29995
I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,V/AlarmManager(  861): ELAPSED_WAKEUP set : Alarm{773e972 type 2 when 119246 com.google.android.gms} when 119246
,I/WVCdm   (  276): CdmEngine::CloseSession
,I/WVCdm   (  276): L3 Terminate.
I/Adreno-EGL( 7250): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7250): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7250): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7250): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7250): Remote Branch: 
I/Adreno-EGL( 7250): Local Patches: 
I/Adreno-EGL( 7250): Reconstruct Branch: 
,I/CheckinRequestBuilder( 4202): Classify the device as Phone.
,D/libc-netbsd( 4202): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4202): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4202): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4202): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  272): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
I/System.out( 4202): propertyValue:false
,D/libc-netbsd( 4202): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4202): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4202): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4202): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4202): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4202): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 4202): Sending checkin request (9739 bytes)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/CheckinRequestBuilder( 4202): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4202): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinRequestBuilder( 4202): Classify the device as Phone.
,I/CheckinTask( 4202): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4202): Checking schedule, now: 1449063152574 next: 1449590401571
I/CheckinService( 4202): active receiver: disabled
,D/CheckinService( 4202): Recording last checkin time for package unspecified as 1449063152599
I/ActivityManager(  861): Killing 6987:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  861): failed to open /acct/uid_10051/pid_6987/cgroup.procs: No such file or directory
,V/SetupWizard( 6965): Connected to Gservices successfully
D/ChimeraCfgMgr( 4202): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/ChimeraCfgMgr( 4202): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/GCM     ( 1962): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ActivityManager(  861): Killing 6917:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  861): failed to open /acct/uid_1000/pid_6917/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]QPairHandler( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1830): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader(  861): Reconfiguring input devices.  changes=0x00000010
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
,W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1374): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/ActivityManager(  861): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7361 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/administrator(  861): Handling package changes for user 0
I/NotificationManager( 7007): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 7007): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7007): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 7007): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/AppUp4:AppBoxCP( 7361): onCreate
,W/AppUp4:DB( 7361):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7361):  setFingerPrint start
I/AppUp4:DB( 7361):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 7361):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7361):  SDK version = 0
I/AppUp4:DB( 7361):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7361): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7361): onReceive
I/AppUp4:CustModeStarterReceiver( 7361): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 7361): Context : android.app.ReceiverRestrictedContext@3949dc71
,D/AppUp4:CustFacade( 7361): isCustomizationCompleted : false
,W/System  ( 7007): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7007): Installed default security provider GmsCore_OpenSSL
D/AppUp4:CustFacade( 7361): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7361): begin check event
I/AppUp4:CustModeStarterReceiver( 7361): Event For Nothing, skip.
,D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
,I/NotificationService(  861): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  861): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  861): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  861): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/ResourcesManager(  861): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     (  861): Explicit concurrent mark sweep GC freed 32713(1559KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 2.101ms total 188.505ms
,I/ActivityManager(  861): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7385 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,V/BackupManagerService(  861): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  861): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@323b2ddb
,W/ResourceType(  861): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,W/ResourcesManager( 7385): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7385): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
V/GmsNetworkLocationProvi( 1731): DISABLE
,I/GCoreNlp( 1731): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/AppConfig( 7385): Total System Memory = 906309632
,D/LocationProviderProxy(  861): applying state to connected service
,I/GalleryUtils( 7385): Application Heap = 96 MB
I/AppConfig( 7385): App Tier : NOT_DEF
D/SystemHelper( 7385): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  861): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7405 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ResourcesManager( 7405): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7405): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7405): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7405): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7405): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  861): Process com.android.vending (pid 7221) has died
,I/SystemConfig( 7405): BUILD Country: EU
I/SystemConfig( 7405): BUILD Operator: OPEN
I/ActivityManager(  861): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7430 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 7405): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7405): existFile = false
,I/SystemConfig( 7405): canReadFile = false
I/SystemConfig( 7405): systemFeature RCS result false
D/SystemConfig( 7405): refreshRcsSupport() :false
,I/LockScreenSettings( 7430): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7430): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7430): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7430): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7430): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
,D/LockScreenSettings( 7430): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  861): Killing 6807:com.android.chrome/u0a48 (adj 15): empty #11
W/libprocessgroup(  861): failed to open /acct/uid_10048/pid_6807/cgroup.procs: No such file or directory
,D/PackageBroadcastService( 4202): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 4202): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 4202): updateResources: need to parse f{com.google.android.gms}
,I/UpdateIcingCorporaServi( 1937): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  861): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7453 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1937): UpdateCorporaTask done [took 102 ms] updated apps [took 102 ms] 
,D/Finsky  ( 7453): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7453): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7453): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7453): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7453): com.android.vending: cancel(-1050172287) by com.android.vending
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
D/Finsky  ( 7453): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7453): [1] Libraries$2.run: Finished loading 1 libraries.
,V/DownloadManager( 3246): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,D/Ads     ( 7453): Skipping gmscore version check
V/DownloadManager( 3246): created cursor android.database.sqlite.SQLiteCursor@196c533 on behalf of 7453
I/ActivityManager(  861): Killing 7162:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 7138): android.os.DeadObjectException
W/System.err( 7138): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7138): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7138): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7138): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7138): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7138): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7138): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7138): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7138): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7138): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7138): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7138): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7138): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7138): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7138): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7138): android.os.DeadObjectException
W/System.err( 7138): 	at android.os.BinderProxy.transactNative(Native Method)
,W/System.err( 7138): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7138): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7138): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7138): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7138): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7138): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7138): 	at android.os.Handler.dispatchMessage(Handler.java:95)
,W/System.err( 7138): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7138): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7138): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7138): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7138): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7138): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7138): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  861): failed to open /acct/uid_10089/pid_7162/cgroup.procs: No such file or directory
W/ActivityManager(  861): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,D/Finsky  ( 7453): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  861): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7509 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Finsky  ( 7453): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/UEI.SmartControl( 7509): Quickset Services start...
,I/UEI.SmartControl( 7509): Manufacture = LGE
,D/UEI.SmartControl( 7509): File observer start...
E/UEI.SmartControl( 7509): IR Port is disabled: false
D/UEI.SmartControl( 7509): Starting file observer...
D/UEI.SmartControl( 7509): Extracting JNI libs...
D/UEI.SmartControl( 7509): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7509): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7509): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7509): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 7509): --- Selecting new region: 2
,I/UEI.SmartControl( 7509): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7509): Platform has CIR...
D/UEI.SmartControl( 7509): NO CIR support, need to check package...
I/UEI.SmartControl( 7509): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7509): QS Service created
E/UEI.SmartControl( 7509): QS start get config
,D/UEI.SmartControl( 7509): Loading JNI Libs...
,D/UEI.SmartControl( 7509):  configuring local db...
D/charger_monitor(  484): init target 500000
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
,I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
,W/Settings(  861): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
W/Settings(  861): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  861): battery changed pluggedType: 2
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 292
D/charger_monitor(  484): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 292, mChargingStatus=5, mChargingStop=false
,I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
,D/UEI.SmartControl( 7509):  ---- Has DB8: true
,D/UEI.SmartControl( 7509): QS start statue = true Error code = 0
D/UEI.SmartControl( 7509): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7509): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7509): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7509): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7509): IrrcClient ++ 
D/irrcClient( 7509): getIrrcService ++ 
D/irrcClient( 7509): getIrrcService -- 
D/irrcClient( 7509): IrrcClient -- 
W/irrc_jni( 7509): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7509): Services init done
,I/UEI.SmartControl( 7509): Device manager: loading config....
D/UEI.SmartControl( 7509): Config is loaded...
D/UEI.SmartControl( 7509): QS Service init finished
,D/UEI.SmartControl( 7509): QS Service version name: 0.1.73
D/UEI.SmartControl( 7509): QS Service version code: 1073
D/UEI.SmartControl( 7509): Service requested: Control
I/ActivityManager(  861): Killing 7138:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 7509): -----IControl: 11
D/UEI.SmartControl( 7509): Caller: com.lge.qremote
D/UEI.SmartControl( 7509): ------------ IControl registerCallback...
I/UEI.SmartControl( 7509): Registering callback...
,D/UEI.SmartControl( 7509):  ----- QS SDK is ready!!!
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/UEI.SmartControl( 7509): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7509): Internal service binding...
W/libprocessgroup(  861): failed to open /acct/uid_10106/pid_7138/cgroup.procs: No such file or directory
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/CloudHub( 2645): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19965
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  861): Killing 2645:com.lge.music/u0a28 (adj 15): empty #11
,V/AudioFlinger(  276): 2645 died, releasing its sessions
V/AudioFlinger(  276):  pid 1750 @ 0
V/AudioFlinger(  276):  pid 3177 @ 1
V/AudioFlinger(  276):  pid 3177 @ 2
,W/libprocessgroup(  861): failed to open /acct/uid_10028/pid_2645/cgroup.procs: No such file or directory
,I/ActivityManager(  861): Killing 6965:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  861): failed to open /acct/uid_10038/pid_6965/cgroup.procs: No such file or directory
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,D/UEI.SmartControl( 7509): Internal timer expired: 1
,D/UEI.SmartControl( 7509): Service.onUnbind: IControl
D/UEI.SmartControl( 7509): Service.onDestroy
W/System.err( 7509): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@28fced73
W/System.err( 7509): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 7509): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 7509): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 7509): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 7509): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 7509): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2983)
W/System.err( 7509): 	at android.app.ActivityThread.access$2200(ActivityThread.java:155)
W/System.err( 7509): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1426)
W/System.err( 7509): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7509): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7509): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7509): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7509): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7509): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7509): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7509): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@28fced73
D/UEI.SmartControl( 7509): Shutdown IRRCPlayer... 
,W/irrc_jni( 7509): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 7509): ~IrrcClient ++ 
D/irrcClient( 7509): ~IrrcClient -- 
W/irrc_jni( 7509): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 7509): Blaster closed
D/UEI.SmartControl( 7509): Blaster closed
,D/UEI.SmartControl( 7509): Shut down QS...
D/UEI.SmartControl( 7509): Stopped file observer...
I/UEI.SmartControl( 7509): QS lib stop result = true
D/UEI.SmartControl( 7509): QS shutdown complete
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 135158064327; DSPS: 4526801; Offset : -2989833742
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/PowerManagerServiceEx(  861): acquireWakeLockInternal: lock=11952745, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=861
,D/WeatherService( 2624): 2 : TimeTick Intent has been received, Time(hour:min:sec) 14:33:0
,D/WeatherService( 2624): 2 : TimeTick Intent And Screen On
D/WeatherService( 2624): 2 : SDK version : 21
W/ActivityManager(  861): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2624): 2 : Utils getTopActivity com.lge.launcher2 / true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/WeatherService( 2624): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2624): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2624): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2624): 2 : This is isUpdating : false
D/WeatherService( 2624): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2624): 2 : buildUpdate, appWidgetId: 2
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
D/WeatherTheme( 2624): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2624): 2 : Fixed theme : optimus
D/WeatherReflect( 2624): 2 : Map key string is -2
,I/[SystemUI]Clock( 1374): called onTimeUpdated()
I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/lim     ( 2624): 2 : time = 14:33
,I/WeatherReflect( 2624): Model Name : LG-D722
D/WeatherTheme( 2624): 2 : Different view - status_min_formatted : 32 != 33
D/WeatherTheme( 2624): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2624): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2624): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2624): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2624): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2624): currentPackage=com.lge.sizechangable.weather.theme.optimus
,D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
,D/Weather4x2_optimus( 2624): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2624): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2624): forecast size is 0
D/Theme   ( 2624): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2624): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2624): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2624): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2624): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2624): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2624): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2624): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2624): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2624): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2624): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2624): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2624): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2624): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2624): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2624): url is : null
D/Theme   ( 2624): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2624): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2624): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2624): 2 : update view, appWidgetId: 2
,D/WeatherService( 2624): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 14:33:0
D/PowerManagerServiceEx(  861): releaseWakeLockInternal: lock=11952745 [*alarm*], flags=0x0
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/AlarmManager(  861): ELAPSED_WAKEUP set : Alarm{25da14ee type 2 when 151067 com.google.android.gms} when 151067
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1962): Vacuum at: now=1449063182922 tag=VacuumService
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/art     ( 1962): Explicit concurrent mark sweep GC freed 26792(1551KB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 11MB/19MB, paused 1.457ms total 83.016ms
,D/GetConfigurationSnapshotOperation( 1962): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1962): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1962): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 1962): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/libc-netbsd( 1962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  272): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
I/System.out( 1962): propertyValue:false
I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,D/libc-netbsd( 1962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/UdcCache:FPQuery( 4202): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1962): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/GetCommittedConfigurationOperation( 1962): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/PowerManagerService(  861): ALS enabled for SRE
,D/PowerManagerServiceEx(  861): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (32055 ms ago)
D/qdlights(  861): set_light_backlight: 253
,D/qdlights(  861): set_light_backlight: 249
D/qdlights(  861): set_light_backlight: 246
,D/qdlights(  861): set_light_backlight: 243
,D/qdlights(  861): set_light_backlight: 239
,D/qdlights(  861): set_light_backlight: 236
,D/qdlights(  861): set_light_backlight: 233
,D/qdlights(  861): set_light_backlight: 229
,D/qdlights(  861): set_light_backlight: 226
,D/qdlights(  861): set_light_backlight: 223
,D/qdlights(  861): set_light_backlight: 219
,D/qdlights(  861): set_light_backlight: 216
,D/qdlights(  861): set_light_backlight: 213
,D/qdlights(  861): set_light_backlight: 209
,D/qdlights(  861): set_light_backlight: 206
,D/qdlights(  861): set_light_backlight: 203
,D/qdlights(  861): set_light_backlight: 199
,D/qdlights(  861): set_light_backlight: 196
,D/qdlights(  861): set_light_backlight: 193
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/qdlights(  861): set_light_backlight: 189
,D/qdlights(  861): set_light_backlight: 186
,D/qdlights(  861): set_light_backlight: 183
,D/qdlights(  861): set_light_backlight: 179
,D/qdlights(  861): set_light_backlight: 176
,D/qdlights(  861): set_light_backlight: 173
,W/Uploader( 1962):  no longer exists, so no auth token.
D/GetCommittedConfigurationOperation( 1962): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/qdlights(  861): set_light_backlight: 169
D/qdlights(  861): set_light_backlight: 166
,D/qdlights(  861): set_light_backlight: 163
,D/qdlights(  861): set_light_backlight: 159
,D/qdlights(  861): set_light_backlight: 156
,D/qdlights(  861): set_light_backlight: 153
,D/qdlights(  861): set_light_backlight: 149
,D/qdlights(  861): set_light_backlight: 146
D/GetCommittedConfigurationOperation( 1962): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/qdlights(  861): set_light_backlight: 143
D/qdlights(  861): set_light_backlight: 139
,D/qdlights(  861): set_light_backlight: 136
,D/qdlights(  861): set_light_backlight: 133
,D/qdlights(  861): set_light_backlight: 129
,D/qdlights(  861): set_light_backlight: 126
,D/qdlights(  861): set_light_backlight: 123
,D/qdlights(  861): set_light_backlight: 119
,D/qdlights(  861): set_light_backlight: 116
,D/qdlights(  861): set_light_backlight: 113
,D/qdlights(  861): set_light_backlight: 109
,D/qdlights(  861): set_light_backlight: 106
,D/qdlights(  861): set_light_backlight: 103
,D/qdlights(  861): set_light_backlight: 99
,D/qdlights(  861): set_light_backlight: 96
,D/qdlights(  861): set_light_backlight: 93
,D/qdlights(  861): set_light_backlight: 89
D/GetCommittedConfigurationOperation( 1962): no corresponding serverToken: com.google.android.gms.playlog.uploader
D/qdlights(  861): set_light_backlight: 86
,D/qdlights(  861): set_light_backlight: 83
,D/qdlights(  861): set_light_backlight: 79
,D/qdlights(  861): set_light_backlight: 76
,D/qdlights(  861): set_light_backlight: 73
,D/qdlights(  861): set_light_backlight: 69
,D/qdlights(  861): set_light_backlight: 66
,D/qdlights(  861): set_light_backlight: 63
,D/GetCommittedConfigurationOperation( 1962): no corresponding serverToken: com.google.android.gms.playlog.uploader
D/qdlights(  861): set_light_backlight: 59
,D/qdlights(  861): set_light_backlight: 56
,D/qdlights(  861): set_light_backlight: 53
,D/qdlights(  861): set_light_backlight: 49
,D/qdlights(  861): set_light_backlight: 46
,D/qdlights(  861): set_light_backlight: 43
,D/qdlights(  861): set_light_backlight: 39
,D/qdlights(  861): set_light_backlight: 36
,D/qdlights(  861): set_light_backlight: 33
,D/qdlights(  861): set_light_backlight: 29
,D/qdlights(  861): set_light_backlight: 26
,D/GetCommittedConfigurationOperation( 1962): no corresponding serverToken: com.google.android.gms.playlog.uploader
D/qdlights(  861): set_light_backlight: 23
,D/qdlights(  861): set_light_backlight: 19
,D/qdlights(  861): set_light_backlight: 16
,D/qdlights(  861): set_light_backlight: 13
,D/qdlights(  861): set_light_backlight: 10
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 155158816820; DSPS: 5182186; Offset : -2989843719
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/PowerManagerService(  861): ALS enabled for SRE
D/PowerManagerServiceEx(  861): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (39053 ms ago)
I/PowerManagerService(  861): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  861): ALS enabled for SRE
D/PowerManagerServiceEx(  861): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (39068 ms ago)
,W/ContextImpl(  861): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  861): Sleeping (uid 1000)...
D/LPWGController(  861): [updateScreenState] screen on = false
,D/LPWGController(  861): disable proximity sensor
D/LPWGController(  861): enable proximity sensor
,I/SensorManager(  861): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@274b0f6f] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  861): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  861): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  861): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  861): activate: handle is 48, enable
,V/sensors_hal_Ctx(  861): activate sensors is 1400000000000
D/sensors_hal_Thresh(  861): enable: handle=48
I/sensors_hal_SAM(  861): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  861): waitForResponse: timeout=1000
V/sensors_hal_SAM(  861): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  861): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  861): enable: Received response: 0
D/PowerManagerServiceEx(  861): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (39132 ms ago)
I/Adreno-EGL(  861): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  861): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  861): Build Date: 03/02/15 Mon
I/Adreno-EGL(  861): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  861): Remote Branch: 
I/Adreno-EGL(  861): Local Patches: 
I/Adreno-EGL(  861): Reconstruct Branch: 
,D/PermissionCache(  247): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (149 us)
,I/Sensors (  414): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  861): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  861): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  861): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  861): processInd: handle 48, count=1
V/sensors_hal_Thresh(  861): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  861): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  861): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  861): poll: count: 256
I/sensors_hal_Ctx(  861): poll: released wakelock sensor_ind
D/sensors_hal_Util(  861): waitForResponse: timeout=0
D/LPWGController(  861): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  861): current mode = 1  value = 1 1
I/LPWGController(  861): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/LPWGController(  861): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  861): set_light_backlight: 0
,I/SensorManager(  861): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
I/sensors_hal_Ctx(  861): activate: handle is 46, disable
,V/sensors_hal_Ctx(  861): activate sensors is 1000000000000
,D/sensors_hal_LP2(  861): enable: handle=46
D/sensors_hal_LP2(  861): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  861): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  247): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  247): hwc_blank: Blanking display: 0
I/DisplayManagerService(  861): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  861): Display changed displayId=0
,V/sensors_hal_SAM(  861): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  861): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1750): Display #0 changed.
,D/qdhwcomposer(  247): hwc_blank: Done blanking display: 0
D/SurfaceControl(  861): Excessive delay in setPowerMode(): 196ms
I/qdhwcomposer(  247): handle_blank_event: dpy:0 panel power state: 0
,I/QCOM PowerHAL(  861): Got set_interactive hint
D/KeyguardViewMediator( 1374): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1334): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1374): notifyScreenOffLocked
D/SmartCoverViewMediator( 1334): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1334): handleNotifyScreenOFF
D/KeyguardViewMediator( 1374): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1374): handleNotifyScreenOff
D/WifiServerServiceExt(  861): sendKtScanInterval  mRtspPlay : false
,I/WifiServerServiceExt(  861): set CMD_KT_SCAN_INTERVAL
,D/ScreenTurnOffBySensor( 1374): unregisterProximitySensor
,V/AudioFlinger(  276): setParameters(): io 0, keyvalue screen_state=on, calling pid 861
D/audio_hw_primary(  276): adev_set_parameters: enter: screen_state=on
V/voice   (  276): voice_set_parameters: enter: screen_state=on
V/compress_voip(  276): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  276): voice_extn_compress_voip_set_parameters: exit
V/voice   (  276): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  276): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  276): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  276): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  276): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  276): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  276): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  276): adev_set_parameters: exit with code(0)
,D/StatusBarWindowView( 1374): onScreenTurnedOff why = 3
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
,D/GpsLocationProvider(  861): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1830): |CORE| sendScreenState: state:true
,I/LEDService( 1803): getCurrentHighestLGLedRecord() start. size = 1
,D/LNfcService( 1786): action : android.intent.action.SCREEN_ON
D/LEDService( 1803): stopPatternFlashing()
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
I/Cliptray Service( 1803): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/Cliptray Service( 1803): lockStatus = 0
I/LEDService( 1803): getCurrentHighestLGLedRecord : size = 1
,D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
I/LEDService( 1803): updateLightsLocked : turn off led
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1803): RESTART MSG
D/NfcServiceNXP( 1786): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1786): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
,D/LNfcService( 1786): isRequireNfcCRouting() return true
D/LNfcService( 1786): isHCERoutingtoHost() return : true
D/NfcService( 1786): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1786): mEnableLPD: true
D/NfcService( 1786): mEnableReader: false
D/NfcService( 1786): mEnableHostRouting: true
D/NfcService( 1786): newParams.techmask= mTechMask: default
D/NfcService( 1786): mEnableLPD: true
D/NfcService( 1786): mEnableReader: false
D/NfcService( 1786): mEnableHostRouting: true
D/NfcService( 1786): screenState= 3
D/NfcService( 1786): Discovery configuration equal, not updating.
D/Ulp_jni (  861): JNI:system_update. Event-0
,D/SplitWindow(  861): check instance of lgWin Window{179e955a u0 SearchPanel}
,D/InputDispatcher(  861): Window went away: Window{252d299f u0 SearchPanel}
,I/[SystemUI]Clock( 1374): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1374): time changed, timezoneChanged : false
,V/PhoneApp( 1750): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2624): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:33:12
,D/WeatherService( 2624): 2 : ACTION screen on
D/WeatherService( 2624): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2624): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2624): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:33:12
W/Settings(  861): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  861): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  861): ACTION_SCREEN_ON
D/AppCleanupService( 4134): android.intent.action.SCREEN_ON
,V/AudioFlinger(  276): setParameters(): io 0, keyvalue screen_state=off, calling pid 861
D/audio_hw_primary(  276): adev_set_parameters: enter: screen_state=off
V/voice   (  276): voice_set_parameters: enter: screen_state=off
V/compress_voip(  276): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  276): voice_extn_compress_voip_set_parameters: exit
V/voice   (  276): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  276): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  276): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  276): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  276): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  276): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  276): adev_set_parameters: exit with code(0)
,D/WifiController(  861): CMD_SCREEN_OFF 
D/WifiController(  861): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  861): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1830): |CORE| sendScreenState: state:false
,I/LEDService( 1803): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1803): stopPatternFlashing()
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
I/LEDService( 1803): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1803): clear
D/LNfcService( 1786): action : android.intent.action.SCREEN_OFF
I/Cliptray Service( 1803): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/LEDService( 1803): updateLightsLocked : turn on led
E/LEDService( 1803): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1803): Can't handle this request of patternId:0
D/LEDHandler( 1803): RESTART MSG
D/NfcServiceNXP( 1786): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1877): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1750): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2624): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:33:12
D/WeatherService( 2624): 2 : ACTION screen off
D/WeatherService( 2624): 2 : TimeTick Receiver Unregister
D/WeatherService( 2624): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:33:12
W/Settings(  861): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  861): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  861): ACTION_SCREEN_OFF
D/AppCleanupService( 4134): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 4134): AppUsageStatsSaveTask
E/NxpNfcJni( 1786): getReconnectState = 0x0
,D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
D/LNfcService( 1786): isRequireNfcCRouting() return true
D/LNfcService( 1786): isHCERoutingtoHost() return : true
D/NfcService( 1786): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1786): mEnableLPD: true
D/NfcService( 1786): mEnableReader: false
D/NfcService( 1786): mEnableHostRouting: true
D/NfcService( 1786): newParams.techmask= mTechMask: 0
D/NfcService( 1786): mEnableLPD: true
D/NfcService( 1786): mEnableReader: false
D/NfcService( 1786): mEnableHostRouting: true
D/NfcService( 1786): screenState= 1
E/NxpNfcJni( 1786): getReconnectState = 0x0
,I/Sensors (  414): sns_pwr.c(301):releasing wakelock
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  861): ELAPSED_WAKEUP set : Alarm{3da3338b type 2 when 165000 com.android.systemui} when 165000
,D/KeyguardViewMediator( 1374): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/PhoneUtils( 1750): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1750): getCallState : 0
,D/PhoneUtils( 1750): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1374): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1374): doKeyguard: not showing because lockscreen is off
I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 175159577593; DSPS: 5837571; Offset : -2989846407
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,D/charger_monitor(  484): init target 500000
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 289, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  861): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  861): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  861): battery changed pluggedType: 2
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  861): ELAPSED_WAKEUP set : Alarm{20b37c68 type 2 when 188273 android} when 188273
,V/AlarmManager(  861): ELAPSED_WAKEUP set : Alarm{3cc3d881 type 2 when 190602 com.google.android.gms} when 190602
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 195160361492; DSPS: 6492957; Offset : -2989855887
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ClearcutLoggerApiImpl( 1731): disconnect managed GoogleApiClient
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 215161093308; DSPS: 7148341; Offset : -2989856363
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 235161839810; DSPS: 7803725; Offset : -2989843064
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,D/charger_monitor(  484): init target 500000
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  861): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  861): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  861): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 255162612042; DSPS: 8459111; Offset : -2989863403
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 275163309899; DSPS: 9114493; Offset : -2989837272
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 295164082131; DSPS: 9769879; Offset : -2989858132
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,D/charger_monitor(  484): init target 500000
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
,D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  861): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  861): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  861): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  861): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  861): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  861): battery changed pluggedType: 2
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
W/Settings(  861): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  861): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  861): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 315164862279; DSPS: 10425264; Offset : -2989841340
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 335165543470; DSPS: 11080647; Offset : -2989861924
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/LocationManagerService(  861): remove 39f3e3b
,D/LocationManagerService(  861): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  861): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  861): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  861): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  861): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/PowerManagerServiceEx(  861): acquireWakeLockInternal: lock=11952745, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=861
,D/PowerManagerServiceEx(  861): releaseWakeLockInternal: lock=11952745 [*alarm*], flags=0x0
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 355166341691; DSPS: 11736033; Offset : -2989857133
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  861): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  861): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  861): battery changed pluggedType: 2
I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 375167026892; DSPS: 12391415; Offset : -2989843318
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 395167781415; DSPS: 13046800; Offset : -2989851866
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 415168463699; DSPS: 13702182; Offset : -2989840863
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  861): battery changed pluggedType: 2
W/Settings(  861): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  861): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 435169164369; DSPS: 14357565; Offset : -2989841891
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 455169935819; DSPS: 15012951; Offset : -2989863715
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 475170840708; DSPS: 15668340; Offset : -2989844253
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
W/Settings(  861): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  861): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  861): battery changed pluggedType: 2
I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 495171520440; DSPS: 16323722; Offset : -2989835803
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 515172283505; DSPS: 16979107; Offset : -2989835834
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 535172969748; DSPS: 17634490; Offset : -2989851599
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 555173743230; DSPS: 18289875; Offset : -2989840899
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 575174427597; DSPS: 18945258; Offset : -2989858542
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 595175200975; DSPS: 19600643; Offset : -2989848051
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  861): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  861): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  861): battery changed pluggedType: 2
I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 615175874509; DSPS: 20256025; Offset : -2989845513
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 635176549553; DSPS: 20911407; Offset : -2989843757
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 655177316004; DSPS: 21566792; Offset : -2989838553
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  861): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  861): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  861): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 675178078965; DSPS: 22222177; Offset : -2989838479
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 695178960520; DSPS: 22877566; Offset : -2989842142
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 715179726397; DSPS: 23532951; Offset : -2989838867
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  861): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  861): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  861): battery changed pluggedType: 2
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 735180711494; DSPS: 24188344; Offset : -2989860875
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 755181462477; DSPS: 24843728; Offset : -2989842548
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 775182223354; DSPS: 25499113; Offset : -2989844663
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 795182907305; DSPS: 26154496; Offset : -2989862643
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 815183591308; DSPS: 26809878; Offset : -2989849531
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 835184368383; DSPS: 27465263; Offset : -2989835969
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  861): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  861): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  861): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 855185352646; DSPS: 28120656; Offset : -2989858369
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,D/PowerManagerServiceEx(  861): acquireWakeLockInternal: lock=11952745, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=861
,V/AlarmManager(  861): ELAPSED_WAKEUP set : Alarm{20ad26 type 2 when 855357 android} when 855357
D/PowerManagerServiceEx(  861): releaseWakeLockInternal: lock=11952745 [*alarm*], flags=0x0
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 875186034149; DSPS: 28776038; Offset : -2989848278
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 895186872475; DSPS: 29431425; Offset : -2989834005
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 915187656009; DSPS: 30086811; Offset : -2989844163
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 935188439595; DSPS: 30742197; Offset : -2989854034
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,D/PowerManagerServiceEx(  861): acquireWakeLockInternal: lock=11952745, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=861
,V/AlarmManager(  861): ELAPSED_WAKEUP set : Alarm{140f7d67 type 2 when 953544 com.android.bluetooth} when 953544
I/ActivityManager(  861): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7745 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,W/bt-smp  ( 1985): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1985): Plain text(LSB ~ MSB) = 91 ba 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 1985): Encrypted text(LSB ~ MSB) = 19 f7 ad 5e 8e 4c 9f 0c ba 50 f9 75 d3 49 69 04 
W/bt-btm  ( 1985): Stopping oneshot timer
,I/DigitalAppWidgetProvider( 7745): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7745): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3949dc71
D/PowerManagerServiceEx(  861): releaseWakeLockInternal: lock=11952745 [*alarm*], flags=0x0
I/ActivityManager(  861): Killing 7250:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  861): failed to open /acct/uid_10006/pid_7250/cgroup.procs: No such file or directory
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 955189104847; DSPS: 31397579; Offset : -2989860664
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 975189783903; DSPS: 32052961; Offset : -2989852005
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 995190684000; DSPS: 32708350; Offset : -2989837308
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,D/PowerManagerServiceEx(  861): acquireWakeLockInternal: lock=11952745, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=861
,V/AlarmManager(  861): ELAPSED_WAKEUP set : Alarm{2777f714 type 2 when 1011940 com.google.android.gms} when 1011940
,D/PowerManagerServiceEx(  861): releaseWakeLockInternal: lock=11952745 [*alarm*], flags=0x0
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1015191366908; DSPS: 33363733; Offset : -2989856226
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1035192129609; DSPS: 34019118; Offset : -2989856412
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1055192892674; DSPS: 34674503; Offset : -2989856313
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1075193572875; DSPS: 35329885; Offset : -2989847446
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  861): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  861): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  861): battery changed pluggedType: 2
I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1095194356201; DSPS: 35985271; Offset : -2989857500
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1115195114526; DSPS: 36640656; Offset : -2989862322
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1135195801290; DSPS: 37296038; Offset : -2989846789
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
W/Settings(  861): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  861): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  861): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1155196560813; DSPS: 37951423; Offset : -2989850180
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1175197248201; DSPS: 38606805; Offset : -2989834386
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1195197931892; DSPS: 39262188; Offset : -2989852808
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1215198621259; DSPS: 39917570; Offset : -2989834672
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/UsageStatsService(  861): User[0] Flushing usage stats to disk
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1235199302658; DSPS: 40572953; Offset : -2989855150
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1255200405880; DSPS: 41228349; Offset : -2989850431
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1275201263788; DSPS: 41883737; Offset : -2989847067
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1295202004458; DSPS: 42539121; Offset : -2989838898
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1315202840388; DSPS: 43194509; Offset : -2989857356
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1335203528609; DSPS: 43849891; Offset : -2989840365
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1355204285685; DSPS: 44505276; Offset : -2989846410
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1375205088021; DSPS: 45160662; Offset : -2989837740
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  861): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  861): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  861): battery changed pluggedType: 2
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1395205774679; DSPS: 45816045; Offset : -2989852778
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1415206641443; DSPS: 46471433; Offset : -2989841027
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1435207423883; DSPS: 47126819; Offset : -2989851602
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1455208124293; DSPS: 47782202; Offset : -2989852965
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1475208802462; DSPS: 48437584; Offset : -2989845975
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1495209586048; DSPS: 49092970; Offset : -2989856184
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  861): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  861): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  861): battery changed pluggedType: 2
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1515210388281; DSPS: 49748356; Offset : -2989847279
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1535211183012; DSPS: 50403742; Offset : -2989845952
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1555211901233; DSPS: 51059126; Offset : -2989860310
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  861): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  861): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  861): battery changed pluggedType: 2
I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1575212585705; DSPS: 51714508; Offset : -2989846989
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1595213351010; DSPS: 52369893; Offset : -2989844806
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1615214040065; DSPS: 53025276; Offset : -2989857759
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  861): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  861): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  861): battery changed pluggedType: 2
I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1635214816255; DSPS: 53680661; Offset : -2989846098
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1655215631768; DSPS: 54336048; Offset : -2989852788
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1675216308948; DSPS: 54991430; Offset : -2989846813
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/QCNEJ   ( 1830): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1830): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  861): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  861): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  861): battery changed pluggedType: 2
I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1695216988367; DSPS: 55646812; Offset : -2989839223
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1715217824974; DSPS: 56302200; Offset : -2989856718
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1735218597050; DSPS: 56957585; Offset : -2989847894
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1755219282094; DSPS: 57612967; Offset : -2989834185
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1775219970056; DSPS: 58268350; Offset : -2989849767
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1795220849528; DSPS: 58923739; Offset : -2989853742
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1815221530249; DSPS: 59579121; Offset : -2989844591
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1835222288731; DSPS: 60234506; Offset : -2989848918
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  861): acquireWakeLockInternal: lock=11952745, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=861
,V/AlarmManager(  861): ELAPSED_WAKEUP set : Alarm{315a75b2 type 2 when 1853712 com.android.bluetooth} when 1853712
,W/bt-smp  ( 1985): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1985): Plain text(LSB ~ MSB) = 9b 82 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 1985): Encrypted text(LSB ~ MSB) = e3 c0 55 f8 7a 33 0a 20 ed da 5f a4 83 b3 9d 74 
W/bt-btm  ( 1985): Stopping oneshot timer
I/ProcessStatsService(  861): Prepared write state in 13ms
,I/ProcessStatsService(  861): Prepared write state in 15ms
,I/DigitalAppWidgetProvider( 7745): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7745): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3949dc71
,D/PowerManagerServiceEx(  861): releaseWakeLockInternal: lock=11952745 [*alarm*], flags=0x0
I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ProcessStatsService(  861): Pruning old procstats: /data/system/procstats/state-2015-12-01-17-48-14.bin
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1855222973932; DSPS: 60889888; Offset : -2989834686
I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1875223653611; DSPS: 61545271; Offset : -2989856939
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1895225727458; DSPS: 62200699; Offset : -2989858183
I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,TIME-OUT KILL (timeout was 1800000ms),I/jxcore-log( 6192): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6192): 
D/AndroidRuntime( 7909): 
D/AndroidRuntime( 7909): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7909): CheckJNI is OFF
D/AndroidRuntime( 7909): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  861): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  861): Killing 6192:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  861): WIN DEATH: Window{2ed49b1a u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  861): Focus left window: Window{2ed49b1a u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  861): Window went away: Window{2ed49b1a u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
W/PackageSettings(  861): Skipping PackageSetting{3583800c com.example.hello/10030} due to missing metadata
I/ActivityManager(  861):   Force finishing activity ActivityRecord{50f768b u0 com.test.thalitest/.MainActivity t220}
V/ActivityManager(  861): Display changed displayId=0
D/DSDPConnection( 1750): Display #0 changed.
W/ActivityManager(  861): Spurious death for ProcessRecord{d0c8903 6192:com.test.thalitest/u0a316}, curProc for 6192: null
I/ActivityManager(  861): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  861):   Force finishing activity ActivityRecord{50f768b u0 com.test.thalitest/.MainActivity t220 f}
W/ActivityManager(  861): Duplicate finish request for ActivityRecord{50f768b u0 com.test.thalitest/.MainActivity t220 f}
I/art     ( 1937): Explicit concurrent mark sweep GC freed 10198(662KB) AllocSpace objects, 3(71KB) LOS objects, 40% free, 12MB/21MB, paused 1.806ms total 74.597ms
D/KeyguardModel( 1374): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 1877): [Launcher.java:5203:onStart()]onStart
W/System.err( 3643): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3643): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3643): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3643): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3643): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3643): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3643): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3643): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3643): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3643): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3643): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3643): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/InputReader(  861): Reconfiguring input devices.  changes=0x00000010
I/QCNEJ   ( 1830): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[LGHome]EVENT( 1877): [Launcher.java:776:onResume()]onResume
I/ActivityManager(  861): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7942 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1877): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_REMOVED
D/KeyguardModel( 1374): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1374): createShortcutInfo...
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/KeyguardModel( 1374): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1374): createShortcutInfo...
I/[LGHome]LGActivityUtil( 1877): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1877): [Launcher.java:929:onResume()]onResume end
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
I/Activity( 1877): Activity.onPostResume() called 
W/PackageManager( 1374): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1374): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1374): createShortcutInfo...
I/[LGHome]EVENT( 1877): [Launcher.java:986:onPause()]onPause
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1374): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1374): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1374): createShortcutInfo...
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1374): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1374): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
W/[LGHome]LGWallpaperInfo( 1877): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1877): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
D/KeyguardModel( 1374): handleShortcutListChanged...
I/SystemUI[Framework](  861): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
D/KeyguardModel( 1374): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1374): createShortcutInfo...
D/KeyguardModel( 1374): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1374): createShortcutInfo...
D/InputDispatcher(  861): Focus entered window: Window{2576a96c u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.mms: Resource ID #0x0
W/PhoneWindowManagerEx(  861): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  861): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  861): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  861): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2988b3ce,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  861): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  861): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  861): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  861): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  861): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  861): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2988b3ce,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  861): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/KeyguardModel( 1374): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/art     (  861): Explicit concurrent mark sweep GC freed 82215(4MB) AllocSpace objects, 16(460KB) LOS objects, 33% free, 23MB/35MB, paused 6.775ms total 253.955ms
I/art     (  861): WaitForGcToComplete blocked for 221.113ms for cause Explicit
D/KeyguardModel( 1374): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1374): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourcesManager( 7942): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7942): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7942): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/KeyguardModel( 1374): handleShortcutListChanged...
D/administrator(  861): Handling package changes for user 0
I/LGEmail ( 7942): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/art     (  861): Explicit concurrent mark sweep GC freed 5717(340KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 7.225ms total 283.247ms
D/LGEmail ( 7942): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/art     (  861): WaitForGcToComplete blocked for 490.942ms for cause Explicit
I/NotificationService(  861): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  861): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  861): Receieved: android.intent.action.PACKAGE_REMOVED
D/PhoneStatusBar( 1374): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/PhoneStatusBar( 1374): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1374): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1374):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1374): , Keyguard show=false, IME shown=false, Panel expanded=false
D/TaskPersister(  861): removeObsoleteFile: deleting file=220_task.xml
I/art     (  861): Explicit concurrent mark sweep GC freed 4992(284KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 7.484ms total 185.027ms
D/AndroidRuntime( 7909): Shutting down VM
W/GeofencerStateMachine( 1731): Ignoring removeGeofence because network location is disabled.
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
I/[LGHome]EVENT( 1877): [Launcher.java:5214:onStop()]onStop
I/[LGHome]EVENT( 1877): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1877): [setNavigationBarColor] color=0x 0
W/InputMethodManagerService(  861): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  861): Got RemoteException sending setActive(false) notification to pid 6192 uid 10316
D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
I/PackageChangeReceiver( 7942): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/Timeline(  861): Timeline: Activity_windows_visible id: ActivityRecord{3355434d u0 com.lge.launcher2/.Launcher t219} time:1906237
D/AppUp4:PreloadHelper( 7361): added Exclude : com.test.thalitest
W/IInputConnectionWrapper( 1877): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1568): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1877): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1877): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/ActivityManager(  861): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7966 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  861): Killing 7007:com.google.android.talk/u0a61 (adj 15): empty #11
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1877): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/ResourcesManager(  861): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/libprocessgroup(  861): failed to open /acct/uid_10061/pid_7007/cgroup.procs: No such file or directory
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/ResourceType(  861): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created

```
