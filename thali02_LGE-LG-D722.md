#### Test 5797209499148df_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/AudioManager( 5167): getMode name:com.lge.qremote
I/Icing   ( 4305): updateResources: need to parse f{com.google.android.gms}
D/Finsky  ( 5953): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
--------- beginning of system
I/ActivityManager(  949): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6012 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
I/art     (  301): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 298us total 23.040ms
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 302us total 22.149ms
I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 21.848ms
D/PhoneMonitor( 6012): Register our PhoneStateListener
V/SetupWizard( 6012): Connected to Gservices successfully
I/ActivityManager(  949): Killing 5493:com.android.providers.calendar/u0a14 (adj 15): empty #11
D/PhoneMonitor( 6012): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6012): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6012): [parse] Load xml
V/TelephonyAutoProfiling( 6012): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6012): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 6012): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  949): failed to open /acct/uid_10014/pid_5493/cgroup.procs: No such file or directory
D/GCM     ( 1728): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
E/MDM     ( 1728): [121] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 4305): Restart initialization of location
D/AuthorizationBluetoothService( 1728): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1728): com.google.android.gms: cancel(0) by com.google.android.gms
I/ActivityManager(  949): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6043 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/GCoreFlp( 1728): No location to return for getLastLocation()
W/FusedLocationProvider( 1728): location=null
W/ActivityManager(  949): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
I/Gmail   ( 6043): getAccountsCursor
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 6034): 
D/AndroidRuntime( 6034): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6034): CheckJNI is OFF
W/GAV2    ( 6043): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ActivityManager(  949): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager(  949): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager(  949): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 6043): Observing account changes for notifications
E/Gmail   ( 6043): Error finding the version of the Email provider.....
E/Gmail   ( 6043): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6043): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6043): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6043): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6043): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6043): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6043): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6043): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6043): We do not support migrating this version of the Email provider.
I/Gmail   ( 6043): getAccountsCursor
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  949): Killing 5843:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  949): failed to open /acct/uid_10011/pid_5843/cgroup.procs: No such file or directory
I/art     ( 1728): Explicit concurrent mark sweep GC freed 34192(2MB) AllocSpace objects, 23(368KB) LOS objects, 40% free, 13MB/22MB, paused 1.803ms total 104.910ms
D/AndroidRuntime( 6034): Calling main entry com.android.commands.am.Am
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  949): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  949): setTaskToReturnTo : TaskRecord{30bdf7b7 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  949): setTaskToReturnTo : TaskRecord{30bdf7b7 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  949): AppWindowTokenEx init.. 
I/Gmail   ( 6043): notifyAccountChanged
I/Gmail   ( 6043): getAccountsCursor
I/Gmail   ( 6043): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/ContextHelper(  949): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/Gmail   ( 6043): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 6043): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 6043): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/[LGHome]EVENT( 1874): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  949): Focus left window: Window{29bf13c3 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 6034): Shutting down VM
D/SplitWindow(  949): check instance of lgWin Window{287d3a45 u0 Starting com.test.thalitest}
I/Icing   ( 4305): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 4305): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/ActivityManager(  949): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6100 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1874): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/GCM     ( 1728): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/AudioManager( 5167): getMode name:com.lge.qremote
I/HotwordDetector( 1929): Closing mic
I/[LGHome]EVENT( 1874): [Launcher.java:5214:onStop()]onStop
I/MicrophoneInputStream( 1929): mic_close com.google.android.apps.gsa.speech.audio.u@39794403
V/AudioRecord( 1929): stop()
D/AudioRecord( 1929): AudioRecord->stop()
V/AudioFlinger(  272): RecordHandle::stop()
V/AudioFlinger(  272): RecordThread::stop
V/AudioFlinger(  272): Record stopped OK
V/AudioPolicyManager(  272): stopInput() input 16
V/AudioPolicyService(  272): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  272): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  272): AudioCommandThread() waking up
V/AudioPolicyService(  272): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  272): releaseAudioPatch handle 17
V/AudioFlinger::PatchPanel(  272): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  272): ThreadBase::setParameters() routing=0
V/AudioFlinger(  272): sendConfigEvent_l() num events 1 event 2
I/WindowStateAnimator(  949): Starting window displayed
V/AudioFlinger(  272): processConfigEvents_l() remaining events 1
V/AudioFlinger(  272): processConfigEvents_l() DONE thread 0xb3827000
D/audio_hw_primary(  272): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
I/SystemUI[Framework](  949): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
,W/PhoneWindowManagerEx(  949): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  949): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  949): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PhoneStatusBar( 1370): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
I/SystemUI[Framework](  949): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@565595d,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  949): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1370): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1370):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1370): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1370): draw background and invalidate : color = c000000
D/BarTransitions( 1370): draw background and invalidate : color = 18171717
V/audio_hw_primary(  272): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  272): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  272): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  272): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  272): disable_audio_route: exit
E/audio_hw_primary(  272): disable_snd_device: enter 144
D/hardware_info(  272): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  272): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  272): stop_input_stream: exit: status(0)
V/audio_hw_primary(  272): in_standby: exit:  status(0)
V/AudioFlinger(  272): RecordThread: loop stopping
V/AudioPolicyService(  272): AudioCommandThread() going to sleep
V/AudioPolicyManager(  272): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  272): removeAudioPatch() handle 18 af handle 17
V/AudioPolicyService(  272): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  272): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  272): AudioCommandThread() waking up
V/AudioPolicyService(  272): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  272): AudioCommandThread() going to sleep
V/AudioPolicyService(  272): AudioCommandThread() adding set parameter string hotword_active=0, io 16 ,delay 0
V/AudioPolicyService(  272): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  272): AudioCommandThread() waking up
V/AudioPolicyService(  272): AudioCommandThread() processing set parameters string hotword_active=0, io 16
V/AudioFlinger(  272): setParameters(): io 16, keyvalue hotword_active=0, calling pid 272
V/AudioFlinger(  272): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  272): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  272): RecordThread: loop starting
V/AudioFlinger(  272): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  272): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  272): in_set_parameters: exit: status(0)
V/AudioFlinger(  272): processConfigEvents_l() DONE thread 0xb3827000
V/AudioFlinger(  272): RecordThread: loop stopping
V/AudioPolicyService(  272): AudioCommandThread() going to sleep
I/ActivityManager(  949): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6124 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AudioRecord( 1929): stop()
V/AudioRecord( 1929): stop()
V/AudioRecord( 1929): stop()
V/AudioFlinger(  272): RecordHandle::stop()
V/AudioFlinger(  272): RecordThread::stop
V/AudioPolicyManager(  272): releaseInput() 16
V/AudioPolicyManager(  272): closeInput(16)
V/AudioFlinger(  272): closeInput() 16
V/AudioSystem(  272): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  272): ThreadBase::exit
V/AudioFlinger(  272): RecordThread: loop starting
V/AudioSystem(  949): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  272): RecordThread 0xb3827000 exiting
V/AudioSystem( 1966): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  272): releasing 15 from 1929 for -1
V/AudioFlinger(  272):  decremented refcount to 0
V/AudioFlinger(  272): purging stale effects
V/AudioSystem( 1746): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1370): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1929): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 2719): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 3195): ioConfigChanged() event 4, ioHandle 16
D/audio_hw_primary(  272): adev_close_input_stream: enter:stream_handle(0xb546e1a0)
D/audio_hw_primary(  272): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  272): in_standby: exit:  status(0)
V/AudioPolicyService(  272): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  272): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  272): releaseInput() exit
V/AudioPolicyService(  272): AudioCommandThread() waking up
V/AudioPolicyService(  272): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  272): AudioCommandThread() going to sleep
V/AudioFlinger(  272): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  272): removeClient_l() pid 1929, calling pid 272
I/[SystemUI]QPairHandler( 1370): onReceive = android.intent.action.PACKAGE_CHANGED
I/QCNEJ   ( 1836): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[LGHome]EVENT( 1874): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/HotwordRecognitionRnr( 1929): Stopping hotword detection.
I/[SystemUI]QSlideListController( 1370): onReceive = android.intent.action.PACKAGE_CHANGED
I/[LGHome]LGPlusHomeDBManager( 1874): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1874): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/InputReader(  949): Reconfiguring input devices.  changes=0x00000010
W/[SystemUI]QSlideLoader( 1370): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1370): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/HotwordRecognitionRnr( 1929): Hotword detection finished
D/administrator(  949): Handling package changes for user 0
W/ResourcesManager( 6124): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/ContextHelper( 6100): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/CalendarApplication( 6124): CalendarApplication.onCreate()
D/PreferenceKeysParser( 6124): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6124): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@2f6f91fc, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@15e42085, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@3fe88eda, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@28276f0b, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@a21d1e8, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1fcb4001, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@38d0bea6, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@255bf0e7, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@25362494, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@35aadb3d, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@36ba1f32, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@156cb483, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@1e9af600, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@2eeee39, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@566fc7e, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@353c15df, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@2b9722c, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@23c734f5, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@1872628a, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@37630fb, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@19618518, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@da32b71, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@101c1d56, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@336ce1d7, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@1575dac4, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@36e0dad, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@3ed4b8e2, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@31b3c473, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@1357df30, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@118ad7a9, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@3b89812e, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@167c34cf, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@1213be5c, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@d904565, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@cb0823a, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@21b14eeb, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@134c6448, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@15c4d2e1, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@38148806, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1cd3eec7, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@de77cf4, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@c5abc1d,
I/Gmail   ( 6043): getAccountsCursor
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/WebViewFactory( 6100): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
D/GeneralPreferenceUtils( 6124): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6124): [init]
I/Config  ( 6124): LGCalendar ver.4.40.17
I/Config  ( 6124): start check model
I/Config  ( 6124): start check native_ca
I/Config  ( 6124): Config Operator=OPEN, Country=EU
D/Config  ( 6124): [setDefaultValuesToPref]
D/Config  ( 6124): [parseProfiles]
I/NotificationService(  949): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  949): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  949): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  949): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
D/ProfilesParser( 6124): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6124): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6124): [updateProfiletoCountryInfo]
D/GeneralPreference( 6124): [checkAndMigrateOldPreference]
V/BackupManagerService(  949): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  949): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1e35107b
D/AlertReceiver( 6124): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
I/LibraryLoader( 6100): Time to load native libraries: 12 ms (timestamps 9652-9664)
I/LibraryLoader( 6100): Expected native library version number "",actual native library version number ""
I/InitNotificationRingtoneService( 6124): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 6124): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
W/ResourcesManager(  949): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/WebViewChromiumFactoryProvider( 6100): Binding Chromium to main looper Looper (main, tid 1) {28276f0b}
I/LibraryLoader( 6100): Expected native library version number "",actual native library version number ""
I/chromium( 6100): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/AlertUtils( 6124): [getCalendarNotiSoundURIFromCursor] getCount()= 21
I/BrowserStartupController( 6100): Initializing chromium process, singleProcess=true
I/AlertUtils( 6124): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
W/art     ( 6100): Attempt to remove local handle scope entry from IRT, ignoring
I/AlertUtils( 6124): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
E/SysUtils( 6100): ApplicationContext is null in ApplicationStatus
I/AlertUtils( 6124): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 6124): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 6124): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6124): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/AlertUtils( 6124): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6124): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 6124): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6124): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
,I/AlertUtils( 6124): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6124): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
W/chromium( 6100): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6100): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6100): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6100): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6100): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6100): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6100): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6100): Remote Branch: 
I/Adreno-EGL( 6100): Local Patches: 
I/Adreno-EGL( 6100): Reconstruct Branch: 
I/AlertUtils( 6124): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6124): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,W/ResourceType(  949): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/AlertUtils( 6124): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
,I/AlertUtils( 6124): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 6124): set default noti to content://media/internal/audio/media/38
,I/[LGHome]EVENT( 1874): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/InitNotificationRingtoneService( 6124): End InitializeAlertRingtoneService.onHandleIntent
,I/GCoreNlp( 1728): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
V/AudioPolicyService(  272): registerClient() client 0xb57e7560, uid 10316
,D/BluetoothManagerService(  949): Message: 20
D/BluetoothManagerService(  949): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@14c685b:true
D/BluetoothAdapterService(626782439)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@23c734f5
,W/HolidayIntentService( 6124): onHandleIntent
D/LCardEmulationManager( 1783): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1783): getDefaultRoute
,D/LocationProviderProxy(  949): applying state to connected service
D/HolidayDataLoader( 6124): readJsonAsset : holiday.json
D/AlertService( 6124): 0 Action = android.intent.action.PROVIDER_CHANGED
,E/AgendaWidgetManager( 6124): [updateWidgets] 
D/MonthWidgetProvider( 6124): [onReceive]
D/CalendarWidgetProvider( 6124): [onReceive]
D/CalendarWidgetProvider( 6124): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6124): [onCreate] mContext.getPackageName() = com.android.calendar
,D/WeekWidgetProvider( 6124): [onReceive]
D/CalendarWidgetProvider( 6124): [onReceive]
D/CalendarWidgetProvider( 6124): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
I/AudioManager( 5167): getMode name:com.lge.qremote
,D/CalendarTypeController( 6124): [onCreate] mContext.getPackageName() = com.android.calendar
I/AudioManager( 5167): getMode name:com.lge.qremote
I/AudioManager( 5167): getMode name:com.lge.qremote
,I/AudioManager( 5167): getMode name:com.lge.qremote
E/HolidayIntentService( 6124): onHandleIntent:holiday data empty
,I/ActivityManager(  949): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6179 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/art     ( 6100): Attempt to remove local handle scope entry from IRT, ignoring
I/NotificationManager( 5774): com.google.android.talk: cancel(8) by com.google.android.talk
W/AwContents( 6100): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6100): CordovaWebView is running on device made by: LGE
W/art     ( 6100): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6100): Attempt to remove local handle scope entry from IRT, ignoring
I/AppUp4:AppBoxCP( 6179): onCreate
,W/AppUp4:DB( 6179):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6179):  setFingerPrint start
,I/AppUp4:DB( 6179):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6179):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6179):  SDK version = 0
I/AppUp4:DB( 6179):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6179): AppBoxApplication onCreate()
,I/Activity( 6100): Activity.onPostResume() called 
I/AppUp4:CustModeStarterReceiver( 6179): onReceive
I/AppUp4:CustModeStarterReceiver( 6179): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 6179): Context : android.app.ReceiverRestrictedContext@15e42085
D/AppUp4:CustFacade( 6179): isCustomizationCompleted : false
D/OpenGLRenderer( 6100): Render dirty regions requested: true
I/OpenGLRenderer( 6100): Initialized EGL, version 1.4
,D/AppUp4:CustFacade( 6179): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6179): begin check event
I/AppUp4:CustModeStarterReceiver( 6179): Event For Nothing, skip.
D/OpenGLRenderer( 6100): Enabling debug mode 0
D/Atlas   ( 6100): Validating map...
,D/SplitWindow(  949): check instance of lgWin Window{3f34d6ca u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 6100): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/LockScreenSettings( 5911): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5911): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5911): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5911): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5911): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  949): Killing 5953:com.android.vending/u0a36 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1929): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
D/InputDispatcher(  949): Focus entered window: Window{3f34d6ca u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/InputMethodManagerService(  949): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,W/libprocessgroup(  949): failed to open /acct/uid_10036/pid_5953/cgroup.procs: No such file or directory
I/Timeline( 6100): Timeline: Activity_idle id: android.os.BinderProxy@101c1d56 time:90348
,I/UpdateIcingCorporaServi( 1929): UpdateCorporaTask done [took 82 ms] updated apps [took 82 ms] 
I/ActivityManager(  949): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6209 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  949): Displayed com.test.thalitest/.MainActivity: +1s445ms
I/Timeline(  949): Timeline: Activity_windows_visible id: ActivityRecord{30e66b24 u0 com.test.thalitest/.MainActivity t222} time:90394
V/AlarmManager(  949): ELAPSED_WAKEUP set : Alarm{3c697522 type 2 when 90430 com.android.providers.calendar} when 90430
,W/BindingManager( 6100): Cannot call determinedVisibility() - never saw a connection for the pid: 6100
D/Finsky  ( 6209): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6209): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6209): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6209): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6209): com.android.vending: cancel(-1050172287) by com.android.vending
D/UEI.SmartControl( 5816): Internal timer expired: 1
,V/DownloadManager( 3244): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3244): created cursor android.database.sqlite.SQLiteCursor@6b651d5 on behalf of 6209
,D/Finsky  ( 6209): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6209): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 6209): Skipping gmscore version check
D/Finsky  ( 6209): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 4305): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/Finsky  ( 6209): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/JsMessageQueue( 6100): Set native->JS mode to OnlineEventsBridgeMode
,I/PackageBroadcastService( 4305): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  949): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6257 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  949): Killing 6012:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/Icing   ( 4305): updateResources: need to parse f{com.google.android.gms}
W/libprocessgroup(  949): failed to open /acct/uid_10038/pid_6012/cgroup.procs: No such file or directory
,W/ResourcesManager( 6257): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6257): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@180c03ce
D/jxcore_app_log( 6100): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622895104
,D/CalendarProvider2( 6257): [getOrCreateCalendarAlarmManager]
,I/chromium( 6100): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/CalendarProvider2( 6257): Created com.android.providers.calendar.CalendarAlarmManager@28276f0b(com.android.providers.calendar.CalendarProvider2@180c03ce)
D/CalendarProviderBroadcastReceiver( 6257): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
,D/CalendarProviderBroadcastReceiver( 6257): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 6257): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 6257): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
,D/CalendarProvider2( 6257): [getOrCreateCalendarAlarmManager]
D/CalendarProvider2( 6257): [IntentService] Release Lock
,D/CalendarProvider2( 6257): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  949): Killing 6179:com.lge.appbox.client/u0a11 (adj 15): empty #11
I/art     ( 6100): CheckpointMarkThreadRoots callback created = 0x995a7510
,I/art     ( 6100): CheckpointMarkThreadRoots callback created = 0x995a74e0
,W/libprocessgroup(  949): failed to open /acct/uid_10011/pid_6179/cgroup.procs: No such file or directory
,I/art     (  949): Explicit concurrent mark sweep GC freed 42705(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.367ms total 179.049ms
,I/Icing   ( 4305): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4305): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,W/jxcore-log( 6100): Initializing JXcore engine
,W/jxcore-log( 6100): JXcore engine is ready
I/ActivityManager(  949): Killing 5867:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/libprocessgroup(  949): failed to open /acct/uid_10023/pid_5867/cgroup.procs: No such file or directory
,W/Thread-746( 6276): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7650]" dev="sockfs" ino=7650 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-746( 6276): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-746( 6276): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[5795]" dev="sockfs" ino=5795 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-746( 6276): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-746( 6276): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-746( 6276): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[24244]" dev="sockfs" ino=24244 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 6100): Starting JXcore engine
,I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,W/jxcore-log( 6100): Platform android
W/jxcore-log( 6100): 
,W/jxcore-log( 6100): Process ARCH arm
W/jxcore-log( 6100): 
I/GAV2    ( 6043): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 6100): JXcore Cordova bridge is ready!
I/jxcore-log( 6100): 
,W/jxcore-log( 6100): JXcore engine is started
V/AlarmManager(  949): RTC_WAKEUP set : Alarm{2b240791 type 0 when 1454416538870 com.android.vending} when 1454416538870
,D/Finsky  ( 6209): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  949): android: cancelAsUser(2) by android
,I/jxcore-log( 6100): Toggling radios to true
I/jxcore-log( 6100): 
,D/BluetoothAdapter( 6100): enable(): BT is already enabled..!
D/WifiServiceImplEx(  949): setWifiEnabled: true pid=6100, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  949): setWifiEnabled: true pid=6100, uid=10316
,D/WifiServiceImplEx(  949): disconnect pid=6100, uid=10316, packageName=com.test.thalitest
D/WifiServiceImplEx(  949): reconnect pid=6100, uid=10316, packageName=com.test.thalitest
,I/jxcore-log( 6100): Radios toggled
I/jxcore-log( 6100): 
I/jxcore-log( 6100): My device name is: LGE-LG-D722
I/jxcore-log( 6100): 
I/wpa_supplicant( 2832): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,I/Netd    (  266): M: Get netlink event, ifname: wlan0 action: 4
D/libc-netbsd( 6209): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6209): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Netd    (  266): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2832): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine(  949): WifiStateMachine: Leaving Connected state
,D/libc-netbsd( 6209): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6209): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/WifiConfigStore(  949): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/BandwidthController(  266): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  266): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  266): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  266): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  266): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  266): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  266): res_queryN name = xxxxx succeed
I/System.out( 6209): propertyValue:false
D/libc-netbsd( 6209): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6209): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WfdsMonitor( 1801): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,D/LGWifiP2pService(  949): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  949): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  949): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  266): Clearing all IP addresses on wlan0
I/Netd    (  266): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1728): Read error: ssl=0xb0460600: I/O error during system call, Connection timed out
,V/NativeCrypto( 1728): SSL shutdown failed: ssl=0xb0460600: I/O error during system call, Broken pipe
I/Netd    (  266): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  266): M: Get netlink event, ifname: wlan0 action: 7
,D/libc-netbsd(  949): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/WifiHS20(  949): hidePasspointNotification off =false
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  949): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  949): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  949): ignoring duplicate network state non-change
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 13:35:39.28 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/ConnectivityService(  949): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/libc-netbsd(  949): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  949): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
,D/libc-netbsd(  949): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  949): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  949): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  949): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  949): ValidatedState{ when=-3ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  949): DefaultState{ when=-11ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  949): Forcing reevaluation
I/ActivityManager(  949): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6340 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,E/WifiStateMachine(  949): Start Disconnecting Watchdog 1
D/WifiHS20(  949): hidePasspointNotification off =false
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  949): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGWifiP2pService(  949): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  949): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2832): wlan0: CTRL-EVENT-SCAN-STARTED 
,I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 13:35:39.351 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
V/AlarmManager(  949): RTC_WAKEUP set : Alarm{ba404e8 type 0 when 1454416539272 com.google.android.googlequicksearchbox} when 1454416539272
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/NotificationManager(  949): android: cancelAsUser(2) by android
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
D/CommandListener(  266): Clearing all IP addresses on wlan0
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
,D/ConnectivityService(  949): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  949): disableDataServiceNotify
D/DSQN    (  949): stop dsqn bin
D/WifiHS20(  949): hidePasspointNotification off =false
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
,I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 13:35:39.417 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  949): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
D/WifiNetworkAgent(  949): NetworkAgent: NetworkAgent channel lost
D/ConnectivityService(  949): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 13:35:39.432 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20(  949): hidePasspointNotification off =false
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  949): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 13:35:39.435 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/ConnectivityService(  949):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  949):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  949): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/ConnectivityService(  949): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  949): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/WifiServerServiceExt(  949): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  949): setSupplicantStateDISCONNECTED
D/libc-netbsd( 6209): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6209): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6209): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/ConnectivityManager.CallbackHandler( 1370): CM callback handler got msg 524292
D/libc-netbsd( 6209): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  949): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  949): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got act,ion android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
D/CSLegacyTypeTracker(  949): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  949): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  949): Disconnected - quitting
D/WifiServerServiceExt(  949): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  949): setSupplicantStateSCANNING
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
D/DhcpStateMachine(  949): StoppedState
D/DhcpStateMachine(  949): StoppedState{ when=-106ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  949): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  949): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  949): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  949): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1836): |CORE| No family connected
D/ConnectivityService(  949): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  949): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  949): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  949): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  949):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/Tethering(  949): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1836): |CORE| No family connected
I/QCNEJ   ( 1836): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1836): |CORE| sendDefaultNwMsg: default = -1
D/TelephonyNetworkFactory-1( 1746): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1746):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
V/NetworkPolicy(  949): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy(  949): [LG_RESTRICTED] !!!isConnected  type  :1
W/Finsky  ( 6209): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: org.apache.http.conn.HttpHostConnectException: Connection to https://android.clients.google.com refused
D/NetworkManagementService(  949): Removing idletimer
,W/Settings(  949): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/TelephonyIcons( 1370): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1370): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/NotificationManager(  949): android: cancelAsUser(2) by android
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/libc-netbsd( 6209): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6209): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6209): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6209): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/TelephonyIcons( 1370): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1370): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  949): Process com.android.contacts (pid 5889) has died
,W/ResourcesManager( 6340): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6340): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6340): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6340): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6340): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/ActivityManager(  949): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6366 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  949): Process com.lge.lockscreensettings (pid 5911) has died
,I/NotificationManager(  949): android: cancelAsUser(2) by android
,I/IndexDatabaseHelper( 6340): Using schema version: 115
I/IndexDatabaseHelper( 6340): Index is fine
W/ResourcesManager( 6366): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6366): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/libc-netbsd( 6209): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6209): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6209): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6209): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Finsky  ( 6209): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: org.apache.http.conn.HttpHostConnectException: Connection to https://android.clients.google.com refused
,D/AlertService( 6124): Beginning updateAlertNotification
,D/AlertService( 6124): No fired or scheduled alerts
,I/NotificationManager( 6124): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6124): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6124): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6124): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6124): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6124): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6124): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6124): com.android.calendar: cancel(7) by com.android.calendar
I/MultiDex( 6366): VM with version 2.1.0 has multidex support
I/NotificationManager( 6124): com.android.calendar: cancel(8) by com.android.calendar
I/MultiDex( 6366): install
I/NotificationManager( 6124): com.android.calendar: cancel(9) by com.android.calendar
I/MultiDex( 6366): VM has multidex support, MultiDex support library is disabled.
I/NotificationManager( 6124): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6124): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6124): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6124): com.android.calendar: cancel(13) by com.android.calendar
,I/NotificationManager( 6124): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6124): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6124): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6124): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6124): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6124): com.android.calendar: cancel(19) by com.android.calendar
,I/NotificationManager( 6124): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 6124): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 6124): No events found starting within 1 week.
,V/JNIHelp ( 6366): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,V/WiFiOffLoadBroadcast( 6340): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6340): MCCMNC not supported: null
W/ActivityThread( 6366): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6366): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@6b651d5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6366): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  949): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6395 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/NotificationManager( 6366): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6366): com.google.android.gms: cancel(39789) by com.google.android.gms
D/sensors_hal_Time(  949): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  949): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  949): tsOffsetIs: Apps: 95258255697; DSPS: 3220351; Offset : -3027918289
,D/ChimeraCfgMgr( 6366): Reading stored module config
,D/ChimeraCfgMgr( 6366): Loading module com.google.android.gms.car from APK com.google.android.gms
,I/PCSuite ( 6395): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6395): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6395): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,D/NativeLibraryUtils( 6366): Install completed successfully. count=14 extracted=0
,I/ActivityManager(  949): Process com.google.android.talk (pid 5774) has died
,I/Netd    (  266): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2832): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
V/WiFiOffLoadBroadcast( 6340): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6340): MCCMNC not supported: null
I/PCSuite ( 6395): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6395): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6395): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  949): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6423 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/LocSvc_java(  949): onReceive
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  949): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  949): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt(  949): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  949): setSupplicantStateASSOCIATING
I/Netd    (  266): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  266): M: Get netlink event, ifname: wlan0 action: 4
,I/Netd    (  266): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2832): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiServerServiceExt(  949): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  949): setSupplicantStateASSOCIATED
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 13:35:40.572 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 13:35:40.574 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
,I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  949): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 13:35:40.587 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  949): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 13:35:40.588 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
D/WifiServerServiceExt(  949): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  949): setSupplicantStateFOUR_WAY_HANDSHAKE
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/wpa_supplicant( 2832): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2832): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  266): M: Get netlink event, ifname: wlan0 action: 4
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
D/WifiServerServiceExt(  949): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  949): setSupplicantStateGROUP_HANDSHAKE
I/WifiServiceExtension(  949): setVHTCapabilityType  : false
D/CAR.SERVICE( 6366): Connecting to CarCallService...
,I/WifiServerServiceExt(  949): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  949): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  949): setSecurityType  : 2
,I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  949): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 13:35:40.644 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  949): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 13:35:40.646 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
,I/art     ( 6366): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6366): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/ConnectivityService(  949): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  949): Got NetworkAgent Messenger
D/ConnectivityService(  949): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  949): NetworkAgent connected
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
E/WifiConfigStore(  949): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  949): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Netd    (  266): M: Get netlink event, ifname: wlan0 action: 9
,D/libc-netbsd(  949): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  949): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  949): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  949): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  266): Setting iface cfg
E/WifiStateMachine(  949): Start Dhcp Watchdog 2
D/DhcpStateMachine(  949): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  949): WaitBeforeStartState
D/ConnectivityService(  949): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,D/CAR.SERVICE( 6366): com.google.android.projection.gearhead isn't installed.
D/CAR.TEL.Service( 6366): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6366): Creating a new PhoneAdapter instance
W/ResourcesManager( 6423): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ActivityManager(  949): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6366): setListener: com.google.android.gms.car.dn@326fa6a8
W/ActivityManager(  949): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6366): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6366): Starting CarCallService with initial phone null
E/WifiStateMachine(  949): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  949): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  949): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@301f8877 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  949): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@301f8877 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper(  949): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  949): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  949): DHCP Start wake lock is acquired.
D/CommandListener(  266): Setting iface cfg
I/Netd    (  266): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  949): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  949): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  266): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  949): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  949): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  949): setSupplicantStateCOMPLETED
D/WifiServerServiceExt(  949): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  949): setSupplicantStateCOMPLETED
D/ConnectivityService(  949): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  949): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  949): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  949): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  949): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  949): ignoring duplicate network state non-change
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  949): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService(  949): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
E/WifiStateMachine(  949): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService(  949): Adding iface wlan0 to network 101
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 13:35:40.822 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 13:35:40.825 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = false, mWifiLevel = 0
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  949): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/WifiHS20(  949): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = true, mWifiLevel = 2
,E/ConnectivityService(  949): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  949): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  266): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  266): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  266): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  266): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 13:35:40.847 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/ConnectivityService(  949): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/libc-netbsd(  266): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  266): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  266): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  266): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  266): netlink response contains error (File exists)
D/ConnectivityService(  949): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  266): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  266): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  949): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  949): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  949): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  949): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  949): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/libc-netbsd(  266): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  266): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  949): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,D/WifiHS20(  949): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 13:35:40.862 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/Nat464Xlat(  949): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  949): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  949): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  949): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  949):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService(  949):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService(  949):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/WifiOffDelayIfNotUsed(  949): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityService(  949):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  949):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  949): currentScore = 0, newScore = 20
D/ConnectivityService(  949):    accepting network in place of null
D/ConnectivityService(  949): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  949): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  949):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  949): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  949): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  949): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyNetworkFactory-1( 1746): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1746):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
,E/ConnectivityService(  949): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  949): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  949): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  949): MasterInitialState.processMessage what=3
D/ConnectivityService(  949): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  949): [e] list.add(nai) empty : false size: 1
W/QCNEJ   ( 1836): |CORE| No family connected
I/QCNEJ   ( 1836): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/ConnectivityService(  949): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
I/QCNEJ   ( 1836): |CORE| sendDefaultNwMsg: default = 1
D/ConnectivityService(  949): validation of new default Network = false
D/ConnectivityService(  949): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  949): enableDataServiceNotify 
D/DSQN    (  949): start dsqn bin
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  949): [LWD] Start DNSResolver start to wait
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
I/[SystemUI]StatusBar.NetworkController( 1370): mWifiConnected = true, mWifiLevel = 2
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1370): Remote
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  949): [LWD] wait 500ms before dns check
,D/ConnectivityService(  949): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  949):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  949):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  949): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1370): CM callback handler got msg 524290
I/NotificationManager( 6366): com.google.android.gms: cancel(10436) by com.google.android.gms
I/DSQN    ( 6449): DSQN samuel.seo ver 141203
E/DSQN    ( 6449): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6449): created command queue thread
I/DSQN    ( 6449): Interface wlan0 address 192.168.1.134 0xc0a80186
V/NetworkPolicy(  949): [LG_RESTRICTED] checkMobilePolicy_type()
I/DSQN    ( 6449): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/TelephonyIcons( 1370): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1370): updateLGTelephonySignalStrength : !hasService()
D/CAR.SERVICE( 6366): Package validated; name: com.android.vending
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/NotificationManager( 6209): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 6209): [1] GearheadStateMonitor.access$100: mIsProjecting:false
D/DhcpStateMachine(  949): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper(  949): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  949): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,I/dhcpcd  ( 6455): version 5.5.6 starting
E/dhcpcd  ( 6455): get_duid: Read-only file system
,I/dhcpcd  ( 6455): wlan0: rebinding lease of 192.168.1.134
,I/Babel_SMS( 6423): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6423): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6423): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6423): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6423): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6423): MmsConfig.loadFromResources
E/Babel_SMS( 6423): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6423): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6423): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6423): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6423): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6423): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6423): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6423): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6423): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6423): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6423): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6423): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6423): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6423): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6423): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6423): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6423): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6423): found sensor: Motion Accel, handle=46
,W/Settings( 6423): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6423): startup - clean
I/art     ( 6423): CheckpointMarkThreadRoots callback created = 0xaaf41980
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  949): android: cancelAsUser(2) by android
I/art     ( 6423): CheckpointMarkThreadRoots callback created = 0xaaf41960
,D/libc-netbsd( 6209): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6209): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6209): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6209): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  266): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  266): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  266): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  266): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  266): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  266): res_queryN name = xxxxx, class = 1, type = 1
I/Babel   ( 6423): deleted: false for 0
,D/libc-netbsd(  266): res_queryN name = xxxxx succeed
,I/System.out( 6209): propertyValue:false
D/libc-netbsd( 6209): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6209): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  949): [LWD] DNSResolver start dns
,I/DSQN    ( 6449): first global connection report this to start monitoring at DSQM.
D/libc-netbsd(  949): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  949): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/DSQN    ( 6449): restart monitoring
D/LGDataListener(  266): argv[0]=dsqncommand
D/LGDataListener(  266): argv[1]=wlan0
D/LGDataListener(  266): argv[2]=1
D/LGDataListener(  266): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 6449): dsqn report finish
D/DSQN    (  949): DSQM DsqnNotification wlan0  1
D/DSQN    (  949): start to monitor internet connection
D/libc-netbsd(  949): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  949): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  266): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  266): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  266): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  266): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  266): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  266): res_queryN name = xxxxx, class = 1, type = 1
V/WiFiOffLoadBroadcast( 6340): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  266): res_queryN name = xxxxx succeed
I/System.out(  949): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  949): [LWD] DNSResolver end dns
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  949): Checking http://clients3.google.com/generate_204 on "NG700"
D/WiFiOffLoadBroadcast( 6340): MCCMNC not supported: null
D/libc-netbsd(  949): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  949): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/PCSuite ( 6395): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6395): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6395): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/libc-netbsd( 6209): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,V/WiFiOffLoadBroadcast( 6340): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/libc-netbsd( 6209): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/AudioCapabilities( 6423): Unsupported mime audio/x-lg-flac
D/WiFiOffLoadBroadcast( 6340): MCCMNC not supported: null
W/AudioCapabilities( 6423): Unsupported mime audio/adpcm
W/AudioCapabilities( 6423): Unsupported mime audio/g726
I/PCSuite ( 6395): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6395): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6395): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,W/AudioCapabilities( 6423): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6423): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6423): Unsupported mime video/mjpg
V/WiFiOffLoadBroadcast( 6340): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6340): MCCMNC not supported: null
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  949): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Feb 2016 12:35:41 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454416541493], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454416541470]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  949): Don't send network conditions - lacking user consent.
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  949): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  949): Validated
,D/ConnectivityService(  949): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  949): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  949):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  949):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  949):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  949): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  949): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  949):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  949):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  949): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  949): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  949): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  949): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  949):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1370): CM callback handler got msg 524290
D/WifiDataContinuityService(  949): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
D/TelephonyNetworkFactory-1( 1746): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1746):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/WifiServerServiceExt(  949): set CMD_CAPTIVE_CHECK_COMPLETED
W/VideoCapabilities( 6423): Unsupported mime video/theora
D/WearableService( 1728): callingUid 10006, callindPid: 1728
,D/TelephonyIcons( 1370): null signal icon name: drawable/stat_sys_signal_null
D/AuthorizationBluetoothService( 1728): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 4305): Restart initialization of location
I/[SystemUI]LGNetworkController( 1370): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
W/AudioCapabilities( 6423): Unsupported mime audio/evrc
W/AudioCapabilities( 6423): Unsupported mime audio/qcelp
W/VideoCapabilities( 6423): Unrecognized profile 2130706433 for video/avc
E/MDM     ( 1728): [146] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
W/AudioCapabilities( 6423): Unsupported mime audio/amr-wb-plus
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/AudioCapabilities( 6423): Unsupported mime audio/qcelp
I/NotificationManager( 1728): com.google.android.gms: cancel(0) by com.google.android.gms
W/AudioCapabilities( 6423): Unsupported mime audio/evrc
V/WiFiOffLoadBroadcast( 6340): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6340): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6340): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/VideoCapabilities( 6423): Unsupported mime video/mp4v-esdp
W/GCoreFlp( 1728): No location to return for getLastLocation()
W/FusedLocationProvider( 1728): location=null
,D/WiFiOffLoadBroadcast( 6340): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6340): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6340): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6340): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6340): MCCMNC not supported: null
I/VideoCapabilities( 6423): Unsupported profile 4 for video/mp4v-es
V/WiFiOffLoadBroadcast( 6340): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6340): MCCMNC not supported: null
W/VideoCapabilities( 6423): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6423): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6423): Unrecognized profile 2130706433 for video/avc
V/WiFiOffLoadBroadcast( 6340): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/VideoCapabilities( 6423): Unrecognized profile 2130706433 for video/avc
D/WiFiOffLoadBroadcast( 6340): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6340): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6340): MCCMNC not supported: null
I/vclib   ( 6423): onServiceConnected
W/Babel   ( 6423): Attempted to change video mute state without an active call.
V/WiFiOffLoadBroadcast( 6340): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6340): MCCMNC not supported: null
,I/NotificationManager( 6423): com.google.android.talk: cancel(10436) by com.google.android.talk
V/WiFiOffLoadBroadcast( 6340): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6340): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6340): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6340): MCCMNC not supported: null
I/PCSuite ( 6395): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6395): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6340): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6340): MCCMNC not supported: null
I/PCSuite ( 6395): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6395): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/ConnectivityService(  949): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/ResourcesManager( 6209): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6209): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6209): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 6209): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  949): RTC_WAKEUP set : Alarm{15cdfcd8 type 0 when 1454416542075 com.android.vending} when 1454416542075
D/DeviceConnectionService( 1728): client connected with version: 8296000
,D/Finsky  ( 6209): [770] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6209): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6209): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/ActivityManager(  949): Process com.google.android.gm (pid 6043) has died
,I/NotificationManager(  949): android: cancelAsUser(2) by android
,D/libc-netbsd( 6209): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6209): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6209): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6209): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  266): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  266): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  266): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  266): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  266): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  266): res_queryN name = xxxxx, class = 1, type = 1
,I/dhcpcd  ( 6455): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
D/libc-netbsd(  266): res_queryN name = xxxxx succeed
,I/System.out( 6209): propertyValue:false
I/dhcpcd  ( 6455): wlan0: leased 192.168.1.134 for 86400 seconds
I/Netd    (  266): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  949): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  949): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  949): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  949): identical MTU - not setting
D/Nat464Xlat(  949): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  949): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  949):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  949):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  949): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  949): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  949): enableDataServiceNotify 
D/DSQN    (  949): start dsqn bin
D/ConnectivityManager.CallbackHandler( 1370): CM callback handler got msg 524295
I/QCNEJ   ( 1836): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 13:35:42.346 DNS addrs= 192.168.1.1, 0.0.0.0, 
,D/DSQN    (  949): dsqn is running restart
,I/DSQN    ( 6498): DSQN samuel.seo ver 141203
E/DSQN    ( 6498): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6498): created command queue thread
I/DSQN    ( 6498): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6498): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,D/ConnectivityService(  949): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  949): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/ProcessCpuTracker(  949): Skipping unknown process pid 6505
,I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.conn.CONNECTIVITY_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/LocSvc_java(  949): onReceive
D/LocSvc_java(  949): got connectivity action
D/LocSvc_java(  949): broadcast - no network connections
D/LocSvc_java(  949): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  949): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  949): onReceive
D/LocSvc_java(  949): got connectivity action
D/LocSvc_java(  949): broadcast - no network connections
,D/LocSvc_java(  949): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  949): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  949): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  949): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  949): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  949): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  949): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  949): ignore wifi update if we are not in OPENING or CLOSING
I/ActivityManager(  949): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6513 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/GpsLocationProvider(  949): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/art     (  301): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 305us total 23.237ms
D/GpsLocationProvider(  949): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/libc-netbsd(  949): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  949): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  949): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  949): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/GpsLocationProvider(  949): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/libc-netbsd(  949): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  949): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  949): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  949): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  949): DHCPV4 succeeded on wlan0
,D/GpsLocationProvider(  949): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LgDhcpStateMachineHelper(  949): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  949): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  949): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  949): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  949): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  949): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  949): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  949): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  949): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  949): RunningState
I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 24.696ms
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 299us total 22.939ms
,I/ActivityManager(  949): Killing 6124:com.android.calendar/u0a13 (adj 15): empty #11
,I/ActivityManager(  949): Process com.google.android.apps.plus (pid 5928) has died
,W/libprocessgroup(  949): failed to open /acct/uid_10013/pid_6124/cgroup.procs: No such file or directory
I/MusicStore( 6513): Database version: 120
,I/ActivityManager(  949): Process com.google.android.talk (pid 6423) has died
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6513): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6513): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6513): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6513): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6513): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,V/JNIHelp ( 6513): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6513): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6513): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1d65eb84: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6513): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6513): GMSCore installation verified
I/ConfigStore( 6513): Config Database version: 1
V/AlarmManager(  949): ELAPSED_WAKEUP set : Alarm{1db4f4dd type 2 when 98372 com.google.android.gms} when 98372
,I/MediaRouter( 6513): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6513): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6513): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6513): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  949): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6547 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/GHttpClientFactory( 6513): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6513): Using platform SSLCertificateSocketFactory
,I/QCNEJ   ( 1836): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-64 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 13:35:43.721 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/art     (  949): Explicit concurrent mark sweep GC freed 78443(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.618ms total 173.829ms
,I/NotificationManager( 6513): com.google.android.music: cancel(1061) by com.google.android.music
,W/ResourcesManager( 6547): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6547): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6547): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,V/WifiInternetCheck(  949): Single check msg out of sync, ignoring.
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/ConnectivityService(  949): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1370): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  949): onReceive
D/LocSvc_java(  949): got connectivity action
D/LocSvc_java(  949): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  949): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  949): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  949): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  949): ignore wifi update if we are not in OPENING or CLOSING
I/NetworkMonitor( 6513): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider(  949): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  949): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/LGEmail ( 6547): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6547): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6547): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  949): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6574 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6547): JNI_OnLoad()
I/HubEmail( 6547): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/HubEmail( 6547): registerNatives()
I/HubEmail( 6547): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6547): registerNativeMethods()
I/HubEmail( 6547): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6547): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 6547): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  949): Process com.android.settings (pid 6340) has died
,D/LGDMClient( 6574): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6574): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6574): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 6574): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6574): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6574): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6574): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6574): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  949): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6611 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
W/ContextImpl( 6574): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 6574): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6574): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6574): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6574): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 6574): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/AppUp4:AppBoxCP( 6611): onCreate
,W/AppUp4:DB( 6611):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6611):  setFingerPrint start
I/AppUp4:DB( 6611):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6611):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6611):  SDK version = 0
I/AppUp4:DB( 6611):  beforefinger == newfinger no write in DB
I/ActivityManager(  949): Process com.google.android.gms:car (pid 6366) has died
,W/ActivityManager(  949): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 1000ms
D/AppUp4:AppBoxApplication( 6611): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6611): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6611): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6611): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6611): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6611): onReceive
I/AppUp4:CustModeStarterReceiver( 6611): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6611): Context : android.app.ReceiverRestrictedContext@a21d1e8
D/AppUp4:CustFacade( 6611): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6611): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6611): begin check event
I/AppUp4:CustModeStarterReceiver( 6611): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6611): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6611): call method handleAsyncCustNotification.
,D/AppUp4:CustModeStarterReceiver( 6611): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6611): handleAsyncCustNotification do not startCustService
I/LgeMiscReceiver( 3195): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3195): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3195): networkInfo.isConnected() = false
D/libc-netbsd(  949): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  949): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  949): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  949): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  266): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  266): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  266): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  266): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  266): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  266): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  949): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6632 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
D/libc-netbsd(  266): res_queryN name = xxxxx succeed
I/System.out(  949): propertyValue:false
,D/libc-netbsd(  949): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  949): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  949): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  949): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  266): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  266): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  266): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  266): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  266): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  266): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  266): res_queryN name = xxxxx succeed
I/System.out(  949): propertyValue:false
I/DSQN    ( 6498): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6498): restart monitoring
D/LGDataListener(  266): argv[0]=dsqncommand
D/LGDataListener(  266): argv[1]=wlan0
D/LGDataListener(  266): argv[2]=1
D/LGDataListener(  266): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  949): DSQM DsqnNotification wlan0  1
D/DSQN    (  949): start to monitor internet connection
,I/DSQN    ( 6498): dsqn report finish
,V/WifiInternetCheck(  949): isHttpConnectionAvailable - We got a valid response : 204
D/PhoneMonitor( 6632): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6632): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6632): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  949): Killing 6257:com.android.providers.calendar/u0a14 (adj 15): empty #11
D/PhoneMonitor( 6632): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6632): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 6632): [parse] Load xml
V/TelephonyAutoProfiling( 6632): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6632): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6632): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  949): failed to open /acct/uid_10014/pid_6257/cgroup.procs: No such file or directory
,V/DownloadManager( 3244): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
I/CheckinService( 4305): Checkin interval check for package: unspecified last checkin: 1454416524065 min interval config: 0 actual interval: 21259
,V/DownloadManager( 3244): DownloadService onCreate
I/DownloadManager( 3244): in removeSpuriousFiles
V/DownloadManager( 3244): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3244): created cursor android.database.sqlite.SQLiteCursor@84dedea on behalf of 3244
,I/DownloadManager( 3244): in trimDatabase
V/DownloadManager( 3244): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,I/NotificationManager( 3244): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3244): created cursor android.database.sqlite.SQLiteCursor@34a7c8db on behalf of 3244
I/ActivityManager(  949): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6661 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/CheckinService( 4305): Checking schedule, now: 1454416545375 next: 1454416554029
I/CheckinService( 4305): active receiver: disabled
V/DownloadManager( 3244): DownloadService onStartCommand
,V/DownloadManager( 3244): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3244): created cursor android.database.sqlite.SQLiteCursor@2c14feb6 on behalf of 3244
V/DownloadManager( 3244): DownloadService onDestroy
,I/ActivityManager(  949): Killing 5816:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 5167): android.os.DeadObjectException
,W/System.err( 5167): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5167): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5167): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5167): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5167): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5167): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5167): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5167): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5167): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5167): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5167): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5167): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5167): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5167): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5167): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5167): android.os.DeadObjectException
W/System.err( 5167): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5167): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5167): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5167): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5167): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5167): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5167): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5167): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5167): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5167): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5167): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5167): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5167): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5167): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5167): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  949): failed to open /acct/uid_10089/pid_5816/cgroup.procs: No such file or directory
W/ActivityManager(  949): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 10248ms
,D/WeatherAncestor( 2688): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:35:45
I/ActivityManager(  949): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6678 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/UpdateThreadPoolManager( 2688): 2 : This is isUpdating : false
D/WeatherAncestor( 2688): connectivity changed - connection : true
D/Weather_cast( 2688): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2688): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:35:45
,D/WeatherService( 2688): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  949): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6695 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  949): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2688): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2688): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2688): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/UEI.SmartControl( 6678): Quickset Services start...
,I/UEI.SmartControl( 6678): Manufacture = LGE
,D/UEI.SmartControl( 6678): File observer start...
I/ActivityManager(  949): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6713 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,E/UEI.SmartControl( 6678): IR Port is disabled: false
D/UEI.SmartControl( 6678): Starting file observer...
,D/UEI.SmartControl( 6678): Extracting JNI libs...
D/UEI.SmartControl( 6678): --- this system supports 32-bit or 64-bit only
,W/ResourcesManager( 6713): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6713): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6695): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/MultiDex( 6713): VM with version 2.1.0 has multidex support
,I/MultiDex( 6713): install
I/MultiDex( 6713): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 6713): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/UEI.SmartControl( 6678): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6678): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6678): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 6678): --- Selecting new region: 2
I/UEI.SmartControl( 6678): -- Running on KitKat(19) and above! JNI will be used.
,W/ActivityThread( 6713): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6713): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@6b651d5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6713): Installed default security provider GmsCore_OpenSSL
D/UEI.SmartControl( 6678): Platform has CIR...
I/NotificationManager( 6713): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6713): com.google.android.gms: cancel(39789) by com.google.android.gms
D/UEI.SmartControl( 6678): NO CIR support, need to check package...
I/UEI.SmartControl( 6678): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6678): QS Service created
D/ChimeraCfgMgr( 6713): Reading stored module config
,E/UEI.SmartControl( 6678): QS start get config
,D/ChimeraCfgMgr( 6713): Loading module com.google.android.gms.car from APK com.google.android.gms
D/UEI.SmartControl( 6678): Loading JNI Libs...
D/UEI.SmartControl( 6678):  configuring local db...
,D/NativeLibraryUtils( 6713): Install completed successfully. count=14 extracted=0
,I/Babel_SMS( 6695): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6695): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6695): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6695): MmsConfig.loadFromDatabase
D/CAR.SERVICE( 6713): Connecting to CarCallService...
,I/ActivityManager(  949): Process com.google.android.music:main (pid 6513) has died
,I/art     ( 6713): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
E/Babel_SMS( 6695): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6695): MmsConfig.loadFromResources
I/art     ( 6713): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
E/Babel_SMS( 6695): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6695): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,I/art     ( 6695): CheckpointMarkThreadRoots callback created = 0xb042d810
D/UEI.SmartControl( 6678):  ---- Has DB8: true
D/UEI.SmartControl( 6678): QS start statue = true Error code = 0
D/UEI.SmartControl( 6678): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6678): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/SensorManager( 6695): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6695): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6695): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6695): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6695): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6695): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6695): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6695): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6695): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6695): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6695): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6695): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6695): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6695): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6695): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6695): found sensor: Motion Accel, handle=46
D/CAR.SERVICE( 6713): com.google.android.projection.gearhead isn't installed.
D/UEI.SmartControl( 6678): IRRCDataComm has AudioManager!!!!.
,D/CAR.TEL.Service( 6713): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 6713): Creating a new PhoneAdapter instance
I/art     ( 6695): CheckpointMarkThreadRoots callback created = 0xb042d800
W/ActivityManager(  949): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6713): setListener: com.google.android.gms.car.dn@326fa6a8
W/ActivityManager(  949): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6713): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6713): Starting CarCallService with initial phone null
W/irrc_jni( 6678): IRRCPlayer_nativeInit ++ 
,D/irrcClient( 6678): IrrcClient ++ 
D/irrcClient( 6678): getIrrcService ++ 
D/irrcClient( 6678): getIrrcService -- 
D/irrcClient( 6678): IrrcClient -- 
W/irrc_jni( 6678): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6678): Services init done
I/NotificationManager( 6713): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/UEI.SmartControl( 6678): QS Service init finished
D/UEI.SmartControl( 6678): QS Service version name: 0.1.73
D/UEI.SmartControl( 6678): QS Service version code: 1073
D/UEI.SmartControl( 6678): Service requested: Control
I/UEI.SmartControl( 6678): Device manager: loading config....
D/UEI.SmartControl( 6678): Config is loaded...
W/Settings( 6695): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
I/Babel_Crash( 6695): startup - clean
D/UEI.SmartControl( 6678): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6678):  ----- QS SDK is ready!!!
,I/ActivityManager(  949): Killing 6395:com.lge.sync/1000 (adj 15): empty #11
D/UEI.SmartControl( 6678): -----IControl: 11
I/UEI.SmartControl( 6678): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6678): Caller: com.lge.qremote
D/UEI.SmartControl( 6678): ------------ IControl registerCallback...
I/UEI.SmartControl( 6678): Registering callback...
D/UEI.SmartControl( 6678): -----IControl: 19
D/UEI.SmartControl( 6678): Caller: com.lge.qremote
I/UEI.SmartControl( 6678): Registering Services Ready callback...
I/UEI.SmartControl( 6678): Notify client services are ready...
D/UEI.SmartControl( 6678): -----IControl: 8
,D/UEI.SmartControl( 6678): Caller: com.lge.qremote
I/Babel   ( 6695): deleted: false for 0
,W/libprocessgroup(  949): failed to open /acct/uid_1000/pid_6395/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 6678): Internal service binding...
I/ActivityManager(  949): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6759 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  949): Killing 5167:com.lge.qremote/u0a106 (adj 15): empty #11
W/libprocessgroup(  949): failed to open /acct/uid_10106/pid_5167/cgroup.procs: No such file or directory
,W/AudioCapabilities( 6695): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6695): Unsupported mime audio/adpcm
W/AudioCapabilities( 6695): Unsupported mime audio/g726
,W/AudioCapabilities( 6695): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6695): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 6695): Unsupported mime video/mjpg
W/VideoCapabilities( 6695): Unsupported mime video/theora
W/AudioCapabilities( 6695): Unsupported mime audio/evrc
,W/AudioCapabilities( 6695): Unsupported mime audio/qcelp
W/VideoCapabilities( 6695): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6695): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6695): Unsupported mime audio/qcelp
W/AudioCapabilities( 6695): Unsupported mime audio/evrc
W/VideoCapabilities( 6695): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6695): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6695): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6695): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6695): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6695): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6695): onServiceConnected
W/Babel   ( 6695): Attempted to change video mute state without an active call.
D/libc-netbsd( 6695): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6695): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6695): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6695): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  266): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  266): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  266): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  266): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd(  266): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  266): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  266): res_queryN name = xxxxx succeed
I/NotificationManager( 6695): com.google.android.talk: cancel(10436) by com.google.android.talk
I/System.out( 6695): propertyValue:false
I/Babel   ( 6695): connection state changed from UNKNOWN to CONNECTED
I/ActivityManager(  949): Killing 6209:com.android.vending/u0a36 (adj 15): empty #11
,I/rmt_storage(  263): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
,I/rmt_storage(  263): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  263): wakelock acquired: 1, error no: 42
I/rmt_storage(  263): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
W/libprocessgroup(  949): failed to open /acct/uid_10036/pid_6209/cgroup.procs: No such file or directory
,I/rmt_storage(  263): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  263): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  263): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  263): 
I/rmt_storage(  263): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6759): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6759): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6759): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6759): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6759): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6759):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6759):   adb logcat -s GAv4
W/GAv4    ( 6759): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/jxcore-log( 6100): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6100): 
,W/GAv4    ( 6759): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6759): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/WebViewFactory( 6759): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6759): Time to load native libraries: 2 ms (timestamps 3248-3250)
I/LibraryLoader( 6759): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6759): Binding Chromium to main looper Looper (main, tid 1) {e705a45}
I/LibraryLoader( 6759): Expected native library version number "",actual native library version number ""
I/chromium( 6759): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6759): Initializing chromium process, singleProcess=true
,W/art     ( 6759): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6759): ApplicationContext is null in ApplicationStatus
I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
W/chromium( 6759): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6759): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6759): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6759): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6759): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6759): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6759): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6759): Remote Branch: 
I/Adreno-EGL( 6759): Local Patches: 
I/Adreno-EGL( 6759): Reconstruct Branch: 
V/AudioPolicyService(  272): registerClient() client 0xb4027800, uid 10079
,I/NSApplication( 6759): Starting up...
W/AudioManagerAndroid( 6759): Requires BLUETOOTH permission
I/ActivityManager(  949): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6822 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  949): Killing 6547:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  949): failed to open /acct/uid_10021/pid_6547/cgroup.procs: No such file or directory
,I/ActivityManager(  949): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6844 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  949): Killing 6574:com.lge.lgdmsclient/1000 (adj 15): empty #11
,I/jxcore-log( 6100): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6100): 
I/art     (  301): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 26.518ms
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 30.429ms
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 21.122ms
I/jxcore-log( 6100): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6100): 
,I/jxcore-log( 6100): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6100): 
W/libprocessgroup(  949): failed to open /acct/uid_1000/pid_6574/cgroup.procs: No such file or directory
,V/AlarmManager(  949): RTC_WAKEUP set : Alarm{207261f6 type 0 when 1454416548892 com.google.android.googlequicksearchbox} when 1454416548892
I/jxcore-log( 6100): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6100): 
,I/jxcore-log( 6100): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6100): 
,W/ResourcesManager( 6844): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/jxcore-log( 6100): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6100): 
,I/jxcore-log( 6100): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6100): 
I/ActivityManager(  949): Killing 6611:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  949): failed to open /acct/uid_10011/pid_6611/cgroup.procs: No such file or directory
,I/ActivityManager(  949): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6886 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/MusicStore( 6886): Database version: 120
,I/ActivityManager(  949): Process com.google.android.gms:car (pid 6713) has died
W/ActivityManager(  949): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 4000ms
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6886): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6886): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6886): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6886): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6886): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6886): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6886): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6886): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1d65eb84: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6886): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6886): GMSCore installation verified
,I/ConfigStore( 6886): Config Database version: 1
,I/MediaRouter( 6886): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/art     (  949): Explicit concurrent mark sweep GC freed 28626(1462KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.277ms total 147.891ms
,V/MusicLeanback( 6886): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6886): type=WIFI subType= reason=null isConnected=true
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/NetworkMonitor( 6886): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  949): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6924 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6886): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6886): Using platform SSLCertificateSocketFactory
,I/NotificationManager( 6886): com.google.android.music: cancel(1061) by com.google.android.music
,W/ResourcesManager( 6924): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6924): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6924): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/LGEmail ( 6924): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6924): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6924): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  949): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6954 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6924): JNI_OnLoad()
I/HubEmail( 6924): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6924): registerNatives()
I/HubEmail( 6924): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6924): registerNativeMethods()
I/HubEmail( 6924): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/art     ( 6924): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  949): Killing 6632:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  949): failed to open /acct/uid_10038/pid_6632/cgroup.procs: No such file or directory
,W/Settings( 6924): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 6954): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6954): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6954): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6954): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6954): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6954): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6954): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6954): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  949): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6978 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/UEI.SmartControl( 6678): Internal timer expired: 1
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/UEI.SmartControl( 6678): Service.onUnbind: IControl
D/UEI.SmartControl( 6678): Service.onDestroy
D/UEI.SmartControl( 6678): Shutdown IRRCPlayer... 
W/ContextImpl( 6954): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 6954): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6954): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
,D/LGDMClient( 6954): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6954): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6954): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
W/irrc_jni( 6678): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6678): ~IrrcClient ++ 
D/irrcClient( 6678): ~IrrcClient -- 
W/irrc_jni( 6678): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6678): Blaster closed
D/UEI.SmartControl( 6678): Blaster closed
D/UEI.SmartControl( 6678): Shut down QS...
D/UEI.SmartControl( 6678): Stopped file observer...
I/UEI.SmartControl( 6678): QS lib stop result = true
D/UEI.SmartControl( 6678): QS shutdown complete
I/ActivityManager(  949): Killing 6661:com.lge.drmservice/u0a51 (adj 15): empty #11
,I/AppUp4:AppBoxCP( 6978): onCreate
,W/AppUp4:DB( 6978):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6978):  setFingerPrint start
I/AppUp4:DB( 6978):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6978):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6978):  SDK version = 0
I/AppUp4:DB( 6978):  beforefinger == newfinger no write in DB
W/libprocessgroup(  949): failed to open /acct/uid_10051/pid_6661/cgroup.procs: No such file or directory
,D/AppUp4:AppBoxApplication( 6978): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 6978): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6978): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6978): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 6978): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6978): onReceive
I/AppUp4:CustModeStarterReceiver( 6978): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 6978): Context : android.app.ReceiverRestrictedContext@a21d1e8
,D/AppUp4:CustFacade( 6978): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6978): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6978): begin check event
I/AppUp4:CustModeStarterReceiver( 6978): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6978): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 6978): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6978): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6978): handleAsyncCustNotification do not startCustService
I/ActivityManager(  949): Killing 6678:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/libprocessgroup(  949): failed to open /acct/uid_10089/pid_6678/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3195): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3195): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3195): networkInfo.isConnected() = false
I/ActivityManager(  949): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7005 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7005): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7005): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7005): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  949): Killing 6695:com.google.android.talk/u0a61 (adj 15): empty #11
,D/PhoneMonitor( 7005): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7005): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7005): [parse] Load xml
V/TelephonyAutoProfiling( 7005): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7005): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7005): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  949): failed to open /acct/uid_10061/pid_6695/cgroup.procs: No such file or directory
V/DownloadManager( 3244): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3244): DownloadService onCreate
I/NotificationManager( 3244): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3244): in removeSpuriousFiles
V/DownloadManager( 3244): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3244): created cursor android.database.sqlite.SQLiteCursor@1bc7e68d on behalf of 3244
I/DownloadManager( 3244): in trimDatabase
V/DownloadManager( 3244): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3244): created cursor android.database.sqlite.SQLiteCursor@1a6a5042 on behalf of 3244
I/ActivityManager(  949): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7027 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3244): DownloadService onStartCommand
V/DownloadManager( 3244): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3244): created cursor android.database.sqlite.SQLiteCursor@2b82b590 on behalf of 3244
I/CheckinService( 4305): Checkin interval check for package: unspecified last checkin: 1454416524065 min interval config: 0 actual interval: 28487
,I/CheckinService( 4305): Checking schedule, now: 1454416552565 next: 1454416554029
I/CheckinService( 4305): active receiver: disabled
,V/DownloadManager( 3244): DownloadService onDestroy
I/ActivityManager(  949): Killing 6759:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,E/libprocessgroup(  949): failed to kill 1 processes for processgroup 6759
,D/WeatherAncestor( 2688): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:35:52
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/UpdateThreadPoolManager( 2688): 2 : This is isUpdating : false
D/WeatherAncestor( 2688): connectivity changed - connection : true
D/Weather_cast( 2688): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2688): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:35:52
D/WeatherService( 2688): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  949): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7048 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  949): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2688): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2688): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2688): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 7048): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,I/Babel_SMS( 7048): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7048): MmsConfig.loadMmsSettings
I/Babel_SMS( 7048): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7048): MmsConfig.loadFromDatabase
E/Babel_SMS( 7048): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7048): MmsConfig.loadFromResources
E/Babel_SMS( 7048): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7048): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 7048): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7048): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7048): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7048): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7048): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7048): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7048): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7048): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7048): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7048): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7048): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7048): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7048): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7048): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7048): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7048): found sensor: Motion Accel, handle=46
,W/Settings( 7048): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 7048): startup - clean
,I/Babel   ( 7048): deleted: false for 0
,I/art     ( 7048): CheckpointMarkThreadRoots callback created = 0xaaf3a930
,I/art     ( 7048): CheckpointMarkThreadRoots callback created = 0xaaf3a910
,I/ActivityManager(  949): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7085 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 7048): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 7048): Unsupported mime audio/adpcm
,W/AudioCapabilities( 7048): Unsupported mime audio/g726
W/AudioCapabilities( 7048): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7048): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7048): Unsupported mime video/mjpg
W/VideoCapabilities( 7048): Unsupported mime video/theora
,W/AudioCapabilities( 7048): Unsupported mime audio/evrc
W/AudioCapabilities( 7048): Unsupported mime audio/qcelp
W/VideoCapabilities( 7048): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7048): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7048): Unsupported mime audio/qcelp
W/AudioCapabilities( 7048): Unsupported mime audio/evrc
W/VideoCapabilities( 7048): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 7048): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7048): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7048): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7048): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7048): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7048): onServiceConnected
W/Babel   ( 7048): Attempted to change video mute state without an active call.
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7085): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
I/NotificationManager( 7048): com.google.android.talk: cancel(10436) by com.google.android.talk
W/ContextImpl( 7085): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7085): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7085):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7085):   adb logcat -s GAv4
D/libc-netbsd( 7048): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7048): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7048): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7048): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  266): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  266): App 10061 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  266): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  266): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  266): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  266): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  266): res_queryN name = xxxxx succeed
I/System.out( 7048): propertyValue:false
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7085): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7085): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 7085): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/Babel   ( 7048): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  949): Killing 6822:com.android.chrome/u0a48 (adj 15): empty #11
W/GAv4    ( 7085): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7085): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/libprocessgroup(  949): failed to open /acct/uid_10048/pid_6822/cgroup.procs: No such file or directory
,I/WebViewFactory( 7085): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7085): Time to load native libraries: 2 ms (timestamps 9220-9222)
I/LibraryLoader( 7085): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7085): Binding Chromium to main looper Looper (main, tid 1) {e705a45}
I/LibraryLoader( 7085): Expected native library version number "",actual native library version number ""
I/chromium( 7085): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7085): Initializing chromium process, singleProcess=true
W/art     ( 7085): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7085): ApplicationContext is null in ApplicationStatus
W/chromium( 7085): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7085): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7085): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7085): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7085): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7085): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7085): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7085): Remote Branch: 
I/Adreno-EGL( 7085): Local Patches: 
I/Adreno-EGL( 7085): Reconstruct Branch: 
I/ActivityManager(  949): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7136 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/NSApplication( 7085): Starting up...
,V/AudioPolicyService(  272): registerClient() client 0xb4027140, uid 10079
W/AudioManagerAndroid( 7085): Requires BLUETOOTH permission
,W/ResourcesManager( 7136): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7136): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  949): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7165 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  949): Killing 6844:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/MultiDex( 7136): VM with version 2.1.0 has multidex support
I/MultiDex( 7136): install
I/MultiDex( 7136): VM has multidex support, MultiDex support library is disabled.
,W/libprocessgroup(  949): failed to open /acct/uid_10086/pid_6844/cgroup.procs: No such file or directory
V/JNIHelp ( 7136): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7136): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7136): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@6b651d5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7136): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  949): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7191 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/NotificationManager( 7136): com.google.android.gms: cancel(10436) by com.google.android.gms
I/art     (  301): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 21.147ms
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 20.467ms
,I/NotificationManager( 7136): com.google.android.gms: cancel(39789) by com.google.android.gms
I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 21.365ms
,D/ChimeraCfgMgr( 7136): Reading stored module config
,W/ResourcesManager( 7191): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/ChimeraCfgMgr( 7136): Loading module com.google.android.gms.car from APK com.google.android.gms
,D/CAR.SERVICE( 7136): Connecting to CarCallService...
,I/art     ( 7136): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7136): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 7136): com.google.android.projection.gearhead isn't installed.
,I/ActivityManager(  949): Killing 6886:com.google.android.music:main/u0a81 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/NativeLibraryUtils( 7136): Install completed successfully. count=14 extracted=0
W/libprocessgroup(  949): failed to open /acct/uid_10081/pid_6886/cgroup.procs: No such file or directory
,D/CAR.TEL.Service( 7136): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 7136): Creating a new PhoneAdapter instance
W/ActivityManager(  949): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 7136): setListener: com.google.android.gms.car.dn@326fa6a8
W/ActivityManager(  949): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 7136): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 7136): Starting CarCallService with initial phone null
I/ActivityManager(  949): Killing 6924:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  949): failed to open /acct/uid_10021/pid_6924/cgroup.procs: No such file or directory
,I/NotificationManager( 7136): com.google.android.gms: cancel(10436) by com.google.android.gms
I/ActivityManager(  949): Killing 6954:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  949): failed to open /acct/uid_1000/pid_6954/cgroup.procs: No such file or directory
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  266): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  266): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  266): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  266): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  266): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  266): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  949): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7227 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  266): res_queryN name = xxxxx succeed
I/System.out( 1728): propertyValue:false
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/MusicStore( 7227): Database version: 120
,I/art     ( 5566): Explicit concurrent mark sweep GC freed 1818(66KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 398us total 28.873ms
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7227): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7227): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7227): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7227): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7227): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7227): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7227): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7227): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1d65eb84: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7227): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7227): GMSCore installation verified
,I/ConfigStore( 7227): Config Database version: 1
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/art     (  949): Explicit concurrent mark sweep GC freed 18933(900KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.661ms total 158.378ms
,V/AlarmManager(  949): RTC_WAKEUP set : Alarm{1616a244 type 0 when 1454416554029 com.google.android.gms} when 1454416554029
,I/ActivityManager(  949): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7255 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  949): RTC_WAKEUP set : Alarm{11abff2d type 0 when 1454416555971 com.android.vending} when 1454416555971
,I/MediaRouter( 7227): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7227): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7227): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7227): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  949): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7274 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7227): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7227): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 7274): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7274): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7274): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/NotificationManager( 7227): com.google.android.music: cancel(1061) by com.google.android.music
,I/ActivityManager(  949): Process com.google.android.talk (pid 7048) has died
,I/LGEmail ( 7274): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 7274): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/Finsky  ( 7255): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/eas_req ( 7274): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  949): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7314 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/HubEmail( 7274): JNI_OnLoad()
I/HubEmail( 7274): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7274): registerNatives()
I/HubEmail( 7274): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7274): registerNativeMethods()
I/HubEmail( 7274): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7274): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 7274): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/Finsky  ( 7255): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 7255): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7255): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 7255): com.android.vending: cancel(-1050172287) by com.android.vending
D/LGDMClient( 7314): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7314): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7314): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 7314): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
I/NetworkStateForAutoUpdateMonitor( 6978): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6978): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6978): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6978): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6978): onReceive
I/AppUp4:CustModeStarterReceiver( 6978): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6978): Context : android.app.ReceiverRestrictedContext@a21d1e8
D/AppUp4:CustFacade( 6978): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6978): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6978): begin check event
I/AppUp4:CustModeStarterReceiver( 6978): Event For GoodConnectivity, noConnectivity : false, but skip! 
I/LgeMiscReceiver( 3195): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3195): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3195): networkInfo.isConnected() = true
D/PhoneState( 3195): setPdpRejectCasuse : false
D/LGDMClient( 7314): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/MobileConnectivityChangeReceiver( 7005): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7005): onReceive CONNECTIVITY_CHANGE networkType=1
D/LGDMClient( 7314): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7314): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,V/DownloadManager( 3244): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3244): DownloadService onCreate
D/Finsky  ( 7255): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/WeatherAncestor( 2688): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:35:56
D/Finsky  ( 7255): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7255): Skipping gmscore version check
I/ActivityManager(  949): Killing 7085:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
I/LGDMClient( 7314): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3244): in removeSpuriousFiles
I/NotificationManager( 3244): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3244): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3244): created cursor android.database.sqlite.SQLiteCursor@12d12e8e on behalf of 3244
,V/DownloadManager( 3244): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 3244): in trimDatabase
V/DownloadManager( 3244): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3244): created cursor android.database.sqlite.SQLiteCursor@33859abc on behalf of 3244
V/DownloadManager( 3244): created cursor android.database.sqlite.SQLiteCursor@e705a45 on behalf of 7255
E/libprocessgroup(  949): failed to kill 1 processes for processgroup 7085
,D/UpdateThreadPoolManager( 2688): 2 : This is isUpdating : false
D/WeatherAncestor( 2688): connectivity changed - connection : true
D/Weather_cast( 2688): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2688): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:35:57
V/DownloadManager( 3244): DownloadService onStartCommand
V/DownloadManager( 3244): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/WeatherService( 2688): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 7314): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3244): created cursor android.database.sqlite.SQLiteCursor@3fe89ecb on behalf of 3244
,D/Finsky  ( 7255): [910] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 7255): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager(  949): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7352 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  949): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2688): 2 : Utils getTopActivity com.lge.launcher2 / true
V/DownloadManager( 3244): DownloadService onDestroy
,I/ActivityManager(  949): Killing 7165:com.android.chrome/u0a48 (adj 15): empty #11
D/WeatherService( 2688): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2688): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
E/LGDMClient( 7314): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7314): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7314): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMClient( 7314): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7314): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
W/libprocessgroup(  949): failed to open /acct/uid_10048/pid_7165/cgroup.procs: No such file or directory
,I/ActivityManager(  949): Killing 7136:com.google.android.gms:car/u0a6 (adj 15): empty #11
,D/Finsky  ( 7255): [1] GmsCoreHelper.cleanupNlp: result=false type=4
W/ResourcesManager( 7352): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/libprocessgroup(  949): failed to open /acct/uid_10006/pid_7136/cgroup.procs: No such file or directory
W/ActivityManager(  949): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 16000ms
,D/Finsky  ( 7255): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Babel_SMS( 7352): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7352): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7352): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7352): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7352): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7352): MmsConfig.loadFromResources
E/Babel_SMS( 7352): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7352): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7352): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7352): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7352): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7352): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7352): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7352): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7352): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7352): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7352): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7352): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7352): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7352): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7352): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7352): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7352): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7352): found sensor: Motion Accel, handle=46
,W/Settings( 7352): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7352): startup - clean
I/art     ( 7352): CheckpointMarkThreadRoots callback created = 0xb042d5a0
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/Babel   ( 7352): deleted: false for 0
,I/art     ( 7352): CheckpointMarkThreadRoots callback created = 0xb042d580
,I/ActivityManager(  949): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7390 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 7352): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7352): Unsupported mime audio/adpcm
W/AudioCapabilities( 7352): Unsupported mime audio/g726
W/AudioCapabilities( 7352): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 7352): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 7352): Unsupported mime video/mjpg
W/VideoCapabilities( 7352): Unsupported mime video/theora
W/AudioCapabilities( 7352): Unsupported mime audio/evrc
,W/AudioCapabilities( 7352): Unsupported mime audio/qcelp
W/VideoCapabilities( 7352): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7352): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7352): Unsupported mime audio/qcelp
,W/AudioCapabilities( 7352): Unsupported mime audio/evrc
W/VideoCapabilities( 7352): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7352): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7352): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7352): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7352): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7352): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7352): onServiceConnected
W/Babel   ( 7352): Attempted to change video mute state without an active call.
I/NotificationManager( 7352): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
D/libc-netbsd( 7352): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7352): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7352): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7352): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  266): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  266): App 10061 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  266): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  266): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  266): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  266): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  266): res_queryN name = xxxxx succeed
I/System.out( 7352): propertyValue:false
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7390): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/GAv4    ( 7390): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7390):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7390):   adb logcat -s GAv4
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7390): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7390): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
W/GAv4    ( 7390): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7390): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/Babel   ( 7352): connection state changed from UNKNOWN to CONNECTED
,W/GAv4    ( 7390): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
I/ActivityManager(  949): Killing 7191:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/GAv4    ( 7390): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  949): failed to open /acct/uid_10086/pid_7191/cgroup.procs: No such file or directory
,I/WebViewFactory( 7390): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7390): Time to load native libraries: 3 ms (timestamps 3766-3769)
I/LibraryLoader( 7390): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7390): Binding Chromium to main looper Looper (main, tid 1) {e705a45}
,I/LibraryLoader( 7390): Expected native library version number "",actual native library version number ""
I/chromium( 7390): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7390): Initializing chromium process, singleProcess=true
W/art     ( 7390): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7390): ApplicationContext is null in ApplicationStatus
W/chromium( 7390): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 7390): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7390): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7390): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7390): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7390): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7390): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7390): Remote Branch: 
I/Adreno-EGL( 7390): Local Patches: 
I/Adreno-EGL( 7390): Reconstruct Branch: 
I/jxcore-log( 6100): Test app app.js loaded
I/jxcore-log( 6100): 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6100): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6100): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6100): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6100): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6100): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6100): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6100): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6100): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6100): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6100): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ea6a294 added. We now have 1 listener(s)
,D/BluetoothAdapterService(626782439)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@23c734f5
I/jxcore-log( 6100): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6100): 
,I/chromium( 6100): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/NSApplication( 7390): Starting up...
,V/AudioPolicyService(  272): registerClient() client 0xb4027180, uid 10079
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/AudioManagerAndroid( 7390): Requires BLUETOOTH permission
,I/ActivityManager(  949): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7456 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  949): Killing 7227:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  949): failed to open /acct/uid_10081/pid_7227/cgroup.procs: No such file or directory
,I/ActivityManager(  949): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7475 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  949): Killing 7274:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  949): failed to open /acct/uid_10021/pid_7274/cgroup.procs: No such file or directory
,W/ResourcesManager( 7475): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  949): Killing 6978:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  949): failed to open /acct/uid_10011/pid_6978/cgroup.procs: No such file or directory
,D/GCM     ( 1728): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/LocationInitializer( 4305): Restart initialization of location
,D/WearableService( 1728): callingUid 10006, callindPid: 1728
D/AuthorizationBluetoothService( 1728): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/MDM     ( 1728): [102] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/NotificationManager( 1728): com.google.android.gms: cancel(0) by com.google.android.gms
I/ActivityManager(  949): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7506 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/GCoreFlp( 1728): No location to return for getLastLocation()
W/FusedLocationProvider( 1728): location=null
,W/ResourcesManager( 7506): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  949): Message: 20
D/BluetoothManagerService(  949): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3ffc83c4:true
,D/BluetoothAdapterService(626782439)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@23c734f5
D/BluetoothAdapterService(626782439)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@23c734f5
I/ActivityManager(  949): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7533 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7506): Create singleton instance
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/AudioManager( 7506): getMode name:com.lge.qremote
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
,I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/art     (  949): Explicit concurrent mark sweep GC freed 25380(1151KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.678ms total 167.047ms
,D/WeatherService( 2688): 2 : TimeTick Intent has been received, Time(hour:min:sec) 13:36:0
,D/WeatherService( 2688): 2 : TimeTick Intent And Screen On
D/WeatherService( 2688): 2 : SDK version : 21
W/ActivityManager(  949): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2688): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2688): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2688): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2688): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2688): 2 : This is isUpdating : false
D/WeatherService( 2688): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2688): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2688): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2688): 2 : Fixed theme : optimus
D/GCM     ( 1728): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/WeatherReflect( 2688): 2 : Map key string is -2
,D/lim     ( 2688): 2 : time = 13:36
,E/MDM     ( 1728): [139] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/WeatherReflect( 2688): Model Name : LG-D722
D/WeatherTheme( 2688): 2 : Different view - status_min_formatted : 35 != 36
D/WeatherTheme( 2688): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2688): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/AuthorizationBluetoothService( 1728): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/Theme   ( 2688): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2688): currentPackage=com.lge.sizechangable.weather.theme.optimus
D/LocationInitializer( 4305): Restart initialization of location
,D/UEI.SmartControl( 7533): Quickset Services start...
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1728): com.google.android.gms: cancel(0) by com.google.android.gms
I/UEI.SmartControl( 7533): Manufacture = LGE
D/UEI.SmartControl( 7533): File observer start...
,E/UEI.SmartControl( 7533): IR Port is disabled: false
D/UEI.SmartControl( 7533): Starting file observer...
D/UEI.SmartControl( 7533): Extracting JNI libs...
D/UEI.SmartControl( 7533): --- this system supports 32-bit or 64-bit only
W/GCoreFlp( 1728): No location to return for getLastLocation()
W/FusedLocationProvider( 1728): location=null
D/sensors_hal_Time(  949): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  949): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  949): tsOffsetIs: Apps: 115259122564; DSPS: 3875740; Offset : -3027935183
D/Weather4x2_optimus( 2688): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
,D/Weather4x2_optimus( 2688): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2688): forecast size is 0
D/Theme   ( 2688): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2688): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2688): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2688): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2688): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2688): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2688): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2688): url is : null
D/Theme   ( 2688): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2688): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2688): 2 : update view, appWidgetId: 2
,D/WeatherService( 2688): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 13:36:0
I/CheckinService( 4305): Checkin interval check for package: unspecified last checkin: 1454416524065 min interval config: 0 actual interval: 36222
,I/AudioManager( 7506): getMode name:com.lge.qremote
I/CheckinService( 4305): Checking schedule, now: 1454416560312 next: 1454416554029
I/CheckinService( 4305): active receiver: enabled
,W/ContextImpl( 3614): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/CheckinService( 4305): Preparing to send checkin request
I/EventLogService( 4305): Accumulating logs since 1454416515204
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1874): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/CheckinRequestBuilder( 4305): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 4305): Failed to find provider info for com.google.android.wearable.settings
D/UEI.SmartControl( 7533): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7533): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7533): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1874): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/UEI.SmartControl( 7533): --- Selecting new region: 2
I/UEI.SmartControl( 7533): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7533): Platform has CIR...
D/UEI.SmartControl( 7533): NO CIR support, need to check package...
I/UEI.SmartControl( 7533): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7533): QS Service created
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/UEI.SmartControl( 7533): QS start get config
,D/UEI.SmartControl( 7533): Loading JNI Libs...
,D/UEI.SmartControl( 7533):  configuring local db...
I/ActivityManager(  949): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7576 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/art     (  301): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 21.028ms
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 21.117ms
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 21.865ms
,W/ResourcesManager( 7576): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7576): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 7576): VM with version 2.1.0 has multidex support
I/MultiDex( 7576): install
I/MultiDex( 7576): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7576): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/UEI.SmartControl( 7533):  ---- Has DB8: true
,D/UEI.SmartControl( 7533): QS start statue = true Error code = 0
D/UEI.SmartControl( 7533): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7533): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
W/ActivityThread( 7576): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7576): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@6b651d5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7576): Installed default security provider GmsCore_OpenSSL
D/UEI.SmartControl( 7533): IRRCDataComm has AudioManager!!!!.
I/NotificationManager( 7576): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7576): com.google.android.gms: cancel(39789) by com.google.android.gms
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,E/MDM     ( 1728): [146] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 4305): Restart initialization of location
W/irrc_jni( 7533): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7533): IrrcClient ++ 
D/irrcClient( 7533): getIrrcService ++ 
D/irrcClient( 7533): getIrrcService -- 
D/irrcClient( 7533): IrrcClient -- 
W/irrc_jni( 7533): IRRCPlayer_nativeInit -- 
,D/AuthorizationBluetoothService( 1728): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/UEI.SmartControl( 7533): Services init done
,D/UEI.SmartControl( 7533): QS Service init finished
D/UEI.SmartControl( 7533): QS Service version name: 0.1.73
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1728): com.google.android.gms: cancel(0) by com.google.android.gms
D/UEI.SmartControl( 7533): QS Service version code: 1073
,I/UEI.SmartControl( 7533): Device manager: loading config....
W/GCoreFlp( 1728): No location to return for getLastLocation()
D/UEI.SmartControl( 7533): Service requested: Control
W/FusedLocationProvider( 1728): location=null
I/art     ( 7576): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7576): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/UEI.SmartControl( 7533): Config is loaded...
,D/UEI.SmartControl( 7533): Request IControl service: devices are loaded...
D/UEI.SmartControl( 7533): -----IControl: 11
D/UEI.SmartControl( 7533): Caller: com.lge.qremote
D/UEI.SmartControl( 7533): ------------ IControl registerCallback...
I/UEI.SmartControl( 7533): Registering callback...
,D/UEI.SmartControl( 7533): -----IControl: 19
D/UEI.SmartControl( 7533): Caller: com.lge.qremote
I/UEI.SmartControl( 7533): Registering Services Ready callback...
D/UEI.SmartControl( 7533): Internal service binding...
,D/NativeLibraryUtils( 7576): Install completed successfully. count=14 extracted=0
,D/UEI.SmartControl( 7533):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 7533): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7533): -----IControl: 8
D/UEI.SmartControl( 7533): Caller: com.lge.qremote
,I/AudioManager( 7506): getMode name:com.lge.qremote
I/ActivityManager(  949): Killing 7027:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  949): failed to open /acct/uid_10051/pid_7027/cgroup.procs: No such file or directory
,I/AudioManager( 7506): getMode name:com.lge.qremote
,I/MusicWidget( 2580): mDelayedStopHandler : unbind
,I/AudioManager( 7506): getMode name:com.lge.qremote
,D/WVCdm   (  272): Instantiating CDM.
I/WVCdm   (  272): CdmEngine::OpenSession
I/WVCdm   (  272): Level3 Library Dec 11 2014 16:13:16
I/MusicBrowser( 2719): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2719): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2719): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2719): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2719): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2719): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2719): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2719): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  949):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@da32b71com.lge.music.MediaPlaybackService$6@101c1d56
,D/MusicBrowser( 2719): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
,I/MusicBrowser( 2719): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2719): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2719): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
W/WVCdm   (  272): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  272): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  272): L1 library not specified. Falling Back to L3
,I/MusicBrowser( 2719): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@25362494
I/MusicBrowser( 2719): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2719): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2719): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2719): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2719): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2719): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2719): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2719): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2719): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2719): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2719): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2719): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2719): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2719): reset
,V/MediaPlayer[Native]( 2719): setListener
V/MediaPlayer[Native]( 2719): disconnect
V/MediaPlayer[Native]( 2719): destructor
V/AudioFlinger(  272): releasing 18 from 2719 for -1
V/AudioFlinger(  272):  decremented refcount to 0
V/AudioFlinger(  272): purging stale effects
V/MediaPlayer[Native]( 2719): disconnect
D/MusicBrowser( 2719): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2719): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2719): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2719): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2719): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2719): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2719): [SmartShareManagerClient] unregisterListener: 862773719
W/SmartShareClient( 2719): [SmartShareManagerClient] unregisterListener invalid listener: 862773719
I/SmartShareClient( 2719): [SmartShareManagerClient] terminate service: 2719/MediaPlaybackService/1072205530
E/HomeCloudIF( 2719): unregiterHomeCloudBroadcast(), Illegal argument.
I/WVCdm   (  272): CdmEngine::QueryKeyControlInfo
I/SmartShareClient( 2719): [SmartShareManagerClient] unbindService context:android.app.Application@1575dac4
W/WVCdm   (  272): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  272): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  272): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  272): PrepareKeyRequest: nonce=3055700067
V/CloudHub( 2719): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2719): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2719): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2719): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2719): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  949): Killing 7314:com.lge.lgdmsclient/1000 (adj 15): empty #11
I/CloudHub( 2719): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29986
,W/libprocessgroup(  949): failed to open /acct/uid_1000/pid_7314/cgroup.procs: No such file or directory
,I/art     ( 7576): CheckpointMarkThreadRoots callback created = 0xb04cbeb0
,I/art     ( 7576): CheckpointMarkThreadRoots callback created = 0xb04cbea0
,I/WVCdm   (  272): CdmEngine::OpenSession
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,I/WVCdm   (  272): CdmEngine::CloseSession
,I/WVCdm   (  272): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  272): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  272): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  272): CdmEngine::GenerateKeyRequest
D/WVCdm   (  272): PrepareKeyRequest: nonce=3224939645
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/WVCdm   (  272): CdmEngine::CloseSession
,I/WVCdm   (  272): L3 Terminate.
,I/dex2oat ( 7633): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=40 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7633): dex2oat took 87.359ms (threads: 4)
,I/Adreno-EGL( 7576): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7576): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7576): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7576): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7576): Remote Branch: 
I/Adreno-EGL( 7576): Local Patches: 
I/Adreno-EGL( 7576): Reconstruct Branch: 
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/UEI.SmartControl( 7533): Internal timer expired: 1
,I/Adreno-EGL( 7576): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7576): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7576): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7576): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7576): Remote Branch: 
I/Adreno-EGL( 7576): Local Patches: 
I/Adreno-EGL( 7576): Reconstruct Branch: 
,I/Adreno-EGL( 7576): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7576): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7576): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7576): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7576): Remote Branch: 
I/Adreno-EGL( 7576): Local Patches: 
I/Adreno-EGL( 7576): Reconstruct Branch: 
,I/CheckinRequestBuilder( 4305): Classify the device as Phone.
,D/libc-netbsd( 4305): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4305): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4305): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4305): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  266): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  266): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  266): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  266): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  266): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  266): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  266): res_queryN name = xxxxx succeed
I/System.out( 4305): propertyValue:false
D/libc-netbsd( 4305): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4305): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4305): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4305): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4305): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4305): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 4305): Sending checkin request (9768 bytes)
,I/CheckinRequestBuilder( 4305): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4305): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinRequestBuilder( 4305): Classify the device as Phone.
,I/CheckinTask( 4305): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4305): Checking schedule, now: 1454416567335 next: 1454943816331
I/CheckinService( 4305): active receiver: disabled
,D/CheckinService( 4305): Recording last checkin time for package unspecified as 1454416567357
I/ActivityManager(  949): Killing 7255:com.android.vending/u0a36 (adj 15): empty #11
,W/libprocessgroup(  949): failed to open /acct/uid_10036/pid_7255/cgroup.procs: No such file or directory
,V/SetupWizard( 7005): Connected to Gservices successfully
I/ActivityManager(  949): Killing 7390:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,W/libprocessgroup(  949): failed to open /acct/uid_10079/pid_7390/cgroup.procs: No such file or directory
,D/GCM     ( 1728): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ThermalEngine(  292): Sensor:pa_therm0:34000 mC
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]QPairHandler( 1370): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[SystemUI]QSlideListController( 1370): onReceive = android.intent.action.PACKAGE_CHANGED
,W/[SystemUI]QSlideLoader( 1370): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1370): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
I/QCNEJ   ( 1836): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,W/[SystemUI]QSlideLoader( 1370): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1370): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/[LGHome]EVENT( 1874): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/InputReader(  949): Reconfiguring input devices.  changes=0x00000010
I/[LGHome]LGPlusHomeDBManager( 1874): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1874): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
D/administrator(  949): Handling package changes for user 0
,I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/ActivityManager(  949): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7677 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/NotificationManager( 7352): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 7352): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7352): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7352): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppUp4:AppBoxCP( 7677): onCreate
W/AppUp4:DB( 7677):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7677):  setFingerPrint start
I/AppUp4:DB( 7677):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 7677):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7677):  SDK version = 0
I/AppUp4:DB( 7677):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7677): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7677): onReceive
I/AppUp4:CustModeStarterReceiver( 7677): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 7677): Context : android.app.ReceiverRestrictedContext@15e42085
D/AppUp4:CustFacade( 7677): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7677): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7677): begin check event
I/AppUp4:CustModeStarterReceiver( 7677): Event For Nothing, skip.
W/System  ( 7352): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7352): Installed default security provider GmsCore_OpenSSL
,I/NotificationService(  949): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  949): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  949): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/ActivityManager(  949): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7700 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/BackupManagerService(  949): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/BackupManagerService(  949): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  949): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3c470880
,D/LCardEmulationManager( 1783): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1783): getDefaultRoute
,W/ResourcesManager( 7700): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7700): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7700): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager(  949): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType(  949): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/AppConfig( 7700): Total System Memory = 906309632
,I/GalleryUtils( 7700): Application Heap = 96 MB
I/AppConfig( 7700): App Tier : NOT_DEF
D/SystemHelper( 7700): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  949): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7722 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  949): Killing 7456:com.android.chrome/u0a48 (adj 15): empty #11
,I/ActivityManager(  949): Process com.google.android.apps.plus (pid 7475) has died
,W/libprocessgroup(  949): failed to open /acct/uid_10048/pid_7456/cgroup.procs: No such file or directory
I/[LGHome]EVENT( 1874): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
W/ResourcesManager( 7722): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7722): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7722): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7722): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7722): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/GCoreNlp( 1728): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/LocationProviderProxy(  949): applying state to connected service
,I/CloudHub( 2719): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19951
,I/SystemConfig( 7722): BUILD Country: EU
I/SystemConfig( 7722): BUILD Operator: OPEN
,I/ActivityManager(  949): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7742 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 7722): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7722): existFile = false
,I/SystemConfig( 7722): canReadFile = false
I/SystemConfig( 7722): systemFeature RCS result false
D/SystemConfig( 7722): refreshRcsSupport() :false
,I/LockScreenSettings( 7742): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/art     (  949): Explicit concurrent mark sweep GC freed 25478(1304KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 2.251ms total 148.582ms
,D/LockScreenSettings( 7742): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7742): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7742): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7742): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7742): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ActivityManager(  949): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7762 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  949): Killing 7533:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 7506): android.os.DeadObjectException
,W/System.err( 7506): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7506): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7506): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7506): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7506): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7506): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7506): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7506): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7506): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7506): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7506): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7506): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7506): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7506): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7506): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7506): android.os.DeadObjectException
W/System.err( 7506): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7506): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7506): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7506): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7506): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7506): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7506): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7506): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7506): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7506): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7506): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7506): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7506): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7506): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7506): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
D/charger_monitor(  490): init target 500000
,W/libprocessgroup(  949): failed to open /acct/uid_10089/pid_7533/cgroup.procs: No such file or directory
W/ActivityManager(  949): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 11533ms
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
D/charger_monitor(  490): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 303, mChargingStatus=5, mChargingStop=false
,I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
W/ResourcesManager( 7762): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 303
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 303
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
,I/ActivityManager(  949): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7780 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/WifiController(  949): battery changed pluggedType: 2
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/UEI.SmartControl( 7780): Quickset Services start...
,I/UEI.SmartControl( 7780): Manufacture = LGE
D/UEI.SmartControl( 7780): File observer start...
E/UEI.SmartControl( 7780): IR Port is disabled: false
D/UEI.SmartControl( 7780): Starting file observer...
D/UEI.SmartControl( 7780): Extracting JNI libs...
D/UEI.SmartControl( 7780): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7780): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7780): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7780): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UpdateIcingCorporaServi( 1929): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/UEI.SmartControl( 7780): --- Selecting new region: 2
I/UEI.SmartControl( 7780): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7780): Platform has CIR...
D/UEI.SmartControl( 7780): NO CIR support, need to check package...
I/UEI.SmartControl( 7780): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7780): QS Service created
,I/ActivityManager(  949): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7817 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/UpdateIcingCorporaServi( 1929): UpdateCorporaTask done [took 68 ms] updated apps [took 68 ms] 
I/ActivityManager(  949): Killing 2719:com.lge.music/u0a28 (adj 15): empty #11
,E/UEI.SmartControl( 7780): QS start get config
V/AudioFlinger(  272): 2719 died, releasing its sessions
V/AudioFlinger(  272):  pid 1746 @ 0
,V/AudioFlinger(  272):  pid 3195 @ 1
V/AudioFlinger(  272):  pid 3195 @ 2
D/UEI.SmartControl( 7780): Loading JNI Libs...
,D/UEI.SmartControl( 7780):  configuring local db...
W/libprocessgroup(  949): failed to open /acct/uid_10028/pid_2719/cgroup.procs: No such file or directory
D/UEI.SmartControl( 7780):  ---- Has DB8: true
,D/UEI.SmartControl( 7780): QS start statue = true Error code = 0
D/UEI.SmartControl( 7780): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7780): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7780): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7780): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7780): IrrcClient ++ 
D/irrcClient( 7780): getIrrcService ++ 
D/irrcClient( 7780): getIrrcService -- 
D/irrcClient( 7780): IrrcClient -- 
W/irrc_jni( 7780): IRRCPlayer_nativeInit -- 
D/Finsky  ( 7817): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/UEI.SmartControl( 7780): Services init done
,I/UEI.SmartControl( 7780): Device manager: loading config....
D/UEI.SmartControl( 7780): QS Service init finished
D/UEI.SmartControl( 7780): Config is loaded...
D/UEI.SmartControl( 7780): QS Service version name: 0.1.73
D/UEI.SmartControl( 7780): QS Service version code: 1073
D/UEI.SmartControl( 7780): Service requested: Control
D/UEI.SmartControl( 7780): -----IControl: 11
D/UEI.SmartControl( 7780): Internal service binding...
,D/UEI.SmartControl( 7780): Caller: com.lge.qremote
D/UEI.SmartControl( 7780): ------------ IControl registerCallback...
I/UEI.SmartControl( 7780): Registering callback...
D/UEI.SmartControl( 7780): -----IControl: 19
D/UEI.SmartControl( 7780): Caller: com.lge.qremote
I/UEI.SmartControl( 7780): Registering Services Ready callback...
I/UEI.SmartControl( 7780): Notify client services are ready...
D/UEI.SmartControl( 7780): -----IControl: 8
D/UEI.SmartControl( 7780): Caller: com.lge.qremote
D/UEI.SmartControl( 7780):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7780): Notify AllClients services are ready: 0
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/Finsky  ( 7817): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7817): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7817): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7817): com.android.vending: cancel(-1050172287) by com.android.vending
V/DownloadManager( 3244): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3244): created cursor android.database.sqlite.SQLiteCursor@c4155c1 on behalf of 7817
D/Finsky  ( 7817): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7817): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7817): Skipping gmscore version check
D/Finsky  ( 7817): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  949): Killing 7506:com.lge.qremote/u0a106 (adj 15): empty #11
,W/libprocessgroup(  949): failed to open /acct/uid_10106/pid_7506/cgroup.procs: No such file or directory
,D/Finsky  ( 7817): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/PackageBroadcastService( 4305): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  949): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7867 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/PackageBroadcastService( 4305): Null package name or gms related package.  Ignoreing.
,W/ResourcesManager( 7867): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/Icing   ( 4305): updateResources: need to parse f{com.google.android.gms}
,I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
D/BluetoothManagerService(  949): Message: 20
D/BluetoothManagerService(  949): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a2be127:true
,D/BluetoothAdapterService(626782439)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@23c734f5
D/BluetoothAdapterService(626782439)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@23c734f5
V/LGMDMManager( 7867): Create singleton instance
,I/AudioManager( 7867): getMode name:com.lge.qremote
,D/UEI.SmartControl( 7780): -----IControl: 11
,D/UEI.SmartControl( 7780): Caller: com.lge.qremote
D/UEI.SmartControl( 7780): ------------ IControl registerCallback...
I/UEI.SmartControl( 7780): Registering callback...
D/UEI.SmartControl( 7780): -----IControl: 19
D/UEI.SmartControl( 7780): Caller: com.lge.qremote
I/UEI.SmartControl( 7780): Registering Services Ready callback...
I/UEI.SmartControl( 7780): Notify client services are ready...
I/AudioManager( 7867): getMode name:com.lge.qremote
D/UEI.SmartControl( 7780): -----IControl: 8
,D/UEI.SmartControl( 7780): Caller: com.lge.qremote
I/AudioManager( 7867): getMode name:com.lge.qremote
I/ActivityManager(  949): Killing 7005:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  949): failed to open /acct/uid_10038/pid_7005/cgroup.procs: No such file or directory
,I/AudioManager( 7867): getMode name:com.lge.qremote
I/AudioManager( 7867): getMode name:com.lge.qremote
,I/ActivityManager(  949): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7895 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 7895): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7895): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7895): VM with version 2.1.0 has multidex support
I/MultiDex( 7895): install
I/MultiDex( 7895): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7895): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7895): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7895): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@6b651d5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7895): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 7895): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7895): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1728): callingUid 10006, callindPid: 1728
,E/MDM     ( 1728): [102] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1728): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 4305): Restart initialization of location
D/ChimeraCfgMgr( 7895): Reading stored module config
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1728): com.google.android.gms: cancel(0) by com.google.android.gms
D/ChimeraCfgMgr( 7895): Loading module com.google.android.gms.car from APK com.google.android.gms
,I/art     ( 1728): Explicit concurrent mark sweep GC freed 30549(2MB) AllocSpace objects, 31(496KB) LOS objects, 40% free, 13MB/22MB, paused 2.467ms total 161.150ms
,W/GCoreFlp( 1728): No location to return for getLastLocation()
W/FusedLocationProvider( 1728): location=null
,D/NativeLibraryUtils( 7895): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 7895): Connecting to CarCallService...
,I/art     ( 7895): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 7895): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/CAR.SERVICE( 7895): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 7895): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 7895): Creating a new PhoneAdapter instance
W/ActivityManager(  949): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 7895): setListener: com.google.android.gms.car.dn@326fa6a8
W/ActivityManager(  949): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 7895): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 7895): Starting CarCallService with initial phone null
I/ActivityManager(  949): Killing 7576:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
W/libprocessgroup(  949): failed to open /acct/uid_10006/pid_7576/cgroup.procs: No such file or directory
,I/NotificationManager( 7895): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/Icing   ( 4305): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4305): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  949): Killing 7352:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  949): failed to open /acct/uid_10061/pid_7352/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 7780): Internal timer expired: 1
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  949): Killing 7677:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  949): failed to open /acct/uid_10011/pid_7677/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  949): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  949): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  949): tsOffsetIs: Apps: 135259965161; DSPS: 4531127; Offset : -3027915987
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,V/AlarmManager(  949): ELAPSED_WAKEUP set : Alarm{aeae834 type 2 when 143861 com.google.android.gms} when 143861
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1728): Vacuum at: now=1454416589045 tag=VacuumService
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,I/PowerManagerService(  949): ALS enabled for SRE
D/PowerManagerServiceEx(  949): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (29541 ms ago)
,D/qdlights(  949): set_light_backlight: 253
,D/qdlights(  949): set_light_backlight: 249
D/qdlights(  949): set_light_backlight: 246
,D/qdlights(  949): set_light_backlight: 243
,D/qdlights(  949): set_light_backlight: 239
,D/qdlights(  949): set_light_backlight: 236
,D/qdlights(  949): set_light_backlight: 233
,D/qdlights(  949): set_light_backlight: 229
,D/qdlights(  949): set_light_backlight: 226
,D/qdlights(  949): set_light_backlight: 223
,D/qdlights(  949): set_light_backlight: 219
,D/qdlights(  949): set_light_backlight: 216
,D/qdlights(  949): set_light_backlight: 213
,D/qdlights(  949): set_light_backlight: 209
,D/qdlights(  949): set_light_backlight: 206
,D/qdlights(  949): set_light_backlight: 203
,D/qdlights(  949): set_light_backlight: 199
,D/qdlights(  949): set_light_backlight: 196
,D/qdlights(  949): set_light_backlight: 193
,D/qdlights(  949): set_light_backlight: 189
,D/qdlights(  949): set_light_backlight: 186
,D/qdlights(  949): set_light_backlight: 183
,D/qdlights(  949): set_light_backlight: 179
,D/qdlights(  949): set_light_backlight: 176
,D/qdlights(  949): set_light_backlight: 173
,D/qdlights(  949): set_light_backlight: 169
,D/qdlights(  949): set_light_backlight: 166
,D/qdlights(  949): set_light_backlight: 163
,D/qdlights(  949): set_light_backlight: 159
,D/qdlights(  949): set_light_backlight: 156
,D/qdlights(  949): set_light_backlight: 153
,D/qdlights(  949): set_light_backlight: 149
,D/qdlights(  949): set_light_backlight: 146
,D/qdlights(  949): set_light_backlight: 143
,D/qdlights(  949): set_light_backlight: 139
,D/qdlights(  949): set_light_backlight: 136
,D/qdlights(  949): set_light_backlight: 133
,D/qdlights(  949): set_light_backlight: 129
,D/qdlights(  949): set_light_backlight: 126
,D/qdlights(  949): set_light_backlight: 123
,D/qdlights(  949): set_light_backlight: 119
,D/qdlights(  949): set_light_backlight: 116
,D/qdlights(  949): set_light_backlight: 113
,D/qdlights(  949): set_light_backlight: 109
,D/qdlights(  949): set_light_backlight: 106
,D/qdlights(  949): set_light_backlight: 103
,D/qdlights(  949): set_light_backlight: 99
,D/qdlights(  949): set_light_backlight: 96
,D/qdlights(  949): set_light_backlight: 93
,D/qdlights(  949): set_light_backlight: 89
,D/qdlights(  949): set_light_backlight: 86
,D/qdlights(  949): set_light_backlight: 83
,D/qdlights(  949): set_light_backlight: 79
,D/qdlights(  949): set_light_backlight: 76
,D/qdlights(  949): set_light_backlight: 73
,D/qdlights(  949): set_light_backlight: 69
,D/qdlights(  949): set_light_backlight: 66
,D/qdlights(  949): set_light_backlight: 63
,D/qdlights(  949): set_light_backlight: 59
,D/qdlights(  949): set_light_backlight: 56
,D/qdlights(  949): set_light_backlight: 53
,D/qdlights(  949): set_light_backlight: 49
,D/qdlights(  949): set_light_backlight: 46
,D/qdlights(  949): set_light_backlight: 43
,D/qdlights(  949): set_light_backlight: 39
,D/qdlights(  949): set_light_backlight: 36
,D/qdlights(  949): set_light_backlight: 33
,D/qdlights(  949): set_light_backlight: 29
,D/qdlights(  949): set_light_backlight: 26
,D/qdlights(  949): set_light_backlight: 23
,D/qdlights(  949): set_light_backlight: 19
,D/qdlights(  949): set_light_backlight: 16
,D/qdlights(  949): set_light_backlight: 13
,D/qdlights(  949): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  949): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  949): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  949): tsOffsetIs: Apps: 155260724789; DSPS: 5186512; Offset : -3027919481
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/PowerManagerService(  949): ALS enabled for SRE
D/PowerManagerServiceEx(  949): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (36535 ms ago)
I/PowerManagerService(  949): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  949): ALS enabled for SRE
D/PowerManagerServiceEx(  949): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (36547 ms ago)
W/ContextImpl(  949): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  949): Sleeping (uid 1000)...
D/LPWGController(  949): [updateScreenState] screen on = false
D/LPWGController(  949): disable proximity sensor
D/LPWGController(  949): enable proximity sensor
,I/SensorManager(  949): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@fab8415] by com.android.server.power.ProximitySensorListener.enable():120
I/sensors_hal_Ctx(  949): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  949): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
,D/sensors_hal_SAM(  949): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  949): activate: handle is 48, enable
V/sensors_hal_Ctx(  949): activate sensors is 1400000000000
D/sensors_hal_Thresh(  949): enable: handle=48
I/sensors_hal_SAM(  949): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  949): waitForResponse: timeout=1000
V/sensors_hal_SAM(  949): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  949): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  949): enable: Received response: 0
D/PowerManagerServiceEx(  949): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (36588 ms ago)
I/Adreno-EGL(  949): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  949): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  949): Build Date: 03/02/15 Mon
I/Adreno-EGL(  949): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  949): Remote Branch: 
I/Adreno-EGL(  949): Local Patches: 
I/Adreno-EGL(  949): Reconstruct Branch: 
,D/PermissionCache(  245): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1062 us)
,I/Sensors (  440): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  949): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,I/sensors_hal_SAM(  949): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  949): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  949): processInd: handle 48, count=1
V/sensors_hal_Thresh(  949): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  949): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  949): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  949): poll: count: 256
I/sensors_hal_Ctx(  949): poll: released wakelock sensor_ind
D/sensors_hal_Util(  949): waitForResponse: timeout=0
D/LPWGController(  949): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  949): current mode = 1  value = 1 1
I/LPWGController(  949): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
,I/LPWGController(  949): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/qdlights(  949): set_light_backlight: 0
,I/SensorManager(  949): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  949): activate: handle is 46, disable
,V/sensors_hal_Ctx(  949): activate sensors is 1000000000000
D/sensors_hal_LP2(  949): enable: handle=46
D/sensors_hal_LP2(  949): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  949): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  245): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  245): hwc_blank: Blanking display: 0
I/DisplayManagerService(  949): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  949): Display changed displayId=0
,V/sensors_hal_SAM(  949): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
,D/sensors_hal_LP2(  949): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1746): Display #0 changed.
,D/qdhwcomposer(  245): hwc_blank: Done blanking display: 0
D/SurfaceControl(  949): Excessive delay in setPowerMode(): 173ms
,I/qdhwcomposer(  245): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  949): Got set_interactive hint
,D/KeyguardViewMediator( 1370): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1330): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1370): notifyScreenOffLocked
D/SmartCoverViewMediator( 1330): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1330): handleNotifyScreenOFF
D/KeyguardViewMediator( 1370): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1370): handleNotifyScreenOff
D/WifiServerServiceExt(  949): sendKtScanInterval  mRtspPlay : false
,D/ScreenTurnOffBySensor( 1370): unregisterProximitySensor
D/StatusBarWindowView( 1370): onScreenTurnedOff why = 3
V/AudioFlinger(  272): setParameters(): io 0, keyvalue screen_state=on, calling pid 949
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/audio_hw_primary(  272): adev_set_parameters: enter: screen_state=on
V/voice   (  272): voice_set_parameters: enter: screen_state=on
V/compress_voip(  272): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  272): voice_extn_compress_voip_set_parameters: exit
V/voice   (  272): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  272): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  272): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  272): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  272): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  272): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  272): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  272): adev_set_parameters: exit with code(0)
I/WifiServerServiceExt(  949): set CMD_KT_SCAN_INTERVAL
,D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
,D/GpsLocationProvider(  949): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1836): |CORE| sendScreenState: state:true
I/LEDService( 1801): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1801): stopPatternFlashing()
I/Cliptray Service( 1801): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
I/LEDService( 1801): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
D/Cliptray Service( 1801): lockStatus = 0
I/LEDService( 1801): updateLightsLocked : turn off led
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1783): action : android.intent.action.SCREEN_ON
D/LEDHandler( 1801): RESTART MSG
,D/NfcServiceNXP( 1783): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1783): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1783): isRequireNfcCRouting() return true
D/LNfcService( 1783): isHCERoutingtoHost() return : true
D/NfcService( 1783): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1783): mEnableLPD: true
D/NfcService( 1783): mEnableReader: false
D/NfcService( 1783): mEnableHostRouting: true
D/NfcService( 1783): newParams.techmask= mTechMask: default
D/NfcService( 1783): mEnableLPD: true
D/NfcService( 1783): mEnableReader: false
D/NfcService( 1783): mEnableHostRouting: true
D/NfcService( 1783): screenState= 3
D/NfcService( 1783): Discovery configuration equal, not updating.
D/SplitWindow(  949): check instance of lgWin Window{2e88f6b8 u0 SearchPanel}
,D/InputDispatcher(  949): Window went away: Window{3e52a692 u0 SearchPanel}
,I/[SystemUI]Clock( 1370): onReceive = android.intent.action.SCREEN_ON
,I/LgeClockWidgetControlView( 1370): time changed, timezoneChanged : false
,D/Ulp_jni (  949): JNI:system_update. Event-0
,V/PhoneApp( 1746): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2688): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:36:43
,D/WeatherService( 2688): 2 : ACTION screen on
D/WeatherService( 2688): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2688): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2688): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:36:43
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  949): ACTION_SCREEN_ON
,D/AppCleanupService( 4103): android.intent.action.SCREEN_ON
,V/AudioFlinger(  272): setParameters(): io 0, keyvalue screen_state=off, calling pid 949
D/audio_hw_primary(  272): adev_set_parameters: enter: screen_state=off
V/voice   (  272): voice_set_parameters: enter: screen_state=off
V/compress_voip(  272): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  272): voice_extn_compress_voip_set_parameters: exit
V/voice   (  272): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  272): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  272): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  272): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  272): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  272): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  272): adev_set_parameters: exit with code(0)
D/WifiController(  949): CMD_SCREEN_OFF 
D/WifiController(  949): shouldWifiStayAwake TRUE
,D/GpsLocationProvider(  949): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1836): |CORE| sendScreenState: state:false
,I/LEDService( 1801): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1801): stopPatternFlashing()
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
I/LEDService( 1801): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
I/LEDService( 1801): updateLightsLocked : turn on led
D/VolumeVibrator( 1801): clear
E/LEDService( 1801): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1801): Can't handle this request of patternId:0
D/LEDHandler( 1801): RESTART MSG
I/Cliptray Service( 1801): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1783): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1783): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1874): [Launcher.java:1711:onReceive()]Screen Off
,I/Sensors (  440): sns_pwr.c(301):releasing wakelock
V/PhoneApp( 1746): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
D/WeatherService( 2688): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:36:43
D/WeatherService( 2688): 2 : ACTION screen off
D/WeatherService( 2688): 2 : TimeTick Receiver Unregister
D/WeatherService( 2688): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:36:43
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  949): ACTION_SCREEN_OFF
D/AppCleanupService( 4103): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 4103): AppUsageStatsSaveTask
E/NxpNfcJni( 1783): getReconnectState = 0x0
,D/LCardEmulationManager( 1783): getHceAppCount hostAppNum : 0
,D/LCardEmulationManager( 1783): getDefaultRoute
D/LNfcService( 1783): isRequireNfcCRouting() return true
D/LNfcService( 1783): isHCERoutingtoHost() return : true
D/NfcService( 1783): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1783): mEnableLPD: true
D/NfcService( 1783): mEnableReader: false
D/NfcService( 1783): mEnableHostRouting: true
D/NfcService( 1783): newParams.techmask= mTechMask: 0
D/NfcService( 1783): mEnableLPD: true
D/NfcService( 1783): mEnableReader: false
D/NfcService( 1783): mEnableHostRouting: true
D/NfcService( 1783): screenState= 1
E/NxpNfcJni( 1783): getReconnectState = 0x0
,D/KeyguardViewMediator( 1370): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  949): ELAPSED_WAKEUP set : Alarm{15cd4c91 type 2 when 162407 com.android.systemui} when 162407
,D/PhoneUtils( 1746): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1746): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1746): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1746): getCallState : 0
,D/PhoneUtils( 1746): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1746): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1746): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1370): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1370): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
D/sensors_hal_Time(  949): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  949): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  949): tsOffsetIs: Apps: 175261410927; DSPS: 5841895; Offset : -3027935377
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,D/PowerManagerServiceEx(  949): acquireWakeLockInternal: lock=518256630, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=949
,V/AlarmManager(  949): ELAPSED_WAKEUP set : Alarm{1ae1b7f7 type 2 when 184321 android} when 184321
D/PowerManagerServiceEx(  949): releaseWakeLockInternal: lock=518256630 [*alarm*], flags=0x0
,D/charger_monitor(  490): init target 500000
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 300, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 300
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 300
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  949): battery changed pluggedType: 2
V/AlarmManager(  949): ELAPSED_WAKEUP set : Alarm{3832c664 type 2 when 188339 com.google.android.gms} when 188339
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/PerfProfileCollectorService( 4305): Turn off PerfProfile Collection
,D/PerfProfileCollectorService( 4305): removeStateFiles() called
,I/PhenotypeConfigurator( 1728): Scheduling Phenotype for one-off execution 8348 seconds from now (1454416633661)
,D/GetConfigurationSnapshotOperation( 1728): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1728): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1728): Using platform SSLCertificateSocketFactory
,I/art     (  949): Explicit concurrent mark sweep GC freed 48877(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 23MB/35MB, paused 2.365ms total 147.595ms
,D/LocationManagerService(  949): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  266): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  266): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  266): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  266): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd(  266): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  266): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  266): res_queryN name = xxxxx succeed
I/System.out( 1728): propertyValue:false
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LocationManagerService(  949): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  949): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  949): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  949): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  949): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  949): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  949): tsOffsetIs: Apps: 195262084670; DSPS: 6497277; Offset : -3027932812
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  949): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  949): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  949): tsOffsetIs: Apps: 215262834922; DSPS: 7152662; Offset : -3027945109
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
D/sensors_hal_Time(  949): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  949): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  949): tsOffsetIs: Apps: 235263512623; DSPS: 7808044; Offset : -3027939368
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/charger_monitor(  490): init target 500000
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 297
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 297, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 297
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  949): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  949): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  949): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  949): tsOffsetIs: Apps: 255264192667; DSPS: 8463426; Offset : -3027930451
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/charger_monitor(  490): init target 500000
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
,I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 296, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  949): battery changed pluggedType: 2
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 296, mChargingStatus=5, mChargingStop=false
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
,I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  949): battery changed pluggedType: 2
W/Settings(  949): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  949): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  949): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  949): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  949): tsOffsetIs: Apps: 275264935889; DSPS: 9118810; Offset : -3027919651
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
D/sensors_hal_Time(  949): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  949): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  949): tsOffsetIs: Apps: 295265610776; DSPS: 9774193; Offset : -3027946511
,I/jxcore-log( 6100): --= Surplus to requirements =--
I/jxcore-log( 6100): 
I/jxcore-log( 6100): ****TEST TOOK:  ms ****
I/jxcore-log( 6100): 
I/jxcore-log( 6100): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6100): 
,D/AndroidRuntime( 8086): 
D/AndroidRuntime( 8086): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8086): CheckJNI is OFF
,D/AndroidRuntime( 8086): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  949): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  949): Killing 6100:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
,W/PackageSettings(  949): Skipping PackageSetting{7b38fe5 com.example.hello/10317} due to missing metadata
,I/WindowState(  949): WIN DEATH: Window{3f34d6ca u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/InputDispatcher(  949): Focus left window: Window{3f34d6ca u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  949): Window went away: Window{3f34d6ca u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  949):   Force finishing activity ActivityRecord{30e66b24 u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  949): Display changed displayId=0
,D/DSDPConnection( 1746): Display #0 changed.
W/ActivityManager(  949): Spurious death for ProcessRecord{35ab5e2c 6100:com.test.thalitest/u0a316}, curProc for 6100: null
I/ActivityManager(  949): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
,I/ActivityManager(  949):   Force finishing activity ActivityRecord{30e66b24 u0 com.test.thalitest/.MainActivity t222 f}
W/ActivityManager(  949): Duplicate finish request for ActivityRecord{30e66b24 u0 com.test.thalitest/.MainActivity t222 f}
,D/KeyguardModel( 1370): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 1874): [Launcher.java:5203:onStart()]onStart
W/GeofencerStateMachine( 1728): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  949): Reconfiguring input devices.  changes=0x00000010
I/[LGHome]EVENT( 1874): [Launcher.java:776:onResume()]onResume
,I/ActivityManager(  949): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8112 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/QCNEJ   ( 1836): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/System.err( 3614): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,W/System.err( 3614): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3614): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3614): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3614): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3614): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3614): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3614): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3614): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3614): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3614): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3614): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/art     ( 1929): Explicit concurrent mark sweep GC freed 9240(635KB) AllocSpace objects, 3(71KB) LOS objects, 40% free, 12MB/20MB, paused 2.149ms total 138.605ms
,I/art     ( 4305): Explicit concurrent mark sweep GC freed 4791(301KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 14MB/18MB, paused 789us total 145.003ms
W/SQLiteConnectionPool( 4305): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/[LGHome]EVENT( 1874): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
,I/[SystemUI]QSlideListController( 1370): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]Launcher.Model( 1874): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
D/KeyguardModel( 1370): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1370): createShortcutInfo...
D/KeyguardModel( 1370): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1370): createShortcutInfo...
I/[LGHome]LGActivityUtil( 1874): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1370): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
,D/KeyguardModel( 1370): createShortcutInfo...
I/[LGHome]EVENT( 1874): [Launcher.java:929:onResume()]onResume end
I/Activity( 1874): Activity.onPostResume() called 
W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1370): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1370): createShortcutInfo...
,W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1370): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1370): createShortcutInfo...
I/[LGHome]EVENT( 1874): [Launcher.java:986:onPause()]onPause
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1370): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1370): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,D/KeyguardModel( 1370): handleShortcutListChanged...
,W/[LGHome]LGWallpaperInfo( 1874): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1874): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
D/KeyguardModel( 1370): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1370): createShortcutInfo...
I/art     (  949): Explicit concurrent mark sweep GC freed 15247(1079KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 3.532ms total 229.218ms
,I/art     (  949): WaitForGcToComplete blocked for 213.915ms for cause Explicit
D/KeyguardModel( 1370): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1370): createShortcutInfo...
,W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/SystemUI[Framework](  949): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
D/KeyguardModel( 1370): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1370): createShortcutInfo...
W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1370): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1370): createShortcutInfo...
D/InputDispatcher(  949): Focus entered window: Window{29bf13c3 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/ResourceType( 1370): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1370): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
W/PhoneWindowManagerEx(  949): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  949): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  949): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  949): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@565595d,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  949): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,I/SystemUI[Framework](  949): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  949): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  949): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  949): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  949): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@565595d,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  949): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/KeyguardModel( 1370): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1370): createShortcutInfo...
I/[LGHome]EVENT( 1874): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1874): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1874): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
W/ResourcesManager( 8112): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8112): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8112): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/KeyguardModel( 1370): handleShortcutListChanged...
,I/[LGHome]EVENT( 1874): [Launcher.java:5214:onStop()]onStop
I/[LGHome]EVENT( 1874): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1874): [setNavigationBarColor] color=0x 0
,W/InputMethodManagerService(  949): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  949): Got RemoteException sending setActive(false) notification to pid 6100 uid 10316
D/administrator(  949): Handling package changes for user 0
,I/[LGHome]Launcher.Model( 1874): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/Timeline(  949): Timeline: Activity_windows_visible id: ActivityRecord{1648114c u0 com.lge.launcher2/.Launcher t221} time:298253
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/LGEmail ( 8112): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,W/IInputConnectionWrapper( 1874): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1874): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,E/b       ( 1621): Unable to connect to the editor to retrieve text... will retry later
,D/LGEmail ( 8112): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1874): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1874): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 1874): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
,W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
,I/art     (  949): Explicit concurrent mark sweep GC freed 3741(208KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 7.347ms total 349.159ms
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
,W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
,W/Resources( 1874): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/NotificationService(  949): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  949): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  949): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  949): removeObsoleteFile: deleting file=222_task.xml
,D/PhoneStatusBar( 1370): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
I/[SystemUI]NavigationThemeResource( 1370): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1370):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1370): , Keyguard show=false, IME shown=false, Panel expanded=false
D/AndroidRuntime( 8086): Shutting down VM
,D/LCardEmulationManager( 1783): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1783): getDefaultRoute
I/PackageChangeReceiver( 8112): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1874): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/ActivityManager(  949): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8144 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  949): Killing 7700:com.android.gallery3d/u0a23 (adj 15): empty #11
I/art     (  301): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 291us total 22.038ms
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 20.981ms
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 297us total 21.621ms
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1874): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1874): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
W/IInputConnectionWrapper( 1874): getTextAfterCursor on inactive InputConnection
W/libprocessgroup(  949): failed to open /acct/uid_10023/pid_7700/cgroup.procs: No such file or directory
,I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
,I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 1874): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1874): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1874): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/AppUp4:AppBoxCP( 8144): onCreate
,W/AppUp4:DB( 8144):  [AppBoxDatabaseHelper] construct
,W/FileUtils( 8144): Failed to chmod(/data/data/com.lge.appbox.client/databases/appbox.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,I/AppUp4:DB( 8144):  setFingerPrint start
I/AppUp4:DB( 8144):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
E/SharedPreferencesImpl( 1874): Couldn't rename file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml to backup file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml.bak
I/Timeline( 1874): Timeline: Activity_idle id: android.os.BinderProxy@155a1016 time:298959
I/AppUp4:DB( 8144):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 8144):  SDK version = 0
I/AppUp4:DB( 8144):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 8144): AppBoxApplication onCreate()
,W/ResourcesManager(  949): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/SQLiteLog( 8144): (3850) statement aborts at 24: [INSERT INTO exclude_apps(package) VALUES (?)] disk I/O error
,E/SQLiteDatabase( 8144): Error inserting package=com.test.thalitest
E/SQLiteDatabase( 8144): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 8144): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 8144): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:790)
E/SQLiteDatabase( 8144): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
E/SQLiteDatabase( 8144): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 8144): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1581)
E/SQLiteDatabase( 8144): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1451)
E/SQLiteDatabase( 8144): 	at com.lge.appbox.databases.AppBoxContentProvider.insert(AppBoxContentProvider.java:220)
E/SQLiteDatabase( 8144): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
E/SQLiteDatabase( 8144): 	at android.content.ContentResolver.insert(ContentResolver.java:1267)
E/SQLiteDatabase( 8144): 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeApp(PreloadListManagerHelper.java:134)
E/SQLiteDatabase( 8144): 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeAppInternal(PreloadListManagerHelper.java:115)
E/SQLiteDatabase( 8144): 	at com.lge.appbox.manager.PreloadListManagerHelper.onRemoveAppEvent(PreloadListManagerHelper.java:100)
E/SQLiteDatabase( 8144): 	at com.lge.appbox.manager.PreloadListManagerHelper.updateExDb(PreloadListManagerHelper.java:65)
E/SQLiteDatabase( 8144): 	at com.lge.appbox.manager.PreloadListManagerHelper.onReceive(PreloadListManagerHelper.java:46)
E/SQLiteDatabase( 8144): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2663)
E/SQLiteDatabase( 8144): 	at android.app.ActivityThread.access$1700(ActivityThread.java:155)
E/SQLiteDatabase( 8144): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1400)
E/SQLiteDatabase( 8144): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8144): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 8144): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/SQLiteDatabase( 8144): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 8144): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 8144): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/SQLiteDatabase( 8144): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/art     ( 1874): Explicit concurrent mark sweep GC freed 26722(1425KB) AllocSpace objects, 17(2MB) LOS objects, 40% free, 15MB/25MB, paused 2.358ms total 52.653ms

```
