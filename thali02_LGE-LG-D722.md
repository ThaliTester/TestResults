#### Test 61432979123161a_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/MediaRouter( 5267): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
I/NetworkMonitor( 5267): type=WIFI subType= reason=null isConnected=true
D/ToneMappingReceiver( 5151): Enter doAlarmRingToneUriMapping()
D/libc-netbsd( 4331): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4331): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4331): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4331): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ToneMappingReceiver( 5151): do ALARM RingToneUriMapping() -> first find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/CommonUtil( 5151): Enter getMatchedBackupTone() enter URI value is On, parentInfo : ALARM
D/CommonUtil( 5151): getFinededDefaultTone() -> backup ringtone value : null
D/CommonUtil( 5151): Exit getMatchedBackupTone() value is null
D/ToneMappingReceiver( 5151): do ALARM RingToneUriMapping() -> second find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/ToneMappingReceiver( 5151): Enter doAlarmRingToneUriMapping(), return value is 0
D/ToneMappingReceiver( 5151): Alarm Success count is 0
D/ToneMappingReceiver( 5151): Timer Success count is 0
I/MediaScannerReceiver( 3817): Calendar.onReceive: a=android.intent.action.MEDIA_SCANNER_FINISHED Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///system/media flg=0x10 cmp=com.android.calendar/.alerts.MediaScannerReceiver }, mData=file:///system/media
I/CheckinTask( 4331): Sending checkin request (9805 bytes)
E/MediaScanReceiver( 5247): media scanning finished
I/NetworkMonitor( 5267): type=WIFI subType= reason=null isConnected=true
I/InitNotificationRingtoneService( 3817): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 3817): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
I/com.lge.bnr.receiver.MediaScanReceiver( 5247): android.intent.action.MEDIA_SCANNER_FINISHED
,I/AlertUtils( 3817): [getCalendarNotiSoundURIFromCursor] getCount()= 21
I/AlertUtils( 3817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/GHttpClientFactory( 5267): Using our fixed implementation of GMSCore's GoogleHttpClient
I/AlertUtils( 3817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
W/ResourceType(  946): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/LocationProviderProxy(  946): applying state to connected service
I/GoogleURLConnFactory( 5267): Using platform SSLCertificateSocketFactory
I/AlertUtils( 3817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 3817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 3817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 3817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 3817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 3817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 3817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 3817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 3817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
E/MediaScanReceiver( 5247): media scanning start or checking
I/AlertUtils( 3817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 3817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 3817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/NotificationManager( 5267): com.google.android.music: cancel(1061) by com.google.android.music
D/ToneMappingReceiver( 5151): Enter doAlarmRingToneUriMapping()
I/AlertUtils( 3817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3817): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
D/ToneMappingReceiver( 5151): do ALARM RingToneUriMapping() -> first find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/CommonUtil( 5151): Enter getMatchedBackupTone() enter URI value is On, parentInfo : ALARM
D/CommonUtil( 5151): getFinededDefaultTone() -> backup ringtone value : null
D/CommonUtil( 5151): Exit getMatchedBackupTone() value is null
D/ToneMappingReceiver( 5151): do ALARM RingToneUriMapping() -> second find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/ToneMappingReceiver( 5151): Enter doAlarmRingToneUriMapping(), return value is 0
D/ToneMappingReceiver( 5151): Alarm Success count is 0
D/ToneMappingReceiver( 5151): Timer Success count is 0
I/MediaScannerReceiver( 3817): Calendar.onReceive: a=android.intent.action.MEDIA_SCANNER_FINISHED Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///storage/emulated/0 flg=0x10 cmp=com.android.calendar/.alerts.MediaScannerReceiver }, mData=file:///storage/emulated/0
I/AlertUtils( 3817): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 3817): End InitializeAlertRingtoneService.onHandleIntent
I/InitNotificationRingtoneService( 3817): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 3817): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
E/MediaScanReceiver( 5247): media scanning finished
I/com.lge.bnr.receiver.MediaScanReceiver( 5247): android.intent.action.MEDIA_SCANNER_FINISHED
--------- beginning of system
V/AlarmManager(  946): ELAPSED_WAKEUP set : Alarm{1e7417de type 2 when 75910 android} when 75910
I/AlertUtils( 3817): [getCalendarNotiSoundURIFromCursor] getCount()= 21
I/AlertUtils( 3817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 3817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/art     ( 3223): Explicit concurrent mark sweep GC freed 11867(824KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/10MB, paused 759us total 49.337ms
I/AlertUtils( 3817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/ActivityManager(  946): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5325 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/AlertUtils( 3817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 3817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 3817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 3817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 3817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 3817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 3817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 3817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 3817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 3817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 3817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 3817): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3817): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 3817): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 3817): End InitializeAlertRingtoneService.onHandleIntent
W/ResourcesManager( 5325): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/art     ( 5267): CheckpointMarkThreadRoots callback created = 0xb042d410
D/CalendarProvider2( 5325): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@10b37240
D/CalendarProvider2( 5325): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 5325): Created com.android.providers.calendar.CalendarAlarmManager@1aced035(com.android.providers.calendar.CalendarProvider2@10b37240)
I/art     ( 5267): CheckpointMarkThreadRoots callback created = 0xb042d3e0
D/CalendarProviderBroadcastReceiver( 5325): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 5325): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 5325): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 5325): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 5325): [getOrCreateCalendarAlarmManager]
D/WearableService( 1733): callingUid 10006, callindPid: 1733
D/LocationInitializer( 4331): Restart initialization of location
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1733): [138] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AndroidRuntime( 5320): 
D/AndroidRuntime( 5320): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
D/CalendarProvider2( 5325): [IntentService] Release Lock
D/AndroidRuntime( 5320): CheckJNI is OFF
I/MediaStoreImporter( 5267): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
D/CalendarProvider2( 5325): CalendarProviderIntentService.onDestroy()
I/CheckinResponseProcessor( 4331): From server: 3 gservices updates and 0 deletes
I/ActivityManager(  946): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5350 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/IcingInternalCorpora( 4331): getNumBytesRead when not calculated.
I/art     (  946): Explicit concurrent mark sweep GC freed 22416(1169KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.912ms total 223.930ms
W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
D/AndroidRuntime( 5320): Calling main entry com.android.commands.am.Am
I/ActivityManager(  946): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  946): setTaskToReturnTo : TaskRecord{a2b9845 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  946): setTaskToReturnTo : TaskRecord{a2b9845 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
I/CertBlacklister(  946): Certificate blacklist changed, updating...
I/GservicesProvider( 3978): main difference update completed
I/CertBlacklister(  946): Certificate blacklist updated
D/WindowStateEx(  946): AppWindowTokenEx init.. 
D/ContextHelper(  946): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
D/InputDispatcher(  946): Focus left window: Window{28f24916 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5320): Shutting down VM
I/[LGHome]EVENT( 1877): [Launcher.java:986:onPause()]onPause
W/ActivityManager(  946): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/CheckinRequestBuilder( 4331): Checkin reason type: 8 attempt count: 1
I/PhoneWindow(  946): [generateLayout] setColorNavigationBar => color=0x ff000001
E/ActivityThread( 4331): Failed to find provider info for com.google.android.wearable.settings
D/PhoneWindowEx(  946): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow(  946): [setNavigationBarColor2] color=0x fff5f5f5
D/SplitWindow(  946): check instance of lgWin Window{14f18afd u0 Starting com.test.thalitest}
I/ActivityManager(  946): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5390 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1877): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[LGHome]EVENT( 1877): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  946): Starting window displayed
D/WindowManager(  946): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
,I/SystemUI[Framework](  946): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
I/[SystemUI]NavigationThemeResource( 1379): notify navigation bar color(0xfff5f5f5)
W/PhoneWindowManagerEx(  946): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  946): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  946): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  946): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@4b0deb4,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  946): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1379): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1379):  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
I/[SystemUI]NavigationThemeResource( 1379): , Keyguard show=false, IME shown=false, Panel expanded=false
I/HotwordDetector( 1941): Closing mic
I/MicrophoneInputStream( 1941): mic_close com.google.android.apps.gsa.speech.audio.u@151a58a2
V/AudioRecord( 1941): stop()
D/AudioRecord( 1941): AudioRecord->stop()
V/AudioFlinger(  274): RecordHandle::stop()
V/AudioFlinger(  274): RecordThread::stop
V/AudioFlinger(  274): Record stopped OK
V/AudioPolicyManager(  274): stopInput() input 16
V/AudioPolicyService(  274): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  274): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  274): AudioCommandThread() waking up
V/AudioPolicyService(  274): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  274): releaseAudioPatch handle 17
V/AudioFlinger::PatchPanel(  274): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  274): ThreadBase::setParameters() routing=0
V/AudioFlinger(  274): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  274): processConfigEvents_l() remaining events 1
I/Gmail   ( 5350): getAccountsCursor
V/AudioFlinger(  274): processConfigEvents_l() DONE thread 0xb3e11000
D/audio_hw_primary(  274): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ContextHelper( 5390): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
V/audio_hw_primary(  274): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  274): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  274): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  274): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  274): disable_audio_route: exit
E/audio_hw_primary(  274): disable_snd_device: enter 144
D/hardware_info(  274): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  274): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  274): stop_input_stream: exit: status(0)
V/audio_hw_primary(  274): in_standby: exit:  status(0)
V/AudioFlinger(  274): RecordThread: loop stopping
V/AudioPolicyService(  274): AudioCommandThread() going to sleep
V/AudioPolicyManager(  274): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  274): removeAudioPatch() handle 18 af handle 17
V/AudioPolicyService(  274): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  274): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  274): AudioCommandThread() waking up
V/AudioPolicyService(  274): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  274): AudioCommandThread() going to sleep
V/AudioPolicyService(  274): AudioCommandThread() adding set parameter string hotword_active=0, io 16 ,delay 0
V/AudioPolicyService(  274): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  274): AudioCommandThread() waking up
V/AudioPolicyService(  274): AudioCommandThread() processing set parameters string hotword_active=0, io 16
V/AudioFlinger(  274): setParameters(): io 16, keyvalue hotword_active=0, calling pid 274
V/AudioFlinger(  274): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  274): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  274): RecordThread: loop starting
V/AudioFlinger(  274): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  274): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  274): in_set_parameters: exit: status(0)
V/AudioFlinger(  274): processConfigEvents_l() DONE thread 0xb3e11000
V/AudioFlinger(  274): RecordThread: loop stopping
V/AudioPolicyService(  274): AudioCommandThread() going to sleep
W/GAV2    ( 5350): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
V/AudioRecord( 1941): stop()
V/AudioRecord( 1941): stop()
V/AudioRecord( 1941): stop()
V/AudioFlinger(  274): RecordHandle::stop()
V/AudioFlinger(  274): RecordThread::stop
V/AudioPolicyManager(  274): releaseInput() 16
V/AudioPolicyManager(  274): closeInput(16)
V/AudioFlinger(  274): closeInput() 16
V/AudioSystem(  274): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1941): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1379): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  274): ThreadBase::exit
V/AudioSystem( 2686): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  274): RecordThread: loop starting
V/AudioFlinger(  274): RecordThread 0xb3e11000 exiting
V/AudioSystem(  946): ioConfigChanged() event 4, ioHandle 16
D/audio_hw_primary(  274): adev_close_input_stream: enter:stream_handle(0xb546dd40)
V/AudioSystem( 3150): ioConfigChanged() event 4, ioHandle 16
D/audio_hw_primary(  274): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/audio_hw_primary(  274): in_standby: exit:  status(0)
V/AudioPolicyService(  274): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  274): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  274): AudioCommandThread() waking up
V/AudioPolicyService(  274): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  274): AudioCommandThread() going to sleep
V/AudioSystem( 1751): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 2021): ioConfigChanged() event 4, ioHandle 16
V/AudioPolicyManager(  274): releaseInput() exit
V/AudioFlinger(  274): releasing 15 from 1941 for -1
V/AudioFlinger(  274):  decremented refcount to 0
V/AudioFlinger(  274): purging stale effects
V/AudioFlinger(  274): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  274): removeClient_l() pid 1941, calling pid 274
I/HotwordRecognitionRnr( 1941): Hotword detection finished
I/HotwordRecognitionRnr( 1941): Stopping hotword detection.
W/ActivityManager(  946): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/art     ( 3978): Explicit concurrent mark sweep GC freed 9468(465KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 957us total 54.557ms
I/WebViewFactory( 5390): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/ActivityManager(  946): Killing 5017:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
E/Gmail   ( 5350): Error finding the version of the Email provider.....
E/Gmail   ( 5350): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5350): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5350): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5350): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5350): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5350): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5350): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5350): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5350): We do not support migrating this version of the Email provider.
W/libprocessgroup(  946): failed to open /acct/uid_10089/pid_5017/cgroup.procs: No such file or directory
W/ActivityManager(  946): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 5350): getAccountsCursor
I/Gmail   ( 5350): Observing account changes for notifications
W/ActivityManager(  946): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/LibraryLoader( 5390): Time to load native libraries: 4 ms (timestamps 7417-7421)
I/LibraryLoader( 5390): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5390): Binding Chromium to main looper Looper (main, tid 1) {2b7cfcca}
I/LibraryLoader( 5390): Expected native library version number "",actual native library version number ""
I/chromium( 5390): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5390): Initializing chromium process, singleProcess=true
W/art     ( 5390): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5390): ApplicationContext is null in ApplicationStatus
I/ActivityManager(  946): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=5427 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     (  301): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 313us total 23.369ms
I/ActivityManager(  946): Killing 5098:com.android.chrome/u0a48 (adj 15): empty #11
W/chromium( 5390): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5390): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5390): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5390): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5390): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5390): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5390): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5390): Remote Branch: 
I/Adreno-EGL( 5390): Local Patches: 
I/Adreno-EGL( 5390): Reconstruct Branch: 
I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 345us total 23.850ms
I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 297us total 22.808ms
W/libprocessgroup(  946): failed to open /acct/uid_10048/pid_5098/cgroup.procs: No such file or directory
V/AudioPolicyService(  274): registerClient() client 0xb3dd4c00, uid 10316
D/BluetoothManagerService(  946): Message: 20
D/BluetoothManagerService(  946): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3b9d1720:true
D/BluetoothAdapterService(514407089)( 2021): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1753de0f
,W/ResourcesManager( 5427): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 4331): Classify the device as Phone.
,I/Gmail   ( 5350): notifyAccountChanged
,I/Gmail   ( 5350): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/art     ( 4331): Explicit concurrent mark sweep GC freed 16753(1201KB) AllocSpace objects, 18(288KB) LOS objects, 40% free, 12MB/20MB, paused 1.270ms total 143.139ms
W/art     ( 5390): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5390): onDetachedFromWindow called when already detached. Ignoring
,I/Gmail   ( 5350): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5350): getAccountsCursor
I/PhoneWindow( 5390): [generateLayout] setColorNavigationBar => color=0x ff000001
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PhoneWindowEx( 5390): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow( 5390): [setNavigationBarColor2] color=0x fff5f5f5
,I/Gmail   ( 5350): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/[SystemUI]TimeTickManager( 1379): setTimeTickHandler, called onTimeChanged()
I/Gmail   ( 5350): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/KeyguardUpdateMonitor( 1379): called onTimeUpdated()
,I/[SystemUI]Clock( 1379): called onTimeUpdated()
I/LgeClockWidgetControlView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1379): handleTimeUpdate
D/SystemWebViewEngine( 5390): CordovaWebView is running on device made by: LGE
,W/art     ( 5390): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5390): Attempt to remove local handle scope entry from IRT, ignoring
I/CheckinTask( 4331): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4331): Checking schedule, now: 1456940219951 next: 1457467468934
I/CheckinService( 4331): active receiver: disabled
,D/CheckinService( 4331): Recording last checkin time for package unspecified as 1456940219980
I/Activity( 5390): Activity.onPostResume() called 
,I/Gmail   ( 5350): getAccountsCursor
D/OpenGLRenderer( 5390): Render dirty regions requested: true
I/OpenGLRenderer( 5390): Initialized EGL, version 1.4
D/WeatherService( 2661): 2 : TimeTick Intent has been received, Time(hour:min:sec) 18:37:0
D/WeatherService( 2661): 2 : TimeTick Intent And Screen On
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/OpenGLRenderer( 5390): Enabling debug mode 0
,D/WeatherService( 2661): 2 : SDK version : 21
W/ActivityManager(  946): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2661): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2661): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2661): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2661): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/Atlas   ( 5390): Validating map...
D/UpdateThreadPoolManager( 2661): 2 : This is isUpdating : false
D/WeatherService( 2661): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2661): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2661): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2661): 2 : Fixed theme : optimus
D/SplitWindow(  946): check instance of lgWin Window{44f7203 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WeatherReflect( 2661): 2 : Map key string is -2
D/lim     ( 2661): 2 : time = 18:37
I/WeatherReflect( 2661): Model Name : LG-D722
,D/WeatherTheme( 2661): 2 : Different view - status_min_formatted : 36 != 37
D/WeatherTheme( 2661): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
I/[SystemUI]TimeTickManager( 1379): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1379): called onTimeUpdated()
I/[SystemUI]Clock( 1379): called onTimeUpdated()
W/chromium( 5390): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/WeatherReflect( 2661): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
I/LgeClockWidgetControlView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1379): handleTimeUpdate
D/Theme   ( 2661): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2661): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2661): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2661): currentPackage=com.lge.sizechangable.weather.theme.optimus
,D/InputDispatcher(  946): Focus entered window: Window{44f7203 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/Weather4x2_optimus( 2661): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2661): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2661): forecast size is 0
D/Theme   ( 2661): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2661): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2661): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2661): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2661): EnableTheme(home): com.lge.launcher2.theme.optimus
,D/Theme   ( 2661): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2661): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2661): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2661): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2661): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2661): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2661): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2661): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2661): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2661): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2661): url is : null
D/Theme   ( 2661): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2661): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2661): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2661): 2 : update view, appWidgetId: 2
D/WeatherService( 2661): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 18:37:0
W/InputMethodManagerService(  946): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ActivityManager(  946): Displayed com.test.thalitest/.MainActivity: +1s267ms
I/Timeline(  946): Timeline: Activity_windows_visible id: ActivityRecord{27530b9a u0 com.test.thalitest/.MainActivity t222} time:78182
I/Timeline( 5390): Timeline: Activity_idle id: android.os.BinderProxy@445d534 time:78186
I/ThermalEngine(  288): Sensor:pa_therm0:31000 mC
,I/Babel_SMS( 5427): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5427): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5427): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5427): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5427): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5427): MmsConfig.loadFromResources
,E/Babel_SMS( 5427): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5427): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
W/BindingManager( 5390): Cannot call determinedVisibility() - never saw a connection for the pid: 5390
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
D/SensorManager( 5427): found sensor: LGE Accelerometer Sensor, handle=0
,D/SensorManager( 5427): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5427): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5427): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5427): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5427): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5427): found sensor: LGE Rotation Vector Sensor, handle=36
,D/SensorManager( 5427): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5427): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5427): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5427): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5427): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5427): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5427): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5427): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5427): found sensor: Motion Accel, handle=46
I/art     ( 5427): CheckpointMarkThreadRoots callback created = 0xb042d880
,I/art     ( 5427): CheckpointMarkThreadRoots callback created = 0xb042d860
,W/Settings( 5427): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5427): startup - clean
I/Babel   ( 5427): deleted: false for 0
,D/JsMessageQueue( 5390): Set native->JS mode to OnlineEventsBridgeMode
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
W/AudioCapabilities( 5427): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5427): Unsupported mime audio/adpcm
W/AudioCapabilities( 5427): Unsupported mime audio/g726
W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
W/AudioCapabilities( 5427): Unsupported mime audio/x-ms-wma
,D/AlertService( 3817): Beginning updateAlertNotification
W/AudioCapabilities( 5427): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5427): Unsupported mime video/mjpg
W/VideoCapabilities( 5427): Unsupported mime video/theora
,V/DownloadManager( 3223): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3223): created cursor android.database.sqlite.SQLiteCursor@3e798fef on behalf of 4331
D/AlertService( 3817): No fired or scheduled alerts
I/NotificationManager( 3817): com.android.calendar: cancel(0) by com.android.calendar
,I/NotificationManager( 3817): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 3817): com.android.calendar: cancel(2) by com.android.calendar
,I/NotificationManager( 3817): com.android.calendar: cancel(3) by com.android.calendar
,I/NotificationManager( 3817): com.android.calendar: cancel(4) by com.android.calendar
,I/NotificationManager( 3817): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 3817): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 3817): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 3817): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 3817): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 3817): com.android.calendar: cancel(10) by com.android.calendar
,I/NotificationManager( 3817): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 3817): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 3817): com.android.calendar: cancel(13) by com.android.calendar
,W/AudioCapabilities( 5427): Unsupported mime audio/evrc
W/AudioCapabilities( 5427): Unsupported mime audio/qcelp
I/NotificationManager( 3817): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 3817): com.android.calendar: cancel(15) by com.android.calendar
,I/NotificationManager( 3817): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 3817): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 3817): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 3817): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 3817): com.android.calendar: cancel(20) by com.android.calendar
I/ActivityManager(  946): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5495 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,W/VideoCapabilities( 5427): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5427): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 5427): Unsupported mime audio/qcelp
D/AlertService( 3817): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,W/AudioCapabilities( 5427): Unsupported mime audio/evrc
V/DownloadManager( 3223): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3223): created cursor android.database.sqlite.SQLiteCursor@25774afc on behalf of 4331
V/DownloadManager( 3223): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3223): created cursor android.database.sqlite.SQLiteCursor@78be585 on behalf of 4331
,W/VideoCapabilities( 5427): Unsupported mime video/mp4v-esdp
,D/AlarmScheduler( 3817): No events found starting within 1 week.
,I/VideoCapabilities( 5427): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5427): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5427): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5427): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5427): Unrecognized profile 2130706433 for video/avc
,D/jxcore_app_log( 5390): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426143104
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5390): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5390):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5390):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5390):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5390):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5390): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@242b1cf6 added. We now have 1 listener(s)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5390): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5390):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5390):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5390):     - Bluetooth MAC address: F8:95:C7:87:85:54
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5390):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5390):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5390):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5390):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5390):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5390):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5390): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e249cd added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5390): addListener: New listener added - the number of listeners is now 1
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/BluetoothAdapterService(514407089)( 2021): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1753de0f
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5390): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 5390): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 5390): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
W/System.err( 5390): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 5390): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 5390): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 5390): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 5390): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 5390): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 5390): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 5390): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 5390): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 5390): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5390): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5390): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/art     ( 5427): Suspending all threads took: 48.351ms
D/JX-Cordova( 5390): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5390): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5390): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2641282 added. We now have 2 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5390): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5390): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14cbad93 added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5390): addListener: New listener added - the number of listeners is now 1
,D/BluetoothAdapterService(514407089)( 2021): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1753de0f
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5390): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 5390): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 5390): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
W/System.err( 5390): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 5390): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 5390): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 5390): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 5390): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 5390): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 5390): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 5390): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 5390): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 5390): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5390): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5390): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PhoneMonitor( 5495): Register our PhoneStateListener
,I/ActivityManager(  946): Killing 5117:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,I/vclib   ( 5427): onServiceConnected
,W/Babel   ( 5427): Attempted to change video mute state without an active call.
W/ResourcesManager( 5427): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5427): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/libprocessgroup(  946): failed to open /acct/uid_10086/pid_5117/cgroup.procs: No such file or directory
,D/PhoneMonitor( 5495): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 5495): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 5495): [parse] Load xml
D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/CheckinService( 4331): Checkin interval check for package: unspecified last checkin: 1456940219980 min interval config: 0 actual interval: 1335
V/TelephonyAutoProfiling( 5495): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5495): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,I/CheckinService( 4331): Checking schedule, now: 1456940221336 next: 1456940249934
I/CheckinService( 4331): active receiver: disabled
D/PhoneMonitor( 5495): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
V/JNIHelp ( 5427): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 5427): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5427): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 5427): com.google.android.talk: cancel(10436) by com.google.android.talk
I/ActivityManager(  946): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5525 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/AudioManager( 5170): getMode name:com.lge.qremote
,I/AudioManager( 5170): getMode name:com.lge.qremote
I/AudioManager( 5170): getMode name:com.lge.qremote
,I/AudioManager( 5170): getMode name:com.lge.qremote
,I/AudioManager( 5170): getMode name:com.lge.qremote
D/UEI.SmartControl( 5525): Quickset Services start...
,I/UEI.SmartControl( 5525): Manufacture = LGE
D/UEI.SmartControl( 5525): File observer start...
,E/UEI.SmartControl( 5525): IR Port is disabled: false
D/UEI.SmartControl( 5525): Starting file observer...
D/UEI.SmartControl( 5525): Extracting JNI libs...
D/UEI.SmartControl( 5525): --- this system supports 32-bit or 64-bit only
D/LocationInitializer( 4331): Restart initialization of location
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1733): [83] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
I/AudioManager( 5170): getMode name:com.lge.qremote
,I/AudioManager( 5170): getMode name:com.lge.qremote
,W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
I/AudioManager( 5170): getMode name:com.lge.qremote
D/UEI.SmartControl( 5525): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 5525): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5525): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/NotificationManager( 5427): com.google.android.talk: cancel(8) by com.google.android.talk
,I/art     ( 1733): Explicit concurrent mark sweep GC freed 29501(1683KB) AllocSpace objects, 7(112KB) LOS objects, 40% free, 13MB/22MB, paused 1.725ms total 99.530ms
,I/UEI.SmartControl( 5525): --- Selecting new region: 2
I/UEI.SmartControl( 5525): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 5525): Platform has CIR...
D/UEI.SmartControl( 5525): NO CIR support, need to check package...
I/UEI.SmartControl( 5525): Model: LG-D722 uses JNI
,D/UEI.SmartControl( 5525): QS Service created
I/ActivityManager(  946): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5559 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/art     (  946): Explicit concurrent mark sweep GC freed 30562(1610KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 2.054ms total 167.024ms
,E/UEI.SmartControl( 5525): QS start get config
,D/UEI.SmartControl( 5525): Loading JNI Libs...
,D/UEI.SmartControl( 5525):  configuring local db...
I/AppUp4:AppBoxCP( 5559): onCreate
,W/AppUp4:DB( 5559):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 5559):  setFingerPrint start
,I/AppUp4:DB( 5559):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 5559):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5559):  SDK version = 0
,I/AppUp4:DB( 5559):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 5559): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 5559): onReceive
I/AppUp4:CustModeStarterReceiver( 5559): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 5559): Context : android.app.ReceiverRestrictedContext@70aef1f
D/AppUp4:CustFacade( 5559): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5559): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 5559): begin check event
I/AppUp4:CustModeStarterReceiver( 5559): Event For Nothing, skip.
,I/ActivityManager(  946): Killing 5191:com.android.settings/1000 (adj 15): empty #11
W/libprocessgroup(  946): failed to open /acct/uid_1000/pid_5191/cgroup.procs: No such file or directory
,I/ActivityManager(  946): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5580 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
D/InitAlarmsService( 3817): Clearing and rescheduling alarms.
D/UEI.SmartControl( 5525):  ---- Has DB8: true
,D/UEI.SmartControl( 5525): QS start statue = true Error code = 0
D/UEI.SmartControl( 5525): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5525): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/CalendarProvider2( 5325): Scheduling check of next Alarm
D/UEI.SmartControl( 5525): IRRCDataComm has AudioManager!!!!.
D/CalendarProvider2( 5325): SCHEDULE_ALARM_REMOVE
W/irrc_jni( 5525): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5525): IrrcClient ++ 
D/irrcClient( 5525): getIrrcService ++ 
D/irrcClient( 5525): getIrrcService -- 
D/irrcClient( 5525): IrrcClient -- 
W/irrc_jni( 5525): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 5525): Services init done
I/UEI.SmartControl( 5525): Device manager: loading config....
D/UEI.SmartControl( 5525): QS Service init finished
D/UEI.SmartControl( 5525): QS Service version name: 0.1.73
D/UEI.SmartControl( 5525): QS Service version code: 1073
D/UEI.SmartControl( 5525): Config is loaded...
,D/UEI.SmartControl( 5525): Service requested: Control
D/UEI.SmartControl( 5525): Internal service binding...
D/UEI.SmartControl( 5525): -----IControl: 11
D/UEI.SmartControl( 5525): Caller: com.lge.qremote
D/UEI.SmartControl( 5525): ------------ IControl registerCallback...
I/UEI.SmartControl( 5525): Registering callback...
,D/UEI.SmartControl( 5525): -----IControl: 19
D/UEI.SmartControl( 5525): Caller: com.lge.qremote
I/UEI.SmartControl( 5525): Registering Services Ready callback...
I/UEI.SmartControl( 5525): Notify client services are ready...
D/UEI.SmartControl( 5525): -----IControl: 8
D/UEI.SmartControl( 5525): Caller: com.lge.qremote
W/ResourcesManager( 5580): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5580): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5580): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/ActivityManager(  946): Killing 4180:com.android.defcontainer/u0a4 (adj 15): empty #11
D/UEI.SmartControl( 5525):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 5525): Notify AllClients services are ready: 0
I/ActivityManager(  946): Killing 5214:com.lge.sync/1000 (adj 15): empty #12
,W/libprocessgroup(  946): failed to open /acct/uid_10004/pid_4180/cgroup.procs: No such file or directory
,W/libprocessgroup(  946): failed to open /acct/uid_1000/pid_5214/cgroup.procs: No such file or directory
I/ActivityManager(  946): Killing 5151:com.lge.clock/u0a10 (adj 15): empty #11
W/libprocessgroup(  946): failed to open /acct/uid_10010/pid_5151/cgroup.procs: No such file or directory
,I/AppConfig( 5580): Total System Memory = 906309632
I/GalleryUtils( 5580): Application Heap = 96 MB
I/AppConfig( 5580): App Tier : NOT_DEF
,D/SystemHelper( 5580): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager(  946): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5609 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  946): Killing 3817:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  946): failed to open /acct/uid_10013/pid_3817/cgroup.procs: No such file or directory
,W/ResourcesManager( 5609): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5609): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 5609): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 5609): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5609): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 5609): BUILD Country: EU
I/SystemConfig( 5609): BUILD Operator: OPEN
,I/ActivityManager(  946): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5628 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  946): Killing 5247:com.lge.bnr/1000 (adj 15): empty #11
W/libprocessgroup(  946): failed to open /acct/uid_1000/pid_5247/cgroup.procs: No such file or directory
,I/SystemConfig( 5609): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5609): existFile = false
I/SystemConfig( 5609): canReadFile = false
I/SystemConfig( 5609): systemFeature RCS result false
D/SystemConfig( 5609): refreshRcsSupport() :false
I/LockScreenSettings( 5628): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 5628): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5628): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5628): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5628): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5628): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  946): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5645 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  946): Killing 5267:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  946): failed to open /acct/uid_10081/pid_5267/cgroup.procs: No such file or directory
,W/ResourcesManager( 5645): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/CheckinService( 4331): Done disabling old GoogleServicesFramework version
I/CalendarProvider2( 5325): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 5325): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  946): Killing 5350:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  946): failed to open /acct/uid_10053/pid_5350/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 1941): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  946): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5670 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  946): Killing 5495:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  946): failed to open /acct/uid_10038/pid_5495/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 1941): UpdateCorporaTask done [took 180 ms] updated apps [took 179 ms] 
,D/Finsky  ( 5670): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 5670): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5670): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5670): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5670): com.android.vending: cancel(-1050172287) by com.android.vending
,I/ActivityManager(  946): Killing 5525:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,V/AlarmManager(  946): RTC_WAKEUP set : Alarm{25082e7d type 0 when 1456940224156 com.google.android.googlequicksearchbox} when 1456940224156
D/Ads     ( 5670): Skipping gmscore version check
W/System.err( 5170): android.os.DeadObjectException
,W/System.err( 5170): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5170): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5170): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5170): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5170): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5170): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5170): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5170): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5170): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5170): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5170): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5170): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5170): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5170): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5170): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5170): android.os.DeadObjectException
W/System.err( 5170): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5170): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5170): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5170): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5170): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5170): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5170): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5170): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5170): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5170): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5170): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5170): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5170): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5170): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5170): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
D/Finsky  ( 5670): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5670): [1] Libraries$2.run: Finished loading 1 libraries.
,V/DownloadManager( 3223): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,W/libprocessgroup(  946): failed to open /acct/uid_10089/pid_5525/cgroup.procs: No such file or directory
V/DownloadManager( 3223): created cursor android.database.sqlite.SQLiteCursor@205d6fda on behalf of 5670
I/ActivityManager(  946): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5734 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/PackageBroadcastService( 4331): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/ActivityManager(  946): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=5752 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/PackageBroadcastService( 4331): Null package name or gms related package.  Ignoreing.
,D/UEI.SmartControl( 5734): Quickset Services start...
I/UEI.SmartControl( 5734): Manufacture = LGE
D/UEI.SmartControl( 5734): File observer start...
E/UEI.SmartControl( 5734): IR Port is disabled: false
D/UEI.SmartControl( 5734): Starting file observer...
D/UEI.SmartControl( 5734): Extracting JNI libs...
D/UEI.SmartControl( 5734): --- this system supports 32-bit or 64-bit only
D/Finsky  ( 5670): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5670): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
W/ResourcesManager( 5752): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5752): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 5752): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/Icing   ( 4331): Storage manager: low false usage 1.72MB avail 2.37GB capacity 4.06GB
D/UEI.SmartControl( 5734): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5734): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5734): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 5734): --- Selecting new region: 2
,I/UEI.SmartControl( 5734): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 5734): Platform has CIR...
D/UEI.SmartControl( 5734): NO CIR support, need to check package...
I/UEI.SmartControl( 5734): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5734): QS Service created
E/UEI.SmartControl( 5734): QS start get config
,D/UEI.SmartControl( 5734): Loading JNI Libs...
D/UEI.SmartControl( 5734):  configuring local db...
I/LGEmail ( 5752): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,I/art     ( 3978): Explicit concurrent mark sweep GC freed 3214(125KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 858us total 32.107ms
D/LGEmail ( 5752): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/PackageChangeReceiver( 5752): intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
,I/Icing   ( 4331): updateResources: need to parse f{com.google.android.gms}
D/UEI.SmartControl( 5734):  ---- Has DB8: true
,D/UEI.SmartControl( 5734): QS start statue = true Error code = 0
D/UEI.SmartControl( 5734): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5734): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5734): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 5734): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5734): IrrcClient ++ 
D/irrcClient( 5734): getIrrcService ++ 
D/irrcClient( 5734): getIrrcService -- 
D/irrcClient( 5734): IrrcClient -- 
W/irrc_jni( 5734): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5734): Services init done
,I/UEI.SmartControl( 5734): Device manager: loading config....
I/ActivityManager(  946): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5790 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  946): Killing 5170:com.lge.qremote/u0a106 (adj 15): empty #11
,I/art     (  301): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 295us total 22.408ms
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 20.281ms
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 20.735ms
,D/UEI.SmartControl( 5734): Config is loaded...
D/UEI.SmartControl( 5734):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 5734): Notify AllClients services are ready: 0
W/libprocessgroup(  946): failed to open /acct/uid_10106/pid_5170/cgroup.procs: No such file or directory
D/UEI.SmartControl( 5734): QS Service init finished
D/UEI.SmartControl( 5734): QS Service version name: 0.1.73
D/UEI.SmartControl( 5734): QS Service version code: 1073
D/UEI.SmartControl( 5734): Service requested: Control
I/ActivityManager(  946): Killing 5559:com.lge.appbox.client/u0a11 (adj 15): empty #11
,D/UEI.SmartControl( 5734): Internal service binding...
W/libprocessgroup(  946): failed to open /acct/uid_10011/pid_5559/cgroup.procs: No such file or directory
I/ActivityManager(  946): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5813 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  946): Killing 5325:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/libprocessgroup(  946): failed to open /acct/uid_10014/pid_5325/cgroup.procs: No such file or directory
,I/Icing   ( 4331): Internal init done: storage state 0
,I/AppUp4:AppBoxCP( 5813): onCreate
,W/AppUp4:DB( 5813):  [AppBoxDatabaseHelper] construct
I/Icing   ( 4331): Post-init done
I/AppUp4:DB( 5813):  setFingerPrint start
I/AppUp4:DB( 5813):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/Icing   ( 4331): updateResources: need to parse f{com.google.android.gms}
I/AppUp4:DB( 5813):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5813):  SDK version = 0
I/AppUp4:DB( 5813):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 5813): AppBoxApplication onCreate()
,I/ThermalEngine(  288): Sensor:pa_therm0:32000 mC
D/AppUp4:PreloadHelper( 5813): removed from Exclude : com.test.thalitest : 1
,I/ActivityManager(  946): Killing 5580:com.android.gallery3d/u0a23 (adj 15): empty #11
W/libprocessgroup(  946): failed to open /acct/uid_10023/pid_5580/cgroup.procs: No such file or directory
,I/ActivityManager(  946): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5830 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 5830): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5830): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5830): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/AppConfig( 5830): Total System Memory = 906309632
,I/GalleryUtils( 5830): Application Heap = 96 MB
I/AppConfig( 5830): App Tier : NOT_DEF
D/SystemHelper( 5830): region [EU], country [EU], operator [OPEN], sub-operator []
I/LockScreenSettings( 5628): New app installed broadcast received ..
,I/LockScreenSettings( 5628): Number of installed packages  1
I/ActivityManager(  946): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=5853 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  946): Killing 5039:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
W/libprocessgroup(  946): failed to open /acct/uid_10006/pid_5039/cgroup.procs: No such file or directory
,D/EulaProviderUpdateObserver( 5853): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 5853): uri : package:com.test.thalitest
,I/ActivityManager(  946): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=5870 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  946): Killing 5645:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  946): failed to open /acct/uid_10086/pid_5645/cgroup.procs: No such file or directory
,I/chromium( 5390): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
I/chromium( 5390): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
,D/[BNRAppListMgrReceiver]( 5870): android.intent.action.PACKAGE_ADDED : com.test.thalitest
,W/MainApplication( 5870): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,I/ActivityManager(  946): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5887 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/ActivityManager(  946): Killing 5734:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/libprocessgroup(  946): failed to open /acct/uid_10089/pid_5734/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/Icing   ( 4331): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/Icing   ( 4331): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 4331): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/GAv4    ( 5887): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5887):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5887):   adb logcat -s GAv4
,W/GAv4    ( 5887): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5887): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5887): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 5887): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
,I/ActivityManager(  946): Killing 5752:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  946): failed to open /acct/uid_10021/pid_5752/cgroup.procs: No such file or directory
,I/ActivityManager(  946): Killing 5427:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  946): failed to open /acct/uid_10061/pid_5427/cgroup.procs: No such file or directory
,I/ActivityManager(  946): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5919 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  946): Killing 5670:com.android.vending/u0a36 (adj 15): empty #11
W/ResourcesManager( 5887): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5887): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5887): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
I/art     ( 5887): CheckpointMarkThreadRoots callback created = 0xaaf2c230
,W/libprocessgroup(  946): failed to open /acct/uid_10036/pid_5670/cgroup.procs: No such file or directory
,I/art     ( 5887): CheckpointMarkThreadRoots callback created = 0xaaf2c200
,W/ResourcesManager( 5919): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/NotificationManager( 5887): com.google.android.apps.docs: cancel(10436) by com.google.android.apps.docs
V/JNIHelp ( 5887): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 5887): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5887): Installed default security provider GmsCore_OpenSSL
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  946): ELAPSED_WAKEUP set : Alarm{2038c585 type 2 when 85290 com.android.providers.calendar} when 85290
,I/art     (  946): Explicit concurrent mark sweep GC freed 23379(1137KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 2.625ms total 166.265ms
,I/ActivityManager(  946): Killing 5790:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,W/libprocessgroup(  946): failed to open /acct/uid_10009/pid_5790/cgroup.procs: No such file or directory
,I/ActivityManager(  946): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5962 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1941): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/UpdateIcingCorporaServi( 1941): UpdateCorporaTask done [took 102 ms] updated apps [took 102 ms] 
,D/Finsky  ( 5962): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 5962): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5962): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5962): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5962): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3223): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3223): created cursor android.database.sqlite.SQLiteCursor@1c793c0b on behalf of 5962
I/NotificationManager( 5962): com.android.vending: cancel(1003285959) by com.android.vending
D/Finsky  ( 5962): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5962): [1] Libraries$2.run: Finished loading 1 libraries.
D/PackageBroadcastService( 4331): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/Finsky  ( 5962): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Ads     ( 5962): Skipping gmscore version check
D/ChimeraCfgMgr( 4331): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4331): Loading module APK com.google.android.play.games
,D/Finsky  ( 5962): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/Finsky  ( 5962): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/ChimeraCfgMgr( 4331): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4331): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 4331): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 4331): Submit a task: k
,D/ChimeraCfgMgr( 4331): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 4331): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 4331): Processing package: com.test.thalitest
D/GassUtils( 4331): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
,D/k       ( 4331): Found info for package com.test.thalitest in db.
I/ActivityManager(  946): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=6023 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,I/PeopleDatabaseHelper( 4331): cleanUpNonGplusAccounts done.
,W/BaseAppContext( 4331): Using Auth Proxy for data requests.
W/BaseAppContext( 4331): Using Auth Proxy for data requests.
E/ActivityThread( 4331): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  946): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 77123, reason: UserStart, SyncResult: databaseError: true stats []
D/SyncManager(  946): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 148477, reason: UserStart
I/NotificationManager(  946): android: cancelAsUser(716319171) by android
,W/BaseAppContext( 4331): Using Auth Proxy for data requests.
,I/ActivityManager(  946): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=6052 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
,I/art     ( 4331): Explicit concurrent mark sweep GC freed 48499(3MB) AllocSpace objects, 26(416KB) LOS objects, 24% free, 13MB/17MB, paused 903us total 89.313ms
,W/SQLiteConnectionPool( 4331): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,W/BaseAppContext( 4331): Using Auth Proxy for data requests.
,W/BaseAppContext( 4331): Using Auth Proxy for data requests.
W/BaseAppContext( 4331): Using Auth Proxy for data requests.
W/BaseAppContext( 4331): Using Auth Proxy for data requests.
,I/ActivityManager(  946): Killing 5813:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  946): failed to open /acct/uid_10011/pid_5813/cgroup.procs: No such file or directory
,E/UpdateRequestReceiver( 6052): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 6052): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 6052): Received malformed URL while handling Gservices.CHANGED_ACTION
E/UpdateRequestReceiver( 6052): Received malformed URL while handling Gservices.CHANGED_ACTION
I/ActivityManager(  946): Killing 5830:com.android.gallery3d/u0a23 (adj 15): empty #11
W/libprocessgroup(  946): failed to open /acct/uid_10023/pid_5830/cgroup.procs: No such file or directory
,I/CheckinService( 4331): Checkin interval check for package: unspecified last checkin: 1456940219980 min interval config: 0 actual interval: 9001
,I/CheckinService( 4331): Checking schedule, now: 1456940228991 next: 1456940249934
I/CheckinService( 4331): active receiver: disabled
,I/SystemUpdateService( 4331): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,I/GservicesUpdateTask( 1941): Updating Gservices keys
D/SystemUpdateService( 4331): onCreate
D/SystemUpdateService( 4331): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/SystemUpdateService( 4331): cancelUpdate (empty URL)
I/SystemUpdateService( 4331): active receiver: disabled
,I/NotificationManager( 4331): com.google.android.gms: cancel(2130838165) by com.google.android.gms
I/NotificationManager( 4331): com.google.android.gms: cancel(2130838166) by com.google.android.gms
,I/art     ( 3978): Explicit concurrent mark sweep GC freed 4079(174KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 418us total 35.360ms
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/NotificationManager( 1941): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/art     ( 3978): Explicit concurrent mark sweep GC freed 2755(107KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 605us total 24.340ms
,I/Icing   ( 4331): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/art     ( 4331): Explicit concurrent mark sweep GC freed 14495(930KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 14MB/19MB, paused 5.356ms total 93.624ms
,D/ChimeraCfgMgr( 4331): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4331): Module APK com.google.android.play.games already loaded
D/SystemUpdateService( 4331): onDestroy
,I/Icing   ( 4331): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
E/DynamiteModule( 4331): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 4331): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /vendor/lib, /system/lib]]
E/DynamiteModule( 4331): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 4331): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/DynamiteModule( 4331): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/DynamiteModule( 4331): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 4331): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 4331): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 4331): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 4331): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 4331): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 4331): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2663)
E/DynamiteModule( 4331): 	at android.app.ActivityThread.access$1700(ActivityThread.java:155)
E/DynamiteModule( 4331): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1400)
E/DynamiteModule( 4331): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 4331): 	at android.os.Looper.loop(Looper.java:135)
E/DynamiteModule( 4331): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/DynamiteModule( 4331): 	at java.lang.reflect.Method.invoke(Native Method)
E/DynamiteModule( 4331): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/DynamiteModule( 4331): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/DynamiteModule( 4331): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/DynamiteModule( 4331): 	Suppressed: java.lang.ClassNotFoundException: com.google.android.gms.chimera.container.DynamiteLoaderImpl
E/DynamiteModule( 4331): 		at java.lang.Class.classForName(Native Method)
E/DynamiteModule( 4331): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/DynamiteModule( 4331): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/DynamiteModule( 4331): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/DynamiteModule( 4331): 		... 17 more
E/DynamiteModule( 4331): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
,I/DynamiteModule( 4331): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
I/DynamiteModule( 4331): Selected local version of com.google.android.gms.flags
D/SystemEventReceiver( 4331): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 4331): Updating ocr activity enabled=false
,W/ActivityManager(  946): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/OcrModelManager( 4331): Updating downloaded model state (gservices changed)
,I/NotificationManager(  946): android: cancelAsUser(-591465577) by android
,I/art     ( 3978): Explicit concurrent mark sweep GC freed 2566(102KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 932us total 25.962ms
,D/GCM     ( 1733): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,I/[SystemUI]QPairHandler( 1379): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/InputReader(  946): Reconfiguring input devices.  changes=0x00000010
D/administrator(  946): Handling package changes for user 0
I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[SystemUI]QSlideListController( 1379): onReceive = android.intent.action.PACKAGE_CHANGED
,W/[SystemUI]QSlideLoader( 1379): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1379): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1379): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1379): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1379): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1379): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1379): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1379): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1379): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1379): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1379): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1379): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1379): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/NotificationService(  946): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  946): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  946): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  946): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  288): Sensor:pa_therm0:32000 mC
I/art     ( 1733): Explicit concurrent mark sweep GC freed 14284(952KB) AllocSpace objects, 20(320KB) LOS objects, 24% free, 13MB/18MB, paused 1.387ms total 124.775ms
,W/ResourcesManager(  946): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/BackupManagerService(  946): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  946): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@36c65eb9
,W/ResourceType(  946): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
,I/art     (  946): Explicit concurrent mark sweep GC freed 38517(1843KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 1.941ms total 157.714ms
,I/GCoreUlr( 1733): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
I/ActivityManager(  946): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6137 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  946): Killing 5609:com.android.contacts/u0a18 (adj 15): empty #11
,W/libprocessgroup(  946): failed to open /acct/uid_10018/pid_5609/cgroup.procs: No such file or directory
,I/GCoreNlp( 1733): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/LocationProviderProxy(  946): applying state to connected service
,I/GCoreUlr( 1733): DispatchingService.onCreate()
,W/GeofencerStateMachine( 1733): Ignoring removeGeofence because network location is disabled.
,E/ctxmgr  ( 1733): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
I/GCoreUlr( 1733): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,W/ctxmgr  ( 1733): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10006, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,E/ctxmgr  ( 1733): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
W/ActivityManager(  946): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/GCoreUlr( 1733): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/GCoreUlr( 1733): Unbound from all location providers
I/GCoreUlr( 1733): Place inference reporting - stopped
,I/GCoreUlr( 1733): DispatchingService.onDestroy()
I/GCoreUlr( 1733): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1733): Unbound from all location providers
I/GCoreUlr( 1733): Place inference reporting - stopped
I/Gmail   ( 6137): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 6137): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  946): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 6137): Error finding the version of the Email provider.....
E/Gmail   ( 6137): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6137): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6137): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6137): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6137): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6137): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6137): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6137): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6137): We do not support migrating this version of the Email provider.
,I/Gmail   ( 6137): getAccountsCursor
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  946): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6182 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,W/ActivityManager(  946): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/art     (  301): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 300us total 22.619ms
,I/ActivityManager(  946): Killing 5628:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
I/Gmail   ( 6137): Observing account changes for notifications
I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 22.697ms
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 21.853ms
,W/libprocessgroup(  946): failed to open /acct/uid_10069/pid_5628/cgroup.procs: No such file or directory
,W/ActivityManager(  946): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PhoneMonitor( 6182): Register our PhoneStateListener
,I/Gmail   ( 6137): notifyAccountChanged
I/Gmail   ( 6137): getAccountsCursor
I/Gmail   ( 6137): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6137): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6137): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/art     ( 3978): Explicit concurrent mark sweep GC freed 2887(113KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 420us total 27.132ms
I/Gmail   ( 6137): calculateUnknownSyncRationalesAndPurgeInBackground: running
V/SetupWizard( 6182): Connected to Gservices successfully
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PhoneMonitor( 6182): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
I/ActivityManager(  946): Killing 5853:com.lge.eula/1000 (adj 15): empty #11
V/TelephonyAutoProfiling( 6182): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6182): [parse] Load xml
V/TelephonyAutoProfiling( 6182): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6182): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6182): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  946): failed to open /acct/uid_1000/pid_5853/cgroup.procs: No such file or directory
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  946): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6212 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/Gmail   ( 6137): getAccountsCursor
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 6212): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/BluetoothManagerService(  946): Message: 20
,D/BluetoothManagerService(  946): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@123cc696:true
D/BluetoothAdapterService(514407089)( 2021): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1753de0f
D/BluetoothAdapterService(514407089)( 2021): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1753de0f
I/ActivityManager(  946): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6230 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 6212): Create singleton instance
,D/UEI.SmartControl( 6230): Quickset Services start...
,I/UEI.SmartControl( 6230): Manufacture = LGE
D/UEI.SmartControl( 6230): File observer start...
E/UEI.SmartControl( 6230): IR Port is disabled: false
D/UEI.SmartControl( 6230): Starting file observer...
D/UEI.SmartControl( 6230): Extracting JNI libs...
D/UEI.SmartControl( 6230): --- this system supports 32-bit or 64-bit only
I/AudioManager( 6212): getMode name:com.lge.qremote
,D/UEI.SmartControl( 6230): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6230): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6230): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/ActivityManager(  946): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver: pid=6253 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/UEI.SmartControl( 6230): --- Selecting new region: 2
I/UEI.SmartControl( 6230): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6230): Platform has CIR...
D/UEI.SmartControl( 6230): NO CIR support, need to check package...
I/UEI.SmartControl( 6230): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6230): QS Service created
,E/UEI.SmartControl( 6230): QS start get config
,D/UEI.SmartControl( 6230): Loading JNI Libs...
,D/UEI.SmartControl( 6230):  configuring local db...
V/AlarmManager(  946): RTC_WAKEUP set : Alarm{248f8d0f type 0 when 1456940232124 com.android.vending} when 1456940232124
,D/Finsky  ( 5962): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/NotificationManager(  946): android: cancelAsUser(2) by android
,I/MusicStore( 6253): Database version: 120
,D/libc-netbsd( 5962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  270): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  270): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  270): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  270): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  270): res_queryN name = xxxxx succeed
I/System.out( 5962): propertyValue:false
D/libc-netbsd( 5962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6253): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/UEI.SmartControl( 6230):  ---- Has DB8: true
,D/UEI.SmartControl( 6230): QS start statue = true Error code = 0
D/UEI.SmartControl( 6230): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6230): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6230): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6230): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6230): IrrcClient ++ 
D/irrcClient( 6230): getIrrcService ++ 
D/irrcClient( 6230): getIrrcService -- 
D/irrcClient( 6230): IrrcClient -- 
W/irrc_jni( 6230): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6230): Services init done
,I/UEI.SmartControl( 6230): Device manager: loading config....
D/UEI.SmartControl( 6230): Config is loaded...
D/UEI.SmartControl( 6230):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6230): Notify AllClients services are ready: 0
,I/art     (  946): Explicit concurrent mark sweep GC freed 14927(788KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 2.204ms total 142.573ms
,D/UEI.SmartControl( 6230): QS Service init finished
D/UEI.SmartControl( 6230): QS Service version name: 0.1.73
D/UEI.SmartControl( 6230): QS Service version code: 1073
D/UEI.SmartControl( 6230): Service requested: Control
D/UEI.SmartControl( 6230): Internal service binding...
D/UEI.SmartControl( 6230): -----IControl: 11
,D/UEI.SmartControl( 6230): Caller: com.lge.qremote
D/UEI.SmartControl( 6230): ------------ IControl registerCallback...
I/UEI.SmartControl( 6230): Registering callback...
D/UEI.SmartControl( 6230): -----IControl: 19
D/UEI.SmartControl( 6230): Caller: com.lge.qremote
I/UEI.SmartControl( 6230): Registering Services Ready callback...
I/UEI.SmartControl( 6230): Notify client services are ready...
D/UEI.SmartControl( 6230): -----IControl: 8
D/UEI.SmartControl( 6230): Caller: com.lge.qremote
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6253): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6253): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6253): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6253): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/libc-netbsd( 5962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,V/JNIHelp ( 6253): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ActivityThread( 6253): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6253): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@742f906: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6253): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6253): GMSCore installation verified
I/ConfigStore( 6253): Config Database version: 1
,I/MediaRouter( 6253): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/NetworkMonitor( 6253): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  946): Killing 5870:com.lge.bnr/1000 (adj 15): empty #11
,W/libprocessgroup(  946): failed to open /acct/uid_1000/pid_5870/cgroup.procs: No such file or directory
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  946): android: cancelAsUser(2) by android
,D/WearableService( 1733): callingUid 10006, callindPid: 1733
,I/NetworkMonitor( 6253): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  946): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6299 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicLeanback( 6253): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6253): Stop autocaching.
I/MusicLeanback( 6253): Stop autocaching.
,I/MusicLeanback( 6253): Stop autocaching.
,I/MusicLeanback( 6253): Stop autocaching.
,I/GHttpClientFactory( 6253): Using our fixed implementation of GMSCore's GoogleHttpClient
W/ResourcesManager( 6299): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/qtaguid ( 5962): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5962): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5962): untagSocket(41) failed with errno -22
I/GoogleURLConnFactory( 6253): Using platform SSLCertificateSocketFactory
D/Finsky  ( 5962): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/art     ( 6253): CheckpointMarkThreadRoots callback created = 0xaaf1b6d0
I/art     ( 6253): CheckpointMarkThreadRoots callback created = 0xaaf1b6a0
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  946): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6331 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/CalendarApplication( 6299): CalendarApplication.onCreate()
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PreferenceKeysParser( 6299): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6299): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@2cb072be, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@70aef1f, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@257d726c, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@1aced035, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2b7cfcca, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@27795e3b, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@26054958, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@1ea93ab1, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@33d61b96, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@3a95a317, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@431a304, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1e5d0ed, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@18d05b22, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@2ac759b3, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@7a7eb70, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@34db8ee9, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@183d076e, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@1753de0f, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@af84e9c, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@3c5530a5, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@29b62c7a, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@247a4c2b, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@1f89b888, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@250d3221, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@326a9646, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@314f8007, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@445d534, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@32e9cf5d, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@29a9d0d2, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@f5a15a3, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@1b0510a0, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@7f90459, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@3a30281e, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@17ee68ff, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@8ba96cc, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@3f2c8d15, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2c32a82a, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@3b4a961b, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2c6053b8, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@36d5e591, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@242b1cf6, lg_preferences_rece,nt_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@257278f
I/NotificationManager(  946): android: cancelAsUser(2) by android
D/GeneralPreferenceUtils( 6299): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6299): [init]
I/Config  ( 6299): LGCalendar ver.4.40.17
I/Config  ( 6299): start check model
I/Config  ( 6299): start check native_ca
I/NotificationManager( 6253): com.google.android.music: cancel(1061) by com.google.android.music
I/Config  ( 6299): Config Operator=OPEN, Country=EU
D/Config  ( 6299): [setDefaultValuesToPref]
D/Config  ( 6299): [parseProfiles]
E/GmsUtils( 6253): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 6253): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/ProfilesParser( 6299): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6299): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6299): [updateProfiletoCountryInfo]
D/GeneralPreference( 6299): [checkAndMigrateOldPreference]
I/ActivityManager(  946): Killing 5887:com.google.android.apps.docs/u0a58 (adj 15): empty #11
,W/ResourcesManager( 6331): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6331): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6331): VM with version 2.1.0 has multidex support
I/MultiDex( 6331): install
,I/MultiDex( 6331): VM has multidex support, MultiDex support library is disabled.
W/libprocessgroup(  946): failed to open /acct/uid_10058/pid_5887/cgroup.procs: No such file or directory
,D/AlertReceiver( 6299): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,V/JNIHelp ( 6331): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/InitNotificationRingtoneService( 6299): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 6299): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
I/AlertUtils( 6299): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6299): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6299): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,I/AlertUtils( 6299): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6299): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6299): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,I/AlertUtils( 6299): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6299): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6299): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
W/ActivityThread( 6331): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6331): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3e798fef: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6331): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 6331): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6331): com.google.android.gms: cancel(39789) by com.google.android.gms
I/AlertUtils( 6299): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6299): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 6299): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 6299): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6299): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6299): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
D/ChimeraCfgMgr( 6331): Reading stored module config
,I/AlertUtils( 6299): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6299): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 6299): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 6299): End InitializeAlertRingtoneService.onHandleIntent
,D/ChimeraCfgMgr( 6331): Loading module com.google.android.gms.car from APK com.google.android.gms
W/HolidayIntentService( 6299): onHandleIntent
,D/HolidayDataLoader( 6299): readJsonAsset : holiday.json
D/AlertService( 6299): 0 Action = android.intent.action.PROVIDER_CHANGED
,E/AgendaWidgetManager( 6299): [updateWidgets] 
D/MonthWidgetProvider( 6299): [onReceive]
D/CalendarWidgetProvider( 6299): [onReceive]
,D/CalendarWidgetProvider( 6299): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6299): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 6299): [onReceive]
D/CalendarWidgetProvider( 6299): [onReceive]
D/CalendarWidgetProvider( 6299): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6299): [onCreate] mContext.getPackageName() = com.android.calendar
E/HolidayIntentService( 6299): onHandleIntent:holiday data empty
,I/ActivityManager(  946): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6364 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/qtaguid ( 5962): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5962): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5962): untagSocket(41) failed with errno -22
,D/NativeLibraryUtils( 6331): Install completed successfully. count=14 extracted=0
,W/ResourcesManager( 6364): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/CAR.SERVICE( 6331): Connecting to CarCallService...
,D/CalendarProvider2( 6364): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@10b37240
,I/art     ( 6331): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CalendarProvider2( 6364): [getOrCreateCalendarAlarmManager]
I/art     ( 6331): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/CalendarProvider2( 6364): Created com.android.providers.calendar.CalendarAlarmManager@1aced035(com.android.providers.calendar.CalendarProvider2@10b37240)
D/CalendarProviderBroadcastReceiver( 6364): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6364): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 6364): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 6364): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6364): [getOrCreateCalendarAlarmManager]
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/CalendarProvider2( 6364): [IntentService] Release Lock
,D/CalendarProvider2( 6364): CalendarProviderIntentService.onDestroy()
D/CAR.SERVICE( 6331): com.google.android.projection.gearhead isn't installed.
I/ActivityManager(  946): Killing 5919:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/art     ( 5962): CheckpointMarkThreadRoots callback created = 0xb05624a0
,W/libprocessgroup(  946): failed to open /acct/uid_10086/pid_5919/cgroup.procs: No such file or directory
D/CAR.TEL.Service( 6331): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6331): Creating a new PhoneAdapter instance
I/art     ( 5962): CheckpointMarkThreadRoots callback created = 0xb0562470
,I/ActivityManager(  946): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6386 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  946): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6331): setListener: com.google.android.gms.car.dn@2461838a
D/CAR.SERVICE( 6331): Package validated; name: com.android.vending
,W/ActivityManager(  946): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6331): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6331): Starting CarCallService with initial phone null
I/NotificationManager( 6331): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 5962): com.android.vending: cancel(10436) by com.android.vending
V/Finsky  ( 5962): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,W/ResourcesManager( 6386): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 92289398615; DSPS: 3122915; Offset : -3021178952
,I/Babel_SMS( 6386): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6386): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6386): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6386): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6386): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6386): MmsConfig.loadFromResources
E/Babel_SMS( 6386): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6386): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/art     ( 6386): CheckpointMarkThreadRoots callback created = 0xb042d8a0
,D/SensorManager( 6386): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6386): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6386): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6386): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6386): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6386): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6386): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6386): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6386): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6386): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6386): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6386): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6386): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6386): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6386): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6386): found sensor: Motion Accel, handle=46
,I/art     ( 6386): CheckpointMarkThreadRoots callback created = 0xb042d890
,W/Settings( 6386): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6386): startup - clean
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  946): android: cancelAsUser(2) by android
I/Babel   ( 6386): deleted: false for 0
,I/art     (  946): Explicit concurrent mark sweep GC freed 13630(649KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.198ms total 138.989ms
,W/AudioCapabilities( 6386): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6386): Unsupported mime audio/adpcm
W/AudioCapabilities( 6386): Unsupported mime audio/g726
W/AudioCapabilities( 6386): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6386): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6386): Unsupported mime video/mjpg
W/VideoCapabilities( 6386): Unsupported mime video/theora
,I/ActivityManager(  946): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6429 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/AudioCapabilities( 6386): Unsupported mime audio/evrc
,W/AudioCapabilities( 6386): Unsupported mime audio/qcelp
W/VideoCapabilities( 6386): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6386): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6386): Unsupported mime audio/qcelp
W/AudioCapabilities( 6386): Unsupported mime audio/evrc
,W/VideoCapabilities( 6386): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6386): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6386): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6386): Unrecognized profile 2130706433 for video/avc
,I/AppUp4:AppBoxCP( 6429): onCreate
W/AppUp4:DB( 6429):  [AppBoxDatabaseHelper] construct
W/VideoCapabilities( 6386): Unrecognized profile 2130706433 for video/avc
I/AppUp4:DB( 6429):  setFingerPrint start
I/AppUp4:DB( 6429):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,W/VideoCapabilities( 6386): Unrecognized profile 2130706433 for video/avc
I/qtaguid ( 5962): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5962): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5962): untagSocket(41) failed with errno -22
,I/AppUp4:DB( 6429):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6429):  SDK version = 0
I/AppUp4:DB( 6429):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6429): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 6429): onReceive
,I/AppUp4:CustModeStarterReceiver( 6429): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
W/art     ( 6386): Suspending all threads took: 6.789ms
D/AppUp4:CustFacade( 6429): Context : android.app.ReceiverRestrictedContext@70aef1f
D/AppUp4:CustFacade( 6429): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6429): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6429): begin check event
I/AppUp4:CustModeStarterReceiver( 6429): Event For Nothing, skip.
I/ActivityManager(  946): Killing 6023:com.google.android.partnersetup/u0a9 (adj 15): empty #11
W/libprocessgroup(  946): failed to open /acct/uid_10009/pid_6023/cgroup.procs: No such file or directory
,I/vclib   ( 6386): onServiceConnected
W/Babel   ( 6386): Attempted to change video mute state without an active call.
I/NotificationManager( 6386): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 6386): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6386): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  946): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6454 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,V/JNIHelp ( 6386): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/ThermalEngine(  288): Sensor:pa_therm0:32000 mC
,W/ResourcesManager( 6454): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6454): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6454): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,W/System  ( 6386): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6386): Installed default security provider GmsCore_OpenSSL
,W/ResourcesManager( 5962): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5962): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/NotificationManager( 6386): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/AppConfig( 6454): Total System Memory = 906309632
,I/GalleryUtils( 6454): Application Heap = 96 MB
I/AppConfig( 6454): App Tier : NOT_DEF
D/SystemHelper( 6454): region [EU], country [EU], operator [OPEN], sub-operator []
W/ResourcesManager( 5962): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  946): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6481 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  946): Killing 6052:com.google.android.configupdater/u0a3 (adj 15): empty #11
W/libprocessgroup(  946): failed to open /acct/uid_10003/pid_6052/cgroup.procs: No such file or directory
,D/Finsky  ( 5962): [1] DailyHygiene.access$600: Logging device features
V/AlarmManager(  946): RTC_WAKEUP set : Alarm{2e76b0aa type 0 when 1456940235461 com.android.vending} when 1456940235461
,W/ResourcesManager( 6481): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6481): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6481): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6481): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6481): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/DeviceConnectionService( 1733): client connected with version: 8296000
,D/Finsky  ( 5962): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 5962): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/ActivityManager(  946): Killing 6253:com.google.android.music:main/u0a81 (adj 15): empty #11
,I/ActivityManager(  946): Killing 6137:com.google.android.gm/u0a53 (adj 15): empty #12
,W/libprocessgroup(  946): failed to open /acct/uid_10081/pid_6253/cgroup.procs: No such file or directory
,W/libprocessgroup(  946): failed to open /acct/uid_10053/pid_6137/cgroup.procs: No such file or directory
I/SystemConfig( 6481): BUILD Country: EU
I/SystemConfig( 6481): BUILD Operator: OPEN
,I/ActivityManager(  946): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6507 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  946): Killing 6230:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
I/art     (  301): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 24.599ms
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 22.085ms
,W/System.err( 6212): android.os.DeadObjectException
W/System.err( 6212): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6212): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6212): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6212): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 6212): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6212): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6212): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6212): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6212): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6212): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6212): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6212): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6212): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6212): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6212): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6212): android.os.DeadObjectException
W/System.err( 6212): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6212): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6212): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6212): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 6212): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6212): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6212): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6212): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6212): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6212): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6212): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6212): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6212): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6212): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6212): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 23.769ms
,W/libprocessgroup(  946): failed to open /acct/uid_10089/pid_6230/cgroup.procs: No such file or directory
W/ActivityManager(  946): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/SystemConfig( 6481): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6481): existFile = false
I/SystemConfig( 6481): canReadFile = false
I/SystemConfig( 6481): systemFeature RCS result false
D/SystemConfig( 6481): refreshRcsSupport() :false
I/ActivityManager(  946): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6525 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/LockScreenSettings( 6507): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6507): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6507): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6507): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6507): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6507): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,D/UEI.SmartControl( 6525): Quickset Services start...
I/UEI.SmartControl( 6525): Manufacture = LGE
D/UEI.SmartControl( 6525): File observer start...
E/UEI.SmartControl( 6525): IR Port is disabled: false
D/UEI.SmartControl( 6525): Starting file observer...
D/UEI.SmartControl( 6525): Extracting JNI libs...
D/UEI.SmartControl( 6525): --- this system supports 32-bit or 64-bit only
,I/ActivityManager(  946): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6543 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  946): Killing 6212:com.lge.qremote/u0a106 (adj 15): empty #11
,D/UEI.SmartControl( 6525): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6525): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6525): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,W/libprocessgroup(  946): failed to open /acct/uid_10106/pid_6212/cgroup.procs: No such file or directory
,I/UEI.SmartControl( 6525): --- Selecting new region: 2
,I/UEI.SmartControl( 6525): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6525): Platform has CIR...
D/UEI.SmartControl( 6525): NO CIR support, need to check package...
I/UEI.SmartControl( 6525): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6525): QS Service created
W/ResourcesManager( 6543): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/UEI.SmartControl( 6525): QS start get config
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/UEI.SmartControl( 6525): Loading JNI Libs...
,D/UEI.SmartControl( 6525):  configuring local db...
I/UpdateIcingCorporaServi( 1941): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 4331): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/UpdateIcingCorporaServi( 1941): UpdateCorporaTask done [took 51 ms] updated apps [took 51 ms] 
,I/ActivityManager(  946): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6573 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/UEI.SmartControl( 6525):  ---- Has DB8: true
,I/PackageBroadcastService( 4331): Null package name or gms related package.  Ignoreing.
D/UEI.SmartControl( 6525): QS start statue = true Error code = 0
D/UEI.SmartControl( 6525): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6525): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6525): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6525): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6525): IrrcClient ++ 
D/irrcClient( 6525): getIrrcService ++ 
D/irrcClient( 6525): getIrrcService -- 
D/irrcClient( 6525): IrrcClient -- 
W/irrc_jni( 6525): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6525): Services init done
,I/UEI.SmartControl( 6525): Device manager: loading config....
D/UEI.SmartControl( 6525): QS Service init finished
D/UEI.SmartControl( 6525): QS Service version name: 0.1.73
D/UEI.SmartControl( 6525): QS Service version code: 1073
D/UEI.SmartControl( 6525): Service requested: Control
D/UEI.SmartControl( 6525): Config is loaded...
,I/Icing   ( 4331): updateResources: need to parse f{com.google.android.gms}
D/UEI.SmartControl( 6525):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 6525): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6525): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6525): Service.onUnbind: IControl
D/UEI.SmartControl( 6525): Service.onDestroy
D/UEI.SmartControl( 6525): Shutdown IRRCPlayer... 
W/irrc_jni( 6525): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6525): ~IrrcClient ++ 
D/irrcClient( 6525): ~IrrcClient -- 
W/irrc_jni( 6525): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6525): Blaster closed
D/UEI.SmartControl( 6525): Blaster closed
D/UEI.SmartControl( 6525): Shut down QS...
D/UEI.SmartControl( 6525): Stopped file observer...
,I/UEI.SmartControl( 6525): QS lib stop result = true
D/UEI.SmartControl( 6525): QS shutdown complete
D/UEI.SmartControl( 6525): QS Service created
E/UEI.SmartControl( 6525): QS start get config
,D/UEI.SmartControl( 6525):  configuring local db...
W/ActivityManager(  946): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/art     ( 1733): Explicit concurrent mark sweep GC freed 26325(1607KB) AllocSpace objects, 5(80KB) LOS objects, 40% free, 13MB/23MB, paused 2.163ms total 74.744ms
,I/Gmail   ( 6573): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 6573): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  946): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager(  946): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager(  946): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 6573): Error finding the version of the Email provider.....
E/Gmail   ( 6573): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6573): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6573): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6573): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6573): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6573): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6573): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6573): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6573): We do not support migrating this version of the Email provider.
,I/Gmail   ( 6573): getAccountsCursor
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6573): Observing account changes for notifications
,D/UEI.SmartControl( 6525):  ---- Has DB8: true
,I/ActivityManager(  946): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6622 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
D/UEI.SmartControl( 6525): QS start statue = true Error code = 0
D/UEI.SmartControl( 6525): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6525): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6525): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6525): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6525): IrrcClient ++ 
D/irrcClient( 6525): getIrrcService ++ 
D/irrcClient( 6525): getIrrcService -- 
D/irrcClient( 6525): IrrcClient -- 
W/irrc_jni( 6525): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6525): Services init done
I/UEI.SmartControl( 6525): Device manager: loading config....
D/UEI.SmartControl( 6525): Config is loaded...
I/ActivityManager(  946): Killing 6364:com.android.providers.calendar/u0a14 (adj 15): empty #11
D/UEI.SmartControl( 6525): QS Service init finished
,D/UEI.SmartControl( 6525): QS Service version name: 0.1.73
D/UEI.SmartControl( 6525): QS Service version code: 1073
D/UEI.SmartControl( 6525): Service requested: Control
D/UEI.SmartControl( 6525):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6525): Notify AllClients services are ready: 0
,I/ActivityManager(  946): Killing 6182:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  946): failed to open /acct/uid_10014/pid_6364/cgroup.procs: No such file or directory
,E/ActivityThread( 6525): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@1ea93ab1 that was originally bound here
E/ActivityThread( 6525): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@1ea93ab1 that was originally bound here
E/ActivityThread( 6525): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6525): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6525): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6525): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6525): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6525): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 6525): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 6525): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 6525): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6525): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6525): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6525): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6525): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6525): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6525): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6525): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6525): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/libprocessgroup(  946): failed to open /acct/uid_10038/pid_6182/cgroup.procs: No such file or directory
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 6525): Internal service binding...
,W/ResourcesManager( 6622): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  946): Message: 20
,D/BluetoothManagerService(  946): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2c392b9d:true
D/BluetoothAdapterService(514407089)( 2021): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1753de0f
D/BluetoothAdapterService(514407089)( 2021): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1753de0f
I/Gmail   ( 6573): notifyAccountChanged
,I/Gmail   ( 6573): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 6573): getAccountsCursor
I/Gmail   ( 6573): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/LGMDMManager( 6622): Create singleton instance
I/Gmail   ( 6573): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 6573): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/AudioManager( 6622): getMode name:com.lge.qremote
,D/UEI.SmartControl( 6525): -----IControl: 11
D/UEI.SmartControl( 6525): File observer start...
E/UEI.SmartControl( 6525): IR Port is disabled: false
D/UEI.SmartControl( 6525): Starting file observer...
D/UEI.SmartControl( 6525): Caller: com.lge.qremote
,I/Gmail   ( 6573): getAccountsCursor
D/UEI.SmartControl( 6525): ------------ IControl registerCallback...
I/UEI.SmartControl( 6525): Registering callback...
D/UEI.SmartControl( 6525): -----IControl: 19
D/UEI.SmartControl( 6525): Caller: com.lge.qremote
I/UEI.SmartControl( 6525): Registering Services Ready callback...
I/UEI.SmartControl( 6525): Notify client services are ready...
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AudioManager( 6622): getMode name:com.lge.qremote
D/UEI.SmartControl( 6525): -----IControl: 8
,D/UEI.SmartControl( 6525): Caller: com.lge.qremote
I/ActivityManager(  946): Killing 6429:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  946): failed to open /acct/uid_10011/pid_6429/cgroup.procs: No such file or directory
,E/MDM     ( 1733): [83] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 4331): Restart initialization of location
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
I/art     (  946): Explicit concurrent mark sweep GC freed 14470(674KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.424ms total 161.808ms
,W/GCoreFlp( 1733): No location to return for getLastLocation()
,W/FusedLocationProvider( 1733): location=null
D/Finsky  ( 5962): [724] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AudioManager( 6622): getMode name:com.lge.qremote
,I/AudioManager( 6622): getMode name:com.lge.qremote
I/NotificationManager(  946): android: cancelAsUser(2) by android
,I/AudioManager( 6622): getMode name:com.lge.qremote
,D/libc-netbsd( 5962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  270): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  270): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  270): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  270): res_queryN name = xxxxx, class = 1, type = 1
I/AudioManager( 6622): getMode name:com.lge.qremote
,D/libc-netbsd(  270): res_queryN name = xxxxx succeed
I/System.out( 5962): propertyValue:false
,I/Icing   ( 4331): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/Icing   ( 4331): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 4331): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/AlertService( 6299): Beginning updateAlertNotification
,W/PackageSettings(  946): Skipping PackageSetting{c5f2f7f com.example.hello/10317} due to missing metadata
,I/ActivityManager(  946): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6680 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6680): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6680): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@10b37240
,D/CalendarProvider2( 6680): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 6680): Created com.android.providers.calendar.CalendarAlarmManager@1aced035(com.android.providers.calendar.CalendarProvider2@10b37240)
D/AlertService( 6299): No fired or scheduled alerts
I/NotificationManager( 6299): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6299): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6299): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6299): com.android.calendar: cancel(3) by com.android.calendar
,I/NotificationManager( 6299): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6299): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6299): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6299): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6299): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6299): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6299): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6299): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6299): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6299): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6299): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6299): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6299): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6299): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6299): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6299): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6299): com.android.calendar: cancel(20) by com.android.calendar
I/ActivityManager(  946): Killing 6454:com.android.gallery3d/u0a23 (adj 15): empty #11
,D/AlertService( 6299): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
W/libprocessgroup(  946): failed to open /acct/uid_10023/pid_6454/cgroup.procs: No such file or directory
,D/AlarmScheduler( 6299): No events found starting within 1 week.
I/ActivityManager(  946): Killing 6299:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  946): failed to open /acct/uid_10013/pid_6299/cgroup.procs: No such file or directory
,D/CAR.SERVICE( 6331): mConnectedToCar = false, abort
,E/ActivityThread( 6331): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@32ca2032 that was originally bound here
E/ActivityThread( 6331): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@32ca2032 that was originally bound here
E/ActivityThread( 6331): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6331): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6331): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6331): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6331): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6331): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6331): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6331): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6331): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6331): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6331): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6331): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6331): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6331): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6331): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6331): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6331): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6331): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6331): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6331): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6331): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6331): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6331): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6331): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@356a39f5 that was originally bound here
E/ActivityThread( 6331): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@356a39f5 that was originally bound here
E/ActivityThread( 6331): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6331): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6331): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6331): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6331): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6331): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6331): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6331): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6331): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6331): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6331): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6331): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6331): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6331): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6331): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6331): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6331): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6331): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6331): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6331): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6331): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6331): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  946): Unbind failed: could not find connection for android.os.BinderProxy@19793c3b
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/ThermalEngine(  288): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  946): Killing 6386:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  946): failed to open /acct/uid_10061/pid_6386/cgroup.procs: No such file or directory
,E/UEI.SmartControl( 6525): file observer is disposed!
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/GAV2    ( 6573): Thread[GAThread,5,main]: No campaign data found.
,D/UEI.SmartControl( 6525): Internal timer expired: 2
,I/ActivityManager(  946): Killing 6481:com.android.contacts/u0a18 (adj 15): empty #11
,W/libprocessgroup(  946): failed to open /acct/uid_10018/pid_6481/cgroup.procs: No such file or directory
,I/ThermalEngine(  288): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/rmt_storage(  266): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  266): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  266): wakelock acquired: 1, error no: 42
,I/rmt_storage(  266): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
I/rmt_storage(  266): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  266): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  266): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  266): 
I/rmt_storage(  266): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
V/AlarmManager(  946): RTC_WAKEUP set : Alarm{2998904 type 0 when 1456940249312 com.android.vending} when 1456940249312
,V/AlarmManager(  946): RTC_WAKEUP set : Alarm{2036beed type 0 when 1456940249934 com.google.android.gms} when 1456940249934
I/CheckinService( 4331): Checkin interval check for package: unspecified last checkin: 1456940219980 min interval config: 0 actual interval: 30011
,W/ContextImpl( 3617): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/CheckinService( 4331): Checking schedule, now: 1456940250024 next: 1456940249934
I/CheckinService( 4331): active receiver: enabled
,I/CheckinService( 4331): Preparing to send checkin request
I/EventLogService( 4331): Accumulating logs since 1456940209519
,I/CheckinRequestBuilder( 4331): Checkin reason type: 3 attempt count: 1
,E/ActivityThread( 4331): Failed to find provider info for com.google.android.wearable.settings
I/ThermalEngine(  288): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/Finsky  ( 5962): [715] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5962): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  946): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6735 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 6735): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6735): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6735): VM with version 2.1.0 has multidex support
I/MultiDex( 6735): install
I/MultiDex( 6735): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6735): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6735): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6735): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3e798fef: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6735): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 6735): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 6735): com.google.android.gms: cancel(39789) by com.google.android.gms
D/LocationInitializer( 4331): Restart initialization of location
,D/WearableService( 1733): callingUid 10006, callindPid: 1733
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
,E/MDM     ( 1733): [105] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/art     ( 6735): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6735): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 6735): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  274): Instantiating CDM.
,I/WVCdm   (  274): CdmEngine::OpenSession
I/WVCdm   (  274): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  274): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/WVCdm   (  274): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  274): L1 library not specified. Falling Back to L3
I/WVCdm   (  274): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  274): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  274): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  274): CdmEngine::GenerateKeyRequest
D/WVCdm   (  274): PrepareKeyRequest: nonce=179094673
,I/art     ( 6735): CheckpointMarkThreadRoots callback created = 0xb042d600
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/art     ( 6735): CheckpointMarkThreadRoots callback created = 0xb042d5f0
,I/dex2oat ( 6779): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 6779): dex2oat took 88.012ms (threads: 4)
,I/Adreno-EGL( 6735): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6735): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6735): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6735): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6735): Remote Branch: 
I/Adreno-EGL( 6735): Local Patches: 
I/Adreno-EGL( 6735): Reconstruct Branch: 
,I/WVCdm   (  274): CdmEngine::OpenSession
,I/WVCdm   (  274): CdmEngine::CloseSession,
,I/WVCdm   (  274): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  274): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  274): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  274): CdmEngine::GenerateKeyRequest
D/WVCdm   (  274): PrepareKeyRequest: nonce=241034630
I/MusicWidget( 2623): mDelayedStopHandler : unbind
,I/MusicBrowser( 2686): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2686): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2686): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2686): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2686): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2686): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2686): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2686): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  946):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@247a4c2bcom.lge.music.MediaPlaybackService$6@1f89b888
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/MusicBrowser( 2686): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2686): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2686): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2686): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2686): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@33d61b96
,I/MusicBrowser( 2686): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2686): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2686): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2686): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2686): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2686): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2686): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2686): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2686): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2686): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2686): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2686): [MediaPlaybackService.java:6745:release()] oooooo 
,I/MusicBrowser( 2686): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2686): reset
V/MediaPlayer[Native]( 2686): setListener
V/MediaPlayer[Native]( 2686): disconnect
V/MediaPlayer[Native]( 2686): destructor
V/AudioFlinger(  274): releasing 19 from 2686 for -1
V/AudioFlinger(  274):  decremented refcount to 0
V/AudioFlinger(  274): purging stale effects
V/MediaPlayer[Native]( 2686): disconnect
,D/MusicBrowser( 2686): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2686): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2686): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2686): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2686): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2686): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2686): [SmartShareManagerClient] unregisterListener: 621621793
W/SmartShareClient( 2686): [SmartShareManagerClient] unregisterListener invalid listener: 621621793
I/SmartShareClient( 2686): [SmartShareManagerClient] terminate service: 2686/MediaPlaybackService/628978284
E/HomeCloudIF( 2686): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2686): [SmartShareManagerClient] unbindService context:android.app.Application@326a9646
,V/CloudHub( 2686): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2686): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2686): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2686): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2686): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/CloudHub( 2686): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29994
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 112290888244; DSPS: 3778324; Offset : -3021185491
,I/WVCdm   (  274): CdmEngine::CloseSession
I/WVCdm   (  274): L3 Terminate.
,I/Adreno-EGL( 6735): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6735): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6735): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6735): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6735): Remote Branch: 
I/Adreno-EGL( 6735): Local Patches: 
I/Adreno-EGL( 6735): Reconstruct Branch: 
,I/Adreno-EGL( 6735): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6735): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6735): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6735): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6735): Remote Branch: 
I/Adreno-EGL( 6735): Local Patches: 
I/Adreno-EGL( 6735): Reconstruct Branch: 
,I/ThermalEngine(  288): Sensor:pa_therm0:31000 mC
,I/CheckinRequestBuilder( 4331): Classify the device as Phone.
,D/libc-netbsd( 4331): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4331): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4331): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4331): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  270): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  270): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  270): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  270): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  270): res_queryN name = xxxxx succeed
I/System.out( 4331): propertyValue:false
D/libc-netbsd( 4331): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4331): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4331): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4331): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4331): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4331): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/CheckinTask( 4331): Sending checkin request (9813 bytes)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/CheckinRequestBuilder( 4331): Checkin reason type: 3 attempt count: 1
,E/ActivityThread( 4331): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinRequestBuilder( 4331): Classify the device as Phone.
,I/CheckinTask( 4331): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4331): Checking schedule, now: 1456940256695 next: 1457467505691
I/CheckinService( 4331): active receiver: disabled
,D/CheckinService( 4331): Recording last checkin time for package unspecified as 1456940256723
I/ActivityManager(  946): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6821 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  946): Killing 6543:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/ActivityManager(  946): Killing 6507:com.lge.lockscreensettings/u0a69 (adj 15): empty #12
,W/libprocessgroup(  946): failed to open /acct/uid_10086/pid_6543/cgroup.procs: No such file or directory
,W/libprocessgroup(  946): failed to open /acct/uid_10069/pid_6507/cgroup.procs: No such file or directory
D/PhoneMonitor( 6821): Register our PhoneStateListener
,V/SetupWizard( 6821): Connected to Gservices successfully
,I/ActivityManager(  946): Killing 6331:com.google.android.gms:car/u0a6 (adj 15): empty #11
D/PhoneMonitor( 6821): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6821): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6821): [parse] Load xml
V/TelephonyAutoProfiling( 6821): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6821): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6821): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  946): failed to open /acct/uid_10006/pid_6331/cgroup.procs: No such file or directory
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,V/AlarmManager(  946): ELAPSED_WAKEUP set : Alarm{292e85da type 2 when 116385 android} when 116385
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QPairHandler( 1379): onReceive = android.intent.action.PACKAGE_CHANGED
I/InputReader(  946): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/ActivityManager(  946): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6844 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/ThermalEngine(  288): Sensor:pa_therm0:31000 mC
,D/administrator(  946): Handling package changes for user 0
I/[SystemUI]QSlideListController( 1379): onReceive = android.intent.action.PACKAGE_CHANGED
,W/[SystemUI]QSlideLoader( 1379): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1379): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1379): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1379): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1379): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1379): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1379): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1379): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1379): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1379): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1379): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1379): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1379): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/ResourcesManager( 6844): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/NotificationService(  946): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  946): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  946): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  946): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/ResourcesManager(  946): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/BackupManagerService(  946): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  946): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3d5737a7
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
W/ResourceType(  946): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1733): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Babel_SMS( 6844): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6844): MmsConfig.loadMmsSettings
,D/LocationProviderProxy(  946): applying state to connected service
D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
,D/LCardEmulationManager( 1786): getDefaultRoute
I/art     ( 6844): CheckpointMarkThreadRoots callback created = 0xaaf21ec0
,I/art     (  946): Explicit concurrent mark sweep GC freed 33194(1910KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 23MB/35MB, paused 3.119ms total 167.916ms
I/Babel_SMS( 6844): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6844): MmsConfig.loadFromDatabase
,I/art     ( 6844): CheckpointMarkThreadRoots callback created = 0xaaf21ea0
,E/Babel_SMS( 6844): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6844): MmsConfig.loadFromResources
D/SensorManager( 6844): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6844): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6844): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6844): found sensor: LGE Proximity Sensor, handle=48
E/Babel_SMS( 6844): canonicalizeMccMnc: invalid mccmnc nullnull
D/SensorManager( 6844): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6844): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6844): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6844): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6844): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6844): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6844): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6844): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6844): found sensor: LGE Tilt Detector Sensor, handle=55
I/Babel_SMS( 6844): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6844): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6844): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6844): found sensor: Motion Accel, handle=46
W/Settings( 6844): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6844): startup - clean
,I/Babel   ( 6844): deleted: false for 0
,W/AudioCapabilities( 6844): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6844): Unsupported mime audio/adpcm
,W/AudioCapabilities( 6844): Unsupported mime audio/g726
W/AudioCapabilities( 6844): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6844): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6844): Unsupported mime video/mjpg
W/VideoCapabilities( 6844): Unsupported mime video/theora
I/ActivityManager(  946): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6890 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/AudioCapabilities( 6844): Unsupported mime audio/evrc
,W/AudioCapabilities( 6844): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6844): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6844): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6844): Unsupported mime audio/qcelp
W/AudioCapabilities( 6844): Unsupported mime audio/evrc
W/VideoCapabilities( 6844): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6844): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6844): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6844): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6844): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6844): Unrecognized profile 2130706433 for video/avc
I/AppUp4:AppBoxCP( 6890): onCreate
W/AppUp4:DB( 6890):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6890):  setFingerPrint start
I/AppUp4:DB( 6890):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6890):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6890):  SDK version = 0
I/AppUp4:DB( 6890):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6890): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 6890): onReceive
I/AppUp4:CustModeStarterReceiver( 6890): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 6890): Context : android.app.ReceiverRestrictedContext@70aef1f
D/AppUp4:CustFacade( 6890): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6890): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6890): begin check event
I/AppUp4:CustModeStarterReceiver( 6890): Event For Nothing, skip.
I/ActivityManager(  946): Killing 6573:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  946): failed to open /acct/uid_10053/pid_6573/cgroup.procs: No such file or directory
,I/ActivityManager(  946): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6911 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/vclib   ( 6844): onServiceConnected
W/Babel   ( 6844): Attempted to change video mute state without an active call.
I/NotificationManager( 6844): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 6844): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6844): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6911): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6911): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6911): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,V/JNIHelp ( 6844): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppConfig( 6911): Total System Memory = 906309632
I/GalleryUtils( 6911): Application Heap = 96 MB
,I/AppConfig( 6911): App Tier : NOT_DEF
W/System  ( 6844): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6844): Installed default security provider GmsCore_OpenSSL
D/SystemHelper( 6911): region [EU], country [EU], operator [OPEN], sub-operator []
I/NotificationManager( 6844): com.google.android.talk: cancel(10436) by com.google.android.talk
I/ActivityManager(  946): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6933 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  946): Killing 6680:com.android.providers.calendar/u0a14 (adj 15): empty #11
I/art     (  301): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 21.528ms
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 21.352ms
,W/libprocessgroup(  946): failed to open /acct/uid_10014/pid_6680/cgroup.procs: No such file or directory
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 21.349ms
W/ResourcesManager( 6933): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6933): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6933): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6933): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6933): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 6933): BUILD Country: EU
I/SystemConfig( 6933): BUILD Operator: OPEN
,W/ProcessCpuTracker(  946): Skipping unknown process pid 6863
,W/ProcessCpuTracker(  946): Skipping unknown process pid 6864
W/ProcessCpuTracker(  946): Skipping unknown process pid 6877
I/ActivityManager(  946): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6955 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  946): Killing 6525:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/ProcessCpuTracker(  946): Skipping unknown process pid 6878
W/ProcessCpuTracker(  946): Skipping unknown process pid 6950
W/System.err( 6622): android.os.DeadObjectException
W/System.err( 6622): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6622): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6622): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6622): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 6622): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6622): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6622): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6622): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6622): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6622): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6622): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6622): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6622): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6622): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6622): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6622): android.os.DeadObjectException
,W/System.err( 6622): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6622): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6622): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6622): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 6622): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6622): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6622): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6622): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6622): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6622): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6622): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6622): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6622): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6622): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6622): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  946): failed to open /acct/uid_10089/pid_6525/cgroup.procs: No such file or directory
W/ActivityManager(  946): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,I/SystemConfig( 6933): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6933): existFile = false
I/SystemConfig( 6933): canReadFile = false
I/SystemConfig( 6933): systemFeature RCS result false
D/SystemConfig( 6933): refreshRcsSupport() :false
,I/LockScreenSettings( 6955): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/ActivityManager(  946): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6973 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/LockScreenSettings( 6955): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 6955): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6955): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6955): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6955): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  946): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6993 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  946): Killing 6622:com.lge.qremote/u0a106 (adj 15): empty #11
,W/libprocessgroup(  946): failed to open /acct/uid_10106/pid_6622/cgroup.procs: No such file or directory
W/ResourcesManager( 6993): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6973): Quickset Services start...
,I/UEI.SmartControl( 6973): Manufacture = LGE
D/UEI.SmartControl( 6973): File observer start...
E/UEI.SmartControl( 6973): IR Port is disabled: false
D/UEI.SmartControl( 6973): Starting file observer...
D/UEI.SmartControl( 6973): Extracting JNI libs...
D/UEI.SmartControl( 6973): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 6973): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6973): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6973): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6973): --- Selecting new region: 2
,I/UEI.SmartControl( 6973): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6973): Platform has CIR...
D/UEI.SmartControl( 6973): NO CIR support, need to check package...
I/UEI.SmartControl( 6973): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6973): QS Service created
E/UEI.SmartControl( 6973): QS start get config
,D/UEI.SmartControl( 6973): Loading JNI Libs...
,D/UEI.SmartControl( 6973):  configuring local db...
I/UpdateIcingCorporaServi( 1941): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 4331): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4331): Null package name or gms related package.  Ignoreing.,
I/UpdateIcingCorporaServi( 1941): UpdateCorporaTask done [took 46 ms] updated apps [took 46 ms] 
,I/Icing   ( 4331): updateResources: need to parse f{com.google.android.gms}
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/UEI.SmartControl( 6973):  ---- Has DB8: true
,D/UEI.SmartControl( 6973): QS start statue = true Error code = 0
D/UEI.SmartControl( 6973): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6973): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6973): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6973): IRRCPlayer_nativeInit ++ 
,D/irrcClient( 6973): IrrcClient ++ 
D/irrcClient( 6973): getIrrcService ++ 
D/irrcClient( 6973): getIrrcService -- 
D/irrcClient( 6973): IrrcClient -- 
W/irrc_jni( 6973): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6973): Services init done
I/UEI.SmartControl( 6973): Device manager: loading config....
,D/UEI.SmartControl( 6973): QS Service init finished
D/UEI.SmartControl( 6973): QS Service version name: 0.1.73
D/UEI.SmartControl( 6973): QS Service version code: 1073
D/UEI.SmartControl( 6973): Config is loaded...
D/UEI.SmartControl( 6973): Service requested: Control
D/UEI.SmartControl( 6973): Service.onUnbind: IControl
D/UEI.SmartControl( 6973): Service.onDestroy
D/UEI.SmartControl( 6973): Shutdown IRRCPlayer... 
W/irrc_jni( 6973): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6973): ~IrrcClient ++ 
D/irrcClient( 6973): ~IrrcClient -- 
W/irrc_jni( 6973): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6973): Blaster closed
D/UEI.SmartControl( 6973): Blaster closed
D/UEI.SmartControl( 6973): Shut down QS...
D/UEI.SmartControl( 6973): Stopped file observer...
I/UEI.SmartControl( 6973): QS lib stop result = true
D/UEI.SmartControl( 6973): QS shutdown complete
D/UEI.SmartControl( 6973): QS Service created
E/UEI.SmartControl( 6973): QS start get config
,D/UEI.SmartControl( 6973):  configuring local db...
,I/UEI.SmartControl( 6973): Notify AllClients services are ready: 11
D/UEI.SmartControl( 6973):  ---- Has DB8: true
,D/UEI.SmartControl( 6973): QS start statue = true Error code = 0
D/UEI.SmartControl( 6973): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6973): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6973): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6973): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6973): IrrcClient ++ 
D/irrcClient( 6973): getIrrcService ++ 
D/irrcClient( 6973): getIrrcService -- 
D/irrcClient( 6973): IrrcClient -- 
W/irrc_jni( 6973): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6973): Services init done
D/UEI.SmartControl( 6973): QS Service init finished
D/UEI.SmartControl( 6973): QS Service version name: 0.1.73
D/UEI.SmartControl( 6973): QS Service version code: 1073
D/UEI.SmartControl( 6973): Service requested: Control
I/ActivityManager(  946): Killing 2686:com.lge.music/u0a28 (adj 15): empty #11
,I/UEI.SmartControl( 6973): Device manager: loading config....
D/UEI.SmartControl( 6973): Config is loaded...
V/AudioFlinger(  274): 2686 died, releasing its sessions
,V/AudioFlinger(  274):  pid 1751 @ 0
V/AudioFlinger(  274):  pid 3150 @ 1
V/AudioFlinger(  274):  pid 3150 @ 2
,W/libprocessgroup(  946): failed to open /acct/uid_10028/pid_2686/cgroup.procs: No such file or directory
,E/ActivityThread( 6973): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@1ea93ab1 that was originally bound here
E/ActivityThread( 6973): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@1ea93ab1 that was originally bound here
E/ActivityThread( 6973): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6973): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6973): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6973): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6973): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6973): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 6973): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 6973): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 6973): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6973): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6973): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6973): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6973): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6973): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6973): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6973): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6973): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6973): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,D/UEI.SmartControl( 6973): Internal service binding...
D/UEI.SmartControl( 6973):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6973): Notify AllClients services are ready: 0
,I/Icing   ( 4331): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4331): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  946): Killing 6821:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,D/UEI.SmartControl( 6973): Internal timer expired: 2
W/System.err( 6973): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@1ea93ab1
,W/libprocessgroup(  946): failed to open /acct/uid_10038/pid_6821/cgroup.procs: No such file or directory
W/System.err( 6973): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 6973): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 6973): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 6973): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 6973): 	at com.uei.control.Service.a(Unknown Source)
W/System.err( 6973): 	at com.uei.control.l.run(Unknown Source)
W/System.err( 6973): 	at java.util.Timer$TimerImpl.run(Timer.java:284)
E/UEI.SmartControl( 6973): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@1ea93ab1
I/ThermalEngine(  288): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ActivityManager(  946): Killing 6735:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  946): failed to open /acct/uid_10006/pid_6735/cgroup.procs: No such file or directory
,E/UEI.SmartControl( 6973): file observer is disposed!
,D/UEI.SmartControl( 6973): Internal timer expired: 3
,D/UEI.SmartControl( 6973): Service.onUnbind: IControl
D/UEI.SmartControl( 6973): Service.onDestroy
D/UEI.SmartControl( 6973): Shutdown IRRCPlayer... 
W/irrc_jni( 6973): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6973): ~IrrcClient ++ 
D/irrcClient( 6973): ~IrrcClient -- 
W/irrc_jni( 6973): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6973): Blaster closed
D/UEI.SmartControl( 6973): Blaster closed
D/UEI.SmartControl( 6973): Shut down QS...
I/UEI.SmartControl( 6973): QS lib stop result = true
D/UEI.SmartControl( 6973): QS shutdown complete
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1379): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1379): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1379): On Skip Timer : true
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 288, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2021): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
I/[SystemUI]LGPowerUI( 1379): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1379): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
W/Settings(  946): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  946): battery changed pluggedType: 2
W/Settings(  946): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]BatterySaverHandler( 1379): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  288): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 132292492296; DSPS: 4433736; Offset : -3021167754
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  288): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/PowerManagerServiceEx(  946): acquireWakeLockInternal: lock=839345930, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=946
,D/WeatherService( 2661): 2 : TimeTick Intent has been received, Time(hour:min:sec) 18:38:0
D/WeatherService( 2661): 2 : TimeTick Intent And Screen On
D/WeatherService( 2661): 2 : SDK version : 21
W/ActivityManager(  946): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2661): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2661): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2661): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2661): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2661): 2 : This is isUpdating : false
D/WeatherService( 2661): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2661): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2661): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2661): 2 : Fixed theme : optimus
D/WeatherReflect( 2661): 2 : Map key string is -2
,D/lim     ( 2661): 2 : time = 18:38
I/WeatherReflect( 2661): Model Name : LG-D722
D/WeatherTheme( 2661): 2 : Different view - status_min_formatted : 37 != 38
D/WeatherTheme( 2661): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2661): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
I/[SystemUI]TimeTickManager( 1379): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1379): called onTimeUpdated()
D/Theme   ( 2661): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2661): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2661): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2661): currentPackage=com.lge.sizechangable.weather.theme.optimus
,I/[SystemUI]Clock( 1379): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1379): handleTimeUpdate
,D/Weather4x2_optimus( 2661): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2661): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2661): forecast size is 0
D/Theme   ( 2661): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2661): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2661): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2661): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2661): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2661): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2661): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2661): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2661): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2661): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2661): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2661): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2661): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2661): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2661): setTouchIntent, appWidgetId: 2
,D/Theme_WeatherAncestor_optimus( 2661): url is : null
D/Theme   ( 2661): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2661): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2661): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2661): 2 : update view, appWidgetId: 2
D/WeatherService( 2661): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 18:38:0
,D/PowerManagerServiceEx(  946): releaseWakeLockInternal: lock=839345930 [*alarm*], flags=0x0
I/ThermalEngine(  288): Sensor:pa_therm0:31000 mC
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/AlarmManager(  946): ELAPSED_WAKEUP set : Alarm{a481b7b type 2 when 139346 com.google.android.gms} when 139346
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1733): Vacuum at: now=1456940281563 tag=VacuumService
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  288): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PowerManagerService(  946): ALS enabled for SRE
D/PowerManagerServiceEx(  946): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (27859 ms ago)
,D/qdlights(  946): set_light_backlight: 254
,D/qdlights(  946): set_light_backlight: 251
,D/qdlights(  946): set_light_backlight: 248
,D/qdlights(  946): set_light_backlight: 244
,D/qdlights(  946): set_light_backlight: 241
,D/qdlights(  946): set_light_backlight: 238
,D/qdlights(  946): set_light_backlight: 234
,D/qdlights(  946): set_light_backlight: 231
,D/qdlights(  946): set_light_backlight: 228
,D/qdlights(  946): set_light_backlight: 224
,D/qdlights(  946): set_light_backlight: 221
,D/qdlights(  946): set_light_backlight: 218
,D/qdlights(  946): set_light_backlight: 214
,D/qdlights(  946): set_light_backlight: 211
,D/qdlights(  946): set_light_backlight: 208
,D/qdlights(  946): set_light_backlight: 204
,D/qdlights(  946): set_light_backlight: 201
,D/qdlights(  946): set_light_backlight: 198
,D/qdlights(  946): set_light_backlight: 194
,D/qdlights(  946): set_light_backlight: 191
,D/qdlights(  946): set_light_backlight: 188
,D/qdlights(  946): set_light_backlight: 184
,D/qdlights(  946): set_light_backlight: 181
,I/ThermalEngine(  288): Sensor:pa_therm0:31000 mC
,D/qdlights(  946): set_light_backlight: 178
D/qdlights(  946): set_light_backlight: 174
,D/qdlights(  946): set_light_backlight: 171
,D/qdlights(  946): set_light_backlight: 168
,D/qdlights(  946): set_light_backlight: 164
,D/qdlights(  946): set_light_backlight: 161
,D/qdlights(  946): set_light_backlight: 158
,D/qdlights(  946): set_light_backlight: 154
,D/qdlights(  946): set_light_backlight: 151
,D/qdlights(  946): set_light_backlight: 148
,D/qdlights(  946): set_light_backlight: 144
,D/qdlights(  946): set_light_backlight: 141
,D/qdlights(  946): set_light_backlight: 138
,D/qdlights(  946): set_light_backlight: 134
,D/qdlights(  946): set_light_backlight: 131
,D/qdlights(  946): set_light_backlight: 128
,D/qdlights(  946): set_light_backlight: 124
,D/qdlights(  946): set_light_backlight: 121
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
D/qdlights(  946): set_light_backlight: 118
,D/qdlights(  946): set_light_backlight: 114
,D/qdlights(  946): set_light_backlight: 111
,D/qdlights(  946): set_light_backlight: 108
,D/qdlights(  946): set_light_backlight: 104
,D/qdlights(  946): set_light_backlight: 101
,D/qdlights(  946): set_light_backlight: 98
,D/qdlights(  946): set_light_backlight: 94
,D/qdlights(  946): set_light_backlight: 91
,D/qdlights(  946): set_light_backlight: 88
,D/qdlights(  946): set_light_backlight: 84
,D/qdlights(  946): set_light_backlight: 81
,D/qdlights(  946): set_light_backlight: 78
,D/qdlights(  946): set_light_backlight: 74
,D/qdlights(  946): set_light_backlight: 71
,D/qdlights(  946): set_light_backlight: 68
,D/qdlights(  946): set_light_backlight: 64
,D/qdlights(  946): set_light_backlight: 61
,D/qdlights(  946): set_light_backlight: 58
,D/qdlights(  946): set_light_backlight: 54
,D/qdlights(  946): set_light_backlight: 51
,D/qdlights(  946): set_light_backlight: 48
,D/qdlights(  946): set_light_backlight: 44
,D/qdlights(  946): set_light_backlight: 41
,D/qdlights(  946): set_light_backlight: 38
,D/qdlights(  946): set_light_backlight: 34
,D/qdlights(  946): set_light_backlight: 31
,D/qdlights(  946): set_light_backlight: 28
,D/qdlights(  946): set_light_backlight: 24
,D/qdlights(  946): set_light_backlight: 21
,D/qdlights(  946): set_light_backlight: 18
,D/qdlights(  946): set_light_backlight: 14
,D/qdlights(  946): set_light_backlight: 11
,D/qdlights(  946): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 152293619784; DSPS: 5089134; Offset : -3021199674
,I/ThermalEngine(  288): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  946): ALS enabled for SRE
D/PowerManagerServiceEx(  946): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (34855 ms ago)
,I/PowerManagerService(  946): Going to sleep due to screen timeout (uid 1000)...
I/PowerManagerService(  946): ALS enabled for SRE
D/PowerManagerServiceEx(  946): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (34869 ms ago)
,W/ContextImpl(  946): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  946): Sleeping (uid 1000)...
D/LPWGController(  946): [updateScreenState] screen on = false
D/LPWGController(  946): disable proximity sensor
,D/LPWGController(  946): enable proximity sensor
I/SensorManager(  946): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@39be47b0] by com.android.server.power.ProximitySensorListener.enable():120
I/sensors_hal_Ctx(  946): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  946): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
,D/sensors_hal_SAM(  946): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  946): activate: handle is 48, enable
V/sensors_hal_Ctx(  946): activate sensors is 1400000000000
D/sensors_hal_Thresh(  946): enable: handle=48
I/sensors_hal_SAM(  946): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  946): waitForResponse: timeout=1000
V/sensors_hal_SAM(  946): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  946): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  946): enable: Received response: 0
D/PowerManagerServiceEx(  946): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (34905 ms ago)
I/Adreno-EGL(  946): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  946): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  946): Build Date: 03/02/15 Mon
I/Adreno-EGL(  946): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  946): Remote Branch: 
I/Adreno-EGL(  946): Local Patches: 
I/Adreno-EGL(  946): Reconstruct Branch: 
,D/PermissionCache(  245): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (967 us)
,I/Sensors (  414): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  946): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  946): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  946): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
,D/sensors_hal_Thresh(  946): processInd: handle 48, count=1
V/sensors_hal_Thresh(  946): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  946): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  946): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  946): poll: count: 256
I/sensors_hal_Ctx(  946): poll: released wakelock sensor_ind
D/sensors_hal_Util(  946): waitForResponse: timeout=0
D/LPWGController(  946): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  946): current mode = 1  value = 1 1
I/LPWGController(  946): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  946): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  946): set_light_backlight: 0
,I/SensorManager(  946): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  946): activate: handle is 46, disable
V/sensors_hal_Ctx(  946): activate sensors is 1000000000000
D/sensors_hal_LP2(  946): enable: handle=46
D/sensors_hal_LP2(  946): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  946): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  245): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  245): hwc_blank: Blanking display: 0
I/DisplayManagerService(  946): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  946): Display changed displayId=0
,V/sensors_hal_SAM(  946): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  946): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1751): Display #0 changed.
,D/qdhwcomposer(  245): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  946): Excessive delay in setPowerMode(): 225ms
I/qdhwcomposer(  245): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  946): Got set_interactive hint
D/KeyguardViewMediator( 1379): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1331): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1331): notifyScreenOffLocked
D/SmartCoverViewMediator( 1331): handleNotifyScreenOFF
D/KeyguardViewMediator( 1379): notifyScreenOffLocked
D/JX-Cordova( 5390): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5390): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5390): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c4de1d0 added. We now have 3 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5390): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5390): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed6b5c9 added. We now have 3 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5390): addListener: New listener added - the number of listeners is now 1
,D/BluetoothAdapterService(514407089)( 2021): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1753de0f
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5390): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 5390): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
D/KeyguardViewMediator( 1379): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1379): handleNotifyScreenOff
W/System.err( 5390): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
W/System.err( 5390): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
,W/System.err( 5390): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 5390): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 5390): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 5390): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 5390): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 5390): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 5390): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 5390): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 5390): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5390): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5390): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ScreenTurnOffBySensor( 1379): unregisterProximitySensor
,D/StatusBarWindowView( 1379): onScreenTurnedOff why = 3
D/WifiServerServiceExt(  946): sendKtScanInterval  mRtspPlay : false
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
V/AudioFlinger(  274): setParameters(): io 0, keyvalue screen_state=on, calling pid 946
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/audio_hw_primary(  274): adev_set_parameters: enter: screen_state=on
V/voice   (  274): voice_set_parameters: enter: screen_state=on
,V/compress_voip(  274): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  274): voice_extn_compress_voip_set_parameters: exit
V/voice   (  274): voice_set_parameters: exit with code(0)
,V/msm8974_platform_lge(  274): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  274): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  274): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  274): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  274): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  274): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  274): adev_set_parameters: exit with code(0)
I/WifiServerServiceExt(  946): set CMD_KT_SCAN_INTERVAL
,D/KeyguardUpdateMonitor( 1379): handleTimeUpdate
I/Sensors (  414): sns_pwr.c(301):releasing wakelock
,D/GpsLocationProvider(  946): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1379): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1839): |CORE| sendScreenState: state:true
,I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1379): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/LEDService( 1803): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1803): stopPatternFlashing()
,D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
I/LEDService( 1803): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
I/LEDService( 1803): updateLightsLocked : turn off led
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1803): RESTART MSG
D/SplitWindow(  946): check instance of lgWin Window{3822174f u0 SearchPanel}
,I/Cliptray Service( 1803): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/Cliptray Service( 1803): lockStatus = 0
D/InputDispatcher(  946): Window went away: Window{3336ba6c u0 SearchPanel}
,I/[SystemUI]Clock( 1379): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1379): time changed, timezoneChanged : false
,D/LNfcService( 1786): action : android.intent.action.SCREEN_ON
D/NfcServiceNXP( 1786): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1786): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1786): isRequireNfcCRouting() return true
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
,D/Ulp_jni (  946): JNI:system_update. Event-0
,V/PhoneApp( 1751): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2661): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 18:38:18
,D/WeatherService( 2661): 2 : ACTION screen on
D/WeatherService( 2661): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2661): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2661): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 18:38:19
W/Settings(  946): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  946): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  946): ACTION_SCREEN_ON
D/AppCleanupService( 4097): android.intent.action.SCREEN_ON
,V/AudioFlinger(  274): setParameters(): io 0, keyvalue screen_state=off, calling pid 946
D/audio_hw_primary(  274): adev_set_parameters: enter: screen_state=off
V/voice   (  274): voice_set_parameters: enter: screen_state=off
V/compress_voip(  274): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  274): voice_extn_compress_voip_set_parameters: exit
V/voice   (  274): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  274): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  274): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  274): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  274): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  274): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  274): adev_set_parameters: exit with code(0)
D/WifiController(  946): CMD_SCREEN_OFF 
D/WifiController(  946): shouldWifiStayAwake TRUE
,D/GpsLocationProvider(  946): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1379): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1839): |CORE| sendScreenState: state:false
,I/LEDService( 1803): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1803): stopPatternFlashing()
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
I/LEDService( 1803): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1803): clear
I/LEDService( 1803): updateLightsLocked : turn on led
E/LEDService( 1803): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1803): Can't handle this request of patternId:0
D/LEDHandler( 1803): RESTART MSG
I/Cliptray Service( 1803): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1786): action : android.intent.action.SCREEN_OFF
,D/NfcServiceNXP( 1786): mScreenState : 1, mInProvisionMode : false
I/[LGHome]EVENT( 1877): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1751): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2661): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 18:38:19
D/WeatherService( 2661): 2 : ACTION screen off
D/WeatherService( 2661): 2 : TimeTick Receiver Unregister
D/WeatherService( 2661): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 18:38:19
W/Settings(  946): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  946): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  946): ACTION_SCREEN_OFF
D/AppCleanupService( 4097): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 4097): AppUsageStatsSaveTask
E/NxpNfcJni( 1786): getReconnectState = 0x0
,D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
D/LNfcService( 1786): isRequireNfcCRouting() return true
D/LNfcService( 1786): isHCERoutingtoHost() return : true
D/NfcService( 1786): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1786): mEnableLPD: true
D/NfcService( 1786): mEnableReader: false
D/NfcService( 1786): mEnableHostRouting: true
,D/NfcService( 1786): newParams.techmask= mTechMask: 0
D/NfcService( 1786): mEnableLPD: true
D/NfcService( 1786): mEnableReader: false
D/NfcService( 1786): mEnableHostRouting: true
D/NfcService( 1786): screenState= 1
E/NxpNfcJni( 1786): getReconnectState = 0x0
,I/ThermalEngine(  288): Sensor:pa_therm0:31000 mC
,D/KeyguardViewMediator( 1379): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  946): ELAPSED_WAKEUP set : Alarm{1fb82edc type 2 when 160744 com.android.systemui} when 160744
,D/PhoneUtils( 1751): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1751): getCallState : 0
,D/PhoneUtils( 1751): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1379): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1379): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  288): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 172295136183; DSPS: 5744543; Offset : -3021178897
,I/ThermalEngine(  288): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  946): ELAPSED_WAKEUP set : Alarm{39db2be5 type 2 when 187143 com.google.android.gms} when 187143
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1379): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1379): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1379): On Skip Timer : true
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1379): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1379): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
,W/Settings(  946): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  946): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  946): battery changed pluggedType: 2
D/HeadsetStateMachine( 2021): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1379): onReceive = android.intent.action.BATTERY_CHANGED
I/PhenotypeConfigurator( 1733): Scheduling Phenotype for one-off execution 12438 seconds from now (1456940329505)
,I/PhenotypeFlagCommitter( 1733): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1733): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  946): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  270): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  270): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  270): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  270): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  270): res_queryN name = xxxxx succeed
I/System.out( 1733): propertyValue:false
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ThermalEngine(  288): Sensor:pa_therm0:30000 mC
,D/LocationManagerService(  946): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  946): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  270): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  270): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  270): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  270): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  270): res_queryN name = xxxxx succeed
,I/System.out( 1733): propertyValue:false
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager(  946): android: cancelAsUser(2) by android
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
,D/LocationManagerService(  946): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  946): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 192297436696; DSPS: 6399978; Offset : -3021167281
,I/ThermalEngine(  288): Sensor:pa_therm0:30000 mC
,I/ClearcutLoggerApiImpl( 1733): disconnect managed GoogleApiClient
,V/AlarmManager(  946): ELAPSED_WAKEUP set : Alarm{1fbf326a type 2 when 197675 android} when 197675
,I/[SystemUI]TimeTickManager( 1379): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1379): called onTimeUpdated()
I/[SystemUI]Clock( 1379): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1379): handleTimeUpdate
I/ThermalEngine(  288): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1379): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1379): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1379): On Skip Timer : true
D/HeadsetStateMachine( 2021): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
W/Settings(  946): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  946): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  946): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1379): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1379): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1379): onReceive = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 2021): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1379): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1379): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1379): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  946): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  946): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  946): battery changed pluggedType: 2
I/ThermalEngine(  288): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 212303995640; DSPS: 7055555; Offset : -3021232603
,I/ThermalEngine(  288): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 232306296246; DSPS: 7710989; Offset : -3021188294
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1379): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1379): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1379): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1379): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1379): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2021): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1379): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  946): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  946): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  946): battery changed pluggedType: 2
I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 252308527340; DSPS: 8366422; Offset : -3021185008
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1379): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1379): called onTimeUpdated()
I/[SystemUI]Clock( 1379): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1379): handleTimeUpdate
I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 272310873603; DSPS: 9021858; Offset : -3021157977
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 292313182521; DSPS: 9677295; Offset : -3021201049
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1379): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1379): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1379): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2021): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1379): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1379): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/[SystemUI]BatterySaverHandler( 1379): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  946): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  946): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  946): battery changed pluggedType: 2
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 312315447411; DSPS: 10332729; Offset : -3021194485
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1379): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1379): called onTimeUpdated()
I/[SystemUI]Clock( 1379): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1379): handleTimeUpdate
I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1379): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1379): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1379): On Skip Timer : true
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1379): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1379): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1379): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1379): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1379): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1379): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2021): Disconnected process message: 10, size: 0
W/Settings(  946): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  946): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  946): battery changed pluggedType: 2
I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1379): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1379): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1379): On Skip Timer : true
I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 332317944366; DSPS: 10988171; Offset : -3021197914
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,I/LocationManagerService(  946): remove 1102bc50
D/LocationManagerService(  946): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  946): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  946): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  946): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  946): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 352320678406; DSPS: 11643619; Offset : -3021149005
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1379): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1379): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1379): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2021): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1379): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1379): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
I/[SystemUI]BatterySaverHandler( 1379): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  946): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  946): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  946): battery changed pluggedType: 2
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 372322870786; DSPS: 12299053; Offset : -3021215342
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  946): acquireWakeLockInternal: lock=839345930, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=946
,D/PowerManagerServiceEx(  946): releaseWakeLockInternal: lock=839345930 [*alarm*], flags=0x0
,I/[SystemUI]TimeTickManager( 1379): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1379): called onTimeUpdated()
I/[SystemUI]Clock( 1379): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1379): handleTimeUpdate
I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 392325113093; DSPS: 12954486; Offset : -3021202850
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,V/AlarmManager(  946): RTC_WAKEUP set : Alarm{2dc0f35b type 0 when 1456940540054 com.google.android.gms} when 1456940540054
,I/EventLogService( 4331): Aggregate from 1456940250119 (log), 1456938739997 (data)
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/art     (  946): Explicit concurrent mark sweep GC freed 55799(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 23MB/34MB, paused 3.006ms total 232.232ms
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 412327315857; DSPS: 13609917; Offset : -3021164802
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1379): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1379): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1379): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2021): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1379): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1379): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
I/[SystemUI]BatterySaverHandler( 1379): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  946): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  946): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  946): battery changed pluggedType: 2
I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 432329610005; DSPS: 14265353; Offset : -3021192021
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1379): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1379): called onTimeUpdated()
,I/[SystemUI]Clock( 1379): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1379): handleTimeUpdate
I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 452331837304; DSPS: 14920787; Offset : -3021220913
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 472334112897; DSPS: 15576220; Offset : -3021173079
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1379): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1379): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1379): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2021): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1379): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1379): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/[SystemUI]BatterySaverHandler( 1379): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  946): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  946): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  946): battery changed pluggedType: 2
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 492336381197; DSPS: 16231655; Offset : -3021193595
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1379): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1379): called onTimeUpdated()
,I/[SystemUI]Clock( 1379): called onTimeUpdated()
I/LgeClockWidgetControlView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1379): handleTimeUpdate
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 512338574513; DSPS: 16887086; Offset : -3021167080
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 532340734145; DSPS: 17542517; Offset : -3021174223
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  946): acquireWakeLockInternal: lock=839345930, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=946
,V/AlarmManager(  946): ELAPSED_WAKEUP set : Alarm{e512ba4 type 2 when 545007 android} when 545007
D/PowerManagerServiceEx(  946): releaseWakeLockInternal: lock=839345930 [*alarm*], flags=0x0
,I/NotificationManager(  946): android: cancelAsUser(-1548111331) by android
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/art     ( 6993): Attempt to remove local handle scope entry from IRT, ignoring
,D/libc-netbsd( 6993): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6993): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
E/BandwidthController(  270): [LG DATA] No such appUid: 10086
D/DnsProxyListener(  270): App 10086 tries DNS query. Accept family:2 protocol:0
D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
D/libc-netbsd(  270): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  270): res_queryN name = xxxxx succeed
,I/NotificationManager( 6993): com.google.android.apps.plus: cancel(10436) by com.google.android.apps.plus
,I/NotificationManager(  946): android: cancelAsUser(2145784878) by android
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1379): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1379): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1379): On Skip Timer : true
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 2021): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/[SystemUI]LGPowerUI( 1379): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1379): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
I/[SystemUI]BatterySaverHandler( 1379): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  946): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  946): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  946): battery changed pluggedType: 2
I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 552342923285; DSPS: 18197948; Offset : -3021152169
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1379): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1379): called onTimeUpdated()
I/[SystemUI]Clock( 1379): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1379): handleTimeUpdate
I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1379): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1379): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1379): On Skip Timer : true
D/HeadsetStateMachine( 2021): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1379): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1379): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
I/[SystemUI]BatterySaverHandler( 1379): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  946): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  946): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  946): battery changed pluggedType: 2
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 572345264354; DSPS: 18853394; Offset : -3021435272
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  946): acquireWakeLockInternal: lock=839345930, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=946
,V/AlarmManager(  946): ELAPSED_WAKEUP set : Alarm{45b5c96 type 2 when 575326 android} when 575326
I/ActivityManager(  946): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7272 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/DigitalAppWidgetProvider( 7272): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7272): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@70aef1f
,D/PowerManagerServiceEx(  946): releaseWakeLockInternal: lock=839345930 [*alarm*], flags=0x0
I/ActivityManager(  946): Killing 6890:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  946): failed to open /acct/uid_10011/pid_6890/cgroup.procs: No such file or directory
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 588601014350; DSPS: 19386055; Offset : -3021208959
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1379): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1379): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1379): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2021): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1379): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1379): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
I/[SystemUI]BatterySaverHandler( 1379): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  946): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  946): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  946): battery changed pluggedType: 2
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 608603323440; DSPS: 20041491; Offset : -3021219360
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1379): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1379): called onTimeUpdated()
I/[SystemUI]Clock( 1379): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1379): handleTimeUpdate
I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 628605580717; DSPS: 20696924; Offset : -3021189686
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 643607689997; DSPS: 21188518; Offset : -3021340737
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 657679710039; DSPS: 21649624; Offset : -3021156783
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1379): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1379): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1379): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2021): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 271, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1379): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1379): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 271
I/[SystemUI]BatterySaverHandler( 1379): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  946): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  946): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  946): battery changed pluggedType: 2
I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 675183167272; DSPS: 22223189; Offset : -3021514584
,I/[SystemUI]TimeTickManager( 1379): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1379): called onTimeUpdated()
I/[SystemUI]Clock( 1379): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1379): handleTimeUpdate
I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 689254727600; DSPS: 22684275; Offset : -3021184264
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 704256930208; DSPS: 23175866; Offset : -3021146451
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 719259248304; DSPS: 23667462; Offset : -3021149695
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1379): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1379): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1379): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2021): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1379): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1379): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
I/[SystemUI]BatterySaverHandler( 1379): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  946): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  946): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  946): battery changed pluggedType: 2
I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 733014995919; DSPS: 24118212; Offset : -3021198649
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1379): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1379): called onTimeUpdated()
I/[SystemUI]Clock( 1379): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1379): handleTimeUpdate
I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 748017262652; DSPS: 24609809; Offset : -3021283670
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 764272645807; DSPS: 25142445; Offset : -3020659073
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 778038317667; DSPS: 25593536; Offset : -3021194076
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1379): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1379): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1379): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2021): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 269, mChargingStatus=5, mChargingStop=false
D/WifiController(  946): battery changed pluggedType: 2
,W/Settings(  946): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  946): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 269
I/[SystemUI]LGPowerUI( 1379): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1379): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 269
I/[SystemUI]BatterySaverHandler( 1379): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 794293060875; DSPS: 26126167; Offset : -3021056888
,I/[SystemUI]TimeTickManager( 1379): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1379): called onTimeUpdated()
I/[SystemUI]Clock( 1379): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1379): handleTimeUpdate
I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 807426103201; DSPS: 26556518; Offset : -3021286959
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 822428406591; DSPS: 27048110; Offset : -3021178831
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 842430590359; DSPS: 27703544; Offset : -3021255394
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1379): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1379): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1379): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2021): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 268, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 268
I/[SystemUI]LGPowerUI( 1379): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1379): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 268
I/[SystemUI]BatterySaverHandler( 1379): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  946): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  946): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  946): battery changed pluggedType: 2
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 857432383700; DSPS: 28195146; Offset : -3021962306
,I/[SystemUI]TimeTickManager( 1379): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1379): called onTimeUpdated()
I/[SystemUI]Clock( 1379): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1379): handleTimeUpdate
I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 871042182004; DSPS: 28641087; Offset : -3021203492
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 885114275743; DSPS: 29102199; Offset : -3021131237
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 905116744692; DSPS: 29757638; Offset : -3021073047
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1379): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1379): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1379): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/HeadsetStateMachine( 2021): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 267
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 267, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1379): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1379): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 267
I/[SystemUI]BatterySaverHandler( 1379): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  946): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  946): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  946): battery changed pluggedType: 2
I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1379): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1379): called onTimeUpdated()
I/[SystemUI]Clock( 1379): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1379): handleTimeUpdate
I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 925119112203; DSPS: 30413078; Offset : -3021149025
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 940121704598; DSPS: 30904684; Offset : -3021179007
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/PowerManagerServiceEx(  946): acquireWakeLockInternal: lock=839345930, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=946
,V/AlarmManager(  946): ELAPSED_WAKEUP set : Alarm{23205017 type 2 when 947408 com.android.bluetooth} when 947408
D/PowerManagerServiceEx(  946): releaseWakeLockInternal: lock=839345930 [*alarm*], flags=0x0
,W/bt-smp  ( 2021): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 2021): Plain text(LSB ~ MSB) = 60 eb 53 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2021): Encrypted text(LSB ~ MSB) = a2 bf 0e b3 8d 46 cf c1 eb 3c 5a 68 7b cd 18 ab 
W/bt-btm  ( 2021): Stopping oneshot timer
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 955123163585; DSPS: 31396251; Offset : -3021156455
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,I/[SystemUI]LGPowerUI( 1379): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1379): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1379): On Skip Timer : true
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2021): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 266
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 266, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1379): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1379): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 266
I/[SystemUI]BatterySaverHandler( 1379): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  946): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  946): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  946): battery changed pluggedType: 2
I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 975125792800; DSPS: 32051696; Offset : -3021121286
,I/[SystemUI]TimeTickManager( 1379): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1379): called onTimeUpdated()
I/[SystemUI]Clock( 1379): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1379): handleTimeUpdate
I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 995128377835; DSPS: 32707134; Offset : -3020914513
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 1008259605595; DSPS: 33137427; Offset : -3021187127
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 1027954001199; DSPS: 33782775; Offset : -3021249453
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1379): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1379): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1379): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2021): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 265
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 265, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1379): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1379): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 265
I/[SystemUI]BatterySaverHandler( 1379): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  946): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  946): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  946): battery changed pluggedType: 2
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1379): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1379): called onTimeUpdated()
I/[SystemUI]Clock( 1379): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1379): handleTimeUpdate
I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 1047956270560; DSPS: 34438205; Offset : -3021118354
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 1067958564875; DSPS: 35093644; Offset : -3021232948
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 1082960800617; DSPS: 35585236; Offset : -3021194368
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1379): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1379): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1379): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2021): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 265
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 265, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1379): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1379): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 265
I/[SystemUI]BatterySaverHandler( 1379): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  946): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  946): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  946): battery changed pluggedType: 2
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 1097963063251; DSPS: 36076836; Offset : -3021373139
,I/[SystemUI]TimeTickManager( 1379): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1379): called onTimeUpdated()
I/[SystemUI]Clock( 1379): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1379): handleTimeUpdate
I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 1119218340304; DSPS: 36773324; Offset : -3021225149
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 1134222331829; DSPS: 37264984; Offset : -3021506086
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1379): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1379): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1379): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 1155796108080; DSPS: 37971902; Offset : -3021153045
,I/[SystemUI]TimeTickManager( 1379): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1379): called onTimeUpdated()
I/[SystemUI]Clock( 1379): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1379): handleTimeUpdate
I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 1175798407937; DSPS: 38627339; Offset : -3021203067
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 1190800629239; DSPS: 39118931; Offset : -3021179290
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 1208304238075; DSPS: 39692489; Offset : -3021171270
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1379): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1379): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1379): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2021): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 264
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 264, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1379): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1379): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 264
I/[SystemUI]BatterySaverHandler( 1379): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  946): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  946): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  946): battery changed pluggedType: 2
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1379): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1379): called onTimeUpdated()
I/[SystemUI]Clock( 1379): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1379): handleTimeUpdate
I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/UsageStatsService(  946): User[0] Flushing usage stats to disk
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 1228306702888; DSPS: 40347931; Offset : -3021210928
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 1248309019068; DSPS: 41003374; Offset : -3021425727
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 1263313729477; DSPS: 41495043; Offset : -3021262386
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1379): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1379): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1379): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2021): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 264, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1379): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 264
I/[SystemUI]LGPowerUI( 1379): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1379): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 264
I/[SystemUI]BatterySaverHandler( 1379): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  946): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  946): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  946): battery changed pluggedType: 2
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1379): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1379): called onTimeUpdated()
I/[SystemUI]Clock( 1379): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
I/[SystemUI]DateView( 1379): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1379): handleTimeUpdate
D/sensors_hal_Time(  946): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  946): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  946): tsOffsetIs: Apps: 1278316038014; DSPS: 41986636; Offset : -3021183715
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,TIME-OUT KILL (timeout was 1200000ms),I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
D/AndroidRuntime( 7475): 
D/AndroidRuntime( 7475): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7475): CheckJNI is OFF
D/AndroidRuntime( 7475): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  946): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  946): Killing 5390:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  946): WIN DEATH: Window{44f7203 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  946): Focus left window: Window{44f7203 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  946): Window went away: Window{44f7203 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  946): Skipping PackageSetting{c5f2f7f com.example.hello/10317} due to missing metadata
I/ActivityManager(  946):   Force finishing activity ActivityRecord{27530b9a u0 com.test.thalitest/.MainActivity t222}
V/ActivityManager(  946): Display changed displayId=0
D/DSDPConnection( 1751): Display #0 changed.
W/ActivityManager(  946): Spurious death for ProcessRecord{15f34c04 5390:com.test.thalitest/u0a316}, curProc for 5390: null
I/ActivityManager(  946): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  946):   Force finishing activity ActivityRecord{27530b9a u0 com.test.thalitest/.MainActivity t222 f}
W/ActivityManager(  946): Duplicate finish request for ActivityRecord{27530b9a u0 com.test.thalitest/.MainActivity t222 f}
D/KeyguardModel( 1379): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 1877): [Launcher.java:5203:onStart()]onStart
I/InputReader(  946): Reconfiguring input devices.  changes=0x00000010
I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/GeofencerStateMachine( 1733): Ignoring removeGeofence because network location is disabled.
I/[LGHome]EVENT( 1877): [Launcher.java:776:onResume()]onResume
I/art     ( 1941): Explicit concurrent mark sweep GC freed 24018(1547KB) AllocSpace objects, 3(71KB) LOS objects, 40% free, 12MB/21MB, paused 1.902ms total 105.190ms
W/System.err( 3617): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3617): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3617): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3617): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3617): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3617): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3617): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3617): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3617): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3617): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3617): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3617): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/ActivityManager(  946): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7506 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/art     ( 4331): Explicit concurrent mark sweep GC freed 20532(1221KB) AllocSpace objects, 6(96KB) LOS objects, 25% free, 14MB/19MB, paused 886us total 136.791ms
I/[LGHome]EVENT( 1877): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
I/[SystemUI]QSlideListController( 1379): onReceive = android.intent.action.PACKAGE_REMOVED
D/KeyguardModel( 1379): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1379): createShortcutInfo...
D/KeyguardModel( 1379): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1379): createShortcutInfo...
I/[LGHome]LGActivityUtil( 1877): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1877): [Launcher.java:929:onResume()]onResume end
I/Activity( 1877): Activity.onPostResume() called 
I/[LGHome]EVENT( 1877): [Launcher.java:986:onPause()]onPause
W/ResourcesManager( 1379): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1379): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourceType( 1379): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1379): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1379): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1379): createShortcutInfo...
W/[LGHome]LGWallpaperInfo( 1877): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1877): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
W/ResourcesManager( 1379): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/art     (  946): Explicit concurrent mark sweep GC freed 32088(2028KB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/34MB, paused 2.722ms total 226.788ms
W/ResourceType( 1379): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1379): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/art     (  946): WaitForGcToComplete blocked for 26.089ms for cause Explicit
D/KeyguardModel( 1379): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1379): createShortcutInfo...
W/ResourcesManager( 1379): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1379): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1379): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourceType( 1379): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1379): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1379): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1379): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1379): createShortcutInfo...
D/KeyguardModel( 1379): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/WindowManager(  946): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
D/InputDispatcher(  946): Focus entered window: Window{28f24916 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/[SystemUI]NavigationThemeResource( 1379): notify navigation bar color(0x0)
I/[SystemUI]NavigationThemeResource( 1379): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1379):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1379): , Keyguard show=false, IME shown=false, Panel expanded=false
I/SystemUI[Framework](  946): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  946): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  946): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  946): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  946): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@4b0deb4,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  946): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/KeyguardModel( 1379): handleShortcutListChanged...
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
I/[LGHome]EVENT( 1877): [Launcher.java:5214:onStop()]onStop
D/KeyguardModel( 1379): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1379): createShortcutInfo...
D/administrator(  946): Handling package changes for user 0
I/[LGHome]EVENT( 1877): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
D/KeyguardModel( 1379): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1379): createShortcutInfo...
I/PhoneWindow( 1877): [setNavigationBarColor] color=0x 0
W/ResourceType( 1379): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1379): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1379): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1379): createShortcutInfo...
W/ResourceType( 1379): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1379): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1379): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1379): createShortcutInfo...
W/InputMethodManagerService(  946): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/ResourceType( 1379): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1379): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
W/ResourcesManager( 7506): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7506): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7506): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/KeyguardModel( 1379): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1379): createShortcutInfo...
W/InputMethodManagerService(  946): Got RemoteException sending setActive(false) notification to pid 5390 uid 10316
D/KeyguardModel( 1379): handleShortcutListChanged...
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/Timeline(  946): Timeline: Activity_windows_visible id: ActivityRecord{193d60f2 u0 com.lge.launcher2/.Launcher t221} time:1291356
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/NotificationService(  946): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  946): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  946): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  946): removeObsoleteFile: deleting file=222_task.xml
W/IInputConnectionWrapper( 1877): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1621): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1877): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1877): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1877): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
I/LGEmail ( 7506): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
D/LGEmail ( 7506): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
I/art     (  946): Explicit concurrent mark sweep GC freed 6175(338KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.211ms total 427.305ms
D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
D/AndroidRuntime( 7475): Shutting down VM
I/PackageChangeReceiver( 7506): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
E/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  946): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7534 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  946): Killing 6844:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  946): failed to open /acct/uid_10061/pid_6844/cgroup.procs: No such file or directory
I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
I/AppUp4:AppBoxCP( 7534): onCreate
W/AppUp4:DB( 7534):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7534):  setFingerPrint start
I/AppUp4:DB( 7534):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7534):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7534):  SDK version = 0
I/AppUp4:DB( 7534):  beforefinger == newfinger no write in DB
E/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/AppUp4:AppBoxApplication( 7534): AppBoxApplication onCreate()
D/AppUp4:PreloadHelper( 7534): added Exclude : com.test.thalitest
I/Timeline( 1877): Timeline: Activity_idle id: android.os.BinderProxy@256f2d48 time:1291997
I/ActivityManager(  946): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7553 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  946): Killing 6911:com.android.gallery3d/u0a23 (adj 15): empty #11
I/art     ( 1877): Explicit concurrent mark sweep GC freed 28069(1533KB) AllocSpace objects, 21(2MB) LOS objects, 40% free, 15MB/25MB, paused 1.225ms total 53.229ms

```
