#### Test 5841644866d9c0e_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/NotificationManager( 5161): com.google.android.music: cancel(1061) by com.google.android.music
D/ToneMappingReceiver( 5064): Enter doAlarmRingToneUriMapping()
D/ToneMappingReceiver( 5064): do ALARM RingToneUriMapping() -> first find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/CommonUtil( 5064): Enter getMatchedBackupTone() enter URI value is On, parentInfo : ALARM
D/CommonUtil( 5064): getFinededDefaultTone() -> backup ringtone value : null
D/CommonUtil( 5064): Exit getMatchedBackupTone() value is null
D/ToneMappingReceiver( 5064): do ALARM RingToneUriMapping() -> second find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/ToneMappingReceiver( 5064): Enter doAlarmRingToneUriMapping(), return value is 0
D/ToneMappingReceiver( 5064): Alarm Success count is 0
D/ToneMappingReceiver( 5064): Timer Success count is 0
--------- beginning of system
I/ActivityManager(  962): Killing 4818:com.google.android.talk/u0a61 (adj 15): empty #11
I/MediaScannerReceiver( 3790): Calendar.onReceive: a=android.intent.action.MEDIA_SCANNER_FINISHED Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///storage/emulated/0 flg=0x10 cmp=com.android.calendar/.alerts.MediaScannerReceiver }, mData=file:///storage/emulated/0
W/libprocessgroup(  962): failed to open /acct/uid_10061/pid_4818/cgroup.procs: No such file or directory
E/MediaScanReceiver( 5144): media scanning finished
I/com.lge.bnr.receiver.MediaScanReceiver( 5144): android.intent.action.MEDIA_SCANNER_FINISHED
I/InitNotificationRingtoneService( 3790): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 3790): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
I/AlertUtils( 3790): [getCalendarNotiSoundURIFromCursor] getCount()= 21
I/AlertUtils( 3790): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
,D/UEI.SmartControl( 4889): Internal timer expired: 1
I/AlertUtils( 3790): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 3790): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 3790): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 3790): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 3790): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 3790): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 3790): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 3790): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/ActivityManager(  962): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5221 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/UEI.SmartControl( 4889): Service.onUnbind: IControl
D/UEI.SmartControl( 4889): Service.onDestroy
D/UEI.SmartControl( 4889): Shutdown IRRCPlayer... 
W/irrc_jni( 4889): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 4889): ~IrrcClient ++ 
D/irrcClient( 4889): ~IrrcClient -- 
W/irrc_jni( 4889): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 4889): Blaster closed
D/UEI.SmartControl( 4889): Blaster closed
D/UEI.SmartControl( 4889): Shut down QS...
D/UEI.SmartControl( 4889): Stopped file observer...
I/UEI.SmartControl( 4889): QS lib stop result = true
D/UEI.SmartControl( 4889): QS shutdown complete
W/ResourcesManager( 5221): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/art     ( 3211): Explicit concurrent mark sweep GC freed 16405(867KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/10MB, paused 499us total 58.269ms
I/AlertUtils( 3790): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 3790): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 3790): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 3790): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 3790): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 3790): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3790): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/AlertUtils( 3790): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 3790): End InitializeAlertRingtoneService.onHandleIntent
I/art     ( 5161): CheckpointMarkThreadRoots callback created = 0xb042d3b0
D/CalendarProvider2( 5221): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@385f69ba
D/CalendarProvider2( 5221): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 5221): Created com.android.providers.calendar.CalendarAlarmManager@e1d1847(com.android.providers.calendar.CalendarProvider2@385f69ba)
D/CalendarProviderBroadcastReceiver( 5221): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 5221): [IntentService] WakeLock acquire, start IntentSerivce
I/MediaStoreImporter( 5161): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
D/CalendarProvider2( 5221): CalendarProviderIntentService.onCreate()
I/art     ( 5161): CheckpointMarkThreadRoots callback created = 0xb042d370
D/CalendarProvider2( 5221): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 5221): [getOrCreateCalendarAlarmManager]
I/ActivityManager(  962): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=5244 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
D/CalendarProvider2( 5221): [IntentService] Release Lock
D/CalendarProvider2( 5221): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  962): Killing 4859:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
W/libprocessgroup(  962): failed to open /acct/uid_10079/pid_4859/cgroup.procs: No such file or directory
D/AndroidRuntime( 5234): 
D/AndroidRuntime( 5234): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
W/ResourcesManager( 5244): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5244): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/AndroidRuntime( 5234): CheckJNI is OFF
W/ResourcesManager( 5244): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/LGEmail ( 5244): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 5244): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
D/AndroidRuntime( 5234): Calling main entry com.android.commands.am.Am
I/ActivityManager(  962): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/PackageChangeReceiver( 5244): intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
D/ActivityManager(  962): setTaskToReturnTo : TaskRecord{3cfce1bf #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  962): setTaskToReturnTo : TaskRecord{3cfce1bf #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  962): AppWindowTokenEx init.. 
D/ContextHelper(  962): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
I/PhoneWindow(  962): [generateLayout] setColorNavigationBar => color=0x ff000001
D/InputDispatcher(  962): Focus left window: Window{409ee66 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5234): Shutting down VM
I/[LGHome]EVENT( 1879): [Launcher.java:986:onPause()]onPause
D/PhoneWindowEx(  962): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow(  962): [setNavigationBarColor2] color=0x fff5f5f5
D/SplitWindow(  962): check instance of lgWin Window{53f49b7 u0 Starting com.test.thalitest}
I/ActivityManager(  962): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5280 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  962): Killing 4889:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/libprocessgroup(  962): failed to open /acct/uid_10089/pid_4889/cgroup.procs: No such file or directory
I/ActivityManager(  962): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5297 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1879): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/Adreno-EGL( 4907): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4907): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 4907): Build Date: 03/02/15 Mon
I/Adreno-EGL( 4907): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 4907): Remote Branch: 
I/Adreno-EGL( 4907): Local Patches: 
I/Adreno-EGL( 4907): Reconstruct Branch: 
I/WindowStateAnimator(  962): Starting window displayed
D/WindowManager(  962): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
I/SystemUI[Framework](  962): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
I/[SystemUI]NavigationThemeResource( 1375): notify navigation bar color(0xfff5f5f5)
W/PhoneWindowManagerEx(  962): Call!!!getLGSystemUiVisibility. =0x0
I/[SystemUI]NavigationThemeResource( 1375): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1375):  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
I/[SystemUI]NavigationThemeResource( 1375): , Keyguard show=false, IME shown=false, Panel expanded=false
D/StatusBarManagerServiceEx(  962): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  962): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  962): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1f63a068,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  962): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[LGHome]EVENT( 1879): [Launcher.java:5214:onStop()]onStop
W/ActivityThread( 1879): Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 1879): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 1879): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3407)
W/ActivityThread( 1879): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3496)
W/ActivityThread( 1879): 	at android.app.ActivityThread.access$1100(ActivityThread.java:155)
W/ActivityThread( 1879): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1352)
W/ActivityThread( 1879): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ActivityThread( 1879): 	at android.os.Looper.loop(Looper.java:135)
W/ActivityThread( 1879): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/ActivityThread( 1879): 	at java.lang.reflect.Method.invoke(Native Method)
W/ActivityThread( 1879): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ActivityThread( 1879): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/ActivityThread( 1879): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/Adreno-EGL( 4907): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4907): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 4907): Build Date: 03/02/15 Mon
I/Adreno-EGL( 4907): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 4907): Remote Branch: 
I/Adreno-EGL( 4907): Local Patches: 
I/Adreno-EGL( 4907): Reconstruct Branch: 
I/HotwordDetector( 1941): Closing mic
I/MicrophoneInputStream( 1941): mic_close com.google.android.apps.gsa.speech.audio.u@20685392
V/AudioRecord( 1941): stop()
D/AudioRecord( 1941): AudioRecord->stop()
V/AudioFlinger(  282): RecordHandle::stop()
V/AudioFlinger(  282): RecordThread::stop
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
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb384a000
D/audio_hw_primary(  282): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
I/ActivityManager(  962): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5322 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
V/audio_hw_primary(  282): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  282): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  282): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  282): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  282): disable_audio_route: exit
E/audio_hw_primary(  282): disable_snd_device: enter 144
D/hardware_info(  282): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  282): disable_snd_device: snd_device(144: lg-vr-handset-mic)
I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 308us total 22.646ms
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
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb384a000
V/AudioFlinger(  282): RecordThread: loop stopping
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
D/ContextHelper( 5297): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
I/ActivityManager(  962): Activity reported stop, but no longer stopping: ActivityRecord{19b17f5 u0 com.lge.launcher2/.Launcher t221}
I/ActivityManager(  962): Killing 4970:com.android.chrome/u0a48 (adj 15): empty #11
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 295us total 21.897ms
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 355us total 23.032ms
V/AudioRecord( 1941): stop()
V/AudioRecord( 1941): stop()
V/AudioRecord( 1941): stop()
V/AudioFlinger(  282): releasing 16 from 1941 for -1
V/AudioFlinger(  282):  decremented refcount to 0
V/AudioFlinger(  282): purging stale effects
V/AudioFlinger(  282): RecordHandle::stop()
V/AudioFlinger(  282): RecordThread::stop
V/AudioPolicyManager(  282): releaseInput() 17
V/AudioPolicyManager(  282): closeInput(17)
V/AudioFlinger(  282): closeInput() 17
V/AudioSystem(  282): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  962): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): ThreadBase::exit
V/AudioSystem( 1375): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): RecordThread: loop starting
V/AudioFlinger(  282): RecordThread 0xb384a000 exiting
V/AudioSystem( 1752): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  282): adev_close_input_stream: enter:stream_handle(0xb546dd40)
D/audio_hw_primary(  282): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioSystem( 2096): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  282): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  282): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  282): releaseInput() exit
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing update audio port list
V/AudioSystem( 1941): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioSystem( 1990): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3186): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  282): removeClient_l() pid 1941, calling pid 282
I/HotwordRecognitionRnr( 1941): Stopping hotword detection.
W/libprocessgroup(  962): failed to open /acct/uid_10048/pid_4970/cgroup.procs: No such file or directory
I/HotwordRecognitionRnr( 1941): Hotword detection finished
I/CheckinRequestBuilder( 4209): Classify the device as Phone.
I/AppUp4:AppBoxCP( 5322): onCreate
W/AppUp4:DB( 5322):  [AppBoxDatabaseHelper] construct
I/WebViewFactory( 5297): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/AppUp4:DB( 5322):  setFingerPrint start
I/AppUp4:DB( 5322):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 5322):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5322):  SDK version = 0
I/AppUp4:DB( 5322):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 5322): AppBoxApplication onCreate()
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
D/libc-netbsd( 4209): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4209): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4209): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4209): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 4209): propertyValue:false
I/LibraryLoader( 5297): Time to load native libraries: 5 ms (timestamps 8678-8683)
I/LibraryLoader( 5297): Expected native library version number "",actual native library version number ""
D/AppUp4:PreloadHelper( 5322): removed from Exclude : com.test.thalitest : 1
I/ActivityManager(  962): Killing 4999:com.google.android.apps.plus/u0a86 (adj 15): empty #11
V/WebViewChromiumFactoryProvider( 5297): Binding Chromium to main looper Looper (main, tid 1) {2db32874}
I/LibraryLoader( 5297): Expected native library version number "",actual native library version number ""
I/chromium( 5297): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
D/libc-netbsd( 4209): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4209): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/BrowserStartupController( 5297): Initializing chromium process, singleProcess=true
W/art     ( 5297): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5297): ApplicationContext is null in ApplicationStatus
W/libprocessgroup(  962): failed to open /acct/uid_10086/pid_4999/cgroup.procs: No such file or directory
,W/chromium( 5297): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5297): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5297): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5297): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5297): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5297): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5297): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5297): Remote Branch: 
I/Adreno-EGL( 5297): Local Patches: 
I/Adreno-EGL( 5297): Reconstruct Branch: 
D/libc-netbsd( 4209): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4209): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4209): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4209): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 4209): Sending checkin request (9798 bytes)
,I/ActivityManager(  962): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5351 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
V/AudioPolicyService(  282): registerClient() client 0xb57ec140, uid 10316
,D/BluetoothManagerService(  962): Message: 20
D/BluetoothManagerService(  962): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2d540cc0:true
,D/BluetoothAdapterService(151581155)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@214943d1
W/ResourcesManager( 5351): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5351): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5351): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/art     ( 5297): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5297): onDetachedFromWindow called when already detached. Ignoring
,I/PhoneWindow( 5297): [generateLayout] setColorNavigationBar => color=0x ff000001
D/PhoneWindowEx( 5297): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow( 5297): [setNavigationBarColor2] color=0x fff5f5f5
I/AppConfig( 5351): Total System Memory = 906309632
,I/GalleryUtils( 5351): Application Heap = 96 MB
D/SystemWebViewEngine( 5297): CordovaWebView is running on device made by: LGE
I/AppConfig( 5351): App Tier : NOT_DEF
W/art     ( 5297): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5297): Attempt to remove local handle scope entry from IRT, ignoring
D/SystemHelper( 5351): region [EU], country [EU], operator [OPEN], sub-operator []
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  962): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5391 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/Activity( 5297): Activity.onPostResume() called 
,D/OpenGLRenderer( 5297): Render dirty regions requested: true
I/OpenGLRenderer( 5297): Initialized EGL, version 1.4
D/OpenGLRenderer( 5297): Enabling debug mode 0
,D/Atlas   ( 5297): Validating map...
,D/SplitWindow(  962): check instance of lgWin Window{1ce425f0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5297): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  962): Killing 5092:com.android.settings/1000 (adj 15): empty #11
I/CheckinRequestBuilder( 4209): Checkin reason type: 8 attempt count: 1
,W/libprocessgroup(  962): failed to open /acct/uid_1000/pid_5092/cgroup.procs: No such file or directory
,E/ActivityThread( 4209): Failed to find provider info for com.google.android.wearable.settings
W/ResourcesManager( 5391): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5391): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5391): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 5391): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5391): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/InputDispatcher(  962): Focus entered window: Window{1ce425f0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/InputMethodManagerService(  962): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  962): Displayed com.test.thalitest/.MainActivity: +1s201ms
I/Timeline(  962): Timeline: Activity_windows_visible id: ActivityRecord{1d2e808c u0 com.test.thalitest/.MainActivity t222} time:79425
I/Timeline( 5297): Timeline: Activity_idle id: android.os.BinderProxy@24265e0e time:79441
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BindingManager( 5297): Cannot call determinedVisibility() - never saw a connection for the pid: 5297
,I/CheckinRequestBuilder( 4209): Classify the device as Phone.
,I/CheckinTask( 4209): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/SystemConfig( 5391): BUILD Country: EU
I/SystemConfig( 5391): BUILD Operator: OPEN
I/CheckinService( 4209): Checking schedule, now: 1455019768026 next: 1455547017009
I/CheckinService( 4209): active receiver: disabled
,D/CheckinService( 4209): Recording last checkin time for package unspecified as 1455019768061
I/ActivityManager(  962): Killing 5064:com.lge.clock/u0a10 (adj 15): empty #11
,D/JsMessageQueue( 5297): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  962): Killing 5115:com.lge.sync/1000 (adj 15): empty #12
,W/libprocessgroup(  962): failed to open /acct/uid_10010/pid_5064/cgroup.procs: No such file or directory
,W/libprocessgroup(  962): failed to open /acct/uid_1000/pid_5115/cgroup.procs: No such file or directory
I/ActivityManager(  962): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5426 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  962): Killing 5144:com.lge.bnr/1000 (adj 15): empty #11
,W/libprocessgroup(  962): failed to open /acct/uid_1000/pid_5144/cgroup.procs: No such file or directory
,I/SystemConfig( 5391): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5391): existFile = false
I/SystemConfig( 5391): canReadFile = false
I/SystemConfig( 5391): systemFeature RCS result false
D/SystemConfig( 5391): refreshRcsSupport() :false
I/LockScreenSettings( 5426): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/LockScreenSettings( 5426): New app installed broadcast received ..
,I/LockScreenSettings( 5426): Number of installed packages  1
,I/ActivityManager(  962): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=5451 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  962): Killing 5161:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  962): failed to open /acct/uid_10081/pid_5161/cgroup.procs: No such file or directory
,D/EulaProviderUpdateObserver( 5451): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 5451): uri : package:com.test.thalitest
,D/jxcore_app_log( 5297): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1618697600
,I/ActivityManager(  962): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=5471 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  962): Killing 5221:com.android.providers.calendar/u0a14 (adj 15): empty #11
,I/chromium( 5297): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/AlertService( 3790): Beginning updateAlertNotification
,W/libprocessgroup(  962): failed to open /acct/uid_10014/pid_5221/cgroup.procs: No such file or directory
V/AlarmManager(  962): ELAPSED_WAKEUP set : Alarm{77c0cd9 type 2 when 80278 android} when 80278
,I/art     ( 5297): CheckpointMarkThreadRoots callback created = 0x9f98e630
,I/ActivityManager(  962): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5488 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 5297): CheckpointMarkThreadRoots callback created = 0x9f98e600
,W/ResourcesManager( 5488): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/[BNRAppListMgrReceiver]( 5471): android.intent.action.PACKAGE_ADDED : com.test.thalitest
D/CalendarProvider2( 5488): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@385f69ba
,D/CalendarProvider2( 5488): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 5488): Created com.android.providers.calendar.CalendarAlarmManager@e1d1847(com.android.providers.calendar.CalendarProvider2@385f69ba)
D/AlertService( 3790): No fired or scheduled alerts
,I/NotificationManager( 3790): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 3790): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 3790): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 3790): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 3790): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 3790): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 3790): com.android.calendar: cancel(6) by com.android.calendar
,I/NotificationManager( 3790): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 3790): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 3790): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 3790): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 3790): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 3790): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 3790): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 3790): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 3790): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 3790): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 3790): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 3790): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 3790): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 3790): com.android.calendar: cancel(20) by com.android.calendar
W/MainApplication( 5471): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,I/ActivityManager(  962): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5509 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/ActivityManager(  962): Killing 5244:com.lge.email/u0a21 (adj 15): empty #11
D/AlertService( 3790): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
I/ActivityManager(  962): Killing 5280:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,W/libprocessgroup(  962): failed to open /acct/uid_10021/pid_5244/cgroup.procs: No such file or directory
,W/libprocessgroup(  962): failed to open /acct/uid_10009/pid_5280/cgroup.procs: No such file or directory
D/AlarmScheduler( 3790): No events found starting within 1 week.
,I/art     (  962): Explicit concurrent mark sweep GC freed 22424(1214KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 2.025ms total 199.195ms
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/GAv4    ( 5509): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5509):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5509):   adb logcat -s GAv4
,W/GAv4    ( 5509): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5509): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5509): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 5509): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
,I/ActivityManager(  962): Process com.google.android.gms (pid 4209) has died
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5509): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
W/jxcore-log( 5297): Initializing JXcore engine
,W/jxcore-log( 5297): JXcore engine is ready
W/ResourcesManager( 5509): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5509): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  962): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5554 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     ( 5509): CheckpointMarkThreadRoots callback created = 0xb0511a70
,V/JNIHelp ( 5509): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ResourcesManager( 5554): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     ( 5509): CheckpointMarkThreadRoots callback created = 0xb0511a50
W/Thread-622( 5470): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6664]" dev="sockfs" ino=6664 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-622( 5470): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-622( 5470): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6007]" dev="sockfs" ino=6007 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-622( 5470): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-622( 5470): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-622( 5470): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[26238]" dev="sockfs" ino=26238 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 5297): Starting JXcore engine
,W/System  ( 5509): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5509): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/jxcore-log( 5297): Platform android
W/jxcore-log( 5297): 
W/jxcore-log( 5297): Process ARCH arm
W/jxcore-log( 5297): 
,I/ActivityManager(  962): Killing 4907:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  962): failed to open /acct/uid_10006/pid_4907/cgroup.procs: No such file or directory
,I/ActivityManager(  962): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5589 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1941): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/UpdateIcingCorporaServi( 1941): UpdateCorporaTask done [took 187 ms] updated apps [took 186 ms] 
,I/jxcore-log( 5297): JXcore Cordova bridge is ready!
I/jxcore-log( 5297): 
,W/jxcore-log( 5297): JXcore engine is started
I/ActivityManager(  962): Process com.android.contacts (pid 5391) has died
,I/ActivityManager(  962): Process com.android.gallery3d (pid 5351) has died
,I/jxcore-log( 5297): Toggling radios to true
I/jxcore-log( 5297): 
D/BluetoothAdapter( 5297): enable(): BT is already enabled..!
,D/Finsky  ( 5589): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
D/WifiServiceImplEx(  962): setWifiEnabled: true pid=5297, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/WifiService(  962): setWifiEnabled: true pid=5297, uid=10316
D/WifiServiceImplEx(  962): disconnect pid=5297, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  962): reconnect pid=5297, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 5297): Radios toggled
I/jxcore-log( 5297): 
I/jxcore-log( 5297): My device name is: LGE-LG-D722
I/jxcore-log( 5297): 
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2751): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2751): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine(  962): WifiStateMachine: Leaving Connected state
D/WfdsMonitor( 1805): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiConfigStore(  962): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/LGWifiP2pService(  962): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  962): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  278): Clearing all IP addresses on wlan0
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1733): Read error: ssl=0xb045f800: I/O error during system call, Connection timed out
,D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 10
D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 7
D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  962): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
I/QCNEJ   ( 1829): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
V/NativeCrypto( 1733): SSL shutdown failed: ssl=0xb045f800: I/O error during system call, Broken pipe
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1829): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 13:09:31.771 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1829): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/ConnectivityService(  962): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/WifiHS20(  962): hidePasspointNotification off =false
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
,E/WifiStateMachine(  962): Start Disconnecting Watchdog 1
D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/WifiHS20(  962): hidePasspointNotification off =false
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/wpa_supplicant( 2751): wlan0: CTRL-EVENT-SCAN-STARTED 
I/QCNEJ   ( 1829): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1829): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 13:09:31.788 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1829): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/LGWifiP2pService(  962): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
,D/ConnectivityService(  962): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  962): ValidatedState{ when=-5ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  962): DefaultState{ when=-12ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  962): Forcing reevaluation
,D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
D/CommandListener(  278): Clearing all IP addresses on wlan0
D/ConnectivityService(  962): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  962): disableDataServiceNotify
I/QCNEJ   ( 1829): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1829): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 13:09:31.87 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1829): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiHS20(  962): hidePasspointNotification off =false
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/DSQN    (  962): stop dsqn bin
,I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/WifiNetworkAgent(  962): NetworkAgent: NetworkAgent channel lost
,D/ConnectivityService(  962): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  962):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  962):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  962): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  962): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  962): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  962): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  962): Disconnected - quitting
D/CSLegacyTypeTracker(  962): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  962): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityManager.CallbackHandler( 1375): CM callback handler got msg 524292
D/WifiHS20(  962): hidePasspointNotification off =false
D/ConnectivityService(  962): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1829): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1829): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 13:09:31.899 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1829): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService(  962): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  962): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  962): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1829): |CORE| No family connected
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
V/NetworkPolicy(  962): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy(  962): [LG_RESTRICTED] !!!isConnected  type  :1
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
W/QCNEJ   ( 1829): |CORE| No family connected
I/QCNEJ   ( 1829): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/ConnectivityService(  962): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  962): MasterInitialState.processMessage what=3
D/ConnectivityService(  962): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  962): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService(  962): Removing idletimer
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/TelephonyNetworkFactory-1( 1752): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1752):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/DhcpStateMachine(  962): StoppedState
D/DhcpStateMachine(  962): StoppedState{ when=-125ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiServerServiceExt(  962): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  962): setSupplicantStateDISCONNECTED
I/QCNEJ   ( 1829): |CORE| sendDefaultNwMsg: default = -1
I/QCNEJ   ( 1829): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  962): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1829): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 13:09:31.92 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1829): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WIFI    (  962): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  962):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiServerServiceExt(  962): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  962): setSupplicantStateSCANNING
E/ConnectivityService(  962): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
W/ActivityManager(  962): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
,V/AlarmManager(  962): RTC_WAKEUP set : Alarm{1fcd0d81 type 0 when 1454933324778 com.android.providers.contacts} when 1454933324778
V/AlarmManager(  962): ELAPSED_WAKEUP set : Alarm{37323e26 type 2 when 60770 com.google.android.talk} when 60770
V/AlarmManager(  962): RTC_WAKEUP set : Alarm{10e67014 type 0 when 1455019771934 com.google.android.googlequicksearchbox} when 1455019771934
D/TelephonyIcons( 1375): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1375): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/TelephonyIcons( 1375): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1375): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/Finsky  ( 5589): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5589): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
W/Settings( 5589): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5589): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3211): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
I/NotificationManager( 5589): com.android.vending: cancel(1003285959) by com.android.vending
,V/DownloadManager( 3211): created cursor android.database.sqlite.SQLiteCursor@38dc866c on behalf of 5589
D/Ads     ( 5589): Skipping gmscore version check
,D/Finsky  ( 5589): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5589): [1] Libraries$2.run: Finished loading 1 libraries.
I/ActivityManager(  962): Start proc com.google.android.gms for service com.google.android.gms/.app.service.PackageBroadcastService: pid=5653 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/Finsky  ( 5589): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5589): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/Finsky  ( 5589): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
W/ResourcesManager( 5653): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5653): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5653): VM with version 2.1.0 has multidex support
I/MultiDex( 5653): install
,I/MultiDex( 5653): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 5653): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5653): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5653): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@90f4cff: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5653): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 5653): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5653): com.google.android.gms: cancel(39789) by com.google.android.gms
D/ChimeraCfgMgr( 5653): Reading stored module config
,D/PackageBroadcastService( 5653): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/ChimeraCfgMgr( 5653): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5653): Loading module APK com.google.android.play.games
,D/NativeLibraryUtils( 5653): Install completed successfully. count=14 extracted=0
,I/art     ( 5653): CheckpointMarkThreadRoots callback created = 0xb042d420
,I/art     ( 5653): CheckpointMarkThreadRoots callback created = 0xb042d400
,I/ActivityManager(  962): Process com.lge.appbox.client (pid 5322) has died
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2751): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/LocSvc_java(  962): onReceive
,I/QCNEJ   ( 1829): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1829): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 13:09:32.955 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1829): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1829): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt(  962): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  962): setSupplicantStateASSOCIATING
I/QCNEJ   ( 1829): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 13:09:32.963 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1829): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2751): wlan0: Associated with c0:ff:d4:d3:aa:48
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt(  962): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  962): setSupplicantStateASSOCIATED
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt(  962): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  962): setSupplicantStateFOUR_WAY_HANDSHAKE
,I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1829): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1829): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 13:09:33.004 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1829): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1829): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1829): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 13:09:33.005 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1829): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/wpa_supplicant( 2751): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2751): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
,I/WifiServiceExtension(  962): setVHTCapabilityType  : false
I/WifiServerServiceExt(  962): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  962): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  962): setSecurityType  : 2
,D/ChimeraCfgMgr( 5653): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5653): Module APK com.google.android.play.games already loaded
,I/QCNEJ   ( 1829): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1829): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 13:09:33.059 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1829): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1829): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1829): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 13:09:33.062 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1829): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
,D/ConnectivityService(  962): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/ConnectivityService(  962): Got NetworkAgent Messenger
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
D/ConnectivityService(  962): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  962): NetworkAgent connected
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
E/WifiConfigStore(  962): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
E/WifiConfigStore(  962): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 9
,D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  278): Setting iface cfg
D/DhcpStateMachine(  962): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  962): Start Dhcp Watchdog 2
D/DhcpStateMachine(  962): WaitBeforeStartState
D/WifiServerServiceExt(  962): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  962): setSupplicantStateGROUP_HANDSHAKE
D/ChimeraCfgMgr( 5653): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ConnectivityService(  962): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/AsyncTaskServiceImpl( 5653): Submit a task: k
I/PeopleDatabaseHelper( 5653): cleanUpNonGplusAccounts done.
,D/ChimeraCfgMgr( 5653): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 5653): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 5653): Processing package: com.test.thalitest
,D/GassUtils( 5653): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 5653): Found info for package com.test.thalitest in db.
,E/WifiStateMachine(  962): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  962): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  962): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService(  962): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3a11cd88 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3a11cd88 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  962): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
I/Icing   ( 5653): Storage manager: low false usage 1.75MB avail 2.38GB capacity 4.06GB
D/CommandListener(  278): Setting iface cfg
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/CommandListener(  278): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  962): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/DhcpStateMachine(  962): DHCP Start wake lock is acquired.
D/WifiServerServiceExt(  962): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  962): setSupplicantStateCOMPLETED
D/ConnectivityService(  962): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,D/LGWifiP2pService(  962): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  962): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  962): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/ConnectivityService(  962): ignoring duplicate network state non-change
D/ConnectivityService(  962): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  962): Adding iface wlan0 to network 101
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1829): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiHS20(  962): [PASSPOINT] passpointNotification: hs20AP list is checked
D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
I/QCNEJ   ( 1829): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 13:09:33.241 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1829): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1829): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
I/QCNEJ   ( 1829): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 13:09:33.243 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1829): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1829): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/WifiStateMachine(  962): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/QCNEJ   ( 1829): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 13:09:33.25 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1829): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/WifiHS20(  962): [PASSPOINT] passpointNotification: hs20AP list is checked
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
E/ConnectivityService(  962): Unexpected mtu value: 0, wlan0
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/ConnectivityService(  962): Adding Route [fe80::/64 -> :: wlan0] to network 101
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  962): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  278): netlink response contains error (File exists)
,I/QCNEJ   ( 1829): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  962): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/QCNEJ   ( 1829): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 13:09:33.26 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
D/ConnectivityService(  962): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  962): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
I/QCNEJ   ( 1829): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/ConnectivityService(  962): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/Nat464Xlat(  962): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  962): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  962): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  962): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  962):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUp,Bandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  962):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  962):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  962):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  962):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  962): currentScore = 0, newScore = 20
D/ConnectivityService(  962):    accepting network in place of null
D/ConnectivityService(  962): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  962): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  962): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  962): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WIFI    (  962): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  962):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = true, mWifiLevel = 2
D/TelephonyNetworkFactory-1( 1752): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1752):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
E/ConnectivityService(  962): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  962): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  962): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  962): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  962): [e] list.add(nai) empty : false size: 1
D/Tethering(  962): MasterInitialState.processMessage what=3
D/ConnectivityService(  962): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
W/QCNEJ   ( 1829): |CORE| No family connected
,I/QCNEJ   ( 1829): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1829): |CORE| sendDefaultNwMsg: default = 1
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  962): [LWD] Start DNSResolver start to wait
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
D/WearableService( 1733): callingUid 10006, callindPid: 1733
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/ConnectivityService(  962): validation of new default Network = false
D/ConnectivityService(  962): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  962): enableDataServiceNotify 
D/DSQN    (  962): start dsqn bin
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  962): [LWD] wait 500ms before dns check
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = true, mWifiLevel = 2
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/ConnectivityService(  962): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  962):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  962):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  962): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1375): CM callback handler got msg 524290
W/BaseAppContext( 5653): Using Auth Proxy for data requests.
V/NetworkPolicy(  962): [LG_RESTRICTED] checkMobilePolicy_type()
E/MDM     ( 1733): [142] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/DSQN    ( 5710): DSQN samuel.seo ver 141203
E/DSQN    ( 5710): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5710): created command queue thread
I/DSQN    ( 5710): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5710): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/TelephonyIcons( 1375): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1375): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/art     ( 5653): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5653): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,E/BaseAppContext( 5653): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,W/BaseAppContext( 5653): Using Auth Proxy for data requests.
D/DhcpStateMachine(  962): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper(  962): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  962): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,I/dhcpcd  ( 5720): version 5.5.6 starting
,E/dhcpcd  ( 5720): get_duid: Read-only file system
D/LocationInitializer( 5653): Restart initialization of location
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
I/dhcpcd  ( 5720): wlan0: rebinding lease of 192.168.1.134
,I/ActivityManager(  962): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5732 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 21.050ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 20.779ms
,W/BaseAppContext( 5653): Using Auth Proxy for data requests.
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 21.667ms
,W/BaseAppContext( 5653): Using Auth Proxy for data requests.
,W/BaseAppContext( 5653): Using Auth Proxy for data requests.
W/BaseAppContext( 5653): Using Auth Proxy for data requests.
,W/BaseAppContext( 5653): Using Auth Proxy for data requests.
,I/dhcpcd  ( 5720): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/dhcpcd  ( 5720): wlan0: leased 192.168.1.134 for 86400 seconds
,W/GCoreFlp( 1733): No location to return for getLastLocation()
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  962): [LWD] DNSResolver start dns
D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/FusedLocationProvider( 1733): location=null
D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  278): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/InitAlarmsService( 3790): Clearing and rescheduling alarms.
,W/IcingInternalCorpora( 5653): getNumBytesRead when not calculated.
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out(  962): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  962): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  962): Checking http://clients3.google.com/generate_204 on "NG700"
,D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/DSQN    ( 5710): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5710): restart monitoring
D/LGDataListener(  278): argv[0]=dsqncommand
D/LGDataListener(  278): argv[1]=wlan0
D/LGDataListener(  278): argv[2]=1
D/LGDataListener(  278): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 5710): dsqn report finish
,D/DSQN    (  962): DSQM DsqnNotification wlan0  1
D/DSQN    (  962): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  962): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 12:09:33 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455019773881], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455019773865]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  962): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  962): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  962): Validated
D/ConnectivityService(  962): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  962): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  962):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  962):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  962):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  962): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  962): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  962):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  962):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  962): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  962): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  962): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  962): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  962):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1375): CM callback handler got msg 524290
I/ActivityManager(  962): Process com.lge.lockscreensettings (pid 5426) has died
D/TelephonyNetworkFactory-1( 1752): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1752):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
E/lowmemorykiller(  243): Error writing /proc/5451/oom_score_adj; errno=22
D/CalendarProvider2( 5488): Scheduling check of next Alarm
,I/ActivityManager(  962): Process com.lge.eula (pid 5451) has died
,I/BackgroundMemoryTrimmer( 1941): Trimming objects from memory, since app is in the background.
,I/PhoneApp( 1752): onTrimMemory: 10
I/PhoneApp( 1752): trim memory
D/WifiDataContinuityService(  962): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
,I/WifiServerServiceExt(  962): set CMD_CAPTIVE_CHECK_COMPLETED
D/ChimeraCfgMgr( 5653): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5653): Module APK com.google.android.play.games already loaded
D/CalendarProvider2( 5488): SCHEDULE_ALARM_REMOVE
W/art     ( 5471): Suspending all threads took: 8.630ms
,D/TelephonyIcons( 1375): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1375): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,W/ActivityManager(  962): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  962): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  962): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  962): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  962): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  962): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  962): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  962): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  962): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  962): RunningState
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/ConnectivityService(  962): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/Gmail   ( 5732): getAccountsCursor
,I/Icing   ( 5653): updateResources: need to parse f{com.google.android.gms}
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 5732): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  962): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
I/QCNEJ   ( 1829): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1829): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 13:09:34.442 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/ConnectivityService(  962): identical MTU - not setting
D/Nat464Xlat(  962): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  962): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  962):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  962):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  962): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1375): CM callback handler got msg 524295
D/ConnectivityService(  962): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  962): enableDataServiceNotify 
D/DSQN    (  962): start dsqn bin
,D/DSQN    (  962): dsqn is running restart
W/ActivityManager(  962): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/DSQN    ( 5794): DSQN samuel.seo ver 141203
E/DSQN    ( 5794): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5794): created command queue thread
I/DSQN    ( 5794): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5794): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,E/Gmail   ( 5732): Error finding the version of the Email provider.....
E/Gmail   ( 5732): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5732): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5732): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5732): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5732): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5732): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5732): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5732): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5732): We do not support migrating this version of the Email provider.
I/Gmail   ( 5732): getAccountsCursor
W/ActivityManager(  962): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager(  962): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 5732): Observing account changes for notifications
I/art     (  962): Explicit concurrent mark sweep GC freed 65000(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 2.589ms total 180.280ms
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 5653): Background sticky concurrent mark sweep GC freed 11428(867KB) AllocSpace objects, 7(112KB) LOS objects, 7% free, 13MB/14MB, paused 19.001ms total 82.543ms
,W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
,V/DownloadManager( 3211): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3211): created cursor android.database.sqlite.SQLiteCursor@a625435 on behalf of 5653
D/ConnectivityService(  962): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  962): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5816 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
D/ConnectivityService(  962): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.conn.CONNECTIVITY_CHANGE at null
I/Gmail   ( 5732): notifyAccountChanged
,I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  962): onReceive
D/LocSvc_java(  962): got connectivity action
D/LocSvc_java(  962): broadcast - no network connections
D/LocSvc_java(  962): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  962): Sending msg: 4 arg1:0 arg2:1
,D/LocSvc_java(  962): onReceive
D/LocSvc_java(  962): got connectivity action
D/LocSvc_java(  962): broadcast - no network connections
D/LocSvc_java(  962): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  962): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  962): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  962): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
I/Gmail   ( 5732): getAccountsCursor
W/InstanceID/Rpc( 5653): Found 10006
W/InstanceID/Rpc( 5653): Found 10006
I/Gmail   ( 5732): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GpsLocationProvider(  962): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  962): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/Gmail   ( 5732): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5732): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5732): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/CalendarProvider2( 5488): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
D/GpsLocationProvider(  962): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContentResolver( 5488): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/GpsLocationProvider(  962): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 3211): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3211): created cursor android.database.sqlite.SQLiteCursor@378430ca on behalf of 5653
V/DownloadManager( 3211): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,I/Icing   ( 5653): Internal init done: storage state 0
V/DownloadManager( 3211): created cursor android.database.sqlite.SQLiteCursor@3062823b on behalf of 5653
I/Icing   ( 5653): Post-init done
,I/NotificationManager( 5653): com.google.android.gms: cancel(10436) by com.google.android.gms
D/PhoneMonitor( 5816): Register our PhoneStateListener
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/ActivityManager(  962): Process com.android.calendar (pid 3790) has died
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
,D/PhoneMonitor( 5816): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 5816): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 5816): [parse] Load xml
V/TelephonyAutoProfiling( 5816): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5816): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PhoneMonitor( 5816): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/CheckinService( 5653): Checkin interval check for package: unspecified last checkin: 1455019768061 min interval config: 0 actual interval: 7319
,V/AlarmManager(  962): ELAPSED_WAKEUP set : Alarm{13c12cff type 2 when 87004 com.google.android.gms} when 87004
,I/art     ( 3954): Explicit concurrent mark sweep GC freed 2670(103KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 2.167ms total 41.074ms
,I/Gmail   ( 5732): getAccountsCursor
I/CheckinService( 5653): Disabling old GoogleServicesFramework version
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinService( 5653): Checking schedule, now: 1455019775511 next: 1455019798009
I/CheckinService( 5653): active receiver: disabled
,I/ActivityManager(  962): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5846 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 5846): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  962): Process com.google.android.apps.docs (pid 5509) has died
,I/Babel_SMS( 5846): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 5846): MmsConfig.loadMmsSettings
I/Babel_SMS( 5846): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5846): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5846): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5846): MmsConfig.loadFromResources
E/Babel_SMS( 5846): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5846): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 5846): found sensor: LGE Accelerometer Sensor, handle=0
,D/SensorManager( 5846): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5846): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5846): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5846): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5846): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5846): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5846): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5846): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5846): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5846): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5846): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5846): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5846): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5846): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5846): found sensor: Motion Accel, handle=46
I/QCNEJ   ( 1829): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1829): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 13:09:36.126 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
W/Settings( 5846): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/art     ( 5846): CheckpointMarkThreadRoots callback created = 0xb042d8b0
I/Babel_Crash( 5846): startup - clean
,I/Babel   ( 5846): deleted: false for 0
,V/WifiInternetCheck(  962): Single check msg out of sync, ignoring.
I/art     ( 5846): CheckpointMarkThreadRoots callback created = 0xb042d890
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/ConnectivityService(  962): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  962): onReceive
D/LocSvc_java(  962): got connectivity action
D/LocSvc_java(  962): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  962): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  962): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  962): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  962): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/AudioCapabilities( 5846): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5846): Unsupported mime audio/adpcm
I/Icing   ( 5653): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
W/AudioCapabilities( 5846): Unsupported mime audio/g726
,W/AudioCapabilities( 5846): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5846): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5846): Unsupported mime video/mjpg
,W/VideoCapabilities( 5846): Unsupported mime video/theora
,W/AudioCapabilities( 5846): Unsupported mime audio/evrc
W/AudioCapabilities( 5846): Unsupported mime audio/qcelp
W/VideoCapabilities( 5846): Unrecognized profile 2130706433 for video/avc
,D/Icing   ( 5653): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 5653): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
W/AudioCapabilities( 5846): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 5846): Unsupported mime audio/qcelp
I/ActivityManager(  962): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5886 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/AudioManager( 5042): getMode name:com.lge.qremote
,W/AudioCapabilities( 5846): Unsupported mime audio/evrc
I/AudioManager( 5042): getMode name:com.lge.qremote
,I/AudioManager( 5042): getMode name:com.lge.qremote
W/VideoCapabilities( 5846): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5846): Unsupported profile 4 for video/mp4v-es
,I/AudioManager( 5042): getMode name:com.lge.qremote
D/UEI.SmartControl( 5886): Quickset Services start...
W/VideoCapabilities( 5846): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5846): Unrecognized profile 2130706433 for video/avc
I/UEI.SmartControl( 5886): Manufacture = LGE
D/UEI.SmartControl( 5886): File observer start...
E/UEI.SmartControl( 5886): IR Port is disabled: false
,D/UEI.SmartControl( 5886): Starting file observer...
D/UEI.SmartControl( 5886): Extracting JNI libs...
D/UEI.SmartControl( 5886): --- this system supports 32-bit or 64-bit only
I/AudioManager( 5042): getMode name:com.lge.qremote
,E/MDM     ( 1733): [84] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/VideoCapabilities( 5846): Unrecognized profile 2130706433 for video/avc
D/LocationInitializer( 5653): Restart initialization of location
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
W/VideoCapabilities( 5846): Unrecognized profile 2130706433 for video/avc
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
,I/AudioManager( 5042): getMode name:com.lge.qremote
W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
I/vclib   ( 5846): onServiceConnected
,W/Babel   ( 5846): Attempted to change video mute state without an active call.
I/AudioManager( 5042): getMode name:com.lge.qremote
D/GCM     ( 1733): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
I/NotificationManager( 5846): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/NotificationManager( 5846): com.google.android.talk: cancel(8) by com.google.android.talk
,I/ActivityManager(  962): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5913 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ResourcesManager( 5846): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5846): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,V/JNIHelp ( 5846): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/NotificationManager( 1941): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/AppUp4:AppBoxCP( 5913): onCreate
,I/ActivityManager(  962): Waited long enough for: ServiceRecord{b9ae950 u0 com.lge.qremote/.QRemoteService}
W/AppUp4:DB( 5913):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 5913):  setFingerPrint start
I/AppUp4:DB( 5913):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 5913):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5913):  SDK version = 0
I/AppUp4:DB( 5913):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 5913): AppBoxApplication onCreate()
,W/System  ( 5846): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5846): Installed default security provider GmsCore_OpenSSL
I/AppUp4:CustModeStarterReceiver( 5913): onReceive
I/AppUp4:CustModeStarterReceiver( 5913): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 5913): Context : android.app.ReceiverRestrictedContext@33f08061
D/AppUp4:CustFacade( 5913): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 5913): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 5913): begin check event
I/AppUp4:CustModeStarterReceiver( 5913): Event For Nothing, skip.
,D/UEI.SmartControl( 5886): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 5886): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5886): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/art     ( 1733): Explicit concurrent mark sweep GC freed 42030(2MB) AllocSpace objects, 24(384KB) LOS objects, 40% free, 13MB/22MB, paused 1.854ms total 159.411ms
,I/ActivityManager(  962): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5936 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/UEI.SmartControl( 5886): --- Selecting new region: 2
I/UEI.SmartControl( 5886): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 5886): Platform has CIR...
D/UEI.SmartControl( 5886): NO CIR support, need to check package...
,I/UEI.SmartControl( 5886): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5886): QS Service created
D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  278): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  962): Process com.lge.bnr (pid 5471) has died
,D/libc-netbsd(  278): res_queryN name = xxxxx succeed
,I/System.out(  962): propertyValue:false
D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  278): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out(  962): propertyValue:false
E/UEI.SmartControl( 5886): QS start get config
W/ResourcesManager( 5936): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5936): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5936): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/DSQN    ( 5794): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5794): restart monitoring
I/DSQN    ( 5794): dsqn report finish
D/LGDataListener(  278): argv[0]=dsqncommand
D/LGDataListener(  278): argv[1]=wlan0
D/LGDataListener(  278): argv[2]=1
D/LGDataListener(  278): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  962): DSQM DsqnNotification wlan0  1
D/DSQN    (  962): start to monitor internet connection
V/WifiInternetCheck(  962): isHttpConnectionAvailable - We got a valid response : 204
,D/UEI.SmartControl( 5886): Loading JNI Libs...
,D/UEI.SmartControl( 5886):  configuring local db...
I/AppConfig( 5936): Total System Memory = 906309632
,I/GalleryUtils( 5936): Application Heap = 96 MB
I/AppConfig( 5936): App Tier : NOT_DEF
D/SystemHelper( 5936): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager(  962): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5961 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,D/UEI.SmartControl( 5886):  ---- Has DB8: true
,D/UEI.SmartControl( 5886): QS start statue = true Error code = 0
D/UEI.SmartControl( 5886): QS version = v2.7.11.1_RC1
W/ResourcesManager( 5961): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5961): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5961): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
D/UEI.SmartControl( 5886): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
W/ResourcesManager( 5961): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
,W/ResourcesManager( 5961): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 5886): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 5886): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5886): IrrcClient ++ 
D/irrcClient( 5886): getIrrcService ++ 
,D/irrcClient( 5886): getIrrcService -- 
D/irrcClient( 5886): IrrcClient -- 
W/irrc_jni( 5886): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5886): Services init done
,I/UEI.SmartControl( 5886): Device manager: loading config....
D/UEI.SmartControl( 5886): Config is loaded...
D/UEI.SmartControl( 5886):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5886): Notify AllClients services are ready: 0
D/UEI.SmartControl( 5886): QS Service init finished
,D/UEI.SmartControl( 5886): QS Service version name: 0.1.73
D/UEI.SmartControl( 5886): QS Service version code: 1073
D/UEI.SmartControl( 5886): Service requested: Control
D/UEI.SmartControl( 5886): Internal service binding...
D/UEI.SmartControl( 5886): -----IControl: 11
,D/UEI.SmartControl( 5886): Caller: com.lge.qremote
D/UEI.SmartControl( 5886): ------------ IControl registerCallback...
I/UEI.SmartControl( 5886): Registering callback...
D/UEI.SmartControl( 5886): -----IControl: 19
D/UEI.SmartControl( 5886): Caller: com.lge.qremote
I/UEI.SmartControl( 5886): Registering Services Ready callback...
I/UEI.SmartControl( 5886): Notify client services are ready...
D/UEI.SmartControl( 5886): -----IControl: 8
,D/UEI.SmartControl( 5886): Caller: com.lge.qremote
I/SystemConfig( 5961): BUILD Country: EU
I/SystemConfig( 5961): BUILD Operator: OPEN
,I/[SystemUI]QPairHandler( 1375): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1829): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[SystemUI]QSlideListController( 1375): onReceive = android.intent.action.PACKAGE_CHANGED
,W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1375): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/InputReader(  962): Reconfiguring input devices.  changes=0x00000010
I/[LGHome]EVENT( 1879): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
D/administrator(  962): Handling package changes for user 0
,I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/SystemConfig( 5961): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5961): existFile = false
,I/SystemConfig( 5961): canReadFile = false
I/SystemConfig( 5961): systemFeature RCS result false
D/SystemConfig( 5961): refreshRcsSupport() :false
I/ActivityManager(  962): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5990 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  962): Killing 5554:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  962): failed to open /acct/uid_10086/pid_5554/cgroup.procs: No such file or directory
,I/LockScreenSettings( 5990): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,W/ResourcesManager(  962): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  962): Process com.google.android.gm (pid 5732) has died
,V/AlarmManager(  962): ELAPSED_WAKEUP set : Alarm{5b63fc0 type 2 when 90088 com.google.android.gms} when 90088
D/LockScreenSettings( 5990): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5990): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5990): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5990): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5990): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  962): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6008 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/NotificationService(  962): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  962): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  962): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/ActivityManager(  962): Process com.android.vending (pid 5589) has died
,I/BackupManagerService(  962): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
D/LCardEmulationManager( 1788): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1788): getDefaultRoute
W/ResourceType(  962): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
V/BackupManagerService(  962): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  962): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@395c4252
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/ResourcesManager( 6008): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[LGHome]EVENT( 1879): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1733): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,V/AlarmManager(  962): ELAPSED_WAKEUP set : Alarm{983cf50 type 2 when 90578 com.android.providers.calendar} when 90578
,I/art     (  962): Explicit concurrent mark sweep GC freed 46407(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.252ms total 192.104ms
,D/LocationProviderProxy(  962): applying state to connected service
I/UpdateIcingCorporaServi( 1941): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  962): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6034 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/UpdateIcingCorporaServi( 1941): UpdateCorporaTask done [took 154 ms] updated apps [took 154 ms] 
,I/ActivityManager(  962): Process com.lge.qremote (pid 5042) has died
,D/Finsky  ( 6034): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/Finsky  ( 6034): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6034): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6034): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6034): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3211): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3211): created cursor android.database.sqlite.SQLiteCursor@12419d58 on behalf of 6034
D/Finsky  ( 6034): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6034): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 6034): Skipping gmscore version check
D/PackageBroadcastService( 5653): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/Finsky  ( 6034): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  962): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6079 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/PackageBroadcastService( 5653): Null package name or gms related package.  Ignoreing.
D/Finsky  ( 6034): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 5653): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 6079): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  962): Message: 20
D/BluetoothManagerService(  962): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@362510ac:true
,D/BluetoothAdapterService(151581155)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@214943d1
D/BluetoothAdapterService(151581155)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@214943d1
V/LGMDMManager( 6079): Create singleton instance
,I/AudioManager( 6079): getMode name:com.lge.qremote
,D/UEI.SmartControl( 5886): -----IControl: 11
,D/UEI.SmartControl( 5886): Caller: com.lge.qremote
D/UEI.SmartControl( 5886): ------------ IControl registerCallback...
I/UEI.SmartControl( 5886): Registering callback...
D/UEI.SmartControl( 5886): -----IControl: 19
D/UEI.SmartControl( 5886): Caller: com.lge.qremote
I/UEI.SmartControl( 5886): Registering Services Ready callback...
I/UEI.SmartControl( 5886): Notify client services are ready...
,D/UEI.SmartControl( 5886): -----IControl: 8
D/UEI.SmartControl( 5886): Caller: com.lge.qremote
V/SetupWizard( 5816): Connected to Gservices successfully
I/ActivityManager(  962): Killing 5488:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/libprocessgroup(  962): failed to open /acct/uid_10014/pid_5488/cgroup.procs: No such file or directory
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
,I/ActivityManager(  962): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6113 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 21.314ms
,D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 1733): propertyValue:false
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 23.655ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 327us total 21.648ms
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/jxcore-log( 5297): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5297): 
,W/ResourcesManager( 6113): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6113): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6113): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6113): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6113): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/IndexDatabaseHelper( 6113): Using schema version: 115
,I/IndexDatabaseHelper( 6113): Index is fine
V/WiFiOffLoadBroadcast( 6113): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/ActivityManager(  962): Process com.android.contacts (pid 5961) has died
,I/Icing   ( 5653): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
V/AlarmManager(  962): RTC_WAKEUP set : Alarm{372e9a2d type 0 when 1455019781294 com.google.android.googlequicksearchbox} when 1455019781294
,D/WiFiOffLoadBroadcast( 6113): MCCMNC not supported: null
I/Icing   ( 5653): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  962): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6155 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/art     ( 5653): Background partial concurrent mark sweep GC freed 17011(986KB) AllocSpace objects, 2(32KB) LOS objects, 39% free, 13MB/22MB, paused 2.696ms total 105.340ms
,I/PCSuite ( 6155): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6155): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6155): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6113): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6113): MCCMNC not supported: null
I/PCSuite ( 6155): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6155): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6155): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  962): Killing 5913:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  962): failed to open /acct/uid_10011/pid_5913/cgroup.procs: No such file or directory
,V/WiFiOffLoadBroadcast( 6113): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6113): MCCMNC not supported: null
I/PCSuite ( 6155): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6155): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6155): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6113): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6113): MCCMNC not supported: null
I/PCSuite ( 6155): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6155): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6155): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6113): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6113): MCCMNC not supported: null
I/ActivityManager(  962): Killing 5936:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/libprocessgroup(  962): failed to open /acct/uid_10023/pid_5936/cgroup.procs: No such file or directory
,D/WearableService( 1733): callingUid 10006, callindPid: 1733,
,D/LocationInitializer( 5653): Restart initialization of location
,E/MDM     ( 1733): [142] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
V/WiFiOffLoadBroadcast( 6113): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 6113): Not supported operator for automatic switch
,V/WiFiOffLoadBroadcast( 6113): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/GCoreFlp( 1733): No location to return for getLastLocation()
,W/FusedLocationProvider( 1733): location=null
I/jxcore-log( 5297): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5297): 
D/WiFiOffLoadBroadcast( 6113): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6113): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6113): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6113): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6113): MCCMNC not supported: null
I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,V/WiFiOffLoadBroadcast( 6113): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/PhoneInterfaceManager( 1752): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
D/WiFiOffLoadBroadcast( 6113): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6113): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/VideoCapabilities( 5846): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5846): Unrecognized profile 2130706433 for video/avc
D/WiFiOffLoadBroadcast( 6113): MCCMNC not supported: null
W/VideoCapabilities( 5846): Unrecognized profile 2130706433 for video/avc
,V/AlarmManager(  962): RTC_WAKEUP set : Alarm{9b10b74 type 0 when 1455019782087 com.android.vending} when 1455019782087
V/WiFiOffLoadBroadcast( 6113): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/Finsky  ( 6034): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/WiFiOffLoadBroadcast( 6113): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6113): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6113): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6113): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/jxcore-log( 5297): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5297): 
D/WiFiOffLoadBroadcast( 6113): MCCMNC not supported: null
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/jxcore-log( 5297): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 5297): 
,V/WiFiOffLoadBroadcast( 6113): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6113): MCCMNC not supported: null
I/PCSuite ( 6155): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6155): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/WiFiOffLoadBroadcast( 6113): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6113): MCCMNC not supported: null
I/PCSuite ( 6155): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6155): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
I/NotificationManager(  962): android: cancelAsUser(2) by android
,I/ActivityManager(  962): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6196 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/jxcore-log( 5297): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 5297): 
,I/NotificationManager( 5846): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/jxcore-log( 5297): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 5297): 
,D/libc-netbsd( 6034): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6034): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6034): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6034): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  278): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
,I/System.out( 6034): propertyValue:false
D/libc-netbsd( 6034): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6034): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 1733): propertyValue:false
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/ActivityManager(  962): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6196): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd( 6034): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6034): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/GAV2    ( 6196): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ActivityManager(  962): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 6196): Error finding the version of the Email provider.....
E/Gmail   ( 6196): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6196): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6196): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6196): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6196): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6196): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6196): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6196): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 6196): We do not support migrating this version of the Email provider.
I/Gmail   ( 6196): getAccountsCursor
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  962): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6238 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ActivityManager(  962): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/NotificationManager(  962): android: cancelAsUser(2) by android
,W/ActivityManager(  962): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 6196): Observing account changes for notifications
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/UEI.SmartControl( 5886): Internal timer expired: 1
,W/art     ( 5846): Attempt to remove local handle scope entry from IRT, ignoring
,I/Gmail   ( 6196): notifyAccountChanged
,I/Gmail   ( 6196): getAccountsCursor
I/Gmail   ( 6196): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 6196): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6196): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6196): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/art     (  962): Explicit concurrent mark sweep GC freed 27280(1290KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.595ms total 175.152ms
,I/ActivityManager(  962): Process com.google.android.apps.plus (pid 6008) has died
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  962): android: cancelAsUser(2) by android
,D/libc-netbsd( 5846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
E/BandwidthController(  278): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  278): App 10061 tries DNS query. Accept family:2 protocol:0
,D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
,D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
,I/MusicStore( 6238): Database version: 120
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/qtaguid ( 6034): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6034): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6034): untagSocket(41) failed with errno -22
D/Finsky  ( 6034): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/Gmail   ( 6196): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  962): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6274 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  962): android: cancelAsUser(2) by android
,I/ActivityManager(  962): Process com.google.android.setupwizard (pid 5816) has died
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 95251272834; DSPS: 3212451; Offset : -2795217364
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ResourcesManager( 6274): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6274): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ContextImpl( 6238): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/MultiDex( 6274): VM with version 2.1.0 has multidex support
I/MultiDex( 6274): install
I/MultiDex( 6274): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6274): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/qtaguid ( 6034): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6034): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6034): untagSocket(41) failed with errno -22
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6238): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6238): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,W/ActivityThread( 6274): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6274): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@df0feb1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6274): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 6274): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6274): com.google.android.gms: cancel(39789) by com.google.android.gms
W/ResourcesManager( 6238): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6238): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/ChimeraCfgMgr( 6274): Reading stored module config
,V/JNIHelp ( 6238): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  962): Process com.lge.lockscreensettings (pid 5990) has died
,I/BackgroundMemoryTrimmer( 1941): Trimming objects from memory, since app is in the background.
I/PhoneApp( 1752): onTrimMemory: 10
I/PhoneApp( 1752): trim memory
,D/UEI.SmartControl( 5886): Service.onTrimMemory: 60
D/ChimeraCfgMgr( 6274): Loading module com.google.android.gms.car from APK com.google.android.gms
E/UEI.SmartControl( 5886): Setup service releasing memory...
,I/art     ( 5846): Note: end time exceeds epoch: 
I/Babel   ( 5846): Account registration complete:1-Redacted-21
,W/ActivityThread( 6238): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6238): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@b3ab5d0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6238): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6238): GMSCore installation verified
I/art     ( 5886): Explicit concurrent mark sweep GC freed 158(17KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 350us total 50.866ms
,I/Babel   ( 5846): ProcessRegisterDeviceResponse
I/Babel   ( 5846): Perform warm sync in case there are messages missed before the device is registered for account Redacted-21
,I/ActivityManager(  962): Process com.android.settings (pid 6113) has died
,V/AlarmManager(  962): ELAPSED_WAKEUP set : Alarm{1de87f0b type 2 when 95777 com.google.android.talk} when 95777
D/NativeLibraryUtils( 6274): Install completed successfully. count=14 extracted=0
I/ConfigStore( 6238): Config Database version: 1
,D/CAR.SERVICE( 6274): Connecting to CarCallService...
,I/art     ( 6274): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6274): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/MediaRouter( 6238): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/art     ( 6034): CheckpointMarkThreadRoots callback created = 0xb05843a0
V/MusicLeanback( 6238): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6238): type=WIFI subType= reason=null isConnected=true
D/CAR.SERVICE( 6274): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6274): Creating a new CarCallService.
,I/art     ( 6034): CheckpointMarkThreadRoots callback created = 0xb0584360
D/CAR.TEL.PhoneAdapter( 6274): Creating a new PhoneAdapter instance
W/ActivityManager(  962): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6274): setListener: com.google.android.gms.car.dn@3a806934
W/ActivityManager(  962): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6274): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6274): Starting CarCallService with initial phone null
I/art     ( 6034): WaitForGcToComplete blocked for 48.646ms for cause HomogeneousSpaceCompact
I/NotificationManager( 6274): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NetworkMonitor( 6238): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  962): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6322 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6238): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/CAR.SERVICE( 6274): Package validated; name: com.android.vending
I/GoogleURLConnFactory( 6238): Using platform SSLCertificateSocketFactory
,I/NotificationManager( 6034): com.android.vending: cancel(10436) by com.android.vending
V/Finsky  ( 6034): [1] GearheadStateMonitor.access$100: mIsProjecting:false
I/NotificationManager( 6238): com.google.android.music: cancel(1061) by com.google.android.music
,W/ResourcesManager( 6322): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6322): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6322): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/LGEmail ( 6322): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6322): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/ActivityManager(  962): Process com.lge.sync (pid 6155) has died
,I/BackgroundMemoryTrimmer( 1941): Trimming objects from memory, since app is in the background.
D/UEI.SmartControl( 5886): Service.onTrimMemory: 60
E/UEI.SmartControl( 5886): Setup service releasing memory...
I/PhoneApp( 1752): onTrimMemory: 10
I/PhoneApp( 1752): trim memory
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  962): android: cancelAsUser(2) by android
D/eas_req ( 6322): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  962): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6348 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6322): JNI_OnLoad()
I/HubEmail( 6322): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6322): registerNatives()
I/HubEmail( 6322): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6322): registerNativeMethods()
I/HubEmail( 6322): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6322): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6322): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/qtaguid ( 6034): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6034): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6034): untagSocket(41) failed with errno -22
,D/LGDMClient( 6348): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6348): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6348): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6348): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,D/LGDMClient( 6348): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6348): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6348): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6348): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  962): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6372 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6348): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6348): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6348): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6348): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6348): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6348): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/AppUp4:AppBoxCP( 6372): onCreate
,W/AppUp4:DB( 6372):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6372):  setFingerPrint start
,I/AppUp4:DB( 6372):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6372):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6372):  SDK version = 0
I/AppUp4:DB( 6372):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 6372): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6372): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6372): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6372): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6372): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6372): onReceive
I/AppUp4:CustModeStarterReceiver( 6372): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 6372): Context : android.app.ReceiverRestrictedContext@2db32874
D/AppUp4:CustFacade( 6372): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6372): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6372): begin check event
I/AppUp4:CustModeStarterReceiver( 6372): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6372): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6372): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6372): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6372): handleAsyncCustNotification do not startCustService
W/ResourcesManager( 6034): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6034): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/LgeMiscReceiver( 3186): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3186): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3186): networkInfo.isConnected() = false
W/ResourcesManager( 6034): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  962): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6393 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/Finsky  ( 6034): [1] DailyHygiene.access$600: Logging device features
I/ActivityManager(  962): Process com.google.android.gm (pid 6196) has died
,V/AlarmManager(  962): RTC_WAKEUP set : Alarm{3ddfaec type 0 when 1455019785879 com.android.vending} when 1455019785879
D/DeviceConnectionService( 1733): client connected with version: 8296000
,D/Finsky  ( 6034): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 6034): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
D/PhoneMonitor( 6393): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6393): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6393): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinService( 5653): Checkin interval check for package: unspecified last checkin: 1455019768061 min interval config: 0 actual interval: 18049
V/DownloadManager( 3211): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3211): DownloadService onCreate
I/DownloadManager( 3211): in removeSpuriousFiles
I/NotificationManager( 3211): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3211): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3211): created cursor android.database.sqlite.SQLiteCursor@df0feb1 on behalf of 3211
D/PhoneMonitor( 6393): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,I/DownloadManager( 3211): in trimDatabase
V/DownloadManager( 3211): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3211): created cursor android.database.sqlite.SQLiteCursor@12ed0717 on behalf of 3211
V/TelephonyAutoProfiling( 6393): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6393): [parse] Load xml
V/TelephonyAutoProfiling( 6393): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6393): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6393): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/ActivityManager(  962): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6418 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3211): DownloadService onStartCommand
V/DownloadManager( 3211): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3211): created cursor android.database.sqlite.SQLiteCursor@17e5d4ed on behalf of 3211
I/ActivityManager(  962): Process com.google.android.music:main (pid 6238) has died
,I/CheckinService( 5653): Checking schedule, now: 1455019786309 next: 1455019798009
I/CheckinService( 5653): active receiver: disabled
V/DownloadManager( 3211): DownloadService onDestroy
D/WeatherAncestor( 2691): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:9:46
,D/UpdateThreadPoolManager( 2691): 2 : This is isUpdating : false
D/WeatherAncestor( 2691): connectivity changed - connection : true
D/Weather_cast( 2691): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2691): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:9:46
D/WeatherService( 2691): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
W/ActivityManager(  962): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2691): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2691): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2691): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/ActivityManager(  962): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6439 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd( 5846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5846): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5846): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  278): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
,I/System.out( 5846): propertyValue:false
I/Babel   ( 5846): connection state changed from UNKNOWN to CONNECTED
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6439): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6439): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6439): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6439): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6439): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6439):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6439):   adb logcat -s GAv4
,I/ActivityManager(  962): Process com.lge.email (pid 6322) has died
,W/GAv4    ( 6439): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 6439): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6439): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/art     (  962): Explicit concurrent mark sweep GC freed 18249(886KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 1.883ms total 144.184ms
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/WebViewFactory( 6439): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6439): Time to load native libraries: 1 ms (timestamps 8961-8962)
,I/LibraryLoader( 6439): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6439): Binding Chromium to main looper Looper (main, tid 1) {27cdf621}
,I/LibraryLoader( 6439): Expected native library version number "",actual native library version number ""
I/chromium( 6439): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6439): Initializing chromium process, singleProcess=true
,W/art     ( 6439): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6439): ApplicationContext is null in ApplicationStatus
W/chromium( 6439): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6439): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6439): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6439): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6439): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6439): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6439): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6439): Remote Branch: 
I/Adreno-EGL( 6439): Local Patches: 
I/Adreno-EGL( 6439): Reconstruct Branch: 
V/AudioPolicyService(  282): registerClient() client 0xb57ec200, uid 10079
,W/AudioManagerAndroid( 6439): Requires BLUETOOTH permission
I/NSApplication( 6439): Starting up...
,I/ActivityManager(  962): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6497 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  962): Killing 5886:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,I/art     (  308): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 305us total 27.268ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 23.325ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 20.960ms
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/ActivityManager(  962): Process com.lge.qremote (pid 6079) has died
E/lowmemorykiller(  243): Error opening /proc/5886/oom_score_adj; errno=2
,W/ActivityManager(  962): Exception when unbinding service com.uei.lg.quicksetsdk.lite/com.uei.control.Service
W/ActivityManager(  962): android.os.DeadObjectException
W/ActivityManager(  962): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  962): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  962): 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
W/ActivityManager(  962): 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1788)
W/ActivityManager(  962): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2174)
W/ActivityManager(  962): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15220)
W/ActivityManager(  962): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:5064)
W/ActivityManager(  962): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:5234)
W/ActivityManager(  962): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1234)
W/ActivityManager(  962): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:553)
,W/ActivityManager(  962): Exception when destroying service com.uei.lg.quicksetsdk.lite/com.uei.control.Service
W/ActivityManager(  962): android.os.DeadObjectException
W/ActivityManager(  962): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  962): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  962): 	at android.app.ApplicationThreadProxy.scheduleStopService(ApplicationThreadNative.java:946)
W/ActivityManager(  962): 	at com.android.server.am.ActiveServices.bringDownServiceLocked(ActiveServices.java:1693)
W/ActivityManager(  962): 	at com.android.server.am.ActiveServices.bringDownServiceIfNeededLocked(ActiveServices.java:1605)
W/ActivityManager(  962): 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1805)
W/ActivityManager(  962): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2174)
W/ActivityManager(  962): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15220)
W/ActivityManager(  962): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:5064)
W/ActivityManager(  962): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:5234)
W/ActivityManager(  962): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1234)
W/ActivityManager(  962): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:553)
W/libprocessgroup(  962): failed to open /acct/uid_10089/pid_5886/cgroup.procs: No such file or directory
I/ActivityManager(  962): Process com.google.android.gms:car (pid 6274) has died
,W/ActivityManager(  962): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 1000ms
I/ActivityManager(  962): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6517 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6517): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/iu.SyncManager( 5653): SYNC; picasa accounts
,D/NetworkLogImpl( 5653): Loaded NetworkSpeedPredictor
I/iu.Environment( 5653): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 5653): num queued entries: 0
I/iu.UploadsManager( 5653): num updated entries: 0
I/iu.SyncManager( 5653): NEXT; no task
,I/ActivityManager(  962): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6558 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  962): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6579 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/MusicStore( 6558): Database version: 120
,W/ResourcesManager( 6579): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6579): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6558): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/MultiDex( 6579): VM with version 2.1.0 has multidex support
I/MultiDex( 6579): install
I/MultiDex( 6579): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6579): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6579): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/System  ( 6579): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@df0feb1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6579): Installed default security provider GmsCore_OpenSSL
W/ContextImpl( 6558): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/NotificationManager( 6579): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6579): com.google.android.gms: cancel(39789) by com.google.android.gms
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6558): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/ChimeraCfgMgr( 6579): Reading stored module config
,W/ResourcesManager( 6558): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6558): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/ChimeraCfgMgr( 6579): Loading module com.google.android.gms.car from APK com.google.android.gms
V/JNIHelp ( 6558): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6558): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6558): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@b3ab5d0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6558): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6558): GMSCore installation verified
I/ConfigStore( 6558): Config Database version: 1
,D/NativeLibraryUtils( 6579): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 6579): Connecting to CarCallService...
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  962): Process com.android.vending (pid 6034) has died
,I/art     ( 6579): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6579): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/CAR.SERVICE( 6579): com.google.android.projection.gearhead isn't installed.
,D/CAR.SERVICE( 6579): mConnectedToCar = false, abort
D/CAR.TEL.Service( 6579): Creating a new CarCallService.
,I/MediaRouter( 6558): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
D/CAR.TEL.PhoneAdapter( 6579): Creating a new PhoneAdapter instance
W/ActivityManager(  962): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6579): setListener: com.google.android.gms.car.dn@3a806934
W/ActivityManager(  962): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6579): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6579): Starting CarCallService with initial phone null
V/MusicLeanback( 6558): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/ActivityThread( 6579): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@e44629c that was originally bound here
E/ActivityThread( 6579): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@e44629c that was originally bound here
E/ActivityThread( 6579): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6579): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6579): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6579): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6579): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6579): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6579): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6579): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6579): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6579): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6579): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6579): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6579): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6579): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6579): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6579): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6579): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6579): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6579): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6579): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6579): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6579): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6579): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/NetworkMonitor( 6558): type=WIFI subType= reason=null isConnected=true
,E/ActivityThread( 6579): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1047e407 that was originally bound here
E/ActivityThread( 6579): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1047e407 that was originally bound here
E/ActivityThread( 6579): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6579): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6579): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6579): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6579): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6579): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6579): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6579): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6579): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6579): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6579): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6579): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6579): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6579): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6579): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6579): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6579): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6579): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6579): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6579): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6579): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6579): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  962): Unbind failed: could not find connection for android.os.BinderProxy@351d175e
I/NotificationManager( 6579): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/ActivityManager(  962): Killing 6348:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/libprocessgroup(  962): failed to open /acct/uid_1000/pid_6348/cgroup.procs: No such file or directory
,I/NetworkMonitor( 6558): type=WIFI subType= reason=null isConnected=true
I/ActivityManager(  962): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6621 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6558): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6558): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  962): Killing 6372:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  962): failed to open /acct/uid_10011/pid_6372/cgroup.procs: No such file or directory
,I/NotificationManager( 6558): com.google.android.music: cancel(1061) by com.google.android.music
W/ResourcesManager( 6621): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6621): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6621): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/LGEmail ( 6621): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6621): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6621): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  962): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6650 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6621): JNI_OnLoad()
I/HubEmail( 6621): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6621): registerNatives()
I/HubEmail( 6621): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6621): registerNativeMethods()
,I/HubEmail( 6621): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6621): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  962): Killing 6393:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  962): failed to open /acct/uid_10038/pid_6393/cgroup.procs: No such file or directory
,W/Settings( 6621): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 6650): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6650): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6650): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6650): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,D/LGDMClient( 6650): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6650): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager(  962): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6680 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/LGDMClient( 6650): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6650): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 6650): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 6650): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6650): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6650): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6650): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 6650): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  962): Killing 6418:com.lge.drmservice/u0a51 (adj 15): empty #11
I/AppUp4:AppBoxCP( 6680): onCreate
W/AppUp4:DB( 6680):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6680):  setFingerPrint start
I/AppUp4:DB( 6680):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6680):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6680):  SDK version = 0
I/AppUp4:DB( 6680):  beforefinger == newfinger no write in DB
,I/jxcore-log( 5297): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 5297): 
I/jxcore-log( 5297): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 5297): 
,I/jxcore-log( 5297): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5297): 
W/libprocessgroup(  962): failed to open /acct/uid_10051/pid_6418/cgroup.procs: No such file or directory
,D/AppUp4:AppBoxApplication( 6680): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6680): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6680): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6680): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6680): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6680): onReceive
I/AppUp4:CustModeStarterReceiver( 6680): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6680): Context : android.app.ReceiverRestrictedContext@2db32874
,D/AppUp4:CustFacade( 6680): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6680): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6680): begin check event
I/AppUp4:CustModeStarterReceiver( 6680): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6680): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6680): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6680): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6680): handleAsyncCustNotification do not startCustService
I/ActivityManager(  962): Killing 5846:com.google.android.talk/u0a61 (adj 15): empty #11
E/libprocessgroup(  962): failed to kill 1 processes for processgroup 5846
,I/LgeMiscReceiver( 3186): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3186): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3186): networkInfo.isConnected() = false
,I/ActivityManager(  962): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6709 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/PhoneMonitor( 6709): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6709): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6709): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  962): Killing 6439:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,D/PhoneMonitor( 6709): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6709): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6709): [parse] Load xml
,V/TelephonyAutoProfiling( 6709): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6709): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 6709): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/rmt_storage(  274): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  274): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  274): wakelock acquired: 1, error no: 42
I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
,I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  274): 
I/rmt_storage(  274): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
W/libprocessgroup(  962): failed to open /acct/uid_10079/pid_6439/cgroup.procs: No such file or directory
V/DownloadManager( 3211): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3211): DownloadService onCreate
I/DownloadManager( 3211): in removeSpuriousFiles
I/NotificationManager( 3211): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3211): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3211): created cursor android.database.sqlite.SQLiteCursor@3b30fdb3 on behalf of 3211
I/DownloadManager( 3211): in trimDatabase
V/DownloadManager( 3211): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3211): created cursor android.database.sqlite.SQLiteCursor@4d7d2e9 on behalf of 3211
I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
I/ActivityManager(  962): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6736 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3211): DownloadService onStartCommand
V/DownloadManager( 3211): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3211): created cursor android.database.sqlite.SQLiteCursor@2eb3c20f on behalf of 3211
,I/CheckinService( 5653): Checkin interval check for package: unspecified last checkin: 1455019768061 min interval config: 0 actual interval: 24122
V/DownloadManager( 3211): DownloadService onDestroy
,I/CheckinService( 5653): Checking schedule, now: 1455019792194 next: 1455019798009
I/CheckinService( 5653): active receiver: disabled
I/ActivityManager(  962): Killing 6497:com.android.chrome/u0a48 (adj 15): empty #11
,W/libprocessgroup(  962): failed to open /acct/uid_10048/pid_6497/cgroup.procs: No such file or directory
D/WeatherAncestor( 2691): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:9:52
,D/UpdateThreadPoolManager( 2691): 2 : This is isUpdating : false
D/WeatherAncestor( 2691): connectivity changed - connection : true
D/Weather_cast( 2691): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2691): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:9:52
D/WeatherService( 2691): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  962): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6758 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  962): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2691): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2691): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2691): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6758): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/jxcore-log( 5297): Test app app.js loaded
I/jxcore-log( 5297): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5297): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5297): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5297): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5297): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5297): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5297): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5297): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5297): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5297): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5297): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ad6b4b3 added. We now have 1 listener(s)
,D/BluetoothAdapterService(151581155)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@214943d1
I/jxcore-log( 5297): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5297): 
,I/chromium( 5297): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/Babel_SMS( 6758): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6758): MmsConfig.loadMmsSettings
I/Babel_SMS( 6758): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6758): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6758): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6758): MmsConfig.loadFromResources
E/Babel_SMS( 6758): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6758): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6758): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6758): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6758): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6758): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6758): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6758): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6758): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6758): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6758): found sensor: LGE Step Counter Sensor, handle=44
,D/SensorManager( 6758): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6758): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6758): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6758): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6758): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6758): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6758): found sensor: Motion Accel, handle=46
W/Settings( 6758): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6758): startup - clean
I/art     ( 6758): CheckpointMarkThreadRoots callback created = 0xb042d8e0
,I/Babel   ( 6758): deleted: false for 0
,I/art     ( 6758): CheckpointMarkThreadRoots callback created = 0xb042d8c0
,I/art     (  962): Explicit concurrent mark sweep GC freed 18131(887KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.516ms total 145.814ms
,I/ActivityManager(  962): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6802 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 6758): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6758): Unsupported mime audio/adpcm,
W/AudioCapabilities( 6758): Unsupported mime audio/g726
W/AudioCapabilities( 6758): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6758): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6758): Unsupported mime video/mjpg
,W/VideoCapabilities( 6758): Unsupported mime video/theora
W/AudioCapabilities( 6758): Unsupported mime audio/evrc
,W/AudioCapabilities( 6758): Unsupported mime audio/qcelp
W/VideoCapabilities( 6758): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6758): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6758): Unsupported mime audio/qcelp
W/AudioCapabilities( 6758): Unsupported mime audio/evrc
W/VideoCapabilities( 6758): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6758): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6758): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6758): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6758): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6758): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6758): onServiceConnected
,W/Babel   ( 6758): Attempted to change video mute state without an active call.
D/libc-netbsd( 6758): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6758): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6758): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6758): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  278): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
I/NotificationManager( 6758): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 6758): propertyValue:false
I/Babel   ( 6758): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  962): Killing 6517:com.google.android.apps.plus/u0a86 (adj 15): empty #11
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6802): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6802): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6802): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6802): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6802): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6802):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6802):   adb logcat -s GAv4
W/libprocessgroup(  962): failed to open /acct/uid_10086/pid_6517/cgroup.procs: No such file or directory
,W/GAv4    ( 6802): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6802): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6802): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 6802): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6802): Time to load native libraries: 2 ms (timestamps 5561-5563)
I/LibraryLoader( 6802): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6802): Binding Chromium to main looper Looper (main, tid 1) {27cdf621}
,I/LibraryLoader( 6802): Expected native library version number "",actual native library version number ""
I/chromium( 6802): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6802): Initializing chromium process, singleProcess=true
W/art     ( 6802): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6802): ApplicationContext is null in ApplicationStatus
W/chromium( 6802): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6802): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6802): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6802): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6802): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6802): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6802): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6802): Remote Branch: 
I/Adreno-EGL( 6802): Local Patches: 
I/Adreno-EGL( 6802): Reconstruct Branch: 
I/NSApplication( 6802): Starting up...
,V/AudioPolicyService(  282): registerClient() client 0xb4027080, uid 10079
W/AudioManagerAndroid( 6802): Requires BLUETOOTH permission
,I/ActivityManager(  962): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6870 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  962): Killing 6579:com.google.android.gms:car/u0a6 (adj 15): empty #11
I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 320us total 30.709ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 319us total 24.929ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 20.633ms
,W/libprocessgroup(  962): failed to open /acct/uid_10006/pid_6579/cgroup.procs: No such file or directory
,I/ActivityManager(  962): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6893 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  962): Killing 6558:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  962): failed to open /acct/uid_10081/pid_6558/cgroup.procs: No such file or directory
,W/ResourcesManager( 6893): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ActivityManager(  962): Killing 6621:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  962): failed to open /acct/uid_10021/pid_6621/cgroup.procs: No such file or directory
,I/ActivityManager(  962): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6921 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6921): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 6921): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6921): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 6921): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@344c57c8, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@33f08061, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@108a6786, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@e1d1847, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2db32874, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@953c19d, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@1a157612, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@908f1e3, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@b1457e0, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@1afda99, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@37d0e15e, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@154ec93f, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@3997120c, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@e1a8755, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@1745b56a, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@1ff0ba5b, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@2fa942f8, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@214943d1, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@381be36, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@19f6a137, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@1aab96a4, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@9cd4c0d, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@18a387c2, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@130a19d3, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@3b5d7910, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@340f9c09, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@24265e0e, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@21d2802f, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@1d09163c, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@100cefc5, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@3dee4d1a, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@3610f04b, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@136f5a28, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@16d1c341, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@261420e6, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@307c4627, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2b73f0d4, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@2bb6527d, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@33716572, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1c5d1dc3, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@3a894640, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@155a99
D/GeneralP,referenceUtils( 6921): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6921): [init]
I/Config  ( 6921): LGCalendar ver.4.40.17
I/Config  ( 6921): start check model
I/Config  ( 6921): start check native_ca
,I/Config  ( 6921): Config Operator=OPEN, Country=EU
D/Config  ( 6921): [setDefaultValuesToPref]
D/Config  ( 6921): [parseProfiles]
D/ProfilesParser( 6921): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6921): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6921): [updateProfiletoCountryInfo]
D/GeneralPreference( 6921): [checkAndMigrateOldPreference]
D/AlertReceiver( 6921): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,I/InitNotificationRingtoneService( 6921): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 6921): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,I/AlertUtils( 6921): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6921): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6921): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,I/AlertUtils( 6921): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6921): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6921): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6921): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/AlertUtils( 6921): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6921): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6921): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6921): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
,I/AlertUtils( 6921): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6921): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6921): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6921): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,I/AlertUtils( 6921): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6921): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 6921): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 6921): End InitializeAlertRingtoneService.onHandleIntent
,W/HolidayIntentService( 6921): onHandleIntent
,D/HolidayDataLoader( 6921): readJsonAsset : holiday.json
D/AlertService( 6921): 0 Action = android.intent.action.PROVIDER_CHANGED
E/AgendaWidgetManager( 6921): [updateWidgets] 
,D/MonthWidgetProvider( 6921): [onReceive]
D/CalendarWidgetProvider( 6921): [onReceive]
D/CalendarWidgetProvider( 6921): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6921): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 6921): [onReceive]
D/CalendarWidgetProvider( 6921): [onReceive]
D/CalendarWidgetProvider( 6921): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6921): [onCreate] mContext.getPackageName() = com.android.calendar
,I/CheckinService( 5653): Done disabling old GoogleServicesFramework version
E/HolidayIntentService( 6921): onHandleIntent:holiday data empty
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  962): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6951 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/MusicStore( 6951): Database version: 120
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6951): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6951): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6951): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6951): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6951): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6951): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6951): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6951): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@b3ab5d0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6951): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6951): GMSCore installation verified
,I/ConfigStore( 6951): Config Database version: 1
,I/MediaRouter( 6951): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6951): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6951): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6951): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  962): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6983 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/GHttpClientFactory( 6951): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6951): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  962): Killing 6650:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/ResourcesManager( 6983): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6983): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6983): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  962): failed to open /acct/uid_1000/pid_6650/cgroup.procs: No such file or directory
,I/NotificationManager( 6951): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6983): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6983): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6983): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ActivityManager(  962): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7006 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6983): JNI_OnLoad()
I/HubEmail( 6983): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6983): registerNatives()
I/HubEmail( 6983): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6983): registerNativeMethods()
I/HubEmail( 6983): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6983): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  962): Killing 6680:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  962): failed to open /acct/uid_10011/pid_6680/cgroup.procs: No such file or directory
,W/Settings( 6983): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 7006): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7006): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7006): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7006): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7006): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7006): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7006): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 7006): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  962): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7038 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7006): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7006): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7006): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7006): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7006): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 7006): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  962): Killing 6736:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  962): failed to open /acct/uid_10051/pid_6736/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 7038): onCreate
,W/AppUp4:DB( 7038):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7038):  setFingerPrint start
,I/AppUp4:DB( 7038):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7038):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
,I/AppUp4:DB( 7038):  SDK version = 0
I/AppUp4:DB( 7038):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7038): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7038): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7038): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7038): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7038): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7038): onReceive
I/AppUp4:CustModeStarterReceiver( 7038): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7038): Context : android.app.ReceiverRestrictedContext@2db32874
D/AppUp4:CustFacade( 7038): isCustomizationCompleted : false
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
D/AppUp4:CustFacade( 7038): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7038): begin check event
I/AppUp4:CustModeStarterReceiver( 7038): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7038): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7038): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7038): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7038): handleAsyncCustNotification do not startCustService
I/ActivityManager(  962): Killing 6758:com.google.android.talk/u0a61 (adj 15): empty #11
I/LgeMiscReceiver( 3186): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3186): action = android.net.conn.CONNECTIVITY_CHANGE
W/libprocessgroup(  962): failed to open /acct/uid_10061/pid_6758/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3186): networkInfo.isConnected() = true
,D/PhoneState( 3186): setPdpRejectCasuse : false
D/MobileConnectivityChangeReceiver( 6709): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6709): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 3211): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3211): DownloadService onCreate
I/DownloadManager( 3211): in removeSpuriousFiles
V/DownloadManager( 3211): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/NotificationManager( 3211): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/ActivityManager(  962): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7068 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager(  962): Killing 6802:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,I/art     (  962): Explicit concurrent mark sweep GC freed 18891(904KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.536ms total 212.375ms
,V/DownloadManager( 3211): created cursor android.database.sqlite.SQLiteCursor@9d1b4a5 on behalf of 3211
I/DownloadManager( 3211): in trimDatabase
V/DownloadManager( 3211): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3211): created cursor android.database.sqlite.SQLiteCursor@1bf4702b on behalf of 3211
D/WeatherAncestor( 2691): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:9:57
W/libprocessgroup(  962): failed to open /acct/uid_10079/pid_6802/cgroup.procs: No such file or directory
,V/DownloadManager( 3211): DownloadService onStartCommand
V/DownloadManager( 3211): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/UpdateThreadPoolManager( 2691): 2 : This is isUpdating : false
D/WeatherAncestor( 2691): connectivity changed - connection : true
D/Weather_cast( 2691): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2691): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:9:57
D/WeatherService( 2691): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3211): created cursor android.database.sqlite.SQLiteCursor@27cdf621 on behalf of 3211
I/ActivityManager(  962): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7095 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  962): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2691): 2 : Utils getTopActivity com.lge.launcher2 / true
V/DownloadManager( 3211): DownloadService onDestroy
D/WeatherService( 2691): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2691): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 7095): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/Babel_SMS( 7095): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7095): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7095): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7095): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7095): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7095): MmsConfig.loadFromResources
E/Babel_SMS( 7095): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7095): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7095): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7095): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7095): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
,D/SensorManager( 7095): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7095): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7095): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7095): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7095): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7095): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7095): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7095): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7095): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7095): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7095): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7095): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7095): found sensor: Motion Accel, handle=46
W/Settings( 7095): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7095): startup - clean
I/Babel   ( 7095): deleted: false for 0
,I/art     ( 7095): CheckpointMarkThreadRoots callback created = 0xb042d910
,I/art     ( 7095): CheckpointMarkThreadRoots callback created = 0xb042d8e0
,I/ActivityManager(  962): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7126 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/AudioCapabilities( 7095): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7095): Unsupported mime audio/adpcm
W/AudioCapabilities( 7095): Unsupported mime audio/g726
W/AudioCapabilities( 7095): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7095): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7095): Unsupported mime video/mjpg
W/VideoCapabilities( 7095): Unsupported mime video/theora
,W/AudioCapabilities( 7095): Unsupported mime audio/evrc
,W/AudioCapabilities( 7095): Unsupported mime audio/qcelp
W/VideoCapabilities( 7095): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7095): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7095): Unsupported mime audio/qcelp
W/AudioCapabilities( 7095): Unsupported mime audio/evrc
,W/VideoCapabilities( 7095): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7095): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 7095): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7095): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7095): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7095): Unrecognized profile 2130706433 for video/avc
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7126): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/vclib   ( 7095): onServiceConnected
W/Babel   ( 7095): Attempted to change video mute state without an active call.
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7126): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/NotificationManager( 7095): com.google.android.talk: cancel(10436) by com.google.android.talk
I/GAv4    ( 7126): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7126):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7126):   adb logcat -s GAv4
,D/libc-netbsd( 7095): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7095): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7095): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7095): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  278): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
,I/System.out( 7095): propertyValue:false
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7126): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
W/GAv4    ( 7126): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7126): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 7126): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7126): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/Babel   ( 7095): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  962): Killing 6870:com.android.chrome/u0a48 (adj 15): empty #11
W/libprocessgroup(  962): failed to open /acct/uid_10048/pid_6870/cgroup.procs: No such file or directory
,I/WebViewFactory( 7126): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7126): Time to load native libraries: 2 ms (timestamps 368-370)
I/LibraryLoader( 7126): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7126): Binding Chromium to main looper Looper (main, tid 1) {27cdf621}
I/LibraryLoader( 7126): Expected native library version number "",actual native library version number ""
I/chromium( 7126): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7126): Initializing chromium process, singleProcess=true
,W/art     ( 7126): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7126): ApplicationContext is null in ApplicationStatus
W/chromium( 7126): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7126): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7126): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7126): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7126): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7126): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7126): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7126): Remote Branch: 
I/Adreno-EGL( 7126): Local Patches: 
I/Adreno-EGL( 7126): Reconstruct Branch: 
V/AudioPolicyService(  282): registerClient() client 0xb4027460, uid 10079
,W/AudioManagerAndroid( 7126): Requires BLUETOOTH permission
I/NSApplication( 7126): Starting up...
,I/ActivityManager(  962): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7194 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  962): Killing 6893:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  962): failed to open /acct/uid_10086/pid_6893/cgroup.procs: No such file or directory
,I/ActivityManager(  962): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7216 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  962): Killing 6951:com.google.android.music:main/u0a81 (adj 15): empty #11
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 26.405ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 21.677ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 263us total 20.468ms
,W/libprocessgroup(  962): failed to open /acct/uid_10081/pid_6951/cgroup.procs: No such file or directory
,W/ResourcesManager( 7216): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  962): Killing 6983:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  962): failed to open /acct/uid_10021/pid_6983/cgroup.procs: No such file or directory
,I/ActivityManager(  962): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7240 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 7240): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  962): Message: 20
D/BluetoothManagerService(  962): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c611df1:true
,D/BluetoothAdapterService(151581155)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@214943d1
D/BluetoothAdapterService(151581155)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@214943d1
I/ActivityManager(  962): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7258 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7240): Create singleton instance
,D/UEI.SmartControl( 7258): Quickset Services start...
I/UEI.SmartControl( 7258): Manufacture = LGE
D/UEI.SmartControl( 7258): File observer start...
E/UEI.SmartControl( 7258): IR Port is disabled: false
D/UEI.SmartControl( 7258): Starting file observer...
D/UEI.SmartControl( 7258): Extracting JNI libs...
,D/UEI.SmartControl( 7258): --- this system supports 32-bit or 64-bit only
I/AudioManager( 7240): getMode name:com.lge.qremote
,I/AppUp4:CustModeStarterReceiver( 7038): onReceive
I/AppUp4:CustModeStarterReceiver( 7038): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 7038): Context : android.app.ReceiverRestrictedContext@2db32874
D/AppUp4:CustFacade( 7038): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7038): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7038): begin check event
I/AppUp4:CustModeStarterReceiver( 7038): Event For Nothing, skip.
D/UEI.SmartControl( 7258): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7258): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7258): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/ActivityManager(  962): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7283 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,V/AlarmManager(  962): RTC_WAKEUP set : Alarm{1d6451ae type 0 when 1455019798009 com.google.android.gms} when 1455019798009
,I/UEI.SmartControl( 7258): --- Selecting new region: 2
,I/UEI.SmartControl( 7258): -- Running on KitKat(19) and above! JNI will be used.
I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
D/UEI.SmartControl( 7258): Platform has CIR...
D/UEI.SmartControl( 7258): NO CIR support, need to check package...
I/UEI.SmartControl( 7258): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7258): QS Service created
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/ActivityManager(  962): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7308 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  962): RTC_WAKEUP set : Alarm{2f2dfb4f type 0 when 1455019800000 com.android.vending} when 1455019800000
,I/[SystemUI]DateView( 1375): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ActivityManager(  962): Process com.google.android.setupwizard (pid 6709) has died
,I/NotificationManager( 7095): com.google.android.talk: cancel(8) by com.google.android.talk
,D/WeatherService( 2691): 2 : TimeTick Intent has been received, Time(hour:min:sec) 13:10:0
D/WeatherService( 2691): 2 : TimeTick Intent And Screen On
D/WeatherService( 2691): 2 : SDK version : 21
W/ActivityManager(  962): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2691): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2691): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2691): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2691): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2691): 2 : This is isUpdating : false
D/WeatherService( 2691): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2691): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2691): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2691): 2 : Fixed theme : optimus
D/WeatherReflect( 2691): 2 : Map key string is -2
,E/UEI.SmartControl( 7258): QS start get config
W/ResourcesManager( 7095): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7095): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 7283): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7283): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7283): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,D/lim     ( 2691): 2 : time = 13:10
I/WeatherReflect( 2691): Model Name : LG-D722
D/WeatherTheme( 2691): 2 : Different view - status_min_formatted : 09 != 10
D/WeatherTheme( 2691): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2691): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2691): strTheme: com.lge.launcher2.theme.optimus
,D/Theme   ( 2691): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2691): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2691): currentPackage=com.lge.sizechangable.weather.theme.optimus
D/UEI.SmartControl( 7258): Loading JNI Libs...
D/UEI.SmartControl( 7258):  configuring local db...
,D/Weather4x2_optimus( 2691): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2691): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2691): forecast size is 0
D/Theme   ( 2691): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2691): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2691): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2691): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2691): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2691): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2691): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2691): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2691): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2691): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2691): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2691): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2691): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2691): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2691): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2691): url is : null
D/Theme   ( 2691): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2691): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2691): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2691): 2 : update view, appWidgetId: 2
D/WeatherService( 2691): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 13:10:0
,V/JNIHelp ( 7095): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/Finsky  ( 7308): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/AppConfig( 7283): Total System Memory = 906309632
I/GalleryUtils( 7283): Application Heap = 96 MB
,W/System  ( 7095): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7095): Installed default security provider GmsCore_OpenSSL
I/AppConfig( 7283): App Tier : NOT_DEF
D/SystemHelper( 7283): region [EU], country [EU], operator [OPEN], sub-operator []
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/ActivityManager(  962): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7339 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,D/AlertService( 6921): Beginning updateAlertNotification
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,D/UEI.SmartControl( 7258):  ---- Has DB8: true
D/UEI.SmartControl( 7258): QS start statue = true Error code = 0
,D/UEI.SmartControl( 7258): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7258): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7258): IRRCDataComm has AudioManager!!!!.
I/ActivityManager(  962): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7358 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/irrc_jni( 7258): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7258): IrrcClient ++ 
D/irrcClient( 7258): getIrrcService ++ 
D/irrcClient( 7258): getIrrcService -- 
D/irrcClient( 7258): IrrcClient -- 
W/irrc_jni( 7258): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7258): Services init done
,I/UEI.SmartControl( 7258): Device manager: loading config....
D/UEI.SmartControl( 7258): QS Service init finished
D/UEI.SmartControl( 7258): QS Service version name: 0.1.73
,D/UEI.SmartControl( 7258): QS Service version code: 1073
D/UEI.SmartControl( 7258): Config is loaded...
D/UEI.SmartControl( 7258): Service requested: Control
D/UEI.SmartControl( 7258): -----IControl: 11
,D/UEI.SmartControl( 7258): Internal service binding...
D/UEI.SmartControl( 7258): Caller: com.lge.qremote
D/UEI.SmartControl( 7258): ------------ IControl registerCallback...
W/ResourcesManager( 7339): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
I/UEI.SmartControl( 7258): Registering callback...
D/UEI.SmartControl( 7258): -----IControl: 19
W/ResourcesManager( 7339): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/UEI.SmartControl( 7258): Caller: com.lge.qremote
I/UEI.SmartControl( 7258): Registering Services Ready callback...
I/UEI.SmartControl( 7258): Notify client services are ready...
D/UEI.SmartControl( 7258): -----IControl: 8
D/Finsky  ( 7308): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
D/UEI.SmartControl( 7258): Caller: com.lge.qremote
,D/UEI.SmartControl( 7258):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7258): Notify AllClients services are ready: 0
W/ResourcesManager( 7358): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
W/Settings( 7308): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7308): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 7308): com.android.vending: cancel(-1050172287) by com.android.vending
,I/ActivityManager(  962): Killing 7006:com.lge.lgdmsclient/1000 (adj 15): empty #11
,D/Ads     ( 7308): Skipping gmscore version check
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/libprocessgroup(  962): failed to open /acct/uid_1000/pid_7006/cgroup.procs: No such file or directory
,D/Finsky  ( 7308): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7308): [1] Libraries$2.run: Finished loading 1 libraries.
D/CalendarProvider2( 7358): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@385f69ba
V/DownloadManager( 3211): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3211): created cursor android.database.sqlite.SQLiteCursor@1047e407 on behalf of 7308
D/CalendarProvider2( 7358): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 7358): Created com.android.providers.calendar.CalendarAlarmManager@e1d1847(com.android.providers.calendar.CalendarProvider2@385f69ba)
D/Finsky  ( 7308): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7308): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/AlertService( 6921): No fired or scheduled alerts
I/NotificationManager( 6921): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6921): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6921): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6921): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6921): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6921): com.android.calendar: cancel(5) by com.android.calendar
,I/NotificationManager( 6921): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6921): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6921): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6921): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6921): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6921): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6921): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6921): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6921): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6921): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6921): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6921): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6921): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6921): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6921): com.android.calendar: cancel(20) by com.android.calendar
I/SystemConfig( 7339): BUILD Country: EU
I/SystemConfig( 7339): BUILD Operator: OPEN
,D/Finsky  ( 7308): [920] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 7308): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager(  962): Process com.google.android.apps.magazines (pid 7126) has died
,D/AlertService( 6921): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,I/ActivityManager(  962): Killing 7068:com.lge.drmservice/u0a51 (adj 15): empty #11
I/SystemConfig( 7339): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7339): existFile = false
I/SystemConfig( 7339): canReadFile = false
I/SystemConfig( 7339): systemFeature RCS result false
D/SystemConfig( 7339): refreshRcsSupport() :false
I/ActivityManager(  962): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7394 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  962): Killing 7194:com.android.chrome/u0a48 (adj 15): empty #11
W/libprocessgroup(  962): failed to open /acct/uid_10051/pid_7068/cgroup.procs: No such file or directory
,W/libprocessgroup(  962): failed to open /acct/uid_10048/pid_7194/cgroup.procs: No such file or directory
D/AlarmScheduler( 6921): No events found starting within 1 week.
I/ActivityManager(  962): Killing 6921:com.android.calendar/u0a13 (adj 15): empty #11
,I/LockScreenSettings( 7394): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,W/libprocessgroup(  962): failed to open /acct/uid_10013/pid_6921/cgroup.procs: No such file or directory
D/LockScreenSettings( 7394): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 7394): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7394): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7394): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7394): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/UpdateIcingCorporaServi( 1941): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  962): Killing 7240:com.lge.qremote/u0a106 (adj 15): empty #11
I/art     ( 7216): CheckpointMarkThreadRoots callback created = 0xb0519050
,I/art     ( 7216): CheckpointMarkThreadRoots callback created = 0xb0519030
,I/UpdateIcingCorporaServi( 1941): UpdateCorporaTask done [took 72 ms] updated apps [took 72 ms] 
W/libprocessgroup(  962): failed to open /acct/uid_10106/pid_7240/cgroup.procs: No such file or directory
,D/PackageBroadcastService( 5653): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 5653): Null package name or gms related package.  Ignoreing.
D/CalendarProviderBroadcastReceiver( 7358): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
,D/CalendarProviderBroadcastReceiver( 7358): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 7358): CalendarProviderIntentService.onCreate()
,I/Icing   ( 5653): updateResources: need to parse f{com.google.android.gms}
D/CalendarProvider2( 7358): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 7358): [getOrCreateCalendarAlarmManager]
I/ActivityManager(  962): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7430 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 7430): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  962): Message: 20
D/BluetoothManagerService(  962): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2aac9e79:true
,D/BluetoothAdapterService(151581155)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@214943d1
D/BluetoothAdapterService(151581155)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@214943d1
I/art     (  962): Explicit concurrent mark sweep GC freed 25778(1177KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.078ms total 148.152ms
,D/CalendarProvider2( 7358): [IntentService] Release Lock
D/CalendarProvider2( 7358): CalendarProviderIntentService.onDestroy()
V/LGMDMManager( 7430): Create singleton instance
,I/AudioManager( 7430): getMode name:com.lge.qremote
,D/UEI.SmartControl( 7258): -----IControl: 11
,D/UEI.SmartControl( 7258): Caller: com.lge.qremote
D/UEI.SmartControl( 7258): ------------ IControl registerCallback...
I/UEI.SmartControl( 7258): Registering callback...
D/UEI.SmartControl( 7258): -----IControl: 19
D/UEI.SmartControl( 7258): Caller: com.lge.qremote
I/UEI.SmartControl( 7258): Registering Services Ready callback...
I/UEI.SmartControl( 7258): Notify client services are ready...
I/AudioManager( 7430): getMode name:com.lge.qremote
D/UEI.SmartControl( 7258): -----IControl: 8
,D/UEI.SmartControl( 7258): Caller: com.lge.qremote
I/ActivityManager(  962): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7451 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  962): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 7451): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,W/GAV2    ( 7451): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ActivityManager(  962): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 7451): Error finding the version of the Email provider.....
E/Gmail   ( 7451): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7451): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7451): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7451): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7451): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7451): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7451): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7451): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 7451): We do not support migrating this version of the Email provider.
,W/ActivityManager(  962): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 7451): getAccountsCursor
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WearableService( 1733): callingUid 10006, callindPid: 1733
,E/MDM     ( 1733): [84] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ActivityManager(  962): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/ActivityManager(  962): Killing 7038:com.lge.appbox.client/u0a11 (adj 15): empty #11
,D/LocationInitializer( 5653): Restart initialization of location
I/Gmail   ( 7451): Observing account changes for notifications
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/libprocessgroup(  962): failed to open /acct/uid_10011/pid_7038/cgroup.procs: No such file or directory
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
,W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
,D/Finsky  ( 7308): [925] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,I/ActivityManager(  962): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7512 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  962): android: cancelAsUser(2) by android
,I/Gmail   ( 7451): notifyAccountChanged
,I/Gmail   ( 7451): getAccountsCursor
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 7451): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 7451): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/PhoneMonitor( 7512): Register our PhoneStateListener
,I/NotificationManager( 7095): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 7308): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7308): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7308): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7308): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  278): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  278): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
I/Gmail   ( 7451): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 7451): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Icing   ( 5653): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/PhoneMonitor( 7512): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7512): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7512): [parse] Load xml
V/TelephonyAutoProfiling( 7512): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7512): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,E/MDM     ( 1733): [124] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/PhoneMonitor( 7512): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,D/LocationInitializer( 5653): Restart initialization of location
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 7308): propertyValue:false
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinService( 5653): Checkin interval check for package: unspecified last checkin: 1455019768061 min interval config: 0 actual interval: 34548
I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
,I/CheckinService( 5653): Checking schedule, now: 1455019802636 next: 1455019798009
I/CheckinService( 5653): active receiver: enabled
,I/Icing   ( 5653): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/CheckinService( 5653): Preparing to send checkin request
I/AudioManager( 7430): getMode name:com.lge.qremote
I/CheckinService( 5653): Checkin interval check for package: unspecified last checkin: 1455019768061 min interval config: 0 actual interval: 34627
,I/AudioManager( 7430): getMode name:com.lge.qremote
I/art     ( 7095): WaitForGcToComplete blocked for 44.235ms for cause HomogeneousSpaceCompact
,I/AudioManager( 7430): getMode name:com.lge.qremote
I/AudioManager( 7430): getMode name:com.lge.qremote
,I/art     ( 3954): Explicit concurrent mark sweep GC freed 3068(124KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.377ms total 36.007ms
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/ContextImpl( 3599): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
I/EventLogService( 5653): Accumulating logs since 1455019758617
,I/AudioManager( 7430): getMode name:com.lge.qremote
,I/AudioManager( 7430): getMode name:com.lge.qremote
,I/Gmail   ( 7451): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/art     ( 7095): Attempt to remove local handle scope entry from IRT, ignoring
,D/libc-netbsd( 7095): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7095): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
E/BandwidthController(  278): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  278): App 10061 tries DNS query. Accept family:2 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/ActivityManager(  962): Killing 7283:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/libprocessgroup(  962): failed to open /acct/uid_10023/pid_7283/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 5653): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 5653): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  962): Explicit concurrent mark sweep GC freed 13560(651KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.228ms total 139.377ms
,I/ActivityManager(  962): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7576 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 21.130ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 21.283ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 24.351ms
,W/ResourcesManager( 7576): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7576): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 7576): VM with version 2.1.0 has multidex support
I/MultiDex( 7576): install
I/MultiDex( 7576): VM has multidex support, MultiDex support library is disabled.
,E/Babel   ( 7095): Invalid server experiment type 3 for BabelExperiment{id='dd8c17d9', experimentType=0, defaultBoolean=null, defaultLong=null}
,E/Babel   ( 7095): Invalid server experiment type 3 for BabelExperiment{id='6412be77', experimentType=0, defaultBoolean=null, defaultLong=null}
V/JNIHelp ( 7576): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 115251935691; DSPS: 3867833; Offset : -2795225294
W/ActivityThread( 7576): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7576): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@df0feb1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7576): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 7576): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7576): com.google.android.gms: cancel(39789) by com.google.android.gms
E/MDM     ( 1733): [149] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 5653): Restart initialization of location
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1733): No location to return for getLastLocation()
,W/FusedLocationProvider( 1733): location=null
I/art     ( 7576): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7576): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7095): Note: end time exceeds epoch: 
,D/NativeLibraryUtils( 7576): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  282): Instantiating CDM.
,I/WVCdm   (  282): CdmEngine::OpenSession
,I/WVCdm   (  282): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  282): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/WVCdm   (  282): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  282): L1 library not specified. Falling Back to L3
I/WVCdm   (  282): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  282): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  282): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  282): CdmEngine::GenerateKeyRequest
D/WVCdm   (  282): PrepareKeyRequest: nonce=3030352002
I/art     ( 7576): CheckpointMarkThreadRoots callback created = 0xb04ccec0
,I/art     ( 7576): CheckpointMarkThreadRoots callback created = 0xb04cceb0
,I/dex2oat ( 7620): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7620): dex2oat took 136.338ms (threads: 4)
,I/Adreno-EGL( 7576): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7576): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7576): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7576): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7576): Remote Branch: 
I/Adreno-EGL( 7576): Local Patches: 
I/Adreno-EGL( 7576): Reconstruct Branch: 
,I/WVCdm   (  282): CdmEngine::OpenSession
,I/MusicWidget( 2660): mDelayedStopHandler : unbind
,I/MusicBrowser( 2096): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
I/MusicBrowser( 2096): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2096): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2096): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2096): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2096): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2096): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2096): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,I/MediaFocusControl(  962):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@9cd4c0dcom.lge.music.MediaPlaybackService$6@18a387c2
D/MusicBrowser( 2096): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2096): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2096): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2096): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2096): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@b1457e0
I/MusicBrowser( 2096): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2096): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2096): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2096): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2096): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2096): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2096): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2096): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2096): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2096): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2096): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,I/MusicBrowser( 2096): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2096): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2096): reset
V/MediaPlayer[Native]( 2096): setListener
V/MediaPlayer[Native]( 2096): disconnect
V/MediaPlayer[Native]( 2096): destructor
,V/AudioFlinger(  282): releasing 19 from 2096 for -1
V/AudioFlinger(  282):  decremented refcount to 0
V/AudioFlinger(  282): purging stale effects
V/MediaPlayer[Native]( 2096): disconnect
D/MusicBrowser( 2096): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2096): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2096): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2096): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2096): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2096): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2096): [SmartShareManagerClient] unregisterListener: 319429075
W/SmartShareClient( 2096): [SmartShareManagerClient] unregisterListener invalid listener: 319429075
I/SmartShareClient( 2096): [SmartShareManagerClient] terminate service: 2096/MediaPlaybackService/277505926
E/HomeCloudIF( 2096): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2096): [SmartShareManagerClient] unbindService context:android.app.Application@3b5d7910
,V/CloudHub( 2096): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
,V/CloudHub( 2096): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2096): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2096): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2096): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  962): Killing 7339:com.android.contacts/u0a18 (adj 15): empty #11
I/CloudHub( 2096): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29996
,W/libprocessgroup(  962): failed to open /acct/uid_10018/pid_7339/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 7258): Internal timer expired: 1
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/WVCdm   (  282): CdmEngine::CloseSession
,I/WVCdm   (  282): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  282): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  282): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  282): CdmEngine::GenerateKeyRequest
D/WVCdm   (  282): PrepareKeyRequest: nonce=154974742
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/ThermalEngine(  293): Sensor:pa_therm0:33000 mC
,I/GAV2    ( 7451): Thread[GAThread,5,main]: No campaign data found.
,I/GAv4-SVC( 5653): Google Analytics 8.4.89 is starting up.
,I/WVCdm   (  282): CdmEngine::CloseSession
I/WVCdm   (  282): L3 Terminate.
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
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
,I/ActivityManager(  962): Killing 7394:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,I/CheckinRequestBuilder( 5653): Classify the device as Phone.
,W/libprocessgroup(  962): failed to open /acct/uid_10069/pid_7394/cgroup.procs: No such file or directory
D/libc-netbsd( 5653): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5653): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5653): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5653): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
,D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 5653): propertyValue:false
D/libc-netbsd( 5653): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5653): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5653): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5653): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5653): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5653): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 5653): Sending checkin request (9760 bytes)
,I/CheckinRequestBuilder( 5653): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5653): Failed to find provider info for com.google.android.wearable.settings
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinRequestBuilder( 5653): Classify the device as Phone.
,I/CheckinTask( 5653): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5653): Checking schedule, now: 1455019809844 next: 1455547058838
I/CheckinService( 5653): active receiver: disabled
,I/CheckinService( 5653): Checking schedule, now: 1455019809876 next: 1455547058838
I/CheckinService( 5653): active receiver: disabled
,D/CheckinService( 5653): Recording last checkin time for package unspecified as 1455019809886
,I/ActivityManager(  962): Killing 7216:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  962): failed to open /acct/uid_10086/pid_7216/cgroup.procs: No such file or directory
,V/SetupWizard( 7512): Connected to Gservices successfully
I/ActivityManager(  962): Killing 7358:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/libprocessgroup(  962): failed to open /acct/uid_10014/pid_7358/cgroup.procs: No such file or directory
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  293): Sensor:pa_therm0:33000 mC
,I/QCNEJ   ( 1829): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1829): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-68 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 13:10:12.283 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/QCNEJ   ( 1829): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QPairHandler( 1375): onReceive = android.intent.action.PACKAGE_CHANGED
I/InputReader(  962): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QSlideListController( 1375): onReceive = android.intent.action.PACKAGE_CHANGED
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
,W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1375): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/[LGHome]EVENT( 1879): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/administrator(  962): Handling package changes for user 0
,I/ActivityManager(  962): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7701 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/NotificationManager( 7095): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 7095): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7095): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/AppUp4:AppBoxCP( 7701): onCreate
,W/AppUp4:DB( 7701):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7701):  setFingerPrint start
,I/AppUp4:DB( 7701):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 7701):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7701):  SDK version = 0
I/AppUp4:DB( 7701):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7701): AppBoxApplication onCreate()
,I/AppUp4:CustModeStarterReceiver( 7701): onReceive
I/AppUp4:CustModeStarterReceiver( 7701): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 7701): Context : android.app.ReceiverRestrictedContext@33f08061
,D/AppUp4:CustFacade( 7701): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7701): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7701): begin check event
I/AppUp4:CustModeStarterReceiver( 7701): Event For Nothing, skip.
I/ActivityManager(  962): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7722 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager(  962): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/NotificationService(  962): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  962): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  962): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  962): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  962): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  962): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@20da8d6
,D/LCardEmulationManager( 1788): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1788): getDefaultRoute
,W/ResourcesManager( 7722): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7722): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7722): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,W/ResourceType(  962): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/ActivityManager(  962): Process com.android.vending (pid 7308) has died
,I/[LGHome]EVENT( 1879): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1733): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/AppConfig( 7722): Total System Memory = 906309632
,I/GalleryUtils( 7722): Application Heap = 96 MB
D/LocationProviderProxy(  962): applying state to connected service
I/AppConfig( 7722): App Tier : NOT_DEF
,D/SystemHelper( 7722): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager(  962): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7743 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/art     ( 1733): Explicit concurrent mark sweep GC freed 34373(2MB) AllocSpace objects, 30(480KB) LOS objects, 40% free, 13MB/22MB, paused 1.414ms total 130.366ms
,W/ResourcesManager( 7743): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7743): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7743): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7743): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7743): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/ActivityManager(  962): Process com.google.android.gm (pid 7451) has died
,I/SystemConfig( 7743): BUILD Country: EU
I/SystemConfig( 7743): BUILD Operator: OPEN
,I/ActivityManager(  962): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7768 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 7743): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7743): existFile = false
,I/SystemConfig( 7743): canReadFile = false
I/SystemConfig( 7743): systemFeature RCS result false
D/SystemConfig( 7743): refreshRcsSupport() :false
,I/LockScreenSettings( 7768): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7768): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7768): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,D/LockScreenSettings( 7768): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7768): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7768): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  962): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7785 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  962): Killing 2096:com.lge.music/u0a28 (adj 15): empty #11
,V/AudioFlinger(  282): 2096 died, releasing its sessions
V/AudioFlinger(  282):  pid 1752 @ 0
,V/AudioFlinger(  282):  pid 3186 @ 1
V/AudioFlinger(  282):  pid 3186 @ 2
W/libprocessgroup(  962): failed to open /acct/uid_10028/pid_2096/cgroup.procs: No such file or directory
,W/ResourcesManager( 7785): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/UpdateIcingCorporaServi( 1941): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  962): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7810 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  962): Killing 7258:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1941): UpdateCorporaTask done [took 58 ms] updated apps [took 58 ms] 
,W/libprocessgroup(  962): failed to open /acct/uid_10089/pid_7258/cgroup.procs: No such file or directory
,W/ActivityManager(  962): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
W/System.err( 7430): android.os.DeadObjectException
W/System.err( 7430): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7430): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7430): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7430): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
,W/System.err( 7430): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7430): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7430): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7430): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7430): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7430): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7430): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7430): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7430): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7430): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7430): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7430): android.os.DeadObjectException
W/System.err( 7430): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7430): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7430): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7430): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7430): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7430): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7430): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7430): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7430): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7430): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7430): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7430): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7430): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7430): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7430): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/ActivityManager(  962): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7827 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 7827): Quickset Services start...
I/UEI.SmartControl( 7827): Manufacture = LGE
D/UEI.SmartControl( 7827): File observer start...
,E/UEI.SmartControl( 7827): IR Port is disabled: false
,D/UEI.SmartControl( 7827): Starting file observer...
D/UEI.SmartControl( 7827): Extracting JNI libs...
D/UEI.SmartControl( 7827): --- this system supports 32-bit or 64-bit only
D/Finsky  ( 7810): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/UEI.SmartControl( 7827): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7827): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7827): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7827): --- Selecting new region: 2
,I/UEI.SmartControl( 7827): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7827): Platform has CIR...
D/UEI.SmartControl( 7827): NO CIR support, need to check package...
I/UEI.SmartControl( 7827): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7827): QS Service created
,E/UEI.SmartControl( 7827): QS start get config
,D/UEI.SmartControl( 7827): Loading JNI Libs...
,D/UEI.SmartControl( 7827):  configuring local db...
,D/Finsky  ( 7810): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7810): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7810): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7810): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3211): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,D/UEI.SmartControl( 7827):  ---- Has DB8: true
,D/UEI.SmartControl( 7827): QS start statue = true Error code = 0
D/UEI.SmartControl( 7827): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7827): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 7827): IRRCDataComm has AudioManager!!!!.
I/art     (  962): Explicit concurrent mark sweep GC freed 30739(1543KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.251ms total 163.559ms
,V/DownloadManager( 3211): created cursor android.database.sqlite.SQLiteCursor@3a806934 on behalf of 7810
W/irrc_jni( 7827): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7827): IrrcClient ++ 
D/irrcClient( 7827): getIrrcService ++ 
D/irrcClient( 7827): getIrrcService -- 
D/irrcClient( 7827): IrrcClient -- 
W/irrc_jni( 7827): IRRCPlayer_nativeInit -- 
D/Finsky  ( 7810): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7810): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 7810): Skipping gmscore version check
,D/UEI.SmartControl( 7827): Services init done
D/UEI.SmartControl( 7827): QS Service init finished
D/UEI.SmartControl( 7827): QS Service version name: 0.1.73
D/UEI.SmartControl( 7827): QS Service version code: 1073
D/UEI.SmartControl( 7827): Service requested: Control
I/ActivityManager(  962): Killing 7430:com.lge.qremote/u0a106 (adj 15): empty #11
,I/UEI.SmartControl( 7827): Device manager: loading config....
D/UEI.SmartControl( 7827): Config is loaded...
D/UEI.SmartControl( 7827): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 7827):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 7827): Notify AllClients services are ready: 0
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/libprocessgroup(  962): failed to open /acct/uid_10106/pid_7430/cgroup.procs: No such file or directory
D/Finsky  ( 7810): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/UEI.SmartControl( 7827): Internal service binding...
D/PackageBroadcastService( 5653): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 5653): Null package name or gms related package.  Ignoreing.
,D/Finsky  ( 7810): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/QCNEJ   ( 1829): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/QCNEJ   ( 1829): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 13:10:15.284 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/Icing   ( 5653): updateResources: need to parse f{com.google.android.gms}
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1829): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1829): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 295, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/charger_monitor(  488): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/WifiController(  962): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
,I/Icing   ( 5653): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 5653): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  962): Killing 7512:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  962): failed to open /acct/uid_10038/pid_7512/cgroup.procs: No such file or directory
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ActivityManager(  962): Killing 7576:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  962): failed to open /acct/uid_10006/pid_7576/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/UEI.SmartControl( 7827): Internal timer expired: 1
,D/UEI.SmartControl( 7827): Service.onUnbind: IControl
D/UEI.SmartControl( 7827): Service.onDestroy
W/System.err( 7827): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@908f1e3
W/System.err( 7827): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 7827): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 7827): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 7827): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 7827): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 7827): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2983)
W/System.err( 7827): 	at android.app.ActivityThread.access$2200(ActivityThread.java:155)
W/System.err( 7827): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1426)
W/System.err( 7827): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7827): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7827): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7827): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7827): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7827): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7827): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7827): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@908f1e3
D/UEI.SmartControl( 7827): Shutdown IRRCPlayer... 
W/irrc_jni( 7827): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 7827): ~IrrcClient ++ 
D/irrcClient( 7827): ~IrrcClient -- 
W/irrc_jni( 7827): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 7827): Blaster closed
D/UEI.SmartControl( 7827): Blaster closed
D/UEI.SmartControl( 7827): Shut down QS...
,D/UEI.SmartControl( 7827): Stopped file observer...
I/UEI.SmartControl( 7827): QS lib stop result = true
D/UEI.SmartControl( 7827): QS shutdown complete
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 135253024434; DSPS: 4523228; Offset : -2795204459
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/AlarmManager(  962): ELAPSED_WAKEUP set : Alarm{37c85cd4 type 2 when 147030 com.google.android.gms} when 147030
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1733): Vacuum at: now=1455019835629 tag=VacuumService
,I/PhenotypeConfigurator( 1733): Scheduling Phenotype for one-off execution 9344 seconds from now (1455019836082)
,D/GetConfigurationSnapshotOperation( 1733): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1733): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1733): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  962): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 1733): propertyValue:false
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/LocationManagerService(  962): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LocationManagerService(  962): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/PowerManagerService(  962): ALS enabled for SRE
,D/PowerManagerServiceEx(  962): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (28628 ms ago)
D/qdlights(  962): set_light_backlight: 252
,D/qdlights(  962): set_light_backlight: 248
D/qdlights(  962): set_light_backlight: 245
,D/qdlights(  962): set_light_backlight: 242
,D/qdlights(  962): set_light_backlight: 238
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,D/qdlights(  962): set_light_backlight: 235
,D/qdlights(  962): set_light_backlight: 232
,D/qdlights(  962): set_light_backlight: 228
,D/qdlights(  962): set_light_backlight: 225
,D/qdlights(  962): set_light_backlight: 222
,D/qdlights(  962): set_light_backlight: 218
,D/qdlights(  962): set_light_backlight: 215
,D/qdlights(  962): set_light_backlight: 212
,D/qdlights(  962): set_light_backlight: 208
,D/qdlights(  962): set_light_backlight: 205
,D/qdlights(  962): set_light_backlight: 202
,D/qdlights(  962): set_light_backlight: 198
,D/qdlights(  962): set_light_backlight: 195
,D/qdlights(  962): set_light_backlight: 192
,D/qdlights(  962): set_light_backlight: 188
,D/qdlights(  962): set_light_backlight: 185
,D/qdlights(  962): set_light_backlight: 182
,D/qdlights(  962): set_light_backlight: 178
,D/qdlights(  962): set_light_backlight: 175
,D/qdlights(  962): set_light_backlight: 172
,D/qdlights(  962): set_light_backlight: 168
,D/qdlights(  962): set_light_backlight: 165
,D/qdlights(  962): set_light_backlight: 162
,D/qdlights(  962): set_light_backlight: 158
,D/qdlights(  962): set_light_backlight: 155
,D/qdlights(  962): set_light_backlight: 152
,D/qdlights(  962): set_light_backlight: 148
,D/qdlights(  962): set_light_backlight: 145
,D/qdlights(  962): set_light_backlight: 142
,D/qdlights(  962): set_light_backlight: 138
,D/qdlights(  962): set_light_backlight: 135
,D/qdlights(  962): set_light_backlight: 132
,D/qdlights(  962): set_light_backlight: 128
,D/qdlights(  962): set_light_backlight: 125
,D/qdlights(  962): set_light_backlight: 122
,D/qdlights(  962): set_light_backlight: 118
,D/qdlights(  962): set_light_backlight: 115
,D/qdlights(  962): set_light_backlight: 112
,D/qdlights(  962): set_light_backlight: 108
,D/qdlights(  962): set_light_backlight: 105
,D/LocationManagerService(  962): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/qdlights(  962): set_light_backlight: 102
,D/qdlights(  962): set_light_backlight: 98
,D/qdlights(  962): set_light_backlight: 95
,D/qdlights(  962): set_light_backlight: 92
,D/qdlights(  962): set_light_backlight: 88
,D/qdlights(  962): set_light_backlight: 85
,D/qdlights(  962): set_light_backlight: 82
,D/LocationManagerService(  962): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/qdlights(  962): set_light_backlight: 78
D/qdlights(  962): set_light_backlight: 75
,D/qdlights(  962): set_light_backlight: 72
,D/qdlights(  962): set_light_backlight: 68
,D/qdlights(  962): set_light_backlight: 65
,D/qdlights(  962): set_light_backlight: 62
,D/LocationManagerService(  962): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/qdlights(  962): set_light_backlight: 58
D/qdlights(  962): set_light_backlight: 55
,D/qdlights(  962): set_light_backlight: 52
,D/qdlights(  962): set_light_backlight: 48
,D/qdlights(  962): set_light_backlight: 45
,D/qdlights(  962): set_light_backlight: 42
,D/qdlights(  962): set_light_backlight: 38
,D/qdlights(  962): set_light_backlight: 35
,D/LocationManagerService(  962): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/qdlights(  962): set_light_backlight: 32
,D/qdlights(  962): set_light_backlight: 28
,D/qdlights(  962): set_light_backlight: 25
,D/qdlights(  962): set_light_backlight: 22
,D/qdlights(  962): set_light_backlight: 18
,D/qdlights(  962): set_light_backlight: 15
,D/LocationManagerService(  962): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/qdlights(  962): set_light_backlight: 12
,D/qdlights(  962): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 155253781249; DSPS: 5178613; Offset : -2795211078
,I/PowerManagerService(  962): ALS enabled for SRE
D/PowerManagerServiceEx(  962): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (35622 ms ago)
I/PowerManagerService(  962): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  962): ALS enabled for SRE
D/PowerManagerServiceEx(  962): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (35636 ms ago)
,W/ContextImpl(  962): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  962): Sleeping (uid 1000)...
,D/LPWGController(  962): [updateScreenState] screen on = false
D/LPWGController(  962): disable proximity sensor
,D/LPWGController(  962): enable proximity sensor
I/SensorManager(  962): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@3a8d4e9c] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  962): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  962): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  962): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  962): activate: handle is 48, enable
,V/sensors_hal_Ctx(  962): activate sensors is 1400000000000
D/sensors_hal_Thresh(  962): enable: handle=48
I/sensors_hal_SAM(  962): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  962): waitForResponse: timeout=1000
V/sensors_hal_SAM(  962): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  962): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  962): enable: Received response: 0
D/PowerManagerServiceEx(  962): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (35710 ms ago)
I/Adreno-EGL(  962): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  962): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  962): Build Date: 03/02/15 Mon
I/Adreno-EGL(  962): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  962): Remote Branch: 
I/Adreno-EGL(  962): Local Patches: 
I/Adreno-EGL(  962): Reconstruct Branch: 
,D/PermissionCache(  246): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1115 us)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/Sensors (  435): sns_pwr.c(273):acquiring wakelock
V/sensors_hal_SAM(  962): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,I/sensors_hal_SAM(  962): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  962): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  962): processInd: handle 48, count=1
V/sensors_hal_Thresh(  962): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  962): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  962): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  962): poll: count: 256
I/sensors_hal_Ctx(  962): poll: released wakelock sensor_ind
D/sensors_hal_Util(  962): waitForResponse: timeout=0
D/LPWGController(  962): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  962): current mode = 1  value = 1 1
I/LPWGController(  962): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  962): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  962): set_light_backlight: 0
,I/SensorManager(  962): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  962): activate: handle is 46, disable
V/sensors_hal_Ctx(  962): activate sensors is 1000000000000
D/sensors_hal_LP2(  962): enable: handle=46
D/sensors_hal_LP2(  962): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  962): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  246): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  246): hwc_blank: Blanking display: 0
I/DisplayManagerService(  962): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  962): Display changed displayId=0
V/sensors_hal_SAM(  962): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  962): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1752): Display #0 changed.
,D/qdhwcomposer(  246): hwc_blank: Done blanking display: 0
,I/qdhwcomposer(  246): handle_blank_event: dpy:0 panel power state: 0
D/SurfaceControl(  962): Excessive delay in setPowerMode(): 233ms
I/QCOM PowerHAL(  962): Got set_interactive hint
D/KeyguardViewMediator( 1375): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1375): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1334): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1375): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1375): handleNotifyScreenOff
,D/WifiServerServiceExt(  962): sendKtScanInterval  mRtspPlay : false
V/AudioFlinger(  282): setParameters(): io 0, keyvalue screen_state=on, calling pid 962
,D/SmartCoverViewMediator( 1334): notifyScreenOffLocked
D/SmartCoverViewMediator( 1334): handleNotifyScreenOFF
D/ScreenTurnOffBySensor( 1375): unregisterProximitySensor
I/WifiServerServiceExt(  962): set CMD_KT_SCAN_INTERVAL
D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=on
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
V/voice   (  282): voice_set_parameters: enter: screen_state=on
V/compress_voip(  282): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  282): voice_extn_compress_voip_set_parameters: exit
V/voice   (  282): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  282): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  282): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  282): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  282): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  282): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  282): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  282): adev_set_parameters: exit with code(0)
D/StatusBarWindowView( 1375): onScreenTurnedOff why = 3
,D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
,I/ActivityManager(  962): Process com.google.android.talk (pid 7095) has died
,D/GpsLocationProvider(  962): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1829): |CORE| sendScreenState: state:true
I/LEDService( 1805): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1805): stopPatternFlashing()
I/Cliptray Service( 1805): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
D/Cliptray Service( 1805): lockStatus = 0
D/LNfcService( 1788): action : android.intent.action.SCREEN_ON
I/LEDService( 1805): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
I/LEDService( 1805): updateLightsLocked : turn off led
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1805): RESTART MSG
,D/NfcServiceNXP( 1788): mScreenState : 3, mInProvisionMode : false
,D/NfcServiceNXP( 1788): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
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
D/SplitWindow(  962): check instance of lgWin Window{34d34c2b u0 SearchPanel}
,D/InputDispatcher(  962): Window went away: Window{726d84b u0 SearchPanel}
,I/[SystemUI]Clock( 1375): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1375): time changed, timezoneChanged : false
,D/Ulp_jni (  962): JNI:system_update. Event-0
,V/PhoneApp( 1752): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
D/WeatherService( 2691): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:10:45
,D/WeatherService( 2691): 2 : ACTION screen on
D/WeatherService( 2691): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2691): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2691): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:10:45
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): ACTION_SCREEN_ON
D/AppCleanupService( 4053): android.intent.action.SCREEN_ON
,V/AudioFlinger(  282): setParameters(): io 0, keyvalue screen_state=off, calling pid 962
D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=off
V/voice   (  282): voice_set_parameters: enter: screen_state=off
V/compress_voip(  282): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  282): voice_extn_compress_voip_set_parameters: exit
V/voice   (  282): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  282): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  282): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  282): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  282): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  282): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  282): adev_set_parameters: exit with code(0)
D/WifiController(  962): CMD_SCREEN_OFF 
D/WifiController(  962): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  962): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.SCREEN_OFF
I/Sensors (  435): sns_pwr.c(301):releasing wakelock
,I/QCNEJ   ( 1829): |CORE| sendScreenState: state:false
,I/LEDService( 1805): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1805): stopPatternFlashing()
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
I/LEDService( 1805): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
I/LEDService( 1805): updateLightsLocked : turn on led
E/LEDService( 1805): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1805): Can't handle this request of patternId:0
D/LEDHandler( 1805): RESTART MSG
D/VolumeVibrator( 1805): clear
I/Cliptray Service( 1805): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,D/LNfcService( 1788): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1788): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1879): [Launcher.java:1711:onReceive()]Screen Off
V/PhoneApp( 1752): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2691): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:10:45
D/WeatherService( 2691): 2 : ACTION screen off
D/WeatherService( 2691): 2 : TimeTick Receiver Unregister
D/WeatherService( 2691): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:10:45
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): ACTION_SCREEN_OFF
D/AppCleanupService( 4053): android.intent.action.SCREEN_OFF
D/AppCleanupService( 4053): AppUsageStatsSaveTask
,E/NxpNfcJni( 1788): getReconnectState = 0x0
,D/LCardEmulationManager( 1788): getHceAppCount hostAppNum : 0
,D/LCardEmulationManager( 1788): getDefaultRoute
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
E/NxpNfcJni( 1788): getReconnectState = 0x0
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,D/KeyguardViewMediator( 1375): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  962): ELAPSED_WAKEUP set : Alarm{336eb888 type 2 when 161586 com.android.systemui} when 161586
,D/PhoneUtils( 1752): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1752): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1752): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1752): getCallState : 0
,D/PhoneUtils( 1752): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1752): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1752): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1375): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1375): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 175254452491; DSPS: 5833995; Offset : -2795210754
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/PowerManagerServiceEx(  962): acquireWakeLockInternal: lock=596521505, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=962
,V/AlarmManager(  962): ELAPSED_WAKEUP set : Alarm{1d579646 type 2 when 182222 android} when 182222
D/PowerManagerServiceEx(  962): releaseWakeLockInternal: lock=596521505 [*alarm*], flags=0x0
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ClearcutLoggerApiImpl( 1733): disconnect managed GoogleApiClient
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 291
I/QCNEJ   ( 1829): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1829): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 291, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  962): battery changed pluggedType: 2
V/AlarmManager(  962): ELAPSED_WAKEUP set : Alarm{2e388007 type 2 when 187513 com.google.android.gms} when 187513
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 195255203161; DSPS: 6489380; Offset : -2795222997
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 215255937944; DSPS: 7144764; Offset : -2795220584
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 235256607676; DSPS: 7800146; Offset : -2795222291
,D/PowerManagerServiceEx(  962): acquireWakeLockInternal: lock=596521505, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=962
,V/AlarmManager(  962): RTC_WAKEUP set : Alarm{317ad534 type 0 when 1455019926495 com.google.android.gms} when 1455019926495
D/PowerManagerServiceEx(  962): releaseWakeLockInternal: lock=596521505 [*alarm*], flags=0x0
,I/EventLogService( 5653): Aggregate from 1455019802993 (log), 1455018126411 (data)
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
,I/QCNEJ   ( 1829): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1829): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 289, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  962): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 255257356523; DSPS: 8455530; Offset : -2795205580
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 275258095109; DSPS: 9110914; Offset : -2795199650
,I/jxcore-log( 5297): --= Surplus to requirements =--
I/jxcore-log( 5297): 
I/jxcore-log( 5297): ****TEST TOOK:  ms ****
I/jxcore-log( 5297): 
I/jxcore-log( 5297): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5297): 
,D/AndroidRuntime( 8033): 
D/AndroidRuntime( 8033): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8033): CheckJNI is OFF
,D/AndroidRuntime( 8033): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  962): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  962): Killing 5297:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
,W/PackageSettings(  962): Skipping PackageSetting{52375c1 com.example.hello/10317} due to missing metadata
,I/WindowState(  962): WIN DEATH: Window{1ce425f0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  962): Focus left window: Window{1ce425f0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  962): Window went away: Window{1ce425f0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  962):   Force finishing activity ActivityRecord{1d2e808c u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  962): Display changed displayId=0
D/DSDPConnection( 1752): Display #0 changed.
,W/ActivityManager(  962): Spurious death for ProcessRecord{359a0459 5297:com.test.thalitest/u0a316}, curProc for 5297: null
,I/ActivityManager(  962): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
,I/ActivityManager(  962):   Force finishing activity ActivityRecord{1d2e808c u0 com.test.thalitest/.MainActivity t222 f}
W/ActivityManager(  962): Duplicate finish request for ActivityRecord{1d2e808c u0 com.test.thalitest/.MainActivity t222 f}
,D/KeyguardModel( 1375): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 1879): [Launcher.java:5203:onStart()]onStart
I/QCNEJ   ( 1829): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,W/GeofencerStateMachine( 1733): Ignoring removeGeofence because network location is disabled.
I/InputReader(  962): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]EVENT( 1879): [Launcher.java:776:onResume()]onResume
,I/ActivityManager(  962): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8066 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
W/System.err( 3599): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3599): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3599): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3599): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
,W/System.err( 3599): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3599): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3599): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3599): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3599): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3599): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3599): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3599): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/art     ( 1941): Explicit concurrent mark sweep GC freed 21513(1256KB) AllocSpace objects, 3(71KB) LOS objects, 39% free, 12MB/21MB, paused 2.054ms total 139.889ms
,I/[LGHome]EVENT( 1879): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
,I/[SystemUI]QSlideListController( 1375): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]Launcher.Model( 1879): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/[LGHome]LGActivityUtil( 1879): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1879): [Launcher.java:929:onResume()]onResume end
I/Activity( 1879): Activity.onPostResume() called 
,I/art     ( 5653): Explicit concurrent mark sweep GC freed 23906(1396KB) AllocSpace objects, 6(96KB) LOS objects, 24% free, 13MB/18MB, paused 7.325ms total 177.109ms
D/KeyguardModel( 1375): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1375): createShortcutInfo...
D/KeyguardModel( 1375): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1375): createShortcutInfo...
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.android.mms: Resource ID #0x0
W/SQLiteConnectionPool( 5653): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/[LGHome]EVENT( 1879): [Launcher.java:986:onPause()]onPause
D/KeyguardModel( 1375): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1375): createShortcutInfo...
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,D/KeyguardModel( 1375): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1375): createShortcutInfo...
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1375): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1375): createShortcutInfo...
I/art     (  962): Explicit concurrent mark sweep GC freed 52251(2MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 5.401ms total 220.319ms
,I/art     (  962): WaitForGcToComplete blocked for 207.107ms for cause Explicit
W/[LGHome]LGWallpaperInfo( 1879): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1879): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1375): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1375): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,D/KeyguardModel( 1375): handleShortcutListChanged...
,D/InputDispatcher(  962): Focus entered window: Window{409ee66 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/WindowManager(  962): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
I/SystemUI[Framework](  962): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
I/[SystemUI]NavigationThemeResource( 1375): notify navigation bar color(0x0)
,I/[SystemUI]NavigationThemeResource( 1375): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1375):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1375): , Keyguard show=false, IME shown=false, Panel expanded=false
D/KeyguardModel( 1375): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1375): createShortcutInfo...
W/PhoneWindowManagerEx(  962): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  962): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  962): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  962): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1f63a068,  pkg=WindowManager.LayoutParams
D/KeyguardModel( 1375): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1375): createShortcutInfo...
I/SystemUI[Framework](  962): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1375): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1375): createShortcutInfo...
,W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1375): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1375): createShortcutInfo...
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1375): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1375): createShortcutInfo...
D/administrator(  962): Handling package changes for user 0
I/[LGHome]EVENT( 1879): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1879): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
,I/[LGHome]EVENT( 1879): [Launcher.java:5214:onStop()]onStop
D/KeyguardModel( 1375): handleShortcutListChanged...
I/[LGHome]EVENT( 1879): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1879): [setNavigationBarColor] color=0x 0
W/ResourcesManager( 8066): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8066): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8066): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/LGEmail ( 8066): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 8066): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,W/InputMethodManagerService(  962): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  962): Got RemoteException sending setActive(false) notification to pid 5297 uid 10316
,I/art     (  962): Explicit concurrent mark sweep GC freed 6209(346KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 6.180ms total 311.374ms
,I/[LGHome]Launcher.Model( 1879): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
I/art     ( 1788): Background sticky concurrent mark sweep GC freed 54664(3MB) AllocSpace objects, 0(0B) LOS objects, 20% free, 11MB/14MB, paused 5.315ms total 35.699ms
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/Timeline(  962): Timeline: Activity_windows_visible id: ActivityRecord{19b17f5 u0 com.lge.launcher2/.Launcher t221} time:278401
I/NotificationService(  962): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,D/BackupManagerService(  962): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  962): Receieved: android.intent.action.PACKAGE_REMOVED
I/PackageChangeReceiver( 8066): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,D/TaskPersister(  962): removeObsoleteFile: deleting file=222_task.xml
W/IInputConnectionWrapper( 1879): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1879): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,E/b       ( 1622): Unable to connect to the editor to retrieve text... will retry later
D/LCardEmulationManager( 1788): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1788): getDefaultRoute
,D/AppUp4:PreloadHelper( 7701): added Exclude : com.test.thalitest
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1879): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1879): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
D/AndroidRuntime( 8033): Shutting down VM
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,W/IInputConnectionWrapper( 1879): getTextAfterCursor on inactive InputConnection
,I/[LGHome]Launcher.Model( 1879): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  962): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8092 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
,W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
,W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1879): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,W/ResourcesManager(  962): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1879): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 8092): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 8092): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 8092): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8092): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 8092): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/ResourceType(  962): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1879): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1879): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]EVENT( 1879): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/[LGHome]Launcher( 1879): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/SQLiteDatabase( 8092): Failed to open database '/data/data/com.android.settings/databases/vibrateuserpattern.db'.
E/SQLiteDatabase( 8092): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8092): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/SQLiteDatabase( 8092): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/SQLiteDatabase( 8092): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/SQLiteDatabase( 8092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/SQLiteDatabase( 8092): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8092): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/SQLiteDatabase( 8092): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/SQLiteDatabase( 8092): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/SQLiteDatabase( 8092): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 8092): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 8092): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8092): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 8092): 	at com.android.settings.vibratecreation.VibrateUserPatternProvider.onCreate(VibrateUserPatternProvider.java:243)
E/SQLiteDatabase( 8092): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
E/SQLiteDatabase( 8092): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
E/SQLiteDatabase( 8092): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
E/SQLiteDatabase( 8092): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
E/SQLiteDatabase( 8092): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
E/SQLiteDatabase( 8092): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
E/SQLiteDatabase( 8092): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 8092): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8092): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 8092): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/SQLiteDatabase( 8092): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 8092): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 8092): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/SQLiteDatabase( 8092): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)

```
