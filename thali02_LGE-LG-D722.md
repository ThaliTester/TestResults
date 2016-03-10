#### Test 6012434713fea37_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
,I/MusicStore( 4591): Database version: 120
--------- beginning of system
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4591): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4591): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4591): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 4591): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4591): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/AndroidRuntime( 4618): 
D/AndroidRuntime( 4618): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4618): CheckJNI is OFF
V/JNIHelp ( 4591): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/art     ( 4591): Suspending all threads took: 6.413ms
W/ActivityThread( 4591): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 4591): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@106e5353: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4591): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 4591): GMSCore installation verified
I/ConfigStore( 4591): Config Database version: 1
D/AndroidRuntime( 4618): Calling main entry com.android.commands.am.Am
I/ActivityManager(  865): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  865): setTaskToReturnTo : TaskRecord{7e4564d #224 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  865): setTaskToReturnTo : TaskRecord{7e4564d #224 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  865): AppWindowTokenEx init.. 
D/ContextHelper(  865): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
D/InputDispatcher(  865): Focus left window: Window{1f4ee12f u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 4618): Shutting down VM
I/PhoneWindow(  865): [generateLayout] setColorNavigationBar => color=0x ff000001
D/PhoneWindowEx(  865): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow(  865): [setNavigationBarColor2] color=0x fff5f5f5
D/SplitWindow(  865): check instance of lgWin Window{3c330205 u0 Starting com.test.thalitest}
I/[LGHome]EVENT( 1878): [Launcher.java:986:onPause()]onPause
I/ThermalEngine(  288): Sensor:pa_therm0:31000 mC
I/ActivityManager(  865): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4640 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1878): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/HotwordDetector( 1943): Closing mic
I/[LGHome]EVENT( 1878): [Launcher.java:5214:onStop()]onStop
,I/WindowStateAnimator(  865): Starting window displayed
,D/WindowManager(  865): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
I/[SystemUI]NavigationThemeResource( 1371): notify navigation bar color(0xfff5f5f5)
I/SystemUI[Framework](  865): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
I/[SystemUI]NavigationThemeResource( 1371): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1371):  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
I/[SystemUI]NavigationThemeResource( 1371): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx(  865): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  865): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  865): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  865): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@20ca6dff,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  865): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,I/MicrophoneInputStream( 1943): mic_close com.google.android.apps.gsa.speech.audio.u@16ebbe7f
V/AudioRecord( 1943): stop()
D/AudioRecord( 1943): AudioRecord->stop()
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
V/AudioFlinger(  275): processConfigEvents_l() remaining events 1
V/AudioFlinger(  275): processConfigEvents_l() DONE thread 0xb42e2000
,D/audio_hw_primary(  275): in_standby: enter: stream (0xb40365c0) usecase(7: audio-record)
I/MediaRouter( 4591): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,D/ToneMappingReceiver( 4548): Enter doAlarmRingToneUriMapping()
,V/audio_hw_primary(  275): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  275): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  275): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  275): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  275): disable_audio_route: exit
E/audio_hw_primary(  275): disable_snd_device: enter 144
D/hardware_info(  275): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  275): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  275): stop_input_stream: exit: status(0)
V/audio_hw_primary(  275): in_standby: exit:  status(0)
V/AudioFlinger(  275): RecordThread: loop stopping
V/AudioPolicyService(  275): AudioCommandThread() going to sleep
,V/AudioPolicyManager(  275): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  275): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  275): AudioCommandThread() adding update audio patch list
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
V/audio_hw_primary(  275): in_set_parameters: exit: status(0)
V/AudioFlinger(  275): processConfigEvents_l() DONE thread 0xb42e2000
V/AudioFlinger(  275): RecordThread: loop stopping
V/AudioPolicyService(  275): AudioCommandThread() going to sleep
V/AudioRecord( 1943): stop()
V/AudioRecord( 1943): stop()
V/AudioRecord( 1943): stop()
V/AudioFlinger(  275): RecordHandle::stop()
V/AudioFlinger(  275): RecordThread::stop
V/AudioPolicyManager(  275): releaseInput() 17
V/AudioPolicyManager(  275): closeInput(17)
V/AudioFlinger(  275): closeInput() 17
V/AudioSystem(  275): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  865): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1371): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1752): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  275): ThreadBase::exit
V/AudioFlinger(  275): RecordThread: loop starting
V/AudioFlinger(  275): RecordThread 0xb42e2000 exiting
V/AudioSystem( 2613): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1943): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  275): releasing 16 from 1943 for -1
V/AudioFlinger(  275):  decremented refcount to 0
V/AudioFlinger(  275): purging stale effects
V/AudioSystem( 3106): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  275): adev_close_input_stream: enter:stream_handle(0xb40365c0)
D/audio_hw_primary(  275): in_standby: enter: stream (0xb40365c0) usecase(7: audio-record)
V/audio_hw_primary(  275): in_standby: exit:  status(0)
V/AudioPolicyService(  275): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  275): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  275): AudioCommandThread() waking up
V/AudioPolicyService(  275): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  275): AudioCommandThread() going to sleep
V/AudioPolicyManager(  275): releaseInput() exit
V/AudioFlinger(  275): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  275): removeClient_l() pid 1943, calling pid 275
D/ToneMappingReceiver( 4548): do ALARM RingToneUriMapping() -> first find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/CommonUtil( 4548): Enter getMatchedBackupTone() enter URI value is On, parentInfo : ALARM
I/HotwordRecognitionRnr( 1943): Hotword detection finished
I/HotwordRecognitionRnr( 1943): Stopping hotword detection.
,D/CommonUtil( 4548): getFinededDefaultTone() -> backup ringtone value : null
D/CommonUtil( 4548): Exit getMatchedBackupTone() value is null
D/ToneMappingReceiver( 4548): do ALARM RingToneUriMapping() -> second find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/ToneMappingReceiver( 4548): Enter doAlarmRingToneUriMapping(), return value is 0
D/ToneMappingReceiver( 4548): Alarm Success count is 0
D/ToneMappingReceiver( 4548): Timer Success count is 0
I/MediaScannerReceiver( 3643): Calendar.onReceive: a=android.intent.action.MEDIA_SCANNER_FINISHED Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///system/media flg=0x10 cmp=com.android.calendar/.alerts.MediaScannerReceiver }, mData=file:///system/media
,I/InitNotificationRingtoneService( 3643): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 3643): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
E/MediaScanReceiver( 4571): media scanning finished
,I/com.lge.bnr.receiver.MediaScanReceiver( 4571): android.intent.action.MEDIA_SCANNER_FINISHED
I/AlertUtils( 3643): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,D/ContextHelper( 4640): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
I/GHttpClientFactory( 4591): Using our fixed implementation of GMSCore's GoogleHttpClient
I/AlertUtils( 3643): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
,I/AlertUtils( 3643): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/GoogleURLConnFactory( 4591): Using platform SSLCertificateSocketFactory
I/AlertUtils( 3643): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 3643): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 3643): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 3643): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/AlertUtils( 3643): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 3643): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 3643): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 3643): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
,I/AlertUtils( 3643): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 3643): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 3643): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
E/MediaScanReceiver( 4571): media scanning start or checking
,I/AlertUtils( 3643): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 3643): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
,I/AlertUtils( 3643): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 3643): set default noti to content://media/internal/audio/media/38
I/WebViewFactory( 4640): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/InitNotificationRingtoneService( 3643): End InitializeAlertRingtoneService.onHandleIntent
D/ToneMappingReceiver( 4548): Enter doAlarmRingToneUriMapping()
I/NotificationManager( 4591): com.google.android.music: cancel(1061) by com.google.android.music
,D/ToneMappingReceiver( 4548): do ALARM RingToneUriMapping() -> first find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/CommonUtil( 4548): Enter getMatchedBackupTone() enter URI value is On, parentInfo : ALARM
D/CommonUtil( 4548): getFinededDefaultTone() -> backup ringtone value : null
D/CommonUtil( 4548): Exit getMatchedBackupTone() value is null
D/ToneMappingReceiver( 4548): do ALARM RingToneUriMapping() -> second find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/ToneMappingReceiver( 4548): Enter doAlarmRingToneUriMapping(), return value is 0
D/ToneMappingReceiver( 4548): Alarm Success count is 0
D/ToneMappingReceiver( 4548): Timer Success count is 0
I/MediaScannerReceiver( 3643): Calendar.onReceive: a=android.intent.action.MEDIA_SCANNER_FINISHED Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///storage/emulated/0 flg=0x10 cmp=com.android.calendar/.alerts.MediaScannerReceiver }, mData=file:///storage/emulated/0
I/ActivityManager(  865): Killing 4413:com.lge.lgdmsclient/1000 (adj 15): empty #11
I/InitNotificationRingtoneService( 3643): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 3643): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,I/LibraryLoader( 4640): Time to load native libraries: 3 ms (timestamps 9074-9077)
,I/LibraryLoader( 4640): Expected native library version number "",actual native library version number ""
W/libprocessgroup(  865): failed to open /acct/uid_1000/pid_4413/cgroup.procs: No such file or directory
,E/MediaScanReceiver( 4571): media scanning finished
I/com.lge.bnr.receiver.MediaScanReceiver( 4571): android.intent.action.MEDIA_SCANNER_FINISHED
I/AlertUtils( 3643): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,V/WebViewChromiumFactoryProvider( 4640): Binding Chromium to main looper Looper (main, tid 1) {119ece07}
I/LibraryLoader( 4640): Expected native library version number "",actual native library version number ""
I/AlertUtils( 3643): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 3643): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,I/AlertUtils( 3643): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 3643): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/chromium( 4640): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4640): Initializing chromium process, singleProcess=true
,W/art     ( 4640): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4640): ApplicationContext is null in ApplicationStatus
I/art     ( 3129): Explicit concurrent mark sweep GC freed 8800(695KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 404us total 39.609ms
,I/AlertUtils( 3643): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 3643): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
W/chromium( 4640): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,I/AlertUtils( 3643): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 3643): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,W/chromium( 4640): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
I/ActivityManager(  865): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=4683 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/AlertUtils( 3643): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,E/libEGL  ( 4640): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4640): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4640): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4640): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 4640): Build Date: 03/02/15 Mon
I/Adreno-EGL( 4640): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 4640): Remote Branch: 
I/Adreno-EGL( 4640): Local Patches: 
I/Adreno-EGL( 4640): Reconstruct Branch: 
I/AlertUtils( 3643): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 3643): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 3643): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 3643): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 3643): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,I/AlertUtils( 3643): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3643): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/art     ( 4591): CheckpointMarkThreadRoots callback created = 0xb042d3f0
W/ResourcesManager( 4683): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/AlertUtils( 3643): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 3643): End InitializeAlertRingtoneService.onHandleIntent
,I/art     ( 4591): CheckpointMarkThreadRoots callback created = 0xb042d3d0
D/CalendarProvider2( 4683): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@119e6ea5
,D/CalendarProvider2( 4683): [getOrCreateCalendarAlarmManager]
,V/AudioPolicyService(  275): registerClient() client 0xb551c8c0, uid 10316
I/CalendarProvider2( 4683): Created com.android.providers.calendar.CalendarAlarmManager@1c4e5c46(com.android.providers.calendar.CalendarProvider2@119e6ea5)
D/CalendarProviderBroadcastReceiver( 4683): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
,D/CalendarProviderBroadcastReceiver( 4683): [IntentService] WakeLock acquire, start IntentSerivce
D/BluetoothManagerService(  865): Message: 20
D/BluetoothManagerService(  865): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@11e345d3:true
D/BluetoothAdapter( 4640): 815653465: getState() :  mService = null. Returning STATE_OFF
,D/CalendarProvider2( 4683): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 4683): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 4683): [getOrCreateCalendarAlarmManager]
,D/WearableService( 1733): callingUid 10006, callindPid: 1733
E/MDM     ( 1733): [129] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/AlarmManager(  865): ELAPSED_WAKEUP set : Alarm{2dd2c172 type 2 when 69440 com.google.android.gms} when 69440
,D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 4106): Restart initialization of location
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
I/MediaStoreImporter( 4591): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,D/CalendarProvider2( 4683): [IntentService] Release Lock
,D/CalendarProvider2( 4683): CalendarProviderIntentService.onDestroy()
I/art     ( 2005): Explicit concurrent mark sweep GC freed 2617(103KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.568ms total 45.391ms
,W/art     ( 4640): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 4640): onDetachedFromWindow called when already detached. Ignoring
,I/PhoneWindow( 4640): [generateLayout] setColorNavigationBar => color=0x ff000001
D/PhoneWindowEx( 4640): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow( 4640): [setNavigationBarColor2] color=0x fff5f5f5
D/SystemWebViewEngine( 4640): CordovaWebView is running on device made by: LGE
,I/ActivityManager(  865): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=4728 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/art     ( 4640): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4640): Attempt to remove local handle scope entry from IRT, ignoring
I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 22.132ms
,W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 313us total 22.143ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 328us total 21.928ms
,I/Activity( 4640): Activity.onPostResume() called 
W/IcingInternalCorpora( 4106): getNumBytesRead when not calculated.
,D/OpenGLRenderer( 4640): Render dirty regions requested: true
I/OpenGLRenderer( 4640): Initialized EGL, version 1.4
D/OpenGLRenderer( 4640): Enabling debug mode 0
,D/Atlas   ( 4640): Validating map...
,D/SplitWindow(  865): check instance of lgWin Window{35087b70 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 4640): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  865): Focus entered window: Window{35087b70 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  865): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  865): Displayed com.test.thalitest/.MainActivity: +1s339ms
I/Timeline(  865): Timeline: Activity_windows_visible id: ActivityRecord{3b126502 u0 com.test.thalitest/.MainActivity t224} time:69945
I/Timeline( 4640): Timeline: Activity_idle id: android.os.BinderProxy@ac8dace time:69965
,W/ActivityManager(  865): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/BindingManager( 4640): Cannot call determinedVisibility() - never saw a connection for the pid: 4640
,I/Gmail   ( 4728): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 4728): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  865): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 4728): getAccountsCursor
,E/Gmail   ( 4728): Error finding the version of the Email provider.....
E/Gmail   ( 4728): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4728): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4728): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4728): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4728): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4728): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4728): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 4728): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 4728): We do not support migrating this version of the Email provider.
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  865): Killing 3214:com.android.defcontainer/u0a4 (adj 15): empty #11
,W/ActivityManager(  865): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/libprocessgroup(  865): failed to open /acct/uid_10004/pid_3214/cgroup.procs: No such file or directory
W/ActivityManager(  865): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 4728): Observing account changes for notifications
W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  865): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=4783 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  865): Process com.lge.qremote (pid 4438) has died
,I/Gmail   ( 4728): notifyAccountChanged
,I/Gmail   ( 4728): getAccountsCursor
I/Gmail   ( 4728): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 4728): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/ActivityManager(  865): Waited long enough for: ServiceRecord{33b327db u0 com.lge.springcleaning/.service.AppCleanupService}
D/JsMessageQueue( 4640): Set native->JS mode to OnlineEventsBridgeMode
I/Gmail   ( 4728): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 4728): calculateUnknownSyncRationalesAndPurgeInBackground: running
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PhoneMonitor( 4783): Register our PhoneStateListener
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/PhoneMonitor( 4783): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 4783): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 4783): [parse] Load xml
V/TelephonyAutoProfiling( 4783): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 4783): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 4783): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/ActivityManager(  865): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=4806 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 4806): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/jxcore_app_log( 4640): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426130816
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4640): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4640):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4640):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4640):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4640):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4640): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@211df500 added. We now have 1 listener(s)
D/BluetoothManagerService(  865): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4640): setBluetoothMacAddress: F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4640): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4640): setIdentityString: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4640): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4640):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4640):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4640):     - Bluetooth MAC address: F8:95:C7:87:85:54
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4640):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4640):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4640):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4640):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4640):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4640):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4640): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ed612c added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4640): addListener: New listener added - the number of listeners is now 1
,I/Gmail   ( 4728): getAccountsCursor
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4640): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 4640): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 4640): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 4640): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 4640): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 4640): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 4640): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 4640): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 4640): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 4640): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 4640): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 4640): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4640): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4640): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4640): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/JX-Cordova( 4640): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4640): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4640): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33b5f7f5 added. We now have 2 listener(s)
D/BluetoothManagerService(  865): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4640): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4640): setIdentityString: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4640): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4640): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3285698a added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4640): addListener: New listener added - the number of listeners is now 1
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4640): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 4640): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 4640): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 4640): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 4640): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 4640): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 4640): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 4640): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 4640): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 4640): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 4640): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 4640): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4640): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4640): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4640): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/UEI.SmartControl( 4460): Internal timer expired: 1
,D/UEI.SmartControl( 4460): Service.onUnbind: IControl
D/UEI.SmartControl( 4460): Service.onDestroy
D/UEI.SmartControl( 4460): Shutdown IRRCPlayer... 
W/irrc_jni( 4460): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 4460): ~IrrcClient ++ 
D/irrcClient( 4460): ~IrrcClient -- 
W/irrc_jni( 4460): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 4460): Blaster closed
D/UEI.SmartControl( 4460): Blaster closed
D/UEI.SmartControl( 4460): Shut down QS...
D/UEI.SmartControl( 4460): Stopped file observer...
,I/UEI.SmartControl( 4460): QS lib stop result = true
D/UEI.SmartControl( 4460): QS shutdown complete
,I/ActivityManager(  865): Process com.android.settings (pid 4491) has died
I/Babel_SMS( 4806): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 4806): MmsConfig.loadMmsSettings
I/Babel_SMS( 4806): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 4806): MmsConfig.loadFromDatabase
,E/Babel_SMS( 4806): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4806): MmsConfig.loadFromResources
E/Babel_SMS( 4806): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 4806): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 4806): found sensor: LGE Accelerometer Sensor, handle=0
,D/SensorManager( 4806): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 4806): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 4806): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 4806): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 4806): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 4806): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 4806): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 4806): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 4806): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 4806): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 4806): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 4806): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 4806): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 4806): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 4806): found sensor: Motion Accel, handle=46
I/art     ( 4806): CheckpointMarkThreadRoots callback created = 0xb042d880
W/Settings( 4806): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/art     ( 4806): CheckpointMarkThreadRoots callback created = 0xb042d860
,I/Babel_Crash( 4806): startup - clean
I/Babel   ( 4806): deleted: false for 0
,W/AudioCapabilities( 4806): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 4806): Unsupported mime audio/adpcm
W/AudioCapabilities( 4806): Unsupported mime audio/g726
W/AudioCapabilities( 4806): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 4806): Unsupported mime audio/wma-voice
W/VideoCapabilities( 4806): Unsupported mime video/mjpg
W/VideoCapabilities( 4806): Unsupported mime video/theora
,W/AudioCapabilities( 4806): Unsupported mime audio/evrc
I/art     (  865): Explicit concurrent mark sweep GC freed 28760(1434KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/34MB, paused 2.070ms total 157.340ms
,W/AudioCapabilities( 4806): Unsupported mime audio/qcelp
W/VideoCapabilities( 4806): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 4806): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 4806): Unsupported mime audio/qcelp
W/AudioCapabilities( 4806): Unsupported mime audio/evrc
W/VideoCapabilities( 4806): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 4806): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4806): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4806): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4806): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4806): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 4806): onServiceConnected
,W/Babel   ( 4806): Attempted to change video mute state without an active call.
,I/ActivityManager(  865): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=4847 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/NotificationManager( 4806): com.google.android.talk: cancel(10436) by com.google.android.talk
,W/ResourcesManager( 4806): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4806): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 4847): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,V/JNIHelp ( 4806): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/BluetoothManagerService(  865): Message: 20
D/BluetoothManagerService(  865): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@20600906:true
,D/BluetoothAdapter( 4847): 352581330: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 4847): 352581330: getState() :  mService = null. Returning STATE_OFF
W/System  ( 4806): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 4806): Installed default security provider GmsCore_OpenSSL
D/UEI.SmartControl( 4460): QS Service created
E/UEI.SmartControl( 4460): QS start get config
,V/LGMDMManager( 4847): Create singleton instance
E/PhoneInterfaceManager( 1752): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
W/VideoCapabilities( 4806): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4806): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4806): Unrecognized profile 2130706433 for video/avc
,D/UEI.SmartControl( 4460):  configuring local db...
,I/NotificationManager( 4806): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/Babel   ( 4806): connection state changed from UNKNOWN to DISCONNECTED
I/AudioManager( 4847): getMode name:com.lge.qremote
,I/ActivityManager(  865): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=4872 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,D/AlertService( 3643): Beginning updateAlertNotification
,D/UEI.SmartControl( 4460):  ---- Has DB8: true
,D/UEI.SmartControl( 4460): QS start statue = true Error code = 0
D/UEI.SmartControl( 4460): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 4460): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 4460): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 4460): IRRCPlayer_nativeInit ++ 
D/irrcClient( 4460): IrrcClient ++ 
D/irrcClient( 4460): getIrrcService ++ 
D/irrcClient( 4460): getIrrcService -- 
D/irrcClient( 4460): IrrcClient -- 
W/irrc_jni( 4460): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 4460): Services init done
I/UEI.SmartControl( 4460): Device manager: loading config....
D/AlertService( 3643): No fired or scheduled alerts
,I/NotificationManager( 3643): com.android.calendar: cancel(0) by com.android.calendar
D/UEI.SmartControl( 4460): Config is loaded...
D/UEI.SmartControl( 4460): QS Service init finished
I/NotificationManager( 3643): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 3643): com.android.calendar: cancel(2) by com.android.calendar
D/UEI.SmartControl( 4460): QS Service version name: 0.1.73
D/UEI.SmartControl( 4460): QS Service version code: 1073
D/UEI.SmartControl( 4460): Service requested: Control
D/UEI.SmartControl( 4460): Internal service binding...
I/NotificationManager( 3643): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 3643): com.android.calendar: cancel(4) by com.android.calendar
D/UEI.SmartControl( 4460): -----IControl: 11
D/UEI.SmartControl( 4460): File observer start...
E/UEI.SmartControl( 4460): IR Port is disabled: false
D/UEI.SmartControl( 4460): Starting file observer...
D/UEI.SmartControl( 4460): Caller: com.lge.qremote
D/UEI.SmartControl( 4460): ------------ IControl registerCallback...
I/UEI.SmartControl( 4460): Registering callback...
D/UEI.SmartControl( 4460): -----IControl: 19
I/NotificationManager( 3643): com.android.calendar: cancel(5) by com.android.calendar
D/UEI.SmartControl( 4460): Caller: com.lge.qremote
I/UEI.SmartControl( 4460): Registering Services Ready callback...
I/UEI.SmartControl( 4460): Notify client services are ready...
,D/UEI.SmartControl( 4460): -----IControl: 8
I/NotificationManager( 3643): com.android.calendar: cancel(6) by com.android.calendar
D/UEI.SmartControl( 4460): Caller: com.lge.qremote
I/NotificationManager( 3643): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 3643): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 3643): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 3643): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 3643): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 3643): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 3643): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 3643): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 3643): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 3643): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 3643): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 3643): com.android.calendar: cancel(18) by com.android.calendar
,I/NotificationManager( 3643): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 3643): com.android.calendar: cancel(20) by com.android.calendar
W/ResourcesManager( 4872): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4872): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4872): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 4460):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 4460): Notify AllClients services are ready: 0
D/AlertService( 3643): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 3643): No events found starting within 1 week.
,I/LGEmail ( 4872): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 4872): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/PackageChangeReceiver( 4872): intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
,I/ActivityManager(  865): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=4902 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  865): Killing 4519:com.lge.sync/1000 (adj 15): empty #11
,W/libprocessgroup(  865): failed to open /acct/uid_1000/pid_4519/cgroup.procs: No such file or directory
,I/[SystemUI]QPairHandler( 1371): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1840): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[SystemUI]QSlideListController( 1371): onReceive = android.intent.action.PACKAGE_CHANGED
I/InputReader(  865): Reconfiguring input devices.  changes=0x00000010
,W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1371): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/art     ( 1787): CheckpointMarkThreadRoots callback created = 0xaaf20b90
,I/art     ( 1787): CheckpointMarkThreadRoots callback created = 0xb042d680
,I/ActivityManager(  865): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=4931 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/administrator(  865): Handling package changes for user 0
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/ActivityManager(  865): Killing 4548:com.lge.clock/u0a10 (adj 15): empty #11
W/libprocessgroup(  865): failed to open /acct/uid_10010/pid_4548/cgroup.procs: No such file or directory
,W/ResourcesManager(  865): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/ActivityManager(  865): Process com.google.android.music:main (pid 4591) has died
,I/NotificationService(  865): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  865): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  865): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  865): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/ResourceType(  865): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
V/BackupManagerService(  865): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  865): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3420e10a
,I/AppUp4:AppBoxCP( 4931): onCreate
W/AppUp4:DB( 4931):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 4931):  setFingerPrint start
I/AppUp4:DB( 4931):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 4931):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 4931):  SDK version = 0
I/AppUp4:DB( 4931):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 4931): AppBoxApplication onCreate()
I/GCoreNlp( 1733): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/AppUp4:PreloadHelper( 4931): removed from Exclude : com.test.thalitest : 1
D/LocationProviderProxy(  865): applying state to connected service
,I/ActivityManager(  865): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=4952 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,D/LCardEmulationManager( 1787): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1787): getDefaultRoute
,W/ResourcesManager( 4952): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4952): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 4952): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 73539378414; DSPS: 2507987; Offset : -3004386496
,I/AppConfig( 4952): Total System Memory = 906309632
,I/GalleryUtils( 4952): Application Heap = 96 MB
I/AppConfig( 4952): App Tier : NOT_DEF
D/SystemHelper( 4952): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ThermalEngine(  288): Sensor:pa_therm0:31000 mC
,I/ActivityManager(  865): Process com.google.android.gm (pid 4728) has died
,I/ActivityManager(  865): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=4978 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ResourcesManager( 4978): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4978): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 4978): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 4978): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 4978): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 4978): BUILD Country: EU
I/SystemConfig( 4978): BUILD Operator: OPEN
,I/SystemConfig( 4978): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 4978): existFile = false
I/SystemConfig( 4978): canReadFile = false
I/SystemConfig( 4978): systemFeature RCS result false
D/SystemConfig( 4978): refreshRcsSupport() :false
,I/ActivityManager(  865): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5002 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  865): Killing 4571:com.lge.bnr/1000 (adj 15): empty #11
W/libprocessgroup(  865): failed to open /acct/uid_1000/pid_4571/cgroup.procs: No such file or directory
,I/LockScreenSettings( 5002): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/LockScreenSettings( 5002): New app installed broadcast received ..
,I/LockScreenSettings( 5002): Number of installed packages  1
I/ActivityManager(  865): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=5020 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  865): Killing 4683:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/libprocessgroup(  865): failed to open /acct/uid_10014/pid_4683/cgroup.procs: No such file or directory
,D/EulaProviderUpdateObserver( 5020): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 5020): uri : package:com.test.thalitest
,I/ActivityManager(  865): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=5040 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  865): Killing 4783:com.google.android.setupwizard/u0a38 (adj 15): empty #11
I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 297us total 21.890ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 21.739ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 20.691ms
,W/libprocessgroup(  865): failed to open /acct/uid_10038/pid_4783/cgroup.procs: No such file or directory
D/[BNRAppListMgrReceiver]( 5040): android.intent.action.PACKAGE_ADDED : com.test.thalitest
,W/MainApplication( 5040): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,I/ActivityManager(  865): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5061 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  865): Killing 4847:com.lge.qremote/u0a106 (adj 15): empty #11
W/libprocessgroup(  865): failed to open /acct/uid_10106/pid_4847/cgroup.procs: No such file or directory
,D/Finsky  ( 5061): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 5061): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  865): android: cancelAsUser(2) by android
,W/Settings( 5061): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5061): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 5061): com.android.vending: cancel(-1050172287) by com.android.vending
,D/libc-netbsd( 5061): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5061): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5061): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
I/NotificationManager( 5061): com.android.vending: cancel(1003285959) by com.android.vending
D/libc-netbsd( 5061): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  269): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  865): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/Ads     ( 5061): Skipping gmscore version check
,I/ActivityManager(  865): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5111 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,V/DownloadManager( 3129): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3129): created cursor android.database.sqlite.SQLiteCursor@3f8bdbe7 on behalf of 5061
D/Finsky  ( 5061): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5061): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 5061): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/Finsky  ( 5061): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 5061): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  865): Killing 4460:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/libprocessgroup(  865): failed to open /acct/uid_10089/pid_4460/cgroup.procs: No such file or directory
,I/ActivityManager(  865): Killing 4872:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  865): failed to open /acct/uid_10021/pid_4872/cgroup.procs: No such file or directory
,I/chromium( 4640): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
I/chromium( 4640): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
,I/GAv4    ( 5111): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5111):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5111):   adb logcat -s GAv4
,W/GAv4    ( 5111): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5111): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5111): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 5111): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
,W/art     ( 5111): Suspending all threads took: 10.755ms
,D/Finsky  ( 5061): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  865): RTC_WAKEUP set : Alarm{3b7aa4d3 type 0 when 1457574271811 com.android.vending} when 1457574271811
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  865): android: cancelAsUser(2) by android
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5111): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
I/art     ( 5111): CheckpointMarkThreadRoots callback created = 0xaaede230
,I/ActivityManager(  865): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5161 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/art     ( 5111): CheckpointMarkThreadRoots callback created = 0xaaede3c0
,W/art     ( 5111): Suspending all threads took: 10.104ms
,W/ResourcesManager( 5111): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5111): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 5161): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/NotificationManager( 5111): com.google.android.apps.docs: cancel(10436) by com.google.android.apps.docs
,V/JNIHelp ( 5111): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/libc-netbsd( 5061): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5061): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5061): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5061): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  269): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  865): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,W/System  ( 5111): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5111): Installed default security provider GmsCore_OpenSSL
,I/art     (  865): Explicit concurrent mark sweep GC freed 32496(1654KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 2.081ms total 159.287ms
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 5061): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/ActivityManager(  865): Process com.android.gallery3d (pid 4952) has died
,I/NotificationManager(  865): android: cancelAsUser(2) by android
,D/libc-netbsd( 5061): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5061): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  865): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5187 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  865): android: cancelAsUser(2) by android
,W/ResourcesManager( 5187): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5187): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/libc-netbsd( 5061): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5061): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/Finsky  ( 5061): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/MultiDex( 5187): VM with version 2.1.0 has multidex support
I/MultiDex( 5187): install
,I/MultiDex( 5187): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 5187): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/ChimeraCfgMgr( 4106): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4106): Loading module APK com.google.android.play.games
,D/PackageBroadcastService( 4106): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
I/UpdateIcingCorporaServi( 1943): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/ActivityThread( 5187): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5187): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2b656418: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5187): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 5187): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5187): com.google.android.gms: cancel(39789) by com.google.android.gms
D/ChimeraCfgMgr( 5187): Reading stored module config
,D/ChimeraCfgMgr( 5187): Loading module com.google.android.gms.car from APK com.google.android.gms
,I/ActivityManager(  865): Process com.lge.appbox.client (pid 4931) has died
,I/UpdateIcingCorporaServi( 1943): UpdateCorporaTask done [took 204 ms] updated apps [took 204 ms] 
,D/CAR.SERVICE( 5187): Connecting to CarCallService...
,D/NativeLibraryUtils( 5187): Install completed successfully. count=14 extracted=0
,I/art     ( 5187): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5187): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/ChimeraCfgMgr( 4106): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4106): Module APK com.google.android.play.games already loaded
I/Icing   ( 4106): Storage manager: low false usage 1.71MB avail 2.37GB capacity 4.06GB
,D/ChimeraCfgMgr( 4106): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/CAR.SERVICE( 5187): com.google.android.projection.gearhead isn't installed.
,D/AsyncTaskServiceImpl( 4106): Submit a task: k
D/ChimeraCfgMgr( 4106): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 4106): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/CAR.TEL.Service( 5187): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 5187): Creating a new PhoneAdapter instance
W/ActivityManager(  865): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5187): setListener: com.google.android.gms.car.dn@75559c7
W/ActivityManager(  865): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5187): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 5187): Starting CarCallService with initial phone null
D/k       ( 4106): Processing package: com.test.thalitest
I/NotificationManager( 5187): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/GassUtils( 4106): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 4106): Found info for package com.test.thalitest in db.
,I/ActivityManager(  865): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=5238 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/PeopleDatabaseHelper( 4106): cleanUpNonGplusAccounts done.
,D/CAR.SERVICE( 5187): Package validated; name: com.android.vending
W/BaseAppContext( 4106): Using Auth Proxy for data requests.
W/BaseAppContext( 4106): Using Auth Proxy for data requests.
W/BaseAppContext( 4106): Using Auth Proxy for data requests.
,I/NotificationManager( 5061): com.android.vending: cancel(10436) by com.android.vending
V/Finsky  ( 5061): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,W/BaseAppContext( 4106): Using Auth Proxy for data requests.
W/ResourcesManager( 5238): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/BaseAppContext( 4106): Using Auth Proxy for data requests.
,D/BluetoothManagerService(  865): Message: 20
D/BluetoothManagerService(  865): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2afd7dfc:true
,D/BluetoothAdapter( 5238): 352581330: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 5238): 352581330: getState() :  mService = null. Returning STATE_OFF
I/ActivityManager(  865): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5260 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 5238): Create singleton instance
,I/AudioManager( 5238): getMode name:com.lge.qremote
,D/UEI.SmartControl( 5260): Quickset Services start...
I/UEI.SmartControl( 5260): Manufacture = LGE
D/UEI.SmartControl( 5260): File observer start...
E/UEI.SmartControl( 5260): IR Port is disabled: false
D/UEI.SmartControl( 5260): Starting file observer...
D/UEI.SmartControl( 5260): Extracting JNI libs...
,I/AudioManager( 5238): getMode name:com.lge.qremote
D/UEI.SmartControl( 5260): --- this system supports 32-bit or 64-bit only
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  269): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  865): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ActivityManager(  865): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5281 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  865): android: cancelAsUser(2) by android
,I/Icing   ( 4106): updateResources: need to parse f{com.google.android.gms}
D/libc-netbsd( 5061): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5061): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Finsky  ( 5061): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 5061): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  865): RTC_WAKEUP set : Alarm{3aab2e8a type 0 when 1457574273684 com.android.vending} when 1457574273684
D/Finsky  ( 5061): [1] DailyHygiene.reschedule: Giving up. (failures=6)
,D/WearableService( 1733): callingUid 10006, callindPid: 1733
,D/DeviceConnectionService( 1733): client connected with version: 8296000
D/Finsky  ( 5061): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5061): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
D/UEI.SmartControl( 5260): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5260): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5260): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 5260): --- Selecting new region: 2
,I/UEI.SmartControl( 5260): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 5260): Platform has CIR...
D/UEI.SmartControl( 5260): NO CIR support, need to check package...
,I/UEI.SmartControl( 5260): Model: LG-D722 uses JNI
W/ActivityManager(  865): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/UEI.SmartControl( 5260): QS Service created
E/UEI.SmartControl( 5260): QS start get config
,D/UEI.SmartControl( 5260): Loading JNI Libs...
,D/UEI.SmartControl( 5260):  configuring local db...
I/Gmail   ( 5281): getAccountsCursor
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 2005): Explicit concurrent mark sweep GC freed 3406(135KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 474us total 40.541ms
,W/GAV2    ( 5281): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Icing   ( 4106): Internal init done: storage state 0
W/ActivityManager(  865): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 5281): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Gmail   ( 5281): Error finding the version of the Email provider.....
E/Gmail   ( 5281): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5281): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5281): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5281): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5281): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5281): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5281): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5281): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5281): We do not support migrating this version of the Email provider.
,I/Icing   ( 4106): Post-init done
,I/ActivityManager(  865): Killing 4902:com.google.android.partnersetup/u0a9 (adj 15): empty #11
D/ChimeraCfgMgr( 4106): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4106): Module APK com.google.android.play.games already loaded
,W/ActivityManager(  865): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/libprocessgroup(  865): failed to open /acct/uid_10009/pid_4902/cgroup.procs: No such file or directory
I/Gmail   ( 5281): Observing account changes for notifications
,I/ThermalEngine(  288): Sensor:pa_therm0:31000 mC
W/ActivityManager(  865): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/UEI.SmartControl( 5260):  ---- Has DB8: true
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/UEI.SmartControl( 5260): QS start statue = true Error code = 0
D/UEI.SmartControl( 5260): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5260): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5260): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 5260): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5260): IrrcClient ++ 
D/irrcClient( 5260): getIrrcService ++ 
,D/irrcClient( 5260): getIrrcService -- 
D/irrcClient( 5260): IrrcClient -- 
W/irrc_jni( 5260): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5260): Services init done
D/UEI.SmartControl( 5260): QS Service init finished
I/UEI.SmartControl( 5260): Device manager: loading config....
,D/UEI.SmartControl( 5260): QS Service version name: 0.1.73
D/UEI.SmartControl( 5260): QS Service version code: 1073
D/UEI.SmartControl( 5260): Service requested: Control
I/AudioManager( 5238): getMode name:com.lge.qremote
D/UEI.SmartControl( 5260): Config is loaded...
I/AudioManager( 5238): getMode name:com.lge.qremote
,D/UEI.SmartControl( 5260):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5260): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 5260): Request IControl service: devices are loaded...
D/UEI.SmartControl( 5260): Internal service binding...
D/UEI.SmartControl( 5260): -----IControl: 11
,D/UEI.SmartControl( 5260): Caller: com.lge.qremote
D/UEI.SmartControl( 5260): ------------ IControl registerCallback...
I/UEI.SmartControl( 5260): Registering callback...
D/UEI.SmartControl( 5260): -----IControl: 19
D/UEI.SmartControl( 5260): Caller: com.lge.qremote
I/UEI.SmartControl( 5260): Registering Services Ready callback...
I/UEI.SmartControl( 5260): Notify client services are ready...
D/UEI.SmartControl( 5260): -----IControl: 8
D/UEI.SmartControl( 5260): Caller: com.lge.qremote
,I/NotificationManager( 4806): com.google.android.talk: cancel(8) by com.google.android.talk
I/ActivityManager(  865): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5330 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/art     (  865): Explicit concurrent mark sweep GC freed 19939(987KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 2.251ms total 154.049ms
I/ActivityManager(  865): Killing 5002:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,I/ActivityManager(  865): Killing 4978:com.android.contacts/u0a18 (adj 15): empty #12
,W/libprocessgroup(  865): failed to open /acct/uid_10069/pid_5002/cgroup.procs: No such file or directory
,W/libprocessgroup(  865): failed to open /acct/uid_10018/pid_4978/cgroup.procs: No such file or directory
I/NotificationManager( 1943): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/Gmail   ( 5281): notifyAccountChanged
I/Gmail   ( 5281): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5281): getAccountsCursor
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AppUp4:AppBoxCP( 5330): onCreate
W/AppUp4:DB( 5330):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 5330):  setFingerPrint start
I/AppUp4:DB( 5330):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/Gmail   ( 5281): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/AppUp4:DB( 5330):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5330):  SDK version = 0
I/AppUp4:DB( 5330):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 5330): AppBoxApplication onCreate()
I/Gmail   ( 5281): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5281): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/AppUp4:CustModeStarterReceiver( 5330): onReceive
,I/AppUp4:CustModeStarterReceiver( 5330): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 5330): Context : android.app.ReceiverRestrictedContext@3bda8e88
D/AppUp4:CustFacade( 5330): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5330): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 5330): begin check event
I/AppUp4:CustModeStarterReceiver( 5330): Event For Nothing, skip.
I/ActivityManager(  865): Killing 5020:com.lge.eula/1000 (adj 15): empty #11
I/art     ( 1733): Explicit concurrent mark sweep GC freed 28838(1801KB) AllocSpace objects, 15(240KB) LOS objects, 39% free, 13MB/22MB, paused 1.722ms total 91.851ms
,W/libprocessgroup(  865): failed to open /acct/uid_1000/pid_5020/cgroup.procs: No such file or directory
,I/ActivityManager(  865): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5361 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/Gmail   ( 5281): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 5361): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5361): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5361): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/AppConfig( 5361): Total System Memory = 906309632
,I/GalleryUtils( 5361): Application Heap = 96 MB
I/AppConfig( 5361): App Tier : NOT_DEF
D/SystemHelper( 5361): region [EU], country [EU], operator [OPEN], sub-operator []
,I/Icing   ( 4106): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/ActivityManager(  865): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5384 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  865): Killing 5040:com.lge.bnr/1000 (adj 15): empty #11
D/Icing   ( 4106): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 4106): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,W/libprocessgroup(  865): failed to open /acct/uid_1000/pid_5040/cgroup.procs: No such file or directory
I/ActivityManager(  865): Killing 5111:com.google.android.apps.docs/u0a58 (adj 15): empty #11
,W/ResourcesManager( 5384): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5384): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5384): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 5384): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5384): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  865): failed to open /acct/uid_10058/pid_5111/cgroup.procs: No such file or directory
,I/SystemConfig( 5384): BUILD Country: EU
I/SystemConfig( 5384): BUILD Operator: OPEN
,I/ActivityManager(  865): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5403 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  865): Killing 5161:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 21.209ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 21.819ms
,W/libprocessgroup(  865): failed to open /acct/uid_10086/pid_5161/cgroup.procs: No such file or directory
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 20.828ms
I/SystemConfig( 5384): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5384): existFile = false
I/SystemConfig( 5384): canReadFile = false
I/SystemConfig( 5384): systemFeature RCS result false
D/SystemConfig( 5384): refreshRcsSupport() :false
I/LockScreenSettings( 5403): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 5403): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5403): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5403): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5403): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5403): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  865): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5423 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  865): Killing 4106:com.google.android.gms/u0a6 (adj 15): empty #11
W/libprocessgroup(  865): failed to open /acct/uid_10006/pid_4106/cgroup.procs: No such file or directory
,W/ResourcesManager( 5423): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1943): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  865): Start proc com.google.android.gms for service com.google.android.gms/.app.service.PackageBroadcastService: pid=5449 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  865): Killing 2005:com.google.process.gapps/u0a6 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1943): UpdateCorporaTask done [took 80 ms] updated apps [took 79 ms] 
W/libprocessgroup(  865): failed to open /acct/uid_10006/pid_2005/cgroup.procs: No such file or directory
,W/ResourcesManager( 5449): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5449): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5449): VM with version 2.1.0 has multidex support
I/MultiDex( 5449): install
I/MultiDex( 5449): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  865): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5468 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/GservicesProvider( 5468): Gservices pushing to system: true; secure/global: true
I/GoogleHttpClient( 5468): GMS http client unavailable, use old client
I/GoogleHttpClient( 5468): GMS http client unavailable, use old client
V/JNIHelp ( 5449): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ActivityThread( 5449): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5449): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@22a6a8de: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5449): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5449): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5449): com.google.android.gms: cancel(39789) by com.google.android.gms
D/PackageBroadcastService( 5449): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/ActivityManager(  865): Killing 5281:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  865): failed to open /acct/uid_10053/pid_5281/cgroup.procs: No such file or directory
I/PackageBroadcastService( 5449): Null package name or gms related package.  Ignoreing.
E/MDM     ( 1733): [84] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 5449): Restart initialization of location
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
I/AudioManager( 5238): getMode name:com.lge.qremote
D/Finsky  ( 5061): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
D/Finsky  ( 5061): [586] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/NativeLibraryUtils( 5449): Install completed successfully. count=14 extracted=0
I/ActivityManager(  865): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5508 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  865): android: cancelAsUser(2) by android
D/libc-netbsd( 5061): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5061): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5061): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5061): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  269): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  865): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/art     ( 5449): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 5449): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5449): CheckpointMarkThreadRoots callback created = 0xb056d8b0
,I/Icing   ( 5449): Storage manager: low false usage 1.71MB avail 2.37GB capacity 4.06GB
I/art     ( 5449): CheckpointMarkThreadRoots callback created = 0xb056d8a0
,I/art     ( 5449): Background partial concurrent mark sweep GC freed 3741(427KB) AllocSpace objects, 12(192KB) LOS objects, 39% free, 10MB/17MB, paused 9.759ms total 57.482ms
,W/ActivityManager(  865): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/IcingInternalCorpora( 5449): getNumBytesRead when not calculated.
W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
,I/Gmail   ( 5508): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     (  865): Explicit concurrent mark sweep GC freed 14317(709KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 2.180ms total 133.449ms
,I/art     (  865): WaitForGcToComplete blocked for 100.185ms for cause HeapTrim
W/ActivityManager(  865): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 5508): Observing account changes for notifications
,W/ActivityManager(  865): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/GAV2    ( 5508): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  865): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Icing   ( 5449): updateResources: need to parse f{com.google.android.gms}
E/Gmail   ( 5508): Error finding the version of the Email provider.....
E/Gmail   ( 5508): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5508): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5508): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5508): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5508): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5508): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5508): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5508): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 5508): We do not support migrating this version of the Email provider.
I/Gmail   ( 5508): getAccountsCursor
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AudioManager( 5238): getMode name:com.lge.qremote
I/ActivityManager(  865): Killing 5330:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  865): failed to open /acct/uid_10011/pid_5330/cgroup.procs: No such file or directory
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/MDM     ( 1733): [103] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 5449): Restart initialization of location
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
,I/AudioManager( 5238): getMode name:com.lge.qremote
W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
I/AudioManager( 5238): getMode name:com.lge.qremote
,I/AudioManager( 5238): getMode name:com.lge.qremote
,I/AudioManager( 5238): getMode name:com.lge.qremote
I/Icing   ( 5449): Internal init done: storage state 0
,I/NotificationManager( 5449): com.google.android.gms: cancel(10436) by com.google.android.gms
I/Gmail   ( 5508): notifyAccountChanged
,I/Gmail   ( 5508): getAccountsCursor
I/Gmail   ( 5508): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5508): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5508): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5508): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Icing   ( 5449): Post-init done
,I/Icing   ( 5449): updateResources: need to parse f{com.google.android.gms}
I/Gmail   ( 5508): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/InitAlarmsService( 3643): Clearing and rescheduling alarms.
,I/ActivityManager(  865): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5598 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 5598): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CAR.SERVICE( 5187): mConnectedToCar = false, abort
,D/CalendarProvider2( 5598): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@119e6ea5
E/ActivityThread( 5187): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@32073fcf that was originally bound here
E/ActivityThread( 5187): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@32073fcf that was originally bound here
E/ActivityThread( 5187): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5187): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5187): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5187): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5187): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5187): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5187): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5187): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5187): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5187): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 5187): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 5187): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 5187): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 5187): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 5187): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 5187): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 5187): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5187): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5187): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5187): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5187): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5187): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5187): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 5187): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1d5cbf06 that was originally bound here
E/ActivityThread( 5187): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1d5cbf06 that was originally bound here
E/ActivityThread( 5187): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5187): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5187): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5187): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5187): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5187): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5187): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5187): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 5187): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 5187): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 5187): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 5187): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 5187): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 5187): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 5187): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 5187): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5187): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5187): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5187): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5187): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5187): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5187): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  865): Unbind failed: could not find connection for android.os.BinderProxy@3c118ff3
D/CalendarProvider2( 5598): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 5598): Created com.android.providers.calendar.CalendarAlarmManager@1c4e5c46(com.android.providers.calendar.CalendarProvider2@119e6ea5)
,D/CalendarProvider2( 5598): Scheduling check of next Alarm
D/CalendarProvider2( 5598): SCHEDULE_ALARM_REMOVE
I/ActivityManager(  865): Killing 3643:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  865): failed to open /acct/uid_10013/pid_3643/cgroup.procs: No such file or directory
,I/Icing   ( 5449): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/Icing   ( 5449): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 5449): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/ThermalEngine(  288): Sensor:pa_therm0:32000 mC
,D/UEI.SmartControl( 5260): Internal timer expired: 1
,I/CalendarProvider2( 5598): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5598): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  865): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=5626 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  865): Killing 5361:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/libprocessgroup(  865): failed to open /acct/uid_10023/pid_5361/cgroup.procs: No such file or directory
W/ResourcesManager( 5626): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 5626): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 5626): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 5626): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@2ad0ba2b, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@3bda8e88, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@18ac5021, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@1c4e5c46, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@119ece07, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@3ce0b34, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@45ccd5d, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@1503f6d2, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@205043a3, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@29daa6a0, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@309de259, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3806ae1e, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@2d1976ff, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@3e538ccc, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@30414b15, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@17eb8e2a, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@1318841b, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@2192a9b8, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@37788391, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@298c62f6, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@373146f7, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@1da4a964, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@3210c7cd, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@393b882, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@3ea95b93, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2eb4f7d0, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@16f13c9, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@ac8dace, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@13841def, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@2639c0fc, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@1e4c2385, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@171bd5da, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@129eaa0b, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@14dff0e8, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@1a307301, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@1d7175a6, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@3f8bdbe7, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@27373394, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@3cb03e3d, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2a2f4632, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@1a304f83, lg_preferences_,recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@211
,D/GeneralPreferenceUtils( 5626): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 5626): [init]
I/Config  ( 5626): LGCalendar ver.4.40.17
I/Config  ( 5626): start check model
I/Config  ( 5626): start check native_ca
I/Config  ( 5626): Config Operator=OPEN, Country=EU
,D/Config  ( 5626): [setDefaultValuesToPref]
D/Config  ( 5626): [parseProfiles]
D/ProfilesParser( 5626): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 5626): [debug_displayParseInfos] profile.operator = null
D/Config  ( 5626): [updateProfiletoCountryInfo]
D/GeneralPreference( 5626): [checkAndMigrateOldPreference]
D/AlertReceiver( 5626): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,I/InitNotificationRingtoneService( 5626): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 5626): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,I/AlertUtils( 5626): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 5626): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 5626): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 5626): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 5626): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 5626): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 5626): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 5626): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 5626): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 5626): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 5626): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 5626): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 5626): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 5626): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 5626): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 5626): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 5626): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 5626): set default noti to content://media/internal/audio/media/38
,I/InitNotificationRingtoneService( 5626): End InitializeAlertRingtoneService.onHandleIntent
W/HolidayIntentService( 5626): onHandleIntent
,D/HolidayDataLoader( 5626): readJsonAsset : holiday.json
D/AlertService( 5626): 0 Action = android.intent.action.PROVIDER_CHANGED
E/AgendaWidgetManager( 5626): [updateWidgets] 
,D/MonthWidgetProvider( 5626): [onReceive]
D/CalendarWidgetProvider( 5626): [onReceive]
D/CalendarWidgetProvider( 5626): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 5626): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 5626): [onReceive]
D/CalendarWidgetProvider( 5626): [onReceive]
D/CalendarWidgetProvider( 5626): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 5626): [onCreate] mContext.getPackageName() = com.android.calendar
,E/HolidayIntentService( 5626): onHandleIntent:holiday data empty
,I/ActivityManager(  865): Killing 5384:com.android.contacts/u0a18 (adj 15): empty #11
,W/libprocessgroup(  865): failed to open /acct/uid_10018/pid_5384/cgroup.procs: No such file or directory
,I/GAv4-SVC( 5449): Google Analytics 8.4.89 is starting up.
,I/GAV2    ( 5508): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  865): Killing 5403:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/libprocessgroup(  865): failed to open /acct/uid_10069/pid_5403/cgroup.procs: No such file or directory
,V/AlarmManager(  865): ELAPSED_WAKEUP set : Alarm{157f2a74 type 2 when 87696 com.android.providers.calendar} when 87696
,D/CalendarProviderBroadcastReceiver( 5598): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 5598): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 5598): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 5598): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 5598): [getOrCreateCalendarAlarmManager]
D/CalendarProvider2( 5598): [IntentService] Release Lock
,D/CalendarProvider2( 5598): CalendarProviderIntentService.onDestroy()
I/ThermalEngine(  288): Sensor:pa_therm0:32000 mC
,D/libc-netbsd(  865): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  865): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  865): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  865): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  269): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  269): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  865): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/AlertService( 5626): Beginning updateAlertNotification
,D/AlertService( 5626): No fired or scheduled alerts
,I/NotificationManager( 5626): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 5626): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 5626): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 5626): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 5626): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5626): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 5626): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 5626): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 5626): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 5626): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 5626): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 5626): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 5626): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 5626): com.android.calendar: cancel(13) by com.android.calendar
,I/NotificationManager( 5626): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 5626): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 5626): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 5626): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5626): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 5626): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 5626): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 5626): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 5626): No events found starting within 1 week.
,I/ActivityManager(  865): Killing 5423:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  865): failed to open /acct/uid_10086/pid_5423/cgroup.procs: No such file or directory
,V/AlarmManager(  865): RTC_WAKEUP set : Alarm{37be5be3 type 0 when 1457574288256 com.android.vending} when 1457574288256
,D/Finsky  ( 5061): [575] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5061): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 93541026021; DSPS: 3163401; Offset : -3004387152
,I/ThermalEngine(  288): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  865): ELAPSED_WAKEUP set : Alarm{309e79e0 type 2 when 102183 com.google.android.gms} when 102183
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  269): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=0, netid=0
,D/DSQN    (  865): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/rmt_storage(  267): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  267): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  267): wakelock acquired: 1, error no: 42
,I/rmt_storage(  267): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
I/rmt_storage(  267): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  267): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  267): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  267): 
I/rmt_storage(  267): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/ThermalEngine(  288): Sensor:pa_therm0:31000 mC
,D/PowerManagerServiceEx(  865): acquireWakeLockInternal: lock=847068853, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=865
,D/WeatherService( 2595): 2 : TimeTick Intent has been received, Time(hour:min:sec) 2:45:0
D/WeatherService( 2595): 2 : TimeTick Intent And Screen On
D/WeatherService( 2595): 2 : SDK version : 21
W/ActivityManager(  865): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2595): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2595): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2595): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2595): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2595): 2 : This is isUpdating : false
D/WeatherService( 2595): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2595): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2595): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2595): 2 : Fixed theme : optimus
D/WeatherReflect( 2595): 2 : Map key string is -2
,D/lim     ( 2595): 2 : time = 02:45
I/WeatherReflect( 2595): Model Name : LG-D722
D/WeatherTheme( 2595): 2 : Different view - status_min_formatted : 44 != 45
D/WeatherTheme( 2595): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2595): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
,D/Theme   ( 2595): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2595): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2595): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2595): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/[SystemUI]Clock( 1371): called onTimeUpdated()
I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
,I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/Weather4x2_optimus( 2595): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2595): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2595): forecast size is 0
D/Theme   ( 2595): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2595): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2595): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2595): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2595): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2595): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2595): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2595): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2595): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2595): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2595): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2595): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2595): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2595): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2595): setTouchIntent, appWidgetId: 2
,D/Theme_WeatherAncestor_optimus( 2595): url is : null
D/Theme   ( 2595): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2595): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2595): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2595): 2 : update view, appWidgetId: 2
D/WeatherService( 2595): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 2:45:0
,D/PowerManagerServiceEx(  865): releaseWakeLockInternal: lock=847068853 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/ThermalEngine(  288): Sensor:pa_therm0:31000 mC
,W/ContextImpl( 3476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 113542555506; DSPS: 3818811; Offset : -3004383389
,I/ThermalEngine(  288): Sensor:pa_therm0:31000 mC
,I/MusicWidget( 2544): mDelayedStopHandler : unbind
,I/MusicBrowser( 2613): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2613): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2613): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2613): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2613): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2613): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2613): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2613): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  865):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@1da4a964com.lge.music.MediaPlaybackService$6@3210c7cd
,D/MusicBrowser( 2613): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
,I/MusicBrowser( 2613): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2613): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2613): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2613): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@205043a3
I/MusicBrowser( 2613): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2613): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2613): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2613): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2613): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2613): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2613): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2613): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2613): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2613): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2613): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2613): [MediaPlaybackService.java:6745:release()] oooooo 
,I/MusicBrowser( 2613): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2613): reset
V/MediaPlayer[Native]( 2613): setListener
,V/MediaPlayer[Native]( 2613): disconnect
V/MediaPlayer[Native]( 2613): destructor
V/AudioFlinger(  275): releasing 19 from 2613 for -1
V/AudioFlinger(  275):  decremented refcount to 0
V/AudioFlinger(  275): purging stale effects
V/MediaPlayer[Native]( 2613): disconnect
D/MusicBrowser( 2613): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2613): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2613): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2613): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2613): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2613): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2613): [SmartShareManagerClient] unregisterListener: 60012674
W/SmartShareClient( 2613): [SmartShareManagerClient] unregisterListener invalid listener: 60012674
I/SmartShareClient( 2613): [SmartShareManagerClient] terminate service: 2613/MediaPlaybackService/413945889
E/HomeCloudIF( 2613): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2613): [SmartShareManagerClient] unbindService context:android.app.Application@3ea95b93
V/CloudHub( 2613): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2613): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2613): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
,I/MusicBrowser( 2613): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2613): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  865): Killing 5187:com.google.android.gms:car/u0a6 (adj 15): empty #11
I/CloudHub( 2613): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29982
,W/libprocessgroup(  865): failed to open /acct/uid_10006/pid_5187/cgroup.procs: No such file or directory
,I/ThermalEngine(  288): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:31000 mC
,I/CloudHub( 2613): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19941
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  481): init target 500000
D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
D/WifiController(  865): battery changed pluggedType: 2
,I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 128544937851; DSPS: 4310412; Offset : -3004473409
,I/ThermalEngine(  288): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 143547387588; DSPS: 4802006; Offset : -3004281844
,I/ThermalEngine(  288): Sensor:pa_therm0:31000 mC
,I/CloudHub( 2613): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
I/CloudHub( 2613): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,I/PowerManagerService(  865): ALS enabled for SRE
,D/PowerManagerServiceEx(  865): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (27028 ms ago)
D/qdlights(  865): set_light_backlight: 252
,D/qdlights(  865): set_light_backlight: 249
D/qdlights(  865): set_light_backlight: 245
,D/qdlights(  865): set_light_backlight: 242
,D/qdlights(  865): set_light_backlight: 239
,D/qdlights(  865): set_light_backlight: 235
,D/qdlights(  865): set_light_backlight: 232
,D/qdlights(  865): set_light_backlight: 229
,D/qdlights(  865): set_light_backlight: 225
,D/qdlights(  865): set_light_backlight: 222
,D/qdlights(  865): set_light_backlight: 219
,D/qdlights(  865): set_light_backlight: 215
,D/qdlights(  865): set_light_backlight: 212
,D/qdlights(  865): set_light_backlight: 209
,D/qdlights(  865): set_light_backlight: 205
,D/qdlights(  865): set_light_backlight: 202
,D/qdlights(  865): set_light_backlight: 199
,D/qdlights(  865): set_light_backlight: 195
,D/qdlights(  865): set_light_backlight: 192
,D/qdlights(  865): set_light_backlight: 189
,D/qdlights(  865): set_light_backlight: 185
,D/qdlights(  865): set_light_backlight: 182
,D/qdlights(  865): set_light_backlight: 178
,D/qdlights(  865): set_light_backlight: 175
,D/qdlights(  865): set_light_backlight: 172
,D/qdlights(  865): set_light_backlight: 168
,D/qdlights(  865): set_light_backlight: 165
,D/qdlights(  865): set_light_backlight: 162
,D/qdlights(  865): set_light_backlight: 158
,D/qdlights(  865): set_light_backlight: 155
,D/qdlights(  865): set_light_backlight: 152
,D/qdlights(  865): set_light_backlight: 148
,D/qdlights(  865): set_light_backlight: 145
,D/qdlights(  865): set_light_backlight: 142
,D/qdlights(  865): set_light_backlight: 138
,D/qdlights(  865): set_light_backlight: 135
,D/qdlights(  865): set_light_backlight: 132
,D/qdlights(  865): set_light_backlight: 128
,D/qdlights(  865): set_light_backlight: 125
,D/qdlights(  865): set_light_backlight: 122
,D/qdlights(  865): set_light_backlight: 118
,D/qdlights(  865): set_light_backlight: 115
,D/qdlights(  865): set_light_backlight: 112
,D/qdlights(  865): set_light_backlight: 108
,D/qdlights(  865): set_light_backlight: 105
,D/qdlights(  865): set_light_backlight: 102
,D/qdlights(  865): set_light_backlight: 98
,D/qdlights(  865): set_light_backlight: 95
,D/qdlights(  865): set_light_backlight: 92
,D/qdlights(  865): set_light_backlight: 88
,D/qdlights(  865): set_light_backlight: 85
,D/qdlights(  865): set_light_backlight: 82
,D/qdlights(  865): set_light_backlight: 78
,D/qdlights(  865): set_light_backlight: 75
,D/qdlights(  865): set_light_backlight: 72
,D/qdlights(  865): set_light_backlight: 68
,D/qdlights(  865): set_light_backlight: 65
,D/qdlights(  865): set_light_backlight: 62
,D/qdlights(  865): set_light_backlight: 58
,D/qdlights(  865): set_light_backlight: 55
,D/qdlights(  865): set_light_backlight: 52
,D/qdlights(  865): set_light_backlight: 48
,D/qdlights(  865): set_light_backlight: 45
,D/qdlights(  865): set_light_backlight: 42
,D/qdlights(  865): set_light_backlight: 38
,D/qdlights(  865): set_light_backlight: 35
,D/qdlights(  865): set_light_backlight: 32
,D/qdlights(  865): set_light_backlight: 28
,D/qdlights(  865): set_light_backlight: 25
,D/qdlights(  865): set_light_backlight: 22
,D/qdlights(  865): set_light_backlight: 18
,D/qdlights(  865): set_light_backlight: 15
,D/qdlights(  865): set_light_backlight: 12
,D/qdlights(  865): set_light_backlight: 10
,I/ThermalEngine(  288): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  865): ELAPSED_WAKEUP set : Alarm{1fdc5499 type 2 when 131763 com.google.android.gms} when 131763
,D/libc-netbsd(  865): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  865): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  865): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  865): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  269): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=0, netid=0
,D/DSQN    (  865): DNSproblemNotiEnabled is disabled ignore DNS fail CB
V/AlarmManager(  865): ELAPSED_WAKEUP set : Alarm{39ecd35e type 2 when 150753 com.google.android.gms} when 150753
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  269): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  865): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  288): Sensor:pa_therm0:31000 mC
,I/PowerManagerService(  865): ALS enabled for SRE
D/PowerManagerServiceEx(  865): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (34005 ms ago)
I/PowerManagerService(  865): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  865): ALS enabled for SRE
D/PowerManagerServiceEx(  865): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (34021 ms ago)
,W/ContextImpl(  865): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  865): Sleeping (uid 1000)...
D/LPWGController(  865): [updateScreenState] screen on = false
D/LPWGController(  865): disable proximity sensor
,D/LPWGController(  865): enable proximity sensor
I/SensorManager(  865): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@2af0d33f] by com.android.server.power.ProximitySensorListener.enable():120
I/sensors_hal_Ctx(  865): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  865): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
,D/sensors_hal_SAM(  865): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  865): activate: handle is 48, enable
V/sensors_hal_Ctx(  865): activate sensors is 1400000000000
D/sensors_hal_Thresh(  865): enable: handle=48
I/sensors_hal_SAM(  865): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  865): waitForResponse: timeout=1000
V/sensors_hal_SAM(  865): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  865): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  865): enable: Received response: 0
D/PowerManagerServiceEx(  865): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (34056 ms ago)
I/Adreno-EGL(  865): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  865): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  865): Build Date: 03/02/15 Mon
I/Adreno-EGL(  865): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  865): Remote Branch: 
I/Adreno-EGL(  865): Local Patches: 
I/Adreno-EGL(  865): Reconstruct Branch: 
,D/PermissionCache(  246): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (157 us)
,I/Sensors (  420): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  865): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  865): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  865): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  865): processInd: handle 48, count=1
V/sensors_hal_Thresh(  865): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  865): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  865): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  865): poll: count: 256
I/sensors_hal_Ctx(  865): poll: released wakelock sensor_ind
D/sensors_hal_Util(  865): waitForResponse: timeout=0
D/LPWGController(  865): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  865): current mode = 1  value = 1 1
I/LPWGController(  865): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  865): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  865): set_light_backlight: 0
,I/SensorManager(  865): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  865): activate: handle is 46, disable
V/sensors_hal_Ctx(  865): activate sensors is 1000000000000
D/sensors_hal_LP2(  865): enable: handle=46
D/sensors_hal_LP2(  865): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  865): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  246): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  246): hwc_blank: Blanking display: 0
I/DisplayManagerService(  865): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  865): Display changed displayId=0
V/sensors_hal_SAM(  865): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  865): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1752): Display #0 changed.
,D/qdhwcomposer(  246): hwc_blank: Done blanking display: 0
D/SurfaceControl(  865): Excessive delay in setPowerMode(): 197ms
,I/qdhwcomposer(  246): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  865): Got set_interactive hint
D/KeyguardViewMediator( 1371): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1329): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1329): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1329): handleNotifyScreenOFF
D/KeyguardViewMediator( 1371): notifyScreenOffLocked
D/WifiServerServiceExt(  865): sendKtScanInterval  mRtspPlay : false
,V/AudioFlinger(  275): setParameters(): io 0, keyvalue screen_state=on, calling pid 865
D/audio_hw_primary(  275): adev_set_parameters: enter: screen_state=on
V/voice   (  275): voice_set_parameters: enter: screen_state=on
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
D/KeyguardViewMediator( 1371): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1371): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1371): unregisterProximitySensor
,D/StatusBarWindowView( 1371): onScreenTurnedOff why = 3
D/JX-Cordova( 4640): jxcore cordova android initializing
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4640): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4640): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13b22bfb added. We now have 3 listener(s)
D/BluetoothManagerService(  865): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4640): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4640): setIdentityString: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4640): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4640): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b656418 added. We now have 3 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4640): addListener: New listener added - the number of listeners is now 1
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4640): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 4640): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/GpsLocationProvider(  865): receive broadcast intent, action: android.intent.action.SCREEN_ON
,W/System.err( 4640): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
,W/System.err( 4640): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 4640): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 4640): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.SCREEN_ON
W/System.err( 4640): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 4640): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 4640): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 4640): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 4640): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 4640): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4640): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4640): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4640): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/QCNEJ   ( 1840): |CORE| sendScreenState: state:true
I/LEDService( 1805): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1805): stopPatternFlashing()
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
,I/LEDService( 1805): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
I/LEDService( 1805): updateLightsLocked : turn off led
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
,D/LEDHandler( 1805): RESTART MSG
,D/SplitWindow(  865): check instance of lgWin Window{42ec76a u0 SearchPanel}
,D/LNfcService( 1787): action : android.intent.action.SCREEN_ON
I/Cliptray Service( 1805): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/Cliptray Service( 1805): lockStatus = 0
D/NfcServiceNXP( 1787): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1787): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1787): isRequireNfcCRouting() return true
D/LNfcService( 1787): isHCERoutingtoHost() return : true
D/NfcService( 1787): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1787): mEnableLPD: true
D/NfcService( 1787): mEnableReader: false
D/NfcService( 1787): mEnableHostRouting: true
D/NfcService( 1787): newParams.techmask= mTechMask: default
D/NfcService( 1787): mEnableLPD: true
D/NfcService( 1787): mEnableReader: false
D/NfcService( 1787): mEnableHostRouting: true
D/NfcService( 1787): screenState= 3
D/NfcService( 1787): Discovery configuration equal, not updating.
,D/InputDispatcher(  865): Window went away: Window{3378e1e0 u0 SearchPanel}
I/[SystemUI]Clock( 1371): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1371): time changed, timezoneChanged : false
,D/Ulp_jni (  865): JNI:system_update. Event-0
,V/PhoneApp( 1752): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
D/WeatherService( 2595): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 2:45:50
,D/WeatherService( 2595): 2 : ACTION screen on
D/WeatherService( 2595): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2595): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2595): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 2:45:50
D/AppCleanupService( 3955): android.intent.action.SCREEN_ON
,V/AudioFlinger(  275): setParameters(): io 0, keyvalue screen_state=off, calling pid 865
D/audio_hw_primary(  275): adev_set_parameters: enter: screen_state=off
,V/voice   (  275): voice_set_parameters: enter: screen_state=off
,V/compress_voip(  275): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  275): voice_extn_compress_voip_set_parameters: exit
V/voice   (  275): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  275): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  275): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  275): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  275): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  275): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  275): adev_set_parameters: exit with code(0)
D/WifiController(  865): CMD_SCREEN_OFF 
D/WifiController(  865): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  865): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1840): |CORE| sendScreenState: state:false
,I/LEDService( 1805): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1805): stopPatternFlashing()
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
I/LEDService( 1805): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1805): clear
I/LEDService( 1805): updateLightsLocked : turn on led
E/LEDService( 1805): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1805): Can't handle this request of patternId:0
D/LEDHandler( 1805): RESTART MSG
,D/LNfcService( 1787): action : android.intent.action.SCREEN_OFF
I/Cliptray Service( 1805): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,I/[LGHome]EVENT( 1878): [Launcher.java:1711:onReceive()]Screen Off
V/PhoneApp( 1752): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,I/art     (  865): Explicit concurrent mark sweep GC freed 22090(1140KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 22MB/33MB, paused 2.018ms total 152.617ms
,D/NfcServiceNXP( 1787): mScreenState : 1, mInProvisionMode : false
D/WeatherService( 2595): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 2:45:51
D/WeatherService( 2595): 2 : ACTION screen off
D/WeatherService( 2595): 2 : TimeTick Receiver Unregister
D/WeatherService( 2595): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 2:45:51
D/AppCleanupService( 3955): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 3955): AppUsageStatsSaveTask
,E/NxpNfcJni( 1787): getReconnectState = 0x0
,D/LCardEmulationManager( 1787): getHceAppCount hostAppNum : 0
,D/LCardEmulationManager( 1787): getDefaultRoute
D/LNfcService( 1787): isRequireNfcCRouting() return true
D/LNfcService( 1787): isHCERoutingtoHost() return : true
D/NfcService( 1787): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1787): mEnableLPD: true
D/NfcService( 1787): mEnableReader: false
D/NfcService( 1787): mEnableHostRouting: true
D/NfcService( 1787): newParams.techmask= mTechMask: 0
D/NfcService( 1787): mEnableLPD: true
D/NfcService( 1787): mEnableReader: false
D/NfcService( 1787): mEnableHostRouting: true
D/NfcService( 1787): screenState= 1
E/NxpNfcJni( 1787): getReconnectState = 0x0
,I/Sensors (  420): sns_pwr.c(301):releasing wakelock
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 158548093708; DSPS: 5293554; Offset : -3004429903
,I/ThermalEngine(  288): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  865): ELAPSED_WAKEUP set : Alarm{2ea9645b type 2 when 159927 com.android.systemui} when 159927
,D/KeyguardViewMediator( 1371): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/PhoneUtils( 1752): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1752): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1752): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1752): getCallState : 0
D/PhoneUtils( 1752): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1752): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1752): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1371): isHdmiPluggedIn :false
,D/KeyguardViewMediator( 1371): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  288): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/charger_monitor(  481): init target 500000
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  865): battery changed pluggedType: 2
I/ThermalEngine(  288): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 173550600385; DSPS: 5785167; Offset : -3004761516
,I/ThermalEngine(  288): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:30000 mC
,I/ClearcutLoggerApiImpl( 1733): disconnect managed GoogleApiClient
,D/PowerManagerServiceEx(  865): acquireWakeLockInternal: lock=847068853, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=865
,V/AlarmManager(  865): ELAPSED_WAKEUP set : Alarm{3415a4f8 type 2 when 185360 com.google.android.gms} when 185360
D/PowerManagerServiceEx(  865): releaseWakeLockInternal: lock=847068853 [*alarm*], flags=0x0
,D/charger_monitor(  481): init target 500000
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 289, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  865): battery changed pluggedType: 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 187784308046; DSPS: 6251565; Offset : -3004391181
,I/ThermalEngine(  288): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  865): ELAPSED_WAKEUP set : Alarm{154afdd1 type 2 when 190399 com.google.android.gms} when 190399
,I/ThermalEngine(  288): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 206539238299; DSPS: 6866122; Offset : -3004252188
,I/ThermalEngine(  288): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 219677028919; DSPS: 7296623; Offset : -3004309521
,I/ThermalEngine(  288): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,V/AlarmManager(  865): ELAPSED_WAKEUP set : Alarm{ae9f036 type 2 when 189697 android} when 189697
,V/AlarmManager(  865): ELAPSED_WAKEUP set : Alarm{2c8feb37 type 2 when 220406 com.google.android.gms} when 220406
D/libc-netbsd(  865): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  865): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  865): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  865): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  269): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  865): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/VacuumService( 1733): Vacuum at: now=1457574426161 tag=VacuumService
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 235170186371; DSPS: 7804305; Offset : -3004378000
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  481): init target 500000
D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  865): battery changed pluggedType: 2
V/AlarmManager(  865): ELAPSED_WAKEUP set : Alarm{335cd9c2 type 2 when 247866 com.google.android.gms} when 247866
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  269): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  865): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 248301940210; DSPS: 8234607; Offset : -3004400079
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 261441492342; DSPS: 8665174; Offset : -3004708131
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 274584383962; DSPS: 9095832; Offset : -3004457572
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 289597359918; DSPS: 9587774; Offset : -3004358004
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/charger_monitor(  481): init target 500000
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  865): battery changed pluggedType: 2
I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 304599638668; DSPS: 10079373; Offset : -3004489959
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  481): init target 500000
D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  865): battery changed pluggedType: 2
I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 327103765249; DSPS: 10816794; Offset : -3004666618
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/LocationManagerService(  865): remove 288cf908
D/LocationManagerService(  865): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  865): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  865): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  865): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  865): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 349608801513; DSPS: 11554231; Offset : -3004423541
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  481): init target 500000
D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  865): battery changed pluggedType: 2
I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 369611606743; DSPS: 12209681; Offset : -3004362810
,I/ThermalEngine(  288): Sensor:pa_therm0:29000 mC
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  865): android: cancelAsUser(2) by android
,D/libc-netbsd( 5061): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5061): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5061): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5061): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  269): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  865): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 384613566763; DSPS: 12701270; Offset : -3004508710
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 404616003406; DSPS: 13356706; Offset : -3004391325
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 419618417271; DSPS: 13848304; Offset : -3004357883
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  481): init target 500000
D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
,D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  865): battery changed pluggedType: 2
I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 434620903734; DSPS: 14339908; Offset : -3004434794
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  865): acquireWakeLockInternal: lock=847068853, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=865
,V/AlarmManager(  865): ELAPSED_WAKEUP set : Alarm{33b5fd41 type 2 when 442057 com.google.android.gms} when 442057
D/PowerManagerServiceEx(  865): releaseWakeLockInternal: lock=847068853 [*alarm*], flags=0x0
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  269): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  865): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 452124911225; DSPS: 14913474; Offset : -3004274497
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 467127418907; DSPS: 15405085; Offset : -3004542011
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 482129681363; DSPS: 15896668; Offset : -3004204040
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  481): init target 500000
D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  865): battery changed pluggedType: 2
I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 495261822243; DSPS: 16326989; Offset : -3004417922
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 512935888666; DSPS: 16906136; Offset : -3004513598
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 532937934083; DSPS: 17561563; Offset : -3004514604
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  481): init target 500000
D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
,D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  865): battery changed pluggedType: 2
I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 552940567882; DSPS: 18216997; Offset : -3004136893
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 567011858989; DSPS: 18678089; Offset : -3004257257
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 580155115729; DSPS: 19108773; Offset : -3004434983
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 595479470763; DSPS: 19610923; Offset : -3004481855
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  481): init target 500000
D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  865): battery changed pluggedType: 2
I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 615481781790; DSPS: 20266348; Offset : -3004154498
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 628932014450; DSPS: 20707096; Offset : -3004483282
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 645352828898; DSPS: 21245165; Offset : -3004231605
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 659424660812; DSPS: 21706276; Offset : -3004388809
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  481): init target 500000
D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  865): battery changed pluggedType: 2
I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 674123285622; DSPS: 22187921; Offset : -3004402837
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  865): android: cancelAsUser(2) by android
,D/libc-netbsd( 5061): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5061): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5061): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5061): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  269): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  865): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 689125545911; DSPS: 22679515; Offset : -3004400823
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 709126894378; DSPS: 23334903; Offset : -3003906693
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 723199702619; DSPS: 23796057; Offset : -3004401934
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  481): init target 500000
D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 739454488082; DSPS: 24328694; Offset : -3004407730
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 756957445083; DSPS: 24902242; Offset : -3004746575
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 771500613630; DSPS: 25378779; Offset : -3004332948
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 786502990266; DSPS: 25870381; Offset : -3004460836
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  481): init target 500000
D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  865): battery changed pluggedType: 2
I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 801504949379; DSPS: 26361966; Offset : -3004485392
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/charger_monitor(  481): init target 500000
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 821506407417; DSPS: 27017381; Offset : -3004703607
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/PowerManagerServiceEx(  865): acquireWakeLockInternal: lock=847068853, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=865
,V/AlarmManager(  865): ELAPSED_WAKEUP set : Alarm{382fc86c type 2 when 830445 com.google.android.gms} when 830445
D/PowerManagerServiceEx(  865): releaseWakeLockInternal: lock=847068853 [*alarm*], flags=0x0
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  269): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  865): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 835577384717; DSPS: 27478446; Offset : -3004315678
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  481): init target 500000
D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 849964996276; DSPS: 27949901; Offset : -3004367040
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 869966768958; DSPS: 28605304; Offset : -3003906615
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 883574960590; DSPS: 29051229; Offset : -3004266007
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 903739757678; DSPS: 29711998; Offset : -3004538238
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  481): init target 500000
D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  865): battery changed pluggedType: 2
I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 918741622893; DSPS: 30203578; Offset : -3004506239
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 933743095135; DSPS: 30695134; Offset : -3004132657
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 948754620345; DSPS: 31187042; Offset : -3004448214
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 963757904613; DSPS: 31678672; Offset : -3004519005
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  481): init target 500000
D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 271
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 271, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  865): battery changed pluggedType: 2
I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  865): android: cancelAsUser(2) by android
,D/libc-netbsd( 5061): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5061): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5061): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5061): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  269): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  865): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 977847503414; DSPS: 32140356; Offset : -3004397795
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 991603068153; DSPS: 32591098; Offset : -3004387178
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 1006605358902; DSPS: 33082695; Offset : -3004446151
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 1026607470466; DSPS: 33738121; Offset : -3004348748
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  481): init target 500000
D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  865): battery changed pluggedType: 2
I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 1039739602035; DSPS: 34168436; Offset : -3004388810
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 1056001911159; DSPS: 34701317; Offset : -3004317157
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 1076004139741; DSPS: 35356751; Offset : -3004346901
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  481): init target 500000
D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 1091006503472; DSPS: 35848351; Offset : -3004426607
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 1104300899723; DSPS: 36283980; Offset : -3004370211
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 1120557936206; DSPS: 36816687; Offset : -3004261452
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 1140560683839; DSPS: 37472144; Offset : -3004473972
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  481): init target 500000
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 1153692437821; DSPS: 37902442; Offset : -3004372796
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 1166822902502; DSPS: 38332699; Offset : -3004309752
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 1182305520614; DSPS: 38840044; Offset : -3004632312
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 1196226889101; DSPS: 39296206; Offset : -3004223379
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  481): init target 500000
D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 1209995318406; DSPS: 39747377; Offset : -3004440234
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 269
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 269
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 269, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  865): battery changed pluggedType: 2
I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/UsageStatsService(  865): User[0] Flushing usage stats to disk
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 1225006564189; DSPS: 40239264; Offset : -3004394403
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 1240008777424; DSPS: 40730844; Offset : -3004012146
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 1254081723950; DSPS: 41191999; Offset : -3004399203
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 1269083478782; DSPS: 41683588; Offset : -3004750240
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  481): init target 500000
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  865): android: cancelAsUser(2) by android
,D/libc-netbsd( 5061): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5061): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5061): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5061): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  269): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  269): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  269): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  269): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  269): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  865): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 1291587244544; DSPS: 42420978; Offset : -3004341490
D/AndroidRuntime( 6299): 
D/AndroidRuntime( 6299): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6299): CheckJNI is OFF
D/AndroidRuntime( 6299): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  865): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  865): Killing 4640:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  865): WIN DEATH: Window{35087b70 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  865): Focus left window: Window{35087b70 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  865): Window went away: Window{35087b70 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  865): Skipping PackageSetting{11e35d68 com.example.hello/10317} due to missing metadata
I/ActivityManager(  865):   Force finishing activity ActivityRecord{3b126502 u0 com.test.thalitest/.MainActivity t224}
V/ActivityManager(  865): Display changed displayId=0
D/DSDPConnection( 1752): Display #0 changed.
W/ActivityManager(  865): Spurious death for ProcessRecord{37573021 4640:com.test.thalitest/u0a316}, curProc for 4640: null
I/ActivityManager(  865): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  865):   Force finishing activity ActivityRecord{3b126502 u0 com.test.thalitest/.MainActivity t224 f}
W/ActivityManager(  865): Duplicate finish request for ActivityRecord{3b126502 u0 com.test.thalitest/.MainActivity t224 f}
I/[LGHome]EVENT( 1878): [Launcher.java:5203:onStart()]onStart
D/KeyguardModel( 1371): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
W/GeofencerStateMachine( 1733): Ignoring removeGeofence because network location is disabled.
I/[LGHome]EVENT( 1878): [Launcher.java:776:onResume()]onResume
I/QCNEJ   ( 1840): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/InputReader(  865): Reconfiguring input devices.  changes=0x00000010
W/System.err( 3476): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3476): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3476): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3476): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3476): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3476): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3476): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3476): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3476): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3476): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3476): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3476): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/ActivityManager(  865): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6327 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/art     ( 1943): Explicit concurrent mark sweep GC freed 18097(1371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 12MB/20MB, paused 3.118ms total 117.643ms
I/ActivityManager(  865): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=6337 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1878): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/[LGHome]LGActivityUtil( 1878): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[SystemUI]QSlideListController( 1371): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 1878): [Launcher.java:929:onResume()]onResume end
I/Activity( 1878): Activity.onPostResume() called 
I/art     (  865): Explicit concurrent mark sweep GC freed 34579(2MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 22MB/33MB, paused 6.218ms total 219.221ms
I/art     (  865): WaitForGcToComplete blocked for 192.466ms for cause Explicit
I/[LGHome]EVENT( 1878): [Launcher.java:986:onPause()]onPause
W/[LGHome]LGWallpaperInfo( 1878): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1878): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
W/ResourcesManager( 6327): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6327): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6327): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/WindowManager(  865): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
I/SystemUI[Framework](  865): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  865): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  865): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  865): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  865): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@20ca6dff,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  865): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher(  865): Focus entered window: Window{1f4ee12f u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1371): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1371): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/[SystemUI]NavigationThemeResource( 1371): notify navigation bar color(0x0)
I/[SystemUI]NavigationThemeResource( 1371): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1371):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1371): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
D/administrator(  865): Handling package changes for user 0
I/[LGHome]EVENT( 1878): [Launcher.java:5214:onStop()]onStop
I/[LGHome]EVENT( 1878): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1878): [setNavigationBarColor] color=0x 0
I/LockScreenSettings( 6337): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
D/KeyguardModel( 1371): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1371): createShortcutInfo...
D/KeyguardModel( 1371): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1371): createShortcutInfo...
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1371): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1371): createShortcutInfo...
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1371): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1371): createShortcutInfo...
W/InputMethodManagerService(  865): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1371): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1371): createShortcutInfo...
W/InputMethodManagerService(  865): Got RemoteException sending setActive(false) notification to pid 4640 uid 10316
D/KeyguardModel( 1371): handleShortcutListChanged...
D/KeyguardModel( 1371): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1371): createShortcutInfo...
D/KeyguardModel( 1371): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1371): createShortcutInfo...
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1371): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1371): createShortcutInfo...
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1371): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1371): createShortcutInfo...
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1371): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1371): createShortcutInfo...
I/ActivityManager(  865): Killing 5508:com.google.android.gm/u0a53 (adj 15): empty #11
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/NotificationService(  865): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  865): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  865): Receieved: android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
D/KeyguardModel( 1371): handleShortcutListChanged...
W/libprocessgroup(  865): failed to open /acct/uid_10053/pid_5508/cgroup.procs: No such file or directory
D/TaskPersister(  865): removeObsoleteFile: deleting file=224_task.xml
I/Timeline(  865): Timeline: Activity_windows_visible id: ActivityRecord{3ce714ee u0 com.lge.launcher2/.Launcher t223} time:1294526
W/IInputConnectionWrapper( 1878): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1615): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1878): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1878): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/art     (  865): Explicit concurrent mark sweep GC freed 8066(447KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 4.994ms total 331.795ms
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
I/LGEmail ( 6327): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
D/LGEmail ( 6327): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
D/LCardEmulationManager( 1787): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1787): getDefaultRoute
D/AndroidRuntime( 6299): Shutting down VM
W/ResourcesManager(  865): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
W/ResourceType(  865): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/PackageChangeReceiver( 6327): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
E/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  865): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6375 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  865): Killing 5260:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
W/IInputConnectionWrapper( 1878): getTextAfterCursor on inactive InputConnection
I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/System.err( 5238): android.os.DeadObjectException
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
W/System.err( 5238): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5238): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5238): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5238): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5238): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5238): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5238): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5238): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5238): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5238): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5238): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5238): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5238): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5238): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5238): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5238): android.os.DeadObjectException
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
W/System.err( 5238): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5238): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5238): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5238): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5238): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5238): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5238): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5238): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5238): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5238): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5238): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5238): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5238): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5238): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5238): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/libprocessgroup(  865): failed to open /acct/uid_10089/pid_5260/cgroup.procs: No such file or directory
W/ActivityManager(  865): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/AppUp4:AppBoxCP( 6375): onCreate
W/AppUp4:DB( 6375):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6375):  setFingerPrint start
I/AppUp4:DB( 6375):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/ActivityManager(  865): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6395 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/AppUp4:DB( 6375):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6375):  SDK version = 0
I/AppUp4:DB( 6375):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6375): AppBoxApplication onCreate()
I/Timeline( 1878): Timeline: Activity_idle id: android.os.BinderProxy@3b58f5b6 time:1295062
D/AppUp4:PreloadHelper( 6375): added Exclude : com.test.thalitest
D/UEI.SmartControl( 6395): Quickset Services start...
I/UEI.SmartControl( 6395): Manufacture = LGE
D/UEI.SmartControl( 6395): File observer start...
E/UEI.SmartControl( 6395): IR Port is disabled: false
D/UEI.SmartControl( 6395): Starting file observer...
D/UEI.SmartControl( 6395): Extracting JNI libs...
D/UEI.SmartControl( 6395): --- this system supports 32-bit or 64-bit only
I/art     ( 1878): Explicit concurrent mark sweep GC freed 26652(1460KB) AllocSpace objects, 16(2MB) LOS objects, 40% free, 15MB/25MB, paused 2.560ms total 63.904ms
I/ActivityManager(  865): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6413 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  865): Killing 5626:com.android.calendar/u0a13 (adj 15): empty #11
I/ThermalEngine(  288): Sensor:pa_therm0:27000 mC
I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 23.688ms
D/UEI.SmartControl( 6395): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6395): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6395): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 20.812ms
E/UEI.SmartControl( 6395): unzip: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.lite/files/libqs_jni.so: open failed: EROFS (Read-only file system)
I/UEI.SmartControl( 6395): --- Selecting new region: 2
I/UEI.SmartControl( 6395): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6395): Platform has CIR...
D/UEI.SmartControl( 6395): NO CIR support, need to check package...
I/UEI.SmartControl( 6395): Model: LG-D722 uses JNI
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 21.117ms
D/UEI.SmartControl( 6395): QS Service created
W/libprocessgroup(  865): failed to open /acct/uid_10013/pid_5626/cgroup.procs: No such file or directory

```
