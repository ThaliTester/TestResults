#### Test 55613145b105d0b_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 36.426ms
I/SystemConfig( 6055): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6055): existFile = false
I/SystemConfig( 6055): canReadFile = false
I/SystemConfig( 6055): systemFeature RCS result false
D/SystemConfig( 6055): refreshRcsSupport() :false
I/LockScreenSettings( 6074): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
D/LockScreenSettings( 6074): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6074): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6074): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6074): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6074): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
--------- beginning of system
I/ActivityManager(  991): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6104 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  991): Killing 5866:com.google.android.configupdater/u0a3 (adj 15): empty #11
,W/libprocessgroup(  991): failed to open /acct/uid_10003/pid_5866/cgroup.procs: No such file or directory
W/ResourcesManager( 6104): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ProcessCpuTracker(  991): Skipping unknown process pid 6098
W/ProcessCpuTracker(  991): Skipping unknown process pid 6099
W/ProcessCpuTracker(  991): Skipping unknown process pid 6110
W/ProcessCpuTracker(  991): Skipping unknown process pid 6128
I/UpdateIcingCorporaServi( 1944): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  991): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6136 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/UpdateIcingCorporaServi( 1944): UpdateCorporaTask done [took 63 ms] updated apps [took 63 ms] 
D/AndroidRuntime( 6123): 
D/AndroidRuntime( 6123): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/ActivityManager(  991): Killing 5789:com.google.android.gm/u0a53 (adj 15): empty #11
D/AndroidRuntime( 6123): CheckJNI is OFF
W/libprocessgroup(  991): failed to open /acct/uid_10053/pid_5789/cgroup.procs: No such file or directory
D/Finsky  ( 6136): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/Finsky  ( 6136): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 6136): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6136): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6136): com.android.vending: cancel(-1050172287) by com.android.vending
V/DownloadManager( 3183): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3183): created cursor android.database.sqlite.SQLiteCursor@20cd7c1a on behalf of 6136
D/AndroidRuntime( 6123): Calling main entry com.android.commands.am.Am
I/ActivityManager(  991): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  991): setTaskToReturnTo : TaskRecord{3a3d4044 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  991): setTaskToReturnTo : TaskRecord{3a3d4044 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  991): AppWindowTokenEx init.. 
D/ContextHelper(  991): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/[LGHome]EVENT( 1884): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  991): Focus left window: Window{21ce4812 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 6123): Shutting down VM
D/SplitWindow(  991): check instance of lgWin Window{3ef9baae u0 Starting com.test.thalitest}
D/Ads     ( 6136): Skipping gmscore version check
I/ActivityManager(  991): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6197 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1884): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
D/Finsky  ( 6136): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6136): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 6136): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/HotwordDetector( 1944): Closing mic
I/WindowStateAnimator(  991): Starting window displayed
I/MicrophoneInputStream( 1944): mic_close com.google.android.apps.gsa.speech.audio.u@9cf6918
V/AudioRecord( 1944): stop()
D/AudioRecord( 1944): AudioRecord->stop()
V/AudioFlinger(  285): RecordHandle::stop()
V/AudioFlinger(  285): RecordThread::stop
I/[LGHome]EVENT( 1884): [Launcher.java:5214:onStop()]onStop
V/AudioFlinger(  285): Record stopped OK
V/AudioPolicyManager(  285): stopInput() input 17
V/AudioPolicyService(  285): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  285): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  285): AudioCommandThread() waking up
V/AudioPolicyService(  285): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  285): releaseAudioPatch handle 18
I/SystemUI[Framework](  991): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
V/AudioFlinger::PatchPanel(  285): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  285): ThreadBase::setParameters() routing=0
V/AudioFlinger(  285): sendConfigEvent_l() num events 1 event 2
D/PhoneStatusBar( 1380): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
V/AudioFlinger(  285): processConfigEvents_l() remaining events 1
V/AudioFlinger(  285): processConfigEvents_l() DONE thread 0xb4317000
D/audio_hw_primary(  285): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
W/PhoneWindowManagerEx(  991): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  991): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  991): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  991): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2917df1a,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  991): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1380): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1380):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1380): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1380): draw background and invalidate : color = 19000000
D/BarTransitions( 1380): draw background and invalidate : color = b0b0b0b
V/audio_hw_primary(  285): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  285): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  285): LGE_platform_add_backend_name: enter: 144
,V/audio_hw_primary(  285): disable_audio_route: reset and update mixer path: audio-record
D/PackageBroadcastService( 4185): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
V/audio_hw_primary(  285): disable_audio_route: exit
E/audio_hw_primary(  285): disable_snd_device: enter 144
D/hardware_info(  285): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  285): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  285): stop_input_stream: exit: status(0)
V/audio_hw_primary(  285): in_standby: exit:  status(0)
V/AudioFlinger(  285): RecordThread: loop stopping
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
V/AudioPolicyManager(  285): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  285): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  285): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  285): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  285): AudioCommandThread() waking up
V/AudioPolicyService(  285): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
V/AudioPolicyService(  285): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  285): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  285): AudioCommandThread() waking up
V/AudioPolicyService(  285): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  285): setParameters(): io 17, keyvalue hotword_active=0, calling pid 285
V/AudioFlinger(  285): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  285): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  285): RecordThread: loop starting
V/AudioFlinger(  285): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  285): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  285): in_set_parameters: exit: status(0)
V/AudioFlinger(  285): processConfigEvents_l() DONE thread 0xb4317000
V/AudioFlinger(  285): RecordThread: loop stopping
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
D/Finsky  ( 6136): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
V/AudioRecord( 1944): stop()
V/AudioRecord( 1944): stop()
V/AudioRecord( 1944): stop()
I/ActivityManager(  991): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6223 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/PackageBroadcastService( 4185): Null package name or gms related package.  Ignoreing.
V/AudioFlinger(  285): RecordHandle::stop()
V/AudioFlinger(  285): RecordThread::stop
V/AudioPolicyManager(  285): releaseInput() 17
V/AudioFlinger(  285): releasing 16 from 1944 for -1
V/AudioPolicyManager(  285): closeInput(17)
V/AudioFlinger(  285):  decremented refcount to 0
V/AudioFlinger(  285): purging stale effects
V/AudioFlinger(  285): closeInput() 17
V/AudioSystem(  285): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  285): ThreadBase::exit
V/AudioFlinger(  285): RecordThread: loop starting
I/HotwordRecognitionRnr( 1944): Stopping hotword detection.
V/AudioFlinger(  285): RecordThread 0xb4317000 exiting
V/AudioSystem( 1380): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  285): adev_close_input_stream: enter:stream_handle(0xb4036520)
D/audio_hw_primary(  285): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  285): in_standby: exit:  status(0)
V/AudioPolicyService(  285): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  285): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  285): AudioCommandThread() waking up
V/AudioPolicyService(  285): AudioCommandThread() processing update audio port list
V/AudioPolicyManager(  285): releaseInput() exit
V/AudioFlinger(  285): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  285): removeClient_l() pid 1944, calling pid 285
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
I/HotwordRecognitionRnr( 1944): Hotword detection finished
V/AudioSystem(  991): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1944): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1983): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2011): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3111): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1758): ioConfigChanged() event 4, ioHandle 17
I/Icing   ( 4185): updateResources: need to parse f{com.google.android.gms}
D/ContextHelper( 6197): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
W/ResourcesManager( 6223): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/CalendarProvider2( 6223): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@e914080
D/CalendarProvider2( 6223): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 6223): Created com.android.providers.calendar.CalendarAlarmManager@30eaf575(com.android.providers.calendar.CalendarProvider2@e914080)
D/CalendarProviderBroadcastReceiver( 6223): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6223): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 6223): CalendarProviderIntentService.onCreate()
I/WebViewFactory( 6197): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
D/CalendarProvider2( 6223): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6223): [getOrCreateCalendarAlarmManager]
I/ActivityManager(  991): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6246 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/CalendarProvider2( 6223): [IntentService] Release Lock
D/CalendarProvider2( 6223): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  991): Killing 5943:com.google.android.setupwizard/u0a38 (adj 15): empty #11
I/LibraryLoader( 6197): Time to load native libraries: 3 ms (timestamps 4540-4543)
I/LibraryLoader( 6197): Expected native library version number "",actual native library version number ""
W/libprocessgroup(  991): failed to open /acct/uid_10038/pid_5943/cgroup.procs: No such file or directory
V/WebViewChromiumFactoryProvider( 6197): Binding Chromium to main looper Looper (main, tid 1) {30eaf575}
I/LibraryLoader( 6197): Expected native library version number "",actual native library version number ""
I/chromium( 6197): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6197): Initializing chromium process, singleProcess=true
W/art     ( 6197): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6197): ApplicationContext is null in ApplicationStatus
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
W/chromium( 6197): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
W/ActivityManager(  991): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/libEGL  ( 6197): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6197): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6197): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6197): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6197): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6197): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6197): Remote Branch: 
I/Adreno-EGL( 6197): Local Patches: 
I/Adreno-EGL( 6197): Reconstruct Branch: 
I/Gmail   ( 6246): getAccountsCursor
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/AudioPolicyService(  285): registerClient() client 0xb382c220, uid 10316
,D/BluetoothManagerService(  991): Message: 20
,D/BluetoothManagerService(  991): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b8d8827:true
D/BluetoothAdapterService(746746865)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@699014f
W/GAV2    ( 6246): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  991): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/Finsky  ( 6136): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/AlarmManager(  991): RTC_WAKEUP set : Alarm{1f8b9758 type 0 when 1452763917892 com.android.vending} when 1452763917892
,E/Gmail   ( 6246): Error finding the version of the Email provider.....
E/Gmail   ( 6246): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6246): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6246): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6246): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6246): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6246): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6246): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6246): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6246): We do not support migrating this version of the Email provider.
W/ActivityManager(  991): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 6246): getAccountsCursor
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  991): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6246): Observing account changes for notifications
,W/art     ( 6197): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6197): onDetachedFromWindow called when already detached. Ignoring
,I/art     ( 3909): Explicit concurrent mark sweep GC freed 2842(113KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.497ms total 29.081ms
,I/NotificationManager(  991): android: cancelAsUser(2) by android
D/SystemWebViewEngine( 6197): CordovaWebView is running on device made by: LGE
,W/art     ( 6197): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6197): Attempt to remove local handle scope entry from IRT, ignoring
I/Activity( 6197): Activity.onPostResume() called 
,D/OpenGLRenderer( 6197): Render dirty regions requested: true
I/OpenGLRenderer( 6197): Initialized EGL, version 1.4
D/OpenGLRenderer( 6197): Enabling debug mode 0
,D/Atlas   ( 6197): Validating map...
,D/SplitWindow(  991): check instance of lgWin Window{3bbc5c1b u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/Gmail   ( 6246): notifyAccountChanged
D/libc-netbsd( 6136): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6136): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6136): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6136): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  281): App 10036 tries DNS query. Accept family:0 protocol:0
I/Gmail   ( 6246): getAccountsCursor
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out( 6136): propertyValue:false
D/libc-netbsd( 6136): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6136): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Gmail   ( 6246): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
W/chromium( 6197): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6246): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6246): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6246): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/InputDispatcher(  991): Focus entered window: Window{3bbc5c1b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  991): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  991): Displayed com.test.thalitest/.MainActivity: +1s313ms
,I/Timeline(  991): Timeline: Activity_windows_visible id: ActivityRecord{2e41452d u0 com.test.thalitest/.MainActivity t222} time:95280
I/Timeline( 6197): Timeline: Activity_idle id: android.os.BinderProxy@2d1ec8 time:95301
,I/ActivityManager(  991): Process com.android.contacts (pid 6055) has died
,D/libc-netbsd( 6136): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6136): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Gmail   ( 6246): getAccountsCursor
,W/BindingManager( 6197): Cannot call determinedVisibility() - never saw a connection for the pid: 6197
V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 4185): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/Icing   ( 4185): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 4185): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  991): android: cancelAsUser(2) by android
,I/qtaguid ( 6136): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6136): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6136): untagSocket(41) failed with errno -22
D/Finsky  ( 6136): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/ActivityManager(  991): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6322 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  991): android: cancelAsUser(2) by android
,D/JsMessageQueue( 6197): Set native->JS mode to OnlineEventsBridgeMode
,W/ResourcesManager( 6322): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6322): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6322): VM with version 2.1.0 has multidex support
,I/MultiDex( 6322): install
I/MultiDex( 6322): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 6322): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/jxcore_app_log( 6197): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622854144
,D/JX-Cordova( 6197): jxcore cordova android initializing
W/ActivityThread( 6322): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6322): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@c91532f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6322): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 6322): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6322): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1739): callingUid 10006, callindPid: 1739
,E/MDM     ( 1739): [142] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/ChimeraCfgMgr( 6322): Reading stored module config
,D/LocationInitializer( 4185): Restart initialization of location
D/AuthorizationBluetoothService( 1739): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1739): com.google.android.gms: cancel(0) by com.google.android.gms
,D/ChimeraCfgMgr( 6322): Loading module com.google.android.gms.car from APK com.google.android.gms
W/GCoreFlp( 1739): No location to return for getLastLocation()
W/FusedLocationProvider( 1739): location=null
,I/art     ( 6197): CheckpointMarkThreadRoots callback created = 0x9f6954d0
,I/art     ( 6197): CheckpointMarkThreadRoots callback created = 0x9f6954a0
,I/qtaguid ( 6136): Failed write_ctrl(u 41) res=-1 errno=22
,I/qtaguid ( 6136): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6136): untagSocket(41) failed with errno -22
D/CAR.SERVICE( 6322): Connecting to CarCallService...
,D/NativeLibraryUtils( 6322): Install completed successfully. count=14 extracted=0
I/art     ( 6322): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6322): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/CAR.SERVICE( 6322): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6322): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6322): Creating a new PhoneAdapter instance
W/ActivityManager(  991): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6322): setListener: com.google.android.gms.car.dn@340d1fca
W/ActivityManager(  991): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6322): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6322): Starting CarCallService with initial phone null
I/NotificationManager( 6322): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/CAR.SERVICE( 6322): Package validated; name: com.android.vending
,D/AlertService( 5975): Beginning updateAlertNotification
,I/NotificationManager( 6136): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 6136): [1] GearheadStateMonitor.access$100: mIsProjecting:false
D/AlertService( 5975): No fired or scheduled alerts
I/NotificationManager( 5975): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 5975): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 5975): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 5975): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 5975): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5975): com.android.calendar: cancel(5) by com.android.calendar
,I/NotificationManager( 5975): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 5975): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 5975): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 5975): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 5975): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 5975): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 5975): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 5975): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 5975): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 5975): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 5975): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 5975): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5975): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 5975): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 5975): com.android.calendar: cancel(20) by com.android.calendar
,D/AlertService( 5975): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 5975): No events found starting within 1 week.
,I/art     ( 6136): CheckpointMarkThreadRoots callback created = 0xaafa1530
,D/sensors_hal_Time(  991): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  991): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  991): tsOffsetIs: Apps: 96909594707; DSPS: 3274433; Offset : -3023289507
,I/art     ( 6136): CheckpointMarkThreadRoots callback created = 0xaafa14f0
,D/PowerManagerServiceEx(  991): acquireWakeLockInternal: lock=557698396, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=991
,I/art     (  991): Explicit concurrent mark sweep GC freed 34061(1657KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 3.163ms total 208.166ms
,I/ActivityManager(  991): Process com.android.calendar (pid 5975) has died
,D/WeatherService( 2699): 2 : TimeTick Intent has been received, Time(hour:min:sec) 10:32:0
D/WeatherService( 2699): 2 : TimeTick Intent And Screen On
D/WeatherService( 2699): 2 : SDK version : 21
,W/ActivityManager(  991): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2699): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2699): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2699): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2699): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2699): 2 : This is isUpdating : false
D/WeatherService( 2699): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2699): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2699): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2699): 2 : Fixed theme : optimus
D/WeatherReflect( 2699): 2 : Map key string is -2
,D/lim     ( 2699): 2 : time = 10:32
I/WeatherReflect( 2699): Model Name : LG-D722
D/WeatherTheme( 2699): 2 : Different view - status_min_formatted : 31 != 32
D/WeatherTheme( 2699): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2699): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
,D/Theme   ( 2699): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2699): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2699): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2699): currentPackage=com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2699): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2699): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2699): forecast size is 0
D/Theme   ( 2699): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2699): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2699): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2699): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2699): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2699): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2699): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2699): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2699): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2699): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2699): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2699): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2699): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2699): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2699): setTouchIntent, appWidgetId: 2
,D/Theme_WeatherAncestor_optimus( 2699): url is : null
D/Theme   ( 2699): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2699): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2699): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2699): 2 : update view, appWidgetId: 2
D/WeatherService( 2699): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 10:32:0
D/PowerManagerServiceEx(  991): releaseWakeLockInternal: lock=557698396 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1884): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/[SystemUI]TimeTickManager( 1380): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1380): called onTimeUpdated()
I/[SystemUI]Clock( 1380): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1380): called onTimeUpdated()
I/[SystemUI]DateView( 1380): called onTimeUpdated()
I/[SystemUI]DateView( 1380): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1380): handleTimeUpdate
E/[LgeWidgetLib]LgeAppWidgetHostView( 1884): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/ActivityManager(  991): Process com.google.android.talk (pid 5310) has died
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  991): android: cancelAsUser(2) by android
,I/qtaguid ( 6136): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6136): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6136): untagSocket(41) failed with errno -22
,W/ResourcesManager( 6136): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6136): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/jxcore-log( 6197): Initializing JXcore engine
,W/jxcore-log( 6197): JXcore engine is ready
W/jxcore-log( 6197): Starting JXcore engine
,I/ActivityManager(  991): Process com.android.gallery3d (pid 6033) has died
W/ResourcesManager( 6136): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 6136): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  991): RTC_WAKEUP set : Alarm{a39ab7 type 0 when 1452763921365 com.android.vending} when 1452763921365
,W/.test.thalitest( 6197): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7485]" dev="sockfs" ino=7485 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6197): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6197): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6889]" dev="sockfs" ino=6889 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6197): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6197): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6197): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[23516]" dev="sockfs" ino=23516 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,D/DeviceConnectionService( 1739): client connected with version: 8296000
,D/Finsky  ( 6136): [755] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6136): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 6136): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  991): android: cancelAsUser(2) by android
,I/art     ( 6136): WaitForGcToComplete blocked for 110.323ms for cause HomogeneousSpaceCompact
,I/art     ( 1739): Explicit concurrent mark sweep GC freed 21984(1383KB) AllocSpace objects, 5(80KB) LOS objects, 39% free, 13MB/23MB, paused 13.376ms total 104.490ms
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
W/jxcore-log( 6197): Platform android
W/jxcore-log( 6197): 
,W/jxcore-log( 6197): Process ARCH arm
W/jxcore-log( 6197): 
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/libc-netbsd( 6136): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6136): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6136): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6136): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  281): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
,I/System.out( 6136): propertyValue:false
W/PackageSettings(  991): Skipping PackageSetting{1620b0de com.example.hello/10317} due to missing metadata
,V/AlarmManager(  991): RTC_WAKEUP set : Alarm{103b7545 type 0 when 1452763922147 com.google.android.googlequicksearchbox} when 1452763922147
,I/jxcore-log( 6197): JXcore Cordova bridge is ready!
I/jxcore-log( 6197): 
,W/jxcore-log( 6197): JXcore engine is started
I/Choreographer( 6197): Skipped 209 frames!  The application may be doing too much work on its main thread.
I/chromium( 6197): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/GAV2    ( 6246): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 6197): Toggling radios to true
I/jxcore-log( 6197): 
D/BluetoothAdapter( 6197): enable(): BT is already enabled..!
,D/WifiServiceImplEx(  991): setWifiEnabled: true pid=6197, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  991): setWifiEnabled: true pid=6197, uid=10316
,D/WifiServiceImplEx(  991): disconnect pid=6197, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  991): reconnect pid=6197, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 6197): Radios toggled
I/jxcore-log( 6197): 
I/jxcore-log( 6197): My device name is: LGE-LG-D722
I/jxcore-log( 6197): 
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2794): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2794): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine(  991): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  991): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WfdsMonitor( 1810): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,D/LGWifiP2pService(  991): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  991): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  991): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  281): Clearing all IP addresses on wlan0
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 7
,V/NativeCrypto( 1739): Read error: ssl=0xb049d600: I/O error during system call, Connection timed out
V/NativeCrypto( 1739): SSL shutdown failed: ssl=0xb049d600: I/O error during system call, Broken pipe
,D/libc-netbsd(  991): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  991): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 7
D/WifiHS20(  991): hidePasspointNotification off =false
,I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1380): mWifiConnected = false, mWifiLevel = 0
D/libc-netbsd(  991): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
W/Settings(  991): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/libc-netbsd(  991): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Settings(  991): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  991): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-14 10:32:03.099 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at null
D/ConnectivityService(  991): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
D/libc-netbsd(  991): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  991): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/ConnectivityService(  991): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  991): ignoring duplicate network state non-change
D/ConnectivityService(  991): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1380): Remote
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  991): ValidatedState{ when=-13ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  991): DefaultState{ when=-20ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  991): Forcing reevaluation
D/WifiServiceExtension( 1810): isInternetCheckAvailable return false
I/ActivityManager(  991): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6407 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,E/WifiStateMachine(  991): Start Disconnecting Watchdog 1
D/WifiHS20(  991): hidePasspointNotification off =false
W/Settings(  991): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  991): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  991): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGWifiP2pService(  991): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  991): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 2794): wlan0: CTRL-EVENT-SCAN-STARTED 
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-14 10:32:03.184 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1380): mWifiConnected = false, mWifiLevel = 0
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1380): Remote
D/CommandListener(  281): Clearing all IP addresses on wlan0
,D/ConnectivityService(  991): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  991): disableDataServiceNotify
D/DSQN    (  991): stop dsqn bin
D/WifiHS20(  991): hidePasspointNotification off =false
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  991): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1380): mWifiConnected = false, mWifiLevel = 0
W/Settings(  991): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  991): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-14 10:32:03.206 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiServiceExtension( 1810): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1380): Remote
D/WifiNetworkAgent(  991): NetworkAgent: NetworkAgent channel lost
,D/ConnectivityService(  991): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/WifiHS20(  991): hidePasspointNotification off =false
W/Settings(  991): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  991): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  991): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService(  991):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  991):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-14 10:32:03.23 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1380): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-14 10:32:03.232 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  991): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  991): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  991): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/ConnectivityService(  991): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  991): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1380): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  991): ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  991): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  991): Disconnected - quitting
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/CSLegacyTypeTracker(  991): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  991): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1380): Remote
I/[SystemUI]StatusBar.NetworkController( 1380): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  991): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  991): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  991): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/QCNEJ   ( 1838): |CORE| No family connected
W/QCNEJ   ( 1838): |CORE| No family connected
I/QCNEJ   ( 1838): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1838): |CORE| sendDefaultNwMsg: default = -1
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/NetworkPolicy(  991): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy(  991): [LG_RESTRICTED] !!!isConnected  type  :1
D/WifiServerServiceExt(  991): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  991): setSupplicantStateDISCONNECTED
D/Tethering(  991): MasterInitialState.processMessage what=3
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at null
D/Tethering(  991): MasterInitialState.processMessage what=3
D/WifiServerServiceExt(  991): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  991): setSupplicantStateSCANNING
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1380): Remote
D/ConnectivityService(  991): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  991): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  991): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  991): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  991):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkManagementService(  991): Removing idletimer
D/TelephonyNetworkFactory-1( 1758): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1758):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
W/Settings(  991): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TelephonyIcons( 1380): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1380): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/DhcpStateMachine(  991): StoppedState
D/DhcpStateMachine(  991): StoppedState{ when=-123ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/TelephonyIcons( 1380): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1380): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/ResourcesManager( 6407): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6407): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6407): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6407): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6407): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/IndexDatabaseHelper( 6407): Using schema version: 115
,I/IndexDatabaseHelper( 6407): Index is fine
V/WiFiOffLoadBroadcast( 6407): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6407): MCCMNC not supported: null
I/ActivityManager(  991): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6434 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  991): Killing 6009:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  991): failed to open /acct/uid_10011/pid_6009/cgroup.procs: No such file or directory
,I/PCSuite ( 6434): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6434): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6434): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6407): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6407): MCCMNC not supported: null
I/PCSuite ( 6434): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6434): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6434): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  991): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6461 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  991): Killing 6074:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
I/ActivityManager(  991): Process com.google.android.apps.plus (pid 6104) has died
,W/libprocessgroup(  991): failed to open /acct/uid_10069/pid_6074/cgroup.procs: No such file or directory
W/ResourcesManager( 6461): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2794): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/LocSvc_java(  991): onReceive
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-14 10:32:04.341 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1380): mWifiConnected = false, mWifiLevel = 0
,W/Settings(  991): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  991): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  991): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1380): Remote
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2794): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-14 10:32:04.358 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1380): mWifiConnected = false, mWifiLevel = 0
W/Settings(  991): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  991): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  991): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1380): Remote
D/WifiServerServiceExt(  991): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  991): setSupplicantStateASSOCIATING
D/WifiServerServiceExt(  991): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  991): setSupplicantStateASSOCIATED
,I/Babel_SMS( 6461): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6461): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6461): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6461): MmsConfig.loadFromDatabase
,I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1380): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-14 10:32:04.452 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  991): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  991): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  991): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1380): Remote
I/[SystemUI]StatusBar.NetworkController( 1380): mWifiConnected = false, mWifiLevel = 0
W/Settings(  991): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  991): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  991): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt(  991): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  991): setSupplicantStateFOUR_WAY_HANDSHAKE
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-14 10:32:04.458 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1380): Remote
I/wpa_supplicant( 2794): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supp,licant( 2794): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiServerServiceExt(  991): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  991): setSupplicantStateGROUP_HANDSHAKE
,I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
I/WifiServiceExtension(  991): setVHTCapabilityType  : false
E/Babel_SMS( 6461): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6461): MmsConfig.loadFromResources
,E/Babel_SMS( 6461): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6461): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/WifiServerServiceExt(  991): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,I/WifiServerServiceExt(  991): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  991): setSecurityType  : 2
W/Settings(  991): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  991): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  991): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1380): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-14 10:32:04.532 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1380): Remote
I/[SystemUI]StatusBar.NetworkController( 1380): mWifiConnected = false, mWifiLevel = 0
W/Settings(  991): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  991): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  991): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-14 10:32:04.539 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1380): Remote
D/ConnectivityService(  991): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262,144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  991): Got NetworkAgent Messenger
D/ConnectivityService(  991): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  991): NetworkAgent connected
,D/WifiServiceExtension( 1810): isInternetCheckAvailable return false
E/WifiConfigStore(  991): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/SensorManager( 6461): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6461): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6461): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6461): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6461): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6461): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6461): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6461): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6461): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6461): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6461): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6461): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6461): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6461): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6461): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6461): found sensor: Motion Accel, handle=46
E/WifiConfigStore(  991): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  991): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  991): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  991): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  991): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  281): Setting iface cfg
E/WifiStateMachine(  991): Start Dhcp Watchdog 2
D/DhcpStateMachine(  991): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  991): WaitBeforeStartState
D/ConnectivityService(  991): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,I/art     ( 6461): CheckpointMarkThreadRoots callback created = 0xb042d860
,E/WifiStateMachine(  991): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  991): Current State is mWaitBeforeStartState.
,I/art     ( 6461): CheckpointMarkThreadRoots callback created = 0xb042d830
V/LgDhcpStateMachineHelper(  991): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService(  991): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@7579994 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  991): P2pEnabledState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@7579994 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  991): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  991): DHCP Start wake lock is acquired.
D/CommandListener(  281): Setting iface cfg
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  991): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  991): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  281): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  991): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
I/ActivityManager(  991): Process com.google.android.gm (pid 6246) has died
D/WifiServerServiceExt(  991): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  991): setSupplicantStateCOMPLETED
,D/ConnectivityService(  991): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  991): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  991): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings( 6461): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6461): startup - clean
E/WifiStateMachine(  991): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  991): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/ConnectivityService(  991): ignoring duplicate network state non-change
I/[SystemUI]StatusBar.NetworkController( 1380): mWifiConnected = false, mWifiLevel = 0
W/Settings(  991): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  991): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  991): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-58 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-14 10:32:04.743 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
D/WifiServiceExtension( 1810): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1380): Remote
D/WifiServiceExtension( 1810): isInternetCheckAvailable return false
W/Settings(  991): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  991): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  991): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/[SystemUI]StatusBar.NetworkController( 1380): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  991): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-58 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-14 10:32:04.75 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/ConnectivityService(  991): Adding iface wlan0 to network 101
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiHS20(  991): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  991): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  991): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  991): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1380): Remote
I/[SystemUI]StatusBar.NetworkController( 1380): mWifiConnected = true, mWifiLevel = 2
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1380): Remote
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-58 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-14 10:32:04.773 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
,E/ConnectivityService(  991): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  991): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/WifiHS20(  991): [PASSPOINT] passpointNotification: hs20AP list is checked
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  991): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/WifiStateMachine(  991): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  281): netlink response contains error (File exists)
D/ConnectivityService(  991): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  991): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  991): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  991): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  991): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  991): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Babel   ( 6461): deleted: false for 0
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  991): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  991): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  991): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/Nat464Xlat(  991): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  991): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  991): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  991): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  991): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  991):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  991): Connected
D/ConnectivityService(  991):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  991):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  991): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  991):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivitySe,rvice(  991):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  991): currentScore = 0, newScore = 20
D/ConnectivityService(  991):    accepting network in place of null
D/ConnectivityService(  991): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1758): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  991): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  991): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/TelephonyNetworkFactory-1( 1758):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/ConnectivityService(  991): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-58 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-14 10:32:04.81 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/ConnectivityService(  991): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  991): [e] list.add(nai) empty : false size: 1
D/ConnectivityService(  991): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/Tethering(  991): MasterInitialState.processMessage what=3
D/ConnectivityService(  991): validation of new default Network = false
D/ConnectivityService(  991): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  991): enableDataServiceNotify 
D/DSQN    (  991): start dsqn bin
W/QCNEJ   ( 1838): |CORE| No family connected
I/QCNEJ   ( 1838): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  991): [LWD] Start DNSResolver start to wait
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): mWifiConnected = true, mWifiLevel = 2
I/QCNEJ   ( 1838): |CORE| sendDefaultNwMsg: default = 1
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  991): [LWD] wait 500ms before dns check
D/ConnectivityService(  991): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  991):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  991):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WIFI    (  991): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  991):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  991): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1380): CM callback handler got msg 524290
V/NetworkPolicy(  991): [LG_RESTRICTED] checkMobilePolicy_type()
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1380): Remote
,I/DSQN    ( 6510): DSQN samuel.seo ver 141203
E/DSQN    ( 6510): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6510): created command queue thread
I/DSQN    ( 6510): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6510): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/CAR.SERVICE( 6322): mConnectedToCar = false, abort
,D/TelephonyIcons( 1380): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1380): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
,E/ActivityThread( 6322): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2f277472 that was originally bound here
E/ActivityThread( 6322): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2f277472 that was originally bound here
E/ActivityThread( 6322): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6322): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6322): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6322): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6322): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6322): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6322): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6322): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6322): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6322): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6322): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6322): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6322): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6322): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6322): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6322): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6322): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6322): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6322): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6322): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6322): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6322): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6322): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/ActivityThread( 6322): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@16cd9f35 that was originally bound here
E/ActivityThread( 6322): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@16cd9f35 that was originally bound here
E/ActivityThread( 6322): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6322): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6322): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6322): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6322): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6322): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6322): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6322): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6322): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6322): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6322): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6322): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6322): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6322): 	at android.app.ActivityThread.acce,ss$1900(ActivityThread.java:155)
E/ActivityThread( 6322): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6322): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6322): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6322): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6322): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6322): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6322): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6322): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  991): Unbind failed: could not find connection for android.os.BinderProxy@b0fa25
V/WiFiOffLoadBroadcast( 6407): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6407): MCCMNC not supported: null
W/AudioCapabilities( 6461): Unsupported mime audio/x-lg-flac
I/PCSuite ( 6434): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6434): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6434): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/AudioCapabilities( 6461): Unsupported mime audio/adpcm
,D/DhcpStateMachine(  991): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper(  991): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  991): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
V/WiFiOffLoadBroadcast( 6407): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/AudioCapabilities( 6461): Unsupported mime audio/g726
,I/dhcpcd  ( 6513): version 5.5.6 starting
E/dhcpcd  ( 6513): get_duid: Read-only file system
D/WiFiOffLoadBroadcast( 6407): MCCMNC not supported: null
I/PCSuite ( 6434): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6434): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 6434): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/AudioCapabilities( 6461): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6461): Unsupported mime audio/wma-voice
V/WiFiOffLoadBroadcast( 6407): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/VideoCapabilities( 6461): Unsupported mime video/mjpg
W/VideoCapabilities( 6461): Unsupported mime video/theora
D/WiFiOffLoadBroadcast( 6407): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6407): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6407): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6407): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6407): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6407): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/dhcpcd  ( 6513): wlan0: rebinding lease of 192.168.1.134
D/WiFiOffLoadBroadcast( 6407): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6407): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6407): MCCMNC not supported: null
W/AudioCapabilities( 6461): Unsupported mime audio/evrc
W/AudioCapabilities( 6461): Unsupported mime audio/qcelp
V/WiFiOffLoadBroadcast( 6407): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/VideoCapabilities( 6461): Unrecognized profile 2130706433 for video/avc
D/WiFiOffLoadBroadcast( 6407): MCCMNC not supported: null
W/AudioCapabilities( 6461): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6461): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6461): Unsupported mime audio/evrc
I/dhcpcd  ( 6513): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
V/WiFiOffLoadBroadcast( 6407): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6407): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6407): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6407): MCCMNC not supported: null
W/VideoCapabilities( 6461): Unsupported mime video/mp4v-esdp
,I/dhcpcd  ( 6513): wlan0: leased 192.168.1.134 for 86400 seconds
V/WiFiOffLoadBroadcast( 6407): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6407): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6407): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6407): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6407): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6407): MCCMNC not supported: null
I/VideoCapabilities( 6461): Unsupported profile 4 for video/mp4v-es
,I/PCSuite ( 6434): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6434): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6407): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/VideoCapabilities( 6461): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6461): Unrecognized profile 2130706433 for video/avc
D/WiFiOffLoadBroadcast( 6407): MCCMNC not supported: null
W/VideoCapabilities( 6461): Unrecognized profile 2130706433 for video/avc
I/PCSuite ( 6434): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6434): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
W/VideoCapabilities( 6461): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6461): onServiceConnected
W/Babel   ( 6461): Attempted to change video mute state without an active call.
,I/NotificationManager( 6461): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd(  991): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  991): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  991): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  991): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  991): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  991): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  991): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  991): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  991): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  991): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  991): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  991): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  991): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  991): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  991): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  991): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  991): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  991): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  991): RunningState
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  991): [LWD] DNSResolver start dns
,D/libc-netbsd(  991): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  991): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  991): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  991): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  281): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
,I/System.out(  991): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  991): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  991): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  991): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  991): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/DSQN    ( 6510): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6510): restart monitoring
,D/LGDataListener(  281): argv[0]=dsqncommand
D/LGDataListener(  281): argv[1]=wlan0
D/LGDataListener(  281): argv[2]=1
D/LGDataListener(  281): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  991): DSQM DsqnNotification wlan0  1
D/DSQN    (  991): start to monitor internet connection
I/DSQN    ( 6510): dsqn report finish
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  991): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 14 Jan 2016 09:32:05 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452763925415], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452763925396]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  991): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1810): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  991): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  991): Validated
D/ConnectivityService(  991): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  991): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  991):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  991):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  991):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  991): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  991): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  991):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  991):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  991): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WifiDataContinuityService(  991): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
D/ConnectivityService(  991): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  991): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory-1( 1758): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1380): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1758):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/WifiServerServiceExt(  991): set CMD_CAPTIVE_CHECK_COMPLETED
D/WIFI    (  991): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  991):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyIcons( 1380): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1380): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/ConnectivityService(  991): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/rmt_storage(  278): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  278): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  278): wakelock acquired: 1, error no: 42
I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
,I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  278): 
I/rmt_storage(  278): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 6
D/ConnectivityService(  991): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/libc-netbsd(  991): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  991): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  991): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/LocSvc_java(  991): onReceive
D/LocSvc_java(  991): got connectivity action
D/LocSvc_java(  991): broadcast - no network connections
D/LocSvc_java(  991): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  991): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  991): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  991): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  991): ignore wifi update if we are not in OPENING or CLOSING
,D/GpsLocationProvider(  991): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  991): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager(  991): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6559 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ConnectivityService(  991): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  991): identical MTU - not setting
D/Nat464Xlat(  991): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/GpsLocationProvider(  991): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  991): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  991):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  991):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  991): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/GpsLocationProvider(  991): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  991): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  991): enableDataServiceNotify 
D/DSQN    (  991): start dsqn bin
D/LocSvc_java(  991): onReceive
D/LocSvc_java(  991): got connectivity action
D/LocSvc_java(  991): broadcast - no network connections
D/LocSvc_java(  991): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  991): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  991): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  991): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  991): ignore wifi update if we are not in OPENING or CLOSING
,D/DSQN    (  991): dsqn is running restart
I/DSQN    ( 6566): DSQN samuel.seo ver 141203
E/DSQN    ( 6566): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6566): created command queue thread
I/DSQN    ( 6566): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6566): Interface wlan0 netmask 255.255.255.0 0xc0a80186
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/ConnectivityManager.CallbackHandler( 1380): CM callback handler got msg 524295
I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-58 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-14 10:32:06.387 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/MusicStore( 6559): Database version: 120
,I/ActivityManager(  991): Process com.android.vending (pid 6136) has died
,E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6559): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6559): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6559): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6559): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6559): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6559): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6559): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6559): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3754a946: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6559): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6559): GMSCore installation verified
I/ConfigStore( 6559): Config Database version: 1
,I/MediaRouter( 6559): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6559): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6559): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6559): type=WIFI subType= reason=null isConnected=true
,I/NotificationManager( 1944): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/ActivityManager(  991): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6604 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 301us total 22.148ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 20.307ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 20.059ms
,I/GHttpClientFactory( 6559): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6559): Using platform SSLCertificateSocketFactory
,I/NotificationManager( 6559): com.google.android.music: cancel(1061) by com.google.android.music
,W/ResourcesManager( 6604): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6604): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6604): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-14 10:32:07.643 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/LGEmail ( 6604): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,V/WifiInternetCheck(  991): Single check msg out of sync, ignoring.
D/LGEmail ( 6604): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/ConnectivityService(  991): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  991): onReceive
D/LocSvc_java(  991): got connectivity action
D/LocSvc_java(  991): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  991): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  991): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  991): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  991): ignore wifi update if we are not in OPENING or CLOSING
I/[SystemUI]QuickSettingsHandler( 1380): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/GpsLocationProvider(  991): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  991): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 6559): type=WIFI subType= reason=null isConnected=true
,D/eas_req ( 6604): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  991): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6630 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6604): JNI_OnLoad()
I/HubEmail( 6604): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6604): registerNatives()
I/HubEmail( 6604): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6604): registerNativeMethods()
I/HubEmail( 6604): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6604): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  991): Killing 6223:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/libprocessgroup(  991): failed to open /acct/uid_10014/pid_6223/cgroup.procs: No such file or directory
,W/Settings( 6604): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 6630): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6630): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6630): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 6630): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6630): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6630): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6630): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6630): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  991): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6657 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6630): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6630): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6630): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6630): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6630): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6630): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  991): Killing 6322:com.google.android.gms:car/u0a6 (adj 15): empty #11
,I/AppUp4:AppBoxCP( 6657): onCreate
,W/AppUp4:DB( 6657):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6657):  setFingerPrint start
I/AppUp4:DB( 6657):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6657):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6657):  SDK version = 0
I/AppUp4:DB( 6657):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6657): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6657): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6657): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6657): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 6657): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6657): onReceive
I/AppUp4:CustModeStarterReceiver( 6657): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6657): Context : android.app.ReceiverRestrictedContext@3852590a
D/AppUp4:CustFacade( 6657): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6657): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6657): begin check event
I/AppUp4:CustModeStarterReceiver( 6657): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6657): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6657): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6657): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6657): handleAsyncCustNotification do not startCustService
I/ActivityManager(  991): Killing 6461:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  991): failed to open /acct/uid_10061/pid_6461/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3111): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3111): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3111): networkInfo.isConnected() = false
I/ActivityManager(  991): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6676 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/PhoneMonitor( 6676): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6676): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6676): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  991): Killing 6407:com.android.settings/1000 (adj 15): empty #11
D/libc-netbsd(  991): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  991): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  991): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  991): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  281): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out(  991): propertyValue:false
,D/libc-netbsd(  991): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  991): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  991): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  991): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  281): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out(  991): propertyValue:false
W/libprocessgroup(  991): failed to open /acct/uid_1000/pid_6407/cgroup.procs: No such file or directory
,I/DSQN    ( 6566): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6566): restart monitoring
I/DSQN    ( 6566): dsqn report finish
D/LGDataListener(  281): argv[0]=dsqncommand
D/LGDataListener(  281): argv[1]=wlan0
D/LGDataListener(  281): argv[2]=1
D/LGDataListener(  281): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  991): DSQM DsqnNotification wlan0  1
D/DSQN    (  991): start to monitor internet connection
,V/DownloadManager( 3183): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/WifiInternetCheck(  991): isHttpConnectionAvailable - We got a valid response : 204
I/CheckinService( 4185): Checkin interval check for package: unspecified last checkin: 1452763904266 min interval config: 0 actual interval: 24799
D/PhoneMonitor( 6676): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/DownloadManager( 3183): DownloadService onCreate
V/TelephonyAutoProfiling( 6676): [loadFeatureFromXml] *** start feature loading from xml
I/NotificationManager( 3183): com.android.providers.downloads: cancelAll by com.android.providers.downloads
D/TelephonyAutoProfiling( 6676): [parse] Load xml
,V/TelephonyAutoProfiling( 6676): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6676): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,I/DownloadManager( 3183): in removeSpuriousFiles
V/DownloadManager( 3183): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/ActivityManager(  991): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6704 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/CheckinService( 4185): Checking schedule, now: 1452763929112 next: 1452763934047
I/CheckinService( 4185): active receiver: disabled
,D/PhoneMonitor( 6676): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
V/DownloadManager( 3183): created cursor android.database.sqlite.SQLiteCursor@2969f34b on behalf of 3183
I/DownloadManager( 3183): in trimDatabase
V/DownloadManager( 3183): DownloadService onStartCommand
V/DownloadManager( 3183): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3183): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3183): created cursor android.database.sqlite.SQLiteCursor@9373fe6 on behalf of 3183
,V/DownloadManager( 3183): created cursor android.database.sqlite.SQLiteCursor@13e27927 on behalf of 3183
,I/ActivityManager(  991): Killing 5660:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 5111): android.os.DeadObjectException
,W/System.err( 5111): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5111): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5111): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5111): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5111): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5111): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5111): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5111): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5111): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5111): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5111): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5111): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5111): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5111): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5111): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5111): android.os.DeadObjectException
W/System.err( 5111): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5111): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5111): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5111): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5111): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5111): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5111): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5111): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5111): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5111): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5111): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5111): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5111): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5111): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5111): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  991): failed to open /acct/uid_10089/pid_5660/cgroup.procs: No such file or directory
W/ActivityManager(  991): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,D/WeatherAncestor( 2699): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:32:9
I/ActivityManager(  991): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6733 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/DownloadManager( 3183): DownloadService onDestroy
D/UpdateThreadPoolManager( 2699): 2 : This is isUpdating : false
D/WeatherAncestor( 2699): connectivity changed - connection : true
D/Weather_cast( 2699): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2699): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:32:9
D/WeatherService( 2699): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  991): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6754 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  991): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2699): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2699): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
,D/WeatherService( 2699): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/art     (  991): Explicit concurrent mark sweep GC freed 86415(4MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 3.389ms total 253.380ms
,W/ResourcesManager( 6754): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6733): Quickset Services start...
,I/UEI.SmartControl( 6733): Manufacture = LGE
D/UEI.SmartControl( 6733): File observer start...
E/UEI.SmartControl( 6733): IR Port is disabled: false
D/UEI.SmartControl( 6733): Starting file observer...
D/UEI.SmartControl( 6733): Extracting JNI libs...
D/UEI.SmartControl( 6733): --- this system supports 32-bit or 64-bit only
,D/UEI.SmartControl( 6733): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6733): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6733): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 6733): --- Selecting new region: 2
I/UEI.SmartControl( 6733): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6733): Platform has CIR...
D/UEI.SmartControl( 6733): NO CIR support, need to check package...
I/UEI.SmartControl( 6733): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6733): QS Service created
I/Babel_SMS( 6754): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6754): MmsConfig.loadMmsSettings
I/Babel_SMS( 6754): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6754): MmsConfig.loadFromDatabase
E/UEI.SmartControl( 6733): QS start get config
,E/Babel_SMS( 6754): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6754): MmsConfig.loadFromResources
,E/Babel_SMS( 6754): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6754): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6754): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6754): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6754): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6754): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6754): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6754): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6754): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6754): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6754): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6754): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6754): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6754): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6754): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6754): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6754): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6754): found sensor: Motion Accel, handle=46
,D/UEI.SmartControl( 6733): Loading JNI Libs...
,D/UEI.SmartControl( 6733):  configuring local db...
W/Settings( 6754): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6754): startup - clean
,I/Babel   ( 6754): deleted: false for 0
,I/art     ( 6754): CheckpointMarkThreadRoots callback created = 0xb042d850
I/art     ( 6754): CheckpointMarkThreadRoots callback created = 0xb042d820
,I/ActivityManager(  991): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6791 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 6754): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6754): Unsupported mime audio/adpcm
,W/AudioCapabilities( 6754): Unsupported mime audio/g726
W/AudioCapabilities( 6754): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6754): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 6754): Unsupported mime video/mjpg
W/VideoCapabilities( 6754): Unsupported mime video/theora
D/UEI.SmartControl( 6733):  ---- Has DB8: true
D/UEI.SmartControl( 6733): QS start statue = true Error code = 0
D/UEI.SmartControl( 6733): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6733): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 6733): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6733): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6733): IrrcClient ++ 
,D/irrcClient( 6733): getIrrcService ++ 
D/irrcClient( 6733): getIrrcService -- 
D/irrcClient( 6733): IrrcClient -- 
W/irrc_jni( 6733): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6733): Services init done
I/UEI.SmartControl( 6733): Device manager: loading config....
W/AudioCapabilities( 6754): Unsupported mime audio/evrc
,W/AudioCapabilities( 6754): Unsupported mime audio/qcelp
W/VideoCapabilities( 6754): Unrecognized profile 2130706433 for video/avc
D/UEI.SmartControl( 6733): QS Service init finished
D/UEI.SmartControl( 6733): QS Service version name: 0.1.73
W/AudioCapabilities( 6754): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6754): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6754): Unsupported mime audio/evrc
D/UEI.SmartControl( 6733): QS Service version code: 1073
D/UEI.SmartControl( 6733): Config is loaded...
D/UEI.SmartControl( 6733): Service requested: Control
,D/UEI.SmartControl( 6733): -----IControl: 11
I/ActivityManager(  991): Killing 6434:com.lge.sync/1000 (adj 15): empty #11
D/UEI.SmartControl( 6733): Caller: com.lge.qremote
D/UEI.SmartControl( 6733): ------------ IControl registerCallback...
I/UEI.SmartControl( 6733): Registering callback...
D/UEI.SmartControl( 6733): -----IControl: 19
D/UEI.SmartControl( 6733): Caller: com.lge.qremote
I/UEI.SmartControl( 6733): Registering Services Ready callback...
I/UEI.SmartControl( 6733): Notify client services are ready...
D/UEI.SmartControl( 6733): -----IControl: 8
D/UEI.SmartControl( 6733): Caller: com.lge.qremote
,W/VideoCapabilities( 6754): Unsupported mime video/mp4v-esdp
D/UEI.SmartControl( 6733):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6733): Notify AllClients services are ready: 0
I/VideoCapabilities( 6754): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6754): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6754): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6754): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6754): Unrecognized profile 2130706433 for video/avc
,W/libprocessgroup(  991): failed to open /acct/uid_1000/pid_6434/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 6733): Internal service binding...
I/vclib   ( 6754): onServiceConnected
W/Babel   ( 6754): Attempted to change video mute state without an active call.
I/NotificationManager( 6754): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6754): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6754): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6754): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6754): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  281): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out( 6754): propertyValue:false
I/Babel   ( 6754): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  991): Killing 5111:com.lge.qremote/u0a106 (adj 15): empty #11
W/libprocessgroup(  991): failed to open /acct/uid_10106/pid_5111/cgroup.procs: No such file or directory
,E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6791): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6791): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6791): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6791): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6791): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6791):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6791):   adb logcat -s GAv4
,W/GAv4    ( 6791): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6791): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6791): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
V/AlarmManager(  991): ELAPSED_WAKEUP set : Alarm{281dd988 type 2 when 108355 com.google.android.gms} when 108355
,I/WebViewFactory( 6791): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6791): Time to load native libraries: 2 ms (timestamps 8480-8482)
I/LibraryLoader( 6791): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6791): Binding Chromium to main looper Looper (main, tid 1) {483661f}
I/LibraryLoader( 6791): Expected native library version number "",actual native library version number ""
I/chromium( 6791): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6791): Initializing chromium process, singleProcess=true
W/art     ( 6791): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6791): ApplicationContext is null in ApplicationStatus
,W/chromium( 6791): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6791): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6791): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6791): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6791): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6791): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6791): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6791): Remote Branch: 
I/Adreno-EGL( 6791): Local Patches: 
I/Adreno-EGL( 6791): Reconstruct Branch: 
I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/NSApplication( 6791): Starting up...
,V/AudioPolicyService(  285): registerClient() client 0xb4027840, uid 10079
W/AudioManagerAndroid( 6791): Requires BLUETOOTH permission
I/ActivityManager(  991): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6858 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  991): Killing 6559:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  991): failed to open /acct/uid_10081/pid_6559/cgroup.procs: No such file or directory
,I/ActivityManager(  991): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6877 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  991): Killing 6604:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  991): failed to open /acct/uid_10021/pid_6604/cgroup.procs: No such file or directory
,W/ResourcesManager( 6877): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  991): Killing 6630:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  991): failed to open /acct/uid_1000/pid_6630/cgroup.procs: No such file or directory
,I/ActivityManager(  991): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6901 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/AlarmManager(  991): RTC_WAKEUP set : Alarm{20a7e12a type 0 when 1452763932831 com.google.android.googlequicksearchbox} when 1452763932831
,I/MusicStore( 6901): Database version: 120
,E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6901): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6901): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6901): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6901): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6901): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6901): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6901): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6901): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3754a946: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6901): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6901): GMSCore installation verified
,I/ConfigStore( 6901): Config Database version: 1
,I/MediaRouter( 6901): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6901): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6901): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6901): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  991): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6942 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 294us total 23.005ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 20.241ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 39.797ms
,I/GHttpClientFactory( 6901): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6901): Using platform SSLCertificateSocketFactory
I/ActivityManager(  991): Killing 6657:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/ResourcesManager( 6942): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6942): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6942): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/libprocessgroup(  991): failed to open /acct/uid_10011/pid_6657/cgroup.procs: No such file or directory
,I/NotificationManager( 6901): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6942): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6942): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6942): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  991): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6965 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6942): JNI_OnLoad()
,I/HubEmail( 6942): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6942): registerNatives()
I/HubEmail( 6942): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6942): registerNativeMethods()
I/HubEmail( 6942): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6942): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  991): Killing 6676:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  991): failed to open /acct/uid_10038/pid_6676/cgroup.procs: No such file or directory
,W/Settings( 6942): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 6965): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6965): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6965): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 6965): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6965): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6965): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager(  991): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6986 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/LGDMClient( 6965): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6965): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 6965): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6965): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6965): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6965): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMClient( 6965): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6965): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  991): Killing 6704:com.lge.drmservice/u0a51 (adj 15): empty #11
,I/AppUp4:AppBoxCP( 6986): onCreate
,W/AppUp4:DB( 6986):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6986):  setFingerPrint start
I/AppUp4:DB( 6986):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6986):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6986):  SDK version = 0
I/AppUp4:DB( 6986):  beforefinger == newfinger no write in DB
W/libprocessgroup(  991): failed to open /acct/uid_10051/pid_6704/cgroup.procs: No such file or directory
,D/AppUp4:AppBoxApplication( 6986): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6986): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6986): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6986): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6986): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6986): onReceive
I/AppUp4:CustModeStarterReceiver( 6986): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 6986): Context : android.app.ReceiverRestrictedContext@3852590a
D/AppUp4:CustFacade( 6986): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6986): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6986): begin check event
I/AppUp4:CustModeStarterReceiver( 6986): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6986): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6986): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6986): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6986): handleAsyncCustNotification do not startCustService
I/ActivityManager(  991): Killing 6733:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/libprocessgroup(  991): failed to open /acct/uid_10089/pid_6733/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3111): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3111): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3111): networkInfo.isConnected() = false
,I/ActivityManager(  991): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7011 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7011): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7011): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7011): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  991): Killing 6754:com.google.android.talk/u0a61 (adj 15): empty #11
,D/PhoneMonitor( 7011): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7011): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7011): [parse] Load xml
V/TelephonyAutoProfiling( 7011): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7011): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7011): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  991): failed to open /acct/uid_10061/pid_6754/cgroup.procs: No such file or directory
,V/DownloadManager( 3183): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3183): DownloadService onCreate
I/DownloadManager( 3183): in removeSpuriousFiles
I/NotificationManager( 3183): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3183): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3183): created cursor android.database.sqlite.SQLiteCursor@314f3d7d on behalf of 3183
I/DownloadManager( 3183): in trimDatabase
V/DownloadManager( 3183): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3183): created cursor android.database.sqlite.SQLiteCursor@2f277472 on behalf of 3183
,I/ActivityManager(  991): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7037 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3183): DownloadService onStartCommand
V/DownloadManager( 3183): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3183): created cursor android.database.sqlite.SQLiteCursor@13173479 on behalf of 3183
I/CheckinService( 4185): Checkin interval check for package: unspecified last checkin: 1452763904266 min interval config: 0 actual interval: 31254
I/CheckinService( 4185): Checking schedule, now: 1452763935531 next: 1452763934047
I/CheckinService( 4185): active receiver: enabled
,V/AlarmManager(  991): RTC_WAKEUP set : Alarm{23c9ff9a type 0 when 1452763934047 com.google.android.gms} when 1452763934047
,I/CheckinService( 4185): Preparing to send checkin request
I/EventLogService( 4185): Accumulating logs since 1452763895615
I/ActivityManager(  991): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7055 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  991): RTC_WAKEUP set : Alarm{13fef0cb type 0 when 1452763935542 com.android.vending} when 1452763935542
V/DownloadManager( 3183): DownloadService onDestroy
,I/art     (  991): Explicit concurrent mark sweep GC freed 19425(1061KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.603ms total 162.312ms
,D/WeatherAncestor( 2699): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:32:15
,D/UpdateThreadPoolManager( 2699): 2 : This is isUpdating : false
,D/WeatherAncestor( 2699): connectivity changed - connection : true
D/Weather_cast( 2699): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2699): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:32:15
D/WeatherService( 2699): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  991): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7073 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  991): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2699): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2699): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2699): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/CheckinRequestBuilder( 4185): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 4185): Failed to find provider info for com.google.android.wearable.settings
,W/ResourcesManager( 7073): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7055): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Babel_SMS( 7073): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7073): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7073): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7073): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7073): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7073): MmsConfig.loadFromResources
E/Babel_SMS( 7073): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7073): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/ActivityManager(  991): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7113 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/SensorManager( 7073): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7073): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7073): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
,D/SensorManager( 7073): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7073): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7073): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7073): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7073): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7073): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7073): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7073): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7073): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7073): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7073): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7073): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7073): found sensor: Motion Accel, handle=46
I/art     ( 7073): CheckpointMarkThreadRoots callback created = 0xb042d800
,I/jxcore-log( 6197): Test app app.js loaded
I/jxcore-log( 6197): 
,I/Choreographer( 6197): Skipped 819 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6197): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/art     ( 7073): CheckpointMarkThreadRoots callback created = 0xb042d7d0
I/ActivityManager(  991): Process com.google.android.apps.magazines (pid 6791) has died
,W/Settings( 7073): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7073): startup - clean
I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
I/Babel   ( 7073): deleted: false for 0
,W/ResourcesManager( 7113): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7113): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Finsky  ( 7055): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 7055): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7055): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7055): com.android.vending: cancel(-1050172287) by com.android.vending
,I/ActivityManager(  991): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7146 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MultiDex( 7113): VM with version 2.1.0 has multidex support
I/MultiDex( 7113): install
I/MultiDex( 7113): VM has multidex support, MultiDex support library is disabled.
,V/DownloadManager( 3183): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
D/Finsky  ( 7055): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7055): [1] Libraries$2.run: Finished loading 1 libraries.
V/DownloadManager( 3183): created cursor android.database.sqlite.SQLiteCursor@483661f on behalf of 7055
D/Ads     ( 7055): Skipping gmscore version check
W/AudioCapabilities( 7073): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 7073): Unsupported mime audio/adpcm
W/AudioCapabilities( 7073): Unsupported mime audio/g726
W/AudioCapabilities( 7073): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 7073): Unsupported mime audio/wma-voice
D/Finsky  ( 7055): [1] GmsCoreHelper.cleanupNlp: result=false type=4
W/VideoCapabilities( 7073): Unsupported mime video/mjpg
,W/VideoCapabilities( 7073): Unsupported mime video/theora
D/Finsky  ( 7055): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/JNIHelp ( 7113): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/AudioCapabilities( 7073): Unsupported mime audio/evrc
W/AudioCapabilities( 7073): Unsupported mime audio/qcelp
,W/VideoCapabilities( 7073): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7073): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7073): Unsupported mime audio/qcelp
W/AudioCapabilities( 7073): Unsupported mime audio/evrc
,W/VideoCapabilities( 7073): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7073): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7073): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7073): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7073): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7073): Unrecognized profile 2130706433 for video/avc
,W/ActivityThread( 7113): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7113): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@c91532f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7113): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 7113): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/vclib   ( 7073): onServiceConnected
W/Babel   ( 7073): Attempted to change video mute state without an active call.
I/NotificationManager( 7113): com.google.android.gms: cancel(39789) by com.google.android.gms
I/NotificationManager( 7073): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 7073): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7073): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7073): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7073): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  281): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out( 7073): propertyValue:false
I/Babel   ( 7073): connection state changed from UNKNOWN to CONNECTED
,D/Finsky  ( 7055): [870] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 7055): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager(  991): Process com.google.android.apps.plus (pid 6877) has died
,I/art     ( 7113): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7113): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7146): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7146): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7146): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7146): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 7146): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7146):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7146):   adb logcat -s GAv4
,I/ActivityManager(  991): Process com.google.android.music:main (pid 6901) has died
W/GAv4    ( 7146): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/NativeLibraryUtils( 7113): Install completed successfully. count=14 extracted=0
,W/GAv4    ( 7146): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7146): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
D/WVCdm   (  285): Instantiating CDM.
,I/WVCdm   (  285): CdmEngine::OpenSession
I/WVCdm   (  285): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  285): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  285): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  285): L1 library not specified. Falling Back to L3
,I/WVCdm   (  285): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  285): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  285): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  285): CdmEngine::GenerateKeyRequest
D/WVCdm   (  285): PrepareKeyRequest: nonce=3475667862
I/WebViewFactory( 7146): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7146): Time to load native libraries: 2 ms (timestamps 4672-4674)
I/LibraryLoader( 7146): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7146): Binding Chromium to main looper Looper (main, tid 1) {483661f}
I/LibraryLoader( 7146): Expected native library version number "",actual native library version number ""
I/chromium( 7146): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7146): Initializing chromium process, singleProcess=true
,W/art     ( 7146): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7146): ApplicationContext is null in ApplicationStatus
W/chromium( 7146): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7146): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7146): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7146): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7146): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7146): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7146): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7146): Remote Branch: 
I/Adreno-EGL( 7146): Local Patches: 
I/Adreno-EGL( 7146): Reconstruct Branch: 
V/AudioPolicyService(  285): registerClient() client 0xb41441c0, uid 10079
,W/AudioManagerAndroid( 7146): Requires BLUETOOTH permission
I/NSApplication( 7146): Starting up...
,I/ActivityManager(  991): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7215 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/dex2oat ( 7213): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7213): dex2oat took 107.265ms (threads: 4)
,I/art     ( 7113): CheckpointMarkThreadRoots callback created = 0xb04cae40
,I/Adreno-EGL( 7113): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7113): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7113): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7113): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7113): Remote Branch: 
I/Adreno-EGL( 7113): Local Patches: 
I/Adreno-EGL( 7113): Reconstruct Branch: 
W/ResourcesManager( 7215): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     ( 7113): CheckpointMarkThreadRoots callback created = 0xb04cae30
,I/ActivityManager(  991): Killing 6942:com.lge.email/u0a21 (adj 15): empty #11
,I/Adreno-EGL( 7113): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7113): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7113): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7113): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7113): Remote Branch: 
I/Adreno-EGL( 7113): Local Patches: 
I/Adreno-EGL( 7113): Reconstruct Branch: 
,W/libprocessgroup(  991): failed to open /acct/uid_10021/pid_6942/cgroup.procs: No such file or directory
I/ActivityManager(  991): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7247 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Adreno-EGL( 7113): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7113): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7113): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7113): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7113): Remote Branch: 
I/Adreno-EGL( 7113): Local Patches: 
I/Adreno-EGL( 7113): Reconstruct Branch: 
,I/WVCdm   (  285): CdmEngine::OpenSession
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/MusicStore( 7247): Database version: 120
,I/ActivityManager(  991): Process com.lge.appbox.client (pid 6986) has died
,E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7247): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7247): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7247): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,W/ResourcesManager( 7247): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7247): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7247): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7247): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7247): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3754a946: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7247): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 7247): GMSCore installation verified
I/ConfigStore( 7247): Config Database version: 1
,I/MediaRouter( 7247): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7247): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7247): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7247): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  991): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7286 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 22.557ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 7(224B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 20.192ms
,I/WVCdm   (  285): CdmEngine::QueryKeyControlInfo
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 324us total 20.084ms
I/WVCdm   (  285): CdmEngine::CloseSession
W/WVCdm   (  285): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  285): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  285): CdmEngine::GenerateKeyRequest
D/WVCdm   (  285): PrepareKeyRequest: nonce=3080068840
,I/ActivityManager(  991): Process com.lge.lgdmsclient (pid 6965) has died
I/GHttpClientFactory( 7247): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7247): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 7286): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7286): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7286): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/NotificationManager( 7247): com.google.android.music: cancel(1061) by com.google.android.music
,D/sensors_hal_Time(  991): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  991): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  991): tsOffsetIs: Apps: 116910491419; DSPS: 3929822; Offset : -3023277363
,I/art     (  991): Explicit concurrent mark sweep GC freed 20714(949KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 1.826ms total 142.760ms
,I/LGEmail ( 7286): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7286): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7286): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  991): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7312 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/MusicWidget( 2651): mDelayedStopHandler : unbind
,I/HubEmail( 7286): JNI_OnLoad()
I/HubEmail( 7286): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7286): registerNatives()
I/HubEmail( 7286): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7286): registerNativeMethods()
I/HubEmail( 7286): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7286): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/MusicBrowser( 2011): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2011): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2011): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
,D/MusicBrowser( 2011): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2011): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2011): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2011): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2011): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
W/Settings( 7286): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/MediaFocusControl(  991):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@280e636bcom.lge.music.MediaPlaybackService$6@2d1ec8
D/MusicBrowser( 2011): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
,I/MusicBrowser( 2011): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2011): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2011): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2011): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@1044fbd6
,I/MusicBrowser( 2011): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2011): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2011): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2011): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2011): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2011): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2011): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2011): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2011): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2011): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2011): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,I/MusicBrowser( 2011): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2011): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2011): reset
D/LGDMClient( 7312): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7312): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
V/MediaPlayer[Native]( 2011): setListener
V/MediaPlayer[Native]( 2011): disconnect
V/MediaPlayer[Native]( 2011): destructor
W/ContextImpl( 7312): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7312): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
V/AudioFlinger(  285): releasing 19 from 2011 for -1
V/AudioFlinger(  285):  decremented refcount to 0
V/AudioFlinger(  285): purging stale effects
V/MediaPlayer[Native]( 2011): disconnect
D/MusicBrowser( 2011): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
,D/LGDMClient( 7312): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7312): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/SmartShareClient( 2011): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2011): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2011): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2011): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2011): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2011): [SmartShareManagerClient] unregisterListener: 692534113
W/SmartShareClient( 2011): [SmartShareManagerClient] unregisterListener invalid listener: 692534113
D/LGDMClient( 7312): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/SmartShareClient( 2011): [SmartShareManagerClient] terminate service: 2011/MediaPlaybackService/537519276
I/LGDMClient( 7312): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
E/HomeCloudIF( 2011): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2011): [SmartShareManagerClient] unbindService context:android.app.Application@15720686
I/ActivityManager(  991): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7342 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7312): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7312): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 7312): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7312): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7312): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
V/CloudHub( 2011): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2011): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,D/LGDMClient( 7312): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/CloudHub( 2011): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/ActivityManager(  991): Killing 7011:com.google.android.setupwizard/u0a38 (adj 15): empty #11
I/MusicBrowser( 2011): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2011): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
W/libprocessgroup(  991): failed to open /acct/uid_10038/pid_7011/cgroup.procs: No such file or directory
,I/CloudHub( 2011): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29900
I/ActivityManager(  991): Killing 7037:com.lge.drmservice/u0a51 (adj 15): empty #11
I/AppUp4:AppBoxCP( 7342): onCreate
,W/AppUp4:DB( 7342):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7342):  setFingerPrint start
,I/AppUp4:DB( 7342):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7342):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7342):  SDK version = 0
I/AppUp4:DB( 7342):  beforefinger == newfinger no write in DB
W/libprocessgroup(  991): failed to open /acct/uid_10051/pid_7037/cgroup.procs: No such file or directory
,D/AppUp4:AppBoxApplication( 7342): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7342): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7342): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7342): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7342): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7342): onReceive
,I/AppUp4:CustModeStarterReceiver( 7342): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7342): Context : android.app.ReceiverRestrictedContext@3852590a
D/AppUp4:CustFacade( 7342): isCustomizationCompleted : false
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/AppUp4:CustFacade( 7342): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7342): begin check event
I/AppUp4:CustModeStarterReceiver( 7342): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7342): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7342): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7342): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7342): handleAsyncCustNotification do not startCustService
I/ActivityManager(  991): Killing 7073:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  991): failed to open /acct/uid_10061/pid_7073/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3111): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3111): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3111): networkInfo.isConnected() = true
D/PhoneState( 3111): setPdpRejectCasuse : false
I/ActivityManager(  991): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7364 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7364): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7364): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7364): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  991): Killing 7146:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,D/PhoneMonitor( 7364): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7364): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7364): [parse] Load xml
V/TelephonyAutoProfiling( 7364): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7364): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7364): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  991): failed to open /acct/uid_10079/pid_7146/cgroup.procs: No such file or directory
,V/DownloadManager( 3183): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3183): DownloadService onCreate
,I/DownloadManager( 3183): in removeSpuriousFiles
I/NotificationManager( 3183): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3183): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3183): created cursor android.database.sqlite.SQLiteCursor@16cd9f35 on behalf of 3183
I/DownloadManager( 3183): in trimDatabase
V/DownloadManager( 3183): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3183): created cursor android.database.sqlite.SQLiteCursor@340d1fca on behalf of 3183
I/ActivityManager(  991): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7389 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3183): DownloadService onStartCommand
V/DownloadManager( 3183): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/CheckinService( 4185): Checkin interval check for package: unspecified last checkin: 1452763904266 min interval config: 0 actual interval: 37270
,V/DownloadManager( 3183): created cursor android.database.sqlite.SQLiteCursor@431a458 on behalf of 3183
,V/DownloadManager( 3183): DownloadService onDestroy
,I/ActivityManager(  991): Killing 7055:com.android.vending/u0a36 (adj 15): empty #11
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,W/libprocessgroup(  991): failed to open /acct/uid_10036/pid_7055/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2699): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:32:21
D/UpdateThreadPoolManager( 2699): 2 : This is isUpdating : false
D/WeatherAncestor( 2699): connectivity changed - connection : true
D/Weather_cast( 2699): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2699): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:32:21
D/WeatherService( 2699): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  991): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7417 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  991): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2699): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2699): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2699): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 7417): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/WVCdm   (  285): CdmEngine::CloseSession
,I/WVCdm   (  285): L3 Terminate.
,I/Babel_SMS( 7417): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7417): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7417): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7417): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7417): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7417): MmsConfig.loadFromResources
E/Babel_SMS( 7417): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7417): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7417): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7417): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7417): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7417): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7417): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7417): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7417): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7417): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7417): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7417): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7417): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7417): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7417): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7417): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7417): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7417): found sensor: Motion Accel, handle=46
,W/Settings( 7417): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7417): startup - clean
,I/CheckinRequestBuilder( 4185): Classify the device as Phone.
,I/Babel   ( 7417): deleted: false for 0
,I/art     ( 7417): CheckpointMarkThreadRoots callback created = 0xb042d860
,D/libc-netbsd( 4185): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4185): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4185): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4185): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  281): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
,I/art     ( 7417): CheckpointMarkThreadRoots callback created = 0xb042d840
,D/libc-netbsd(  281): res_queryN name = xxxxx succeed
,I/System.out( 4185): propertyValue:false
I/ActivityManager(  991): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7456 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/libc-netbsd( 4185): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4185): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/AudioCapabilities( 7417): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 7417): Unsupported mime audio/adpcm
,W/AudioCapabilities( 7417): Unsupported mime audio/g726
W/AudioCapabilities( 7417): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7417): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7417): Unsupported mime video/mjpg
W/VideoCapabilities( 7417): Unsupported mime video/theora
D/libc-netbsd( 4185): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4185): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4185): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4185): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 4185): Sending checkin request (9963 bytes)
,W/AudioCapabilities( 7417): Unsupported mime audio/evrc
W/AudioCapabilities( 7417): Unsupported mime audio/qcelp
,W/VideoCapabilities( 7417): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7417): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7417): Unsupported mime audio/qcelp
W/AudioCapabilities( 7417): Unsupported mime audio/evrc
W/VideoCapabilities( 7417): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 7417): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7417): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7417): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7417): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7417): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 7417): onServiceConnected
,W/Babel   ( 7417): Attempted to change video mute state without an active call.
D/libc-netbsd( 7417): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7417): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7417): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7417): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  281): App 10061 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out( 7417): propertyValue:false
I/NotificationManager( 7417): com.google.android.talk: cancel(10436) by com.google.android.talk
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7456): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7456): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 7456): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7456):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7456):   adb logcat -s GAv4
,E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7456): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  242): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  242): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  242): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7456): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 7456): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/Babel   ( 7417): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  991): Killing 6858:com.android.chrome/u0a48 (adj 15): empty #11
W/GAv4    ( 7456): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7456): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/libprocessgroup(  991): failed to open /acct/uid_10048/pid_6858/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 4185): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4185): Failed to find provider info for com.google.android.wearable.settings
,I/WebViewFactory( 7456): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/art     ( 3909): Explicit concurrent mark sweep GC freed 2232(83KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 374us total 30.331ms
,I/LibraryLoader( 7456): Time to load native libraries: 2 ms (timestamps 9821-9823)
I/LibraryLoader( 7456): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7456): Binding Chromium to main looper Looper (main, tid 1) {483661f}
,I/LibraryLoader( 7456): Expected native library version number "",actual native library version number ""
I/chromium( 7456): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7456): Initializing chromium process, singleProcess=true
,W/art     ( 7456): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7456): ApplicationContext is null in ApplicationStatus
W/chromium( 7456): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7456): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7456): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7456): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7456): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7456): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7456): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7456): Remote Branch: 
I/Adreno-EGL( 7456): Local Patches: 
I/Adreno-EGL( 7456): Reconstruct Branch: 
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinRequestBuilder( 4185): Classify the device as Phone.
,V/AudioPolicyService(  285): registerClient() client 0xb4027300, uid 10079
W/AudioManagerAndroid( 7456): Requires BLUETOOTH permission
I/NSApplication( 7456): Starting up...
I/CheckinTask( 4185): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4185): Checking schedule, now: 1452763942970 next: 1453291191960
I/CheckinService( 4185): active receiver: disabled
,I/ActivityManager(  991): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7523 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  991): Killing 7215:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,I/CheckinService( 4185): Checking schedule, now: 1452763943083 next: 1453291191960
I/CheckinService( 4185): active receiver: disabled
,W/libprocessgroup(  991): failed to open /acct/uid_10086/pid_7215/cgroup.procs: No such file or directory
,D/CheckinService( 4185): Recording last checkin time for package unspecified as 1452763943098
,I/ActivityManager(  991): Killing 7286:com.lge.email/u0a21 (adj 15): empty #11
,I/ActivityManager(  991): Killing 7247:com.google.android.music:main/u0a81 (adj 15): empty #12
,W/libprocessgroup(  991): failed to open /acct/uid_10021/pid_7286/cgroup.procs: No such file or directory
,W/libprocessgroup(  991): failed to open /acct/uid_10081/pid_7247/cgroup.procs: No such file or directory
I/ActivityManager(  991): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7542 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  991): Killing 2011:com.lge.music/u0a28 (adj 15): empty #11
V/AudioFlinger(  285): 2011 died, releasing its sessions
V/AudioFlinger(  285):  pid 1758 @ 0
V/AudioFlinger(  285):  pid 3111 @ 1
V/AudioFlinger(  285):  pid 3111 @ 2
,W/libprocessgroup(  991): failed to open /acct/uid_10028/pid_2011/cgroup.procs: No such file or directory
,W/ResourcesManager( 7542): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  991): Killing 7312:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  991): failed to open /acct/uid_1000/pid_7312/cgroup.procs: No such file or directory
,D/GCM     ( 1739): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  991): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7569 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 7569): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/BluetoothManagerService(  991): Message: 20
D/BluetoothManagerService(  991): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e94a7c4:true
,D/BluetoothAdapterService(746746865)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@699014f
D/BluetoothAdapterService(746746865)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@699014f
,I/ActivityManager(  991): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7587 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/LGMDMManager( 7569): Create singleton instance
,D/UEI.SmartControl( 7587): Quickset Services start...
,I/UEI.SmartControl( 7587): Manufacture = LGE
D/UEI.SmartControl( 7587): File observer start...
E/UEI.SmartControl( 7587): IR Port is disabled: false
D/UEI.SmartControl( 7587): Starting file observer...
D/UEI.SmartControl( 7587): Extracting JNI libs...
D/UEI.SmartControl( 7587): --- this system supports 32-bit or 64-bit only
I/AudioManager( 7569): getMode name:com.lge.qremote
,D/libc-netbsd( 1739): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1739): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1739): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1739): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  281): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
I/CheckinService( 4185): Checkin interval check for package: unspecified last checkin: 1452763943098 min interval config: 0 actual interval: 1032
,I/CheckinService( 4185): Checking schedule, now: 1452763944141 next: 1453291191960
I/CheckinService( 4185): active receiver: disabled
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
,I/System.out( 1739): propertyValue:false
D/WearableService( 1739): callingUid 10006, callindPid: 1739
,D/LocationInitializer( 4185): Restart initialization of location
,D/AuthorizationBluetoothService( 1739): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
W/ContextImpl( 3567): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,E/MDM     ( 1739): [105] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/libc-netbsd( 1739): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1739): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/UEI.SmartControl( 7587): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/libc-netbsd( 1739): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1739): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/UEI.SmartControl( 7587): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7587): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 7587): --- Selecting new region: 2
I/UEI.SmartControl( 7587): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7587): Platform has CIR...
D/UEI.SmartControl( 7587): NO CIR support, need to check package...
I/UEI.SmartControl( 7587): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7587): QS Service created
I/art     (  991): Explicit concurrent mark sweep GC freed 17045(830KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.907ms total 170.430ms
,E/lowmemorykiller(  240): Error writing /proc/7417/oom_score_adj; errno=22
V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1739): com.google.android.gms: cancel(0) by com.google.android.gms
E/UEI.SmartControl( 7587): QS start get config
,I/ActivityManager(  991): Process com.google.android.talk (pid 7417) has died
,W/GCoreFlp( 1739): No location to return for getLastLocation()
W/FusedLocationProvider( 1739): location=null
,V/SetupWizard( 7364): Connected to Gservices successfully
,I/AudioManager( 7569): getMode name:com.lge.qremote
,D/UEI.SmartControl( 7587): Loading JNI Libs...
D/UEI.SmartControl( 7587):  configuring local db...
D/GCM     ( 1739): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1739): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  991): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7634 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 20.896ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 21.127ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 21.057ms
W/ResourcesManager( 7634): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 7587):  ---- Has DB8: true
,D/UEI.SmartControl( 7587): QS start statue = true Error code = 0
D/UEI.SmartControl( 7587): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7587): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7587): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7587): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7587): IrrcClient ++ 
D/irrcClient( 7587): getIrrcService ++ 
,D/irrcClient( 7587): getIrrcService -- 
D/irrcClient( 7587): IrrcClient -- 
W/irrc_jni( 7587): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7587): Services init done
D/UEI.SmartControl( 7587): QS Service init finished
D/UEI.SmartControl( 7587): QS Service version name: 0.1.73
D/UEI.SmartControl( 7587): QS Service version code: 1073
D/UEI.SmartControl( 7587): Service requested: Control
,I/UEI.SmartControl( 7587): Device manager: loading config....
D/UEI.SmartControl( 7587): Config is loaded...
D/UEI.SmartControl( 7587): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 7587):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7587): Notify AllClients services are ready: 0
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/UEI.SmartControl( 7587): Internal service binding...
D/UEI.SmartControl( 7587): -----IControl: 11
D/UEI.SmartControl( 7587): Caller: com.lge.qremote
D/UEI.SmartControl( 7587): ------------ IControl registerCallback...
I/UEI.SmartControl( 7587): Registering callback...
D/UEI.SmartControl( 7587): -----IControl: 19
D/UEI.SmartControl( 7587): Caller: com.lge.qremote
I/UEI.SmartControl( 7587): Registering Services Ready callback...
I/UEI.SmartControl( 7587): Notify client services are ready...
,D/UEI.SmartControl( 7587): -----IControl: 8
I/Babel_SMS( 7634): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7634): MmsConfig.loadMmsSettings
D/UEI.SmartControl( 7587): Caller: com.lge.qremote
I/Babel_SMS( 7634): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7634): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7634): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7634): MmsConfig.loadFromResources
E/Babel_SMS( 7634): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7634): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7634): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7634): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7634): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7634): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7634): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7634): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7634): found sensor: LGE Rotation Vector Sensor, handle=36
,D/SensorManager( 7634): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7634): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7634): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7634): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7634): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7634): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7634): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7634): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7634): found sensor: Motion Accel, handle=46
I/art     ( 7634): CheckpointMarkThreadRoots callback created = 0xb042d850
,W/Settings( 7634): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 7634): startup - clean
,I/art     ( 7634): CheckpointMarkThreadRoots callback created = 0xb042d830
,I/Babel   ( 7634): deleted: false for 0
,I/AudioManager( 7569): getMode name:com.lge.qremote
,W/AudioCapabilities( 7634): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 7634): Unsupported mime audio/adpcm
W/AudioCapabilities( 7634): Unsupported mime audio/g726
W/AudioCapabilities( 7634): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7634): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 7634): Unsupported mime video/mjpg
W/VideoCapabilities( 7634): Unsupported mime video/theora
I/AudioManager( 7569): getMode name:com.lge.qremote
,I/AudioManager( 7569): getMode name:com.lge.qremote
,W/AudioCapabilities( 7634): Unsupported mime audio/evrc
W/AudioCapabilities( 7634): Unsupported mime audio/qcelp
W/VideoCapabilities( 7634): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7634): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7634): Unsupported mime audio/qcelp
W/AudioCapabilities( 7634): Unsupported mime audio/evrc
,W/VideoCapabilities( 7634): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 7634): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7634): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7634): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7634): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7634): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7634): onServiceConnected
W/Babel   ( 7634): Attempted to change video mute state without an active call.
I/NotificationManager( 7634): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/[SystemUI]QPairHandler( 1380): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1838): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QSlideListController( 1380): onReceive = android.intent.action.PACKAGE_CHANGED
I/InputReader(  991): Reconfiguring input devices.  changes=0x00000010
,W/[SystemUI]QSlideLoader( 1380): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1380): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1380): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1380): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,I/[LGHome]EVENT( 1884): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1884): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1884): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/AppUp4:CustModeStarterReceiver( 7342): onReceive
I/AppUp4:CustModeStarterReceiver( 7342): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 7342): Context : android.app.ReceiverRestrictedContext@3852590a
,D/AppUp4:CustFacade( 7342): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7342): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7342): begin check event
I/AppUp4:CustModeStarterReceiver( 7342): Event For Nothing, skip.
W/ResourcesManager( 7634): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7634): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/NotificationManager( 7634): com.google.android.talk: cancel(8) by com.google.android.talk
I/[LGHome]Launcher( 1884): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,V/JNIHelp ( 7634): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  991): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7680 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/art     ( 1793): Background sticky concurrent mark sweep GC freed 90126(5MB) AllocSpace objects, 0(0B) LOS objects, 32% free, 10MB/14MB, paused 2.452ms total 142.942ms
W/System  ( 7634): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7634): Installed default security provider GmsCore_OpenSSL
,D/administrator(  991): Handling package changes for user 0
,W/ResourcesManager( 7680): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7680): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7680): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
D/LCardEmulationManager( 1793): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1793): getDefaultRoute
,I/AppConfig( 7680): Total System Memory = 906309632
,I/GalleryUtils( 7680): Application Heap = 96 MB
I/AppConfig( 7680): App Tier : NOT_DEF
,D/SystemHelper( 7680): region [EU], country [EU], operator [OPEN], sub-operator []
I/NotificationService(  991): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  991): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  991): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/ResourcesManager(  991): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  991): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7703 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/BackupManagerService(  991): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/BackupManagerService(  991): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  991): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@291196fe
,W/ResourcesManager( 7703): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7703): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7703): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7703): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7703): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourceType(  991): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,W/ProcessCpuTracker(  991): Skipping unknown process pid 7672
,W/ProcessCpuTracker(  991): Skipping unknown process pid 7675
I/[LGHome]EVENT( 1884): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/ActivityManager(  991): Process com.google.android.apps.magazines (pid 7456) has died
,I/GCoreNlp( 1739): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  991): applying state to connected service
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/SystemConfig( 7703): BUILD Country: EU
I/SystemConfig( 7703): BUILD Operator: OPEN
I/ActivityManager(  991): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7726 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 7703): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7703): existFile = false
I/SystemConfig( 7703): canReadFile = false
I/SystemConfig( 7703): systemFeature RCS result false
,D/SystemConfig( 7703): refreshRcsSupport() :false
,I/LockScreenSettings( 7726): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7726): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 7726): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7726): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7726): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7726): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/UpdateIcingCorporaServi( 1944): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  991): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7747 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  991): ELAPSED_WAKEUP set : Alarm{37b7289d type 2 when 123948 com.google.android.gms} when 123948
I/art     ( 7542): CheckpointMarkThreadRoots callback created = 0xaaf35360
I/art     ( 7542): CheckpointMarkThreadRoots callback created = 0xaaf35330
,I/ActivityManager(  991): Killing 7389:com.lge.drmservice/u0a51 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1944): UpdateCorporaTask done [took 118 ms] updated apps [took 118 ms] 
,W/libprocessgroup(  991): failed to open /acct/uid_10051/pid_7389/cgroup.procs: No such file or directory
,I/ActivityManager(  991): Process com.lge.qremote (pid 7569) has died
,D/Finsky  ( 7747): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/Finsky  ( 7747): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7747): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7747): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7747): com.android.vending: cancel(-1050172287) by com.android.vending
,D/Ads     ( 7747): Skipping gmscore version check
,V/DownloadManager( 3183): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3183): created cursor android.database.sqlite.SQLiteCursor@18c56e96 on behalf of 7747
I/ActivityManager(  991): Killing 7523:com.android.chrome/u0a48 (adj 15): empty #11
,D/Finsky  ( 7747): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7747): [1] Libraries$2.run: Finished loading 1 libraries.
W/libprocessgroup(  991): failed to open /acct/uid_10048/pid_7523/cgroup.procs: No such file or directory
,D/PackageBroadcastService( 4185): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 4185): Null package name or gms related package.  Ignoreing.
D/Finsky  ( 7747): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/Icing   ( 4185): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 7747): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/Icing   ( 4185): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4185): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  991): Killing 7364:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  991): failed to open /acct/uid_10038/pid_7364/cgroup.procs: No such file or directory
,I/ActivityManager(  991): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7815 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 7815): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  991): Message: 20
D/BluetoothManagerService(  991): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3165d93c:true
,D/BluetoothAdapterService(746746865)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@699014f
D/BluetoothAdapterService(746746865)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@699014f
V/LGMDMManager( 7815): Create singleton instance
,D/UEI.SmartControl( 7587): Internal timer expired: 1
,I/AudioManager( 7815): getMode name:com.lge.qremote
,D/UEI.SmartControl( 7587): -----IControl: 11
D/UEI.SmartControl( 7587): Caller: com.lge.qremote
D/UEI.SmartControl( 7587): ------------ IControl registerCallback...
I/UEI.SmartControl( 7587): Registering callback...
D/UEI.SmartControl( 7587): -----IControl: 19
D/UEI.SmartControl( 7587): Caller: com.lge.qremote
,I/UEI.SmartControl( 7587): Registering Services Ready callback...
I/UEI.SmartControl( 7587): Notify client services are ready...
D/UEI.SmartControl( 7587): -----IControl: 8
D/UEI.SmartControl( 7587): Caller: com.lge.qremote
I/AudioManager( 7815): getMode name:com.lge.qremote
I/ActivityManager(  991): Killing 7342:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  991): failed to open /acct/uid_10011/pid_7342/cgroup.procs: No such file or directory
,I/AudioManager( 7815): getMode name:com.lge.qremote
I/AudioManager( 7815): getMode name:com.lge.qremote
,D/KeyguardUpdateMonitor( 1380): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1810): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1380): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1380): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1380): On Skip Timer : true
D/KeyguardUpdateMonitor( 1380): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/[SystemUI]LGPowerUI( 1380): onReceive = android.intent.action.BATTERY_CHANGED
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/WifiController(  991): battery changed pluggedType: 2
W/Settings(  991): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  991): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1380): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
,D/LEDHandler( 1810): ACTION_BATTERY_CHANGED : plugged type=2
,D/LEDHandler( 1810): Battery Level Remaining: 100%
D/LEDHandler( 1810): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
D/charger_monitor(  482): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[SystemUI]BatterySaverHandler( 1380): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  991): Killing 7634:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  991): failed to open /acct/uid_10061/pid_7634/cgroup.procs: No such file or directory
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/sensors_hal_Time(  991): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  991): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  991): tsOffsetIs: Apps: 136915274380; DSPS: 4585339; Offset : -3023286547
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/AlarmManager(  991): ELAPSED_WAKEUP set : Alarm{8851527 type 2 when 141447 com.google.android.gms} when 141447
,I/art     (  991): Explicit concurrent mark sweep GC freed 36196(1732KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.615ms total 169.387ms
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1739): Vacuum at: now=1452763964910 tag=VacuumService
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PhenotypeConfigurator( 1739): Scheduling Phenotype for one-off execution 8550 seconds from now (1452763965429)
,D/GetConfigurationSnapshotOperation( 1739): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1739): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1739): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  991): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1739): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1739): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1739): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1739): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  281): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
,I/System.out( 1739): propertyValue:false
,D/libc-netbsd( 1739): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1739): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1739): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1739): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/LocationManagerService(  991): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,D/LocationManagerService(  991): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LocationManagerService(  991): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  991): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  991): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/PowerManagerService(  991): ALS enabled for SRE
D/PowerManagerServiceEx(  991): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (29965 ms ago)
,D/qdlights(  991): set_light_backlight: 253
,D/qdlights(  991): set_light_backlight: 250
D/qdlights(  991): set_light_backlight: 246
,D/qdlights(  991): set_light_backlight: 243
,D/qdlights(  991): set_light_backlight: 240
,D/qdlights(  991): set_light_backlight: 236
,D/qdlights(  991): set_light_backlight: 233
,D/qdlights(  991): set_light_backlight: 230
,D/qdlights(  991): set_light_backlight: 226
,D/qdlights(  991): set_light_backlight: 223
,D/qdlights(  991): set_light_backlight: 220
,D/qdlights(  991): set_light_backlight: 216
,D/qdlights(  991): set_light_backlight: 213
,D/qdlights(  991): set_light_backlight: 210
,D/qdlights(  991): set_light_backlight: 206
,D/qdlights(  991): set_light_backlight: 203
,D/qdlights(  991): set_light_backlight: 200
,D/qdlights(  991): set_light_backlight: 196
,D/qdlights(  991): set_light_backlight: 193
,D/qdlights(  991): set_light_backlight: 190
,D/qdlights(  991): set_light_backlight: 186
,D/qdlights(  991): set_light_backlight: 183
,D/qdlights(  991): set_light_backlight: 180
,D/qdlights(  991): set_light_backlight: 176
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/qdlights(  991): set_light_backlight: 173
,D/qdlights(  991): set_light_backlight: 170
,D/qdlights(  991): set_light_backlight: 166
,D/qdlights(  991): set_light_backlight: 163
,D/qdlights(  991): set_light_backlight: 160
,D/qdlights(  991): set_light_backlight: 156
,D/qdlights(  991): set_light_backlight: 153
,D/qdlights(  991): set_light_backlight: 150
,D/qdlights(  991): set_light_backlight: 146
,D/qdlights(  991): set_light_backlight: 143
,D/qdlights(  991): set_light_backlight: 140
,D/qdlights(  991): set_light_backlight: 136
,D/qdlights(  991): set_light_backlight: 133
,D/qdlights(  991): set_light_backlight: 130
,D/qdlights(  991): set_light_backlight: 126
,D/qdlights(  991): set_light_backlight: 123
,D/qdlights(  991): set_light_backlight: 120
,D/qdlights(  991): set_light_backlight: 116
,D/qdlights(  991): set_light_backlight: 113
,D/qdlights(  991): set_light_backlight: 110
,D/qdlights(  991): set_light_backlight: 106
,D/qdlights(  991): set_light_backlight: 103
,D/qdlights(  991): set_light_backlight: 100
,D/qdlights(  991): set_light_backlight: 96
,D/qdlights(  991): set_light_backlight: 93
,D/qdlights(  991): set_light_backlight: 90
,D/qdlights(  991): set_light_backlight: 86
,D/qdlights(  991): set_light_backlight: 83
,D/qdlights(  991): set_light_backlight: 80
,D/qdlights(  991): set_light_backlight: 76
,D/qdlights(  991): set_light_backlight: 73
,D/qdlights(  991): set_light_backlight: 70
,D/qdlights(  991): set_light_backlight: 66
,D/qdlights(  991): set_light_backlight: 63
,D/qdlights(  991): set_light_backlight: 60
,D/qdlights(  991): set_light_backlight: 56
,D/qdlights(  991): set_light_backlight: 53
,D/qdlights(  991): set_light_backlight: 50
,D/qdlights(  991): set_light_backlight: 46
,D/qdlights(  991): set_light_backlight: 43
,D/qdlights(  991): set_light_backlight: 40
,D/qdlights(  991): set_light_backlight: 36
,D/qdlights(  991): set_light_backlight: 33
,D/qdlights(  991): set_light_backlight: 30
,D/qdlights(  991): set_light_backlight: 26
,D/qdlights(  991): set_light_backlight: 23
,D/qdlights(  991): set_light_backlight: 20
,D/qdlights(  991): set_light_backlight: 16
,D/qdlights(  991): set_light_backlight: 13
,D/qdlights(  991): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/sensors_hal_Time(  991): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  991): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  991): tsOffsetIs: Apps: 156916027028; DSPS: 5240724; Offset : -3023296526
,I/PowerManagerService(  991): ALS enabled for SRE
D/PowerManagerServiceEx(  991): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (36958 ms ago)
I/PowerManagerService(  991): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  991): ALS enabled for SRE
D/PowerManagerServiceEx(  991): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (36969 ms ago)
W/ContextImpl(  991): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  991): Sleeping (uid 1000)...
D/LPWGController(  991): [updateScreenState] screen on = false
D/LPWGController(  991): disable proximity sensor
D/LPWGController(  991): enable proximity sensor
I/SensorManager(  991): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@ef1310f] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  991): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  991): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  991): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  991): activate: handle is 48, enable
,V/sensors_hal_Ctx(  991): activate sensors is 1400000000000
D/sensors_hal_Thresh(  991): enable: handle=48
I/sensors_hal_SAM(  991): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  991): waitForResponse: timeout=1000
V/sensors_hal_SAM(  991): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  991): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  991): enable: Received response: 0
D/PowerManagerServiceEx(  991): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (37018 ms ago)
D/PowerManagerServiceEx(  991): acquireWakeLockInternal: lock=557698396, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=991
,D/WeatherService( 2699): 2 : TimeTick Intent has been received, Time(hour:min:sec) 10:33:0
,D/WeatherService( 2699): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 10:33:0
,D/PowerManagerServiceEx(  991): releaseWakeLockInternal: lock=557698396 [*alarm*], flags=0x0
I/[SystemUI]TimeTickManager( 1380): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1380): called onTimeUpdated()
,I/[SystemUI]Clock( 1380): called onTimeUpdated()
I/LgeClockWidgetControlView( 1380): called onTimeUpdated()
I/[SystemUI]DateView( 1380): called onTimeUpdated()
I/[SystemUI]DateView( 1380): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1380): handleTimeUpdate
I/Adreno-EGL(  991): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  991): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  991): Build Date: 03/02/15 Mon
I/Adreno-EGL(  991): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  991): Remote Branch: 
I/Adreno-EGL(  991): Local Patches: 
I/Adreno-EGL(  991): Reconstruct Branch: 
,D/PermissionCache(  243): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1021 us)
,I/Sensors (  423): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  991): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  991): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  991): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  991): processInd: handle 48, count=1
V/sensors_hal_Thresh(  991): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  991): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  991): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  991): poll: count: 256
I/sensors_hal_Ctx(  991): poll: released wakelock sensor_ind
D/sensors_hal_Util(  991): waitForResponse: timeout=0
D/LPWGController(  991): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  991): current mode = 1  value = 1 1
I/LPWGController(  991): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  991): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/qdlights(  991): set_light_backlight: 0
,I/SensorManager(  991): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
I/sensors_hal_Ctx(  991): activate: handle is 46, disable
V/sensors_hal_Ctx(  991): activate sensors is 1000000000000
D/sensors_hal_LP2(  991): enable: handle=46
D/sensors_hal_LP2(  991): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  991): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
,D/SurfaceFlinger(  243): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  243): hwc_blank: Blanking display: 0
I/DisplayManagerService(  991): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  991): Display changed displayId=0
,D/DSDPConnection( 1758): Display #0 changed.
,V/sensors_hal_SAM(  991): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  991): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
D/qdhwcomposer(  243): hwc_blank: Done blanking display: 0
D/SurfaceControl(  991): Excessive delay in setPowerMode(): 250ms
,I/qdhwcomposer(  243): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  991): Got set_interactive hint
,D/KeyguardViewMediator( 1380): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1380): notifyScreenOffLocked
,D/KeyguardViewMediator( 1380): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1380): handleNotifyScreenOff
D/WifiServerServiceExt(  991): sendKtScanInterval  mRtspPlay : false
,D/SmartCoverViewMediator( 1339): onScreenTurnedOff(3)
D/ScreenTurnOffBySensor( 1380): unregisterProximitySensor
I/WifiServerServiceExt(  991): set CMD_KT_SCAN_INTERVAL
,V/AudioFlinger(  285): setParameters(): io 0, keyvalue screen_state=on, calling pid 991
D/SmartCoverViewMediator( 1339): notifyScreenOffLocked
D/SmartCoverViewMediator( 1339): handleNotifyScreenOFF
D/StatusBarWindowView( 1380): onScreenTurnedOff why = 3
D/audio_hw_primary(  285): adev_set_parameters: enter: screen_state=on
V/voice   (  285): voice_set_parameters: enter: screen_state=on
V/compress_voip(  285): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  285): voice_extn_compress_voip_set_parameters: exit
V/voice   (  285): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  285): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  285): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  285): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  285): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  285): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  285): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  285): adev_set_parameters: exit with code(0)
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1380): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/GpsLocationProvider(  991): receive broadcast intent, action: android.intent.action.SCREEN_ON
D/KeyguardUpdateMonitor( 1380): handleTimeUpdate
I/[SystemUI]LGPowerUI( 1380): onReceive = android.intent.action.SCREEN_ON
,I/QCNEJ   ( 1838): |CORE| sendScreenState: state:true
I/LEDService( 1810): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1810): stopPatternFlashing()
I/Cliptray Service( 1810): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/qdlights( 1810): set_light_notifications: 0,0,0,0,3
D/Cliptray Service( 1810): lockStatus = 0
I/LEDService( 1810): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1810): set_light_notifications: 0,0,0,0,3
I/LEDService( 1810): updateLightsLocked : turn off led
D/qdlights( 1810): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1810): RESTART MSG
D/LNfcService( 1793): action : android.intent.action.SCREEN_ON
D/NfcServiceNXP( 1793): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1793): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1793): isRequireNfcCRouting() return true
D/LNfcService( 1793): isHCERoutingtoHost() return : true
D/NfcService( 1793): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1793): mEnableLPD: true
D/NfcService( 1793): mEnableReader: false
D/NfcService( 1793): mEnableHostRouting: true
D/NfcService( 1793): newParams.techmask= mTechMask: default
D/NfcService( 1793): mEnableLPD: true
D/NfcService( 1793): mEnableReader: false
D/NfcService( 1793): mEnableHostRouting: true
D/NfcService( 1793): screenState= 3
D/NfcService( 1793): Discovery configuration equal, not updating.
,D/Ulp_jni (  991): JNI:system_update. Event-0
D/SplitWindow(  991): check instance of lgWin Window{be5db7a u0 SearchPanel}
,D/InputDispatcher(  991): Window went away: Window{d0e4508 u0 SearchPanel}
,I/[SystemUI]Clock( 1380): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1380): time changed, timezoneChanged : false
,I/art     ( 1739): Explicit concurrent mark sweep GC freed 96340(5MB) AllocSpace objects, 41(679KB) LOS objects, 40% free, 15MB/26MB, paused 1.785ms total 139.495ms
,V/PhoneApp( 1758): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2699): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 10:33:1
,D/WeatherService( 2699): 2 : ACTION screen on
D/WeatherService( 2699): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2699): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2699): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 10:33:1
W/Settings(  991): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  991): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  991): ACTION_SCREEN_ON
D/AppCleanupService( 4033): android.intent.action.SCREEN_ON
,V/AudioFlinger(  285): setParameters(): io 0, keyvalue screen_state=off, calling pid 991
D/audio_hw_primary(  285): adev_set_parameters: enter: screen_state=off
V/voice   (  285): voice_set_parameters: enter: screen_state=off
V/compress_voip(  285): voice_extn_compress_voip_set_parameters: enter: screen_state=off
,V/compress_voip(  285): voice_extn_compress_voip_set_parameters: exit
V/voice   (  285): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  285): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  285): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  285): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  285): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  285): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  285): adev_set_parameters: exit with code(0)
D/WifiController(  991): CMD_SCREEN_OFF 
D/WifiController(  991): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  991): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1380): onReceive = android.intent.action.SCREEN_OFF
,I/QCNEJ   ( 1838): |CORE| sendScreenState: state:false
,I/LEDService( 1810): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1810): stopPatternFlashing()
D/qdlights( 1810): set_light_notifications: 0,0,0,0,3
I/LEDService( 1810): getCurrentHighestLGLedRecord : size = 1
,D/qdlights( 1810): set_light_notifications: 0,0,0,0,3
I/LEDService( 1810): updateLightsLocked : turn on led
E/LEDService( 1810): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1810): Can't handle this request of patternId:0
D/LEDHandler( 1810): RESTART MSG
D/VolumeVibrator( 1810): clear
I/Cliptray Service( 1810): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1793): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1793): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1884): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1758): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2699): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 10:33:1
D/WeatherService( 2699): 2 : ACTION screen off
D/WeatherService( 2699): 2 : TimeTick Receiver Unregister
D/WeatherService( 2699): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 10:33:1
W/Settings(  991): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  991): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  991): ACTION_SCREEN_OFF
D/AppCleanupService( 4033): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 4033): AppUsageStatsSaveTask
E/NxpNfcJni( 1793): getReconnectState = 0x0
,D/LCardEmulationManager( 1793): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1793): getDefaultRoute
D/LNfcService( 1793): isRequireNfcCRouting() return true
D/LNfcService( 1793): isHCERoutingtoHost() return : true
,D/NfcService( 1793): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1793): mEnableLPD: true
D/NfcService( 1793): mEnableReader: false
D/NfcService( 1793): mEnableHostRouting: true
D/NfcService( 1793): newParams.techmask= mTechMask: 0
D/NfcService( 1793): mEnableLPD: true
D/NfcService( 1793): mEnableReader: false
D/NfcService( 1793): mEnableHostRouting: true
D/NfcService( 1793): screenState= 1
E/NxpNfcJni( 1793): getReconnectState = 0x0
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/Sensors (  423): sns_pwr.c(301):releasing wakelock
,D/KeyguardViewMediator( 1380): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  991): ELAPSED_WAKEUP set : Alarm{1419cf2b type 2 when 162978 com.android.systemui} when 162978
D/PhoneUtils( 1758): getSubIdUsingSlotId() slotId:0 -> subId:-1
,D/PhoneUtils( 1758): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1758): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1758): getCallState : 0
D/PhoneUtils( 1758): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1758): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1758): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1380): isHdmiPluggedIn :false
,D/KeyguardViewMediator( 1380): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  991): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  991): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  991): tsOffsetIs: Apps: 176916703791; DSPS: 5896106; Offset : -3023291072
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1380): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1380): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1380): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1380): On Skip Timer : true
D/PowerService( 1810): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1810): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1810): Battery Level Remaining: 100%
D/LEDHandler( 1810): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1380): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1380): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1380): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
I/[SystemUI]BatterySaverHandler( 1380): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  991): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  991): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  991): battery changed pluggedType: 2
I/ClearcutLoggerApiImpl( 1739): disconnect managed GoogleApiClient
,V/AlarmManager(  991): ELAPSED_WAKEUP set : Alarm{125e7f88 type 2 when 188608 com.google.android.gms} when 188608
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  991): ELAPSED_WAKEUP set : Alarm{847ed21 type 2 when 190142 android} when 190142
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  991): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  991): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  991): tsOffsetIs: Apps: 196917388523; DSPS: 6551489; Offset : -3023307879
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  991): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  991): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  991): tsOffsetIs: Apps: 216918244245; DSPS: 7206877; Offset : -3023306754
,I/[SystemUI]TimeTickManager( 1380): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1380): called onTimeUpdated()
I/[SystemUI]Clock( 1380): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1380): called onTimeUpdated()
I/[SystemUI]DateView( 1380): called onTimeUpdated()
I/[SystemUI]DateView( 1380): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1380): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  991): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  991): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  991): tsOffsetIs: Apps: 236919025383; DSPS: 7862262; Offset : -3023288685
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1810): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1380): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1380): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1380): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1380): On Skip Timer : true
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1380): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1810): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1810): Battery Level Remaining: 100%
D/LEDHandler( 1810): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1380): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1380): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/[SystemUI]BatterySaverHandler( 1380): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  991): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  991): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  991): battery changed pluggedType: 2
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  991): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  991): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  991): tsOffsetIs: Apps: 256919709073; DSPS: 8517645; Offset : -3023306951
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  991): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  991): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  991): tsOffsetIs: Apps: 276920602973; DSPS: 9173034; Offset : -3023298061
,I/[SystemUI]TimeTickManager( 1380): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1380): called onTimeUpdated()
I/[SystemUI]Clock( 1380): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1380): called onTimeUpdated()
I/[SystemUI]DateView( 1380): called onTimeUpdated()
I/[SystemUI]DateView( 1380): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1380): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  991): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  991): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  991): tsOffsetIs: Apps: 296921459423; DSPS: 9828422; Offset : -3023295999
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1380): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1380): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1380): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1380): On Skip Timer : true
D/PowerService( 1810): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1810): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1810): Battery Level Remaining: 100%
D/LEDHandler( 1810): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1380): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1380): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1380): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/[SystemUI]BatterySaverHandler( 1380): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  991): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  991): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  991): battery changed pluggedType: 2
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  991): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  991): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  991): tsOffsetIs: Apps: 316922225301; DSPS: 10483807; Offset : -3023293191
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/PowerService( 1810): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1380): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1380): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1380): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1380): On Skip Timer : true
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1380): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1810): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1380): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1380): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1380): On Skip Timer : true
D/KeyguardUpdateMonitor( 1380): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1380): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1380): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
D/LEDHandler( 1810): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1810): Battery Level Remaining: 100%
D/LEDHandler( 1810): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1380): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  991): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  991): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  991): battery changed pluggedType: 2
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1380): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1810): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1380): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1380): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1380): On Skip Timer : true
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1810): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1810): Battery Level Remaining: 100%
D/LEDHandler( 1810): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1380): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1380): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1380): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/[SystemUI]BatterySaverHandler( 1380): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  991): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  991): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  991): battery changed pluggedType: 2
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6197): --= Surplus to requirements =--
I/jxcore-log( 6197): 
I/jxcore-log( 6197): ****TEST TOOK:  ms ****
I/jxcore-log( 6197): 
I/jxcore-log( 6197): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6197): 
,D/AndroidRuntime( 7971): 
D/AndroidRuntime( 7971): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7971): CheckJNI is OFF
,D/AndroidRuntime( 7971): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  991): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
,I/ActivityManager(  991): Killing 6197:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
W/PackageSettings(  991): Skipping PackageSetting{1620b0de com.example.hello/10317} due to missing metadata
,I/WindowState(  991): WIN DEATH: Window{3bbc5c1b u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  991): Focus left window: Window{3bbc5c1b u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  991): Window went away: Window{3bbc5c1b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  991):   Force finishing activity ActivityRecord{2e41452d u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  991): Display changed displayId=0
D/DSDPConnection( 1758): Display #0 changed.
,W/ActivityManager(  991): Spurious death for ProcessRecord{39663546 6197:com.test.thalitest/u0a316}, curProc for 6197: null
I/ActivityManager(  991): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  991):   Force finishing activity ActivityRecord{2e41452d u0 com.test.thalitest/.MainActivity t222 f}
,W/ActivityManager(  991): Duplicate finish request for ActivityRecord{2e41452d u0 com.test.thalitest/.MainActivity t222 f}
,D/KeyguardModel( 1380): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/QCNEJ   ( 1838): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/InputReader(  991): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1739): Ignoring removeGeofence because network location is disabled.
I/art     ( 1944): Explicit concurrent mark sweep GC freed 9460(550KB) AllocSpace objects, 3(71KB) LOS objects, 40% free, 12MB/21MB, paused 2.416ms total 87.685ms
,W/System.err( 3567): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3567): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3567): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3567): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3567): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3567): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3567): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3567): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3567): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3567): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3567): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3567): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,I/ActivityManager(  991): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8005 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1884): [Launcher.java:5203:onStart()]onStart
,I/art     ( 4185): Explicit concurrent mark sweep GC freed 4162(216KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 14MB/18MB, paused 1.128ms total 127.914ms
I/[LGHome]EVENT( 1884): [Launcher.java:776:onResume()]onResume
,D/KeyguardModel( 1380): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1380): createShortcutInfo...
I/[SystemUI]QSlideListController( 1380): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 1884): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1884): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/KeyguardModel( 1380): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1380): createShortcutInfo...
,I/[LGHome]LGActivityUtil( 1884): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1884): [Launcher.java:929:onResume()]onResume end
I/Activity( 1884): Activity.onPostResume() called 
W/ResourcesManager( 1380): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1380): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourceType( 1380): No package identifier when getting value for resource number 0x00000000
,W/PackageManager( 1380): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1380): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1380): createShortcutInfo...
I/[LGHome]EVENT( 1884): [Launcher.java:986:onPause()]onPause
,W/ResourcesManager( 1380): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1380): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1380): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,D/KeyguardModel( 1380): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1380): createShortcutInfo...
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1380): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1380): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
W/ResourcesManager( 1380): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1380): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1380): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourceType( 1380): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1380): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,D/KeyguardModel( 1380): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1380): createShortcutInfo...
I/art     (  991): Explicit concurrent mark sweep GC freed 42650(2MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 3.228ms total 235.819ms
I/art     (  991): WaitForGcToComplete blocked for 142.960ms for cause Explicit
D/KeyguardModel( 1380): handleShortcutListChanged...
,W/[LGHome]LGWallpaperInfo( 1884): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1884): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
D/KeyguardModel( 1380): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1380): createShortcutInfo...
,D/KeyguardModel( 1380): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1380): createShortcutInfo...
W/ResourceType( 1380): No package identifier when getting value for resource number 0x00000000
I/SystemUI[Framework](  991): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/PackageManager( 1380): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1380): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1380): createShortcutInfo...
W/ResourceType( 1380): No package identifier when getting value for resource number 0x00000000
,W/PackageManager( 1380): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
W/PhoneWindowManagerEx(  991): Call!!!getLGSystemUiVisibility. =0x0
D/KeyguardModel( 1380): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1380): createShortcutInfo...
D/StatusBarManagerServiceEx(  991): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  991): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  991): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2917df1a,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  991): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  991): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  991): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  991): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  991): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  991): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2917df1a,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  991): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,W/ResourceType( 1380): No package identifier when getting value for resource number 0x00000000
D/InputDispatcher(  991): Focus entered window: Window{21ce4812 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/PackageManager( 1380): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1380): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1380): createShortcutInfo...
D/KeyguardModel( 1380): handleShortcutListChanged...
W/ResourcesManager( 8005): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8005): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/[LGHome]EVENT( 1884): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
W/ResourcesManager( 8005): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[LGHome]LGPlusHomeDBManager( 1884): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1884): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
I/[LGHome]EVENT( 1884): [Launcher.java:5214:onStop()]onStop
I/[LGHome]EVENT( 1884): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,I/PhoneWindow( 1884): [setNavigationBarColor] color=0x 0
D/administrator(  991): Handling package changes for user 0
,I/LGEmail ( 8005): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,I/art     (  991): Explicit concurrent mark sweep GC freed 5418(302KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 11.776ms total 238.164ms
W/InputMethodManagerService(  991): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,W/InputMethodManagerService(  991): Got RemoteException sending setActive(false) notification to pid 6197 uid 10316
D/LGEmail ( 8005): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/[LGHome]Launcher.Model( 1884): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1884): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/Timeline(  991): Timeline: Activity_windows_visible id: ActivityRecord{11da5a9 u0 com.lge.launcher2/.Launcher t221} time:335937
,I/[LGHome]EVENT( 1884): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1884): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1884): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1884): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
D/AndroidRuntime( 7971): Shutting down VM
,W/IInputConnectionWrapper( 1884): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1884): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1884): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1612): Unable to connect to the editor to retrieve text... will retry later
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1884): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1884): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 1884): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,D/LCardEmulationManager( 1793): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1793): getDefaultRoute
W/IInputConnectionWrapper( 1884): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1884): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1884): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/Resources( 1884): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
,W/Resources( 1884): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1884): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1884): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1884): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
,W/Resources( 1884): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1884): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
I/NotificationService(  991): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  991): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  991): Receieved: android.intent.action.PACKAGE_REMOVED
W/Resources( 1884): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1884): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1884): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
D/PhoneStatusBar( 1380): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
,D/PhoneStatusBar( 1380): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1380): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1380):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1380): , Keyguard show=false, IME shown=false, Panel expanded=false
D/TaskPersister(  991): removeObsoleteFile: deleting file=222_task.xml
,W/Resources( 1884): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1884): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
,I/PackageChangeReceiver( 8005): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/ActivityManager(  991): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8032 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  991): Killing 7680:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/libprocessgroup(  991): failed to open /acct/uid_10023/pid_7680/cgroup.procs: No such file or directory
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1884): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
W/ResourcesManager(  991): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/AppUp4:AppBoxCP( 8032): onCreate
,W/AppUp4:DB( 8032):  [AppBoxDatabaseHelper] construct
E/SQLiteDatabase( 8032): Failed to open database '/data/data/com.lge.appbox.client/databases/appbox.db'.
E/SQLiteDatabase( 8032): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8032): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8032): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/SQLiteDatabase( 8032): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/SQLiteDatabase( 8032): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/SQLiteDatabase( 8032): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/SQLiteDatabase( 8032): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8032): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/SQLiteDatabase( 8032): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/SQLiteDatabase( 8032): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/SQLiteDatabase( 8032): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 8032): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 8032): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8032): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 8032): 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
E/SQLiteDatabase( 8032): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
E/SQLiteDatabase( 8032): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
E/SQLiteDatabase( 8032): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
E/SQLiteDatabase( 8032): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
E/SQLiteDatabase( 8032): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
E/SQLiteDatabase( 8032): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
E/SQLiteDatabase( 8032): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 8032): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8032): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 8032): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/SQLiteDatabase( 8032): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 8032): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 8032): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/SQLiteDatabase( 8032): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/AndroidRuntime( 8032): Shutting down VM
,--------- beginning of crash
E/AndroidRuntime( 8032): FATAL EXCEPTION: main
E/AndroidRuntime( 8032): Process: com.lge.appbox.client, PID: 8032
E/AndroidRuntime( 8032): java.lang.RuntimeException: Unable to get provider com.lge.appbox.databases.AppBoxContentProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8032): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5106)
E/AndroidRuntime( 8032): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
E/AndroidRuntime( 8032): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
E/AndroidRuntime( 8032): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
E/AndroidRuntime( 8032): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 8032): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8032): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 8032): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/AndroidRuntime( 8032): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8032): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8032): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/AndroidRuntime( 8032): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/AndroidRuntime( 8032): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8032): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 8032): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/AndroidRuntime( 8032): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/AndroidRuntime( 8032): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/AndroidRuntime( 8032): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/AndroidRuntime( 8032): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 8032): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/AndroidRuntime( 8032): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/AndroidRuntime( 8032): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/AndroidRuntime( 8032): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/AndroidRuntime( 8032): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 8032): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 8032): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 8032): 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
E/AndroidRuntime( 8032): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
E/AndroidRuntime( 8032): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
E/AndroidRuntime( 8032): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
E/AndroidRuntime( 8032): 	... 11 more
E/[LgeWidgetLib]LgeAppWidgetHostView( 1884): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1884): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1884): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1884): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,E/DropBoxManagerService(  991): Can't write: system_app_crash
E/DropBoxManagerService(  991): java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  991): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  991): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  991): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  991): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  991): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  991): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12621)
E/DropBoxManagerService(  991): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  991): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  991): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  991): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  991): 	... 5 more
I/[LGHome]EVENT( 1884): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]Launcher( 1884): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume

```
