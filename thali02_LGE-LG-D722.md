#### Test 61362366b6c9a6f_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/art     ( 3097): Explicit concurrent mark sweep GC freed 14012(951KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 8MB/10MB, paused 590us total 43.223ms
I/AlertUtils( 3567): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3567): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/MediaScannerReceiver( 3567): Calendar.onReceive: a=android.intent.action.MEDIA_SCANNER_FINISHED Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///storage/emulated/0 flg=0x10 cmp=com.android.calendar/.alerts.MediaScannerReceiver }, mData=file:///storage/emulated/0
E/MediaScanReceiver( 4454): media scanning finished
I/com.lge.bnr.receiver.MediaScanReceiver( 4454): android.intent.action.MEDIA_SCANNER_FINISHED
I/AlertUtils( 3567): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 3567): End InitializeAlertRingtoneService.onHandleIntent
--------- beginning of system
I/ActivityManager(  941): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=4535 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/InitNotificationRingtoneService( 3567): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 3567): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
D/charger_monitor(  486): init target 500000
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/AlertUtils( 3567): [getCalendarNotiSoundURIFromCursor] getCount()= 21
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/WifiController(  941): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
W/MainApplication( 4454): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/AlertUtils( 3567): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
I/AlertUtils( 3567): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 3567): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 3567): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 3567): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 3567): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 3567): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
V/AlarmManager(  941): ELAPSED_WAKEUP set : Alarm{170b4164 type 2 when 67030 com.google.android.gms} when 67030
W/ResourcesManager( 4535): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/AlertUtils( 3567): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 3567): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 3567): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 3567): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 3567): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 3567): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 3567): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/art     ( 4471): CheckpointMarkThreadRoots callback created = 0xb042d390
I/AlertUtils( 3567): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3567): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
D/CalendarProvider2( 4535): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@33efbda7
I/AlertUtils( 3567): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 3567): End InitializeAlertRingtoneService.onHandleIntent
D/CalendarProvider2( 4535): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 4535): Created com.android.providers.calendar.CalendarAlarmManager@2e28bfc0(com.android.providers.calendar.CalendarProvider2@33efbda7)
I/art     ( 4471): CheckpointMarkThreadRoots callback created = 0xb042d370
D/CalendarProviderBroadcastReceiver( 4535): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 4535): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 4535): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 4535): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 4535): [getOrCreateCalendarAlarmManager]
D/WearableService( 1728): callingUid 10006, callindPid: 1728
D/LocationInitializer( 4014): Restart initialization of location
D/AuthorizationBluetoothService( 1728): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1728): [128] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1728): com.google.android.gms: cancel(0) by com.google.android.gms
I/MediaStoreImporter( 4471): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
D/CalendarProvider2( 4535): [IntentService] Release Lock
D/CalendarProvider2( 4535): CalendarProviderIntentService.onDestroy()
D/AndroidRuntime( 4550): 
D/AndroidRuntime( 4550): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4550): CheckJNI is OFF
I/art     ( 2000): Explicit concurrent mark sweep GC freed 2447(96KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 936us total 31.051ms
W/IcingInternalCorpora( 4014): getNumBytesRead when not calculated.
I/ActivityManager(  941): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=4577 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/GCoreFlp( 1728): No location to return for getLastLocation()
W/FusedLocationProvider( 1728): location=null
D/AndroidRuntime( 4550): Calling main entry com.android.commands.am.Am
W/ActivityManager(  941): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/ActivityManager(  941): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/art     (  941): Explicit concurrent mark sweep GC freed 14947(756KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/33MB, paused 2.265ms total 130.670ms
D/ActivityManager(  941): setTaskToReturnTo : TaskRecord{171f6b7e #224 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  941): setTaskToReturnTo : TaskRecord{171f6b7e #224 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  941): AppWindowTokenEx init.. 
D/ContextHelper(  941): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
D/InputDispatcher(  941): Focus left window: Window{27ffa8fb u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 4550): Shutting down VM
I/PhoneWindow(  941): [generateLayout] setColorNavigationBar => color=0x ff000001
I/[LGHome]EVENT( 1874): [Launcher.java:986:onPause()]onPause
D/PhoneWindowEx(  941): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow(  941): [setNavigationBarColor2] color=0x fff5f5f5
D/SplitWindow(  941): check instance of lgWin Window{14936c56 u0 Starting com.test.thalitest}
I/ActivityManager(  941): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4605 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1874): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[LGHome]EVENT( 1874): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  941): Starting window displayed
I/HotwordDetector( 1962): Closing mic
D/WindowManager(  941): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
I/SystemUI[Framework](  941): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
I/Gmail   ( 4577): getAccountsCursor
I/[SystemUI]NavigationThemeResource( 1370): notify navigation bar color(0xfff5f5f5)
W/PhoneWindowManagerEx(  941): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  941): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  941): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/[SystemUI]NavigationThemeResource( 1370): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1370):  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
I/[SystemUI]NavigationThemeResource( 1370): , Keyguard show=false, IME shown=false, Panel expanded=false
I/SystemUI[Framework](  941): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@230969de,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  941): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,I/MicrophoneInputStream( 1962): mic_close com.google.android.apps.gsa.speech.audio.u@324bf5b1
V/AudioRecord( 1962): stop()
D/AudioRecord( 1962): AudioRecord->stop()
,V/AudioFlinger(  280): RecordHandle::stop()
V/AudioFlinger(  280): RecordThread::stop
,V/AudioFlinger(  280): Record stopped OK
V/AudioPolicyManager(  280): stopInput() input 17
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/AudioPolicyService(  280): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  280): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  280): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  280): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  280): ThreadBase::setParameters() routing=0
V/AudioFlinger(  280): sendConfigEvent_l() num events 1 event 2
,V/AudioFlinger(  280): processConfigEvents_l() remaining events 1
V/AudioFlinger(  280): processConfigEvents_l() DONE thread 0xb3ddc000
D/audio_hw_primary(  280): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
W/GAV2    ( 4577): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,V/audio_hw_primary(  280): stop_input_stream: enter: usecase(7: audio-record)
,V/audio_hw_primary(  280): disable_audio_route: enter: usecase(7)
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
,V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  280): setParameters(): io 17, keyvalue hotword_active=0, calling pid 280
V/AudioFlinger(  280): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  280): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  280): RecordThread: loop starting
V/AudioFlinger(  280): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  280): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  280): in_set_parameters: exit: status(0)
V/AudioFlinger(  280): processConfigEvents_l() DONE thread 0xb3ddc000
V/AudioFlinger(  280): RecordThread: loop stopping
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioRecord( 1962): stop()
V/AudioRecord( 1962): stop()
,V/AudioRecord( 1962): stop()
W/ActivityManager(  941): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager(  941): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
V/AudioFlinger(  280): RecordHandle::stop()
V/AudioFlinger(  280): releasing 16 from 1962 for -1
V/AudioFlinger(  280):  decremented refcount to 0
V/AudioFlinger(  280): RecordThread::stop
V/AudioFlinger(  280): purging stale effects
V/AudioPolicyManager(  280): releaseInput() 17
V/AudioPolicyManager(  280): closeInput(17)
V/AudioFlinger(  280): closeInput() 17
V/AudioSystem(  280): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  941): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1747): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  280): ThreadBase::exit
V/AudioSystem( 2720): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1962): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1370): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  280): RecordThread: loop starting
V/AudioSystem( 3067): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  280): RecordThread 0xb3ddc000 exiting
D/audio_hw_primary(  280): adev_close_input_stream: enter:stream_handle(0xb546e1a0)
D/audio_hw_primary(  280): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  280): in_standby: exit:  status(0)
V/AudioPolicyService(  280): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  280): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  280): releaseInput() exit
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioFlinger(  280): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioPolicyService(  280): AudioCommandThread() processing update audio port list
V/AudioFlinger(  280): removeClient_l() pid 1962, calling pid 280
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
,D/ContextHelper( 4605): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
I/HotwordRecognitionRnr( 1962): Stopping hotword detection.
I/HotwordRecognitionRnr( 1962): Hotword detection finished
E/Gmail   ( 4577): Error finding the version of the Email provider.....
E/Gmail   ( 4577): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4577): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4577): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4577): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4577): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4577): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4577): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 4577): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 4577): We do not support migrating this version of the Email provider.
I/Gmail   ( 4577): getAccountsCursor
I/ActivityManager(  941): Killing 4373:com.android.settings/1000 (adj 15): empty #11
,I/Gmail   ( 4577): Observing account changes for notifications
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/libprocessgroup(  941): failed to open /acct/uid_1000/pid_4373/cgroup.procs: No such file or directory
,W/ActivityManager(  941): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/WebViewFactory( 4605): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1728): No location to return for getLastLocation()
,W/FusedLocationProvider( 1728): location=null
I/LibraryLoader( 4605): Time to load native libraries: 7 ms (timestamps 8392-8399)
,I/LibraryLoader( 4605): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 4605): Binding Chromium to main looper Looper (main, tid 1) {204654f9}
,I/LibraryLoader( 4605): Expected native library version number "",actual native library version number ""
I/chromium( 4605): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4605): Initializing chromium process, singleProcess=true
W/art     ( 4605): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 4605): ApplicationContext is null in ApplicationStatus
I/ActivityManager(  941): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=4660 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,W/chromium( 4605): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
I/art     (  309): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 296us total 28.078ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 22.751ms
,W/chromium( 4605): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 321us total 23.114ms
,E/libEGL  ( 4605): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4605): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4605): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4605): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 4605): Build Date: 03/02/15 Mon
I/Adreno-EGL( 4605): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 4605): Remote Branch: 
I/Adreno-EGL( 4605): Local Patches: 
I/Adreno-EGL( 4605): Reconstruct Branch: 
I/Gmail   ( 4577): notifyAccountChanged
I/Gmail   ( 4577): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4577): getAccountsCursor
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 4577): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 4577): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 4577): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
,V/AudioPolicyService(  280): registerClient() client 0xb4027340, uid 10316
,D/BluetoothManagerService(  941): Message: 20
D/BluetoothManagerService(  941): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5cac0c1:true
D/BluetoothAdapter( 4605): 453920693: getState() :  mService = null. Returning STATE_OFF
,D/PhoneMonitor( 4660): Register our PhoneStateListener
,D/GCM     ( 1728): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  941): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=4697 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/PhoneMonitor( 4660): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 4660): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 4660): [parse] Load xml
I/Gmail   ( 4577): getAccountsCursor
,V/TelephonyAutoProfiling( 4660): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 4660): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 4660): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 4697): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 4342): Internal timer expired: 1
,W/art     ( 4605): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 4605): onDetachedFromWindow called when already detached. Ignoring
,I/PhoneWindow( 4605): [generateLayout] setColorNavigationBar => color=0x ff000001
D/PhoneWindowEx( 4605): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow( 4605): [setNavigationBarColor2] color=0x fff5f5f5
D/SystemWebViewEngine( 4605): CordovaWebView is running on device made by: LGE
,W/art     ( 4605): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4605): Attempt to remove local handle scope entry from IRT, ignoring
,I/Activity( 4605): Activity.onPostResume() called 
,D/OpenGLRenderer( 4605): Render dirty regions requested: true
I/OpenGLRenderer( 4605): Initialized EGL, version 1.4
D/OpenGLRenderer( 4605): Enabling debug mode 0
,D/Atlas   ( 4605): Validating map...
,D/SplitWindow(  941): check instance of lgWin Window{33576e1c u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 4605): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  941): Killing 4342:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 4320): android.os.DeadObjectException
W/System.err( 4320): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 4320): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 4320): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 4320): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 4320): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 4320): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 4320): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4320): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4320): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4320): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 4320): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4320): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4320): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 4320): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 4320): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 4320): android.os.DeadObjectException
W/System.err( 4320): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 4320): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 4320): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 4320): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 4320): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 4320): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 4320): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4320): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4320): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4320): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 4320): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4320): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4320): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 4320): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 4320): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
,I/art     ( 4697): CheckpointMarkThreadRoots callback created = 0xb042d320
,I/art     ( 4697): CheckpointMarkThreadRoots callback created = 0xb042d300
,W/libprocessgroup(  941): failed to open /acct/uid_10089/pid_4342/cgroup.procs: No such file or directory
,W/ActivityManager(  941): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
D/InputDispatcher(  941): Focus entered window: Window{33576e1c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  941): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=4729 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  941): Displayed com.test.thalitest/.MainActivity: +1s697ms
I/Timeline(  941): Timeline: Activity_windows_visible id: ActivityRecord{c9558df u0 com.test.thalitest/.MainActivity t224} time:69574
,W/InputMethodManagerService(  941): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/Timeline( 4605): Timeline: Activity_idle id: android.os.BinderProxy@29c59608 time:69609
I/Babel_SMS( 4697): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 4697): MmsConfig.loadMmsSettings
,I/Babel_SMS( 4697): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 4697): MmsConfig.loadFromDatabase
,D/UEI.SmartControl( 4729): Quickset Services start...
,I/UEI.SmartControl( 4729): Manufacture = LGE
D/UEI.SmartControl( 4729): File observer start...
E/UEI.SmartControl( 4729): IR Port is disabled: false
D/UEI.SmartControl( 4729): Starting file observer...
,D/UEI.SmartControl( 4729): Extracting JNI libs...
D/UEI.SmartControl( 4729): --- this system supports 32-bit or 64-bit only
W/BindingManager( 4605): Cannot call determinedVisibility() - never saw a connection for the pid: 4605
,E/Babel_SMS( 4697): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4697): MmsConfig.loadFromResources
D/UEI.SmartControl( 4729): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 4729): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 4729): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,E/Babel_SMS( 4697): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 4697): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 4697): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 4697): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 4697): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 4697): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 4697): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 4697): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 4697): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 4697): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 4697): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 4697): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 4697): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 4697): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 4697): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 4697): found sensor: LGE Absolute Motion Detector Sensor, handle=33
,D/SensorManager( 4697): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 4697): found sensor: Motion Accel, handle=46
I/ActivityManager(  941): Waited long enough for: ServiceRecord{1e51e57 u0 com.lge.springcleaning/.service.AppCleanupService}
,D/AlertService( 3567): Beginning updateAlertNotification
I/UEI.SmartControl( 4729): --- Selecting new region: 2
I/UEI.SmartControl( 4729): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 4729): Platform has CIR...
D/UEI.SmartControl( 4729): NO CIR support, need to check package...
I/UEI.SmartControl( 4729): Model: LG-D722 uses JNI
D/UEI.SmartControl( 4729): QS Service created
W/Settings( 4697): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 4697): startup - clean
D/AlertService( 3567): No fired or scheduled alerts
I/NotificationManager( 3567): com.android.calendar: cancel(0) by com.android.calendar
,I/NotificationManager( 3567): com.android.calendar: cancel(1) by com.android.calendar
I/Babel   ( 4697): deleted: false for 0
I/NotificationManager( 3567): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 3567): com.android.calendar: cancel(3) by com.android.calendar
E/UEI.SmartControl( 4729): QS start get config
I/NotificationManager( 3567): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 3567): com.android.calendar: cancel(5) by com.android.calendar
,I/NotificationManager( 3567): com.android.calendar: cancel(6) by com.android.calendar
D/JsMessageQueue( 4605): Set native->JS mode to OnlineEventsBridgeMode
I/NotificationManager( 3567): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 3567): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 3567): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 3567): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 3567): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 3567): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 3567): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 3567): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 3567): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 3567): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 3567): com.android.calendar: cancel(17) by com.android.calendar
,I/NotificationManager( 3567): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 3567): com.android.calendar: cancel(19) by com.android.calendar
,I/NotificationManager( 3567): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 3567): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/UEI.SmartControl( 4729): Loading JNI Libs...
D/UEI.SmartControl( 4729):  configuring local db...
,W/AudioCapabilities( 4697): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 4697): Unsupported mime audio/adpcm
W/AudioCapabilities( 4697): Unsupported mime audio/g726
W/AudioCapabilities( 4697): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 4697): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 4697): Unsupported mime video/mjpg
D/AlarmScheduler( 3567): No events found starting within 1 week.
,W/VideoCapabilities( 4697): Unsupported mime video/theora
W/AudioCapabilities( 4697): Unsupported mime audio/evrc
,W/AudioCapabilities( 4697): Unsupported mime audio/qcelp
W/VideoCapabilities( 4697): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 4697): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 4697): Unsupported mime audio/qcelp
W/AudioCapabilities( 4697): Unsupported mime audio/evrc
W/VideoCapabilities( 4697): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 4697): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4697): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4697): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4697): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4697): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 4697): onServiceConnected
W/Babel   ( 4697): Attempted to change video mute state without an active call.
,I/AudioManager( 4320): getMode name:com.lge.qremote
I/AudioManager( 4320): getMode name:com.lge.qremote
,I/AudioManager( 4320): getMode name:com.lge.qremote
,D/UEI.SmartControl( 4729):  ---- Has DB8: true
,I/art     (  309): Background concurrent mark sweep GC freed 796(33KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 10.383ms total 31.664ms
,I/ActivityManager(  941): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=4770 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
D/UEI.SmartControl( 4729): QS start statue = true Error code = 0
D/UEI.SmartControl( 4729): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 4729): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 4729): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 4729): IRRCPlayer_nativeInit ++ 
D/irrcClient( 4729): IrrcClient ++ 
D/irrcClient( 4729): getIrrcService ++ 
D/irrcClient( 4729): getIrrcService -- 
D/irrcClient( 4729): IrrcClient -- 
W/irrc_jni( 4729): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 4729): Services init done
D/UEI.SmartControl( 4729): QS Service init finished
D/UEI.SmartControl( 4729): QS Service version name: 0.1.73
I/UEI.SmartControl( 4729): Device manager: loading config....
,D/UEI.SmartControl( 4729): QS Service version code: 1073
D/UEI.SmartControl( 4729): Service requested: Control
D/UEI.SmartControl( 4729): Config is loaded...
I/ActivityManager(  941): Killing 4400:com.lge.sync/1000 (adj 15): empty #11
,D/UEI.SmartControl( 4729): -----IControl: 11
D/UEI.SmartControl( 4729): Caller: com.lge.qremote
D/UEI.SmartControl( 4729): ------------ IControl registerCallback...
I/UEI.SmartControl( 4729): Registering callback...
D/UEI.SmartControl( 4729): -----IControl: 19
D/UEI.SmartControl( 4729): Caller: com.lge.qremote
I/UEI.SmartControl( 4729): Registering Services Ready callback...
I/UEI.SmartControl( 4729): Notify client services are ready...
,D/UEI.SmartControl( 4729): -----IControl: 8
D/UEI.SmartControl( 4729): Caller: com.lge.qremote
D/UEI.SmartControl( 4729):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 4729): Notify AllClients services are ready: 0
D/jxcore_app_log( 4605): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622966656
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4605): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4605):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4605):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4605):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4605):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4605): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b049aa added. We now have 1 listener(s)
,W/libprocessgroup(  941): failed to open /acct/uid_1000/pid_4400/cgroup.procs: No such file or directory
D/UEI.SmartControl( 4729): Internal service binding...
D/BluetoothManagerService(  941): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4605): setBluetoothMacAddress: F8:95:C7:87:85:54
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4605): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4605): setIdentityString: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
I/NotificationManager( 4697): com.google.android.talk: cancel(10436) by com.google.android.talk
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4605): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4605):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4605):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4605):     - Bluetooth MAC address: F8:95:C7:87:85:54
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4605):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4605):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4605):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4605):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4605):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4605):     - Scan report delay in milliseconds: 500
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4605): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ca15676 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4605): addListener: New listener added - the number of listeners is now 1
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4605): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 4605): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
,W/System.err( 4605): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 4605): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 4605): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 4605): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 4605): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 4605): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 4605): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
,W/System.err( 4605): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 4605): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 4605): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4605): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4605): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4605): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/JX-Cordova( 4605): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4605): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4605): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e4df477 added. We now have 2 listener(s)
D/BluetoothManagerService(  941): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4605): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4605): setIdentityString: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4605): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4605): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32b788e4 added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4605): addListener: New listener added - the number of listeners is now 1
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4605): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 4605): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 4605): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 4605): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 4605): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 4605): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 4605): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 4605): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 4605): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 4605): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 4605): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 4605): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4605): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4605): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4605): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ResourcesManager( 4697): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4697): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 4770): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4770): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 4770): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
V/JNIHelp ( 4697): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 4697): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 4697): Installed default security provider GmsCore_OpenSSL
E/PhoneInterfaceManager( 1747): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,W/VideoCapabilities( 4697): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4697): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4697): Unrecognized profile 2130706433 for video/avc
I/LGEmail ( 4770): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 4770): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/NotificationManager( 4697): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/Babel   ( 4697): connection state changed from UNKNOWN to DISCONNECTED
,I/art     (  941): Explicit concurrent mark sweep GC freed 18694(962KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/33MB, paused 1.853ms total 148.770ms
,I/[LGHome]EVENT( 1874): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1874): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1874): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/QCNEJ   ( 1837): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[SystemUI]QPairHandler( 1370): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]QSlideListController( 1370): onReceive = android.intent.action.PACKAGE_CHANGED
I/InputReader(  941): Reconfiguring input devices.  changes=0x00000010
,W/[SystemUI]QSlideLoader( 1370): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
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
,D/administrator(  941): Handling package changes for user 0
,I/art     ( 1784): CheckpointMarkThreadRoots callback created = 0xb042d3d0
I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/art     ( 1784): CheckpointMarkThreadRoots callback created = 0xb042d780
I/PackageChangeReceiver( 4770): intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
,I/ActivityManager(  941): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=4804 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  941): Killing 3198:com.android.defcontainer/u0a4 (adj 15): empty #11
I/ActivityManager(  941): Process com.lge.bnr (pid 4454) has died
,W/libprocessgroup(  941): failed to open /acct/uid_10004/pid_3198/cgroup.procs: No such file or directory
W/ResourcesManager(  941): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/NotificationService(  941): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  941): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  941): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/ActivityManager(  941): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=4824 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/BackupManagerService(  941): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  941): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  941): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@129f906e
,I/AppUp4:AppBoxCP( 4824): onCreate
,W/AppUp4:DB( 4824):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 4824):  setFingerPrint start
,I/AppUp4:DB( 4824):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/ActivityManager(  941): Process com.google.android.music:main (pid 4471) has died
I/AppUp4:DB( 4824):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 4824):  SDK version = 0
I/AppUp4:DB( 4824):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 4824): AppBoxApplication onCreate()
D/LCardEmulationManager( 1784): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1784): getDefaultRoute
W/ResourceType(  941): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1874): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1728): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ActivityManager(  941): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=4842 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 4842): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4842): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 4842): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
D/LocationProviderProxy(  941): applying state to connected service
I/ActivityManager(  941): Process com.google.android.gm (pid 4577) has died
,I/AppConfig( 4842): Total System Memory = 906309632
,I/GalleryUtils( 4842): Application Heap = 96 MB
I/AppConfig( 4842): App Tier : NOT_DEF
D/SystemHelper( 4842): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  941): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=4861 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ResourcesManager( 4861): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4861): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 4861): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 4861): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 4861): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 4861): BUILD Country: EU
I/SystemConfig( 4861): BUILD Operator: OPEN
,I/SystemConfig( 4861): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 4861): existFile = false
I/SystemConfig( 4861): canReadFile = false
I/SystemConfig( 4861): systemFeature RCS result false
D/SystemConfig( 4861): refreshRcsSupport() :false
,I/ActivityManager(  941): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=4887 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  941): Killing 4421:com.lge.clock/u0a10 (adj 15): empty #11
W/libprocessgroup(  941): failed to open /acct/uid_10010/pid_4421/cgroup.procs: No such file or directory
,I/LockScreenSettings( 4887): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/LockScreenSettings( 4887): New app installed broadcast received ..
,I/LockScreenSettings( 4887): Number of installed packages  1
I/ActivityManager(  941): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=4904 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  941): Killing 4535:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/libprocessgroup(  941): failed to open /acct/uid_10014/pid_4535/cgroup.procs: No such file or directory
,D/EulaProviderUpdateObserver( 4904): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 4904): uri : package:com.test.thalitest
,I/ActivityManager(  941): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=4921 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  941): Killing 4660:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  941): failed to open /acct/uid_10038/pid_4660/cgroup.procs: No such file or directory
,D/[BNRAppListMgrReceiver]( 4921): android.intent.action.PACKAGE_ADDED : com.test.thalitest
,W/MainApplication( 4921): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,I/ActivityManager(  941): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4938 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  941): Killing 4729:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
I/art     (  309): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 21.678ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 21.537ms
,W/System.err( 4320): android.os.DeadObjectException
W/System.err( 4320): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 4320): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 4320): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 4320): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 4320): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 4320): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 4320): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4320): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4320): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4320): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 4320): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4320): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4320): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 4320): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 4320): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 4320): android.os.DeadObjectException
W/System.err( 4320): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 4320): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 4320): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 4320): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 4320): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 4320): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 4320): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4320): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4320): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4320): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 4320): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4320): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4320): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 4320): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 4320): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 21.224ms
,W/libprocessgroup(  941): failed to open /acct/uid_10089/pid_4729/cgroup.procs: No such file or directory
W/ActivityManager(  941): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/ActivityManager(  941): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=4955 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 4955): Quickset Services start...
,I/UEI.SmartControl( 4955): Manufacture = LGE
D/UEI.SmartControl( 4955): File observer start...
E/UEI.SmartControl( 4955): IR Port is disabled: false
D/UEI.SmartControl( 4955): Starting file observer...
D/UEI.SmartControl( 4955): Extracting JNI libs...
D/UEI.SmartControl( 4955): --- this system supports 32-bit or 64-bit only
,D/UEI.SmartControl( 4955): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 4955): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 4955): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 4955): --- Selecting new region: 2
I/UEI.SmartControl( 4955): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 4955): Platform has CIR...
D/UEI.SmartControl( 4955): NO CIR support, need to check package...
I/UEI.SmartControl( 4955): Model: LG-D722 uses JNI
D/UEI.SmartControl( 4955): QS Service created
E/UEI.SmartControl( 4955): QS start get config
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 73060298154; DSPS: 2492039; Offset : -3000199425
,D/UEI.SmartControl( 4955): Loading JNI Libs...
,D/UEI.SmartControl( 4955):  configuring local db...
D/Finsky  ( 4938): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/UEI.SmartControl( 4955):  ---- Has DB8: true
,D/Finsky  ( 4938): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
D/UEI.SmartControl( 4955): QS start statue = true Error code = 0
D/UEI.SmartControl( 4955): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 4955): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 4955): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 4955): IRRCPlayer_nativeInit ++ 
D/irrcClient( 4955): IrrcClient ++ 
D/irrcClient( 4955): getIrrcService ++ 
D/irrcClient( 4955): getIrrcService -- 
D/irrcClient( 4955): IrrcClient -- 
W/irrc_jni( 4955): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 4955): Services init done
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/UEI.SmartControl( 4955): Device manager: loading config....
W/Settings( 4938): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/UEI.SmartControl( 4955): QS Service init finished
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 4955): QS Service version name: 0.1.73
W/Settings( 4938): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/UEI.SmartControl( 4955): QS Service version code: 1073
I/NotificationManager( 4938): com.android.vending: cancel(-1050172287) by com.android.vending
D/UEI.SmartControl( 4955): Service requested: Control
D/UEI.SmartControl( 4955): Config is loaded...
I/NotificationManager(  941): android: cancelAsUser(2) by android
,D/UEI.SmartControl( 4955):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 4955): Notify AllClients services are ready: 0
,V/DownloadManager( 3097): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
I/NotificationManager( 4938): com.android.vending: cancel(1003285959) by com.android.vending
V/DownloadManager( 3097): created cursor android.database.sqlite.SQLiteCursor@1dfdc3d9 on behalf of 4938
D/UEI.SmartControl( 4955): Request IControl service: devices are loaded...
,I/ActivityManager(  941): Killing 4320:com.lge.qremote/u0a106 (adj 15): empty #11
D/libc-netbsd( 4938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  276): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  941): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/UEI.SmartControl( 4955): Internal service binding...
,W/libprocessgroup(  941): failed to open /acct/uid_10106/pid_4320/cgroup.procs: No such file or directory
D/Finsky  ( 4938): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4938): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 4938): Skipping gmscore version check
I/ActivityManager(  941): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5013 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,D/Finsky  ( 4938): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/ActivityManager(  941): Killing 4770:com.lge.email/u0a21 (adj 15): empty #11
,D/Finsky  ( 4938): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
W/libprocessgroup(  941): failed to open /acct/uid_10021/pid_4770/cgroup.procs: No such file or directory
D/Finsky  ( 4938): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  941): Killing 4804:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,W/libprocessgroup(  941): failed to open /acct/uid_10009/pid_4804/cgroup.procs: No such file or directory
,I/GAv4    ( 5013): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5013):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5013):   adb logcat -s GAv4
,W/GAv4    ( 5013): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5013): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5013): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 5013): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
,D/Finsky  ( 4938): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  941): RTC_WAKEUP set : Alarm{c3c5c8a type 0 when 1457599039959 com.android.vending} when 1457599039959
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  941): android: cancelAsUser(2) by android
I/art     ( 5013): CheckpointMarkThreadRoots callback created = 0xb050c9c0
,I/art     ( 5013): CheckpointMarkThreadRoots callback created = 0xb050c9a0
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5013): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
D/libc-netbsd( 4938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  276): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  276): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  941): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/ResourcesManager( 5013): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5013): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/Finsky  ( 4938): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/ActivityManager(  941): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5060 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  941): android: cancelAsUser(2) by android
D/libc-netbsd( 4938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/ResourcesManager( 5060): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/JNIHelp ( 5013): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/ActivityManager(  941): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5082 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/System  ( 5013): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5013): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  941): android: cancelAsUser(2) by android
,D/libc-netbsd( 4938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/Finsky  ( 4938): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
W/ResourcesManager( 5082): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5082): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 5082): VM with version 2.1.0 has multidex support
I/MultiDex( 5082): install
I/MultiDex( 5082): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 5082): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5082): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5082): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@31c46402: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5082): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5082): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5082): com.google.android.gms: cancel(39789) by com.google.android.gms
D/ChimeraCfgMgr( 5082): Reading stored module config
,D/ChimeraCfgMgr( 5082): Loading module com.google.android.gms.car from APK com.google.android.gms
,D/NativeLibraryUtils( 5082): Install completed successfully. count=14 extracted=0
,I/chromium( 4605): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
,I/chromium( 4605): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
I/art     (  941): Explicit concurrent mark sweep GC freed 28031(1387KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 1.959ms total 159.126ms
,D/CAR.SERVICE( 5082): Connecting to CarCallService...
I/art     ( 5082): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5082): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/PackageBroadcastService( 4014): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 4014): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4014): Loading module APK com.google.android.play.games
D/CAR.SERVICE( 5082): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 5082): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 5082): Creating a new PhoneAdapter instance
W/ActivityManager(  941): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5082): setListener: com.google.android.gms.car.dn@185622b9
W/ActivityManager(  941): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5082): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 5082): Starting CarCallService with initial phone null
I/NotificationManager( 5082): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/UpdateIcingCorporaServi( 1962): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/CAR.SERVICE( 5082): Package validated; name: com.android.vending
,I/NotificationManager( 4938): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 4938): [1] GearheadStateMonitor.access$100: mIsProjecting:false
D/ChimeraCfgMgr( 4014): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4014): Module APK com.google.android.play.games already loaded
,I/UpdateIcingCorporaServi( 1962): UpdateCorporaTask done [took 169 ms] updated apps [took 169 ms] 
D/ChimeraCfgMgr( 4014): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 4014): Submit a task: k
,I/Icing   ( 4014): Storage manager: low false usage 1.72MB avail 2.37GB capacity 4.06GB
,D/ChimeraCfgMgr( 4014): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 4014): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 4014): Processing package: com.test.thalitest
D/GassUtils( 4014): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 4014): Found info for package com.test.thalitest in db.
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  941): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ActivityManager(  941): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5150 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/BaseAppContext( 4014): Using Auth Proxy for data requests.
,W/BaseAppContext( 4014): Using Auth Proxy for data requests.
I/PeopleDatabaseHelper( 4014): cleanUpNonGplusAccounts done.
W/BaseAppContext( 4014): Using Auth Proxy for data requests.
,W/BaseAppContext( 4014): Using Auth Proxy for data requests.
,W/BaseAppContext( 4014): Using Auth Proxy for data requests.
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  941): android: cancelAsUser(2) by android
D/libc-netbsd( 4938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/Finsky  ( 4938): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/Finsky  ( 4938): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  941): RTC_WAKEUP set : Alarm{40a1584 type 0 when 1457599041555 com.android.vending} when 1457599041555
D/Finsky  ( 4938): [1] DailyHygiene.reschedule: Scheduling new run in 277 minutes (failures=4)
,D/WearableService( 1728): callingUid 10006, callindPid: 1728
,D/DeviceConnectionService( 1728): client connected with version: 8296000
W/ActivityManager(  941): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/Finsky  ( 4938): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 4938): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/ActivityManager(  941): Killing 4842:com.android.gallery3d/u0a23 (adj 15): empty #11
I/ActivityManager(  941): Killing 4824:com.lge.appbox.client/u0a11 (adj 15): empty #12
,W/libprocessgroup(  941): failed to open /acct/uid_10023/pid_4842/cgroup.procs: No such file or directory
,W/libprocessgroup(  941): failed to open /acct/uid_10011/pid_4824/cgroup.procs: No such file or directory
I/Gmail   ( 5150): getAccountsCursor
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 5150): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  941): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 5150): Error finding the version of the Email provider.....
E/Gmail   ( 5150): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5150): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5150): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5150): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5150): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5150): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5150): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5150): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 5150): We do not support migrating this version of the Email provider.
W/ActivityManager(  941): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 5150): getAccountsCursor
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  941): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 5150): Observing account changes for notifications
,I/Icing   ( 4014): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  941): Killing 4861:com.android.contacts/u0a18 (adj 15): empty #11
,W/libprocessgroup(  941): failed to open /acct/uid_10018/pid_4861/cgroup.procs: No such file or directory
,I/Gmail   ( 5150): notifyAccountChanged
I/Gmail   ( 5150): getAccountsCursor
I/Gmail   ( 5150): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5150): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/ActivityManager(  941): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=5193 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/Gmail   ( 5150): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5150): calculateUnknownSyncRationalesAndPurgeInBackground: running
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2000): Explicit concurrent mark sweep GC freed 3248(128KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 532us total 47.738ms
,W/ResourcesManager( 5193): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/Icing   ( 4014): Internal init done: storage state 0
,I/Icing   ( 4014): Post-init done
,D/BluetoothManagerService(  941): Message: 20
D/BluetoothManagerService(  941): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@346c3e49:true
D/BluetoothAdapter( 5193): 481957868: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 5193): 481957868: getState() :  mService = null. Returning STATE_OFF
D/ChimeraCfgMgr( 4014): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4014): Module APK com.google.android.play.games already loaded
V/LGMDMManager( 5193): Create singleton instance
,I/Gmail   ( 5150): getAccountsCursor
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AudioManager( 5193): getMode name:com.lge.qremote
,D/UEI.SmartControl( 4955): -----IControl: 11
D/UEI.SmartControl( 4955): Caller: com.lge.qremote
D/UEI.SmartControl( 4955): ------------ IControl registerCallback...
I/UEI.SmartControl( 4955): Registering callback...
D/UEI.SmartControl( 4955): -----IControl: 19
,D/UEI.SmartControl( 4955): Caller: com.lge.qremote
I/UEI.SmartControl( 4955): Registering Services Ready callback...
I/UEI.SmartControl( 4955): Notify client services are ready...
D/UEI.SmartControl( 4955): -----IControl: 8
D/UEI.SmartControl( 4955): Caller: com.lge.qremote
I/ActivityManager(  941): Killing 4887:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/libprocessgroup(  941): failed to open /acct/uid_10069/pid_4887/cgroup.procs: No such file or directory
,I/NotificationManager( 4697): com.google.android.talk: cancel(8) by com.google.android.talk
,I/ActivityManager(  941): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5220 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/AppUp4:AppBoxCP( 5220): onCreate
W/AppUp4:DB( 5220):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 5220):  setFingerPrint start
I/AppUp4:DB( 5220):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 5220):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5220):  SDK version = 0
I/AppUp4:DB( 5220):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 5220): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 5220): onReceive
,I/AppUp4:CustModeStarterReceiver( 5220): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 5220): Context : android.app.ReceiverRestrictedContext@956e2f2
D/AppUp4:CustFacade( 5220): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5220): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 5220): begin check event
,I/AppUp4:CustModeStarterReceiver( 5220): Event For Nothing, skip.
I/ActivityManager(  941): Killing 4904:com.lge.eula/1000 (adj 15): empty #11
W/libprocessgroup(  941): failed to open /acct/uid_1000/pid_4904/cgroup.procs: No such file or directory
,I/ActivityManager(  941): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5239 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 5239): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5239): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5239): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/AppConfig( 5239): Total System Memory = 906309632
,I/GalleryUtils( 5239): Application Heap = 96 MB
I/AppConfig( 5239): App Tier : NOT_DEF
D/SystemHelper( 5239): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  941): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5264 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  941): Killing 4921:com.lge.bnr/1000 (adj 15): empty #11
,W/libprocessgroup(  941): failed to open /acct/uid_1000/pid_4921/cgroup.procs: No such file or directory
,W/ResourcesManager( 5264): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5264): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 5264): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 5264): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5264): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 5264): BUILD Country: EU
I/SystemConfig( 5264): BUILD Operator: OPEN
,I/SystemConfig( 5264): pm.hasSystemFeature(com.lge.ims.rcs) = false
,I/SystemConfig( 5264): existFile = false
I/SystemConfig( 5264): canReadFile = false
I/SystemConfig( 5264): systemFeature RCS result false
D/SystemConfig( 5264): refreshRcsSupport() :false
,I/ActivityManager(  941): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5283 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  941): Killing 5013:com.google.android.apps.docs/u0a58 (adj 15): empty #11
W/libprocessgroup(  941): failed to open /acct/uid_10058/pid_5013/cgroup.procs: No such file or directory
,I/art     (  941): Explicit concurrent mark sweep GC freed 19141(951KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 2.165ms total 139.399ms
,I/Icing   ( 4014): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/LockScreenSettings( 5283): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 5283): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5283): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5283): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5283): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5283): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/UpdateIcingCorporaServi( 1962): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  941): Killing 2000:com.google.process.gapps/u0a6 (adj 15): empty #11
,D/PackageBroadcastService( 4014): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
D/Icing   ( 4014): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 4014): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/UpdateIcingCorporaServi( 1962): UpdateCorporaTask done [took 71 ms] updated apps [took 71 ms] 
,W/libprocessgroup(  941): failed to open /acct/uid_10006/pid_2000/cgroup.procs: No such file or directory
,I/PackageBroadcastService( 4014): Null package name or gms related package.  Ignoreing.
E/MDM     ( 1728): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1728): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 4014): Restart initialization of location
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1728): com.google.android.gms: cancel(0) by com.google.android.gms
,I/Icing   ( 4014): updateResources: need to parse f{com.google.android.gms}
W/GCoreFlp( 1728): No location to return for getLastLocation()
W/FusedLocationProvider( 1728): location=null
D/Finsky  ( 4938): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
,D/Finsky  ( 4938): [580] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AudioManager( 5193): getMode name:com.lge.qremote
I/NotificationManager(  941): android: cancelAsUser(2) by android
,D/libc-netbsd( 4938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  276): App 10036 tries DNS query. Accept family:0 protocol:0
I/AudioManager( 5193): getMode name:com.lge.qremote
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  941): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/NotificationManager( 1962): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/AudioManager( 5193): getMode name:com.lge.qremote
,I/AudioManager( 5193): getMode name:com.lge.qremote
,D/UEI.SmartControl( 4955): Internal timer expired: 1
,I/art     ( 1728): Explicit concurrent mark sweep GC freed 30500(1956KB) AllocSpace objects, 19(304KB) LOS objects, 39% free, 13MB/22MB, paused 1.216ms total 98.452ms
,I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
,I/Icing   ( 4014): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4014): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,D/CAR.SERVICE( 5082): mConnectedToCar = false, abort
,E/ActivityThread( 5082): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3026481 that was originally bound here
E/ActivityThread( 5082): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3026481 that was originally bound here
E/ActivityThread( 5082): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5082): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5082): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5082): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5082): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5082): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5082): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5082): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5082): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5082): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 5082): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 5082): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 5082): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 5082): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 5082): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 5082): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 5082): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5082): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5082): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5082): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5082): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5082): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5082): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 5082): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3e042c80 that was originally bound here
E/ActivityThread( 5082): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3e042c80 that was originally bound here
E/ActivityThread( 5082): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5082): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5082): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5082): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5082): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5082): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5082): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5082): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 5082): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 5082): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 5082): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 5082): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 5082): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 5082): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 5082): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 5082): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5082): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5082): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5082): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5082): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5082): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5082): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  941): Unbind failed: could not find connection for android.os.BinderProxy@2daaf56a
I/CheckinService( 4014): Done disabling old GoogleServicesFramework version
I/GAV2    ( 5150): Thread[GAThread,5,main]: No campaign data found.
,D/InitAlarmsService( 3567): Clearing and rescheduling alarms.
,I/ActivityManager(  941): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5347 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 40.787ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 54.247ms
,W/ResourcesManager( 5347): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 20.984ms
,D/CalendarProvider2( 5347): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@33efbda7
,D/CalendarProvider2( 5347): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 5347): Created com.android.providers.calendar.CalendarAlarmManager@2e28bfc0(com.android.providers.calendar.CalendarProvider2@33efbda7)
,D/CalendarProvider2( 5347): Scheduling check of next Alarm
D/CalendarProvider2( 5347): SCHEDULE_ALARM_REMOVE
,I/ActivityManager(  941): Killing 3567:com.android.calendar/u0a13 (adj 15): empty #11
W/libprocessgroup(  941): failed to open /acct/uid_10013/pid_3567/cgroup.procs: No such file or directory
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/charger_monitor(  486): init target 500000
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/WifiController(  941): battery changed pluggedType: 2
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
,I/CalendarProvider2( 5347): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 5347): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  941): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=5384 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  941): Killing 5220:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  941): failed to open /acct/uid_10011/pid_5220/cgroup.procs: No such file or directory
I/ActivityManager(  941): Killing 5239:com.android.gallery3d/u0a23 (adj 15): empty #11
W/ResourcesManager( 5384): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/libprocessgroup(  941): failed to open /acct/uid_10023/pid_5239/cgroup.procs: No such file or directory
,I/ActivityManager(  941): Killing 5264:com.android.contacts/u0a18 (adj 15): empty #11
W/libprocessgroup(  941): failed to open /acct/uid_10018/pid_5264/cgroup.procs: No such file or directory
,D/CalendarApplication( 5384): CalendarApplication.onCreate()
D/PreferenceKeysParser( 5384): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 5384): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@2af555fd, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@956e2f2, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@2c508d43, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@2e28bfc0, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@204654f9, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1d6c3c3e, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@1764ba9f, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@1cba17ec, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@1b0e47b5, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@9ebde4a, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@e6461bb, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@826c6d8, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@2c28aa31, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@4119516, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@3bed5e97, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@16ad7884, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@3cacb86d, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@709eca2, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@2c9f4d33, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@31cb98f0, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@35e96e69, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@223e30ee, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@d77898f, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@1b69541c, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@2d218825, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@20606dfa, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@33ed2fab, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@29c59608, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@f0781a1, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@13376fc6, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@bcd1b87, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@16220ab4, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@6f996dd, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@102ac252, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@6d5e923, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@a2f1e20, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1dfdc3d9, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@298eb19e, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2a13f47f, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1837fc4c, lg_preferences_alerts_vibratetype=com.android.calendar.ada,ptation.PreferenceKey$KeyData@d7dc495, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@30b049aa, l
,D/GeneralPreferenceUtils( 5384): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 5384): [init]
I/Config  ( 5384): LGCalendar ver.4.40.17
I/Config  ( 5384): start check model
I/Config  ( 5384): start check native_ca
I/Config  ( 5384): Config Operator=OPEN, Country=EU
D/Config  ( 5384): [setDefaultValuesToPref]
D/Config  ( 5384): [parseProfiles]
D/ProfilesParser( 5384): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 5384): [debug_displayParseInfos] profile.operator = null
D/Config  ( 5384): [updateProfiletoCountryInfo]
,D/GeneralPreference( 5384): [checkAndMigrateOldPreference]
D/AlertReceiver( 5384): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
I/InitNotificationRingtoneService( 5384): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 5384): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
I/AlertUtils( 5384): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 5384): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 5384): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 5384): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 5384): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 5384): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 5384): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 5384): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 5384): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 5384): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 5384): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 5384): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 5384): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 5384): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 5384): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 5384): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 5384): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 5384): set default noti to content://media/internal/audio/media/38
,I/InitNotificationRingtoneService( 5384): End InitializeAlertRingtoneService.onHandleIntent
W/HolidayIntentService( 5384): onHandleIntent
,D/HolidayDataLoader( 5384): readJsonAsset : holiday.json
D/AlertService( 5384): 0 Action = android.intent.action.PROVIDER_CHANGED
E/AgendaWidgetManager( 5384): [updateWidgets] 
D/MonthWidgetProvider( 5384): [onReceive]
D/CalendarWidgetProvider( 5384): [onReceive]
D/CalendarWidgetProvider( 5384): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 5384): [onCreate] mContext.getPackageName() = com.android.calendar
,D/WeekWidgetProvider( 5384): [onReceive]
D/CalendarWidgetProvider( 5384): [onReceive]
D/CalendarWidgetProvider( 5384): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 5384): [onCreate] mContext.getPackageName() = com.android.calendar
I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
,E/HolidayIntentService( 5384): onHandleIntent:holiday data empty
,V/AlarmManager(  941): ELAPSED_WAKEUP set : Alarm{18238d1a type 2 when 87072 com.android.providers.calendar} when 87072
,D/CalendarProviderBroadcastReceiver( 5347): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 5347): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 5347): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 5347): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 5347): [getOrCreateCalendarAlarmManager]
D/CalendarProvider2( 5347): [IntentService] Release Lock
,D/CalendarProvider2( 5347): CalendarProviderIntentService.onDestroy()
D/libc-netbsd(  941): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  941): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  941): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  941): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  276): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=0, netid=0
,D/DSQN    (  941): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/AlertService( 5384): Beginning updateAlertNotification
,I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
D/AlertService( 5384): No fired or scheduled alerts
,I/NotificationManager( 5384): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 5384): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 5384): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 5384): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 5384): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5384): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 5384): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 5384): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 5384): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 5384): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 5384): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 5384): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 5384): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 5384): com.android.calendar: cancel(13) by com.android.calendar
,I/NotificationManager( 5384): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 5384): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 5384): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 5384): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5384): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 5384): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 5384): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 5384): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 5384): No events found starting within 1 week.
,I/ActivityManager(  941): Killing 5283:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/libprocessgroup(  941): failed to open /acct/uid_10069/pid_5283/cgroup.procs: No such file or directory
,V/AlarmManager(  941): RTC_WAKEUP set : Alarm{39780341 type 0 when 1457599056146 com.android.vending} when 1457599056146
,D/Finsky  ( 4938): [570] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4938): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 93061915239; DSPS: 3147450; Offset : -3000139336
,I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  941): ELAPSED_WAKEUP set : Alarm{e5d60e6 type 2 when 98328 com.google.android.gms} when 98328
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  941): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
,I/rmt_storage(  273): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  273): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  273): wakelock acquired: 1, error no: 42
,I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  273): 
I/rmt_storage(  273): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
,I/ActivityManager(  941): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5430 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  941): Killing 5060:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  941): failed to open /acct/uid_10086/pid_5060/cgroup.procs: No such file or directory
,I/GservicesProvider( 5430): Gservices pushing to system: true; secure/global: true
,I/GoogleHttpClient( 5430): GMS http client unavailable, use old client
,I/GoogleHttpClient( 5430): GMS http client unavailable, use old client
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,W/ContextImpl( 3397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 113066408580; DSPS: 3802958; Offset : -3000162649
,I/MusicWidget( 2656): mDelayedStopHandler : unbind
I/MusicBrowser( 2720): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2720): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2720): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2720): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2720): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2720): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2720): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2720): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  941):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@223e30eecom.lge.music.MediaPlaybackService$6@d77898f
,D/MusicBrowser( 2720): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2720): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2720): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2720): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2720): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@1b0e47b5
,I/MusicBrowser( 2720): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2720): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2720): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2720): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2720): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2720): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2720): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2720): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2720): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2720): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2720): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,I/MusicBrowser( 2720): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2720): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2720): reset
V/MediaPlayer[Native]( 2720): setListener
,V/MediaPlayer[Native]( 2720): disconnect
V/MediaPlayer[Native]( 2720): destructor
V/AudioFlinger(  280): releasing 19 from 2720 for -1
V/AudioFlinger(  280):  decremented refcount to 0
V/AudioFlinger(  280): purging stale effects
V/MediaPlayer[Native]( 2720): disconnect
D/MusicBrowser( 2720): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2720): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2720): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2720): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2720): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2720): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2720): [SmartShareManagerClient] unregisterListener: 459887644
W/SmartShareClient( 2720): [SmartShareManagerClient] unregisterListener invalid listener: 459887644
I/SmartShareClient( 2720): [SmartShareManagerClient] terminate service: 2720/MediaPlaybackService/743476547
E/HomeCloudIF( 2720): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2720): [SmartShareManagerClient] unbindService context:android.app.Application@2d218825
V/CloudHub( 2720): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2720): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2720): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
,I/MusicBrowser( 2720): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2720): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  941): Killing 5082:com.google.android.gms:car/u0a6 (adj 15): empty #11
I/CloudHub( 2720): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29985
,W/libprocessgroup(  941): failed to open /acct/uid_10006/pid_5082/cgroup.procs: No such file or directory
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,D/PowerManagerServiceEx(  941): acquireWakeLockInternal: lock=923706738, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=941
,D/WeatherService( 2703): 2 : TimeTick Intent has been received, Time(hour:min:sec) 9:38:0
D/WeatherService( 2703): 2 : TimeTick Intent And Screen On
D/WeatherService( 2703): 2 : SDK version : 21
W/ActivityManager(  941): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2703): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2703): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2703): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2703): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2703): 2 : This is isUpdating : false
D/WeatherService( 2703): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2703): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2703): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2703): 2 : Fixed theme : optimus
D/WeatherReflect( 2703): 2 : Map key string is -2
,D/lim     ( 2703): 2 : time = 09:38
I/WeatherReflect( 2703): Model Name : LG-D722
D/WeatherTheme( 2703): 2 : Different view - status_min_formatted : 37 != 38
D/WeatherTheme( 2703): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2703): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2703): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2703): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2703): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2703): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
,I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
D/Weather4x2_optimus( 2703): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2703): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2703): forecast size is 0
D/Theme   ( 2703): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2703): EnableTheme(home): com.lge.launcher2.theme.optimus
,D/Theme   ( 2703): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2703): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2703): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2703): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2703): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2703): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2703): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2703): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2703): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2703): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2703): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2703): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2703): setTouchIntent, appWidgetId: 2
,D/Theme_WeatherAncestor_optimus( 2703): url is : null
D/Theme   ( 2703): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2703): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2703): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2703): 2 : update view, appWidgetId: 2
D/WeatherService( 2703): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 9:38:0
D/PowerManagerServiceEx(  941): releaseWakeLockInternal: lock=923706738 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1874): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1874): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/CloudHub( 2720): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19944
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): init target 500000
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  941): battery changed pluggedType: 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 128068437909; DSPS: 4294546; Offset : -3000210390
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/CloudHub( 2720): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
I/CloudHub( 2720): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,V/AlarmManager(  941): ELAPSED_WAKEUP set : Alarm{fd15dc3 type 2 when 143538 com.google.android.gms} when 143538
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  941): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 145571978673; DSPS: 4868102; Offset : -3000207763
,I/PowerManagerService(  941): ALS enabled for SRE
D/PowerManagerServiceEx(  941): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (26538 ms ago)
,D/qdlights(  941): set_light_backlight: 253
,D/qdlights(  941): set_light_backlight: 250
D/qdlights(  941): set_light_backlight: 247
,D/qdlights(  941): set_light_backlight: 243
,D/qdlights(  941): set_light_backlight: 240
,D/qdlights(  941): set_light_backlight: 237
,D/qdlights(  941): set_light_backlight: 233
,D/qdlights(  941): set_light_backlight: 230
,D/qdlights(  941): set_light_backlight: 227
,D/qdlights(  941): set_light_backlight: 223
,D/qdlights(  941): set_light_backlight: 220
,D/qdlights(  941): set_light_backlight: 217
,D/qdlights(  941): set_light_backlight: 213
,D/qdlights(  941): set_light_backlight: 210
,D/qdlights(  941): set_light_backlight: 207
,D/qdlights(  941): set_light_backlight: 203
,D/qdlights(  941): set_light_backlight: 200
,D/qdlights(  941): set_light_backlight: 197
,D/qdlights(  941): set_light_backlight: 193
,D/qdlights(  941): set_light_backlight: 190
,D/qdlights(  941): set_light_backlight: 187
,D/qdlights(  941): set_light_backlight: 183
,D/qdlights(  941): set_light_backlight: 180
,D/qdlights(  941): set_light_backlight: 177
,D/qdlights(  941): set_light_backlight: 173
,D/qdlights(  941): set_light_backlight: 170
,D/qdlights(  941): set_light_backlight: 167
,D/qdlights(  941): set_light_backlight: 163
,D/qdlights(  941): set_light_backlight: 160
,D/qdlights(  941): set_light_backlight: 157
,D/qdlights(  941): set_light_backlight: 153
,D/qdlights(  941): set_light_backlight: 150
,D/qdlights(  941): set_light_backlight: 147
,D/qdlights(  941): set_light_backlight: 143
,D/qdlights(  941): set_light_backlight: 140
,D/qdlights(  941): set_light_backlight: 137
,D/qdlights(  941): set_light_backlight: 133
,D/qdlights(  941): set_light_backlight: 130
,D/qdlights(  941): set_light_backlight: 127
,D/qdlights(  941): set_light_backlight: 123
,D/qdlights(  941): set_light_backlight: 120
,D/qdlights(  941): set_light_backlight: 117
,D/qdlights(  941): set_light_backlight: 113
,D/qdlights(  941): set_light_backlight: 110
,D/qdlights(  941): set_light_backlight: 107
,D/qdlights(  941): set_light_backlight: 103
,D/qdlights(  941): set_light_backlight: 100
,D/qdlights(  941): set_light_backlight: 97
,D/qdlights(  941): set_light_backlight: 93
,D/qdlights(  941): set_light_backlight: 90
,D/qdlights(  941): set_light_backlight: 87
,D/qdlights(  941): set_light_backlight: 83
,D/qdlights(  941): set_light_backlight: 80
,D/qdlights(  941): set_light_backlight: 77
,D/qdlights(  941): set_light_backlight: 73
,D/qdlights(  941): set_light_backlight: 70
,D/qdlights(  941): set_light_backlight: 67
,D/qdlights(  941): set_light_backlight: 63
,D/qdlights(  941): set_light_backlight: 60
,D/qdlights(  941): set_light_backlight: 57
,D/qdlights(  941): set_light_backlight: 53
,D/qdlights(  941): set_light_backlight: 50
,D/qdlights(  941): set_light_backlight: 47
,D/qdlights(  941): set_light_backlight: 43
,D/qdlights(  941): set_light_backlight: 40
,D/qdlights(  941): set_light_backlight: 37
,D/qdlights(  941): set_light_backlight: 33
,D/qdlights(  941): set_light_backlight: 30
,D/qdlights(  941): set_light_backlight: 27
,D/qdlights(  941): set_light_backlight: 23
,D/qdlights(  941): set_light_backlight: 20
,D/qdlights(  941): set_light_backlight: 17
,D/qdlights(  941): set_light_backlight: 13
,D/qdlights(  941): set_light_backlight: 10
,V/AlarmManager(  941): ELAPSED_WAKEUP set : Alarm{e888640 type 2 when 129992 com.google.android.gms} when 129992
,D/libc-netbsd(  941): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  941): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  941): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  941): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  276): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=0, netid=0
,D/DSQN    (  941): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/PowerManagerService(  941): ALS enabled for SRE
D/PowerManagerServiceEx(  941): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (33535 ms ago)
I/PowerManagerService(  941): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  941): ALS enabled for SRE
,D/PowerManagerServiceEx(  941): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (33557 ms ago)
W/ContextImpl(  941): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  941): Sleeping (uid 1000)...
D/LPWGController(  941): [updateScreenState] screen on = false
,D/LPWGController(  941): disable proximity sensor
D/LPWGController(  941): enable proximity sensor
I/SensorManager(  941): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@1e88d979] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  941): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  941): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  941): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  941): activate: handle is 48, enable
,V/sensors_hal_Ctx(  941): activate sensors is 1400000000000
D/sensors_hal_Thresh(  941): enable: handle=48
I/sensors_hal_SAM(  941): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  941): waitForResponse: timeout=1000
V/sensors_hal_SAM(  941): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  941): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  941): enable: Received response: 0
D/PowerManagerServiceEx(  941): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (33604 ms ago)
I/Adreno-EGL(  941): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  941): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  941): Build Date: 03/02/15 Mon
I/Adreno-EGL(  941): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  941): Remote Branch: 
I/Adreno-EGL(  941): Local Patches: 
I/Adreno-EGL(  941): Reconstruct Branch: 
,D/PermissionCache(  248): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1860 us)
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/Sensors (  440): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  941): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  941): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  941): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  941): processInd: handle 48, count=1
V/sensors_hal_Thresh(  941): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  941): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  941): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  941): poll: count: 256
I/sensors_hal_Ctx(  941): poll: released wakelock sensor_ind
D/sensors_hal_Util(  941): waitForResponse: timeout=0
D/LPWGController(  941): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  941): current mode = 1  value = 1 1
I/LPWGController(  941): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  941): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  941): set_light_backlight: 0
,I/SensorManager(  941): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  941): activate: handle is 46, disable
V/sensors_hal_Ctx(  941): activate sensors is 1000000000000
D/sensors_hal_LP2(  941): enable: handle=46
D/sensors_hal_LP2(  941): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  941): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  248): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  248): hwc_blank: Blanking display: 0
I/DisplayManagerService(  941): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  941): Display changed displayId=0
,V/sensors_hal_SAM(  941): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  941): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1747): Display #0 changed.
,D/qdhwcomposer(  248): hwc_blank: Done blanking display: 0
,I/qdhwcomposer(  248): handle_blank_event: dpy:0 panel power state: 0
D/SurfaceControl(  941): Excessive delay in setPowerMode(): 217ms
I/QCOM PowerHAL(  941): Got set_interactive hint
,D/KeyguardViewMediator( 1370): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1330): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1370): notifyScreenOffLocked
D/SmartCoverViewMediator( 1330): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1330): handleNotifyScreenOFF
D/JX-Cordova( 4605): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4605): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4605): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@832f14d added. We now have 3 listener(s)
,D/BluetoothManagerService(  941): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/KeyguardViewMediator( 1370): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1370): handleNotifyScreenOff
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4605): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4605): setIdentityString: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4605): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4605): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31c46402 added. We now have 3 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4605): addListener: New listener added - the number of listeners is now 1
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4605): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 4605): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 4605): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 4605): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 4605): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 4605): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 4605): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 4605): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 4605): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 4605): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 4605): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 4605): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4605): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4605): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4605): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/ScreenTurnOffBySensor( 1370): unregisterProximitySensor
D/StatusBarWindowView( 1370): onScreenTurnedOff why = 3
,D/WifiServerServiceExt(  941): sendKtScanInterval  mRtspPlay : false
V/AudioFlinger(  280): setParameters(): io 0, keyvalue screen_state=on, calling pid 941
,D/audio_hw_primary(  280): adev_set_parameters: enter: screen_state=on
V/voice   (  280): voice_set_parameters: enter: screen_state=on
V/compress_voip(  280): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  280): voice_extn_compress_voip_set_parameters: exit
V/voice   (  280): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  280): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  280): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  280): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  280): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  280): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  280): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  280): adev_set_parameters: exit with code(0)
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
D/GpsLocationProvider(  941): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1837): |CORE| sendScreenState: state:true
I/LEDService( 1801): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1801): stopPatternFlashing()
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
I/LEDService( 1801): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
I/LEDService( 1801): updateLightsLocked : turn off led
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1801): RESTART MSG
,D/SplitWindow(  941): check instance of lgWin Window{2d8fc66c u0 SearchPanel}
,D/LNfcService( 1784): action : android.intent.action.SCREEN_ON
I/Cliptray Service( 1801): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/Cliptray Service( 1801): lockStatus = 0
,D/NfcServiceNXP( 1784): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1784): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1784): isRequireNfcCRouting() return true
D/LNfcService( 1784): isHCERoutingtoHost() return : true
D/NfcService( 1784): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1784): mEnableLPD: true
D/NfcService( 1784): mEnableReader: false
D/NfcService( 1784): mEnableHostRouting: true
D/NfcService( 1784): newParams.techmask= mTechMask: default
D/NfcService( 1784): mEnableLPD: true
D/NfcService( 1784): mEnableReader: false
D/NfcService( 1784): mEnableHostRouting: true
D/NfcService( 1784): screenState= 3
D/NfcService( 1784): Discovery configuration equal, not updating.
D/InputDispatcher(  941): Window went away: Window{34643533 u0 SearchPanel}
,I/[SystemUI]Clock( 1370): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1370): time changed, timezoneChanged : false
,D/Ulp_jni (  941): JNI:system_update. Event-0
,V/PhoneApp( 1747): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2703): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 9:38:40
,D/WeatherService( 2703): 2 : ACTION screen on
D/WeatherService( 2703): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2703): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2703): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 9:38:40
,D/AppCleanupService( 3860): android.intent.action.SCREEN_ON
V/AudioFlinger(  280): setParameters(): io 0, keyvalue screen_state=off, calling pid 941
,D/audio_hw_primary(  280): adev_set_parameters: enter: screen_state=off
V/voice   (  280): voice_set_parameters: enter: screen_state=off
V/compress_voip(  280): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  280): voice_extn_compress_voip_set_parameters: exit
V/voice   (  280): voice_set_parameters: exit with code(0)
,V/msm8974_platform_lge(  280): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  280): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  280): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  280): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  280): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  280): adev_set_parameters: exit with code(0)
D/WifiController(  941): CMD_SCREEN_OFF 
D/WifiController(  941): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  941): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.SCREEN_OFF
I/Sensors (  440): sns_pwr.c(301):releasing wakelock
,I/QCNEJ   ( 1837): |CORE| sendScreenState: state:false
I/LEDService( 1801): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1801): stopPatternFlashing()
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1801): clear
I/LEDService( 1801): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
I/LEDService( 1801): updateLightsLocked : turn on led
E/LEDService( 1801): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1801): Can't handle this request of patternId:0
D/LNfcService( 1784): action : android.intent.action.SCREEN_OFF
D/LEDHandler( 1801): RESTART MSG
I/Cliptray Service( 1801): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,D/NfcServiceNXP( 1784): mScreenState : 1, mInProvisionMode : false
I/[LGHome]EVENT( 1874): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1747): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2703): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 9:38:40
D/WeatherService( 2703): 2 : ACTION screen off
D/WeatherService( 2703): 2 : TimeTick Receiver Unregister
D/WeatherService( 2703): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 9:38:40
D/AppCleanupService( 3860): android.intent.action.SCREEN_OFF
D/AppCleanupService( 3860): AppUsageStatsSaveTask
,E/NxpNfcJni( 1784): getReconnectState = 0x0
,D/LCardEmulationManager( 1784): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1784): getDefaultRoute
D/LNfcService( 1784): isRequireNfcCRouting() return true
D/LNfcService( 1784): isHCERoutingtoHost() return : true
D/NfcService( 1784): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1784): mEnableLPD: true
D/NfcService( 1784): mEnableReader: false
D/NfcService( 1784): mEnableHostRouting: true
D/NfcService( 1784): newParams.techmask= mTechMask: 0
D/NfcService( 1784): mEnableLPD: true
D/NfcService( 1784): mEnableReader: false
D/NfcService( 1784): mEnableHostRouting: true
D/NfcService( 1784): screenState= 1
E/NxpNfcJni( 1784): getReconnectState = 0x0
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,D/KeyguardViewMediator( 1370): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  941): ELAPSED_WAKEUP set : Alarm{18349435 type 2 when 159517 com.android.systemui} when 159517
,D/PhoneUtils( 1747): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1747): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1747): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1747): getCallState : 0
D/PhoneUtils( 1747): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1747): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1747): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1370): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1370): doKeyguard: not showing because lockscreen is off
,D/charger_monitor(  486): init target 500000
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  941): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  941): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 165573396851; DSPS: 5523508; Offset : -3000195321
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 180575602782; DSPS: 6015103; Offset : -3000278234
,I/ClearcutLoggerApiImpl( 1728): disconnect managed GoogleApiClient
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,D/PowerManagerServiceEx(  941): acquireWakeLockInternal: lock=923706738, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=941
,V/AlarmManager(  941): ELAPSED_WAKEUP set : Alarm{298970ca type 2 when 185384 com.google.android.gms} when 185384
D/PowerManagerServiceEx(  941): releaseWakeLockInternal: lock=923706738 [*alarm*], flags=0x0
,D/charger_monitor(  486): init target 500000
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/WifiController(  941): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
V/AlarmManager(  941): ELAPSED_WAKEUP set : Alarm{161ec23b type 2 when 188192 com.google.android.gms} when 188192
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 200577979185; DSPS: 6670536; Offset : -3000129562
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 216834709712; DSPS: 7203248; Offset : -3000479139
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
,I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
D/WifiController(  941): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
,I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
,I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  941): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,V/AlarmManager(  941): ELAPSED_WAKEUP set : Alarm{3ee8dd58 type 2 when 188715 android} when 188715
,V/AlarmManager(  941): ELAPSED_WAKEUP set : Alarm{6a73eb1 type 2 when 218201 com.google.android.gms} when 218201
D/libc-netbsd(  941): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  941): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  941): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  941): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  276): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  941): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/VacuumService( 1728): Vacuum at: now=1457599195303 tag=VacuumService
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,V/AlarmManager(  941): ELAPSED_WAKEUP set : Alarm{9ba7704 type 2 when 233932 com.google.android.gms} when 233932
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  941): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 238090428508; DSPS: 7899740; Offset : -3000009263
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  941): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 253092646729; DSPS: 8391340; Offset : -3000232448
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 268094849982; DSPS: 8882931; Offset : -3000195943
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 283097843534; DSPS: 9374537; Offset : -2999826878
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 297798537553; DSPS: 9856262; Offset : -3000213258
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  941): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 312800852448; DSPS: 10347862; Offset : -3000339847
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 335305399531; DSPS: 11085288; Offset : -3000248253
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/LocationManagerService(  941): remove 248334e6
,D/LocationManagerService(  941): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  941): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  941): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  941): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  941): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 350307709798; DSPS: 11576882; Offset : -3000196287
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 367811127794; DSPS: 12150445; Offset : -3000531953
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  941): Explicit concurrent mark sweep GC freed 32997(1723KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 22MB/34MB, paused 3.150ms total 228.936ms
,I/NotificationManager(  941): android: cancelAsUser(2) by android
,D/libc-netbsd( 4938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  276): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  276): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  941): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 384066544882; DSPS: 12683093; Offset : -3000241818
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 399068582950; DSPS: 13174679; Offset : -3000217884
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  941): acquireWakeLockInternal: lock=923706738, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=941
,D/PowerManagerServiceEx(  941): releaseWakeLockInternal: lock=923706738 [*alarm*], flags=0x0
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
V/AlarmManager(  941): ELAPSED_WAKEUP set : Alarm{940b02b type 2 when 414682 com.google.android.gms} when 414682
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  941): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 416892794165; DSPS: 13758742; Offset : -3000194954
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
,D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  941): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 434396077361; DSPS: 14332290; Offset : -3000207656
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 454398101594; DSPS: 14987696; Offset : -2999587414
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 468941419569; DSPS: 15464267; Offset : -3000061878
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 482558506403; DSPS: 15910474; Offset : -3000132129
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
D/WifiController(  941): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 496631136137; DSPS: 16371608; Offset : -3000195162
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 511633848456; DSPS: 16863207; Offset : -2999893784
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 524769955909; DSPS: 17293664; Offset : -3000289088
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 541032611141; DSPS: 17826556; Offset : -3000209520
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  941): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 556034800107; DSPS: 18318147; Offset : -3000187302
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 573538368582; DSPS: 18891709; Offset : -3000341894
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 586987731584; DSPS: 19332413; Offset : -3000197617
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 600119298647; DSPS: 19762708; Offset : -3000191910
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  941): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 620121581307; DSPS: 20418141; Offset : -3000137086
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 640123844387; DSPS: 21073578; Offset : -3000223807
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 653258325156; DSPS: 21503968; Offset : -3000203487
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 672952673675; DSPS: 22149303; Offset : -2999916169
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  941): android: cancelAsUser(2) by android
,D/libc-netbsd( 4938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  276): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  941): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 686084365184; DSPS: 22579608; Offset : -3000091167
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 699698875729; DSPS: 23025732; Offset : -3000204620
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 713309983985; DSPS: 23471741; Offset : -3000210918
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 728311858972; DSPS: 23963337; Offset : -3000655293
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  941): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 743316603597; DSPS: 24454991; Offset : -2999999998
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 756775309068; DSPS: 24896014; Offset : -3000248306
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 770846556065; DSPS: 25357098; Offset : -3000168354
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  941): acquireWakeLockInternal: lock=923706738, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=941
,V/AlarmManager(  941): ELAPSED_WAKEUP set : Alarm{3475c1e type 2 when 776167 com.google.android.gms} when 776167
D/PowerManagerServiceEx(  941): releaseWakeLockInternal: lock=923706738 [*alarm*], flags=0x0
,D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  941): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
,I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  941): battery changed pluggedType: 2
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 790848754888; DSPS: 26012532; Offset : -3000227831
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 810851066649; DSPS: 26667967; Offset : -3000204836
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  941): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 830853288296; DSPS: 27323398; Offset : -3000149885
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  941): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 850855565786; DSPS: 27978834; Offset : -3000191783
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 870857778288; DSPS: 28634265; Offset : -3000146029
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 890860405260; DSPS: 29289714; Offset : -3000232803
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 905862765333; DSPS: 29781314; Offset : -3000316507
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  941): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 918994788281; DSPS: 30211609; Offset : -2999854708
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 932132686083; DSPS: 30642121; Offset : -3000140656
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 946205054264; DSPS: 31103245; Offset : -3000160222
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 968716407984; DSPS: 31840896; Offset : -3000128368
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  941): android: cancelAsUser(2) by android
,D/libc-netbsd( 4938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  276): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=0, netid=0
,D/DSQN    (  941): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 983718337201; DSPS: 32332480; Offset : -3000152276
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 998719150561; DSPS: 32824050; Offset : -3000864872
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 1019974908215; DSPS: 33520525; Offset : -2999837417
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 271
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 271, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  941): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 1033582745351; DSPS: 33966439; Offset : -3000215561
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 1047032824607; DSPS: 34407170; Offset : -3000179161
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 1060171750459; DSPS: 34837705; Offset : -3000138754
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 1075658049866; DSPS: 35345165; Offset : -3000289516
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 1089729994595; DSPS: 35806271; Offset : -3000180744
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 1104732805056; DSPS: 36297871; Offset : -2999814111
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 1118489292067; DSPS: 36748654; Offset : -3000132494
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 1133505079110; DSPS: 37240691; Offset : -3000123039
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 1148509107997; DSPS: 37732352; Offset : -3000397235
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  941): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 1162581280589; DSPS: 38193459; Offset : -3000093461
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 1178841796393; DSPS: 38726283; Offset : -3000075756
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 1192597383953; DSPS: 39177035; Offset : -3000347467
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 1206984465951; DSPS: 39648462; Offset : -3000075876
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  941): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 1220598803417; DSPS: 40094580; Offset : -3000179329
,I/UsageStatsService(  941): User[0] Flushing usage stats to disk
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 1235303252982; DSPS: 40576416; Offset : -3000197458
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 1250305563348; DSPS: 41068015; Offset : -3000298059
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 1264376925740; DSPS: 41529102; Offset : -3000194239
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  941): battery changed pluggedType: 2
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  941): android: cancelAsUser(2) by android
,D/libc-netbsd( 4938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  276): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  941): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 1278448759196; DSPS: 41990209; Offset : -3000229548
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 1300953044336; DSPS: 42727634; Offset : -3000369509
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 1314085490561; DSPS: 43157955; Offset : -3000278046
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 1330341390588; DSPS: 43690625; Offset : -3000176385
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 1344109176405; DSPS: 44141766; Offset : -3000121307
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 1360365017192; DSPS: 44674440; Offset : -3000200905
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 1375367219401; DSPS: 45166029; Offset : -3000104356
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 1392870865848; DSPS: 45739587; Offset : -3000059009
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 1407873091640; DSPS: 46231185; Offset : -3000213615
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 1422876036965; DSPS: 46722798; Offset : -3000106425
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 1439763922430; DSPS: 47276194; Offset : -3000526571
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 1453519512296; DSPS: 47726926; Offset : -3000185782
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 1468522200721; DSPS: 48218526; Offset : -2999938736
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  941): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  941): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  941): tsOffsetIs: Apps: 1491027127396; DSPS: 48955980; Offset : -3000322119
,TIME-OUT KILL (timeout was 1400000ms)
```
