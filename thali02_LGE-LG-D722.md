#### Test 613623660556c10_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
W/ContextImpl( 4518): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,--------- beginning of system
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4518): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4518): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 4518): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4518): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 4518): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/ActivityManager(  848): Waited long enough for: ServiceRecord{d25f50b u0 com.android.calendar/.alerts.InitAlarmsService}
W/ActivityThread( 4518): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 4518): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@13a159b7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4518): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 4518): GMSCore installation verified
I/ConfigStore( 4518): Config Database version: 1
D/AndroidRuntime( 4550): 
D/AndroidRuntime( 4550): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4550): CheckJNI is OFF
I/MediaRouter( 4518): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
D/ToneMappingReceiver( 4466): Enter doAlarmRingToneUriMapping()
D/ToneMappingReceiver( 4466): do ALARM RingToneUriMapping() -> first find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/CommonUtil( 4466): Enter getMatchedBackupTone() enter URI value is On, parentInfo : ALARM
D/CommonUtil( 4466): getFinededDefaultTone() -> backup ringtone value : null
D/CommonUtil( 4466): Exit getMatchedBackupTone() value is null
D/ToneMappingReceiver( 4466): do ALARM RingToneUriMapping() -> second find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/ToneMappingReceiver( 4466): Enter doAlarmRingToneUriMapping(), return value is 0
D/ToneMappingReceiver( 4466): Alarm Success count is 0
D/ToneMappingReceiver( 4466): Timer Success count is 0
I/MediaScannerReceiver( 3579): Calendar.onReceive: a=android.intent.action.MEDIA_SCANNER_FINISHED Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///system/media flg=0x10 cmp=com.android.calendar/.alerts.MediaScannerReceiver }, mData=file:///system/media
I/InitNotificationRingtoneService( 3579): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 3579): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
E/MediaScanReceiver( 4496): media scanning finished
I/com.lge.bnr.receiver.MediaScanReceiver( 4496): android.intent.action.MEDIA_SCANNER_FINISHED
I/GHttpClientFactory( 4518): Using our fixed implementation of GMSCore's GoogleHttpClient
D/KeyguardUpdateMonitor( 1361): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1361): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1361): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1361): On Skip Timer : true
D/PowerService( 1872): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): init target 500000
D/AndroidRuntime( 4550): Calling main entry com.android.commands.am.Am
I/AlertUtils( 3579): [getCalendarNotiSoundURIFromCursor] getCount()= 21
I/GoogleURLConnFactory( 4518): Using platform SSLCertificateSocketFactory
I/AlertUtils( 3579): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/ActivityManager(  848): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/AlertUtils( 3579): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 3579): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 3579): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 3579): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 3579): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 3579): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 3579): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
D/charger_monitor(  486): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/AlertUtils( 3579): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 3579): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 3579): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 3579): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 3579): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 3579): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 3579): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3579): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
D/ActivityManager(  848): setTaskToReturnTo : TaskRecord{358bcd9b #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  848): setTaskToReturnTo : TaskRecord{358bcd9b #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  848): AppWindowTokenEx init.. 
D/ContextHelper(  848): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
D/InputDispatcher(  848): Focus left window: Window{34a9f1d3 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 4550): Shutting down VM
D/KeyguardUpdateMonitor( 1361): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1361): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1361): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
I/PhoneWindow(  848): [generateLayout] setColorNavigationBar => color=0x ff000001
D/LEDHandler( 1872): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1872): Battery Level Remaining: 100%
D/LEDHandler( 1872): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1361): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1908): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1908): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/WifiController(  848): battery changed pluggedType: 2
W/MainApplication( 4496): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/[LGHome]EVENT( 1946): [Launcher.java:986:onPause()]onPause
D/PhoneWindowEx(  848): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow(  848): [setNavigationBarColor2] color=0x fff5f5f5
I/AlertUtils( 3579): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 3579): End InitializeAlertRingtoneService.onHandleIntent
D/SplitWindow(  848): check instance of lgWin Window{101e6949 u0 Starting com.test.thalitest}
I/ActivityManager(  848): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4586 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1946): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
E/MediaScanReceiver( 4496): media scanning start or checking
D/ToneMappingReceiver( 4466): Enter doAlarmRingToneUriMapping()
D/ToneMappingReceiver( 4466): do ALARM RingToneUriMapping() -> first find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/CommonUtil( 4466): Enter getMatchedBackupTone() enter URI value is On, parentInfo : ALARM
D/CommonUtil( 4466): getFinededDefaultTone() -> backup ringtone value : null
D/CommonUtil( 4466): Exit getMatchedBackupTone() value is null
D/ToneMappingReceiver( 4466): do ALARM RingToneUriMapping() -> second find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/ToneMappingReceiver( 4466): Enter doAlarmRingToneUriMapping(), return value is 0
D/ToneMappingReceiver( 4466): Alarm Success count is 0
D/ToneMappingReceiver( 4466): Timer Success count is 0
I/[LGHome]EVENT( 1946): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  848): Starting window displayed
D/WindowManager(  848): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
I/SystemUI[Framework](  848): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
W/PhoneWindowManagerEx(  848): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  848): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  848): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  848): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3d8b5a3b,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  848): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1361): notify navigation bar color(0xfff5f5f5)
I/MediaScannerReceiver( 3579): Calendar.onReceive: a=android.intent.action.MEDIA_SCANNER_FINISHED Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///storage/emulated/0 flg=0x10 cmp=com.android.calendar/.alerts.MediaScannerReceiver }, mData=file:///storage/emulated/0
I/[SystemUI]NavigationThemeResource( 1361): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1361):  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
I/[SystemUI]NavigationThemeResource( 1361): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager(  848): Killing 4331:com.lge.lgdmsclient/1000 (adj 15): empty #11
I/NotificationManager( 4518): com.google.android.music: cancel(1061) by com.google.android.music
I/InitNotificationRingtoneService( 3579): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 3579): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
I/HotwordDetector( 2022): Closing mic
,I/MicrophoneInputStream( 2022): mic_close com.google.android.apps.gsa.speech.audio.u@1d7dda23
V/AudioRecord( 2022): stop()
D/AudioRecord( 2022): AudioRecord->stop()
V/AudioFlinger(  275): RecordHandle::stop()
V/AudioFlinger(  275): RecordThread::stop
V/AudioFlinger(  275): Record stopped OK
V/AudioPolicyManager(  275): stopInput() input 17
V/AudioPolicyService(  275): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  275): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  275): AudioCommandThread() waking up
V/AudioPolicyService(  275): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  275): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  275): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  275): ThreadBase::setParameters() routing=0
V/AudioFlinger(  275): sendConfigEvent_l() num events 1 event 2
,V/AudioFlinger(  275): processConfigEvents_l() remaining events 1
V/AudioFlinger(  275): processConfigEvents_l() DONE thread 0xb414a000
D/audio_hw_primary(  275): in_standby: enter: stream (0xb40365c0) usecase(7: audio-record)
W/libprocessgroup(  848): failed to open /acct/uid_1000/pid_4331/cgroup.procs: No such file or directory
,E/MediaScanReceiver( 4496): media scanning finished
I/com.lge.bnr.receiver.MediaScanReceiver( 4496): android.intent.action.MEDIA_SCANNER_FINISHED
I/AlertUtils( 3579): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 3579): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
V/audio_hw_primary(  275): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  275): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  275): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  275): disable_audio_route: reset and update mixer path: audio-record
I/AlertUtils( 3579): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
V/audio_hw_primary(  275): disable_audio_route: exit
E/audio_hw_primary(  275): disable_snd_device: enter 144
D/hardware_info(  275): hw_info_append_hw_type : device_name = lg-vr-handset-mic
,V/audio_hw_primary(  275): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  275): stop_input_stream: exit: status(0)
V/audio_hw_primary(  275): in_standby: exit:  status(0)
V/AudioFlinger(  275): RecordThread: loop stopping
V/AudioPolicyService(  275): AudioCommandThread() going to sleep
V/AudioPolicyManager(  275): resetInputDevice() releaseAudioPatch returned -22
I/AlertUtils( 3579): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
V/AudioPolicyManager(  275): removeAudioPatch() handle 18 af handle 18
,V/AudioPolicyService(  275): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  275): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  275): AudioCommandThread() waking up
V/AudioPolicyService(  275): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  275): AudioCommandThread() going to sleep
V/AudioPolicyService(  275): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  275): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  275): AudioCommandThread() waking up
V/AudioPolicyService(  275): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  275): setParameters(): io 17, keyvalue hotword_active=0, calling pid 275
V/AudioFlinger(  275): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  275): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  275): RecordThread: loop starting
V/AudioFlinger(  275): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  275): in_set_parameters: enter: kvpairs=hotword_active=0
,V/audio_hw_primary(  275): in_set_parameters: exit: status(0)
V/AudioFlinger(  275): processConfigEvents_l() DONE thread 0xb414a000
V/AudioFlinger(  275): RecordThread: loop stopping
V/AudioPolicyService(  275): AudioCommandThread() going to sleep
V/AudioRecord( 2022): stop()
V/AudioRecord( 2022): stop()
V/AudioRecord( 2022): stop()
I/AlertUtils( 3579): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 3579): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 3579): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/AlertUtils( 3579): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
D/ContextHelper( 4586): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
V/AudioFlinger(  275): RecordHandle::stop()
V/AudioFlinger(  275): RecordThread::stop
V/AudioPolicyManager(  275): releaseInput() 17
V/AudioPolicyManager(  275): closeInput(17)
V/AudioFlinger(  275): releasing 16 from 2022 for -1
V/AudioFlinger(  275):  decremented refcount to 0
V/AudioFlinger(  275): purging stale effects
V/AudioFlinger(  275): closeInput() 17
V/AudioSystem(  275): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  848): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1361): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1782): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  275): ThreadBase::exit
V/AudioFlinger(  275): RecordThread: loop starting
,V/AudioFlinger(  275): RecordThread 0xb414a000 exiting
D/audio_hw_primary(  275): adev_close_input_stream: enter:stream_handle(0xb40365c0)
D/audio_hw_primary(  275): in_standby: enter: stream (0xb40365c0) usecase(7: audio-record)
V/audio_hw_primary(  275): in_standby: exit:  status(0)
V/AudioPolicyService(  275): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  275): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  275): AudioCommandThread() waking up
V/AudioPolicyService(  275): AudioCommandThread() processing update audio port list
V/AudioPolicyManager(  275): releaseInput() exit
V/AudioFlinger(  275): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  275): removeClient_l() pid 2022, calling pid 275
V/AudioSystem( 3037): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2022): ioConfigChanged() event 4, ioHandle 17
I/AlertUtils( 3579): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
V/AudioPolicyService(  275): AudioCommandThread() going to sleep
V/AudioSystem( 2095): ioConfigChanged() event 4, ioHandle 17
I/AlertUtils( 3579): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/HotwordRecognitionRnr( 2022): Hotword detection finished
,I/AlertUtils( 3579): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/HotwordRecognitionRnr( 2022): Stopping hotword detection.
I/AlertUtils( 3579): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 3579): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 3579): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/ActivityManager(  848): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=4607 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 4518): CheckpointMarkThreadRoots callback created = 0xb042d380
,I/AlertUtils( 3579): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 3579): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3579): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
,I/AlertUtils( 3579): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 3579): End InitializeAlertRingtoneService.onHandleIntent
I/art     ( 4518): CheckpointMarkThreadRoots callback created = 0xb042d360
,W/ResourcesManager( 4607): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/WebViewFactory( 4586): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
D/CalendarProvider2( 4607): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@2a28cbe9
,I/art     ( 3065): Explicit concurrent mark sweep GC freed 13622(750KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 449us total 46.266ms
,D/CalendarProvider2( 4607): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 4607): Created com.android.providers.calendar.CalendarAlarmManager@3345b57a(com.android.providers.calendar.CalendarProvider2@2a28cbe9)
D/CalendarProviderBroadcastReceiver( 4607): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
,D/CalendarProviderBroadcastReceiver( 4607): [IntentService] WakeLock acquire, start IntentSerivce
I/LibraryLoader( 4586): Time to load native libraries: 6 ms (timestamps 7592-7598)
,D/CalendarProvider2( 4607): CalendarProviderIntentService.onCreate()
I/LibraryLoader( 4586): Expected native library version number "",actual native library version number ""
D/CalendarProvider2( 4607): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 4607): [getOrCreateCalendarAlarmManager]
V/WebViewChromiumFactoryProvider( 4586): Binding Chromium to main looper Looper (main, tid 1) {2855a12b}
,I/LibraryLoader( 4586): Expected native library version number "",actual native library version number ""
D/CalendarProvider2( 4607): [IntentService] Release Lock
D/CalendarProvider2( 4607): CalendarProviderIntentService.onDestroy()
I/chromium( 4586): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/MediaStoreImporter( 4518): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/BrowserStartupController( 4586): Initializing chromium process, singleProcess=true
,W/art     ( 4586): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4586): ApplicationContext is null in ApplicationStatus
I/art     ( 3752): Explicit concurrent mark sweep GC freed 2470(97KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.263ms total 32.078ms
,W/chromium( 4586): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 4586): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4586): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4586): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 4586): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4586): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 4586): Build Date: 03/02/15 Mon
I/Adreno-EGL( 4586): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 4586): Remote Branch: 
I/Adreno-EGL( 4586): Local Patches: 
I/Adreno-EGL( 4586): Reconstruct Branch: 
I/ActivityManager(  848): Killing 4407:com.android.settings/1000 (adj 15): empty #11
W/libprocessgroup(  848): failed to open /acct/uid_1000/pid_4407/cgroup.procs: No such file or directory
,D/WearableService( 1749): callingUid 10006, callindPid: 1749
,D/LocationInitializer( 4049): Restart initialization of location
D/AuthorizationBluetoothService( 1749): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/MDM     ( 1749): [127] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1749): com.google.android.gms: cancel(0) by com.google.android.gms
,V/AudioPolicyService(  275): registerClient() client 0xb381e200, uid 10316
,D/BluetoothManagerService(  848): Message: 20
D/BluetoothManagerService(  848): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1d7bee2d:true
D/BluetoothAdapter( 4586): 1072279366: getState() :  mService = null. Returning STATE_OFF
I/ActivityManager(  848): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=4646 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/GCoreFlp( 1749): No location to return for getLastLocation()
,W/FusedLocationProvider( 1749): location=null
W/IcingInternalCorpora( 4049): getNumBytesRead when not calculated.
,W/art     ( 4586): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 4586): onDetachedFromWindow called when already detached. Ignoring
,I/PhoneWindow( 4586): [generateLayout] setColorNavigationBar => color=0x ff000001
D/PhoneWindowEx( 4586): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow( 4586): [setNavigationBarColor2] color=0x fff5f5f5
D/SystemWebViewEngine( 4586): CordovaWebView is running on device made by: LGE
,W/art     ( 4586): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4586): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager(  848): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Activity( 4586): Activity.onPostResume() called 
,D/OpenGLRenderer( 4586): Render dirty regions requested: true
I/OpenGLRenderer( 4586): Initialized EGL, version 1.4
D/OpenGLRenderer( 4586): Enabling debug mode 0
,D/Atlas   ( 4586): Validating map...
,D/SplitWindow(  848): check instance of lgWin Window{28d799f8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/Gmail   ( 4646): getAccountsCursor
,W/chromium( 4586): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/InputDispatcher(  848): Focus entered window: Window{28d799f8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/GAV2    ( 4646): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ActivityManager(  848): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/InputMethodManagerService(  848): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  848): Displayed com.test.thalitest/.MainActivity: +1s372ms
I/Timeline(  848): Timeline: Activity_windows_visible id: ActivityRecord{60df538 u0 com.test.thalitest/.MainActivity t222} time:68470
W/ActivityManager(  848): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager(  848): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Timeline( 4586): Timeline: Activity_idle id: android.os.BinderProxy@18f7fb82 time:68488
I/Gmail   ( 4646): Observing account changes for notifications
,E/Gmail   ( 4646): Error finding the version of the Email provider.....
E/Gmail   ( 4646): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4646): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4646): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4646): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4646): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4646): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4646): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 4646): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 4646): We do not support migrating this version of the Email provider.
I/Gmail   ( 4646): getAccountsCursor
,W/BindingManager( 4586): Cannot call determinedVisibility() - never saw a connection for the pid: 4586
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1749): No location to return for getLastLocation()
,W/FusedLocationProvider( 1749): location=null
I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ActivityManager(  848): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=4721 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/art     (  299): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 311us total 24.035ms
,I/art     (  299): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 297us total 21.972ms
,I/art     (  299): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 23.092ms
,D/JsMessageQueue( 4586): Set native->JS mode to OnlineEventsBridgeMode
I/Gmail   ( 4646): getAccountsCursor
I/Gmail   ( 4646): notifyAccountChanged
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 4646): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 4646): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 4646): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4646): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/PhoneMonitor( 4721): Register our PhoneStateListener
,I/ActivityManager(  848): Killing 4376:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 4358): android.os.DeadObjectException
W/System.err( 4358): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 4358): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 4358): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 4358): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 4358): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 4358): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 4358): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4358): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4358): 	at android.os.Looper.loop(Looper.java:135)
,W/System.err( 4358): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 4358): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4358): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4358): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 4358): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 4358): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 4358): android.os.DeadObjectException
W/System.err( 4358): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 4358): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 4358): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 4358): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 4358): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 4358): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 4358): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4358): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4358): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4358): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 4358): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4358): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4358): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 4358): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 4358): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
D/PhoneMonitor( 4721): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 4721): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 4721): [parse] Load xml
V/TelephonyAutoProfiling( 4721): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 4721): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 4721): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  848): failed to open /acct/uid_10089/pid_4376/cgroup.procs: No such file or directory
I/Gmail   ( 4646): getAccountsCursor
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  848): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=4747 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/GCM     ( 1749): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/UEI.SmartControl( 4747): Quickset Services start...
,I/UEI.SmartControl( 4747): Manufacture = LGE
,D/UEI.SmartControl( 4747): File observer start...
E/UEI.SmartControl( 4747): IR Port is disabled: false
D/UEI.SmartControl( 4747): Starting file observer...
D/UEI.SmartControl( 4747): Extracting JNI libs...
D/UEI.SmartControl( 4747): --- this system supports 32-bit or 64-bit only
D/jxcore_app_log( 4586): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1618687872
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4586): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4586):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4586):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4586):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4586):     - Handshake required: false
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4586): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bbe94 added. We now have 1 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4586): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4586):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4586):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4586):     - Bluetooth MAC address: F8:95:C7:87:85:54
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4586):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4586):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4586):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4586):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4586):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4586):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4586): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f7a9683 added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4586): addListener: New listener added - the number of listeners is now 1
I/ActivityManager(  848): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=4773 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4586): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,I/ActivityManager(  848): Waited long enough for: ServiceRecord{3be4603a u0 com.lge.springcleaning/.service.AppCleanupService}
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4586): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4586): setDiscoveryMode: Discovery mode BLE is supported
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4586): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 4586): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 4586): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/ResourcesManager( 4773): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     ( 4586): CheckpointMarkThreadRoots callback created = 0x9fab7b30
,I/art     ( 4586): CheckpointMarkThreadRoots callback created = 0x9fab7af0
,D/UEI.SmartControl( 4747): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 4747): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 4747): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 4747): --- Selecting new region: 2
,I/UEI.SmartControl( 4747): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 4747): Platform has CIR...
D/UEI.SmartControl( 4747): NO CIR support, need to check package...
I/UEI.SmartControl( 4747): Model: LG-D722 uses JNI
D/UEI.SmartControl( 4747): QS Service created
E/UEI.SmartControl( 4747): QS start get config
,D/UEI.SmartControl( 4747): Loading JNI Libs...
,D/UEI.SmartControl( 4747):  configuring local db...
,I/art     (  848): Explicit concurrent mark sweep GC freed 28943(1466KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/33MB, paused 6.446ms total 166.836ms
,I/art     (  848): WaitForGcToComplete blocked for 82.954ms for cause Explicit
V/AlarmManager(  848): ELAPSED_WAKEUP set : Alarm{2c1d63d2 type 2 when 70268 com.google.android.gms} when 70268
,D/UEI.SmartControl( 4747):  ---- Has DB8: true
,D/UEI.SmartControl( 4747): QS start statue = true Error code = 0
D/UEI.SmartControl( 4747): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 4747): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 4747): IRRCDataComm has AudioManager!!!!.
,I/art     ( 4773): CheckpointMarkThreadRoots callback created = 0xaaf259f0
I/art     (  848): Explicit concurrent mark sweep GC freed 3612(241KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/33MB, paused 2.308ms total 150.599ms
W/irrc_jni( 4747): IRRCPlayer_nativeInit ++ 
D/irrcClient( 4747): IrrcClient ++ 
,D/irrcClient( 4747): getIrrcService ++ 
D/irrcClient( 4747): getIrrcService -- 
D/irrcClient( 4747): IrrcClient -- 
W/irrc_jni( 4747): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 4747): Services init done
D/UEI.SmartControl( 4747): QS Service init finished
D/UEI.SmartControl( 4747): QS Service version name: 0.1.73
D/UEI.SmartControl( 4747): QS Service version code: 1073
D/UEI.SmartControl( 4747): Service requested: Control
I/UEI.SmartControl( 4747): Device manager: loading config....
,D/UEI.SmartControl( 4747): Config is loaded...
I/Babel_SMS( 4773): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 4773): MmsConfig.loadMmsSettings
,I/Babel_SMS( 4773): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 4773): MmsConfig.loadFromDatabase
I/art     ( 4773): CheckpointMarkThreadRoots callback created = 0xaaf259d0
D/UEI.SmartControl( 4747): Request IControl service: devices are loaded...
D/UEI.SmartControl( 4747):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 4747): Notify AllClients services are ready: 0
D/UEI.SmartControl( 4747): Internal service binding...
D/UEI.SmartControl( 4747): -----IControl: 11
D/UEI.SmartControl( 4747): Caller: com.lge.qremote
D/UEI.SmartControl( 4747): ------------ IControl registerCallback...
I/UEI.SmartControl( 4747): Registering callback...
D/UEI.SmartControl( 4747): -----IControl: 19
D/UEI.SmartControl( 4747): Caller: com.lge.qremote
I/UEI.SmartControl( 4747): Registering Services Ready callback...
I/UEI.SmartControl( 4747): Notify client services are ready...
D/UEI.SmartControl( 4747): -----IControl: 8
,D/UEI.SmartControl( 4747): Caller: com.lge.qremote
,E/Babel_SMS( 4773): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4773): MmsConfig.loadFromResources
E/Babel_SMS( 4773): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 4773): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 4773): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 4773): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 4773): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
,D/SensorManager( 4773): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 4773): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 4773): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 4773): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 4773): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 4773): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 4773): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 4773): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 4773): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 4773): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 4773): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 4773): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 4773): found sensor: Motion Accel, handle=46
D/AlertService( 3579): Beginning updateAlertNotification
,D/AlertService( 3579): No fired or scheduled alerts
,W/Settings( 4773): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/NotificationManager( 3579): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 3579): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 3579): com.android.calendar: cancel(2) by com.android.calendar
,I/NotificationManager( 3579): com.android.calendar: cancel(3) by com.android.calendar
I/Babel_Crash( 4773): startup - clean
I/NotificationManager( 3579): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 3579): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 3579): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 3579): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 3579): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 3579): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 3579): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 3579): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 3579): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 3579): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 3579): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 3579): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 3579): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 3579): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 3579): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 3579): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 3579): com.android.calendar: cancel(20) by com.android.calendar
I/Babel   ( 4773): deleted: false for 0
,D/AlertService( 3579): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 3579): No events found starting within 1 week.
D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
I/AudioManager( 4358): getMode name:com.lge.qremote
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  848): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/AudioManager( 4358): getMode name:com.lge.qremote
I/AudioManager( 4358): getMode name:com.lge.qremote
W/AudioCapabilities( 4773): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 4773): Unsupported mime audio/adpcm
W/AudioCapabilities( 4773): Unsupported mime audio/g726
W/AudioCapabilities( 4773): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 4773): Unsupported mime audio/wma-voice
W/VideoCapabilities( 4773): Unsupported mime video/mjpg
W/VideoCapabilities( 4773): Unsupported mime video/theora
,I/ActivityManager(  848): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=4810 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  848): Killing 4440:com.lge.sync/1000 (adj 15): empty #11
W/AudioCapabilities( 4773): Unsupported mime audio/evrc
,W/AudioCapabilities( 4773): Unsupported mime audio/qcelp
W/VideoCapabilities( 4773): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 4773): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 4773): Unsupported mime audio/qcelp
W/AudioCapabilities( 4773): Unsupported mime audio/evrc
W/libprocessgroup(  848): failed to open /acct/uid_1000/pid_4440/cgroup.procs: No such file or directory
W/ResourcesManager( 4810): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/VideoCapabilities( 4773): Unsupported mime video/mp4v-esdp
W/ResourcesManager( 4810): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4810): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/VideoCapabilities( 4773): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4773): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4773): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4773): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4773): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  848): Killing 3153:com.android.defcontainer/u0a4 (adj 15): empty #11
W/libprocessgroup(  848): failed to open /acct/uid_10004/pid_3153/cgroup.procs: No such file or directory
,I/vclib   ( 4773): onServiceConnected
W/Babel   ( 4773): Attempted to change video mute state without an active call.
I/NotificationManager( 4773): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/LGEmail ( 4810): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 4810): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,W/jxcore-log( 4586): Initializing JXcore engine
,W/jxcore-log( 4586): JXcore engine is ready
,W/Thread-504( 4789): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6692]" dev="sockfs" ino=6692 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-504( 4789): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-504( 4789): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6854]" dev="sockfs" ino=6854 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-504( 4789): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-504( 4789): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-504( 4789): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[20267]" dev="sockfs" ino=20267 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
I/[LGHome]EVENT( 1946): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1946): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1946): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/[SystemUI]QPairHandler( 1361): onReceive = android.intent.action.PACKAGE_CHANGED
W/jxcore-log( 4586): Starting JXcore engine
I/QCNEJ   ( 1908): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/InputReader(  848): Reconfiguring input devices.  changes=0x00000010
I/[SystemUI]QSlideListController( 1361): onReceive = android.intent.action.PACKAGE_CHANGED
W/[SystemUI]QSlideLoader( 1361): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1361): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1361): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1361): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1361): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
,W/[SystemUI]QSlideLoader( 1361): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1361): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1361): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1361): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1361): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1361): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1361): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1361): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
D/administrator(  848): Handling package changes for user 0
I/PackageChangeReceiver( 4810): intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
,I/art     ( 1854): CheckpointMarkThreadRoots callback created = 0xb042d300
,I/art     ( 1854): CheckpointMarkThreadRoots callback created = 0xb042d6b0
,I/ActivityManager(  848): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=4833 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  848): Killing 4466:com.lge.clock/u0a10 (adj 15): empty #11
I/[LGHome]Launcher( 1946): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/libprocessgroup(  848): failed to open /acct/uid_10010/pid_4466/cgroup.procs: No such file or directory
,W/jxcore-log( 4586): Platform android
W/jxcore-log( 4586): 
,W/jxcore-log( 4586): Process ARCH arm
W/jxcore-log( 4586): 
I/NotificationService(  848): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  848): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  848): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  848): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/ResourcesManager(  848): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType(  848): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  848): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=4853 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  848): Process com.google.android.music:main (pid 4518) has died
,I/[LGHome]EVENT( 1946): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
V/BackupManagerService(  848): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  848): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3a492ba2
,I/GCoreNlp( 1749): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/AppUp4:AppBoxCP( 4853): onCreate
,W/AppUp4:DB( 4853):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 4853):  setFingerPrint start
I/AppUp4:DB( 4853):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 4853):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 4853):  SDK version = 0
I/AppUp4:DB( 4853):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 4853): AppBoxApplication onCreate()
I/ActivityManager(  848): Killing 4496:com.lge.bnr/1000 (adj 15): empty #11
,W/libprocessgroup(  848): failed to open /acct/uid_1000/pid_4496/cgroup.procs: No such file or directory
,D/LCardEmulationManager( 1854): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1854): getDefaultRoute
D/LocationProviderProxy(  848): applying state to connected service
I/ActivityManager(  848): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=4871 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 4871): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4871): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 4871): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/jxcore-log( 4586): JXcore Cordova bridge is ready!
I/jxcore-log( 4586): 
W/jxcore-log( 4586): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 4586): execute: REQUEST_ACCESS_COARSE_LOCATION
I/AppConfig( 4871): Total System Memory = 906309632
I/GalleryUtils( 4871): Application Heap = 96 MB
,I/AppConfig( 4871): App Tier : NOT_DEF
D/SystemHelper( 4871): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  848): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=4893 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  848): Killing 4607:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/libprocessgroup(  848): failed to open /acct/uid_10014/pid_4607/cgroup.procs: No such file or directory
,W/ResourcesManager( 4893): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4893): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4893): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 4893): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 4893): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
V/AlarmManager(  848): ELAPSED_WAKEUP set : Alarm{25107c23 type 2 when 72489 com.google.android.gms} when 72489
I/SystemConfig( 4893): BUILD Country: EU
I/SystemConfig( 4893): BUILD Operator: OPEN
,I/SystemConfig( 4893): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 4893): existFile = false
I/SystemConfig( 4893): canReadFile = false
I/SystemConfig( 4893): systemFeature RCS result false
D/SystemConfig( 4893): refreshRcsSupport() :false
,I/ActivityManager(  848): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=4919 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  848): Killing 4646:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  848): failed to open /acct/uid_10053/pid_4646/cgroup.procs: No such file or directory
,I/LockScreenSettings( 4919): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/LockScreenSettings( 4919): New app installed broadcast received ..
,I/LockScreenSettings( 4919): Number of installed packages  1
I/ActivityManager(  848): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=4936 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  848): Killing 4721:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  848): failed to open /acct/uid_10038/pid_4721/cgroup.procs: No such file or directory
,D/EulaProviderUpdateObserver( 4936): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 4936): uri : package:com.test.thalitest
,I/ActivityManager(  848): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=4956 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  848): Killing 4773:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  848): failed to open /acct/uid_10061/pid_4773/cgroup.procs: No such file or directory
,D/[BNRAppListMgrReceiver]( 4956): android.intent.action.PACKAGE_ADDED : com.test.thalitest
,W/MainApplication( 4956): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,I/ActivityManager(  848): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4978 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/ActivityManager(  848): Killing 4747:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 4358): android.os.DeadObjectException
W/System.err( 4358): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 4358): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 4358): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 4358): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 4358): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 4358): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 4358): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4358): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4358): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4358): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 4358): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4358): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4358): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 4358): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 4358): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 4358): android.os.DeadObjectException
W/System.err( 4358): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 4358): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 4358): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 4358): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 4358): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 4358): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 4358): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4358): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4358): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4358): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 4358): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4358): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4358): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 4358): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 4358): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
,I/art     (  299): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 324us total 29.016ms
I/art     (  299): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 20.519ms
,I/art     (  299): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 20.565ms
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  848): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  848): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  848): tsOffsetIs: Apps: 73721150134; DSPS: 2513908; Offset : -3004297978
,W/libprocessgroup(  848): failed to open /acct/uid_10089/pid_4747/cgroup.procs: No such file or directory
,I/ActivityManager(  848): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=4996 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  848): Killing 4358:com.lge.qremote/u0a106 (adj 15): empty #11
,W/libprocessgroup(  848): failed to open /acct/uid_10106/pid_4358/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 4996): Quickset Services start...
,I/UEI.SmartControl( 4996): Manufacture = LGE
D/UEI.SmartControl( 4996): File observer start...
E/UEI.SmartControl( 4996): IR Port is disabled: false
D/UEI.SmartControl( 4996): Starting file observer...
D/UEI.SmartControl( 4996): Extracting JNI libs...
D/UEI.SmartControl( 4996): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 4996): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 4996): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 4996): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 4996): --- Selecting new region: 2
I/UEI.SmartControl( 4996): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 4996): Platform has CIR...
D/UEI.SmartControl( 4996): NO CIR support, need to check package...
I/UEI.SmartControl( 4996): Model: LG-D722 uses JNI
D/UEI.SmartControl( 4996): QS Service created
,E/UEI.SmartControl( 4996): QS start get config
,D/UEI.SmartControl( 4996): Loading JNI Libs...
D/UEI.SmartControl( 4996):  configuring local db...
,D/UEI.SmartControl( 4996):  ---- Has DB8: true
D/UEI.SmartControl( 4996): QS start statue = true Error code = 0
D/UEI.SmartControl( 4996): QS version = v2.7.11.1_RC1
,D/UEI.SmartControl( 4996): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 4996): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 4996): IRRCPlayer_nativeInit ++ 
D/irrcClient( 4996): IrrcClient ++ 
D/irrcClient( 4996): getIrrcService ++ 
D/irrcClient( 4996): getIrrcService -- 
D/irrcClient( 4996): IrrcClient -- 
W/irrc_jni( 4996): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 4996): Services init done
I/UEI.SmartControl( 4996): Device manager: loading config....
,D/UEI.SmartControl( 4996): Config is loaded...
D/UEI.SmartControl( 4996): QS Service init finished
D/UEI.SmartControl( 4996): QS Service version name: 0.1.73
D/UEI.SmartControl( 4996): QS Service version code: 1073
D/UEI.SmartControl( 4996): Service requested: Control
I/ActivityManager(  848): Killing 4810:com.lge.email/u0a21 (adj 15): empty #11
D/UEI.SmartControl( 4996):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 4996): Notify AllClients services are ready: 0
,I/GAv4    ( 4978): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4978):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4978):   adb logcat -s GAv4
,W/libprocessgroup(  848): failed to open /acct/uid_10021/pid_4810/cgroup.procs: No such file or directory
D/UEI.SmartControl( 4996): Internal service binding...
,W/GAv4    ( 4978): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 4978): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4978): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 4978): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4978): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
W/ResourcesManager( 4978): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4978): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  848): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5038 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  848): Killing 4833:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,W/libprocessgroup(  848): failed to open /acct/uid_10009/pid_4833/cgroup.procs: No such file or directory
W/ResourcesManager( 5038): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     ( 4978): CheckpointMarkThreadRoots callback created = 0xaaef01a0
,I/art     ( 4978): CheckpointMarkThreadRoots callback created = 0xb050cac0
,V/JNIHelp ( 4978): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/ActivityManager(  848): Process com.google.process.gapps (pid 3752) has died
,W/System  ( 4978): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4978): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  848): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5066 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  848): Process com.android.contacts (pid 4893) has died
,I/ActivityManager(  848): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5089 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GservicesProvider( 5066): Gservices pushing to system: true; secure/global: true
,I/UpdateIcingCorporaServi( 2022): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/GoogleHttpClient( 5066): GMS http client unavailable, use old client
,I/GoogleHttpClient( 5066): GMS http client unavailable, use old client
,I/UpdateIcingCorporaServi( 2022): UpdateCorporaTask done [took 160 ms] updated apps [took 160 ms] 
,I/art     (  848): Explicit concurrent mark sweep GC freed 21238(1082KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 1.826ms total 161.431ms
,D/Finsky  ( 5089): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 5089): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 5089): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5089): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5089): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3065): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3065): created cursor android.database.sqlite.SQLiteCursor@66578da on behalf of 5089
I/NotificationManager( 5089): com.android.vending: cancel(1003285959) by com.android.vending
,D/Ads     ( 5089): Skipping gmscore version check
,D/Finsky  ( 5089): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/ChimeraCfgMgr( 4049): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4049): Loading module APK com.google.android.play.games
D/PackageBroadcastService( 4049): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/Finsky  ( 5089): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 5089): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5089): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/Finsky  ( 5089): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/ChimeraCfgMgr( 4049): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4049): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 4049): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 4049): Submit a task: k
,I/Icing   ( 4049): Storage manager: low false usage 1.71MB avail 2.38GB capacity 4.06GB
D/ChimeraCfgMgr( 4049): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 4049): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 4049): Processing package: com.test.thalitest
,W/BaseAppContext( 4049): Using Auth Proxy for data requests.
W/BaseAppContext( 4049): Using Auth Proxy for data requests.
,D/GassUtils( 4049): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 4049): Found info for package com.test.thalitest in db.
I/PeopleDatabaseHelper( 4049): cleanUpNonGplusAccounts done.
,I/ActivityManager(  848): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5160 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  848): Process com.android.gallery3d (pid 4871) has died
,W/BaseAppContext( 4049): Using Auth Proxy for data requests.
,W/BaseAppContext( 4049): Using Auth Proxy for data requests.
W/BaseAppContext( 4049): Using Auth Proxy for data requests.
W/BaseAppContext( 4049): Using Auth Proxy for data requests.
W/BaseAppContext( 4049): Using Auth Proxy for data requests.
,D/Finsky  ( 5089): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/AlarmManager(  848): RTC_WAKEUP set : Alarm{1a40aaae type 0 when 1456908868335 com.android.vending} when 1456908868335
W/ActivityManager(  848): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
,V/AlarmManager(  848): RTC_WAKEUP set : Alarm{121de04f type 0 when 1456736024961 com.android.providers.contacts} when 1456736024961
V/AlarmManager(  848): ELAPSED_WAKEUP set : Alarm{1d2ac3dc type 2 when 56362 com.google.android.talk} when 56362
W/ActivityManager(  848): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 2022): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/NotificationManager(  848): android: cancelAsUser(2) by android
,I/Gmail   ( 5160): getAccountsCursor
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 5160): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/libc-netbsd( 5089): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5089): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5089): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5089): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  271): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  271): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  848): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/ActivityManager(  848): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/Finsky  ( 5089): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  848): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
E/Gmail   ( 5160): Error finding the version of the Email provider.....
E/Gmail   ( 5160): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5160): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5160): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5160): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5160): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5160): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5160): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5160): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5160): We do not support migrating this version of the Email provider.
I/NotificationManager(  848): android: cancelAsUser(2) by android
,D/libc-netbsd( 5089): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5089): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/ActivityManager(  848): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 5160): getAccountsCursor
V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 5160): Observing account changes for notifications
I/Icing   ( 4049): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  848): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=5206 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager(  848): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5212 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  848): android: cancelAsUser(2) by android
,W/ResourcesManager( 5212): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5212): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5206): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/libc-netbsd( 5089): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5089): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/Finsky  ( 5089): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/MultiDex( 5212): VM with version 2.1.0 has multidex support
I/MultiDex( 5212): install
I/MultiDex( 5212): VM has multidex support, MultiDex support library is disabled.
D/BluetoothManagerService(  848): Message: 20
D/BluetoothManagerService(  848): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2a1c2922:true
,D/BluetoothAdapter( 5206): 1072279366: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 5206): 1072279366: getState() :  mService = null. Returning STATE_OFF
V/JNIHelp ( 5212): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Gmail   ( 5160): notifyAccountChanged
,I/Gmail   ( 5160): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  848): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/Gmail   ( 5160): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5160): getAccountsCursor
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5160): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5160): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/ChimeraCfgMgr( 4049): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4049): Module APK com.google.android.play.games already loaded
W/ActivityThread( 5212): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5212): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@11984c2c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5212): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5212): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5212): com.google.android.gms: cancel(39789) by com.google.android.gms
D/ChimeraCfgMgr( 5212): Reading stored module config
,D/ChimeraCfgMgr( 5212): Loading module com.google.android.gms.car from APK com.google.android.gms
,V/LGMDMManager( 5206): Create singleton instance
I/AudioManager( 5206): getMode name:com.lge.qremote
D/UEI.SmartControl( 4996): -----IControl: 11
,D/UEI.SmartControl( 4996): Caller: com.lge.qremote
D/UEI.SmartControl( 4996): ------------ IControl registerCallback...
I/UEI.SmartControl( 4996): Registering callback...
D/UEI.SmartControl( 4996): -----IControl: 19
D/UEI.SmartControl( 4996): Caller: com.lge.qremote
,I/UEI.SmartControl( 4996): Registering Services Ready callback...
I/UEI.SmartControl( 4996): Notify client services are ready...
D/UEI.SmartControl( 4996): -----IControl: 8
D/UEI.SmartControl( 4996): Caller: com.lge.qremote
I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
I/ActivityManager(  848): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5256 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/NativeLibraryUtils( 5212): Install completed successfully. count=14 extracted=0
,I/Gmail   ( 5160): getAccountsCursor
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/CAR.SERVICE( 5212): Connecting to CarCallService...
,I/art     (  848): Explicit concurrent mark sweep GC freed 23013(1149KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/33MB, paused 2.152ms total 149.448ms
,I/art     ( 5212): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5212): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/ResourcesManager( 5256): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Icing   ( 4049): Internal init done: storage state 0
,I/Icing   ( 4049): Post-init done
,D/CAR.SERVICE( 5212): com.google.android.projection.gearhead isn't installed.
D/CAR.TEL.Service( 5212): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 5212): Creating a new PhoneAdapter instance
W/ActivityManager(  848): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5212): setListener: com.google.android.gms.car.dn@32a5f0eb
,W/ActivityManager(  848): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5212): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 5212): Starting CarCallService with initial phone null
I/NotificationManager( 5212): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/CAR.SERVICE( 5212): Package validated; name: com.android.vending
,I/art     ( 5066): Explicit concurrent mark sweep GC freed 7911(397KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 424us total 42.092ms
,I/NotificationManager( 5089): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 5089): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,D/UEI.SmartControl( 4996): Internal timer expired: 1
,I/ActivityManager(  848): Process com.lge.appbox.client (pid 4853) has died
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  848): android: cancelAsUser(2) by android
,D/libc-netbsd( 5089): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5089): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Finsky  ( 5089): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 5089): [1] DailyHygiene.access$600: Logging device features
V/AlarmManager(  848): RTC_WAKEUP set : Alarm{325cc939 type 0 when 1456908870456 com.android.vending} when 1456908870456
,I/Babel_SMS( 5256): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5256): MmsConfig.loadMmsSettings
,D/Finsky  ( 5089): [1] DailyHygiene.reschedule: Scheduling new run in 92 minutes (failures=3)
I/Babel_SMS( 5256): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5256): MmsConfig.loadFromDatabase
I/art     ( 5256): CheckpointMarkThreadRoots callback created = 0xaaf26b40
,D/DeviceConnectionService( 1749): client connected with version: 8296000
E/Babel_SMS( 5256): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5256): MmsConfig.loadFromResources
I/art     ( 5256): CheckpointMarkThreadRoots callback created = 0xaaf26b20
E/Babel_SMS( 5256): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5256): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,I/ActivityManager(  848): Process com.lge.lockscreensettings (pid 4919) has died
,D/WearableService( 1749): callingUid 10006, callindPid: 1749
D/Finsky  ( 5089): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 5089): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,D/SensorManager( 5256): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5256): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5256): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5256): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5256): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5256): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5256): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5256): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5256): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5256): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5256): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5256): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5256): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5256): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5256): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5256): found sensor: Motion Accel, handle=46
W/Settings( 5256): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5256): startup - clean
I/Babel   ( 5256): deleted: false for 0
,I/AudioManager( 5206): getMode name:com.lge.qremote
,I/AudioManager( 5206): getMode name:com.lge.qremote
,W/AudioCapabilities( 5256): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5256): Unsupported mime audio/adpcm
W/AudioCapabilities( 5256): Unsupported mime audio/g726
W/AudioCapabilities( 5256): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5256): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5256): Unsupported mime video/mjpg
W/VideoCapabilities( 5256): Unsupported mime video/theora
,W/AudioCapabilities( 5256): Unsupported mime audio/evrc
,W/AudioCapabilities( 5256): Unsupported mime audio/qcelp
W/VideoCapabilities( 5256): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5256): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5256): Unsupported mime audio/qcelp
W/AudioCapabilities( 5256): Unsupported mime audio/evrc
,W/VideoCapabilities( 5256): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5256): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5256): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5256): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5256): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5256): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  848): Process com.google.android.apps.docs (pid 4978) has died
,I/vclib   ( 5256): onServiceConnected
,W/Babel   ( 5256): Attempted to change video mute state without an active call.
,I/ActivityManager(  848): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5298 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/Icing   ( 4049): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
I/NotificationManager( 5256): com.google.android.talk: cancel(10436) by com.google.android.talk
I/NotificationManager( 5256): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 5256): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5256): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/AppUp4:AppBoxCP( 5298): onCreate
W/AppUp4:DB( 5298):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 5298):  setFingerPrint start
I/AppUp4:DB( 5298):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 5298):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5298):  SDK version = 0
I/AppUp4:DB( 5298):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 5298): AppBoxApplication onCreate()
V/JNIHelp ( 5256): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/Icing   ( 4049): Loaded CLD2 Version V2.0 - 20141016
I/AppUp4:CustModeStarterReceiver( 5298): onReceive
I/AppUp4:CustModeStarterReceiver( 5298): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 5298): Context : android.app.ReceiverRestrictedContext@3c606f9c
D/AppUp4:CustFacade( 5298): isCustomizationCompleted : false
I/Icing   ( 4049): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
D/AppUp4:CustFacade( 5298): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 5298): begin check event
I/AppUp4:CustModeStarterReceiver( 5298): Event For Nothing, skip.
I/ActivityManager(  848): Killing 4936:com.lge.eula/1000 (adj 15): empty #11
W/System  ( 5256): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5256): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  848): failed to open /acct/uid_1000/pid_4936/cgroup.procs: No such file or directory
I/ActivityManager(  848): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5320 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
W/ResourcesManager( 5320): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5320): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5320): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/ActivityManager(  848): Process com.lge.bnr (pid 4956) has died
I/AppConfig( 5320): Total System Memory = 906309632
I/GalleryUtils( 5320): Application Heap = 96 MB
I/AppConfig( 5320): App Tier : NOT_DEF
D/SystemHelper( 5320): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager(  848): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5342 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/art     (  299): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 25.499ms
I/art     (  299): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 20.722ms
,I/art     (  299): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 21.526ms
W/ResourcesManager( 5342): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5342): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5342): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 5342): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5342): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 5342): BUILD Country: EU
I/SystemConfig( 5342): BUILD Operator: OPEN
,I/SystemConfig( 5342): pm.hasSystemFeature(com.lge.ims.rcs) = false
,I/SystemConfig( 5342): existFile = false
I/SystemConfig( 5342): canReadFile = false
I/SystemConfig( 5342): systemFeature RCS result false
D/SystemConfig( 5342): refreshRcsSupport() :false
I/CheckinService( 4049): Done disabling old GoogleServicesFramework version
,I/ActivityManager(  848): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5366 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  848): Killing 5038:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  848): failed to open /acct/uid_10086/pid_5038/cgroup.procs: No such file or directory
,I/LockScreenSettings( 5366): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 5366): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 5366): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5366): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5366): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5366): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  848): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5386 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  848): Killing 5160:com.google.android.gm/u0a53 (adj 15): empty #11
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4586): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,V/io.jxcore.node.JXcoreExtension( 4586): isBleMultipleAdvertisementSupported: NOT_RESOLVED
I/jxcore-log( 4586): BLE multiple advertisement supported
I/jxcore-log( 4586): 
W/libprocessgroup(  848): failed to open /acct/uid_10053/pid_5160/cgroup.procs: No such file or directory
,W/ResourcesManager( 5386): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/jxcore-log( 4586): INFO testUtils Toggling radios to: true
I/jxcore-log( 4586): 
,D/BluetoothManagerService(  848): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  848): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  848): Message: 1
D/BluetoothManagerService(  848): MESSAGE_ENABLE: mBluetooth = null
D/InitAlarmsService( 3579): Clearing and rescheduling alarms.
I/jxcore-log( 4586): Unit Test app is loaded
I/jxcore-log( 4586): 
,D/BluetoothAdapterService(1072279366)( 2073): onBind()
,D/LocationManagerService(  848): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  848): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  848): JNI:system_update. Event-4
,I/chromium( 4586): [INFO:CONSOLE(66)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (66)
I/ActivityManager(  848): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5408 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/BluetoothManagerService(  848): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  848): Message: 40
D/BluetoothManagerService(  848): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/WifiServiceImplEx(  848): setWifiEnabled: true pid=4586, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  848): setWifiEnabled: true pid=4586, uid=10316
,D/LocationManagerService(  848): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  848): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  848): JNI:system_update. Event-4
D/WifiServiceImplEx(  848): disconnect pid=4586, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  848): reconnect pid=4586, uid=10316, packageName=com.test.thalitest
I/LGFTMITEM(  848): [GET_FTM][id=6], offset=12288
I/bluedroid( 2073): config_hci_snoop_log
E/WifiHW  (  848): Wifi MAC Address = a0:39:f7:70:12:80
D/BluetoothManagerService(  848): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  848): Broadcasting onBluetoothServiceUp() to 9 receivers.
E/WifiHW  (  848): wifi_check_config compare "cur_etheraddr=a0:39:f7:70:12:80
E/WifiHW  (  848): band=b
E/WifiHW  (  848): ": cur_etheraddr=a0:39:f7:70:12:80
,D/SoftapController(  271): Softap fwReload - Ok
,I/UpdateIcingCorporaServi( 2022): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
D/libc-netbsd(  848): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  848): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/CommandListener(  271): Setting iface cfg
D/CommandListener(  271): Trying to bring down wlan0
D/CommandListener(  271): Clearing all IP addresses on wlan0
E/WifiHW  (  848): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,E/lowmemorykiller(  242): Error writing /proc/4049/oom_score_adj; errno=22
,V/LGMDMManagerInternal( 2073): Create singleton instance
E/lowmemorykiller(  242): Error writing /proc/4049/oom_score_adj; errno=22
I/ActivityManager(  848): Killing 4049:com.google.android.gms/u0a6 (adj 15): empty #11
,W/ResourcesManager( 5408): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/wpa_supplicant( 5434): Successfully initialized wpa_supplicant
I/UpdateIcingCorporaServi( 2022): UpdateCorporaTask done [took 122 ms] updated apps [took 122 ms] 
,D/CalendarProvider2( 5408): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@2a28cbe9
,W/libprocessgroup(  848): failed to open /acct/uid_10006/pid_4049/cgroup.procs: No such file or directory
,I/wpa_supplicant( 5434): rfkill: Cannot open RFKILL control device
I/wpa_supplicant( 5434): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
D/BluetoothAdapterService(1072279366)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@28ecf7cc
D/BluetoothAdapterService(1072279366)( 2073): enable() - Enable called with quiet mode status =  false
D/WifiMonitor(  848): startMonitoring(wlan0) with mConnected = false
D/BluetoothAdapterState( 2073): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 2073): Setting state to 11
,D/CalendarProvider2( 5408): [getOrCreateCalendarAlarmManager]
I/WifiServerServiceExt(  848): WIFI_STATE_CHANGED_ACTION [2]
I/CalendarProvider2( 5408): Created com.android.providers.calendar.CalendarAlarmManager@3345b57a(com.android.providers.calendar.CalendarProvider2@2a28cbe9)
I/QCNEJ   ( 1908): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
I/BluetoothAdapterState( 2073): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService(1072279366)( 2073): updateAdapterState() - Broadcasting state to 1 receivers.
D/BluetoothManagerService(  848): Message: 60
,D/BluetoothManagerService(  848): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  848): Bluetooth State Change Intent: 10 -> 11
I/ActivityManager(  848): Start proc com.google.android.gms for service com.google.android.gms/.app.service.PackageBroadcastService: pid=5437 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
I/QCNEJ   ( 1908): |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-03-02 09:54:32.946 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1908): |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
D/BluetoothAdapterService(1072279366)( 2073): processStart()
,D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/LGBluetoothAPIService( 1872): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,D/CalendarProvider2( 5408): Scheduling check of next Alarm
D/BtSettings.ProfileConfig( 2073): Unable to read settings
D/BtSettings.ProfileConfig( 2073): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2073): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 2073): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 2073): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 2073): 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:672)
D/BtSettings.ProfileConfig( 2073): 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
D/BtSettings.ProfileConfig( 2073): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 2073): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 2073): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 2073): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 2073): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager(  848): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=5452 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
W/BluetoothAdapterService( 2073): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,D/CalendarProvider2( 5408): SCHEDULE_ALARM_REMOVE
,D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  848): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/BluetoothAdapterService( 2073): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 2073): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 2073): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 2073): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 2073): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 2073): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 2073): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,W/BluetoothAdapterService( 2073): isProfileEnabled(): profile not found com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 2073): isProfileEnabled(): profile not found com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(1072279366)( 2073): processStart() - Make Bond State Machine
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1361): Got action android.net.wifi.WIFI_STATE_CHANGED at null
D/BluetoothBondStateMachine( 2073): make
,D/BluetoothAdapterService( 2073): setAdapterService() - set to: null
D/BluetoothAdapterService( 2073): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fe9af46
D/LGBluetoothServiceAdapter( 2073): [BTUI] check adapter is available - true : set adapter available.
I/BluetoothBondStateMachine( 2073): StableState(): Entering Off State
W/ResourcesManager( 5437): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,D/BluetoothAdapterService( 2073): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2073): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/ResourcesManager( 5437): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/BtSettings.ProfileConfig( 2073): Unable to read settings
D/BtSettings.ProfileConfig( 2073): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2073): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 2073): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 2073): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 2073): 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
D/BtSettings.ProfileConfig( 2073): 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:712)
D/BtSettings.ProfileConfig( 2073): 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
D/BtSettings.ProfileConfig( 2073): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 2073): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 2073): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 2073): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 2073): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BluetoothAdapterService( 2073): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService(1072279366)( 2073): setProfileServiceState() - Starting service com.android.bluetooth.hfp.HeadsetService
I/ActivityManager(  848): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5478 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  848): Killing 3579:com.android.calendar/u0a13 (adj 15): empty #11
,D/BluetoothAdapterService(1072279366)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@28ecf7cc
D/BluetoothAdapterService(1072279366)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@28ecf7cc
I/[SystemUI]QuickSettingsHandler( 1361): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
D/BluetoothAdapterService( 2073): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2073): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 2073): Not skipping com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService(1072279366)( 2073): setProfileServiceState() - Starting service com.android.bluetooth.a2dp.A2dpService
I/MultiDex( 5437): VM with version 2.1.0 has multidex support
I/MultiDex( 5437): install
I/MultiDex( 5437): VM has multidex support, MultiDex support library is disabled.
,I/[SystemUI]BluetoothHandler( 1361): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
W/libprocessgroup(  848): failed to open /acct/uid_10013/pid_3579/cgroup.procs: No such file or directory
,D/BluetoothAdapterService( 2073): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2073): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 2073): Not skipping com.android.bluetooth.hid.HidService
D/BluetoothAdapterService(1072279366)( 2073): setProfileServiceState() - Starting service com.android.bluetooth.hid.HidService
D/HeadsetService( 2073): Received start request. Starting profile...
D/BluetoothHeadset(  848): Proxy object connected
D/BluetoothHeadset( 1782): Proxy object connected
,I/LGBluetoothHeadsetServiceJni( 2073): classInitNative: succeeds
D/BluetoothAdapterService( 2073): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2073): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 2073): Not skipping com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService(1072279366)( 2073): setProfileServiceState() - Starting service com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService(1072279366)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@28ecf7cc
D/BluetoothAdapterService( 2073): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2073): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 2073): Not skipping com.android.bluetooth.pan.PanService
D/BluetoothAdapterService(1072279366)( 2073): setProfileServiceState() - Starting service com.android.bluetooth.pan.PanService
D/LGBluetoothFeatureConfig( 2073): isPrivacyLogsEnabled : true
I/BluetoothHeadsetServiceJni( 2073): classInitNative: succeeds
,D/BluetoothAdapterService( 2073): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2073): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 2073): Not skipping com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(1072279366)( 2073): setProfileServiceState() - Starting service com.android.bluetooth.gatt.GattService
D/HeadsetStateMachine( 2073): make
D/BluetoothAdapterService( 2073): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2073): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 2073): Not skipping com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService(1072279366)( 2073): setProfileServiceState() - Starting service com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2073): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2073): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 2073): Not skipping com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1072279366)( 2073): setProfileServiceState() - Starting service com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 2073): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2073): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 2073): Not skipping com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(1072279366)( 2073): setProfileServiceState() - Starting service com.broadcom.bt.service.ftp.FTPService
,D/BluetoothHeadset( 1782): Proxy object connected
D/BluetoothAdapterService( 2073): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2073): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
D/BtSettings.ProfileConfig( 2073): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 2073): Not skipping com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(1072279366)( 2073): setProfileServiceState() - Starting service com.broadcom.bt.service.opp.OppService
D/BluetoothHeadset( 1782): Proxy object connected
V/LGMDMManager( 2073): Create singleton instance
,I/BluetoothAdapterState( 2073): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetStateMachine( 2073): max_hf_connections = 1
I/bluedroid( 2073): get_profile_interface handsfree
I/bt-btif ( 2073): btif_hf_get_interface
I/bt-btif ( 2073): init
D/bt-btif ( 2073): max_hf_clients = 1
D/bt-btif ( 2073): btif_max_hf_clients = 1
D/bt-btif ( 2073): btif_enable_service: current services:0xa06c0330
V/ToneGenerator( 2073): ToneGenerator constructor: streamType=8, volume=1.000000
V/AudioPolicyService(  275): registerClient() client 0xb39b64c0, uid 1002
V/AudioPolicyManager(  275): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  275): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  275): getOutput() returns output 2
V/AudioFlinger(  275): registerClient() client 0xb3ac3160, pid 2073
V/AudioFlinger(  275): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  275): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  275): sendConfigEvent_l() num events 1 event 0
V/AudioSystem( 2073): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioFlinger(  275): thread 0xb56eb000 type 0 TID 1287 waking up
V/AudioFlinger(  275): processConfigEvents_l() remaining events 1
V/AudioFlinger(  275): PlaybackThread::audioConfigChanged, thread 0xb56eb000, event 0, param 0
V/AudioSystem(  275): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  275): ioConfigChanged() opening already existing output! 4
V/AudioFlinger(  275): processConfigEvents_l() DONE thread 0xb56eb000
V/AudioSystem( 2022): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 2022): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 3037): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3037): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1782): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1782): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 2073): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 2073): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/AudioFlinger(  275): thread 0xb5735000 type 0 TID 1289 waking up
V/AudioSystem(  848): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  848): ioConfigChanged() opening already existing output! 4
V/AudioFlinger(  275): processConfigEvents_l() remaining events 1
V/AudioFlinger(  275): PlaybackThread::audioConfigChanged, thread 0xb5735000, event 0, param 0
V/AudioSystem(  275): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem(  275): ioConfigChanged() opening already existing output! 6
V/AudioFlinger(  275): processConfigEvents_l() DONE thread 0xb5735000
V/AudioFlinger(  275): thread 0xb5651000 type 0 TID 1285 waking up
V/AudioFlinger(  275): processConfigEvents_l() remaining events 1
V/AudioFlinger(  275): PlaybackThread::audioConfigChanged, thread 0xb5651000, event 0, param 0
V/AudioSystem(  848): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem(  848): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 2022): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 2022): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 2095): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 2095): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 2073): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 2073): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 1152 latency 112
V/AudioSystem( 3037): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem(  275): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3037): ioConfigChanged() opening already existing output! 6
V/AudioSystem(  275): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1361): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1361): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 2095): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 2095): ioConfigChanged() opening already existing output! 6
V/ToneGenerator( 2073): Create Track: 0xb4909480
V/AudioTrack( 2073): set(): streamType 8, sampleRate 48000, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 2073): set() streamType 8, sampleRate 48000, format 1, frameCount 0, flags 0004
V/AudioFlinger(  275): processConfigEvents_l() DONE thread 0xb5651000
V/AudioSystem( 2095): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2095): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 2073): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2073): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
I/AudioFlinger(  275): isAudioPlaybackHookO,n() false
D/AudioTrack( 2073): TrackOffload: AudioTrack Offload disabled by property, returning false
V/AudioPolicyManager(  275): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  275): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioPolicyManagerEx(  275): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  275): getOutput() returns output 2
V/AudioSystem(  848): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  848): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 2073): getLatency() output 2, latency 50
V/AudioSystem( 2073): getFrameCount() output 2, frameCount 960
V/AudioTrack( 2073): createTrack_l() output 2 afLatency 50
V/AudioTrack( 2073): Create normal PCM 0x1 Track
V/AudioFlinger(  275): createTrack() lSessionId: 22
V/AudioFlinger(  275): AUDIO_OUTPUT_FLAG_FAST accepted: frameCount=480 mFrameCount=240
V/AudioFlinger(  275): sendConfigEvent_l() num events 1 event 1
V/AudioSystem( 3037): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3037): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1361): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1361): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 2022): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2022): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1361): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1361): ioConfigChanged() opening already existing output! 2
V/AudioTrack( 2073): Flags here  0x4 
V/AudioTrack( 2073): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  275): acquiring 22 from 2073, for 2073
V/AudioFlinger(  275):  added new entry for 22
V/ToneGenerator( 2073): ToneGenerator INIT OK, time: 82450
D/BluetoothAdapterService( 2073): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fe9af46
V/AudioFlinger(  275): processConfigEvents_l() remaining events 1
V/AudioFlinger(  275): processConfigEvents_l() DONE thread 0xb5651000
D/HeadsetStateMachine( 2073): Enter Disconnected: -2, size: 0
D/HeadsetPhoneState( 2073): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 2073): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 2073): [BTUI] change sampling rate to 8000 when device is disconnected
V/AudioFlinger(  275): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 2073
D/audio_hw_primary(  275): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  275): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  275): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  275): voice_extn_compress_voip_set_parameters: exit
V/voice   (  275): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  275): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  275): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  275): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  275): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  275): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  275): adev_set_parameters: exit with code(0)
V/ToneGenerator( 2073): ToneGenerator destructor
V/ToneGenerator( 2073): stopTone
V/ToneGenerator( 2073): Delete Track: 0xb4909480
V/AudioTrack( 2073): ~AudioTrack, releasing session id from 2073 on behalf of 2073
,V/AudioFlinger(  275): releasing 22 from 2073 for 2073
V/AudioFlinger(  275):  decremented refcount to 0
V/AudioFlinger(  275): purging stale effects
V/AudioFlinger(  275): remove track (4099) and delete from mixer
V/AudioPolicyService(  275): AudioCommandThread() adding release output 2
V/AudioPolicyService(  275): inserting command: 6 at index 0, num commands 0
V/AudioFlinger(  275): PlaybackThread::Track destructor
V/AudioFlinger(  275): removeClient_l() pid 2073, calling pid 275
V/AudioPolicyService(  275): AudioCommandThread() waking up
V/AudioPolicyService(  275): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  275): releaseOutput() 2
V/AudioPolicyService(  275): AudioCommandThread() going to sleep
V/AudioSystem( 1782): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1782): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1782): ioConfigChanged() event 0, ioHandle 2
,V/AudioSystem( 1782): ioConfigChanged() opening already existing output! 2
I/ActivityManager(  848): Process com.lge.qremote (pid 5206) has died
,D/UEI.SmartControl( 4996): Service.onUnbind: IControl
D/UEI.SmartControl( 4996): Service.onDestroy
D/BluetoothAdapterService( 2073): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fe9af46
D/BluetoothA2dp(  848): Proxy object connected
D/A2dpService( 2073): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 2073): classInitNative: succeeds
D/UEI.SmartControl( 4996): Shutdown IRRCPlayer... 
V/Avrcp   ( 2073): make
D/Avrcp   ( 2073): [BTUI] Use Native AVRCP : init jni
I/bluedroid( 2073): get_profile_interface avrcp
D/BluetoothAdapterService(1072279366)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@28ecf7cc
,I/bt-btif ( 2073): btif_rc_get_interface
I/bt-btif ( 2073): ## init ##
I/LGBluetoothAvrcpServiceJni( 2073): classInitNative: succeeds
I/LGBluetoothAvrcpAdapter( 2073): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
I/LGBluetoothAvrcpServiceJni( 2073): initNative: succeeds
W/ResourcesManager( 5452): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5452): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 5452): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/irrc_jni( 4996): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 4996): ~IrrcClient ++ 
D/irrcClient( 4996): ~IrrcClient -- 
W/irrc_jni( 4996): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 4996): Blaster closed
D/UEI.SmartControl( 4996): Blaster closed
D/UEI.SmartControl( 4996): Shut down QS...
W/ResourcesManager( 5452): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/UEI.SmartControl( 4996): Stopped file observer...
W/ResourcesManager( 5452): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/UEI.SmartControl( 4996): QS lib stop result = true
,D/UEI.SmartControl( 4996): QS shutdown complete
,I/ActivityManager(  848): Process com.google.process.gapps (pid 5066) has died
,I/IndexDatabaseHelper( 5452): Using schema version: 115
,I/IndexDatabaseHelper( 5452): Index is fine
I/art     (  848): Explicit concurrent mark sweep GC freed 16358(740KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 2.622ms total 169.709ms
,I/ActivityManager(  848): Process com.uei.lg.quicksetsdk.lite (pid 4996) has died
,I/BluetoothAvrcpBrcmAdapterJni( 2073): classInitBrcmNative
W/ActivityManager(  848): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/BluetoothAvrcpBrcmAdapterJni( 2073): initBrcmNative
I/ActivityManager(  848): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5507 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/AudioService(  848): updateRemoteControllerOnExistingMediaPlayers: size of Player list: 0
,E/AudioService(  848): No RCC entry present to update
E/RemoteController( 2073): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 2073): classInitNative
I/BluetoothA2dpServiceJni( 2073): classInitNative: succeeds
D/A2dpStateMachine( 2073): make
I/bluedroid( 2073): get_profile_interface a2dp
I/bt-btif ( 2073): btif_av_get_src_interface
I/bt-btif ( 2073): init
D/bt-btif ( 2073): btif_enable_service: current services:0xa06c0330
I/LGBluetoothA2dpServiceJni( 2073): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 2073): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/LGBluetoothPowerControlManager( 2073): [BTUI] getInstance
D/LGBluetoothPowerControlManager( 2073): [BTUI] init
D/LGBluetoothPowerControlManager( 2073): [BTUI] init : getProfileProxy
,D/BluetoothManagerService(  848): Message: 30
D/BluetoothAdapterService( 2073): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fe9af46
D/A2dpStateMachine( 2073): Enter Disconnected: -2
I/BluetoothHidServiceJni( 2073): classInitNative: succeeds
I/GservicesProvider( 5507): Gservices pushing to system: true; secure/global: true
D/HidService( 2073): Received start request. Starting profile...
I/bluedroid( 2073): get_profile_interface hidhost
I/bt-btif ( 2073): btif_hh_get_interface
I/bt-btif ( 2073): init
D/bt-btif ( 2073): btif_enable_service: current services:0xa06c0330
D/BluetoothAdapterService( 2073): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fe9af46
I/BluetoothHealthServiceJni( 2073): classInitNative: succeeds
D/HealthService( 2073): Received start request. Starting profile...
,I/bluedroid( 2073): get_profile_interface health
I/bt-btif ( 2073): btif_hl_get_interface
I/bt-btif ( 2073): init
D/bt-btif ( 2073): Process name (droid.bluetooth)
D/bt-btif ( 2073): btif_hl_soc_thread_init
D/bt-btif ( 2073): create_thread: entered
D/bt-btif ( 2073): create_thread: thread created successfully
D/bt-btif ( 2073): entered btif_hl_select_thread
D/bt-btif ( 2073): btif_hl_select_wakeup_init
D/bt-btif ( 2073): btif_hl_select_wakeup_init signal_fds[0]=55 signal_fds[1]=56
D/bt-btif ( 2073): max_s=55 
D/bt-btif ( 2073): set curr_set = org_set 
I/LGBluetoothHealthServiceJni( 2073): classInitNative: succeeds
D/BluetoothAdapterService( 2073): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fe9af46
I/BluetoothPanServiceJni( 2073): classInitNative(L105): succeeds
D/PanService( 2073): Received start request. Starting profile...
,D/BluetoothPanServiceJni( 2073): initializeNative(L110): pan
I/bluedroid( 2073): get_profile_interface pan
D/bt-btif ( 2073): stack_initialized = 0, btpan_cb.enabled:0
I/ActivityManager(  848): Process com.android.gallery3d (pid 5320) has died
,I/LGBluetoothPanAdapter( 2073): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 2073): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fe9af46
I/BtGatt.JNI( 2073): classInitNative(L901): classInitNative: Success!
I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 4
D/BtGatt.DebugUtils( 2073): handleDebugAction() action=null
,D/BtGatt.GattService( 2073): Received start request. Starting profile...
D/BtGatt.GattService( 2073): start()
I/bluedroid( 2073): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 2073): advertise manager created
I/LGBluetoothGattAdapter( 2073): [BTUI] getInstance : create [LGBluetoothGattAdapter]
D/LGBluetoothGattAdapter( 2073): setGattService:  set to: null
D/BluetoothAdapterService( 2073): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fe9af46
D/BluetoothAdapterService( 2073): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fe9af46
I/LGBluetoothMapAdapter( 2073): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 2073): BluetoothMapBinder()
,D/BluetoothMapService( 2073): Received start request. Starting profile...
D/BluetoothMapService( 2073): start()
D/Tethering(  848): sendTetherStateChangedBroadcast 1, 0, 0
D/libc-netbsd(  848): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/BluetoothMapEmailSettingsLoader( 2073): Found 0 applications
D/libc-netbsd(  848): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/BluetoothMapEmailAppObserver( 2073): createReceiver()
D/libc-netbsd(  848): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  848): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  271): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  271): App 1000 tries DNS query. Accept family:0 protocol:0
D/BluetoothMapEmailAppObserver( 2073): initObservers()
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/BluetoothMapEmailAppObserver( 2073): getEnabledAccountItems()
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  848): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/BluetoothAdapterService( 2073): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fe9af46
D/libc-netbsd(  848): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  848): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/BluetoothSAPServiceJni( 2073): classInitNative(L170): succeeds
D/SapService( 2073): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 2073): initializeNative(L175): sap
I/bluedroid( 2073): get_profile_interface sap
I/bt-btif ( 2073): btif_sc_get_interface
I/bt-btif ( 2073): init
D/bt-btif ( 2073): btif_enable_service: current services:0xa06c0330
I/LGBluetoothSapAdapter( 2073): [BTUI] getInstance : create [LGBluetoothSapAdapter]
I/LGBluetoothSapAdapter( 2073): [BTUI] Create LGBluetoothSapManager Instance
D/LGBluetoothSapManager( 2073): [BTUI] initSapManager
D/BluetoothAdapterService( 2073): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fe9af46
,D/LgeBluetoothSimManager( 1782): [BTUI] SAP_ENABLE_EVT
I/GoogleHttpClient( 5507): GMS http client unavailable, use old client
V/BluetoothFTPServiceJni( 2073): classInitNative
,I/BluetoothFTPServiceJni( 2073): classInitNative(L271): succeeds
D/BluetoothAdapterService( 2073): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fe9af46
D/BluetoothFTPService( 2073): BluetoothFtpBinder()
D/**BluetoothFTPService( 2073): Received start request. Starting profile...
V/BluetoothFTPService( 2073): FTP-Server Service start
E/wpa_supplicant( 5434): USIM:  scard_init function
I/wpa_supplicant( 5434): rfkill: Cannot open RFKILL control device
D/BluetoothFTPServiceJni( 2073): initFtpNativeDataNative(L275): FTP
I/bluedroid( 2073): get_profile_interface ftp
I/bt-btif ( 2073): btif_fts_get_interface
I/bt-btif ( 2073): init
D/bt-btif ( 2073): btif_enable_service: current services:0xa06c0330
D/BluetoothFTPServiceJni( 2073): initFtpNativeDataNative(L317): FTP init done
D/BluetoothAdapterService( 2073): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fe9af46
I/Netd    (  271): M: Get netlink event, ifname: p2p0 action: 4
I/Netd    (  271): M: Get netlink event, ifname: p2p0 action: 9
D/LGBluetoothFeatureConfig( 2073): isPrivacyLogsEnabled : true
E/BluetoothOPPServiceJni( 2073): classInitNative
I/BluetoothOPPServiceJni( 2073): classInitNative(L373): succeeds
I/Netd    (  271): M: Get netlink event, ifname: p2p0 action: 4
D/libc-netbsd(  848): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  848): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/OppService( 2073): Opp initBinder
D/**OppService( 2073): Received start request. Starting profile...
D/OppService( 2073): Starting OppService 
D/LGBluetoothOppAdapter( 2073): [BTUI] getInstance : create [LGBluetoothOppAdapter]
,I/NotificationManager( 2073): com.android.bluetooth: cancelAll by com.android.bluetooth
V/BluetoothOppNotification( 2073): send message
D/BluetoothOppPreference( 2073): Dumping Names:  
D/BluetoothOppPreference( 2073): {}
D/BluetoothOppPreference( 2073): Dumping Channels:  
D/BluetoothOppPreference( 2073): {}
D/OppService( 2073): Start()
W/BluetoothOPPServiceJni( 2073): initOppNative
D/BluetoothOPPServiceJni( 2073): initOppNative(L383): OPP
I/bluedroid( 2073): get_profile_interface opp
I/bt-btif ( 2073): btif_op_get_interface
D/BluetoothOPPServiceJni( 2073): initOppNative(L411): mOppCallbacksObj 1049850
D/BluetoothOPPServiceJni( 2073): initOppNative(L413): calling OPP init
I/bt-btif ( 2073): btif_opp_init
D/bt-btif ( 2073): btif_enable_service: current services:0xa06c0330
D/BluetoothOPPServiceJni( 2073): initOppNative(L429): OPC and OPS init Succesful
D/BluetoothOPPServiceJni( 2073): initOppNative(L430): mOppCallbacksObj 1049850
V/OppService( 2073): setOppService(): set to: com.broadcom.bt.service.opp.OppService@b5d185c
D/BluetoothAdapterService( 2073): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fe9af46
,D/HeadsetStateMachine( 2073): Proxy object connected
D/LGBluetoothHfpAdapter( 2073): [BTUI] queryPhoneState
D/BluetoothAdapterService(1072279366)( 2073): handleMessage() - Message: 1
D/BluetoothAdapterService(1072279366)( 2073): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1072279366)( 2073): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
D/BluetoothAdapterState( 2073): isTurningOnRadio()=false
V/OppService( 2073): pendingUpdate is :  true
D/BluetoothAdapterState( 2073): isTurningOffRadio()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2073): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 2073): Profile still not running:com.broadcom.bt.service.opp.OppService
D/HeadsetStateMachine( 2073): Disconnected process message: 10, size: 0
V/BluetoothPbapReceiver( 2073): PbapReceiver onReceive 
D/HeadsetPhoneState( 2073): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 2073): Disconnected process message: 11, size: 0
V/BluetoothPbapReceiver( 2073): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 2073): ***********state = 11
V/OppService( 2073): Deleted complete outbound shares, number =  0
D/BluetoothA2dp( 2073): Proxy object connected
D/LGBluetoothPowerControlManager( 2073): [BTUI] onServiceConnected : Got BluetoothA2dp: android.bluetooth.BluetoothA2dp@32a5f0eb
D/BluetoothAdapterService(1072279366)( 2073): handleMessage() - Message: 1
D/BluetoothAdapterService(1072279366)( 2073): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1072279366)( 2073): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
D/BluetoothAdapterState( 2073): isTurningOnRadio()=false
V/BluetoothOppProvider( 2073): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
D/BluetoothAdapterState( 2073): isTurningOffRadio()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2073): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/OppService( 2073): Deleted complete inbound failed shares, number = 0
,V/BluetoothOppProvider( 2073): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 2073): created cursor android.database.sqlite.SQLiteCursor@20d15e48 on behalf of 
V/BluetoothOppProvider( 2073): created cursor android.database.sqlite.SQLiteCursor@378f44e1 on behalf of 
D/BluetoothAdapterService( 2073): Profile still not running:com.broadcom.bt.service.opp.OppService
I/GoogleHttpClient( 5507): GMS http client unavailable, use old client
D/BluetoothAdapterService(1072279366)( 2073): handleMessage() - Message: 1
D/BluetoothAdapterService(1072279366)( 2073): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1072279366)( 2073): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
D/BluetoothAdapterState( 2073): isTurningOnRadio()=false
D/BluetoothAdapterState( 2073): isTurningOffRadio()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2073): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/BluetoothOppNotification( 2073): update too frequent, put in queue
D/BluetoothAdapterService( 2073): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(1072279366)( 2073): handleMessage() - Message: 1
D/BluetoothAdapterService(1072279366)( 2073): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1072279366)( 2073): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
D/BluetoothAdapterState( 2073): isTurningOnRadio()=false
D/BluetoothAdapterState( 2073): isTurningOffRadio()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2073): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/OppService( 2073): pendingUpdate is :  false
E/OppService( 2073): UpdateThread is Completed
D/BluetoothAdapterService( 2073): Profile still not running:com.broadcom.bt.service.opp.OppService
I/wpa_supplicant( 5434): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,V/PanService( 2073): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService(1072279366)( 2073): handleMessage() - Message: 1
D/BluetoothAdapterService(1072279366)( 2073): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1072279366)( 2073): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
D/BluetoothAdapterState( 2073): isTurningOnRadio()=false
D/BluetoothAdapterState( 2073): isTurningOffRadio()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2073): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 2073): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(1072279366)( 2073): handleMessage() - Message: 1
D/BluetoothAdapterService(1072279366)( 2073): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1072279366)( 2073): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=true
D/BluetoothAdapterState( 2073): isTurningOnRadio()=false
D/BluetoothAdapterState( 2073): isTurningOffRadio()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2073): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 2073): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothMapService( 2073): Handler(): got msg=1
D/BluetoothAdapterService(1072279366)( 2073): handleMessage() - Message: 1
D/BluetoothAdapterService(1072279366)( 2073): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1072279366)( 2073): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
D/BluetoothAdapterState( 2073): isTurningOnRadio()=false
D/BluetoothAdapterState( 2073): isTurningOffRadio()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2073): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
,D/BluetoothPermissionRequest( 5452): onReceive
D/BluetoothAdapterService( 2073): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(1072279366)( 2073): handleMessage() - Message: 1
D/BluetoothAdapterService(1072279366)( 2073): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1072279366)( 2073): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
D/BluetoothAdapterState( 2073): isTurningOnRadio()=false
D/BluetoothAdapterState( 2073): isTurningOffRadio()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2073): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/LGBluetoothFeatureConfig( 5452):  get() - isFeatureLoaded : false
D/BluetoothAdapterService( 2073): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(1072279366)( 2073): handleMessage() - Message: 1
D/BluetoothAdapterService(1072279366)( 2073): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1072279366)( 2073): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, doUpdate=true
D/BluetoothAdapterState( 2073): isTurningOnRadio()=false
D/BluetoothAdapterState( 2073): isTurningOffRadio()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2073): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
I/wpa_supplicant( 5434): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/BluetoothAdapterService( 2073): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothOppNotification( 2073): new notify threadi!
D/WifiStateMachine(  848): MAC Addr from driver = a0:39:f7:70:12:80
V/BluetoothOppNotification( 2073): send delay message
D/BluetoothAdapterService(1072279366)( 2073): handleMessage() - Message: 1
D/BluetoothAdapterService(1072279366)( 2073): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(1072279366)( 2073): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=12, doUpdate=true
D/BluetoothAdapterState( 2073): isTurningOnRadio()=false
D/BluetoothAdapterState( 2073): isTurningOffRadio()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2073): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2073): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService(1072279366)( 2073): onProfileServiceStateChange() - All profile services started.
V/OppService( 2073): ContentObserver received notification
V/OppService( 2073): ContentObserver received notification
D/BluetoothAdapterState( 2073): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 2073): enable
I/bt-btif ( 2073): BTIF ENABLE BLUETOOTH :: current btif_core_radio_refcount: 0, btif_core_state: 0, btif_core_cb.dut_mode: 0
E/bt-btu  ( 2073): VERSION AFBT-LREL-30_00.06 (BTE: BTE0322_00.20.00)
V/BluetoothOppProvider( 2073): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/OppService( 2073): pendingUpdate is :  true
V/BluetoothOppProvider( 2073): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 2073): created cursor android.database.sqlite.SQLiteCursor@36031206 on behalf of 
V/BluetoothOppProvider( 2073): created cursor android.database.sqlite.SQLiteCursor@2570b0c7 on behalf of 
V/BluetoothOppNotification( 2073): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 2073): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
I/bt_hci_bdroid( 2073): init
I/bt_vendor( 2073): init
I/bt_vnd_conf( 2073): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
V/OppService( 2073): pendingUpdate is :  false
E/OppService( 2073): UpdateThread is Completed
I/bt_vnd_conf( 2073): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,V/BluetoothOppProvider( 2073): created cursor android.database.sqlite.SQLiteCursor@7c216f4 on behalf of 
V/BluetoothOppNotification( 2073): outbound: succ-0  fail-0
I/NotificationManager( 2073): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
I/bt-btif ( 2073): libbt-hci init returns 0
D/WifiOffDelayIfNotUsed(  848): setPowerSaveActivated(false)
W/Settings(  848): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  848): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/BluetoothOppNotification( 2073): outbound notification was removed.
I/GKI_LINUX( 2073): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 2073): btu_task pending for preload complete event
I/QCNEJ   ( 1908): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
I/QCNEJ   ( 1908): |CORE| sendWifiStatus - subType: 21 networkState: 5 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-03-02 09:54:34.024 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1908): |CORE| notifyRatConnectStatus ratType=1 status=5 ipV4Addr= ipV6Addr=
I/WifiServerServiceExt(  848): WIFI_STATE_CHANGED_ACTION [3]
V/BluetoothOppProvider( 2073): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
E/WifiServerServiceExt(  848): sendAutoJoinStatus  LgeWifiConfig.mEnableAutoJoin : 0
,I/WifiServerServiceExt(  848): batteryPsActivateMsgHandler : state:0 event:3
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
V/JNIHelp ( 5437): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/[SystemUI]QuickSettingsHandler( 1361): Got action android.net.wifi.WIFI_STATE_CHANGED at null
E/WifiConfigStore(  848): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiStateMachine(  848): enableVerboseLogging : level 2
,D/WifiStateMachine(  848): Setting OUI to DA-A1-19
D/WifiNative-HAL(  848): Setting external_sim to 1
I/WifiNative-HAL(  848): startHal
E/wifi    (  848): getStaticLongField sWifiHalHandle 0x9ad478ec
I/WifiHAL (  848): Initializing wifi
I/WifiHAL (  848): Creating socket
I/WifiHAL (  848): Initialized Wifi HAL Successfully; vendor cmd = 103
D/wifi    (  848): Did set static halHandle = 0x9cd5ee40
D/wifi    (  848): halHandle = 0x9cd5ee40, mVM = 0xb487c280, mCls = 0x601aea
E/wifi    (  848): getStaticLongField sWifiHalHandle 0x9ad4789c
D/wifi    (  848): array field set
I/WifiNative-HAL(  848): interface[0] = wlan0
I/WifiNative-HAL(  848): interface[1] = p2p0
D/WfdsService( 1872): Supplicant Connection state is changed : true
W/Settings( 5256): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/wifi    (  848): setting scan oui 0x9d0858b0
D/WifiHAL (  848): Sending mac address OUI
E/WifiHAL (  848): failed to set scanning mac OUI; result = -95
D/WifiStateMachine(  848): Setting OUI to DA-A1-19
I/WifiNative-HAL(  848): startHal
D/wifi    (  848): setting scan oui 0x9d0858b0
D/WifiHAL (  848): Sending mac address OUI
E/WifiHAL (  848): failed to set scanning mac OUI; result = -95
I/WifiNative-HAL(  848): Waiting for HAL events mWifiHalHandle=-1663701440
D/wifi    (  848): waitForHalEvents called, vm = 0xb487c280, obj = 0x601aea, env = 0x9d082400
E/wifi    (  848): getStaticLongField sWifiHalHandle 0x99996b2c
V/BluetoothOppProvider( 2073): created cursor android.database.sqlite.SQLiteCursor@255a4e1d on behalf of 
,V/BluetoothOppNotification( 2073): inbound: succ-0  fail-0
D/WfdsService( 1872): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WfdsService( 1872): Set the WFDS Monitor: true
D/WifiHS20(  848): hidePasspointNotification off =false
I/QCNEJ   ( 1908): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  848): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  848): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  848): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/BluetoothManagerService(  848): Message: 20
D/BluetoothManagerService(  848): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@17971950:true
D/WfdsMonitor( 1872): WfdsMonitorThread create
D/WfdsMonitor( 1872): WFDS Monitor is created and started
D/WfdsService( 1872): WiFi: Supplicant connection re-established
I/[SystemUI]StatusBar.NetworkController( 1361): mWifiConnected = false, mWifiLevel = 0
D/WifiScanningService(  848): SCAN_AVAILABLE : 3
D/LGWifiP2pService(  848): P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  848): SCAN_AVAILABLE : 3
D/WifiScanningService(  848): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  848): startHal
D/RttService(  848): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
E/CtrlSupplicant( 1872): Access OK "@android:wpa_wlan0"
,D/wifi    (  848): getting scan capabilities on interface[0] = 0x9d0858b0
D/WifiHAL (  848): Creating message to get scan capablities; iface = 24
D/wifi    (  848): failed to get capabilities : -95
E/WifiScanningService(  848): could not get scan capabilities
E/CtrlSupplicant( 1872): Succeed to open control connection
E/CtrlSupplicant( 1872): Succeed to open monitor connection
D/libc-netbsd(  848): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  848): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  271): Setting iface cfg
D/CommandListener(  271): Trying to bring up p2p0
D/WfdsMonitor( 1872): Supplicant connection established
D/WifiMonitor(  848): startMonitoring(p2p0) with mConnected = true
D/WfdsService( 1872): Connected to the supplicant for wfds
D/LGWifiP2pService(  848): P2pEnablingState
D/LGWifiP2pService(  848): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1361): Got action android.net.wifi.STATE_CHANGE at null
D/LGWifiP2pService(  848): P2p socket connection successful
D/LGWifiP2pService(  848): P2pEnabledState
I/[SystemUI]QuickSettingsHandler( 1361): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1361): Remote
W/Settings(  848): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  848): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  848): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/[SystemUI]StatusBar.NetworkController( 1361): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1908): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-03-02 09:54:34.09 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1908): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1908): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1908): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-03-02 09:54:34.09 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1908): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1361): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1361): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1361): Remote
D/LGWifiP2pService(  848): [LGE_P2P] initializeP2pSettings() check postfix
D/LGWifiP2pService(  848): before postfix = G3s-1
D/WifiServerServiceExt(  848): postfix byte check : 5
D/LGWifiP2pService(  848): after postfix = G3s-1
D/WifiNative-HAL(  848): p2pGetDeviceAddress
D/WifiNative-HAL(  848): p2pGetDeviceAddress returning a2:39:f7:70:12:80
I/WifiServerServiceExt(  848): set CMD_ADD_DEFAULT_PROFILE
D/LGWifiP2pService(  848): DeviceAddress: a2:39:f7:70:12:80
D/WfdsService( 1872): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
,I/bt_userial_vendor( 2073): userial vendor open: opening /dev/ttyHS99
I/WifiServerServiceExt(  848): setWifiDualbandAPConnection band : 1
D/bt_userial_vendor( 2073): userial_vendor_open():UART is setup
I/bt_userial_vendor( 2073): device fd = 71 open
V/BluetoothSapReceiver( 2073): [BTUI] checkServiceStart
D/WfdsService( 1872): Update P2p Interface State: 3
,D/LGBluetoothStateChangeReceiver( 2073): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
I/NotificationManager( 2073): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
V/BluetoothOppNotification( 2073): inbound notification was removed.
V/BluetoothOppProvider( 2073): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
D/bt_hwcfg( 2073): hw_config_cback opcode:0x0c03
D/bt_hwcfg( 2073): hw_config_cback state=1
I/CalendarProvider2( 5408): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5408): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
V/BluetoothOppProvider( 2073): created cursor android.database.sqlite.SQLiteCursor@32ae4892 on behalf of 
D/bt_hwcfg( 2073): hw_config_cback opcode:0x0c14
D/bt_hwcfg( 2073): hw_config_cback state=4
D/bt_hwcfg( 2073): Chipset Name: BCM4334B0
D/bt_hwcfg( 2073): Chipset BCM4334B0
,D/bt_hwcfg( 2073): Target name = [BCM4334B0]
W/ActivityThread( 5437): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5437): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@32ae4892: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/bt_hwcfg( 2073): Found patchfile: /system/bin//BCM4334B0_002.001.013.1820.2163.hcd
I/ProviderInstaller( 5437): Installed default security provider GmsCore_OpenSSL
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc45
D/bt_hwcfg( 2073): hw_config_cback state=2
E/wpa_supplicant( 5434): nWIFIDualbandAPConnection: 1
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc18
D/bt_hwcfg( 2073): hw_config_cback state=3
I/bt_hwcfg( 2073): bt vendor lib: set UART baud 4000000
,I/WifiServerServiceExt(  848): set CMD_DISCONNECT_RSSI_LVL : -100
D/LGWifiP2pService(  848): sending p2p persistent groups changed broadcast
E/wpa_supplicant( 5434): disconnect_rssi_lvl: -100
I/WifiServerServiceExt(  848): set CMD_SET_FRAMEWORK_AUTO_JOIN 0
E/wpa_supplicant( 5434): wpa_supplicant_ctrl_iface_set_framework_auto_join: enable : 0
I/WifiServerServiceExt(  848): set CMD_UPDATE_DEFAULT_PROFILE
I/ActivityManager(  848): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=5556 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
D/LGWifiP2pService(  848): sending p2p connection changed broadcast
,I/NotificationManager( 5437): com.google.android.gms: cancel(10436) by com.google.android.gms
D/LGWifiP2pService(  848): InactiveState
D/LGWifiP2pService(  848): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  848): P2pEnabledState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  848): DefaultState{ when=-1ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  848): InactiveState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  848): P2pEnabledState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  848): DefaultState{ when=-1ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt(  848): No p2p device connected
I/wpa_supplicant( 5434): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,I/wpa_supplicant( 5434): [LGE_PATCH]scan interval[0] = 2 sec.
D/LGWifiP2pService(  848): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  848): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  848): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1872): Event [CTRL-EVENT-SCAN-RESULTS ]
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc2e
D/bt_hwcfg( 2073): hw_config_cback state=5
W/Settings(  848): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  848): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  848): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/NotificationManager( 5437): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WfdsService( 1872): WifiP2pState is changed : true
D/WfdsService( 1872): WIFI_P2P_CONNECTION_CHANGED_ACTION
I/[SystemUI]QuickSettingsHandler( 1361): Got action android.net.wifi.p2p.STATE_CHANGED at null
D/WfdsService( 1872): Receive the WFDS_ENABLE Method
D/WfdsService( 1872): Set the WFDS Monitor: true
D/WfdsService( 1872): Connected to the supplicant for wfds
D/WfdsJNI ( 1872): doCommand: WFDS_SET TRUE
,D/WfdsService( 1872): isConnected: false
D/LGWifiP2pService(  848): InactiveState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  848): P2pEnabledState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  848): DefaultState{ when=0 what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  848): InactiveState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  848): P2pEnabledState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  848): DefaultState{ when=0 what=139285 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1872): GroupInfoAvailable: mGroupInfo is null
I/[SystemUI]StatusBar.NetworkController( 1361): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1908): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1908): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-03-02 09:54:34.212 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1908): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1361): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1361): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1361): Remote
I/Gmail   ( 5478): getAccountsCursor
I/wpa_supplicant( 5434): wlan0: CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 5434): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
D/WfdsJNI ( 1872): doCommand: WFDS_GET_MAC_ADDRESS
I/wpa_supplicant( 5434): WFDS: wfds_supplicant_wfds_cmd: cmd = GET_MAC_ADDRESS
D/WfdsJNI ( 1872): doCommand: WFDS_CLEAR_PD_INFO
,I/wpa_supplicant( 5434): WFDS: wfds_supplicant_wfds_cmd: cmd = CLEAR_PD_INFO
D/WfdsJNI ( 1872): wfds_send_command: [WFDS_CLEAR_PD_INFO] failed
D/WfdsJNI ( 1872): doCommand: IFNAME=wlan0 GET_CAPABILITY channels
D/WfdsService( 1872): selectPreferredScanChannel [6]
D/WfdsService( 1872): STATE : WfdsEnabledState - enter: this device mac a2:39:f7:70:12:80
D/WifiServerServiceExt(  848): SUPPLICANT_STATE_CHANGED_ACTION
W/WfdsService( 1872): DefaultState - msg [9441285] is not handled
D/WifiServerServiceExt(  848): setSupplicantStateSCANNING
V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LocSvc_java(  848): onReceive
D/WifiServerServiceExt(  848): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  848): setSupplicantStateSCANNING
D/GONS    ( 1782): GONS isTestMode: false Country: 
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
,D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
,D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
W/GAV2    ( 5478): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/PackageBroadcastService( 5437): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
,D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
I/PackageBroadcastService( 5437): Null package name or gms related package.  Ignoreing.
,D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
,D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
W/ResourcesManager( 5556): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
,D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
,D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 2073): hw_config_cback state=6
D/LGBluetoothProfileConnectionReceiver_EasySetting( 5556): [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information EasySettings
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/AuthorizationBluetoothService( 1749): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
,D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
W/ActivityManager(  848): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
,D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
,D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
,D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
E/Gmail   ( 5478): Error finding the version of the Email provider.....
E/Gmail   ( 5478): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5478): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5478): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5478): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5478): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5478): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5478): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5478): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
W/EmailMigration( 5478): We do not support migrating this version of the Email provider.
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
,D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
,D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
,D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
I/Gmail   ( 5478): getAccountsCursor
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
,D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
,D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
,I/ActivityManager(  848): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=5596 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
,D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
,D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
,D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
I/ActivityManager(  848): Killing 5298:com.lge.appbox.client/u0a11 (adj 15): empty #11
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
,D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
,D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
,D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2073): hw_config_cback state=6
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc4e
D/bt_hwcfg( 2073): hw_config_cback state=6
W/ActivityManager(  848): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/libprocessgroup(  848): failed to open /acct/uid_10011/pid_5298/cgroup.procs: No such file or directory
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5478): Observing account changes for notifications
,W/ActivityManager(  848): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,W/art     ( 5437): Suspending all threads took: 23.528ms
,W/ResourcesManager( 5596): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/bt_hwcfg( 2073): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 2073): Settlement delay -- 100 ms
I/bt_hwcfg( 2073): Setting fw settlement delay to 100 
,D/NativeLibraryUtils( 5437): Install completed successfully. count=14 extracted=0
,I/Icing   ( 5437): Storage manager: low false usage 1.71MB avail 2.38GB capacity 4.06GB
,D/BluetoothManagerService(  848): Message: 20
D/BluetoothManagerService(  848): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2a45fc2d:true
,D/BluetoothAdapterService(1072279366)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@28ecf7cc
D/BluetoothAdapterService(1072279366)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@28ecf7cc
I/Gmail   ( 5478): notifyAccountChanged
,I/art     ( 5437): CheckpointMarkThreadRoots callback created = 0xaaf18be0
I/Gmail   ( 5478): getAccountsCursor
I/Gmail   ( 5478): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5478): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc45
D/bt_hwcfg( 2073): hw_config_cback state=2
D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc18
D/bt_hwcfg( 2073): hw_config_cback state=7
I/bt_hwcfg( 2073): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 2073): Setting local bd addr to F8:95:C7:87:85:54
I/art     ( 5437): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5437): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/Gmail   ( 5478): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5478): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/art     ( 5437): CheckpointMarkThreadRoots callback created = 0xb056cab0
,D/bt_hwcfg( 2073): hw_config_cback opcode:0xfc01
D/bt_hwcfg( 2073): hw_config_cback state=8
I/bt_hwcfg( 2073): vendor lib fwcfg completed
I/bt-btif ( 2073): HC preload_cb 0 [0:SUCCESS 1:FAIL]
I/bt-btu  ( 2073): btu_task received preload complete event
I/        ( 2073): BTE_InitTraceLevels -- TRC_HCI,2
I/        ( 2073): BTE_InitTraceLevels -- TRC_L2CAP,2
I/        ( 2073): BTE_InitTraceLevels -- TRC_RFCOMM,2
I/        ( 2073): BTE_InitTraceLevels -- TRC_OBEX,2
I/        ( 2073): BTE_InitTraceLevels -- TRC_AVCT,2
I/        ( 2073): BTE_InitTraceLevels -- TRC_AVDT,2
I/        ( 2073): BTE_InitTraceLevels -- TRC_AVRC,2
I/        ( 2073): BTE_InitTraceLevels -- TRC_AVDT_SCB,2
I/        ( 2073): BTE_InitTraceLevels -- TRC_A2D,2
I/        ( 2073): BTE_InitTraceLevels -- TRC_BNEP,2
I/        ( 2073): BTE_InitTraceLevels -- TRC_BTM,2
I/        ( 2073): BTE_InitTraceLevels -- TRC_GAP,2
I/        ( 2073): BTE_InitTraceLevels -- TRC_PAN,2
I/        ( 2073): BTE_InitTraceLevels -- TRC_SAP,2
I/        ( 2073): BTE_InitTraceLevels -- TRC_SDP,2
I/        ( 2073): BTE_InitTraceLevels -- TRC_GATT,2
I/        ( 2073): BTE_InitTraceLevels -- TRC_SMP,2
I/        ( 2073): BTE_InitTraceLevels -- TRC_BTAPP,3
I/        ( 2073): BTE_InitTraceLevels -- TRC_BTIF,3
I/        ( 2073): BTE_InitTraceLevels -- TRC_PROTOCOL,0
,I/ActivityManager(  848): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5629 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/LGMDMManager( 5596): Create singleton instance
,I/Gmail   ( 5478): getAccountsCursor
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/bt-btif ( 2073): bta_dm_ctrl_features_rd_cmpl_cback Ctrl BLE feature read failed: status :1
,I/GKI_LINUX( 2073): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 2073): warning : media task started media_task_refcnt 1 
E/bt-btif ( 2073): Calling BTA_HhEnable
W/bt-smp  ( 2073): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 2073): Plain text(LSB ~ MSB) = 96 f4 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2073): Encrypted text(LSB ~ MSB) = 70 33 61 71 e6 31 de cb 86 65 a0 d5 fd b7 e8 a2 
W/bt-btm  ( 2073): Stopping oneshot timer
E/bt-btif ( 2073): btif_storage_get_adapter_property service_mask:0x1201c8
I/bt-btif ( 2073): HAL bt_hal_cbacks->adapter_properties_cb
D/BT_PROF_AUDIO( 2073): created moving average (N=100)
D/BT_PROF_AUDIO( 2073): reset rate average
W/bt-btif ( 2073): overflow 0, enter 0, exit 0
D/BluetoothAdapterProperties( 2073): Address is:F8:95:C7:87:85:54
D/BluetoothManagerService(  848): Bluetooth Adapter name changed to G3s-1
D/BluetoothManagerService(  848): Stored Bluetooth name: G3s-1
D/BluetoothAdapterProperties( 2073): Name is: G3s-1
D/BluetoothAdapterProperties( 2073): Scan Mode:20
D/BluetoothAdapterProperties( 2073): Discoverable Timeout:120
E/bt-btif ( 2073): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 2073): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
E/bt-btif ( 2073): btif_sock_init: !radio_req && !rfc_init
I/bt-btif ( 2073): BTA_JvEnable
D/UEI.SmartControl( 5629): Quickset Services start...
E/bt-btif ( 2073): btsock_vendor_hci_init: !vhci_init
D/bt-btif ( 2073): btsock_ctrl_hci_init(L191): poll handle:6
D/bt-btif ( 2073): init_hci_slots(L136): in
D/IOP_DB_BT( 2073): db_open: file /etc/bluetooth/iop_bt.db
I/AudioManager( 5596): getMode name:com.lge.qremote
,D/IOP_DB_BT( 2073): db_open: db_open : handle 2691475420l, read 11046 bytes onto local cache
D/IOP_DB_BT( 2073): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 2073): db_query: result 1
I/        ( 2073): iop_db_open: iop_db_open status 0
E/bt-btif ( 2073): btif_sock_init, radio_req:0, rfc_init:1, vhci_init:1
D/bt-btif ( 2073): btsock_ctrl_hci_init(L191): poll handle:6
I/bt-btif ( 2073): bta_pan_co_init
D/bte_conf( 2073): Device ID record 1 : primary
D/bte_conf( 2073):   vendorId            = 00c4
D/bte_conf( 2073):   vendorIdSource      = 0001
D/bte_conf( 2073):   product             = 13a1
D/bte_conf( 2073):   version             = 1000
D/bte_conf( 2073):   clientExecutableURL = 
D/bte_conf( 2073):   serviceDescription  = 
D/bte_conf( 2073):   documentationURL    = 
D/bte_conf( 2073): bte_load_did_conf no section named DID2.
I/bt-btif ( 2073): HAL bt_hal_cbacks->adapter_state_changed_cb
E/bt-btif ( 2073): btif_hf_upstreams_evt: wrong handle = 8240 
I/bt-btif ( 2073): HAL bt_op_callbacks->opc_state_cb
D/BluetoothOPPServiceJni( 2073): opc_state_cb(L140):  opc_state_cb state:0
D/OppService( 2073): onOpcStateChange()
I/bt-btif ( 2073): HAL bt_op_callbacks->ops_state_cb
D/BluetoothOPPServiceJni( 2073): ops_state_cb(L223):  ops_state_cb state:0
D/BluetoothAdapterState( 2073): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/OppService( 2073): Recieved MESSAGE_OPC_ENABLE
D/BluetoothAdapterProperties( 2073): ScanMode =  20
D/BluetoothAdapterProperties( 2073): State =  11
D/BluetoothAdapterProperties( 2073): mDiscoverableTimeout = 120
D/BluetoothAdapterProperties( 2073): Setting state to 12
,I/BluetoothAdapterState( 2073): Bluetooth adapter state changed: 11-> 12
D/LGBluetoothFeatureConfig( 2073): isPrivacyLogsEnabled : true
D/BluetoothAdapterService(1072279366)( 2073): updateAdapterState() - Broadcasting state to 1 receivers.
D/BluetoothManagerService(  848): Message: 60
D/BluetoothManagerService(  848): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
I/BluetoothAdapterState( 2073): Entering On State
D/BluetoothManagerService(  848): Broadcasting onBluetoothStateChange(true) to 6 receivers.
I/BluetoothAdapterState( 2073): Entering On State from state = 11
D/BluetoothAdapterService(1072279366)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@28ecf7cc
D/BluetoothA2dp( 2073): onBluetoothStateChange: up=true
D/BluetoothAdapterService(1072279366)( 2073): isQuetModeEnabled() - Enabled = false
D/BluetoothAdapterService(1072279366)( 2073): autoConnect() - Initiate auto connection on BT on...
D/BluetoothAdapterService( 2073): [BTUI] autoConnect() : not allowed
D/BluetoothHeadset( 1782): onBluetoothStateChange: up=true
D/LGBluetoothServiceAdapter( 2073): [BTUI] OnState
D/BluetoothHeadset( 1782): onBluetoothStateChange: up=true
D/LGBluetoothServiceAdapter( 2073): [BTUI]         global_name: G3s-1
D/LGBluetoothServiceAdapter( 2073): [BTUI]         local_name: G3s-1
D/BluetoothHeadset(  848): onBluetoothStateChange: up=true
D/OppService( 2073): onOpsStateChange() :0
D/BluetoothA2dp(  848): onBluetoothStateChange: up=true
I/bt-btif ( 2073): HAL bt_fts_callbacks->operation_cmpl_cb
D/BluetoothFTPServiceJni( 2073): operation_cmpl_callback(L192):  oper:3 status:0
D/OppService( 2073): Recieved MESSAGE_OPS_ENABLE
I/BluetoothFTPService( 2073): onFtpServerEnabled: /storage
D/BluetoothAdapterService(1072279366)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@28ecf7cc
D/BluetoothAdapterService(1072279366)( 2073): isQuetModeEnabled() - Enabled = false
D/BluetoothHeadset( 1782): onBluetoothStateChange: up=true
D/BluetoothAdapterService(1072279366)( 2073): autoConnect() - Initiate auto connection on BT on...
D/BluetoothAdapterService( 2073): [BTUI] autoConnect() : not allowed
D/BluetoothPanServiceJni( 2073): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
I/bt-btif ( 2073): HAL bt_hal_cbacks->adapter_properties_cb
,E/BluetoothManagerService(  848): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
D/BluetoothManagerService(  848): Bluetooth State Change Intent: 11 -> 12
D/BluetoothAdapterProperties( 2073): Scan Mode:21
I/bt-btif ( 2073): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 2073): Discoverable Timeout:120
D/BluetoothManagerService(  848): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  848): Message: 40
D/BluetoothManagerService(  848): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothAdapterService(1072279366)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@28ecf7cc
D/BluetoothAdapterService(1072279366)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@28ecf7cc
,D/LGBluetoothAPIService( 1872): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/bt_h4   ( 2073): vendor lib postload completed
I/[SystemUI]QuickSettingsHandler( 1361): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1361): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
D/BluetoothAdapterService(1072279366)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@28ecf7cc
I/UEI.SmartControl( 5629): Manufacture = LGE
D/UEI.SmartControl( 5629): File observer start...
E/UEI.SmartControl( 5629): IR Port is disabled: false
D/UEI.SmartControl( 5629): Starting file observer...
D/UEI.SmartControl( 5629): Extracting JNI libs...
,D/UEI.SmartControl( 5629): --- this system supports 32-bit or 64-bit only
D/LGBluetoothAPIService( 1872): Message: 1
D/LGBluetoothAPIService( 1872): MESSAGE_BOOT_COMPLETED
I/BluetoothMapService( 2073): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 2073): STATE_ON
I/LGBluetoothAPIService( 1872): [BTUI] LGBluetoothAPIService Binding Success
W/ContextImpl( 5452): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,D/BluetoothAdapterService( 2073): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3fe9af46
,V/BluetoothPbapService( 2073): Pbap Service onCreate
V/BluetoothPbapService( 2073): Starting PBAP service
D/BluetoothAdapterService(1072279366)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@28ecf7cc
D/LGBluetoothPbapAdapter( 2073): [BTUI] getInstance : create
V/BluetoothPbapService( 2073): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 2073): state: 12
V/BluetoothMapService( 2073): Handler(): got msg=1
D/BluetoothMapMasInstance( 2073): Map Service startRfcommSocketListener
V/BluetoothOppNotification( 2073): new notify threadi!
V/BluetoothOppNotification( 2073): send delay message
D/BluetoothMapMasInstance( 2073): MAS initSocket()
D/BluetoothMapMasInstance( 2073):   masId = 00
D/BluetoothMapMasInstance( 2073):   msgTypes = 0e
D/BluetoothMapMasInstance( 2073):   masName = SMS/MMS
D/BluetoothMapMasInstance( 2073):   SDP string = 000eSMS/MMS
D/LGBluetoothAPIServer( 2073): [BTUI] onCreate()
D/LGBluetoothAPIServer( 2073): [BTUI] onBind()
D/LGBluetoothAPIService( 1872): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
V/BluetoothPbapReceiver( 2073): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 2073): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1872): Message: 100
V/BluetoothPbapReceiver( 2073): ***********state = 12
D/LGBluetoothAPIService( 1872): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,V/BluetoothPbapService( 2073): Handler(): got msg=1
D/BluetoothAdapterService(1072279366)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@28ecf7cc
V/BluetoothOppProvider( 2073): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BluetoothPbapService( 2073): Pbap Service startRfcommSocketListener
V/BluetoothOppProvider( 2073): created cursor android.database.sqlite.SQLiteCursor@28d2af19 on behalf of 
D/BluetoothManagerService(  848): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothPbapService( 2073): Pbap Service initSocket
D/BluetoothManagerService(  848): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LocalBluetoothProfileManager( 5452): Adding local A2DP profile
W/BluetoothAdapter( 2073): getBluetoothService() called with no BluetoothManagerCallback
W/BluetoothAdapter( 2073): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 2073): BTA_JvCreateRecordByUser
I/bt-btif ( 2073): BTA_JvCreateRecordByUser
I/bt-btif ( 2073): BTA_JvRfcommStartServer
I/bt-btif ( 2073): BTA_JvRfcommStartServer
D/LGBluetoothServiceAdapter( 2073): [BTUI] createSocketChannel FD=84 mFd=0
D/LGBluetoothServiceAdapter( 2073): [BTUI] createSocketChannel FD=86 mFd=84
V/BluetoothMapMasInstance( 2073): Succeed to create listening socket 
V/BluetoothPbapService( 2073): Succeed to create listening socket 
V/BluetoothPbapService( 2073): Accepting socket connection...
D/BluetoothMapMasInstance( 2073): Accepting socket connection...
,V/BluetoothOppNotification( 2073): mUpdateCompleteNotification = true
D/BluetoothManagerService(  848): Message: 30
V/BluetoothOppProvider( 2073): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 2073): created cursor android.database.sqlite.SQLiteCursor@19645bde on behalf of 
,D/LocalBluetoothProfileManager( 5452): Adding local HEADSET profile
V/BluetoothOppNotification( 2073): outbound: succ-0  fail-0
I/NotificationManager( 2073): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
V/BluetoothOppNotification( 2073): outbound notification was removed.
V/BluetoothOppProvider( 2073): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
D/BluetoothManagerService(  848): Message: 30
V/BluetoothOppProvider( 2073): created cursor android.database.sqlite.SQLiteCursor@f6cf1bf on behalf of 
,V/BluetoothOppNotification( 2073): inbound: succ-0  fail-0
D/BluetoothManagerService(  848): Message: 30
I/NotificationManager( 2073): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
V/BluetoothOppNotification( 2073): inbound notification was removed.
V/BluetoothOppProvider( 2073): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 2073): created cursor android.database.sqlite.SQLiteCursor@3bc5508c on behalf of 
,I/ActivityManager(  848): Process com.google.android.apps.plus (pid 5386) has died
,I/art     (  848): Explicit concurrent mark sweep GC freed 26507(1334KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/34MB, paused 2.254ms total 163.999ms
,D/BluetoothManagerService(  848): Message: 30
D/LocalBluetoothProfileManager( 5452): Adding local MAP profile
D/BluetoothMap( 5452): Create BluetoothMap proxy object
D/BluetoothManagerService(  848): Message: 30
,D/BluetoothManagerService(  848): Message: 30
V/BluetoothPbapService( 2073): Pbap Service onBind
D/LocalBluetoothProfileManager( 5452): LocalBluetoothProfileManager construction complete
D/CAR.SERVICE( 5212): mConnectedToCar = false, abort
D/LGBluetoothUserBindClient( 5452): [BTUI] initUserBindClient
,W/ContextImpl( 5452): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 5452): finishStartingService: stopping service
E/ActivityThread( 5212): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@13fe2673 that was originally bound here
E/ActivityThread( 5212): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@13fe2673 that was originally bound here
E/ActivityThread( 5212): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5212): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5212): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5212): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5212): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5212): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5212): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5212): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5212): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5212): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 5212): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 5212): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 5212): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 5212): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 5212): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 5212): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 5212): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5212): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5212): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5212): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5212): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5212): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5212): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,D/BluetoothA2dp( 5452): Proxy object connected
D/A2dpProfile( 5452): Bluetooth service connected
D/BluetoothAdapterService(1072279366)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@28ecf7cc
D/BluetoothHeadset( 5452): Proxy object connected
D/HeadsetProfile( 5452): Bluetooth service connected
D/BluetoothAdapterService(1072279366)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@28ecf7cc
,E/MDM     ( 1749): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/BluetoothInputDevice( 5452): Proxy object connected
D/HidProfile( 5452): Bluetooth service connected
D/BluetoothAdapterService(1072279366)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@28ecf7cc
E/ActivityThread( 5212): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1fea6c3a that was originally bound here
E/ActivityThread( 5212): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1fea6c3a that was originally bound here
E/ActivityThread( 5212): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5212): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5212): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5212): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5212): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5212): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5212): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5212): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 5212): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 5212): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 5212): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 5212): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 5212): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 5212): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 5212): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 5212): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5212): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5212): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5212): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5212): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5212): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5212): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  848): Unbind failed: could not find connection for android.os.BinderProxy@f0be817
D/BluetoothPan( 5452): BluetoothPAN Proxy object connected
D/PanProfile( 5452): Bluetooth service connected
D/BluetoothAdapterService(1072279366)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@28ecf7cc
D/BluetoothMap( 5452): Proxy object connected
D/MapProfile( 5452): Bluetooth service connected
D/BluetoothMap( 5452): getConnectedDevices()
D/BluetoothAdapterService(1072279366)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@28ecf7cc
V/BluetoothMapService( 2073): getConnectedDevices()
D/BluetoothPbap( 5452): Proxy object connected
D/PbapServerProfile( 5452): Bluetooth service connected
,D/LGBluetoothUserBindClient( 5452): [BTUI] onServiceConnected
I/Netd    (  271): M: Get netlink event, ifname: p2p0 action: 6
I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 5434): Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2437 MHz)
D/BluetoothPermissionRequest( 5452): onReceive
D/libc-netbsd(  848): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  848): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LGBluetoothFeatureConfig( 5452): isPrivacyLogsEnabled : true
,D/LGBluetoothUtils( 5452): [BTUI] FileNotFound: readProperty
V/BluetoothOppReceiver( 2073): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
V/BluetoothOppManager( 2073): restoreApplicationData! falsefalsenullnull
,V/BluetoothSapReceiver( 2073): [BTUI] checkServiceStart
D/LGBluetoothStateChangeReceiver( 2073): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
,D/AuthorizationBluetoothService( 1749): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/LocSvc_java(  848): onReceive
I/[SystemUI]StatusBar.NetworkController( 1361): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1908): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  848): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  848): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  848): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt(  848): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  848): setSupplicantStateASSOCIATING
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1361): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1908): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-03-02 09:54:35.378 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]QuickSettingsHandler( 1361): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1361): Remote
I/QCNEJ   ( 1908): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 5434): wlan0: Associated with f4:f2:6d:22:99:3e
I/QCNEJ   ( 1908): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,W/Settings(  848): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  848): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  848): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/[SystemUI]StatusBar.NetworkController( 1361): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1908): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-03-02 09:54:35.427 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1908): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/Icing   ( 5437): updateResources: need to parse f{com.google.android.gms}
I/QCNEJ   ( 1908): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  848): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  848): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/WifiOffDelayIfNotUsed(  848): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/WifiServerServiceExt(  848): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  848): setSupplicantStateFOUR_WAY_HANDSHAKE
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1361): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1361): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1361): Remote
I/QCNEJ   ( 1908): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-03-02 09:54:35.432 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1908): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1361): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1361): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1361): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1361): Remote
I/art     ( 1749): Explicit concurrent mark sweep GC freed 30289(1930KB) AllocSpace objects, 19(304KB) LOS objects, 39% free, 13MB/22MB, paused 20.511ms total 159.958ms
,D/UEI.SmartControl( 5629): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5629): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5629): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/wpa_supplicant( 5434): wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 5434): wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 4
I/WifiServiceExtension(  848): setVHTCapabilityType  : false
,D/LocationInitializer( 5437): Restart initialization of location
,I/UEI.SmartControl( 5629): --- Selecting new region: 2
,D/AuthorizationBluetoothService( 1749): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/WifiServerServiceExt(  848): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/UEI.SmartControl( 5629): -- Running on KitKat(19) and above! JNI will be used.
I/WifiServerServiceExt(  848): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  848): setSecurityType  : 2
D/UEI.SmartControl( 5629): Platform has CIR...
,D/UEI.SmartControl( 5629): NO CIR support, need to check package...
V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[SystemUI]StatusBar.NetworkController( 1361): mWifiConnected = false, mWifiLevel = 0
W/Settings(  848): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  848): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  848): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1908): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1908): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-03-02 09:54:35.521 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1908): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1908): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1908): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-03-02 09:54:35.523 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1908): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  848): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  848): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  848): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/UEI.SmartControl( 5629): Model: LG-D722 uses JNI
I/NotificationManager( 1749): com.google.android.gms: cancel(0) by com.google.android.gms
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1361): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1361): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1361): Remote
I/[SystemUI]StatusBar.NetworkController( 1361): mWifiConnected = false, mWifiLevel = 0
,D/UEI.SmartControl( 5629): QS Service created
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1361): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1361): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1361): Remote
I/AudioManager( 5596): getMode name:com.lge.qremote
,E/UEI.SmartControl( 5629): QS start get config
,W/GCoreFlp( 1749): No location to return for getLastLocation()
W/FusedLocationProvider( 1749): location=null
D/ConnectivityService(  848): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/WifiExtManager(  848): WifiExtManager service = com.lge.wifi.impl.IWifiExtManager$Stub$Proxy@347eeaa3
D/ConnectivityService(  848): Got NetworkAgent Messenger
,D/ConnectivityService(  848): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  848): NetworkAgent connected
,D/WifiServiceExtension( 1872): isInternetCheckAvailable return false
E/WifiConfigStore(  848): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  848): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/Finsky  ( 5089): [600] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
V/WiFiOffLoadBroadcast( 5452): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 9
,D/libc-netbsd(  848): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  848): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  848): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  848): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  271): Setting iface cfg
E/WifiStateMachine(  848): Start Dhcp Watchdog 1
D/UEI.SmartControl( 5629): Loading JNI Libs...
D/WifiServerServiceExt(  848): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  848): setSupplicantStateGROUP_HANDSHAKE
,D/UEI.SmartControl( 5629):  configuring local db...
D/DhcpStateMachine(  848): StoppedState
D/DhcpStateMachine(  848): StoppedState{ when=-4ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  848): WaitBeforeStartState
I/QCNEJ   ( 1908): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1908): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-47 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-03-02 09:54:35.678 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
D/WifiServerServiceExt(  848): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  848): setSupplicantStateCOMPLETED
D/ConnectivityService(  848): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,D/WifiServerServiceExt(  848): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  848): setSupplicantStateCOMPLETED
W/IcingInternalCorpora( 5437): getNumBytesRead when not calculated.
,D/WiFiOffLoadUpdatePriority( 5452): remove : truetruetrue
V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  848): android: cancelAsUser(2) by android
,E/WifiStateMachine(  848): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
D/LGWifiP2pService(  848): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2caf10b target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  848): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2caf10b target=com.android.internal.util.StateMachine$SmHandler }
V/DhcpStateMachine(  848): Current State is mWaitBeforeStartState.
D/DhcpStateMachine(  848): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  848): DHCP Start wake lock is acquired.
V/LgDhcpStateMachineHelper(  848): [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
V/LgDhcpStateMachineHelper(  848): [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700" is not exist.
D/WiFiOffLoadUpdatePriority( 5452): remove1
V/WiFiOffLoadSharedPrefsUtils( 5452): save remove
,D/WiFiOffLoadBroadcast( 5452): mLastConnectedNetwork from SharedPrefsUtils for wifioffloading : null
D/WiFiOffLoadBroadcast( 5452): S: false, R: false
,D/WiFiOffLoadUpdatePriority( 5452): saved SSID: "NG700"
D/WiFiOffLoadUpdatePriority( 5452): connected SSID: null
D/WiFiOffLoadUpdatePriority( 5452): private wpa: "NG700" 300
D/WifiServiceImplEx(  848): addOrUpdateNetwork pid=5452, uid=1000, packageName=android.uid.system:1000
E/addOrUpdateNetwork(  848):  uid = 1000 SSID "NG700" nid=0
E/WifiConfigStore(  848):  key="NG700"WPA_PSK netId=0 uid=0/1000
,I/Icing   ( 5437): Internal init done: storage state 0
I/NotificationManager( 5437): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/Icing   ( 5437): Post-init done
I/Icing   ( 5437): updateResources: need to parse f{com.google.android.gms}
E/WifiConfigStore(  848): Setting BSSID for "NG700"WPA_PSK to any
,D/libc-netbsd( 5089): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5089): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5089): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5089): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  271): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
I/WifiServerServiceExt(  848): set CMD_UPDATE_DEFAULT_PROFILE
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/WiFiOffLoadUpdatePriority( 5452):  ssid "NG700" prio 300
D/WiFiOffLoadUpdatePriority( 5452): configuration updated: 0
D/DSQN    (  848): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/WiFiOffLoadUpdatePriority( 5452): configuration saved: true
,I/ActivityManager(  848): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5686 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/art     (  299): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 21.002ms
,D/UEI.SmartControl( 5629):  ---- Has DB8: true
D/UEI.SmartControl( 5629): QS start statue = true Error code = 0
,D/UEI.SmartControl( 5629): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5629): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5629): IRRCDataComm has AudioManager!!!!.
I/art     (  299): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 20.985ms
W/irrc_jni( 5629): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5629): IrrcClient ++ 
D/irrcClient( 5629): getIrrcService ++ 
,D/irrcClient( 5629): getIrrcService -- 
D/irrcClient( 5629): IrrcClient -- 
W/irrc_jni( 5629): IRRCPlayer_nativeInit -- 
D/DhcpStateMachine(  848): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper(  848): [bssid] hash key :f4:f2:6d:22:99:3e
D/LgDhcpStateMachineHelper(  848): dhcp.ap.macaddress = f4:f2:6d:22:99:3e
D/UEI.SmartControl( 5629): Services init done
I/art     (  299): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 337us total 23.898ms
,I/UEI.SmartControl( 5629): Device manager: loading config....
D/UEI.SmartControl( 5629): QS Service init finished
I/dhcpcd  ( 5696): version 5.5.6 starting
D/UEI.SmartControl( 5629): QS Service version name: 0.1.73
,E/dhcpcd  ( 5696): get_duid: Read-only file system
D/UEI.SmartControl( 5629): Config is loaded...
D/UEI.SmartControl( 5629): QS Service version code: 1073
D/UEI.SmartControl( 5629): Service requested: Control
D/UEI.SmartControl( 5629): Internal service binding...
,D/UEI.SmartControl( 5629): -----IControl: 11
D/UEI.SmartControl( 5629): Caller: com.lge.qremote
D/UEI.SmartControl( 5629): ------------ IControl registerCallback...
I/UEI.SmartControl( 5629): Registering callback...
D/UEI.SmartControl( 5629): -----IControl: 19
D/UEI.SmartControl( 5629): Caller: com.lge.qremote
I/UEI.SmartControl( 5629): Registering Services Ready callback...
I/UEI.SmartControl( 5629): Notify client services are ready...
,D/UEI.SmartControl( 5629): -----IControl: 8
D/UEI.SmartControl( 5629): Caller: com.lge.qremote
I/ActivityManager(  848): Killing 5342:com.android.contacts/u0a18 (adj 15): empty #11
D/UEI.SmartControl( 5629):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 5629): Notify AllClients services are ready: 0
I/dhcpcd  ( 5696): wlan0: rebinding lease of 192.168.1.114
,W/libprocessgroup(  848): failed to open /acct/uid_10018/pid_5342/cgroup.procs: No such file or directory
D/PCSuite ( 5686): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/ActivityManager(  848): Killing 5366:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
I/dhcpcd  ( 5696): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
I/dhcpcd  ( 5696): wlan0: leased 192.168.1.114 for 172800 seconds
I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  848): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  848): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  848): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
W/libprocessgroup(  848): failed to open /acct/uid_10069/pid_5366/cgroup.procs: No such file or directory
,D/UsbSettingsReceiver( 5452): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 5452): [AUTORUN] sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 5452): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 5452): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 5452): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 5452): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 5452): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 5452): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 5452): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 5452): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 5452): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 5452): [AUTORUN] setTetherStatus() : status=false
V/WiFiOffLoadBroadcast( 5452): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/WiFiOffLoadBroadcast( 5452): MCCMNC not supported: null
D/PCSuite ( 5686): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  848): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=5733 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,V/AudioFlinger(  275): thread 0xb5735000 type 0 TID 1289 going to sleep
,V/AudioFlinger(  275): thread 0xb56eb000 type 0 TID 1287 going to sleep
V/AudioFlinger(  275): thread 0xb5651000 type 0 TID 1285 going to sleep
D/libc-netbsd(  848): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  848): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  848): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  848): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  848): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  848): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  848): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  848): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  848): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  848): CheckDhcpDirectory [Lease File Count] : 4
V/LgDhcpStateMachineHelper(  848): [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
D/libc-netbsd(  848): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  848): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  848): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.114
V/LgDhcpStateMachineHelper(  848): Add DhcpResults: IP address 192.168.1.114/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
V/DhcpStateMachine(  848): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  848): bShouldSendDhcpAction Result: true
D/DhcpStateMachine(  848): DHCP Start/Renew wake lock is released.
D/LGWifiP2pService(  848): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  848): RunningState
D/LGWifiP2pService(  848): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  848): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,E/WifiStateMachine(  848): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  848): ignoring duplicate network state non-change
W/Settings(  848): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  848): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  848): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1908): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServiceExtension( 1872): isInternetCheckAvailable return false
D/ConnectivityService(  848): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/[SystemUI]StatusBar.NetworkController( 1361): mWifiConnected = false, mWifiLevel = 0
D/WifiServiceExtension( 1872): isInternetCheckAvailable return false
D/ConnectivityService(  848): Adding iface wlan0 to network 100
,W/Settings(  848): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  848): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  848): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1361): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1361): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1361): Remote
E/WifiStateMachine(  848): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/[SystemUI]StatusBar.NetworkController( 1361): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20(  848): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  848): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  848): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  848): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  848): [PASSPOINT] passpointNotification: hs20AP list is checked
,I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1361): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1361): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1361): Remote
I/QCNEJ   ( 1908): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-47 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.114 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-03-02 09:54:36.435 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1908): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.114 ipV6Addr=
I/QCNEJ   ( 1908): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1908): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-47 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.114 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-03-02 09:54:36.438 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1908): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.114 ipV6Addr=
I/QCNEJ   ( 1908): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1908): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-47 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.114 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-03-02 09:54:36.441 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1908): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.114 ipV6Addr=
W/Settings(  848): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  848): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  848): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/QCNEJ   ( 1908): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1908): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-47 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.114 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-03-02 09:54:36.444 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1908): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.114 ipV6Addr=
D/LGDMClient( 5733): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 5733): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 5733): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 5733): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
I/[SystemUI]StatusBar.NetworkController( 1361): mWifiConnected = true, mWifiLevel = 3
V/WiFiOffLoadBroadcast( 5452): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/ConnectivityService(  848): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  848): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WiFiOffLoadBroadcast( 5452): MCCMNC not supported: null
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  848): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  848): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/ConnectivityService(  848): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  848): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService(  848): Setting Dns servers for network 100 to [/192.168.1.1]
D/libc-netbsd(  848): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  848): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/PCSuite ( 5686): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/Nat464Xlat(  848): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  848): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  848): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  848): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  848):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  848): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  848): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  848): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  848):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  848):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
,D/ConnectivityService(  848):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  848):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  848): currentScore = 0, newScore = 20
D/ConnectivityService(  848):    accepting network in place of null
D/ConnectivityService(  848): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  848): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  848):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/LGDMClient( 5733): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/ConnectivityService(  848): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
I/[SystemUI]QuickSettingsHandler( 1361): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1361): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1361): Remote
I/[SystemUI]StatusBar.NetworkController( 1361): mWifiConnected = true, mWifiLevel = 3
,D/TelephonyNetworkFactory-1( 1782): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1782):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/LGDMClient( 5733): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_0_fully mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1361): Got action android.net.wifi.STATE_CHANGE at null
E/ConnectivityService(  848): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  848): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
I/[SystemUI]QuickSettingsHandler( 1361): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1361): Remote
D/PCSuite ( 5686): [StartReceiver][getUpdateNecessity]update = false
D/ConnectivityService(  848): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/PCSuite ( 5686): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/Tethering(  848): MasterInitialState.processMessage what=3
D/libc-netbsd(  848): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  848): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  848): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  848): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  271): App 1000 tries DNS query. Accept family:0 protocol:0
W/QCNEJ   ( 1908): |CORE| No family connected
I/QCNEJ   ( 1908): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=0
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
I/QCNEJ   ( 1908): |CORE| sendDefaultNwMsg: default = 1
,D/ConnectivityService(  848): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  848): [e] list.add(nai) empty : false size: 1
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/ConnectivityService(  848): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  848): [LWD] Start DNSResolver start to wait
D/DSQN    (  848): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/ConnectivityService(  848): validation of new default Network = false
D/ConnectivityService(  848): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  848): enableDataServiceNotify 
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  848): [LWD] wait 500ms before dns check
D/DSQN    (  848): start dsqn bin
,V/WiFiOffLoadBroadcast( 5452): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  848): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  848):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  848):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
V/NetworkPolicy(  848): [LG_RESTRICTED] checkMobilePolicy_type()
D/WiFiOffLoadBroadcast( 5452): MCCMNC not supported: null
D/LGDMClient( 5733): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,D/ConnectivityService(  848): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1361): CM callback handler got msg 524290
I/DSQN    ( 5779): DSQN samuel.seo ver 141203
I/LGDMClient( 5733): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
E/DSQN    ( 5779): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5779): created command queue thread
I/DSQN    ( 5779): Interface wlan0 address 192.168.1.114 0xc0a80172
I/DSQN    ( 5779): Interface wlan0 netmask 255.255.255.0 0xc0a80172
D/TelephonyIcons( 1361): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1361): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
W/ContextImpl( 5733): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
E/LGDMClient( 5733): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 5733): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 5733): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
E/MDM     ( 1749): [104] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
D/LGDMClient( 5733): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LocationInitializer( 5437): Restart initialization of location
D/AuthorizationBluetoothService( 1749): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LGDMClient( 5733): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  848): Killing 5212:com.google.android.gms:car/u0a6 (adj 15): empty #11
,W/libprocessgroup(  848): failed to open /acct/uid_10006/pid_5212/cgroup.procs: No such file or directory
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1749): com.google.android.gms: cancel(0) by com.google.android.gms
I/ActivityManager(  848): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=5787 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1749): No location to return for getLastLocation()
W/FusedLocationProvider( 1749): location=null
,W/ResourcesManager( 5787): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 5787): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 5787): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 5787): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@4b3e30f, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@3c606f9c, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@5b93da5, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@3345b57a, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2855a12b, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@15d2e988, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@35250f21, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@3fe9af46, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@b2507, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@14711634, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@9227c5d, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@328179d2, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@3eab0aa3, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@292361a0, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@2d8f8159, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@359611e, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@23d9adff, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@28ecf7cc, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@142dda15, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@1136712a, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@1b252b1b, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@13d7c4b8, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@f1f0291, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@302275f6, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@30e15df7, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1ea07464, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@172036cd, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@18f7fb82, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@38c3e293, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@2b2272d0, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@398672c9, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@5ae4dce, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@24014ef, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@1b83ebfc, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@29fa7285, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@66578da, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@36a3110b, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@2c21cbe8, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@33f4b201, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1b3248a6, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@3cefb2e7, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@3bbe94, l
D/GeneralP,referenceUtils( 5787): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 5787): [init]
I/Config  ( 5787): LGCalendar ver.4.40.17
I/Config  ( 5787): start check model
I/Config  ( 5787): start check native_ca
I/Config  ( 5787): Config Operator=OPEN, Country=EU
D/Config  ( 5787): [setDefaultValuesToPref]
D/Config  ( 5787): [parseProfiles]
D/ProfilesParser( 5787): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 5787): [debug_displayParseInfos] profile.operator = null
D/Config  ( 5787): [updateProfiletoCountryInfo]
D/GeneralPreference( 5787): [checkAndMigrateOldPreference]
D/AlertReceiver( 5787): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
I/InitNotificationRingtoneService( 5787): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 5787): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,I/AlertUtils( 5787): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 5787): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 5787): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 5787): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 5787): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 5787): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 5787): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 5787): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 5787): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 5787): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 5787): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 5787): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 5787): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 5787): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 5787): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 5787): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 5787): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 5787): set default noti to content://media/internal/audio/media/38
,I/InitNotificationRingtoneService( 5787): End InitializeAlertRingtoneService.onHandleIntent
W/HolidayIntentService( 5787): onHandleIntent
,D/HolidayDataLoader( 5787): readJsonAsset : holiday.json
D/AlertService( 5787): 0 Action = android.intent.action.PROVIDER_CHANGED
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  848): [LWD] DNSResolver start dns
D/libc-netbsd(  848): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  848): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  848): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=100; mark=0
D/libc-netbsd(  848): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  271): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=983140
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
E/AgendaWidgetManager( 5787): [updateWidgets] 
D/MonthWidgetProvider( 5787): [onReceive]
D/CalendarWidgetProvider( 5787): [onReceive]
D/CalendarWidgetProvider( 5787): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 5787): [onCreate] mContext.getPackageName() = com.android.calendar
,D/WeekWidgetProvider( 5787): [onReceive]
D/CalendarWidgetProvider( 5787): [onReceive]
D/CalendarWidgetProvider( 5787): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 5787): [onCreate] mContext.getPackageName() = com.android.calendar
I/Icing   ( 5437): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/ActivityManager(  848): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=5816 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,E/HolidayIntentService( 5787): onHandleIntent:holiday data empty
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
,I/System.out(  848): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  848): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  848): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  848): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  848): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Icing   ( 5437): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 5437): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/DSQN    ( 5779): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5779): restart monitoring
,D/LGDataListener(  271): argv[0]=dsqncommand
D/LGDataListener(  271): argv[1]=wlan0
D/LGDataListener(  271): argv[2]=1
D/LGDataListener(  271): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 5779): dsqn report finish
D/DSQN    (  848): DSQM DsqnNotification wlan0  1
D/DSQN    (  848): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  848): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 02 Mar 2016 08:54:36 GMT], X-Android-Received-Millis=[1456908877220], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1456908877175]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  848): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1872): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  848): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  848): Validated
D/ConnectivityService(  848): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  848): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  848):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  848):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  848):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  848): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  848): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  848):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiDataContinuityService(  848): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
D/ConnectivityService(  848):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  848): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  848): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  848): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
I/WifiServerServiceExt(  848): set CMD_CAPTIVE_CHECK_COMPLETED
D/WIFI    (  848): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  848):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1361): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1782): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory-1( 1782):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/TelephonyIcons( 1361): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1361): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
V/[BNRBootReceiver]( 5816): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/BNRAndroBeam( 5816): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
V/[BNRBootReceiver]( 5816): Boot Receiver Return
,W/MainApplication( 5816): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
V/WiFiOffLoadBroadcast( 5452): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 5452): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5452): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 5452): Not supported operator for automatic switch
I/AudioManager( 5596): getMode name:com.lge.qremote
,V/WiFiOffLoadBroadcast( 5452): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 5452): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 5452): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5452): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5452): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5452): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5452): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5452): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5452): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5452): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5452): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5452): MCCMNC not supported: null
I/AudioManager( 5596): getMode name:com.lge.qremote
,I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/WiFiOffLoadBroadcast( 5452): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 5452): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 5452): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5452): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5452): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5452): MCCMNC not supported: null
I/PCSuite ( 5686): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 5686): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 5452): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 5452): MCCMNC not supported: null
I/PCSuite ( 5686): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 5686): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  848): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
I/AudioManager( 5596): getMode name:com.lge.qremote
D/libc-netbsd(  848): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  848): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=true
D/ConnectivityService(  848): identical MTU - not setting
D/Nat464Xlat(  848): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  848): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  848):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  848):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  848): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  848): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  848): enableDataServiceNotify 
D/DSQN    (  848): start dsqn bin
D/ConnectivityManager.CallbackHandler( 1361): CM callback handler got msg 524295
I/QCNEJ   ( 1908): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1908): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-47 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.114 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-03-02 09:54:37.534 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/AudioManager( 5596): getMode name:com.lge.qremote
,I/AudioManager( 5596): getMode name:com.lge.qremote
I/AudioManager( 5596): getMode name:com.lge.qremote
I/ActivityManager(  848): Killing 5408:com.android.providers.calendar/u0a14 (adj 15): empty #11
D/DSQN    (  848): dsqn is running restart
I/jxcore-log( 4586): My device name is: LGE-LG-D722
I/jxcore-log( 4586): 
I/DSQN    ( 5846): DSQN samuel.seo ver 141203
E/DSQN    ( 5846): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5846): created command queue thread
I/DSQN    ( 5846): Interface wlan0 address 192.168.1.114 0xc0a80172
,I/DSQN    ( 5846): Interface wlan0 netmask 255.255.255.0 0xc0a80172
W/libprocessgroup(  848): failed to open /acct/uid_10014/pid_5408/cgroup.procs: No such file or directory
,V/AlarmManager(  848): ELAPSED_WAKEUP set : Alarm{303dd0eb type 2 when 87156 com.android.providers.calendar} when 87156
,I/ActivityManager(  848): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5856 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 5856): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 5856): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@2a28cbe9
,D/CalendarProvider2( 5856): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 5856): Created com.android.providers.calendar.CalendarAlarmManager@3345b57a(com.android.providers.calendar.CalendarProvider2@2a28cbe9)
D/CalendarProviderBroadcastReceiver( 5856): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 5856): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 5856): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 5856): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 5856): [getOrCreateCalendarAlarmManager]
I/ActivityManager(  848): Killing 5556:com.lge.settings.easy/1000 (adj 15): empty #11
,W/libprocessgroup(  848): failed to open /acct/uid_1000/pid_5556/cgroup.procs: No such file or directory
,D/CalendarProvider2( 5856): [IntentService] Release Lock
D/CalendarProvider2( 5856): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  848): Killing 5507:com.google.process.gapps/u0a6 (adj 15): empty #11
W/libprocessgroup(  848): failed to open /acct/uid_10006/pid_5507/cgroup.procs: No such file or directory
,I/QCNEJ   ( 1908): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1908): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-47 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.114 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-03-02 09:54:38.695 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/WifiInternetCheck(  848): Single check msg out of sync, ignoring.
,I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/art     (  848): Explicit concurrent mark sweep GC freed 55570(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/34MB, paused 2.371ms total 183.920ms
,I/GAV2    ( 5478): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityService(  848): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  848): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5890 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
D/GpsLocationProvider(  848): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  848): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LocSvc_java(  848): onReceive
D/LocSvc_java(  848): got connectivity action
D/libc-netbsd(  848): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  848): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  848): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  848): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  271): App 1000 tries DNS query. Accept family:0 protocol:0
,D/LocSvc_java(  848): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  848): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  848): getAGpsConnectionInfo connType - 4
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
I/[SystemUI]QuickSettingsHandler( 1361): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
D/LocSvc_java(  848): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  848): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  848): Sending msg: 5 arg1:0 arg2:1
I/ActivityManager(  848): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5905 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/libc-netbsd(  848): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  848): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  848): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  848): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  271): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  848): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  848): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  848): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  848): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  271): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out(  848): propertyValue:false
,I/System.out(  848): propertyValue:false
I/System.out(  848): propertyValue:false
,I/GservicesProvider( 5890): Gservices pushing to system: true; secure/global: true
I/ActivityManager(  848): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=5936 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  848): No APN found to select.
I/GoogleHttpClient( 5890): GMS http client unavailable, use old client
,I/GoogleHttpClient( 5890): GMS http client unavailable, use old client
,I/GAv4-SVC( 5437): Google Analytics 8.4.89 is starting up.
,I/ActivityManager(  848): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=5961 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/ActivityManager(  848): Process com.google.android.talk (pid 5256) has died
,I/MusicStore( 5905): Database version: 120
,D/LgeGpsConstants(  848): Can't find 'ext_gps.conf'!!
D/libc-netbsd(  848): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  848): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  848): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  848): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  271): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
W/ResourcesManager( 5961): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5961): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5961): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,D/libc-netbsd(  271): res_queryN name = xxxxx succeed
,I/System.out(  848): propertyValue:false
I/GoogleURLConnFactory( 1749): Using platform SSLCertificateSocketFactory
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5905): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 5936): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5936): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 5936): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/LgeGpsLocationProvider(  848): NTP server: europe.pool.ntp.org
D/LgeGpsLocationProvider(  848): NTP server returned: 1456908880130 (Wed Mar 02 09:54:40 GMT+01:00 2016) reference: 89462 certainty: 81 system time offset: -252
I/ActivityManager(  848): Process com.android.vending (pid 5089) has died
,I/AppConfig( 5961): Total System Memory = 906309632
I/GalleryUtils( 5961): Application Heap = 96 MB
,I/AppConfig( 5961): App Tier : NOT_DEF
W/System  ( 5936): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5936): Installed default security provider GmsCore_OpenSSL
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/SystemHelper( 5961): region [EU], country [EU], operator [OPEN], sub-operator []
E/ActivityThread( 5437): Failed to find provider info for com.android.contacts.metadata
,I/NotificationManager(  848): android: cancelAsUser(-1816247584) by android
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5905): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5905): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/Auth.Api.Credentials( 5437): [CredentialSyncAdapter] Unknown sync event.
D/SyncManager(  848): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 35859, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  848): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 122266, reason: UserStart
I/NotificationManager(  848): android: cancelAsUser(716319171) by android
I/NotificationManager(  848): android: cancelAsUser(-591465577) by android
,D/libc-netbsd(  848): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  848): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  848): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  848): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  271): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
,I/NotificationManager(  848): android: cancelAsUser(-1597574061) by android
,W/ResourcesManager( 5905): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5905): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/AlarmManager(  848): ELAPSED_WAKEUP set : Alarm{1ff01aa1 type 2 when 89777 com.google.android.gms} when 89777
,V/JNIHelp ( 5905): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5905): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
W/System  ( 5905): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@13a159b7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
I/ProviderInstaller( 5905): Installed default security provider GmsCore_OpenSSL
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/AndroidMusic( 5905): GMSCore installation verified
E/BandwidthController(  271): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
W/art     ( 5936): Suspending all threads took: 34.421ms
,I/ConfigStore( 5905): Config Database version: 1
,D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out(  848): propertyValue:false
D/libc-netbsd(  848): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  848): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  848): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  848): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  271): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
,D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out(  848): propertyValue:false
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
,I/DSQN    ( 5846): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5846): restart monitoring
D/LGDataListener(  271): argv[0]=dsqncommand
D/LGDataListener(  271): argv[1]=wlan0
D/LGDataListener(  271): argv[2]=1
D/LGDataListener(  271): notifyDSQN DSQN STARTMONITOR wlan0 1
,D/DSQN    (  848): DSQM DsqnNotification wlan0  1
D/DSQN    (  848): start to monitor internet connection
I/DSQN    ( 5846): dsqn report finish
I/System.out( 1749): propertyValue:false
D/UEI.SmartControl( 5629): Internal timer expired: 1
I/NotificationManager(  848): android: cancelAsUser(-1816247584) by android
,V/WifiInternetCheck(  848): isHttpConnectionAvailable - We got a valid response : 204
,I/art     ( 5936): CheckpointMarkThreadRoots callback created = 0xb042d970
I/art     ( 5936): CheckpointMarkThreadRoots callback created = 0xb4958de0
,I/NotificationManager(  848): android: cancelAsUser(-1597574061) by android
W/ResourcesManager( 5936): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5936): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/YouTube MDX( 5936): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
D/ConnectivityService(  848): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  848): dumpNetworkRequest
D/ConnectivityService(  848):     NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/ConnectivityService(  848):     Requests:
D/ConnectivityService(  848):         NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  848):         NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  848):     Lingered:
D/ConnectivityService(  848): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  848): apparently satisfied.  currentScore=60
D/ConnectivityService(  848): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 5437): CM callback handler got msg 524290
D/libc-netbsd( 5936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5936): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
I/NotificationManager(  848): android: cancelAsUser(-591465577) by android
,I/ActivityManager(  848): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6052 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/dex2oat ( 6046): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads333828325.jar --oat-fd=41 --oat-location=/data/data/com.google.android.youtube/cache/ads333828325.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/MediaRouter( 5905): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/MusicLeanback( 5905): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 5905): type=WIFI subType= reason=null isConnected=true
,W/ResourcesManager( 6052): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/NetworkMonitor( 5905): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  848): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6081 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/NotificationManager( 5936): com.google.android.youtube: cancel(2) by com.google.android.youtube
I/art     ( 5890): Explicit concurrent mark sweep GC freed 7885(397KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 9.168ms total 153.881ms
,I/dex2oat ( 6046): dex2oat took 264.692ms (threads: 4)
,I/ActivityManager(  848): Process com.lge.bnr (pid 5816) has died
,I/art     (  848): Explicit concurrent mark sweep GC freed 35789(1668KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 22MB/34MB, paused 2.924ms total 206.907ms
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5936): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
I/GHttpClientFactory( 5905): Using our fixed implementation of GMSCore's GoogleHttpClient
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5936): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
I/GoogleURLConnFactory( 5905): Using platform SSLCertificateSocketFactory
W/ContextImpl( 5936): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
W/InstanceID/Rpc( 5936): Found 10006
,W/ResourcesManager( 6081): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6081): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6081): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
,W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5936): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
D/AlertService( 5787): Beginning updateAlertNotification
,I/NotificationManager( 5905): com.google.android.music: cancel(1061) by com.google.android.music
,W/DriveInitializer( 5437): Awaiting to be initialized
W/DriveInitializer( 5437): Background init thread started
I/PhenotypeConfigurator( 1749): Scheduling Phenotype for one-off execution 13541 seconds from now (1456908882165)
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
,W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5437): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
D/AlertService( 5787): No fired or scheduled alerts
I/NotificationManager( 5787): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 5787): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 5787): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 5787): com.android.calendar: cancel(3) by com.android.calendar
,I/NotificationManager( 5787): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5787): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 5787): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 5787): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 5787): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 5787): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 5787): com.android.calendar: cancel(10) by com.android.calendar
,I/NotificationManager( 5787): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 5787): com.android.calendar: cancel(12) by com.android.calendar
,I/NotificationManager( 5787): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 5787): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 5787): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 5787): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 5787): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5787): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 5787): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 5787): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 5787): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,I/NotificationManager( 5936): com.google.android.youtube: cancel(10436) by com.google.android.youtube
,D/AlarmScheduler( 5787): No events found starting within 1 week.
,W/DriveInitializer( 5437): Background init thread ended
,D/libc-netbsd( 5936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  271): App 10100 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  848): Killing 5733:com.lge.lgdmsclient/1000 (adj 15): empty #11
,D/libc-netbsd(  271): res_queryN name = xxxxx succeed
,I/System.out( 5936): propertyValue:false
D/libc-netbsd( 5936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/PhenotypeFlagCommitter( 1749): Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,W/libprocessgroup(  848): failed to open /acct/uid_1000/pid_5733/cgroup.procs: No such file or directory
,I/LGEmail ( 6081): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6081): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/ActivityManager(  848): Process com.android.settings (pid 5452) has died
,I/NotificationManager(  848): android: cancelAsUser(-1548111331) by android
D/ChimeraCfgMgr( 5437): Reading stored module config
,I/ActivityManager(  848): Process com.android.calendar (pid 5787) has died
,D/ChimeraCfgMgr( 5437): Loading module com.google.android.gms.games from APK com.google.android.play.games
I/NotificationManager(  848): android: cancelAsUser(353845882) by android
D/ChimeraModuleLdr( 5437): Loading module APK com.google.android.play.games
D/libc-netbsd( 5936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  848): Process com.lge.sync (pid 5686) has died
,I/art     ( 5437): Background sticky concurrent mark sweep GC freed 9542(843KB) AllocSpace objects, 24(384KB) LOS objects, 7% free, 13MB/14MB, paused 6.160ms total 91.908ms
D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
,D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out( 1749): propertyValue:false
,I/GamesSyncServiceMain( 5437): Found unexpected GCM tag when scheduling; aborting
W/GamesSyncServiceMain( 5437): Failed to execute periodic sync, missing client context - aborting
,D/libc-netbsd( 5936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  271): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
D/eas_req ( 6081): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
I/System.out( 5936): propertyValue:false
D/libc-netbsd( 5936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  848): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6177 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/libc-netbsd( 5936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/art     (  299): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 22.895ms
,I/art     (  299): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 297us total 24.968ms
,I/art     (  299): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 22.827ms
,I/HubEmail( 6081): JNI_OnLoad()
I/HubEmail( 6081): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6081): registerNatives()
I/HubEmail( 6081): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6081): registerNativeMethods()
I/HubEmail( 6081): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6081): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  848): Process com.google.android.gm (pid 5478) has died
,D/LGDMClient( 6177): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6177): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6177): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6177): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/Settings( 6081): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 6177): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6177): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6177): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6177): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  848): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6202 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6177): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 6177): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6177): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6177): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6177): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 6177): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
D/libc-netbsd( 5936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/NotificationManager(  848): android: cancelAsUser(-1874035846) by android
,I/AppUp4:AppBoxCP( 6202): onCreate
,W/AppUp4:DB( 6202):  [AppBoxDatabaseHelper] construct
D/libc-netbsd( 5936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/AppUp4:DB( 6202):  setFingerPrint start
,I/AppUp4:DB( 6202):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6202):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6202):  SDK version = 0
I/AppUp4:DB( 6202):  beforefinger == newfinger no write in DB
I/NotificationManager(  848): android: cancelAsUser(2) by android
D/AppUp4:AppBoxApplication( 6202): AppBoxApplication onCreate()
,I/NotificationManager(  848): android: cancelAsUser(353845882) by android
I/NetworkStateForAutoUpdateMonitor( 6202): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6202): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6202): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6202): [onReceive] request level :IDLE....
I/NotificationManager( 1749): com.google.android.gms: cancel(0) by com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 6202): onReceive
,I/AppUp4:CustModeStarterReceiver( 6202): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6202): Context : android.app.ReceiverRestrictedContext@2855a12b
D/AppUp4:CustFacade( 6202): isCustomizationCompleted : false
I/ActivityManager(  848): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=6226 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/AppUp4:CustFacade( 6202): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6202): begin check event
,I/AppUp4:CustModeStarterReceiver( 6202): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6202): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6202): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6202): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6202): handleAsyncCustNotification do not startCustService
,W/art     ( 6052): Attempt to remove local handle scope entry from IRT, ignoring
,I/LgeMiscReceiver( 3037): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3037): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3037): networkInfo.isConnected() = true
D/PhoneState( 3037): setPdpRejectCasuse : false
,I/ActivityManager(  848): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6245 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  848): Process com.lge.qremote (pid 5596) has died
,W/ActivityManager(  848): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/UEI.SmartControl( 5629): Service.onUnbind: IControl
D/UEI.SmartControl( 5629): Service.onDestroy
D/UEI.SmartControl( 5629): Shutdown IRRCPlayer... 
D/libc-netbsd( 6052): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6052): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
,E/BandwidthController(  271): [LG DATA] No such appUid: 10086
D/DnsProxyListener(  271): App 10086 tries DNS query. Accept family:2 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
W/irrc_jni( 5629): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 5629): ~IrrcClient ++ 
D/irrcClient( 5629): ~IrrcClient -- 
W/irrc_jni( 5629): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 5629): Blaster closed
D/UEI.SmartControl( 5629): Blaster closed
D/UEI.SmartControl( 5629): Shut down QS...
D/UEI.SmartControl( 5629): Stopped file observer...
I/UEI.SmartControl( 5629): QS lib stop result = true
D/UEI.SmartControl( 5629): QS shutdown complete
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6226): getAccountsCursor
,W/InstanceID/Rpc( 5437): Found 10006
W/GAV2    ( 6226): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/PhoneMonitor( 6245): Register our PhoneStateListener
,I/art     (  848): Explicit concurrent mark sweep GC freed 29422(1360KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 2.080ms total 156.506ms
,I/art     (  848): WaitForGcToComplete blocked for 28.270ms for cause HeapTrim
I/ActivityManager(  848): Process com.uei.lg.quicksetsdk.lite (pid 5629) has died
,W/ActivityManager(  848): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager(  848): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6226): Observing account changes for notifications
W/ActivityManager(  848): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,W/Gmail   ( 6226): Sync started for account: account:61035162
D/MobileConnectivityChangeReceiver( 6245): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6245): onReceive CONNECTIVITY_CHANGE networkType=1
E/Gmail   ( 6226): Error finding the version of the Email provider.....
E/Gmail   ( 6226): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6226): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6226): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6226): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6226): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6226): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6226): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6226): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6226): We do not support migrating this version of the Email provider.
,I/Gmail   ( 6226): getAccountsCursor
D/sensors_hal_Time(  848): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  848): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  848): tsOffsetIs: Apps: 93729281792; DSPS: 3169534; Offset : -3004285791
,V/DownloadManager( 3065): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/PhoneMonitor( 6245): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/DownloadManager( 3065): DownloadService onCreate
V/TelephonyAutoProfiling( 6245): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6245): [parse] Load xml
V/TelephonyAutoProfiling( 6245): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6245): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6245): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/DownloadManager( 3065): in removeSpuriousFiles
I/NotificationManager( 3065): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,V/DownloadManager( 3065): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3065): created cursor android.database.sqlite.SQLiteCursor@33f4b201 on behalf of 3065
I/DownloadManager( 3065): in trimDatabase
V/DownloadManager( 3065): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3065): created cursor android.database.sqlite.SQLiteCursor@3cefb2e7 on behalf of 3065
I/ActivityManager(  848): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6296 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/DownloadManager( 3065): DownloadService onStartCommand
,V/DownloadManager( 3065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3065): created cursor android.database.sqlite.SQLiteCursor@7f96d3d on behalf of 3065
,I/CheckinService( 5437): Checkin interval check for package: unspecified last checkin: 1456825786151 min interval config: 0 actual interval: 83098650
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinService( 5437): Disabling old GoogleServicesFramework version
,I/VacuumService( 1749): Vacuum at: now=1456908884860 tag=VacuumService
,V/DownloadManager( 3065): DownloadService onDestroy
,D/DrmBroadcastReceiver( 6296): Receive CONNECTIVITY_ACTION
D/DrmBroadcastReceiver( 6296): 1  network is available. Sync DRM Time with NTP
,V/DrmService( 6296): Service onCreate
D/DrmService( 6296): Received new request = 2
I/DrmSntpClient( 6296): Start Sync process
D/DrmSntpClient( 6296): Server : 0
,D/WeatherAncestor( 2575): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:54:44
D/UpdateThreadPoolManager( 2575): 2 : This is isUpdating : false
D/WeatherAncestor( 2575): connectivity changed - connection : true
D/libc-netbsd( 6296): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6296): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6296): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6296): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10051
D/DnsProxyListener(  271): App 10051 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/Weather_cast( 2575): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2575): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:54:44
D/WeatherService( 2575): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out( 6296): propertyValue:false
,I/ActivityManager(  848): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6322 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  848): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2575): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2575): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2575): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/Gmail   ( 6226): notifyAccountChanged
,I/CheckinService( 5437): Checking schedule, now: 1456908885091 next: 1456825816111
I/CheckinService( 5437): active receiver: enabled
I/Gmail   ( 6226): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 6226): getAccountsCursor
I/LGDrmClient( 6296): _DRM_ServiceGet() : Bind lgdrm service
,V/ILGDrmService(  280): eDRM_SetDRMTime +++
I/LGDRM   (  280): [DRM] SET TIME : YR=2016, MON=3, DAY=2
I/LGDRM   (  280): [DRM] SET TIME : HR=8, MIN=54, SEC=43
,I/Gmail   ( 6226): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/CheckinService( 5437): Preparing to send checkin request
V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/ILGDrmService(  280): eDRM_SetDRMTime ---
,I/DrmSntpClient( 6296): Synched
D/DrmService( 6296): Completed !! request = 2
D/DrmService( 6296): Request count = 0
V/DrmService( 6296): Service onDestroy
W/ResourcesManager( 6322): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/EventLogService( 5437): Accumulating logs since 1456908732559
,I/Gmail   ( 6226): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 6226): notifyAccountChanged
I/Gmail   ( 6226): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/ActivityManager(  848): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6342 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  848): RTC_WAKEUP set : Alarm{3349f9f4 type 0 when 1456908885172 com.android.vending} when 1456908885172
I/ActivityManager(  848): Process com.google.android.music:main (pid 5905) has died
,I/Gmail   ( 6226): getAccountsCursor
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6342): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/CheckinRequestBuilder( 5437): Checkin reason type: 8 attempt count: 1
I/Babel_SMS( 6322): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6322): MmsConfig.loadMmsSettings
,I/ActivityManager(  848): Process com.android.gallery3d (pid 5961) has died
,E/ActivityThread( 5437): Failed to find provider info for com.google.android.wearable.settings
I/jxcore-log( 4586): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 4586): 
I/Babel_SMS( 6322): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6322): MmsConfig.loadFromDatabase
,D/Finsky  ( 6342): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/NotificationManager(  848): android: cancelAsUser(2145784878) by android
I/NotificationManager( 6052): com.google.android.apps.plus: cancel(10436) by com.google.android.apps.plus
W/Settings( 6342): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6342): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Babel_SMS( 6322): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6322): MmsConfig.loadFromResources
E/Babel_SMS( 6322): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6322): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/NotificationManager( 6342): com.android.vending: cancel(-1050172287) by com.android.vending
W/art     ( 5890): Suspending all threads took: 14.843ms
,I/art     ( 5890): Explicit concurrent mark sweep GC freed 2796(112KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 23.859ms total 116.537ms
,I/ActivityManager(  848): Start proc com.google.android.apps.magazines for service com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.service.SyncAdapterService: pid=6398 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  848): Process com.lge.email (pid 6081) has died
,V/DownloadManager( 3065): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3065): created cursor android.database.sqlite.SQLiteCursor@3f7a9683 on behalf of 6342
,D/SensorManager( 6322): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6322): found sensor: LGE Magnetometer Sensor, handle=10
,D/SensorManager( 6322): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6322): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6322): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6322): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6322): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6322): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6322): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6322): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6322): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6322): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6322): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6322): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6322): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6322): found sensor: Motion Accel, handle=46
I/art     ( 6322): CheckpointMarkThreadRoots callback created = 0xb042d800
D/Ads     ( 6342): Skipping gmscore version check
,D/Finsky  ( 6342): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6342): [1] Libraries$2.run: Finished loading 1 libraries.
I/art     ( 6322): CheckpointMarkThreadRoots callback created = 0xb042d7e0
,D/Finsky  ( 6342): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/Gmail   ( 6226): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 17727, normalSync: true
,W/Settings( 6322): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6322): startup - clean
,D/Finsky  ( 6342): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Babel   ( 6322): deleted: false for 0
,I/art     (  848): Explicit concurrent mark sweep GC freed 26820(1290KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 22MB/34MB, paused 2.681ms total 169.113ms
,I/ActivityManager(  848): Process com.android.providers.calendar (pid 5856) has died
,D/Finsky  ( 6342): [765] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6342): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
W/AudioCapabilities( 6322): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6322): Unsupported mime audio/adpcm
W/AudioCapabilities( 6322): Unsupported mime audio/g726
W/AudioCapabilities( 6322): Unsupported mime audio/x-ms-wma
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/AudioCapabilities( 6322): Unsupported mime audio/wma-voice
W/ContextImpl( 6398): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
W/VideoCapabilities( 6322): Unsupported mime video/mjpg
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6398): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,W/VideoCapabilities( 6322): Unsupported mime video/theora
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6398): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 6398): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6398):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6398):   adb logcat -s GAv4
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6398): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 6398): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/art     ( 5437): Suspending all threads took: 11.645ms
I/art     ( 5437): Background partial concurrent mark sweep GC freed 17132(1026KB) AllocSpace objects, 5(80KB) LOS objects, 40% free, 12MB/21MB, paused 13.375ms total 68.607ms
,W/GAv4    ( 6398): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/AudioCapabilities( 6322): Unsupported mime audio/evrc
W/AudioCapabilities( 6322): Unsupported mime audio/qcelp
W/VideoCapabilities( 6322): Unrecognized profile 2130706433 for video/avc
,W/ResourcesManager( 6226): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6226): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/GAv4    ( 6398): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AudioCapabilities( 6322): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6322): Unsupported mime audio/qcelp
W/AudioCapabilities( 6322): Unsupported mime audio/evrc
W/VideoCapabilities( 6322): Unsupported mime video/mp4v-esdp
,V/AlarmManager(  848): RTC_WAKEUP set : Alarm{23b5a86d type 0 when 1456908887000 com.android.vending} when 1456908887000
D/Finsky  ( 6342): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  848): android: cancelAsUser(2) by android
,I/VideoCapabilities( 6322): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 6322): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6322): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6322): Unrecognized profile 2130706433 for video/avc
V/JNIHelp ( 6226): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/VideoCapabilities( 6322): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6322): onServiceConnected
,W/Babel   ( 6322): Attempted to change video mute state without an active call.
I/NotificationManager( 6322): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6322): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6322): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6322): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6322): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  271): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out( 6322): propertyValue:false
D/libc-netbsd( 6342): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6342): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6342): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6342): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  271): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out( 6342): propertyValue:false
D/libc-netbsd( 6342): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6342): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/System  ( 6226): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[directory "."],nativeLibraryDirectories=[/vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6226): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  848): android: cancelAsUser(2) by android
,I/Babel   ( 6322): connection state changed from UNKNOWN to CONNECTED
,I/NotificationManager(  848): android: cancelAsUser(2) by android
,I/ActivityManager(  848): Process com.lge.appbox.client (pid 6202) has died
,I/NotificationManager( 1749): com.google.android.gms: cancel(0) by com.google.android.gms
D/libc-netbsd( 6342): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6342): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6226): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6226): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6226): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6226): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10053
D/DnsProxyListener(  271): App 10053 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
,D/libc-netbsd(  271): res_queryN name = xxxxx succeed
,I/System.out( 6226): propertyValue:false
D/libc-netbsd( 6226): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6226): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/WebViewFactory( 6398): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/jxcore-log( 4586): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 4586): 
,I/ActivityManager(  848): Process com.lge.lgdmsclient (pid 6177) has died
,D/ChimeraCfgMgr( 5437): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5437): Module APK com.google.android.play.games already loaded
,I/BackgroundMemoryTrimmer( 2022): Trimming objects from memory, since app is in the background.
,I/PhoneApp( 1782): onTrimMemory: 10
I/PhoneApp( 1782): trim memory
,I/ActivityManager(  848): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6458 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/art     ( 6226): CheckpointMarkThreadRoots callback created = 0xaaf623b0
,I/LibraryLoader( 6398): Time to load native libraries: 5 ms (timestamps 6916-6921)
I/LibraryLoader( 6398): Expected native library version number "",actual native library version number ""
,I/jxcore-log( 4586): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4586): 
I/jxcore-log( 4586): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 4586): 
,I/art     ( 6226): CheckpointMarkThreadRoots callback created = 0xb042dd20
V/WebViewChromiumFactoryProvider( 6398): Binding Chromium to main looper Looper (main, tid 1) {b5d185c}
I/LibraryLoader( 6398): Expected native library version number "",actual native library version number ""
,W/ResourcesManager( 6458): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6458): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/chromium( 6398): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6398): Initializing chromium process, singleProcess=true
,W/art     ( 6398): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6398): ApplicationContext is null in ApplicationStatus
I/MultiDex( 6458): VM with version 2.1.0 has multidex support
I/MultiDex( 6458): install
I/MultiDex( 6458): VM has multidex support, MultiDex support library is disabled.
,I/jxcore-log( 4586): INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native
I/jxcore-log( 4586): 
,I/jxcore-log( 4586): INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native
I/jxcore-log( 4586): 
I/io.jxcore.node.ConnectivityInfo( 4586): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 4586):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 4586):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 4586):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 4586):     - is Bluetooth enabled: false
I/io.jxcore.node.ConnectivityInfo( 4586):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo( 4586):     - is connected/connecting to active network: true
I/io.jxcore.node.ConnectivityInfo( 4586):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo( 4586):     - force notify: true
D/io.jxcore.node.JXcoreExtension( 4586): notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,I/jxcore-log( 4586): INFO thaliMobileNativeWrapper Method networkChanged registered to native
I/jxcore-log( 4586): 
I/jxcore-log( 4586): INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native
I/jxcore-log( 4586): 
V/JNIHelp ( 6458): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/art     ( 1782): Explicit concurrent mark sweep GC freed 26462(1472KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 11MB/18MB, paused 15.539ms total 335.635ms
,W/ActivityThread( 6458): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6458): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@11984c2c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6458): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6458): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6458): com.google.android.gms: cancel(39789) by com.google.android.gms
,W/chromium( 6398): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,D/libc-netbsd( 6226): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6226): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/art     ( 1749): Explicit concurrent mark sweep GC freed 81595(4MB) AllocSpace objects, 29(487KB) LOS objects, 40% free, 14MB/23MB, paused 1.358ms total 148.475ms
I/art     ( 6458): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6458): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  848): android: cancelAsUser(2) by android
,E/libEGL  ( 6398): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6398): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6398): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6398): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6398): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6398): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6398): Remote Branch: 
I/Adreno-EGL( 6398): Local Patches: 
I/Adreno-EGL( 6398): Reconstruct Branch: 
,D/NativeLibraryUtils( 6458): Install completed successfully. count=14 extracted=0
I/qtaguid ( 6342): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6342): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6342): untagSocket(41) failed with errno -22
D/Finsky  ( 6342): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/ActivityManager(  848): Process com.google.android.setupwizard (pid 6245) has died
I/ActivityManager(  848): Process com.lge.drmservice (pid 6296) has died
,I/PhoneApp( 1782): onTrimMemory: 15
I/PhoneApp( 1782): trim memory
D/WVCdm   (  275): Instantiating CDM.
I/WVCdm   (  275): CdmEngine::OpenSession
I/WVCdm   (  275): Level3 Library Dec 11 2014 16:13:16
,W/WVCdm   (  275): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  275): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  275): L1 library not specified. Falling Back to L3
,I/GoogleURLConnFactory( 6458): Using platform SSLCertificateSocketFactory
,D/libc-netbsd( 6458): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6458): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6458): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6458): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out( 6458): propertyValue:false
V/AudioPolicyService(  275): registerClient() client 0xb39b6420, uid 10079
W/AudioManagerAndroid( 6398): Requires BLUETOOTH permission
,I/WVCdm   (  275): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  275): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  275): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  275): CdmEngine::GenerateKeyRequest
D/WVCdm   (  275): PrepareKeyRequest: nonce=133600561
,I/ActivityManager(  848): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6503 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NSApplication( 6398): Starting up...
,I/NotificationManager(  848): android: cancelAsUser(2) by android
,D/libc-netbsd( 6458): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6458): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6458): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6458): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/SyncAdapterService( 6398): Ignoring sync request for non-current account
,W/ResourcesManager( 6503): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6503): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  848): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6522 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MultiDex( 6503): VM with version 2.1.0 has multidex support
I/MultiDex( 6503): install
I/MultiDex( 6503): VM has multidex support, MultiDex support library is disabled.
,E/libprocessgroup(  848): failed to kill 1 processes for processgroup 6052
I/ActivityManager(  848): Process com.google.android.apps.plus (pid 6052) has died
,I/NotificationManager(  848): android: cancelAsUser(-701419433) by android
,V/JNIHelp ( 6503): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/art     ( 6458): CheckpointMarkThreadRoots callback created = 0xaaf0c550
I/art     ( 6458): CheckpointMarkThreadRoots callback created = 0xaae47e20
,W/ActivityThread( 6503): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6503): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@11984c2c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6503): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6503): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6503): com.google.android.gms: cancel(39789) by com.google.android.gms
,I/GAV2    ( 6226): Thread[GAThread,5,main]: No campaign data found.
,D/ChimeraCfgMgr( 6503): Reading stored module config
I/PeopleSync( 5437): onPerformSync() [5005f081]
,D/ChimeraCfgMgr( 6503): Loading module com.google.android.gms.car from APK com.google.android.gms
,I/NotificationManager( 6226): com.google.android.gm: cancel(10436) by com.google.android.gm
,I/ActivityManager(  848): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6554 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/qtaguid ( 6342): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6342): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6342): untagSocket(41) failed with errno -22
,I/art     (  299): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 300us total 25.499ms
D/NativeLibraryUtils( 6503): Install completed successfully. count=14 extracted=0
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
I/art     (  299): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 20.955ms
,I/art     (  299): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 20.659ms
,W/ResourcesManager( 6554): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CAR.SERVICE( 6503): Connecting to CarCallService...
I/art     ( 6503): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6503): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/PeopleDatabaseHelper( 5437): cleanUpNonGplusAccounts done.
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/CAR.SERVICE( 6503): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6503): Creating a new CarCallService.
,D/CAR.SERVICE( 6503): Package validated; name: com.android.vending
D/CAR.TEL.PhoneAdapter( 6503): Creating a new PhoneAdapter instance
W/ActivityManager(  848): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6503): setListener: com.google.android.gms.car.dn@32a5f0eb
,W/ActivityManager(  848): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6503): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6503): Starting CarCallService with initial phone null
I/art     ( 5890): Explicit concurrent mark sweep GC freed 2786(114KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 618us total 67.489ms
,I/NotificationManager( 6503): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6342): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 6342): [1] GearheadStateMonitor.access$100: mIsProjecting:false
I/ActivityManager(  848): Process com.google.android.talk (pid 6322) has died
,I/PhoneApp( 1782): onTrimMemory: 15
I/PhoneApp( 1782): trim memory
I/dex2oat ( 6581): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=39 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/PeopleSync( 5437): Setting subscription: result=true [5005f081]
,I/PeopleSync( 5437): Starting sync, feed=null [5005f081]
I/dex2oat ( 6581): dex2oat took 181.393ms (threads: 4)
,I/WVCdm   (  275): CdmEngine::CloseSession
I/WVCdm   (  275): L3 Terminate.
,I/Adreno-EGL( 6458): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6458): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6458): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6458): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6458): Remote Branch: 
I/Adreno-EGL( 6458): Local Patches: 
I/Adreno-EGL( 6458): Reconstruct Branch: 
,I/iu.SyncManager( 5437): SYNC; picasa accounts
,D/NetworkLogImpl( 5437): Loaded NetworkSpeedPredictor
,I/iu.Environment( 5437): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 5437): num queued entries: 0
,I/iu.UploadsManager( 5437): num updated entries: 0
I/iu.SyncManager( 5437): NEXT; no task
D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
,D/libc-netbsd( 5936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  271): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
,I/art     ( 6342): CheckpointMarkThreadRoots callback created = 0xaaf12f50
I/ActivityManager(  848): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6603 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out( 1749): propertyValue:false
,I/art     ( 6342): CheckpointMarkThreadRoots callback created = 0xaaf12f40
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out( 5936): propertyValue:false
D/libc-netbsd( 5936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/BaseAppContext( 5437): Using Auth Proxy for data requests.
,D/libc-netbsd( 5936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,E/BaseAppContext( 5437): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,W/ResourcesManager( 6603): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/art     (  848): Explicit concurrent mark sweep GC freed 23090(1075KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 2.478ms total 178.595ms
,W/BaseAppContext( 5437): Using Auth Proxy for data requests.
,D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/BaseAppContext( 5437): Using Auth Proxy for data requests.
,I/GCM     ( 1749): GCM config loaded
D/BluetoothManagerService(  848): Message: 20
D/BluetoothManagerService(  848): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1f06381a:true
,D/BluetoothAdapterService(1072279366)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@28ecf7cc
D/BluetoothAdapterService(1072279366)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@28ecf7cc
I/PeopleSync( 5437): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,I/Adreno-EGL( 6458): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6458): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6458): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6458): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6458): Remote Branch: 
I/Adreno-EGL( 6458): Local Patches: 
I/Adreno-EGL( 6458): Reconstruct Branch: 
,I/Adreno-EGL( 6458): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6458): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6458): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6458): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6458): Remote Branch: 
I/Adreno-EGL( 6458): Local Patches: 
I/Adreno-EGL( 6458): Reconstruct Branch: 
,D/WearableService( 1749): callingUid 10006, callindPid: 1749
,E/MDM     ( 1749): [114] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1749): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 5437): Restart initialization of location
D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/System.out( 1749): propertyValue:false
I/NotificationManager( 1749): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1749): No location to return for getLastLocation()
W/FusedLocationProvider( 1749): location=null
E/MDM     ( 1749): [127] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1749): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 5437): Restart initialization of location
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1749): com.google.android.gms: cancel(0) by com.google.android.gms
,W/GCoreFlp( 1749): No location to return for getLastLocation()
W/FusedLocationProvider( 1749): location=null
,D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/art     ( 6226): Explicit concurrent mark sweep GC freed 7458(295KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 10MB/14MB, paused 665us total 65.628ms
I/Gmail   ( 6226): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 17798, normalSync: true
,I/Gmail   ( 6226): lowestBackward conversation id 0
I/ActivityManager(  848): Process com.google.android.youtube (pid 5936) has died
I/ActivityManager(  848): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6643 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 6603): Create singleton instance
I/WVCdm   (  275): CdmEngine::OpenSession
I/WVCdm   (  275): Level3 Library Dec 11 2014 16:13:16
,W/WVCdm   (  275): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  275): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  275): L1 library not specified. Falling Back to L3
,I/NotificationManager( 6226): com.google.android.gm: cancel(10436) by com.google.android.gm
I/WVCdm   (  275): CdmEngine::QueryKeyControlInfo
I/NotificationManager( 6226): com.google.android.gm: cancel(10436) by com.google.android.gm
,W/WVCdm   (  275): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  275): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  275): CdmEngine::GenerateKeyRequest
I/AudioManager( 6603): getMode name:com.lge.qremote
D/WVCdm   (  275): PrepareKeyRequest: nonce=2044984548
,I/NotificationManager(  848): android: cancelAsUser(2) by android
,I/NotificationManager( 1749): com.google.android.gms: cancel(0) by com.google.android.gms
,I/ActivityManager(  848): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6661 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
D/UEI.SmartControl( 6643): Quickset Services start...
I/UEI.SmartControl( 6643): Manufacture = LGE
,D/UEI.SmartControl( 6643): File observer start...
E/UEI.SmartControl( 6643): IR Port is disabled: false
D/UEI.SmartControl( 6643): Starting file observer...
D/UEI.SmartControl( 6643): Extracting JNI libs...
D/UEI.SmartControl( 6643): --- this system supports 32-bit or 64-bit only
,D/UEI.SmartControl( 6643): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6643): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6643): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6643): --- Selecting new region: 2
I/UEI.SmartControl( 6643): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6643): Platform has CIR...
,D/UEI.SmartControl( 6643): NO CIR support, need to check package...
I/UEI.SmartControl( 6643): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6643): QS Service created
,E/UEI.SmartControl( 6643): QS start get config
,I/Gmail   ( 6226): notifyAccountChanged
I/Gmail   ( 6226): getAccountsCursor
V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 6661): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Gmail   ( 6226): notifyAccountChanged
W/Gmail   ( 6226): Sync complete for account: account:61035162
,I/Gmail   ( 6226): getAccountsCursor
I/NotificationManager(  848): android: cancelAsUser(1479798955) by android
,D/UEI.SmartControl( 6643): Loading JNI Libs...
V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 6643):  configuring local db...
,D/libc-netbsd( 5437): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5437): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5437): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5437): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
,D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out( 5437): propertyValue:false
I/GoogleURLConnFactory( 5437): Using platform SSLCertificateSocketFactory
,D/libc-netbsd( 5437): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5437): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5437): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5437): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5437): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5437): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/UEI.SmartControl( 6643):  ---- Has DB8: true
D/UEI.SmartControl( 6643): QS start statue = true Error code = 0
D/UEI.SmartControl( 6643): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6643): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6643): IRRCDataComm has AudioManager!!!!.
,E/libprocessgroup(  848): failed to kill 1 processes for processgroup 6398
I/ActivityManager(  848): Process com.google.android.apps.magazines (pid 6398) has died
I/PhoneApp( 1782): onTrimMemory: 15
I/PhoneApp( 1782): trim memory
V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/irrc_jni( 6643): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6643): IrrcClient ++ 
D/irrcClient( 6643): getIrrcService ++ 
I/NotificationManager(  848): android: cancelAsUser(2) by android
D/irrcClient( 6643): getIrrcService -- 
D/irrcClient( 6643): IrrcClient -- 
W/irrc_jni( 6643): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6643): Services init done
I/UEI.SmartControl( 6643): Device manager: loading config....
D/UEI.SmartControl( 6643): QS Service init finished
D/UEI.SmartControl( 6643): QS Service version name: 0.1.73
,D/UEI.SmartControl( 6643): QS Service version code: 1073
D/UEI.SmartControl( 6643): Service requested: Control
D/UEI.SmartControl( 6643): Config is loaded...
D/UEI.SmartControl( 6643): -----IControl: 11
D/UEI.SmartControl( 6643): Caller: com.lge.qremote
,D/UEI.SmartControl( 6643): ------------ IControl registerCallback...
I/UEI.SmartControl( 6643): Registering callback...
D/UEI.SmartControl( 6643): -----IControl: 19
D/UEI.SmartControl( 6643): Caller: com.lge.qremote
I/UEI.SmartControl( 6643): Registering Services Ready callback...
D/UEI.SmartControl( 6643): Service.onTrimMemory: 15
E/UEI.SmartControl( 6643): Setup service releasing memory...
V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  848): android: cancelAsUser(2) by android
,D/UEI.SmartControl( 6643):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6643): Notify AllClients services are ready: 0
,I/art     ( 6643): Explicit concurrent mark sweep GC freed 10294(745KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 7MB/9MB, paused 378us total 63.223ms
D/UEI.SmartControl( 6643): Internal service binding...
D/UEI.SmartControl( 6643): -----IControl: 8
D/UEI.SmartControl( 6643): Caller: com.lge.qremote
D/UEI.SmartControl( 6643): Service.onTrimMemory: 80
E/UEI.SmartControl( 6643): Setup service releasing memory...
,D/libc-netbsd( 5437): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5437): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5437): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5437): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out( 5437): propertyValue:false
,D/KeyguardUpdateMonitor( 1361): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1872): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1361): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1361): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
,D/charger_monitor(  486): init target 500000
I/[SystemUI]LGPowerUI( 1361): On Skip Timer : true
I/Babel_SMS( 6661): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6661): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6661): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6661): MmsConfig.loadFromDatabase
I/QCNEJ   ( 1908): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2073): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1361): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1361): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1872): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1872): Battery Level Remaining: 100%
D/LEDHandler( 1872): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1908): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
W/Settings(  848): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  848): battery changed pluggedType: 2
W/Settings(  848): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/charger_monitor(  486): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[SystemUI]LGPowerUI( 1361): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,I/QCNEJ   ( 1908): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1908): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
W/Settings(  848): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  848): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LEDHandler( 1872): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1872): Battery Level Remaining: 100%
D/WifiController(  848): battery changed pluggedType: 2
D/LEDHandler( 1872): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2073): Disconnected process message: 10, size: 0
,I/[SystemUI]BatterySaverHandler( 1361): onReceive = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1361): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1361): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1361): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
I/[SystemUI]BatterySaverHandler( 1361): onReceive = android.intent.action.BATTERY_CHANGED
,E/Babel_SMS( 6661): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6661): MmsConfig.loadFromResources
E/Babel_SMS( 6661): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6661): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Icing   ( 5437): Indexing D5FAA4CC7B77CE1CF3A47D8A751643B189A42F2E from com.google.android.gm
,I/ActivityManager(  848): Process com.google.android.apps.plus (pid 6554) has died
,D/SensorManager( 6661): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6661): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6661): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6661): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6661): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6661): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6661): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6661): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6661): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6661): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6661): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6661): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6661): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6661): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6661): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6661): found sensor: Motion Accel, handle=46
,I/qtaguid ( 6342): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6342): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6342): untagSocket(41) failed with errno -22
I/art     ( 6661): CheckpointMarkThreadRoots callback created = 0xaaf51360
,W/Settings( 6661): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Icing   ( 5437): Indexing done D5FAA4CC7B77CE1CF3A47D8A751643B189A42F2E
I/Babel_Crash( 6661): startup - clean
,I/Babel   ( 6661): deleted: false for 0
I/art     ( 6661): CheckpointMarkThreadRoots callback created = 0xaaf51330
D/libc-netbsd( 5437): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5437): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5437): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5437): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/AudioManager( 6603): getMode name:com.lge.qremote
,D/UEI.SmartControl( 6643): Service.onTrimMemory: 60
E/UEI.SmartControl( 6643): Setup service releasing memory...
W/AudioCapabilities( 6661): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6661): Unsupported mime audio/adpcm
W/AudioCapabilities( 6661): Unsupported mime audio/g726
W/AudioCapabilities( 6661): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6661): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6661): Unsupported mime video/mjpg
,W/VideoCapabilities( 6661): Unsupported mime video/theora
,I/AudioManager( 6603): getMode name:com.lge.qremote
,W/AudioCapabilities( 6661): Unsupported mime audio/evrc
,W/AudioCapabilities( 6661): Unsupported mime audio/qcelp
D/UEI.SmartControl( 6643): Service.onTrimMemory: 80
E/UEI.SmartControl( 6643): Setup service releasing memory...
W/VideoCapabilities( 6661): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6661): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6661): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6661): Unsupported mime audio/evrc
W/VideoCapabilities( 6661): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6661): Unsupported profile 4 for video/mp4v-es
,I/AudioManager( 6603): getMode name:com.lge.qremote
D/UEI.SmartControl( 6643): Service.onTrimMemory: 80
E/UEI.SmartControl( 6643): Setup service releasing memory...
,W/VideoCapabilities( 6661): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6661): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6661): Unrecognized profile 2130706433 for video/avc
,W/ResourcesManager( 6342): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6342): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/VideoCapabilities( 6661): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6661): onServiceConnected
W/Babel   ( 6661): Attempted to change video mute state without an active call.
I/NotificationManager( 6661): com.google.android.talk: cancel(10436) by com.google.android.talk
,W/ResourcesManager( 6342): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/Finsky  ( 6342): [1] DailyHygiene.access$600: Logging device features
,I/WVCdm   (  275): CdmEngine::CloseSession
,I/WVCdm   (  275): L3 Terminate.
V/AlarmManager(  848): RTC_WAKEUP set : Alarm{339c0dad type 0 when 1456908894235 com.android.vending} when 1456908894235
,I/CheckinRequestBuilder( 5437): Classify the device as Phone.
,D/DeviceConnectionService( 1749): client connected with version: 8296000
D/Finsky  ( 6342): [775] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6342): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 6342): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  848): android: cancelAsUser(2) by android
,I/art     ( 5437): Explicit concurrent mark sweep GC freed 28046(1908KB) AllocSpace objects, 15(263KB) LOS objects, 40% free, 13MB/23MB, paused 1.933ms total 108.211ms
,E/Volley  ( 5437): [715] BasicNetwork.performRequest: Unexpected response code 410 for https://www.googleapis.com/plus/v2whitelisted/people/me/people/all?prettyPrint=false&fields=items(etag,id,names,nicknames,images,urls,sortKeys,taglines,emails,phoneNumbers,addresses,metadata,memberships,legacyFields/mobileOwnerId),nextPageToken,nextSyncToken&customResponseMaskingType=menagerie&includeAffinity=gplusAutocomplete&includeAffinity=chatAutocomplete&includeAffinity=emailAutocomplete&includeOthers=true&maxResults=100&orderBy=modified&syncToken=CPj2pMuyKhIBMRjnEioECAEQAQ
,I/PeopleSync( 5437): Sync Token out of date, syncing all people/gaia-map
D/libc-netbsd( 6342): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6342): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6342): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6342): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  271): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
,I/System.out( 6342): propertyValue:false
D/libc-netbsd( 5437): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5437): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/rmt_storage(  268): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  268): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  268): wakelock acquired: 1, error no: 42
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
,I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 22
I/rmt_storage(  268): 
I/rmt_storage(  268): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
D/libc-netbsd( 5437): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5437): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/NotificationManager(  848): android: cancelAsUser(2126026182) by android
,I/ActivityManager(  848): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/com.google.android.apps.photos.service.GooglePhotoDownsyncService: pid=6718 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6718): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/PeopleSync( 5437): Sync finished, successful=true, took 3502ms
,I/PeopleContactsSync( 5437): CP2 sync start [5005f081]
,D/libc-netbsd( 5437): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5437): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5437): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5437): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/PeopleContactsSync( 5437): CP2 sync: diff=PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
I/PeopleContactsSync( 5437): Syncing people to contacts: PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,I/CheckinTask( 5437): Sending checkin request (10136 bytes)
,I/[SystemUI]QPairHandler( 1361): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1908): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[SystemUI]QSlideListController( 1361): onReceive = android.intent.action.PACKAGE_CHANGED
W/ResourcesManager( 1782): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/InputReader(  848): Reconfiguring input devices.  changes=0x00000010
,D/CAR.SERVICE( 6503): mConnectedToCar = false, abort
,W/[SystemUI]QSlideLoader( 1361): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1361): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1361): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1361): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1361): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1361): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1361): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1361): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1361): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1361): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1361): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1361): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1361): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/[LGHome]EVENT( 1946): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/art     (  848): Explicit concurrent mark sweep GC freed 28272(1281KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 26.158ms total 276.714ms
I/[LGHome]LGPlusHomeDBManager( 1946): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1946): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
D/administrator(  848): Handling package changes for user 0
E/ActivityThread( 6503): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@22df9930 that was originally bound here
E/ActivityThread( 6503): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@22df9930 that was originally bound here
E/ActivityThread( 6503): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6503): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6503): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6503): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6503): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6503): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6503): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6503): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6503): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6503): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6503): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6503): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6503): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6503): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6503): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6503): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6503): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6503): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6503): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6503): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6503): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6503): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6503): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6503): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1fea6c3a that was originally bound here
E/ActivityThread( 6503): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1fea6c3a that was originally bound here
E/ActivityThread( 6503): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6503): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6503): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6503): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6503): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6503): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6503): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6503): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6503): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6503): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6503): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6503): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6503): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6503): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6503): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6503): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6503): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6503): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6503): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6503): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6503): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6503): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  848): Unbind failed: could not find connection for android.os.BinderProxy@2c040b24
,I/NotificationManager( 6661): com.google.android.talk: cancel(8) by com.google.android.talk
,I/[LGHome]Launcher( 1946): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  848): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6745 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ResourcesManager( 6661): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6661): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/lowmemorykiller(  242): Error writing /proc/6226/oom_score_adj; errno=22
,V/JNIHelp ( 6661): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/CheckinResponseProcessor( 5437): From server: 3 gservices updates and 0 deletes
,I/ActivityManager(  848): Process com.google.android.gm (pid 6226) has died
,I/BackgroundMemoryTrimmer( 2022): Trimming objects from memory, since app is in the background.
,I/PhoneApp( 1782): onTrimMemory: 10
I/PhoneApp( 1782): trim memory
I/AppUp4:AppBoxCP( 6745): onCreate
,W/AppUp4:DB( 6745):  [AppBoxDatabaseHelper] construct
D/UEI.SmartControl( 6643): Service.onTrimMemory: 60
E/UEI.SmartControl( 6643): Setup service releasing memory...
I/AppUp4:DB( 6745):  setFingerPrint start
I/AppUp4:DB( 6745):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/PeopleContactsSync( 5437): CP2 cleanup done, kept= duration=832 ms
I/AppUp4:DB( 6745):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6745):  SDK version = 0
I/AppUp4:DB( 6745):  beforefinger == newfinger no write in DB
I/NotificationService(  848): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  848): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  848): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/AppUp4:AppBoxApplication( 6745): AppBoxApplication onCreate()
I/PeopleContactsSync( 5437): ===CP2 sync finished, success=true, time=895,0,0,0,0,0 rc=0,0,0,0 av=0,0,0,0,0,0 [5005f081]
I/BackupManagerService(  848): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/AppUp4:CustModeStarterReceiver( 6745): onReceive
I/AppUp4:CustModeStarterReceiver( 6745): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,V/BackupManagerService(  848): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  848): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@16feead9
D/AppUp4:CustFacade( 6745): Context : android.app.ReceiverRestrictedContext@3c606f9c
D/AppUp4:CustFacade( 6745): isCustomizationCompleted : false
D/LCardEmulationManager( 1854): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1854): getDefaultRoute
D/AppUp4:CustFacade( 6745): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6745): begin check event
I/AppUp4:CustModeStarterReceiver( 6745): Event For Nothing, skip.
,I/PeopleSync( 5437): ***Sync finished***, duration: 6471 [5005f081]
,W/System  ( 6661): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6661): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  848): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6770 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager(  848): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  848): Process com.android.chrome (pid 6522) has died
,I/BackgroundMemoryTrimmer( 2022): Trimming objects from memory, since app is in the background.
I/art     ( 6718): CheckpointMarkThreadRoots callback created = 0xb042d430
I/PhoneApp( 1782): onTrimMemory: 10
I/PhoneApp( 1782): trim memory
D/UEI.SmartControl( 6643): Service.onTrimMemory: 60
E/UEI.SmartControl( 6643): Setup service releasing memory...
W/ResourcesManager( 6770): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     ( 6718): CheckpointMarkThreadRoots callback created = 0xb042d410
W/ResourcesManager( 6770): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6770): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/CertBlacklister(  848): Certificate blacklist changed, updating...
,I/CertBlacklister(  848): Certificate blacklist updated
,I/GservicesProvider( 5890): main difference update completed
D/LocationManagerService(  848): getAllProviders()=[passive, gps, network]
I/CheckinRequestBuilder( 5437): Checkin reason type: 8 attempt count: 1
D/Ulp_jni (  848): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,D/Ulp_jni (  848): JNI:system_update. Event-4
E/ActivityThread( 5437): Failed to find provider info for com.google.android.wearable.settings
D/LocationManagerService(  848): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  848): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  848): JNI:system_update. Event-4
W/ResourceType(  848): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/AppConfig( 6770): Total System Memory = 906309632
,I/GalleryUtils( 6770): Application Heap = 96 MB
I/AppConfig( 6770): App Tier : NOT_DEF
D/SystemHelper( 6770): region [EU], country [EU], operator [OPEN], sub-operator []
I/art     ( 5890): Explicit concurrent mark sweep GC freed 9368(455KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.596ms total 31.867ms
,I/[LGHome]EVENT( 1946): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/ActivityManager(  848): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6794 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/NotificationManager(  848): android: cancelAsUser(148851818) by android
,I/GCoreNlp( 1749): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  848): applying state to connected service
,W/BaseAppContext( 5437): Using Auth Proxy for data requests.
,W/BaseAppContext( 5437): Using Auth Proxy for data requests.
W/ResourcesManager( 6794): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6794): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6794): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6794): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6794): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/BaseAppContext( 5437): Using Auth Proxy for data requests.
,I/NotificationManager(  848): android: cancelAsUser(1500439826) by android
,I/ActivityManager(  848): Start proc com.google.android.music:main for service com.google.android.music/.sync.SyncAdapterService: pid=6814 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/BaseAppContext( 5437): Using Auth Proxy for data requests.
,W/BaseAppContext( 5437): Using Auth Proxy for data requests.
,W/BaseAppContext( 5437): Using Auth Proxy for data requests.
,I/SystemConfig( 6794): BUILD Country: EU
I/SystemConfig( 6794): BUILD Operator: OPEN
W/BaseAppContext( 5437): Using Auth Proxy for data requests.
,I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/CheckinRequestBuilder( 5437): Classify the device as Phone.
,I/MusicStore( 6814): Database version: 120
,I/ActivityManager(  848): Process com.google.android.gms:car (pid 6503) has died
,I/SystemConfig( 6794): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6794): existFile = false
,I/SystemConfig( 6794): canReadFile = false
I/SystemConfig( 6794): systemFeature RCS result false
D/SystemConfig( 6794): refreshRcsSupport() :false
I/ActivityManager(  848): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6843 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/NotificationManager(  848): android: cancelAsUser(-379682945) by android
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6814): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/CheckinTask( 5437): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5437): Checking schedule, now: 1456908897297 next: 1457436146270
I/CheckinService( 5437): active receiver: disabled
,D/CheckinService( 5437): Recording last checkin time for package unspecified as 1456908897339
,I/LockScreenSettings( 6843): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/ActivityManager(  848): Start proc com.lge.qmemoplus for service com.lge.qmemoplus/.network.googledrive.DriveSyncService: pid=6861 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
D/LockScreenSettings( 6843): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6843): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6843): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6843): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
,D/LockScreenSettings( 6843): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
W/ResourcesManager( 6861): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6814): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6814): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/UpdateIcingCorporaServi( 2022): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/ResourcesManager( 6814): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6814): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/App     ( 6861): [App][onCreate()] 4.40.23
,V/JNIHelp ( 6814): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/PackageBroadcastService( 5437): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 5437): Null package name or gms related package.  Ignoreing.
W/ActivityThread( 6814): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6814): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@13a159b7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6814): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6814): GMSCore installation verified
D/ChimeraCfgMgr( 5437): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5437): Module APK com.google.android.play.games already loaded
,I/ConfigStore( 6814): Config Database version: 1
I/UpdateIcingCorporaServi( 2022): UpdateCorporaTask done [took 139 ms] updated apps [took 139 ms] 
I/ActivityManager(  848): Process com.lge.qremote (pid 6603) has died
,W/PlaySystemBroadcastReceiver( 5437): Processed handlePeopleChanged at 106858
,D/UEI.SmartControl( 6643): Internal timer expired: 1
,D/UEI.SmartControl( 6643): Service.onUnbind: IControl
D/UEI.SmartControl( 6643): Service.onDestroy
W/System.err( 6643): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@3fe9af46
W/System.err( 6643): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
,W/System.err( 6643): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 6643): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 6643): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 6643): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 6643): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2983)
W/System.err( 6643): 	at android.app.ActivityThread.access$2200(ActivityThread.java:155)
W/System.err( 6643): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1426)
W/System.err( 6643): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6643): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6643): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6643): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6643): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6643): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6643): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6643): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@3fe9af46
D/UEI.SmartControl( 6643): Shutdown IRRCPlayer... 
W/irrc_jni( 6643): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6643): ~IrrcClient ++ 
D/irrcClient( 6643): ~IrrcClient -- 
W/irrc_jni( 6643): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6643): Blaster closed
D/UEI.SmartControl( 6643): Blaster closed
D/UEI.SmartControl( 6643): Shut down QS...
D/UEI.SmartControl( 6643): Stopped file observer...
,I/UEI.SmartControl( 6643): QS lib stop result = true
D/UEI.SmartControl( 6643): QS shutdown complete
D/AccountManager( 6861): setSyncFrequency
,I/ActivityManager(  848): Process com.android.gallery3d (pid 6770) has died
,I/BackgroundMemoryTrimmer( 2022): Trimming objects from memory, since app is in the background.
I/PhoneApp( 1782): onTrimMemory: 10
I/PhoneApp( 1782): trim memory
D/DriveSyncService( 6861): onCreate
D/DriveSyncService( 6861): onBind
,I/ActivityManager(  848): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=6890 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,I/art     (  299): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 305us total 21.021ms
,I/art     (  299): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 25.120ms
,I/art     (  299): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 21.690ms
,I/MediaRouter( 6814): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
I/Icing   ( 5437): updateResources: need to parse f{com.google.android.gms}
,D/ChimeraCfgMgr( 5437): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 5437): Module APK com.google.android.play.games already loaded
I/art     (  848): Explicit concurrent mark sweep GC freed 27010(1359KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 2.472ms total 251.451ms
,D/DriveSyncAdapter( 6861): onPerformSync() START
D/DriveSyncAdapter( 6861): Not added account. Stop
I/ActivityManager(  848): Process com.uei.lg.quicksetsdk.lite (pid 6643) has died
,I/BackgroundMemoryTrimmer( 2022): Trimming objects from memory, since app is in the background.
I/PhoneApp( 1782): onTrimMemory: 10
I/PhoneApp( 1782): trim memory
I/NotificationManager(  848): android: cancelAsUser(1312559638) by android
,I/GHttpClientFactory( 6814): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6814): Using platform SSLCertificateSocketFactory
,I/NetworkMonitor( 6814): type=WIFI subType= reason=null isConnected=true
I/MusicLifecycle( 6814): Sync started
,I/art     ( 5890): Explicit concurrent mark sweep GC freed 3447(145KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 691us total 42.072ms
,W/BaseAppContext( 5437): Using Auth Proxy for data requests.
W/BaseAppContext( 5437): Using Auth Proxy for data requests.
,I/ActivityManager(  848): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=6923 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
,I/NetworkMonitor( 6814): type=WIFI subType= reason=null isConnected=true
,I/GHttpClientFactory( 6814): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 6814): Using platform SSLCertificateSocketFactory
,I/art     ( 6814): CheckpointMarkThreadRoots callback created = 0xb042d380
,I/art     ( 6814): CheckpointMarkThreadRoots callback created = 0xb042d340
,I/art     ( 5437): Explicit concurrent mark sweep GC freed 33346(2MB) AllocSpace objects, 19(304KB) LOS objects, 24% free, 14MB/19MB, paused 2.147ms total 134.645ms
,W/BaseAppContext( 5437): Using Auth Proxy for data requests.
,W/BaseAppContext( 5437): Using Auth Proxy for data requests.
,W/BaseAppContext( 5437): Using Auth Proxy for data requests.
W/BaseAppContext( 5437): Using Auth Proxy for data requests.
W/BaseAppContext( 5437): Using Auth Proxy for data requests.
,I/NotificationManager( 6814): com.google.android.music: cancel(1061) by com.google.android.music
,I/RemindersSync( 5437): Found sync condition that we don't recognize, aborting. [T SyncAdapterThread-1:id=736:priority=5:group=main]
,E/UpdateRequestReceiver( 6923): Received malformed URL while handling Gservices.CHANGED_ACTION
I/NotificationManager(  848): android: cancelAsUser(898701380) by android
,I/UpdateFetcherService( 6923): Update started
,E/UpdateRequestReceiver( 6923): Received malformed URL while handling Gservices.CHANGED_ACTION
E/UpdateRequestReceiver( 6923): Received malformed URL while handling Gservices.CHANGED_ACTION
,D/DownloadManager( 3065): DB Update : deleted 1
,V/DownloadManager( 3065): DownloadService onCreate
I/DownloadManager( 3065): in removeSpuriousFiles
I/NotificationManager( 3065): com.android.providers.downloads: cancelAll by com.android.providers.downloads
W/art     ( 6923): No such thread id for suspend: 15
W/art     ( 6923): No such thread id for suspend: 15
,V/DownloadManager( 3065): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3065): created cursor android.database.sqlite.SQLiteCursor@d603000 on behalf of 3065
I/DownloadManager( 3065): in trimDatabase
V/DownloadManager( 3065): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3065): created cursor android.database.sqlite.SQLiteCursor@2094a039 on behalf of 3065
V/DownloadManager( 3065): initiating download with UID 10003
I/DownloadManager( 3065): insert() mimeType is null / COLUMN_TYPESORT_INDEX =100
E/UpdateRequestReceiver( 6923): Received malformed URL while handling Gservices.CHANGED_ACTION
,V/DownloadManager( 3065): DownloadService onStartCommand
V/DownloadManager( 3065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3065): DownloadService onStartCommand
,V/DownloadManager( 3065): created cursor android.database.sqlite.SQLiteCursor@11984c2c on behalf of 3065
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  848): android: cancelAsUser(2) by android
,I/GservicesUpdateTask( 2022): Updating Gservices keys
,I/CheckinService( 5437): Checkin interval check for package: unspecified last checkin: 1456908897339 min interval config: 0 actual interval: 1983
V/DownloadManager( 3065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3065): created cursor android.database.sqlite.SQLiteCursor@3b1606f5 on behalf of 3065
,D/DownloadManager( 3065): DB Update : status 192
,I/CheckinService( 5437): Checking schedule, now: 1456908899381 next: 1457436146270
I/CheckinService( 5437): active receiver: disabled
I/SystemUpdateService( 5437): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 5437): onCreate
,D/libc-netbsd( 6814): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6814): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6814): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6814): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  271): [LG DATA] No such appUid: 10081
D/DnsProxyListener(  271): App 10081 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/SystemUpdateService( 5437): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 5437): cancelUpdate (empty URL)
I/SystemUpdateService( 5437): active receiver: disabled
,V/DownloadManager( 3065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3065): created cursor android.database.sqlite.SQLiteCursor@211e52fb on behalf of 3065
V/DownloadManager( 3065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
I/art     ( 5890): Explicit concurrent mark sweep GC freed 3658(153KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.437ms total 30.943ms
V/DownloadManager( 3065): created cursor android.database.sqlite.SQLiteCursor@53ff18 on behalf of 3065
,D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out( 6814): propertyValue:false
V/DownloadManager( 3065): processing updated download 77, status: 192
V/DownloadManager( 3065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
I/NotificationManager( 5437): com.google.android.gms: cancel(2130838165) by com.google.android.gms
V/DownloadManager( 3065): created cursor android.database.sqlite.SQLiteCursor@200d1d71 on behalf of 3065
I/NotificationManager( 5437): com.google.android.gms: cancel(2130838166) by com.google.android.gms
I/DownloadManager( 3065): Download 77 starting
,I/DownloadManager( 3065): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
I/DownloadManager( 3065): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
D/DownloadManager( 3065): fileSize : -1state.mContinuingDownload :false
I/art     ( 1749): Explicit concurrent mark sweep GC freed 38509(2MB) AllocSpace objects, 14(224KB) LOS objects, 40% free, 14MB/23MB, paused 3.267ms total 230.633ms
,D/libc-netbsd( 3065): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 3065): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 3065): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 3065): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10019
D/DnsProxyListener(  271): App 10019 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
,D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out( 3065): propertyValue:false
D/libc-netbsd( 3065): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 3065): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,I/jxcore-log( 4586): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 4586): 
,I/jxcore-log( 4586): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
I/jxcore-log( 4586): 
,D/libc-netbsd( 6814): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6814): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/jxcore-log( 4586): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 4586): 
W/BaseAppContext( 1749): Using Auth Proxy for data requests.
,D/LocSvc_java(  848): requestTime failed
D/LocSvc_java(  848): Sending msg: 10 arg1:0 arg2:1
D/libc-netbsd(  848): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  848): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  848): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  848): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  271): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out(  848): propertyValue:false
I/DownloadManager( 3065): Ignoring Content-Length since Transfer-Encoding is also defined
V/DownloadManager( 3065): Content-Disposition: null
V/DownloadManager( 3065): Content-Length: -1
V/DownloadManager( 3065): Content-Location: null
V/DownloadManager( 3065): Content-Type: text/plain
V/DownloadManager( 3065): ETag: null
V/DownloadManager( 3065): Transfer-Encoding: chunked
V/DownloadManager( 3065): X-Oma-Drm-Separate-Delivery: null
V/DownloadManager( 3065): Min update size = 16384
V/DownloadManager( 3065): getting filename from uri
I/DownloadManager( 3065): in verifySpace, destination: 2, path: 02022016-sms-blacklist-metadata.txt, length: 0
,V/DownloadManager( 3065): keeping extension
V/DownloadManager( 3065): target file: /data/data/com.android.providers.downloads/cache/02022016-sms-blacklist-metadata.txt
I/DowlnoadThread( 3065): updateDatabaseFromHeaders mMimeType =text/plainfilename=/data/data/com.android.providers.downloads/cache/02022016-sms-blacklist-metadata.txt
,I/DownloadProvider.LgeUtils( 3065): getTypeSortIndex mimeType is =text/plain / filename=/data/data/com.android.providers.downloads/cache/02022016-sms-blacklist-metadata.txt
I/DownloadProvider.LgeUtils( 3065): getTypeSortIndex mediaType is =text / extension=txt
I/DownloadProvider.LgeUtils( 3065): getTypeSortIndex  index is =40
I/DowlnoadThread( 3065): updateDatabaseFromHeaders  COLUMN_TYPESORT_INDEX =40
V/DownloadManager( 3065): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3065): created cursor android.database.sqlite.SQLiteCursor@1215f4c4 on behalf of 3065
E/BaseAppContext( 1749): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
D/DownloadManager( 3065): DB Update : title 02022016-sms-blacklist-metadata.txt
,D/DownloadManager( 3065): DB Update : _data /data/data/com.android.providers.downloads/cache/02022016-sms-blacklist-metadata.txt
D/DownloadManager( 3065): DB Update : total_bytes -1
D/DownloadManager( 3065): DB Update : type_sort_index 40
D/DownloadManager( 3065): DB Update : mimetype text/plain
V/DownloadManager( 3065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 3065): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
V/DownloadManager( 3065): created cursor android.database.sqlite.SQLiteCursor@202362e2 on behalf of 3065
I/LGDrmClient( 3065): _DRM_ServiceGet() : Bind lgdrm service
,V/ILGDrmService(  280): eDRM_GetObjectInfo +++
,V/ILGDrmService(  280): eDRM_GetObjectInfo ---
D/DownloadManager( 3065): ID : 77, start SingleThread download.
V/DownloadManager( 3065): ID : 77, transferData threadNum -1 start for http://www.gstatic.com/android/config_update/02022016-sms-blacklist-metadata.txt
D/DownloadManager( 3065): ID : 77, transferData threadNum -1 is completed
D/DownloadManager( 3065): DB Update : total_bytes 384
D/DownloadManager( 3065): DB Update : current_bytes 384
,V/DownloadManager( 3065): processing updated download 77, status: 192
V/DownloadManager( 3065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
I/art     ( 5890): Explicit concurrent mark sweep GC freed 2849(111KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 479us total 27.003ms
V/DownloadManager( 3065): created cursor android.database.sqlite.SQLiteCursor@13fe2673 on behalf of 3065
,V/LFT     ( 3065): notifyThroughDatabase after updateDB  id :  77, mstatus : 192, largemode : 0, settingMode : 0
V/DownloadManager( 3065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/DownloadManager( 3065): notifyThroughDatabase start id : 77 name : /data/data/com.android.providers.downloads/cache/02022016-sms-blacklist-metadata.txt status : 200
V/DownloadManager( 3065): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3065): created cursor android.database.sqlite.SQLiteCursor@22df9930 on behalf of 3065
V/DownloadManager( 3065): created cursor android.database.sqlite.SQLiteCursor@250109a9 on behalf of 3065
D/DownloadManager( 3065): DB Update : numfailed 0
D/DownloadManager( 3065): DB Update : method 0
D/DownloadManager( 3065): DB Update : _data /data/data/com.android.providers.downloads/cache/02022016-sms-blacklist-metadata.txt
D/DownloadManager( 3065): DB Update : lastmod 1456908899825
D/DownloadManager( 3065): DB Update : status 200
D/DownloadManager( 3065): DB Update : mimetype text/plain
,V/DownloadManager( 3065): processing updated download 77, status: 192
V/DownloadManager( 3065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 3065): Download 77 finished with status SUCCESS
V/DownloadManager( 3065): created cursor android.database.sqlite.SQLiteCursor@3418cb2e on behalf of 3065
D/DownloadManager( 3065): checkStatusUpdate current status 192 is changed to 200
D/DownloadManager( 3065): checkStatusUpdate return true mID : mStatus = 77 : 200 => 200
W/DataBroker( 5437): No player ID found and calling context is not the dest app
,V/DownloadManager( 3065): DownloadService onDestroy
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/jxcore-log( 4586): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
I/jxcore-log( 4586): 
,D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out( 1749): propertyValue:false
,I/art     ( 5437): Explicit concurrent mark sweep GC freed 14151(961KB) AllocSpace objects, 10(160KB) LOS objects, 24% free, 15MB/20MB, paused 2.835ms total 130.344ms
,D/libc-netbsd( 6814): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6814): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WeatherService( 2575): 2 : TimeTick Intent has been received, Time(hour:min:sec) 9:55:0
,D/WeatherService( 2575): 2 : TimeTick Intent And Screen On
D/WeatherService( 2575): 2 : SDK version : 21
W/ActivityManager(  848): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2575): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2575): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2575): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2575): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2575): 2 : This is isUpdating : false
D/WeatherService( 2575): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2575): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2575): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2575): 2 : Fixed theme : optimus
,D/WeatherReflect( 2575): 2 : Map key string is -2
I/[SystemUI]TimeTickManager( 1361): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1361): called onTimeUpdated()
,D/lim     ( 2575): 2 : time = 09:55
D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Icing   ( 5437): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/SQLiteConnectionPool( 5437): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/WeatherReflect( 2575): Model Name : LG-D722
D/WeatherTheme( 2575): 2 : Different view - status_min_formatted : 54 != 55
D/WeatherTheme( 2575): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
,I/[SystemUI]Clock( 1361): called onTimeUpdated()
D/WeatherReflect( 2575): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
I/LgeClockWidgetControlView( 1361): called onTimeUpdated()
I/[SystemUI]DateView( 1361): called onTimeUpdated()
D/Theme   ( 2575): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2575): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2575): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2575): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/[SystemUI]DateView( 1361): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1361): handleTimeUpdate
D/Weather4x2_optimus( 2575): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2575): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2575): forecast size is 0
,D/Theme   ( 2575): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2575): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2575): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2575): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2575): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2575): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2575): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2575): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2575): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2575): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2575): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2575): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2575): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2575): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2575): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2575): url is : null
D/Theme   ( 2575): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2575): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2575): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2575): 2 : update view, appWidgetId: 2
D/WeatherService( 2575): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 9:55:0
,D/SystemUpdateService( 5437): onDestroy
I/Icing   ( 5437): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,E/DynamiteModule( 5437): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 5437): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /vendor/lib, /system/lib]]
E/DynamiteModule( 5437): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 5437): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/DynamiteModule( 5437): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/DynamiteModule( 5437): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 5437): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 5437): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 5437): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 5437): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 5437): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 5437): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2663)
E/DynamiteModule( 5437): 	at android.app.ActivityThread.access$1700(ActivityThread.java:155)
E/DynamiteModule( 5437): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1400)
E/DynamiteModule( 5437): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 5437): 	at android.os.Looper.loop(Looper.java:135)
E/DynamiteModule( 5437): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/DynamiteModule( 5437): 	at java.lang.reflect.Method.invoke(Native Method)
E/DynamiteModule( 5437): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/DynamiteModule( 5437): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/DynamiteModule( 5437): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/DynamiteModule( 5437): 	Suppressed: java.lang.ClassNotFoundException: com.google.android.gms.chimera.container.DynamiteLoaderImpl
E/DynamiteModule( 5437): 		at java.lang.Class.classForName(Native Method)
E/DynamiteModule( 5437): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/DynamiteModule( 5437): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/DynamiteModule( 5437): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/DynamiteModule( 5437): 		... 17 more
E/DynamiteModule( 5437): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
I/DynamiteModule( 5437): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
I/DynamiteModule( 5437): Selected local version of com.google.android.gms.flags
,I/NotificationManager( 5437): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/SystemEventReceiver( 5437): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 5437): Updating ocr activity enabled=false
I/[LgeWidgetLib]LgeAppWidgetHostView( 1946): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/NotificationManager(  848): android: cancelAsUser(2) by android
,I/art     (  848): Explicit concurrent mark sweep GC freed 21063(940KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.361ms total 159.469ms
I/NotificationManager( 1749): com.google.android.gms: cancel(0) by com.google.android.gms
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1946): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/MusicSyncAdapter( 6814): Will attempt periodic sync for account: Account {name=thalitester@gmail.com, type=com.google}
I/MusicSyncAdapter( 6814): Periodic update
,I/ActivityManager(  848): Process com.android.contacts (pid 6794) has died
,D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out( 1749): propertyValue:false
I/NotificationManager(  848): android: cancelAsUser(-1123058983) by android
,W/ActivityManager(  848): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/art     ( 5890): Explicit concurrent mark sweep GC freed 2567(100KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 826us total 28.692ms
,W/MusicApiClient( 6814): Activity events list is null or empty. Skip reporting.
D/OcrModelManager( 5437): Updating downloaded model state (gservices changed)
I/MusicLifecycle( 6814): Sync ended
D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/NotificationManager(  848): android: cancelAsUser(-591465577) by android
I/MusicLifecycle( 6814): Sync started
,D/GCM     ( 1749): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  848): android: cancelAsUser(2) by android
,I/MusicSyncAdapter( 6814): Skipping periodic sync. Last sync was 1 seconds ago. Frequency: 86400
,I/art     ( 5890): Explicit concurrent mark sweep GC freed 2903(114KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 722us total 28.963ms
,W/MusicApiClient( 6814): Activity events list is null or empty. Skip reporting.
I/MusicLifecycle( 6814): Sync ended
,I/ActivityManager(  848): Killing 6661:com.google.android.talk/u0a61 (adj 15): empty #11
,I/NotificationManager(  848): android: cancelAsUser(-1123058983) by android
I/art     ( 1749): Explicit concurrent mark sweep GC freed 18202(1158KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 14MB/24MB, paused 7.692ms total 125.250ms
,W/libprocessgroup(  848): failed to open /acct/uid_10061/pid_6661/cgroup.procs: No such file or directory
,I/GCoreUlr( 1749): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/ActivityManager(  848): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7023 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/GCoreUlr( 1749): DispatchingService.onCreate()
,I/GCoreUlr( 1749): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,I/NotificationManager(  848): android: cancelAsUser(-1816247584) by android
,I/NotificationManager(  848): android: cancelAsUser(1222422273) by android
,I/GCoreUlr( 1749): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,W/ResourcesManager( 7023): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,E/Auth.Api.Credentials( 5437): [CredentialSyncAdapter] Unknown sync event.
,W/GeofencerStateMachine( 1749): Ignoring removeGeofence because network location is disabled.
,E/ctxmgr  ( 1749): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
I/NotificationManager(  848): android: cancelAsUser(-591465577) by android
I/ActivityManager(  848): Killing 6745:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  848): failed to open /acct/uid_10011/pid_6745/cgroup.procs: No such file or directory
,D/BluetoothManagerService(  848): Message: 20
D/BluetoothManagerService(  848): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@159a4e24:true
,D/BluetoothAdapterService(1072279366)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@28ecf7cc
D/BluetoothAdapterService(1072279366)( 2073): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@28ecf7cc
I/GCoreUlr( 1749): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,W/ctxmgr  ( 1749): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10006, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
E/ctxmgr  ( 1749): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
I/ActivityManager(  848): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7053 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/GCoreUlr( 1749): Unbound from all location providers
I/GCoreUlr( 1749): Place inference reporting - stopped
,I/GCoreUlr( 1749): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1749): Unbound from all location providers
I/GCoreUlr( 1749): Place inference reporting - stopped
I/GCoreUlr( 1749): DispatchingService.onDestroy()
,I/GCoreUlr( 1749): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 1749): Unbound from all location providers
I/GCoreUlr( 1749): Place inference reporting - stopped
D/PhoneMonitor( 7053): Register our PhoneStateListener
,V/SetupWizard( 7053): Connected to Gservices successfully
,D/PhoneMonitor( 7053): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
I/ActivityManager(  848): Killing 6843:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
V/TelephonyAutoProfiling( 7053): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7053): [parse] Load xml
V/TelephonyAutoProfiling( 7053): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7053): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7053): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  848): failed to open /acct/uid_10069/pid_6843/cgroup.procs: No such file or directory
,D/GCM     ( 1749): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1749): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
V/DownloadManager( 3065): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 77; sort is lastmod DESC.
,V/DownloadManager( 3065): created cursor android.database.sqlite.SQLiteCursor@b5d185c on behalf of 6923
V/DownloadManager( 3065): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 77; sort is lastmod DESC.
V/DownloadManager( 3065): created cursor android.database.sqlite.SQLiteCursor@27379765 on behalf of 6923
V/DownloadManager( 3065): initiating download with UID 10003
I/DownloadManager( 3065): insert() mimeType is null / COLUMN_TYPESORT_INDEX =100
,V/DownloadManager( 3065): DownloadService onCreate
,I/DownloadManager( 3065): in removeSpuriousFiles
V/DownloadManager( 3065): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/NotificationManager( 3065): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3065): created cursor android.database.sqlite.SQLiteCursor@1fea6c3a on behalf of 3065
V/DownloadManager( 3065): DownloadService onStartCommand
V/DownloadManager( 3065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 3065): in trimDatabase
V/DownloadManager( 3065): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3065): created cursor android.database.sqlite.SQLiteCursor@378f44e1 on behalf of 3065
,V/DownloadManager( 3065): created cursor android.database.sqlite.SQLiteCursor@36031206 on behalf of 3065
V/DownloadManager( 3065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3065): created cursor android.database.sqlite.SQLiteCursor@2570b0c7 on behalf of 3065
D/DownloadManager( 3065): DB Update : status 192
V/DownloadManager( 3065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3065): created cursor android.database.sqlite.SQLiteCursor@255a4e1d on behalf of 3065
V/DownloadManager( 3065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3065): processing updated download 78, status: 192
V/DownloadManager( 3065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3065): created cursor android.database.sqlite.SQLiteCursor@32ae4892 on behalf of 3065
V/DownloadManager( 3065): created cursor android.database.sqlite.SQLiteCursor@213d9263 on behalf of 3065
W/ContextImpl( 3378): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
I/DownloadManager( 3065): Download 78 starting
,I/DownloadManager( 3065): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
I/DownloadManager( 3065): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
D/DownloadManager( 3065): fileSize : -1state.mContinuingDownload :false
D/libc-netbsd( 3065): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 3065): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 3065): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 3065): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10019
D/DnsProxyListener(  271): App 10019 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
,I/System.out( 3065): propertyValue:false
D/libc-netbsd( 3065): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 3065): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/DownloadManager( 3065): Ignoring Content-Length since Transfer-Encoding is also defined
V/DownloadManager( 3065): Content-Disposition: null
,V/DownloadManager( 3065): Content-Length: -1
V/DownloadManager( 3065): Content-Location: null
V/DownloadManager( 3065): Content-Type: text/plain
V/DownloadManager( 3065): ETag: null
V/DownloadManager( 3065): Transfer-Encoding: chunked
V/DownloadManager( 3065): X-Oma-Drm-Separate-Delivery: null
,V/DownloadManager( 3065): Min update size = 16384
V/DownloadManager( 3065): getting filename from uri
I/DownloadManager( 3065): in verifySpace, destination: 2, path: 02022016-sms-blacklist.txt, length: 0
V/DownloadManager( 3065): keeping extension
V/DownloadManager( 3065): target file: /data/data/com.android.providers.downloads/cache/02022016-sms-blacklist.txt
I/DowlnoadThread( 3065): updateDatabaseFromHeaders mMimeType =text/plainfilename=/data/data/com.android.providers.downloads/cache/02022016-sms-blacklist.txt
I/DownloadProvider.LgeUtils( 3065): getTypeSortIndex mimeType is =text/plain / filename=/data/data/com.android.providers.downloads/cache/02022016-sms-blacklist.txt
I/DownloadProvider.LgeUtils( 3065): getTypeSortIndex mediaType is =text / extension=txt
I/DownloadProvider.LgeUtils( 3065): getTypeSortIndex  index is =40
I/DowlnoadThread( 3065): updateDatabaseFromHeaders  COLUMN_TYPESORT_INDEX =40
V/DownloadManager( 3065): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6814): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6814): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
,I/art     (  848): Explicit concurrent mark sweep GC freed 25344(1240KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 23MB/34MB, paused 2.209ms total 150.440ms
,V/DownloadManager( 3065): created cursor android.database.sqlite.SQLiteCursor@19645bde on behalf of 3065
D/DownloadManager( 3065): DB Update : title 02022016-sms-blacklist.txt
D/DownloadManager( 3065): DB Update : _data /data/data/com.android.providers.downloads/cache/02022016-sms-blacklist.txt
,D/DownloadManager( 3065): DB Update : total_bytes -1
D/DownloadManager( 3065): DB Update : type_sort_index 40
D/DownloadManager( 3065): DB Update : mimetype text/plain
V/DownloadManager( 3065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 3065): activeInfo is not null,  NetworkInfo.getTypeName() = WIFI
V/ILGDrmService(  280): eDRM_GetObjectInfo +++
D/LGDRM   (  280): [DRM] Part_DetectType() : Buffer contains XML Prologue
,V/DownloadManager( 3065): created cursor android.database.sqlite.SQLiteCursor@f6cf1bf on behalf of 3065
,D/LGDRM   (  280): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
V/ILGDrmService(  280): eDRM_GetObjectInfo ---
D/DownloadManager( 3065): ID : 78, start SingleThread download.
V/DownloadManager( 3065): ID : 78, transferData threadNum -1 start for http://www.gstatic.com/android/config_update/02022016-sms-blacklist.txt
D/DownloadManager( 3065): ID : 78, transferData threadNum -1 is completed
D/DownloadManager( 3065): DB Update : total_bytes 13698
D/DownloadManager( 3065): DB Update : current_bytes 13698
I/MusicLeanback( 6814): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6814): Stop autocaching.
V/DownloadManager( 3065): processing updated download 78, status: 192
V/DownloadManager( 3065): starting query, database is not null; projection[0] is status; selection is null; selectionArgs is null; sort is null.
V/LFT     ( 3065): notifyThroughDatabase after updateDB  id :  78, mstatus : 192, largemode : 0, settingMode : 0
D/DownloadManager( 3065): notifyThroughDatabase start id : 78 name : /data/data/com.android.providers.downloads/cache/02022016-sms-blacklist.txt status : 200
,V/DownloadManager( 3065): starting query, database is not null; projection[0] is title; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3065): created cursor android.database.sqlite.SQLiteCursor@29d623d5 on behalf of 3065
V/DownloadManager( 3065): created cursor android.database.sqlite.SQLiteCursor@1ad657ea on behalf of 3065
D/DownloadManager( 3065): DB Update : numfailed 0
D/DownloadManager( 3065): DB Update : method 0
D/DownloadManager( 3065): DB Update : _data /data/data/com.android.providers.downloads/cache/02022016-sms-blacklist.txt
D/DownloadManager( 3065): DB Update : lastmod 1456908903005
D/DownloadManager( 3065): DB Update : status 200
D/DownloadManager( 3065): DB Update : mimetype text/plain
V/DownloadManager( 3065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3065): created cursor android.database.sqlite.SQLiteCursor@2508eadb on behalf of 3065
I/DownloadManager( 3065): Download 78 finished with status SUCCESS
,V/DownloadManager( 3065): DownloadService onDestroy
,I/MusicLeanback( 6814): Conditions not met for autocaching. okToAttempt=false
,I/MusicLeanback( 6814): Stop autocaching.
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6814): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6814): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
I/ActivityManager(  848): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7100 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7023): Create singleton instance
,I/AudioManager( 7023): getMode name:com.lge.qremote
,D/UEI.SmartControl( 7100): Quickset Services start...
,I/UEI.SmartControl( 7100): Manufacture = LGE
D/UEI.SmartControl( 7100): File observer start...
,E/UEI.SmartControl( 7100): IR Port is disabled: false
D/UEI.SmartControl( 7100): Starting file observer...
D/UEI.SmartControl( 7100): Extracting JNI libs...
D/UEI.SmartControl( 7100): --- this system supports 32-bit or 64-bit only
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6814): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
D/WearableService( 1749): callingUid 10006, callindPid: 1749
,I/MusicLeanback( 6814): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6814): Stop autocaching.
,V/DownloadManager( 3065): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 78; sort is lastmod DESC.
V/DownloadManager( 3065): created cursor android.database.sqlite.SQLiteCursor@36622851 on behalf of 6923
V/DownloadManager( 3065): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (_id = ? ) AND deleted != '1'; selectionArgs[0] is 78; sort is lastmod DESC.
,V/DownloadManager( 3065): created cursor android.database.sqlite.SQLiteCursor@fba08b6 on behalf of 6923
,I/UpdateFetcherService( 6923): Update downloaded, starting installation
,I/UpdateFetcherService( 6923): doneInstall
D/DownloadManager( 3065): DB Update : deleted 1
V/DownloadManager( 3065): DownloadService onCreate
I/DownloadManager( 3065): in removeSpuriousFiles
V/DownloadManager( 3065): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,I/NotificationManager( 3065): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3065): created cursor android.database.sqlite.SQLiteCursor@13a159b7 on behalf of 3065
E/GmsUtils( 6814): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/DownloadManager( 3065): in trimDatabase
V/DownloadManager( 3065): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3065): DownloadService onStartCommand
V/DownloadManager( 3065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3065): created cursor android.database.sqlite.SQLiteCursor@1455fa42 on behalf of 3065
E/GmsUtils( 6814): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 6814): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 6814): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
V/DownloadManager( 3065): created cursor android.database.sqlite.SQLiteCursor@2be7da53 on behalf of 3065
,E/GmsUtils( 6814): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6814): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6814): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/cache
D/DownloadManager( 3065): deleteFileIfExists() deleting /data/data/com.android.providers.downloads/cache/02022016-sms-blacklist-metadata.txt
,D/DownloadManager( 3065): deleteFileIfExists() deleting /data/data/com.android.providers.downloads/cache/02022016-sms-blacklist.txt
I/ConfigUpdateInstallReceiver(  848): Found new update, installing...
,V/DownloadManager( 3065): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3065): created cursor android.database.sqlite.SQLiteCursor@56f6f90 on behalf of 3065
,V/DownloadManager( 3065): DownloadService onDestroy
,I/ConfigUpdateInstallReceiver(  848): Installation successful
D/UEI.SmartControl( 7100): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7100): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7100): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/MusicWidget( 2533): mDelayedStopHandler : unbind
I/MusicBrowser( 2095): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2095): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2095): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2095): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2095): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2095): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/UEI.SmartControl( 7100): --- Selecting new region: 2
I/UEI.SmartControl( 7100): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7100): Platform has CIR...
I/MusicBrowser( 2095): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
D/UEI.SmartControl( 7100): NO CIR support, need to check package...
I/MusicBrowser( 2095): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/UEI.SmartControl( 7100): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7100): QS Service created
,I/MediaFocusControl(  848):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@f1f0291com.lge.music.MediaPlaybackService$6@302275f6
D/MusicBrowser( 2095): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2095): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2095): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2095): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
E/UEI.SmartControl( 7100): QS start get config
I/MusicBrowser( 2095): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@b2507
I/MusicBrowser( 2095): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2095): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2095): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2095): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2095): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2095): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2095): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2095): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2095): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2095): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2095): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2095): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2095): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2095): reset
,V/MediaPlayer[Native]( 2095): setListener
V/MediaPlayer[Native]( 2095): disconnect
V/MediaPlayer[Native]( 2095): destructor
D/UEI.SmartControl( 7100): Loading JNI Libs...
,D/UEI.SmartControl( 7100):  configuring local db...
V/AudioFlinger(  275): releasing 19 from 2095 for -1
V/AudioFlinger(  275):  decremented refcount to 0
V/AudioFlinger(  275): purging stale effects
V/MediaPlayer[Native]( 2095): disconnect
D/MusicBrowser( 2095): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2095): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2095): [SmartShareManagerClient] smartshare client enabled
,I/MusicBrowser( 2095): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2095): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2095): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2095): [SmartShareManagerClient] unregisterListener: 820076023
W/SmartShareClient( 2095): [SmartShareManagerClient] unregisterListener invalid listener: 820076023
I/SmartShareClient( 2095): [SmartShareManagerClient] terminate service: 2095/MediaPlaybackService/96026021
E/HomeCloudIF( 2095): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2095): [SmartShareManagerClient] unbindService context:android.app.Application@1ea07464
V/CloudHub( 2095): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
,V/CloudHub( 2095): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2095): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
,I/MusicBrowser( 2095): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2095): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  848): Killing 6718:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/CloudHub( 2095): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29997
W/libprocessgroup(  848): failed to open /acct/uid_10086/pid_6718/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 7100):  ---- Has DB8: true
,D/UEI.SmartControl( 7100): QS start statue = true Error code = 0
,D/UEI.SmartControl( 7100): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7100): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7100): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7100): IRRCPlayer_nativeInit ++ 
,D/irrcClient( 7100): IrrcClient ++ 
D/irrcClient( 7100): getIrrcService ++ 
D/irrcClient( 7100): getIrrcService -- 
D/irrcClient( 7100): IrrcClient -- 
W/irrc_jni( 7100): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7100): Services init done
,I/UEI.SmartControl( 7100): Device manager: loading config....
D/UEI.SmartControl( 7100): QS Service init finished
D/UEI.SmartControl( 7100): QS Service version name: 0.1.73
D/UEI.SmartControl( 7100): QS Service version code: 1073
D/UEI.SmartControl( 7100): Service requested: Control
D/UEI.SmartControl( 7100): Config is loaded...
D/UEI.SmartControl( 7100):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7100): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 7100): Request IControl service: devices are loaded...
D/UEI.SmartControl( 7100): Internal service binding...
,D/UEI.SmartControl( 7100): -----IControl: 11
D/UEI.SmartControl( 7100): Caller: com.lge.qremote
D/UEI.SmartControl( 7100): ------------ IControl registerCallback...
I/UEI.SmartControl( 7100): Registering callback...
D/UEI.SmartControl( 7100): -----IControl: 19
D/UEI.SmartControl( 7100): Caller: com.lge.qremote
I/UEI.SmartControl( 7100): Registering Services Ready callback...
I/UEI.SmartControl( 7100): Notify client services are ready...
D/UEI.SmartControl( 7100): -----IControl: 8
,D/UEI.SmartControl( 7100): Caller: com.lge.qremote
I/AudioManager( 7023): getMode name:com.lge.qremote
I/ActivityManager(  848): Killing 6890:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,I/ActivityManager(  848): Killing 6861:com.lge.qmemoplus/1000 (adj 15): empty #12
,W/libprocessgroup(  848): failed to open /acct/uid_10009/pid_6890/cgroup.procs: No such file or directory
,W/libprocessgroup(  848): failed to open /acct/uid_1000/pid_6861/cgroup.procs: No such file or directory
,I/AudioManager( 7023): getMode name:com.lge.qremote
I/AudioManager( 7023): getMode name:com.lge.qremote
,I/jxcore-log( 4586): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
I/jxcore-log( 4586): 
,I/jxcore-log( 4586): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
I/jxcore-log( 4586): 
,I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
D/sensors_hal_Time(  848): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  848): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  848): tsOffsetIs: Apps: 113729949910; DSPS: 3824916; Offset : -3004287394
,I/jxcore-log( 4586): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
I/jxcore-log( 4586): 
,I/jxcore-log( 4586): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
I/jxcore-log( 4586): 
,I/jxcore-log( 4586): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4586): 
,I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/CheckinService( 5437): Done disabling old GoogleServicesFramework version
,I/jxcore-log( 4586): INFO thaliMobileNativeWrapper networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
I/jxcore-log( 4586): 
,I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/AlarmManager(  848): RTC_WAKEUP set : Alarm{86e4857 type 0 when 1456908906872 com.android.vending} when 1456908906872
,D/Finsky  ( 6342): [765] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6342): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/[SystemUI]QPairHandler( 1361): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1908): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/InputReader(  848): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  848): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7166 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/[SystemUI]QSlideListController( 1361): onReceive = android.intent.action.PACKAGE_CHANGED
W/[SystemUI]QSlideLoader( 1361): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1361): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1361): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1361): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1361): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1361): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1361): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1361): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1361): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1361): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1361): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1361): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1361): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,I/[LGHome]EVENT( 1946): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1946): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1946): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/[LGHome]Launcher( 1946): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/administrator(  848): Handling package changes for user 0
,W/ResourcesManager( 7166): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     ( 1854): Background sticky concurrent mark sweep GC freed 84711(4MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 9MB/14MB, paused 2.125ms total 101.130ms
D/ConnectivityService(  848): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@c5defa4)
,D/ConnectivityService(  848): dumpNetworkRequest
D/ConnectivityService(  848):     NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/ConnectivityService(  848):     Requests:
D/ConnectivityService(  848):         NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  848):         NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  848):         NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  848):     Lingered:
D/ConnectivityService(  848): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  848): sending notification RELEASED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  848): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/ActivityManager(  848): Process com.google.android.gms (pid 5437) has died
,I/NotificationService(  848): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  848): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  848): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  848): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  848): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  848): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@b320c6e
,W/ResourcesManager(  848): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/LCardEmulationManager( 1854): getHceAppCount hostAppNum : 0
,D/LCardEmulationManager( 1854): getDefaultRoute
,I/Babel_SMS( 7166): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7166): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7166): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7166): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7166): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7166): MmsConfig.loadFromResources
E/Babel_SMS( 7166): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7166): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7166): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7166): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7166): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7166): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7166): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7166): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7166): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7166): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7166): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7166): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7166): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7166): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7166): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7166): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7166): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7166): found sensor: Motion Accel, handle=46
W/ResourceType(  848): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,W/Settings( 7166): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7166): startup - clean
I/Babel   ( 7166): deleted: false for 0
,I/[LGHome]EVENT( 1946): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/art     ( 7166): CheckpointMarkThreadRoots callback created = 0xb042d970
I/GCoreNlp( 1749): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/art     ( 7166): CheckpointMarkThreadRoots callback created = 0xb042d940
,I/ActivityManager(  848): Process com.google.android.gms.unstable (pid 6458) has died
,D/LocationProviderProxy(  848): applying state to connected service
,W/AudioCapabilities( 7166): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7166): Unsupported mime audio/adpcm
,W/AudioCapabilities( 7166): Unsupported mime audio/g726
,W/AudioCapabilities( 7166): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7166): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7166): Unsupported mime video/mjpg
I/ActivityManager(  848): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7204 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/VideoCapabilities( 7166): Unsupported mime video/theora
,W/AudioCapabilities( 7166): Unsupported mime audio/evrc
,W/AudioCapabilities( 7166): Unsupported mime audio/qcelp
W/VideoCapabilities( 7166): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7166): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7166): Unsupported mime audio/qcelp
W/AudioCapabilities( 7166): Unsupported mime audio/evrc
W/VideoCapabilities( 7166): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7166): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7166): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7166): Unrecognized profile 2130706433 for video/avc
I/AppUp4:AppBoxCP( 7204): onCreate
,W/VideoCapabilities( 7166): Unrecognized profile 2130706433 for video/avc
W/AppUp4:DB( 7204):  [AppBoxDatabaseHelper] construct
W/VideoCapabilities( 7166): Unrecognized profile 2130706433 for video/avc
I/AppUp4:DB( 7204):  setFingerPrint start
I/AppUp4:DB( 7204):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7204):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7204):  SDK version = 0
I/AppUp4:DB( 7204):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7204): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7204): onReceive
,I/AppUp4:CustModeStarterReceiver( 7204): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 7204): Context : android.app.ReceiverRestrictedContext@3c606f9c
D/AppUp4:CustFacade( 7204): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7204): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7204): begin check event
I/AppUp4:CustModeStarterReceiver( 7204): Event For Nothing, skip.
,I/ActivityManager(  848): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7225 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/vclib   ( 7166): onServiceConnected
W/Babel   ( 7166): Attempted to change video mute state without an active call.
,W/PackageSettings(  848): Skipping PackageSetting{13a3907c com.example.hello/10317} due to missing metadata
,I/NotificationManager( 7166): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 7166): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 7225): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7225): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7225): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
V/JNIHelp ( 7166): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7166): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7166): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 7166): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/AppConfig( 7225): Total System Memory = 906309632
,I/GalleryUtils( 7225): Application Heap = 96 MB
I/AppConfig( 7225): App Tier : NOT_DEF
D/SystemHelper( 7225): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  848): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7251 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ResourcesManager( 7251): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7251): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7251): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7251): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7251): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/UEI.SmartControl( 7100): Internal timer expired: 1
,I/SystemConfig( 7251): BUILD Country: EU
I/SystemConfig( 7251): BUILD Operator: OPEN
,I/SystemConfig( 7251): pm.hasSystemFeature(com.lge.ims.rcs) = false
,I/SystemConfig( 7251): existFile = false
I/SystemConfig( 7251): canReadFile = false
I/SystemConfig( 7251): systemFeature RCS result false
D/SystemConfig( 7251): refreshRcsSupport() :false
I/ActivityManager(  848): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7273 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  848): Killing 7053:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  848): failed to open /acct/uid_10038/pid_7053/cgroup.procs: No such file or directory
,I/LockScreenSettings( 7273): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7273): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7273): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7273): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7273): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7273): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  848): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7290 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  848): Killing 6814:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  848): failed to open /acct/uid_10081/pid_6814/cgroup.procs: No such file or directory
,I/art     (  848): Explicit concurrent mark sweep GC freed 29468(1779KB) AllocSpace objects, 6(87KB) LOS objects, 33% free, 23MB/35MB, paused 2.357ms total 158.389ms
,W/ResourcesManager( 7290): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
I/UpdateIcingCorporaServi( 2022): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  848): Start proc com.google.android.gms for service com.google.android.gms/.app.service.PackageBroadcastService: pid=7315 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/art     (  299): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 29.598ms
,I/ActivityManager(  848): Killing 6923:com.google.android.configupdater/u0a3 (adj 15): empty #11
I/art     (  299): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 20.898ms
,I/UpdateIcingCorporaServi( 2022): UpdateCorporaTask done [took 114 ms] updated apps [took 114 ms] 
I/art     (  299): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 21.261ms
,W/libprocessgroup(  848): failed to open /acct/uid_10003/pid_6923/cgroup.procs: No such file or directory
W/ResourcesManager( 7315): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7315): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/AlarmManager(  848): ELAPSED_WAKEUP set : Alarm{2e16b356 type 2 when 119191 android} when 119191
I/MultiDex( 7315): VM with version 2.1.0 has multidex support
I/MultiDex( 7315): install
,I/MultiDex( 7315): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 7315): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7315): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7315): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@32ae4892: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7315): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 7315): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7315): com.google.android.gms: cancel(39789) by com.google.android.gms
D/PackageBroadcastService( 7315): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 7315): Null package name or gms related package.  Ignoreing.
D/WearableService( 1749): callingUid 10006, callindPid: 1749
,E/MDM     ( 1749): [114] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 7315): Restart initialization of location
D/AuthorizationBluetoothService( 1749): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1749): com.google.android.gms: cancel(0) by com.google.android.gms
,W/art     ( 7315): Suspending all threads took: 13.438ms
,I/art     ( 7315): Background sticky concurrent mark sweep GC freed 26494(1388KB) AllocSpace objects, 2(32KB) LOS objects, 10% free, 10MB/11MB, paused 20.917ms total 90.646ms
,D/NativeLibraryUtils( 7315): Install completed successfully. count=14 extracted=0
I/art     ( 7315): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7315): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/Icing   ( 7315): Storage manager: low false usage 1.71MB avail 2.38GB capacity 4.06GB
,I/art     ( 7315): CheckpointMarkThreadRoots callback created = 0xb042dc40
,I/art     ( 7315): CheckpointMarkThreadRoots callback created = 0xb042dc30
,W/IcingInternalCorpora( 7315): getNumBytesRead when not calculated.
,W/GCoreFlp( 1749): No location to return for getLastLocation()
,W/FusedLocationProvider( 1749): location=null
,I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/Icing   ( 7315): updateResources: need to parse f{com.google.android.gms}
,I/Icing   ( 7315): Internal init done: storage state 0
,I/NotificationManager( 7315): com.google.android.gms: cancel(10436) by com.google.android.gms
I/Icing   ( 7315): Post-init done
,I/Icing   ( 7315): updateResources: need to parse f{com.google.android.gms}
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/Icing   ( 7315): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/Icing   ( 7315): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 7315): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/CloudHub( 2095): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19995
,I/ActivityManager(  848): Killing 2095:com.lge.music/u0a28 (adj 15): empty #11
,V/AudioFlinger(  275): 2095 died, releasing its sessions
V/AudioFlinger(  275):  pid 1782 @ 0
V/AudioFlinger(  275):  pid 3037 @ 1
V/AudioFlinger(  275):  pid 3037 @ 2
,W/libprocessgroup(  848): failed to open /acct/uid_10028/pid_2095/cgroup.procs: No such file or directory
,I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  848): Killing 7204:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  848): failed to open /acct/uid_10011/pid_7204/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/charger_monitor(  486): init target 500000
,D/KeyguardUpdateMonitor( 1361): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1361): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1361): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1361): On Skip Timer : true
,D/PowerService( 1872): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1361): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1361): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1361): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,D/LEDHandler( 1872): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1872): Battery Level Remaining: 100%
D/LEDHandler( 1872): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1908): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1908): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/charger_monitor(  486): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 2073): Disconnected process message: 10, size: 0
,W/Settings(  848): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  848): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  848): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1361): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  848): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  848): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  848): tsOffsetIs: Apps: 133731992507; DSPS: 4480344; Offset : -3004320460
,I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/PowerManagerService(  848): ALS enabled for SRE
,D/PowerManagerServiceEx(  848): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (27105 ms ago)
D/qdlights(  848): set_light_backlight: 253
,D/qdlights(  848): set_light_backlight: 249
D/qdlights(  848): set_light_backlight: 246
,D/qdlights(  848): set_light_backlight: 243
,D/qdlights(  848): set_light_backlight: 239
,D/qdlights(  848): set_light_backlight: 236
,D/qdlights(  848): set_light_backlight: 233
,D/qdlights(  848): set_light_backlight: 229
,D/qdlights(  848): set_light_backlight: 226
,D/qdlights(  848): set_light_backlight: 223
,D/qdlights(  848): set_light_backlight: 219
,D/qdlights(  848): set_light_backlight: 216
,D/qdlights(  848): set_light_backlight: 213
,D/qdlights(  848): set_light_backlight: 209
,D/qdlights(  848): set_light_backlight: 206
,D/qdlights(  848): set_light_backlight: 203
,D/qdlights(  848): set_light_backlight: 199
,D/qdlights(  848): set_light_backlight: 196
,D/qdlights(  848): set_light_backlight: 193
,D/qdlights(  848): set_light_backlight: 189
,D/qdlights(  848): set_light_backlight: 186
,D/qdlights(  848): set_light_backlight: 183
,D/qdlights(  848): set_light_backlight: 179
,D/qdlights(  848): set_light_backlight: 176
,D/qdlights(  848): set_light_backlight: 173
,D/qdlights(  848): set_light_backlight: 169
,D/qdlights(  848): set_light_backlight: 166
,D/qdlights(  848): set_light_backlight: 163
,D/qdlights(  848): set_light_backlight: 159
,D/qdlights(  848): set_light_backlight: 156
,D/qdlights(  848): set_light_backlight: 153
,D/qdlights(  848): set_light_backlight: 149
,D/qdlights(  848): set_light_backlight: 146
,D/qdlights(  848): set_light_backlight: 143
,D/qdlights(  848): set_light_backlight: 139
,D/qdlights(  848): set_light_backlight: 136
,D/qdlights(  848): set_light_backlight: 133
,D/qdlights(  848): set_light_backlight: 129
,D/qdlights(  848): set_light_backlight: 126
,D/qdlights(  848): set_light_backlight: 123
,D/qdlights(  848): set_light_backlight: 119
,D/qdlights(  848): set_light_backlight: 116
,D/qdlights(  848): set_light_backlight: 113
,D/qdlights(  848): set_light_backlight: 109
,D/qdlights(  848): set_light_backlight: 106
,D/qdlights(  848): set_light_backlight: 103
,D/qdlights(  848): set_light_backlight: 99
,D/qdlights(  848): set_light_backlight: 96
,D/qdlights(  848): set_light_backlight: 93
,D/qdlights(  848): set_light_backlight: 89
,D/qdlights(  848): set_light_backlight: 86
,D/qdlights(  848): set_light_backlight: 83
,D/qdlights(  848): set_light_backlight: 79
,D/qdlights(  848): set_light_backlight: 76
,D/qdlights(  848): set_light_backlight: 73
,D/qdlights(  848): set_light_backlight: 69
,D/qdlights(  848): set_light_backlight: 66
,I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
D/qdlights(  848): set_light_backlight: 63
,D/qdlights(  848): set_light_backlight: 59
,D/qdlights(  848): set_light_backlight: 56
,D/qdlights(  848): set_light_backlight: 53
,D/qdlights(  848): set_light_backlight: 49
,D/qdlights(  848): set_light_backlight: 46
,D/qdlights(  848): set_light_backlight: 42
,D/qdlights(  848): set_light_backlight: 39
,D/qdlights(  848): set_light_backlight: 36
,D/qdlights(  848): set_light_backlight: 32
,D/qdlights(  848): set_light_backlight: 29
,D/qdlights(  848): set_light_backlight: 26
,D/qdlights(  848): set_light_backlight: 22
,D/qdlights(  848): set_light_backlight: 19
,D/qdlights(  848): set_light_backlight: 16
,D/qdlights(  848): set_light_backlight: 12
,D/qdlights(  848): set_light_backlight: 10
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/AlarmManager(  848): ELAPSED_WAKEUP set : Alarm{8479578 type 2 when 149197 android} when 149197
,D/ChimeraCfgMgr( 7315): Reading stored module config
,D/ChimeraCfgMgr( 7315): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 7315): Loading module APK com.google.android.play.games
E/ActivityThread( 7315): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  848): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 122266, reason: UserStart, SyncResult: databaseError: true stats []
D/SyncManager(  848): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 215108, reason: UserStart
I/NotificationManager(  848): android: cancelAsUser(716319171) by android
V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AccountUtils( 7315): 0 accounts found with uca feature
I/GamesSyncAdapter( 7315): Starting sync for 3a3529a
W/BaseAppContext( 7315): Using Auth Proxy for data requests.
,E/BaseAppContext( 7315): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,W/BaseAppContext( 7315): Using Auth Proxy for data requests.
W/BaseAppContext( 7315): Using Auth Proxy for data requests.
,I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
W/BaseAppContext( 7315): Using Auth Proxy for data requests.
,W/BaseAppContext( 7315): Using Auth Proxy for data requests.
W/BaseAppContext( 7315): Using Auth Proxy for data requests.
W/BaseAppContext( 7315): Using Auth Proxy for data requests.
,I/GamesSyncAdapter( 7315): Sync duration for 3a3529a: 642
,D/ChimeraCfgMgr( 7315): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 7315): Module APK com.google.android.play.games already loaded
,I/NotificationManager(  848): android: cancelAsUser(-715483196) by android
,D/ChimeraCfgMgr( 7315): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 7315): Module APK com.google.android.play.games already loaded
,I/NotificationManager( 7315): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
D/sensors_hal_Time(  848): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  848): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  848): tsOffsetIs: Apps: 153732690728; DSPS: 5135726; Offset : -3004293626
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/PowerManagerService(  848): ALS enabled for SRE
D/PowerManagerServiceEx(  848): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (34100 ms ago)
,I/PowerManagerService(  848): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  848): ALS enabled for SRE
D/PowerManagerServiceEx(  848): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (34120 ms ago)
W/ContextImpl(  848): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  848): Sleeping (uid 1000)...
D/LPWGController(  848): [updateScreenState] screen on = false
D/LPWGController(  848): disable proximity sensor
D/LPWGController(  848): enable proximity sensor
,I/SensorManager(  848): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@5588b54] by com.android.server.power.ProximitySensorListener.enable():120
I/sensors_hal_Ctx(  848): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  848): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  848): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  848): activate: handle is 48, enable
,V/sensors_hal_Ctx(  848): activate sensors is 1400000000000
D/sensors_hal_Thresh(  848): enable: handle=48
I/sensors_hal_SAM(  848): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  848): waitForResponse: timeout=1000
V/sensors_hal_SAM(  848): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  848): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  848): enable: Received response: 0
D/PowerManagerServiceEx(  848): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (34164 ms ago)
I/Adreno-EGL(  848): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  848): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  848): Build Date: 03/02/15 Mon
I/Adreno-EGL(  848): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  848): Remote Branch: 
I/Adreno-EGL(  848): Local Patches: 
I/Adreno-EGL(  848): Reconstruct Branch: 
,D/PermissionCache(  245): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1047 us)
,I/Sensors (  416): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  848): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  848): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  848): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  848): processInd: handle 48, count=1
V/sensors_hal_Thresh(  848): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  848): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  848): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  848): poll: count: 256
I/sensors_hal_Ctx(  848): poll: released wakelock sensor_ind
D/sensors_hal_Util(  848): waitForResponse: timeout=0
D/LPWGController(  848): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  848): current mode = 1  value = 1 1
I/LPWGController(  848): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  848): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  848): set_light_backlight: 0
,I/SensorManager(  848): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  848): activate: handle is 46, disable
V/sensors_hal_Ctx(  848): activate sensors is 1000000000000
D/sensors_hal_LP2(  848): enable: handle=46
D/sensors_hal_LP2(  848): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  848): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  245): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  245): hwc_blank: Blanking display: 0
I/DisplayManagerService(  848): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  848): Display changed displayId=0
,V/sensors_hal_SAM(  848): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
,D/sensors_hal_LP2(  848): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1782): Display #0 changed.
,D/qdhwcomposer(  245): hwc_blank: Done blanking display: 0
D/SurfaceControl(  848): Excessive delay in setPowerMode(): 227ms
,I/qdhwcomposer(  245): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  848): Got set_interactive hint
D/KeyguardViewMediator( 1361): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1326): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1361): notifyScreenOffLocked
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/SmartCoverViewMediator( 1326): notifyScreenOffLocked
D/SmartCoverViewMediator( 1326): handleNotifyScreenOFF
D/WifiServerServiceExt(  848): sendKtScanInterval  mRtspPlay : false
,I/WifiServerServiceExt(  848): set CMD_KT_SCAN_INTERVAL
D/KeyguardViewMediator( 1361): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1361): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1361): unregisterProximitySensor
,I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1361): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
V/AudioFlinger(  275): setParameters(): io 0, keyvalue screen_state=on, calling pid 848
D/audio_hw_primary(  275): adev_set_parameters: enter: screen_state=on
,V/voice   (  275): voice_set_parameters: enter: screen_state=on
V/compress_voip(  275): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  275): voice_extn_compress_voip_set_parameters: exit
V/voice   (  275): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  275): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  275): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  275): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  275): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  275): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  275): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  275): adev_set_parameters: exit with code(0)
D/StatusBarWindowView( 1361): onScreenTurnedOff why = 3
D/KeyguardUpdateMonitor( 1361): handleTimeUpdate
,I/[SystemUI]LGPowerUI( 1361): onReceive = android.intent.action.SCREEN_ON
D/GpsLocationProvider(  848): receive broadcast intent, action: android.intent.action.SCREEN_ON
D/SplitWindow(  848): check instance of lgWin Window{3cf45a43 u0 SearchPanel}
,I/QCNEJ   ( 1908): |CORE| sendScreenState: state:true
,I/LEDService( 1872): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1872): stopPatternFlashing()
D/InputDispatcher(  848): Window went away: Window{1273c743 u0 SearchPanel}
D/qdlights( 1872): set_light_notifications: 0,0,0,0,3
I/LEDService( 1872): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1872): set_light_notifications: 0,0,0,0,3
I/[SystemUI]Clock( 1361): onReceive = android.intent.action.SCREEN_ON
I/LEDService( 1872): updateLightsLocked : turn off led
D/qdlights( 1872): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1872): RESTART MSG
,I/LgeClockWidgetControlView( 1361): time changed, timezoneChanged : false
,I/ActivityManager(  848): Process com.google.android.talk (pid 7166) has died
,D/LNfcService( 1854): action : android.intent.action.SCREEN_ON
I/Cliptray Service( 1872): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/Cliptray Service( 1872): lockStatus = 0
D/NfcServiceNXP( 1854): mScreenState : 3, mInProvisionMode : false
,D/NfcServiceNXP( 1854): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1854): isRequireNfcCRouting() return true
D/LNfcService( 1854): isHCERoutingtoHost() return : true
D/NfcService( 1854): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1854): mEnableLPD: true
D/NfcService( 1854): mEnableReader: false
D/NfcService( 1854): mEnableHostRouting: true
D/NfcService( 1854): newParams.techmask= mTechMask: default
D/NfcService( 1854): mEnableLPD: true
D/NfcService( 1854): mEnableReader: false
D/NfcService( 1854): mEnableHostRouting: true
D/NfcService( 1854): screenState= 3
D/NfcService( 1854): Discovery configuration equal, not updating.
D/Ulp_jni (  848): JNI:system_update. Event-0
,V/PhoneApp( 1782): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2575): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 9:55:46
,D/WeatherService( 2575): 2 : ACTION screen on
D/WeatherService( 2575): 2 : shouldTimeTickRegistered : false
,D/Weather_cast( 2575): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2575): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 9:55:46
D/AppCleanupService( 3865): android.intent.action.SCREEN_ON
,W/Settings(  848): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  848): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  848): ACTION_SCREEN_ON
V/AudioFlinger(  275): setParameters(): io 0, keyvalue screen_state=off, calling pid 848
,D/audio_hw_primary(  275): adev_set_parameters: enter: screen_state=off
V/voice   (  275): voice_set_parameters: enter: screen_state=off
V/compress_voip(  275): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  275): voice_extn_compress_voip_set_parameters: exit
V/voice   (  275): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  275): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  275): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  275): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  275): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  275): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  275): adev_set_parameters: exit with code(0)
D/WifiController(  848): CMD_SCREEN_OFF 
D/WifiController(  848): shouldWifiStayAwake TRUE
I/[SystemUI]LGPowerUI( 1361): onReceive = android.intent.action.SCREEN_OFF
D/GpsLocationProvider(  848): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,I/QCNEJ   ( 1908): |CORE| sendScreenState: state:false
I/LEDService( 1872): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1872): stopPatternFlashing()
D/qdlights( 1872): set_light_notifications: 0,0,0,0,3
I/LEDService( 1872): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1872): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1872): clear
I/LEDService( 1872): updateLightsLocked : turn on led
E/LEDService( 1872): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1872): Can't handle this request of patternId:0
D/LEDHandler( 1872): RESTART MSG
D/LNfcService( 1854): action : android.intent.action.SCREEN_OFF
I/Cliptray Service( 1872): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1854): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1946): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1782): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2575): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 9:55:46
D/WeatherService( 2575): 2 : ACTION screen off
D/WeatherService( 2575): 2 : TimeTick Receiver Unregister
D/WeatherService( 2575): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 9:55:46
D/AppCleanupService( 3865): android.intent.action.SCREEN_OFF
,W/Settings(  848): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  848): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  848): ACTION_SCREEN_OFF
D/AppCleanupService( 3865): AppUsageStatsSaveTask
E/NxpNfcJni( 1854): getReconnectState = 0x0
,D/LCardEmulationManager( 1854): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1854): getDefaultRoute
D/LNfcService( 1854): isRequireNfcCRouting() return true
D/LNfcService( 1854): isHCERoutingtoHost() return : true
D/NfcService( 1854): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1854): mEnableLPD: true
D/NfcService( 1854): mEnableReader: false
D/NfcService( 1854): mEnableHostRouting: true
,D/NfcService( 1854): newParams.techmask= mTechMask: 0
D/NfcService( 1854): mEnableLPD: true
D/NfcService( 1854): mEnableReader: false
D/NfcService( 1854): mEnableHostRouting: true
D/NfcService( 1854): screenState= 1
E/NxpNfcJni( 1854): getReconnectState = 0x0
,I/Sensors (  416): sns_pwr.c(301):releasing wakelock
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,D/KeyguardViewMediator( 1361): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  848): ELAPSED_WAKEUP set : Alarm{3a5d08c0 type 2 when 160102 com.android.systemui} when 160102
,D/PhoneUtils( 1782): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1782): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1782): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1782): getCallState : 0
D/PhoneUtils( 1782): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1782): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1782): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1361): isHdmiPluggedIn :false
,D/KeyguardViewMediator( 1361): doKeyguard: not showing because lockscreen is off
D/KeyguardUpdateMonitor( 1361): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1361): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1361): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1361): On Skip Timer : true
,D/PowerService( 1872): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): init target 500000
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1361): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/[SystemUI]LGPowerUI( 1361): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1361): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
,I/QCNEJ   ( 1908): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1872): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1872): Battery Level Remaining: 100%
D/LEDHandler( 1872): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1908): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2073): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1361): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  848): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  848): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  848): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1361): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1361): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1361): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
,W/Settings(  848): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  848): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  848): battery changed pluggedType: 2
I/QCNEJ   ( 1908): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1908): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1361): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1872): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1872): Battery Level Remaining: 100%
D/LEDHandler( 1872): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2073): Disconnected process message: 10, size: 0
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1361): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1361): called onTimeUpdated()
I/[SystemUI]Clock( 1361): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1361): called onTimeUpdated()
I/[SystemUI]DateView( 1361): called onTimeUpdated()
I/[SystemUI]DateView( 1361): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1361): handleTimeUpdate
D/sensors_hal_Time(  848): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  848): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  848): tsOffsetIs: Apps: 173733453429; DSPS: 5791111; Offset : -3004293813
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,D/PowerManagerServiceEx(  848): acquireWakeLockInternal: lock=919038457, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=848
,V/AlarmManager(  848): ELAPSED_WAKEUP set : Alarm{4c82d3e type 2 when 179630 android} when 179630
D/PowerManagerServiceEx(  848): releaseWakeLockInternal: lock=919038457 [*alarm*], flags=0x0
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  848): ELAPSED_WAKEUP set : Alarm{2f8579f type 2 when 185592 com.google.android.gms} when 185592
,I/art     ( 1749): Explicit concurrent mark sweep GC freed 26615(1684KB) AllocSpace objects, 12(192KB) LOS objects, 40% free, 14MB/24MB, paused 1.642ms total 92.907ms
,I/PhenotypeFlagCommitter( 1749): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1749): Using platform SSLCertificateSocketFactory
,I/art     (  848): Explicit concurrent mark sweep GC freed 44812(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 23MB/34MB, paused 2.271ms total 154.257ms
,D/LocationManagerService(  848): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
,I/System.out( 1749): propertyValue:false
D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LocationManagerService(  848): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
,I/System.out( 1749): propertyValue:false
D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1749): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1749): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/charger_monitor(  486): init target 500000
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1361): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1361): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1361): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1361): On Skip Timer : true
,D/PowerService( 1872): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/NotificationManager(  848): android: cancelAsUser(2) by android
,D/KeyguardUpdateMonitor( 1361): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/[SystemUI]LGPowerUI( 1361): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1361): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
,D/LEDHandler( 1872): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1872): Battery Level Remaining: 100%
D/LEDHandler( 1872): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1908): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1908): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1361): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2073): Disconnected process message: 10, size: 0
W/Settings(  848): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  848): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  848): battery changed pluggedType: 2
I/NotificationManager( 1749): com.google.android.gms: cancel(0) by com.google.android.gms
D/LocationManagerService(  848): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  848): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/AlarmManager(  848): ELAPSED_WAKEUP set : Alarm{37ac668f type 2 when 188253 android} when 188253
,D/LocationManagerService(  848): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,D/LocationManagerService(  848): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  848): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  848): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  848): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  848): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  848): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  848): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  848): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  848): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  848): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  848): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/sensors_hal_Time(  848): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  848): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  848): tsOffsetIs: Apps: 193734127067; DSPS: 6446493; Offset : -3004291926
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  848): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  848): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  848): tsOffsetIs: Apps: 213734936851; DSPS: 7101880; Offset : -3004305493
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ClearcutLoggerApiImpl( 1749): disconnect managed GoogleApiClient
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1361): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1361): called onTimeUpdated()
I/[SystemUI]Clock( 1361): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1361): called onTimeUpdated()
I/[SystemUI]DateView( 1361): called onTimeUpdated()
I/[SystemUI]DateView( 1361): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1361): handleTimeUpdate
D/sensors_hal_Time(  848): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  848): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  848): tsOffsetIs: Apps: 233735625906; DSPS: 7757263; Offset : -3004318576
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  486): init target 500000
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1361): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1361): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1361): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1361): On Skip Timer : true
,D/PowerService( 1872): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1361): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1361): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1361): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
,I/QCNEJ   ( 1908): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1872): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1872): Battery Level Remaining: 100%
D/LEDHandler( 1872): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1908): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2073): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1361): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  848): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  848): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  848): battery changed pluggedType: 2
I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  848): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  848): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  848): tsOffsetIs: Apps: 253736309283; DSPS: 8412645; Offset : -3004306117
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  848): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  848): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  848): tsOffsetIs: Apps: 273737065630; DSPS: 9068030; Offset : -3004312891
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1361): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1361): called onTimeUpdated()
I/[SystemUI]Clock( 1361): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1361): called onTimeUpdated()
I/[SystemUI]DateView( 1361): called onTimeUpdated()
I/[SystemUI]DateView( 1361): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1361): handleTimeUpdate
I/jxcore-log( 4586): Reconnected to the test server
I/jxcore-log( 4586): 
,I/jxcore-log( 4586): --= Surplus to requirements =--
I/jxcore-log( 4586): 
I/jxcore-log( 4586): ****TEST TOOK:  ms ****
I/jxcore-log( 4586): 
I/jxcore-log( 4586): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4586): 
,D/sensors_hal_Time(  848): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  848): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  848): tsOffsetIs: Apps: 293737748539; DSPS: 9723412; Offset : -3004301474
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/AndroidRuntime( 7536): 
D/AndroidRuntime( 7536): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7536): CheckJNI is OFF
,D/AndroidRuntime( 7536): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  848): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  848): Killing 4586:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
,W/PackageSettings(  848): Skipping PackageSetting{13a3907c com.example.hello/10317} due to missing metadata
,I/WindowState(  848): WIN DEATH: Window{28d799f8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  848): Focus left window: Window{28d799f8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  848): Window went away: Window{28d799f8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  848):   Force finishing activity ActivityRecord{60df538 u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  848): Display changed displayId=0
D/DSDPConnection( 1782): Display #0 changed.
,W/ActivityManager(  848): Spurious death for ProcessRecord{23c22d25 4586:com.test.thalitest/u0a316}, curProc for 4586: null
,I/ActivityManager(  848): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  848):   Force finishing activity ActivityRecord{60df538 u0 com.test.thalitest/.MainActivity t222 f}
W/ActivityManager(  848): Duplicate finish request for ActivityRecord{60df538 u0 com.test.thalitest/.MainActivity t222 f}
,D/KeyguardModel( 1361): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/InputReader(  848): Reconfiguring input devices.  changes=0x00000010
I/QCNEJ   ( 1908): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,W/GeofencerStateMachine( 1749): Ignoring removeGeofence because network location is disabled.
W/System.err( 3378): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,I/ActivityManager(  848): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7568 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1946): [Launcher.java:5203:onStart()]onStart
W/System.err( 3378): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3378): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3378): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3378): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3378): 	at android.os.Handler.dispatchMessage(Handler.java:95)
,W/System.err( 3378): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3378): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3378): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3378): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3378): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3378): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,I/art     ( 2022): Explicit concurrent mark sweep GC freed 30744(2MB) AllocSpace objects, 2(47KB) LOS objects, 40% free, 12MB/20MB, paused 1.802ms total 125.720ms
I/[SystemUI]QSlideListController( 1361): onReceive = android.intent.action.PACKAGE_REMOVED
,I/[LGHome]EVENT( 1946): [Launcher.java:776:onResume()]onResume
I/[LGHome]EVENT( 1946): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
D/KeyguardModel( 1361): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1361): createShortcutInfo...
I/[LGHome]Launcher.Model( 1946): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/KeyguardModel( 1361): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1361): createShortcutInfo...
,I/[LGHome]LGActivityUtil( 1946): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1946): [Launcher.java:929:onResume()]onResume end
I/Activity( 1946): Activity.onPostResume() called 
I/[LGHome]EVENT( 1946): [Launcher.java:986:onPause()]onPause
W/ResourcesManager( 1361): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1361): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourceType( 1361): No package identifier when getting value for resource number 0x00000000
,W/PackageManager( 1361): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1361): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1361): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/KeyguardModel( 1361): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1361): createShortcutInfo...
W/ResourcesManager( 1361): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourceType( 1361): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1361): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
W/[LGHome]LGWallpaperInfo( 1946): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1946): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
D/KeyguardModel( 1361): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1361): createShortcutInfo...
W/ResourcesManager( 1361): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1361): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1361): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,W/ResourceType( 1361): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1361): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/art     (  848): Explicit concurrent mark sweep GC freed 17995(1190KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 5.435ms total 218.312ms
I/art     (  848): WaitForGcToComplete blocked for 186.395ms for cause Explicit
D/KeyguardModel( 1361): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1361): createShortcutInfo...
D/KeyguardModel( 1361): handleShortcutListChanged...
D/KeyguardModel( 1361): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1361): createShortcutInfo...
D/KeyguardModel( 1361): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1361): createShortcutInfo...
W/ResourceType( 1361): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1361): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1361): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1361): createShortcutInfo...
,W/ResourceType( 1361): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1361): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/InputDispatcher(  848): Focus entered window: Window{34a9f1d3 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/WindowManager(  848): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
I/Adreno-EGL( 1946): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 1946): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 1946): Build Date: 03/02/15 Mon
I/Adreno-EGL( 1946): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 1946): Remote Branch: 
I/Adreno-EGL( 1946): Local Patches: 
I/Adreno-EGL( 1946): Reconstruct Branch: 
I/OpenGLRenderer( 1946): Initialized EGL, version 1.4
I/SystemUI[Framework](  848): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
D/KeyguardModel( 1361): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1361): createShortcutInfo...
I/[SystemUI]NavigationThemeResource( 1361): notify navigation bar color(0x0)
I/[SystemUI]NavigationThemeResource( 1361): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1361):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1361): , Keyguard show=false, IME shown=false, Panel expanded=false
W/ResourceType( 1361): No package identifier when getting value for resource number 0x00000000
,W/PackageManager( 1361): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
W/PhoneWindowManagerEx(  848): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  848): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  848): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/SystemUI[Framework](  848): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3d8b5a3b,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  848): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/KeyguardModel( 1361): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1361): createShortcutInfo...
D/KeyguardModel( 1361): handleShortcutListChanged...
,I/[LGHome]EVENT( 1946): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1946): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1946): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
I/[LGHome]EVENT( 1946): [Launcher.java:5214:onStop()]onStop
,W/ResourcesManager( 7568): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7568): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7568): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1946): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1946): [setNavigationBarColor] color=0x 0
D/administrator(  848): Handling package changes for user 0
,I/art     (  848): Explicit concurrent mark sweep GC freed 2857(152KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 6.070ms total 219.898ms
,D/AndroidRuntime( 7536): Shutting down VM
,I/LGEmail ( 7568): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7568): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/LCardEmulationManager( 1854): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1854): getDefaultRoute
,W/InputMethodManagerService(  848): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,W/InputMethodManagerService(  848): Got RemoteException sending setActive(false) notification to pid 4586 uid 10316
I/NotificationService(  848): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,D/BackupManagerService(  848): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  848): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  848): removeObsoleteFile: deleting file=222_task.xml
,I/[LGHome]Launcher.Model( 1946): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1946): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/Timeline(  848): Timeline: Activity_windows_visible id: ActivityRecord{309856d9 u0 com.lge.launcher2/.Launcher t221} time:295762
I/[LGHome]EVENT( 1946): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1946): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1946): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1946): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
W/IInputConnectionWrapper( 1946): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1946): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1946): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,E/b       ( 1622): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1946): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1946): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 1946): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,W/IInputConnectionWrapper( 1946): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1946): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1946): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/Resources( 1946): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
,W/Resources( 1946): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1946): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1946): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1946): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1946): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
,W/Resources( 1946): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
I/PackageChangeReceiver( 7568): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
W/ResourcesManager(  848): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/Resources( 1946): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1946): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1946): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1946): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}

```
