#### Test 549702619369e5e_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
D/Finsky  ( 6037): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 6037): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6037): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6037): com.android.vending: cancel(-1050172287) by com.android.vending
V/DownloadManager( 3195): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3195): created cursor android.database.sqlite.SQLiteCursor@9f2b119 on behalf of 6037
D/Finsky  ( 6037): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6037): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 6037): Skipping gmscore version check
D/Finsky  ( 6037): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 4164): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
D/Finsky  ( 6037): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
--------- beginning of system
I/ActivityManager(  831): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6095 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/PackageBroadcastService( 4164): Null package name or gms related package.  Ignoreing.
I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 317us total 25.650ms
I/Icing   ( 4164): updateResources: need to parse f{com.google.android.gms}
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 21.766ms
W/ResourcesManager( 6095): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 21.425ms
D/CalendarProvider2( 6095): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@32de1493
D/CalendarProvider2( 6095): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 6095): Created com.android.providers.calendar.CalendarAlarmManager@3d1d5fc(com.android.providers.calendar.CalendarProvider2@32de1493)
D/CalendarProviderBroadcastReceiver( 6095): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6095): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 6095): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 6095): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6095): [getOrCreateCalendarAlarmManager]
D/CalendarProvider2( 6095): [IntentService] Release Lock
D/CalendarProvider2( 6095): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  831): Killing 5774:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  831): failed to open /acct/uid_10053/pid_5774/cgroup.procs: No such file or directory
D/AndroidRuntime( 6092): 
D/AndroidRuntime( 6092): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6092): CheckJNI is OFF
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
D/AndroidRuntime( 6092): Calling main entry com.android.commands.am.Am
I/ActivityManager(  831): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  831): setTaskToReturnTo : TaskRecord{3d295310 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  831): setTaskToReturnTo : TaskRecord{3d295310 #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  831): AppWindowTokenEx init.. 
D/ContextHelper(  831): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/[LGHome]EVENT( 1876): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  831): Focus left window: Window{18b98781 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 6092): Shutting down VM
D/SplitWindow(  831): check instance of lgWin Window{1c4b571a u0 Starting com.test.thalitest}
I/ActivityManager(  831): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6138 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1876): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/HotwordDetector( 1943): Closing mic
I/MicrophoneInputStream( 1943): mic_close com.google.android.apps.gsa.speech.audio.u@3e006a14
I/[LGHome]EVENT( 1876): [Launcher.java:5214:onStop()]onStop
V/AudioRecord( 1943): stop()
D/AudioRecord( 1943): AudioRecord->stop()
V/AudioFlinger(  288): RecordHandle::stop()
V/AudioFlinger(  288): RecordThread::stop
V/AudioFlinger(  288): Record stopped OK
V/AudioPolicyManager(  288): stopInput() input 17
V/AudioPolicyService(  288): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  288): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  288): AudioCommandThread() waking up
V/AudioPolicyService(  288): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  288): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  288): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  288): ThreadBase::setParameters() routing=0
V/AudioFlinger(  288): sendConfigEvent_l() num events 1 event 2
I/WindowStateAnimator(  831): Starting window displayed
V/AudioFlinger(  288): processConfigEvents_l() remaining events 1
V/AudioFlinger(  288): processConfigEvents_l() DONE thread 0xb383d000
D/audio_hw_primary(  288): in_standby: enter: stream (0xb546e240) usecase(7: audio-record)
I/SystemUI[Framework](  831): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1375): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  831): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  831): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  831): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  831): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@21de9a98,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  831): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1375): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1375):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1375): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1375): draw background and invalidate : color = 15000000
D/BarTransitions( 1375): draw background and invalidate : color = 14131313
V/audio_hw_primary(  288): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  288): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  288): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  288): disable_audio_route: reset and update mixer path: audio-record
,V/audio_hw_primary(  288): disable_audio_route: exit
E/audio_hw_primary(  288): disable_snd_device: enter 144
D/hardware_info(  288): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  288): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  288): stop_input_stream: exit: status(0)
V/audio_hw_primary(  288): in_standby: exit:  status(0)
V/AudioFlinger(  288): RecordThread: loop stopping
V/AudioPolicyService(  288): AudioCommandThread() going to sleep
V/AudioPolicyManager(  288): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  288): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  288): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  288): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  288): AudioCommandThread() waking up
V/AudioPolicyService(  288): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  288): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  288): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  288): AudioCommandThread() waking up
V/AudioPolicyService(  288): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  288): setParameters(): io 17, keyvalue hotword_active=0, calling pid 288
V/AudioFlinger(  288): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  288): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  288): RecordThread: loop starting
V/AudioFlinger(  288): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  288): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  288): in_set_parameters: exit: status(0)
V/AudioFlinger(  288): processConfigEvents_l() DONE thread 0xb383d000
V/AudioFlinger(  288): RecordThread: loop stopping
V/AudioPolicyService(  288): AudioCommandThread() going to sleep
V/AudioPolicyService(  288): AudioCommandThread() going to sleep
V/AudioRecord( 1943): stop()
V/AudioRecord( 1943): stop()
V/AudioRecord( 1943): stop()
V/AudioFlinger(  288): RecordHandle::stop()
V/AudioFlinger(  288): RecordThread::stop
V/AudioPolicyManager(  288): releaseInput() 17
V/AudioPolicyManager(  288): closeInput(17)
V/AudioFlinger(  288): closeInput() 17
V/AudioSystem(  288): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1375): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  831): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1943): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  288): ThreadBase::exit
V/AudioSystem( 1989): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  288): RecordThread: loop starting
V/AudioSystem( 2738): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  288): RecordThread 0xb383d000 exiting
V/AudioFlinger(  288): releasing 16 from 1943 for -1
V/AudioFlinger(  288):  decremented refcount to 0
D/audio_hw_primary(  288): adev_close_input_stream: enter:stream_handle(0xb546e240)
V/AudioFlinger(  288): purging stale effects
D/audio_hw_primary(  288): in_standby: enter: stream (0xb546e240) usecase(7: audio-record)
V/audio_hw_primary(  288): in_standby: exit:  status(0)
V/AudioSystem( 1750): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3158): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  288): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  288): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  288): releaseInput() exit
V/AudioPolicyService(  288): AudioCommandThread() waking up
V/AudioFlinger(  288): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioPolicyService(  288): AudioCommandThread() processing update audio port list
V/AudioFlinger(  288): removeClient_l() pid 1943, calling pid 288
V/AudioPolicyService(  288): AudioCommandThread() going to sleep
I/HotwordRecognitionRnr( 1943): Stopping hotword detection.
I/HotwordRecognitionRnr( 1943): Hotword detection finished
I/Icing   ( 4164): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
D/ContextHelper( 6138): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/Icing   ( 4164): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/ActivityManager(  831): Killing 5925:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  831): failed to open /acct/uid_10011/pid_5925/cgroup.procs: No such file or directory
I/WebViewFactory( 6138): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 6138): Time to load native libraries: 3 ms (timestamps 3897-3900)
I/LibraryLoader( 6138): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6138): Binding Chromium to main looper Looper (main, tid 1) {3d1d5fc}
I/LibraryLoader( 6138): Expected native library version number "",actual native library version number ""
I/chromium( 6138): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6138): Initializing chromium process, singleProcess=true
W/art     ( 6138): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6138): ApplicationContext is null in ApplicationStatus
W/chromium( 6138): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6138): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6138): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6138): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6138): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6138): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6138): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6138): Remote Branch: 
I/Adreno-EGL( 6138): Local Patches: 
I/Adreno-EGL( 6138): Reconstruct Branch: 
V/AudioPolicyService(  288): registerClient() client 0xb383bde0, uid 10316
D/AlertService( 5855): Beginning updateAlertNotification
,D/BluetoothManagerService(  831): Message: 20
D/sensors_hal_Time(  831): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  831): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time(  831): tsOffsetIs: Apps: 94217073719; DSPS: 3185385; Offset : -3004917785
,D/BluetoothManagerService(  831): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@245e806c:true
D/BluetoothAdapterService(1013208552)( 1989): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@777a07e
D/AlertService( 5855): No fired or scheduled alerts
I/NotificationManager( 5855): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 5855): com.android.calendar: cancel(1) by com.android.calendar
,I/NotificationManager( 5855): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 5855): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 5855): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5855): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 5855): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 5855): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 5855): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 5855): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 5855): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 5855): com.android.calendar: cancel(11) by com.android.calendar
,I/NotificationManager( 5855): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 5855): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 5855): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 5855): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 5855): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 5855): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5855): com.android.calendar: cancel(18) by com.android.calendar
,I/NotificationManager( 5855): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 5855): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 5855): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AlarmScheduler( 5855): No events found starting within 1 week.
,D/Finsky  ( 6037): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  831): RTC_WAKEUP set : Alarm{1964ffb3 type 0 when 1452292031740 com.android.vending} when 1452292031740
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/art     ( 6138): Attempt to remove local handle scope entry from IRT, ignoring
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/AwContents( 6138): onDetachedFromWindow called when already detached. Ignoring
,I/NotificationManager(  831): android: cancelAsUser(2) by android
,D/SystemWebViewEngine( 6138): CordovaWebView is running on device made by: LGE
W/art     ( 6138): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6138): Attempt to remove local handle scope entry from IRT, ignoring
,D/libc-netbsd( 6037): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6037): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6037): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6037): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  284): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  284): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  284): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  284): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  284): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  284): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  284): res_queryN name = xxxxx succeed
I/System.out( 6037): propertyValue:false
D/libc-netbsd( 6037): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6037): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Activity( 6138): Activity.onPostResume() called 
,D/OpenGLRenderer( 6138): Render dirty regions requested: true
I/OpenGLRenderer( 6138): Initialized EGL, version 1.4
D/OpenGLRenderer( 6138): Enabling debug mode 0
,D/Atlas   ( 6138): Validating map...
,D/SplitWindow(  831): check instance of lgWin Window{1d4deeff u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 6138): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  831): Focus entered window: Window{1d4deeff u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  831): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  831): Displayed com.test.thalitest/.MainActivity: +1s189ms
I/Timeline(  831): Timeline: Activity_windows_visible id: ActivityRecord{30476e09 u0 com.test.thalitest/.MainActivity t220} time:94625
I/Timeline( 6138): Timeline: Activity_idle id: android.os.BinderProxy@138d44fb time:94648
,D/libc-netbsd( 6037): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6037): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/BindingManager( 6138): Cannot call determinedVisibility() - never saw a connection for the pid: 6138
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  831): android: cancelAsUser(2) by android
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/qtaguid ( 6037): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6037): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6037): untagSocket(41) failed with errno -22
D/Finsky  ( 6037): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,D/JsMessageQueue( 6138): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  831): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6221 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  831): android: cancelAsUser(2) by android
,W/ResourcesManager( 6221): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6221): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6221): VM with version 2.1.0 has multidex support
I/MultiDex( 6221): install
I/MultiDex( 6221): VM has multidex support, MultiDex support library is disabled.
,I/qtaguid ( 6037): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6037): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6037): untagSocket(41) failed with errno -22
V/JNIHelp ( 6221): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 23:27:12.951 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/ActivityThread( 6221): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6221): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@a135de: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6221): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6221): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 6221): com.google.android.gms: cancel(39789) by com.google.android.gms
D/jxcore_app_log( 6138): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622752768
,D/JX-Cordova( 6138): jxcore cordova android initializing
D/WearableService( 1731): callingUid 10006, callindPid: 1731
,D/ChimeraCfgMgr( 6221): Reading stored module config
E/MDM     ( 1731): [118] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1731): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 4164): Restart initialization of location
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
D/ChimeraCfgMgr( 6221): Loading module com.google.android.gms.car from APK com.google.android.gms
,I/art     ( 6138): Background sticky concurrent mark sweep GC freed 22496(1788KB) AllocSpace objects, 4(60KB) LOS objects, 5% free, 10MB/11MB, paused 7.272ms total 83.912ms
,I/art     ( 6138): CheckpointMarkThreadRoots callback created = 0x9b131580
,I/art     ( 6138): CheckpointMarkThreadRoots callback created = 0x9b131550
,I/art     ( 4164): Explicit concurrent mark sweep GC freed 81549(5MB) AllocSpace objects, 31(496KB) LOS objects, 40% free, 14MB/23MB, paused 1.169ms total 162.979ms
W/GCoreFlp( 1731): No location to return for getLastLocation()
,W/FusedLocationProvider( 1731): location=null
W/SQLiteConnectionPool( 4164): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/NativeLibraryUtils( 6221): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 6221): Connecting to CarCallService...
,I/art     ( 6221): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6221): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6037): CheckpointMarkThreadRoots callback created = 0xaaf9b250
D/CAR.SERVICE( 6221): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6221): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6221): Creating a new PhoneAdapter instance
W/ActivityManager(  831): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6221): setListener: com.google.android.gms.car.dn@27134e45
W/ActivityManager(  831): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6221): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6221): Starting CarCallService with initial phone null
I/NotificationManager( 6221): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/art     ( 6037): CheckpointMarkThreadRoots callback created = 0xaaf9b210
D/CAR.SERVICE( 6221): Package validated; name: com.android.vending
,I/NotificationManager( 6037): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 6037): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,I/art     (  831): Explicit concurrent mark sweep GC freed 34159(1660KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.465ms total 170.441ms
,I/ActivityManager(  831): Process com.google.android.talk (pid 5263) has died
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  831): android: cancelAsUser(2) by android
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/qtaguid ( 6037): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6037): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6037): untagSocket(41) failed with errno -22
,W/ResourcesManager( 6037): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6037): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6037): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/jxcore-log( 6138): Initializing JXcore engine
,W/jxcore-log( 6138): JXcore engine is ready
I/ActivityManager(  831): Process com.android.calendar (pid 5855) has died
,W/jxcore-log( 6138): Starting JXcore engine
D/Finsky  ( 6037): [1] DailyHygiene.access$600: Logging device features
V/AlarmManager(  831): RTC_WAKEUP set : Alarm{16ebd71d type 0 when 1452292035002 com.android.vending} when 1452292035002
,W/.test.thalitest( 6138): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5463]" dev="sockfs" ino=5463 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6138): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 6138): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7876]" dev="sockfs" ino=7876 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6138): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6138): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6138): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[29191]" dev="sockfs" ino=29191 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
I/ActivityManager(  831): Process com.android.contacts (pid 5970) has died
,D/DeviceConnectionService( 1731): client connected with version: 8296000
D/Finsky  ( 6037): [739] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6037): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 6037): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/NotificationManager(  831): android: cancelAsUser(2) by android
D/libc-netbsd( 6037): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6037): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6037): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6037): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  284): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  284): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  284): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  284): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  284): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  284): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  284): res_queryN name = xxxxx succeed
,I/System.out( 6037): propertyValue:false
W/jxcore-log( 6138): Platform android
W/jxcore-log( 6138): 
W/jxcore-log( 6138): Process ARCH arm
W/jxcore-log( 6138): 
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  831): Process com.android.gallery3d (pid 5950) has died
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 23:27:15.961 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/AlarmManager(  831): RTC_WAKEUP set : Alarm{18393bdb type 0 when 1452292036069 com.google.android.googlequicksearchbox} when 1452292036069
,I/jxcore-log( 6138): JXcore Cordova bridge is ready!
I/jxcore-log( 6138): 
,W/jxcore-log( 6138): JXcore engine is started
I/Choreographer( 6138): Skipped 199 frames!  The application may be doing too much work on its main thread.
I/chromium( 6138): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6138): Toggling radios to true
I/jxcore-log( 6138): 
,D/BluetoothAdapter( 6138): enable(): BT is already enabled..!
D/WifiServiceImplEx(  831): setWifiEnabled: true pid=6138, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  831): setWifiEnabled: true pid=6138, uid=10316
,D/WifiServiceImplEx(  831): disconnect pid=6138, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  831): reconnect pid=6138, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 6138): Radios toggled
I/jxcore-log( 6138): 
,I/Netd    (  284): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2791): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/Netd    (  284): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2791): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,E/WifiStateMachine(  831): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  831): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WfdsMonitor( 1803): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/LGWifiP2pService(  831): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  831): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  284): Clearing all IP addresses on wlan0
D/DhcpStateMachine(  831): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/Netd    (  284): M: Get netlink event, ifname: wlan0 action: 7
,I/Netd    (  284): M: Get netlink event, ifname: wlan0 action: 10
,I/Netd    (  284): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1731): Read error: ssl=0xb045ba00: I/O error during system call, Connection timed out
V/NativeCrypto( 1731): SSL shutdown failed: ssl=0xb045ba00: I/O error during system call, Broken pipe
D/ConnectivityService(  831): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
,D/libc-netbsd(  831): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  831): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WifiHS20(  831): hidePasspointNotification off =false
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 23:27:16.645 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
W/Settings(  831): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  831): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  831): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/libc-netbsd(  831): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  831): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  831): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  831): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  831): ValidatedState{ when=-25ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  831): DefaultState{ when=-34ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  831): Forcing reevaluation
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/ConnectivityService(  831): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  831): ignoring duplicate network state non-change
D/ConnectivityService(  831): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
,I/ActivityManager(  831): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6296 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,E/WifiStateMachine(  831): Start Disconnecting Watchdog 1
D/WifiHS20(  831): hidePasspointNotification off =false
D/LGWifiP2pService(  831): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  831): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings(  831): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  831): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  831): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/wpa_supplicant( 2791): wlan0: CTRL-EVENT-SCAN-STARTED 
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 23:27:16.721 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/CommandListener(  284): Clearing all IP addresses on wlan0
,D/ConnectivityService(  831): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  831): disableDataServiceNotify
D/DSQN    (  831): stop dsqn bin
D/WifiHS20(  831): hidePasspointNotification off =false
W/Settings(  831): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  831): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  831): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 23:27:16.778 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
,D/ConnectivityService(  831): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  831):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  831):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WifiNetworkAgent(  831): NetworkAgent: NetworkAgent channel lost
D/ConnectivityService(  831): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  831): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  831): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1375): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  831): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  831): Disconnected - quitting
D/CSLegacyTypeTracker(  831): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  831): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/WifiHS20(  831): hidePasspointNotification off =false
D/ConnectivityService(  831): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/Settings(  831): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  831): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  831): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService(  831): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
W/Settings(  831): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService(  831): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/Settings(  831): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
D/WifiOffDelayIfNotUsed(  831): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/ConnectivityService(  831): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  831): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  831): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 23:27:16.805 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 23:27:16.805 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/TelephonyNetworkFactory-1( 1750): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1750):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
V/NetworkPolicy(  831): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy(  831): [LG_RESTRICTED] !!!isConnected  type  :1
W/QCNEJ   ( 1839): |CORE| No family connected
W/QCNEJ   ( 1839): |CORE| No family connected
I/QCNEJ   ( 1839): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/NetworkManagementService(  831): Removing idletimer
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt(  831): SUPPLICANT_STATE_CHANGED_ACTION
,D/Tethering(  831): MasterInitialState.processMessage what=3
D/WifiServerServiceExt(  831): setSupplicantStateDISCONNECTED
D/Tethering(  831): MasterInitialState.processMessage what=3
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/QCNEJ   ( 1839): |CORE| sendDefaultNwMsg: default = -1
W/Settings(  831): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/ResourcesManager( 6296): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6296): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6296): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6296): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6296): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/WifiServerServiceExt(  831): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  831): setSupplicantStateSCANNING
D/WIFI    (  831): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  831):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/DhcpStateMachine(  831): StoppedState
D/DhcpStateMachine(  831): StoppedState{ when=-114ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyIcons( 1375): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1375): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/TelephonyIcons( 1375): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1375): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/IndexDatabaseHelper( 6296): Using schema version: 115
,I/IndexDatabaseHelper( 6296): Index is fine
V/WiFiOffLoadBroadcast( 6296): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6296): MCCMNC not supported: null
,I/ActivityManager(  831): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6326 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/PCSuite ( 6326): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6326): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6326): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6296): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6296): MCCMNC not supported: null
,I/PCSuite ( 6326): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6326): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6326): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  831): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6351 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6351): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6351): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6351): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6351): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6351): MmsConfig.loadFromDatabase
I/Netd    (  284): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2791): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,E/Babel_SMS( 6351): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6351): MmsConfig.loadFromResources
E/Babel_SMS( 6351): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6351): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/art     ( 6351): CheckpointMarkThreadRoots callback created = 0xb042d550
,I/Netd    (  284): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  284): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  284): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2791): wlan0: Associated with c0:ff:d4:d3:aa:48
D/SensorManager( 6351): found sensor: LGE Accelerometer Sensor, handle=0
,D/SensorManager( 6351): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6351): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6351): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6351): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6351): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6351): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6351): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6351): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6351): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6351): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6351): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6351): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6351): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6351): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6351): found sensor: Motion Accel, handle=46
I/art     ( 6351): CheckpointMarkThreadRoots callback created = 0xb042d530
I/wpa_supplicant( 2791): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2791): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
,I/Netd    (  284): M: Get netlink event, ifname: wlan0 action: 4
I/ActivityManager(  831): Process com.google.android.apps.plus (pid 6012) has died
D/LocSvc_java(  831): onReceive
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 23:27:17.982 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  831): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  831): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  831): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/Settings(  831): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  831): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiOffDelayIfNotUsed(  831): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 23:27:17.985 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
,W/Settings(  831): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  831): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  831): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,W/Settings(  831): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  831): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  831): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 23:27:18.001 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 23:27:18.002 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/WifiServiceExtension(  831): setVHTCapabilityType  : false
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoS,imIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
W/Settings( 6351): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6351): startup - clean
,I/WifiServerServiceExt(  831): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  831): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  831): setSecurityType  : 2
I/Babel   ( 6351): deleted: false for 0
,W/Settings(  831): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  831): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  831): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
W/Settings(  831): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  831): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  831): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 23:27:18.062 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-08 23:27:18.063 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
,D/ConnectivityService(  831): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  831): Got NetworkAgent Messenger
D/ConnectivityService(  831): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  831): NetworkAgent connected
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
E/WifiConfigStore(  831): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  831): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Netd    (  284): M: Get netlink event, ifname: wlan0 action: 9
,D/libc-netbsd(  831): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  831): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  831): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  831): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  284): Setting iface cfg
E/WifiStateMachine(  831): Start Dhcp Watchdog 2
D/DhcpStateMachine(  831): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  831): WaitBeforeStartState
D/WifiServerServiceExt(  831): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  831): setSupplicantStateASSOCIATING
D/WifiServerServiceExt(  831): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  831): setSupplicantStateASSOCIATED
D/WifiServerServiceExt(  831): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  831): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt(  831): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  831): setSupplicantStateGROUP_HANDSHAKE
D/ConnectivityService(  831): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,V/WiFiOffLoadBroadcast( 6296): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6296): MCCMNC not supported: null
W/AudioCapabilities( 6351): Unsupported mime audio/x-lg-flac
I/PCSuite ( 6326): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6326): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6326): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/AudioCapabilities( 6351): Unsupported mime audio/adpcm
,W/AudioCapabilities( 6351): Unsupported mime audio/g726
W/AudioCapabilities( 6351): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6351): Unsupported mime audio/wma-voice
V/WiFiOffLoadBroadcast( 6296): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/VideoCapabilities( 6351): Unsupported mime video/mjpg
W/VideoCapabilities( 6351): Unsupported mime video/theora
,D/WiFiOffLoadBroadcast( 6296): MCCMNC not supported: null
I/PCSuite ( 6326): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6326): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6326): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6296): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6296): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6296): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6296): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6296): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine(  831): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  831): Current State is mWaitBeforeStartState.
,D/LGWifiP2pService(  831): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3bf17dfd target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  831): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3bf17dfd target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  831): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/WiFiOffLoadBroadcast( 6296): MCCMNC not supported: null
V/LgDhcpStateMachineHelper(  831): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  831): DHCP Start wake lock is acquired.
D/CommandListener(  284): Setting iface cfg
I/Netd    (  284): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  831): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  831): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  284): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  831): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/WiFiOffLoadBroadcast( 6296): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiServerServiceExt(  831): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  831): setSupplicantStateCOMPLETED
D/ConnectivityService(  831): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,D/LGWifiP2pService(  831): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  831): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WiFiOffLoadBroadcast( 6296): MCCMNC not supported: null
D/ConnectivityService(  831): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  831): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  831): ignoring duplicate network state non-change
D/ConnectivityService(  831): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
E/WifiStateMachine(  831): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService(  831): Adding iface wlan0 to network 101
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
W/Settings(  831): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  831): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  831): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 23:27:18.255 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
W/Settings(  831): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  831): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  831): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 23:27:18.261 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
,I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20(  831): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = true, mWifiLevel = 2
E/ConnectivityService(  831): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  831): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  284): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  284): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  284): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  284): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Settings(  831): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  831): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  831): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  831): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  831): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService(  831): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
W/Settings(  831): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  831): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/libc-netbsd(  284): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  284): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  284): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  284): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  284): netlink response contains error (File exists)
D/ConnectivityService(  831): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 23:27:18.278 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/libc-netbsd(  284): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  284): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  831): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  831): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  831): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  831): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  831): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/libc-netbsd(  284): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  284): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  831): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  831): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  831): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 23:27:18.284 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  831): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  831): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  831): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  831): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  831):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  831):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  831):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  831):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  831):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  831): currentScore = 0, newScore = 20
D/ConnectivityService(  831):    accepting network in place of null
D/ConnectivityService(  831): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1750): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1750):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
E/ConnectivityService(  831): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  831): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  831): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  831): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  831): [e] list.add(nai) empty : false size: 1
D/ConnectivityService(  831): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  831): validation of new default Network = false
D/ConnectivityService(  831): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  831): enableDataServiceNotify 
D/DSQN    (  831): start dsqn bin
D/Tethering(  831): MasterInitialState.processMe,ssage what=3
D/libc-netbsd(  831): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  831): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/QCNEJ   ( 1839): |CORE| No family connected
I/QCNEJ   ( 1839): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  831): [LWD] Start DNSResolver start to wait
I/QCNEJ   ( 1839): |CORE| sendDefaultNwMsg: default = 1
D/WIFI    (  831): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  831):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/libc-netbsd(  831): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  831): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  284): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  284): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  284): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  284): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  284): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  831): [LWD] wait 500ms before dns check
D/libc-netbsd(  284): res_queryN name = xxxxx, class = 1, type = 1
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = true, mWifiLevel = 2
V/WiFiOffLoadBroadcast( 6296): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/ConnectivityService(  831): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  831):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  831):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  831): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1375): CM callback handler got msg 524290
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/WiFiOffLoadBroadcast( 6296): MCCMNC not supported: null
I/DSQN    ( 6397): DSQN samuel.seo ver 141203
E/DSQN    ( 6397): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6397): created command queue thread
I/DSQN    ( 6397): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6397): Interface wlan0 netmask 255.255.255.0 0xc0a80186
W/AudioCapabilities( 6351): Unsupported mime audio/evrc
,W/AudioCapabilities( 6351): Unsupported mime audio/qcelp
W/VideoCapabilities( 6351): Unrecognized profile 2130706433 for video/avc
V/WiFiOffLoadBroadcast( 6296): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/TelephonyIcons( 1375): null signal icon name: drawable/stat_sys_signal_null
D/WiFiOffLoadBroadcast( 6296): MCCMNC not supported: null
I/[SystemUI]LGNetworkController( 1375): updateLGTelephonySignalStrength : !hasService()
W/AudioCapabilities( 6351): Unsupported mime audio/amr-wb-plus
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
W/AudioCapabilities( 6351): Unsupported mime audio/qcelp
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
W/AudioCapabilities( 6351): Unsupported mime audio/evrc
V/WiFiOffLoadBroadcast( 6296): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6296): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6296): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6296): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6296): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6296): MCCMNC not supported: null
W/VideoCapabilities( 6351): Unsupported mime video/mp4v-esdp
D/DhcpStateMachine(  831): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper(  831): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  831): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,V/WiFiOffLoadBroadcast( 6296): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6296): MCCMNC not supported: null
I/VideoCapabilities( 6351): Unsupported profile 4 for video/mp4v-es
I/dhcpcd  ( 6400): version 5.5.6 starting
W/VideoCapabilities( 6351): Unrecognized profile 2130706433 for video/avc
E/dhcpcd  ( 6400): get_duid: Read-only file system
,W/VideoCapabilities( 6351): Unrecognized profile 2130706433 for video/avc
V/WiFiOffLoadBroadcast( 6296): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/VideoCapabilities( 6351): Unrecognized profile 2130706433 for video/avc
D/WiFiOffLoadBroadcast( 6296): MCCMNC not supported: null
I/PCSuite ( 6326): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,W/VideoCapabilities( 6351): Unrecognized profile 2130706433 for video/avc
D/PCSuite ( 6326): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6296): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/vclib   ( 6351): onServiceConnected
W/Babel   ( 6351): Attempted to change video mute state without an active call.
D/WiFiOffLoadBroadcast( 6296): MCCMNC not supported: null
,D/libc-netbsd(  284): res_queryN name = xxxxx succeed
I/System.out(  831): propertyValue:false
I/NotificationManager( 6351): com.google.android.talk: cancel(10436) by com.google.android.talk
I/PCSuite ( 6326): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6326): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  831): Killing 5995:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,V/AlarmManager(  831): ELAPSED_WAKEUP set : Alarm{1b2931ec type 2 when 101068 com.google.android.gms} when 101068
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  284): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  284): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  284): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  284): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd(  284): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  284): res_queryN name = xxxxx, class = 1, type = 1
I/dhcpcd  ( 6400): wlan0: rebinding lease of 192.168.1.134
,D/libc-netbsd(  284): res_queryN name = xxxxx succeed
,I/System.out( 1731): propertyValue:false
,I/DSQN    ( 6397): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6397): restart monitoring
,D/LGDataListener(  284): argv[0]=dsqncommand
D/LGDataListener(  284): argv[1]=wlan0
D/LGDataListener(  284): argv[2]=1
D/LGDataListener(  284): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 6397): dsqn report finish
D/DSQN    (  831): DSQM DsqnNotification wlan0  1
D/DSQN    (  831): start to monitor internet connection
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/libprocessgroup(  831): failed to open /acct/uid_10069/pid_5995/cgroup.procs: No such file or directory
D/CAR.SERVICE( 6221): mConnectedToCar = false, abort
,E/ActivityThread( 6221): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@24840c53 that was originally bound here
E/ActivityThread( 6221): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@24840c53 that was originally bound here
E/ActivityThread( 6221): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6221): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6221): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6221): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6221): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6221): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6221): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6221): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6221): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6221): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6221): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6221): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6221): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6221): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6221): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6221): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6221): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6221): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6221): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6221): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6221): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6221): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6221): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/ActivityThread( 6221): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@15cbdebc that was originally bound here
E/ActivityThread( 6221): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@15cbdebc that was originally bound here
E/ActivityThread( 6221): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6221): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6221): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6221): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6221): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6221): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6221): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6221): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6221): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6221): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6221): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6221): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6221): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6221): 	at android.app.ActivityThread.acce,ss$1900(ActivityThread.java:155)
E/ActivityThread( 6221): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6221): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6221): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6221): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6221): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6221): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6221): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6221): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  831): Unbind failed: could not find connection for android.os.BinderProxy@264859b5
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  831): [LWD] DNSResolver start dns
D/libc-netbsd(  831): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  831): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  831): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  831): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  284): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  284): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  284): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  284): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  284): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  284): res_queryN name = xxxxx, class = 1, type = 1
,D/libc-netbsd(  284): res_queryN name = xxxxx succeed,
I/System.out(  831): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  831): [LWD] DNSResolver end dns
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  831): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  831): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  831): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  831): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 22:27:19 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452292038898], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452292038866]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  831): Don't send network conditions - lacking user consent.
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  831): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  831): Validated
D/ConnectivityService(  831): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  831): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  831):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  831):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  831):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  831): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  831): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  831):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  831):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  831): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  831): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  831): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  831): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  831):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1375): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1750): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1750):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WifiDataContinuityService(  831): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
,I/WifiServerServiceExt(  831): set CMD_CAPTIVE_CHECK_COMPLETED
D/TelephonyIcons( 1375): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1375): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/Netd    (  284): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  831): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  831): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  831): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  831): identical MTU - not setting
D/Nat464Xlat(  831): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  831): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  831):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  831):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 23:27:19.189 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/ConnectivityService(  831): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  831): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  831): enableDataServiceNotify 
D/DSQN    (  831): start dsqn bin
D/ConnectivityManager.CallbackHandler( 1375): CM callback handler got msg 524295
D/DSQN    (  831): dsqn is running restart
,I/DSQN    ( 6428): DSQN samuel.seo ver 141203
E/DSQN    ( 6428): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6428): created command queue thread
I/DSQN    ( 6428): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6428): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/ConnectivityService(  831): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/dhcpcd  ( 6400): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/dhcpcd  ( 6400): wlan0: leased 192.168.1.134 for 86400 seconds
,D/ConnectivityService(  831): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  831): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  831): onReceive
D/LocSvc_java(  831): got connectivity action
,D/libc-netbsd(  831): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  831): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LocSvc_java(  831): broadcast - no network connections
D/LocSvc_java(  831): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  831): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  831): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  831): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  831): ignore wifi update if we are not in OPENING or CLOSING
I/ActivityManager(  831): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6440 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/LocSvc_java(  831): onReceive
D/LocSvc_java(  831): got connectivity action
D/LocSvc_java(  831): broadcast - no network connections
D/LocSvc_java(  831): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  831): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  831): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  831): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  831): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  831): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/GpsLocationProvider(  831): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  831): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider(  831): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/libc-netbsd(  831): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  831): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  831): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  831): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  831): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  831): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  831): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  831): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  831): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  831): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  831): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  831): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  831): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  831): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  831): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  831): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  831): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  831): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  831): RunningState
I/ActivityManager(  831): Process com.android.vending (pid 6037) has died
,I/MusicStore( 6440): Database version: 120
,I/rmt_storage(  277): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
,I/rmt_storage(  277): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  277): wakelock acquired: 1, error no: 42
I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6440): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  277): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  277): 
I/rmt_storage(  277): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6440): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6440): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6440): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6440): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6440): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6440): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6440): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@397d6531: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6440): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6440): GMSCore installation verified
I/ConfigStore( 6440): Config Database version: 1
I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/MediaRouter( 6440): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6440): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6440): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6440): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  831): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6494 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6440): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6440): Using platform SSLCertificateSocketFactory
,I/NotificationManager( 6440): com.google.android.music: cancel(1061) by com.google.android.music
,W/ResourcesManager( 6494): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6494): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6494): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-08 23:27:21.141 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/NotificationManager( 1943): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,V/WifiInternetCheck(  831): Single check msg out of sync, ignoring.
I/LGEmail ( 6494): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/ConnectivityService(  831): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/LocSvc_java(  831): onReceive
D/LocSvc_java(  831): got connectivity action
D/LocSvc_java(  831): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  831): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  831): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  831): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  831): ignore wifi update if we are not in OPENING or CLOSING
I/NetworkMonitor( 6440): type=WIFI subType= reason=null isConnected=true
,I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/GpsLocationProvider(  831): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  831): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LGEmail ( 6494): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6494): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  831): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6528 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/HubEmail( 6494): JNI_OnLoad()
I/HubEmail( 6494): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6494): registerNatives()
I/HubEmail( 6494): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6494): registerNativeMethods()
I/HubEmail( 6494): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6494): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  831): Killing 6095:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/libprocessgroup(  831): failed to open /acct/uid_10014/pid_6095/cgroup.procs: No such file or directory
,W/Settings( 6494): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 6528): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6528): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6528): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 6528): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6528): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6528): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6528): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6528): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  831): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6555 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6528): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6528): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6528): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6528): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6528): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 6528): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  831): Killing 6221:com.google.android.gms:car/u0a6 (adj 15): empty #11
,W/libprocessgroup(  831): failed to open /acct/uid_10006/pid_6221/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 6555): onCreate
,W/AppUp4:DB( 6555):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6555):  setFingerPrint start
,I/AppUp4:DB( 6555):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6555):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6555):  SDK version = 0
I/AppUp4:DB( 6555):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6555): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6555): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6555): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6555): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6555): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6555): onReceive
I/AppUp4:CustModeStarterReceiver( 6555): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6555): Context : android.app.ReceiverRestrictedContext@c731485
D/AppUp4:CustFacade( 6555): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6555): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6555): begin check event
I/AppUp4:CustModeStarterReceiver( 6555): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6555): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6555): call method handleAsyncCustNotification.
,D/AppUp4:CustModeStarterReceiver( 6555): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6555): handleAsyncCustNotification do not startCustService
I/ActivityManager(  831): Killing 6296:com.android.settings/1000 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/libprocessgroup(  831): failed to open /acct/uid_1000/pid_6296/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3158): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3158): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3158): networkInfo.isConnected() = false
I/ActivityManager(  831): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6574 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/libc-netbsd(  831): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  831): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  831): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  831): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  284): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  284): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  284): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  284): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  284): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  284): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  284): res_queryN name = xxxxx succeed
,I/System.out(  831): propertyValue:false
D/libc-netbsd(  831): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  831): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  831): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  831): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  284): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  284): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  284): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  284): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  284): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  284): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  284): res_queryN name = xxxxx succeed
I/System.out(  831): propertyValue:false
I/DSQN    ( 6428): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6428): restart monitoring
,D/LGDataListener(  284): argv[0]=dsqncommand
D/LGDataListener(  284): argv[1]=wlan0
D/LGDataListener(  284): argv[2]=1
D/LGDataListener(  284): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 6428): dsqn report finish
D/DSQN    (  831): DSQM DsqnNotification wlan0  1
D/DSQN    (  831): start to monitor internet connection
V/WifiInternetCheck(  831): isHttpConnectionAvailable - We got a valid response : 204
,D/PhoneMonitor( 6574): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6574): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6574): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  831): Killing 6326:com.lge.sync/1000 (adj 15): empty #11
W/libprocessgroup(  831): failed to open /acct/uid_1000/pid_6326/cgroup.procs: No such file or directory
,I/CheckinService( 4164): Checkin interval check for package: unspecified last checkin: 1452292017927 min interval config: 0 actual interval: 24929
D/PhoneMonitor( 6574): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6574): [loadFeatureFromXml] *** start feature loading from xml
V/DownloadManager( 3195): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3195): DownloadService onCreate
I/DownloadManager( 3195): in removeSpuriousFiles
,I/NotificationManager( 3195): com.android.providers.downloads: cancelAll by com.android.providers.downloads
D/TelephonyAutoProfiling( 6574): [parse] Load xml
V/DownloadManager( 3195): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/TelephonyAutoProfiling( 6574): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6574): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,V/DownloadManager( 3195): created cursor android.database.sqlite.SQLiteCursor@2ac1c3bf on behalf of 3195
I/DownloadManager( 3195): in trimDatabase
V/DownloadManager( 3195): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/PhoneMonitor( 6574): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
V/DownloadManager( 3195): created cursor android.database.sqlite.SQLiteCursor@22deba8c on behalf of 3195
I/ActivityManager(  831): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6615 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3195): DownloadService onStartCommand
I/CheckinService( 4164): Checking schedule, now: 1452292042912 next: 1452292047875
I/CheckinService( 4164): active receiver: disabled
I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 22.573ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 20.413ms
,V/DownloadManager( 3195): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3195): created cursor android.database.sqlite.SQLiteCursor@206d1ea on behalf of 3195
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 311us total 21.938ms
,V/DownloadManager( 3195): DownloadService onDestroy
,I/ActivityManager(  831): Killing 5627:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 5038): android.os.DeadObjectException
,W/System.err( 5038): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5038): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5038): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5038): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5038): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5038): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5038): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5038): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5038): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5038): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5038): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5038): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5038): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5038): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5038): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5038): android.os.DeadObjectException
W/System.err( 5038): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5038): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5038): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5038): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5038): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5038): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5038): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5038): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5038): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5038): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5038): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5038): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5038): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5038): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5038): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
E/libprocessgroup(  831): failed to kill 1 processes for processgroup 5627
,D/WeatherAncestor( 2729): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:27:23
,W/ActivityManager(  831): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,D/UpdateThreadPoolManager( 2729): 2 : This is isUpdating : false
D/WeatherAncestor( 2729): connectivity changed - connection : true
D/Weather_cast( 2729): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2729): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:27:23
D/WeatherService( 2729): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  831): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6639 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  831): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2729): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2729): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2729): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/art     (  831): Explicit concurrent mark sweep GC freed 79054(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.588ms total 230.192ms
,D/UEI.SmartControl( 6639): Quickset Services start...
,I/UEI.SmartControl( 6639): Manufacture = LGE
I/ActivityManager(  831): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6667 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/UEI.SmartControl( 6639): File observer start...
E/UEI.SmartControl( 6639): IR Port is disabled: false
D/UEI.SmartControl( 6639): Starting file observer...
D/UEI.SmartControl( 6639): Extracting JNI libs...
D/UEI.SmartControl( 6639): --- this system supports 32-bit or 64-bit only
D/libc-netbsd( 6351): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6351): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6351): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6351): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  284): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  284): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  284): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  284): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  284): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  284): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  284): res_queryN name = xxxxx succeed
I/System.out( 6351): propertyValue:false
,I/Babel   ( 6351): connection state changed from UNKNOWN to CONNECTED
,D/UEI.SmartControl( 6639): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6639): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6639): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 6639): --- Selecting new region: 2
I/UEI.SmartControl( 6639): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6639): Platform has CIR...
D/UEI.SmartControl( 6639): NO CIR support, need to check package...
I/UEI.SmartControl( 6639): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6639): QS Service created
,E/UEI.SmartControl( 6639): QS start get config
,D/UEI.SmartControl( 6639): Loading JNI Libs...
,D/UEI.SmartControl( 6639):  configuring local db...
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6667): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6667): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,I/GAv4    ( 6667): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6667):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6667):   adb logcat -s GAv4
W/ContextImpl( 6667): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6667): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 6667): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6667): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6667): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/UEI.SmartControl( 6639):  ---- Has DB8: true
,D/UEI.SmartControl( 6639): QS start statue = true Error code = 0
D/UEI.SmartControl( 6639): QS version = v2.7.11.1_RC1
,D/UEI.SmartControl( 6639): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6639): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6639): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6639): IrrcClient ++ 
D/irrcClient( 6639): getIrrcService ++ 
,D/irrcClient( 6639): getIrrcService -- 
D/irrcClient( 6639): IrrcClient -- 
W/irrc_jni( 6639): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6639): Services init done
D/UEI.SmartControl( 6639): QS Service init finished
,D/UEI.SmartControl( 6639): QS Service version name: 0.1.73
D/UEI.SmartControl( 6639): QS Service version code: 1073
D/UEI.SmartControl( 6639): Service requested: Control
I/UEI.SmartControl( 6639): Device manager: loading config....
D/UEI.SmartControl( 6639): Config is loaded...
,D/UEI.SmartControl( 6639):  ----- QS SDK is ready!!!
D/UEI.SmartControl( 6639): Request IControl service: devices are loaded...
,I/UEI.SmartControl( 6639): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6639): Internal service binding...
D/UEI.SmartControl( 6639): -----IControl: 11
D/UEI.SmartControl( 6639): Caller: com.lge.qremote
D/UEI.SmartControl( 6639): ------------ IControl registerCallback...
I/UEI.SmartControl( 6639): Registering callback...
D/UEI.SmartControl( 6639): -----IControl: 19
D/UEI.SmartControl( 6639): Caller: com.lge.qremote
I/UEI.SmartControl( 6639): Registering Services Ready callback...
I/UEI.SmartControl( 6639): Notify client services are ready...
D/UEI.SmartControl( 6639): -----IControl: 8
,D/UEI.SmartControl( 6639): Caller: com.lge.qremote
I/WebViewFactory( 6667): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6667): Time to load native libraries: 3 ms (timestamps 7069-7072)
I/LibraryLoader( 6667): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6667): Binding Chromium to main looper Looper (main, tid 1) {35f4d28e}
I/LibraryLoader( 6667): Expected native library version number "",actual native library version number ""
I/chromium( 6667): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6667): Initializing chromium process, singleProcess=true
,W/art     ( 6667): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6667): ApplicationContext is null in ApplicationStatus
W/chromium( 6667): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6667): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6667): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6667): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6667): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6667): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6667): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6667): Remote Branch: 
I/Adreno-EGL( 6667): Local Patches: 
I/Adreno-EGL( 6667): Reconstruct Branch: 
V/AudioPolicyService(  288): registerClient() client 0xb383bfc0, uid 10079
,W/AudioManagerAndroid( 6667): Requires BLUETOOTH permission
I/NSApplication( 6667): Starting up...
,I/ActivityManager(  831): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6731 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  831): Killing 6440:com.google.android.music:main/u0a81 (adj 15): empty #11
I/ActivityManager(  831): Killing 5038:com.lge.qremote/u0a106 (adj 15): empty #12
,W/libprocessgroup(  831): failed to open /acct/uid_10081/pid_6440/cgroup.procs: No such file or directory
,W/libprocessgroup(  831): failed to open /acct/uid_10106/pid_5038/cgroup.procs: No such file or directory
I/ActivityManager(  831): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6753 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  831): Killing 6494:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  831): failed to open /acct/uid_10021/pid_6494/cgroup.procs: No such file or directory
,W/ResourcesManager( 6753): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  831): Killing 6528:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  831): failed to open /acct/uid_1000/pid_6528/cgroup.procs: No such file or directory
,I/ActivityManager(  831): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6777 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/MusicStore( 6777): Database version: 120
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6777): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6777): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6777): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6777): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6777): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6777): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/AlarmManager(  831): RTC_WAKEUP set : Alarm{36ae8c70 type 0 when 1452292046302 com.google.android.googlequicksearchbox} when 1452292046302
W/ActivityThread( 6777): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6777): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@397d6531: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6777): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6777): GMSCore installation verified
,I/ConfigStore( 6777): Config Database version: 1
,I/MediaRouter( 6777): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6777): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6777): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6777): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  831): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6818 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6777): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6777): Using platform SSLCertificateSocketFactory
I/ActivityManager(  831): Killing 6555:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/ResourcesManager( 6818): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6818): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6818): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/libprocessgroup(  831): failed to open /acct/uid_10011/pid_6555/cgroup.procs: No such file or directory
,I/NotificationManager( 6777): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6818): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6818): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6818): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  831): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6841 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6818): JNI_OnLoad()
I/HubEmail( 6818): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6818): registerNatives()
I/HubEmail( 6818): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6818): registerNativeMethods()
I/HubEmail( 6818): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6818): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  831): Killing 6574:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  831): failed to open /acct/uid_10038/pid_6574/cgroup.procs: No such file or directory
W/Settings( 6818): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 6841): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6841): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6841): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6841): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6841): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6841): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6841): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6841): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  831): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6865 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6841): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6841): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6841): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6841): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6841): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6841): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  831): Killing 6615:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  831): failed to open /acct/uid_10051/pid_6615/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 6865): onCreate
,W/AppUp4:DB( 6865):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6865):  setFingerPrint start
I/AppUp4:DB( 6865):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6865):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6865):  SDK version = 0
,I/AppUp4:DB( 6865):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6865): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6865): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6865): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6865): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6865): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6865): onReceive
I/AppUp4:CustModeStarterReceiver( 6865): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6865): Context : android.app.ReceiverRestrictedContext@c731485
D/AppUp4:CustFacade( 6865): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6865): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6865): begin check event
I/AppUp4:CustModeStarterReceiver( 6865): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6865): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6865): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6865): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6865): handleAsyncCustNotification do not startCustService
I/ActivityManager(  831): Killing 6351:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  831): failed to open /acct/uid_10061/pid_6351/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3158): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3158): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3158): networkInfo.isConnected() = false
,I/ActivityManager(  831): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6887 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6887): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6887): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6887): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  831): Killing 6639:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
D/PhoneMonitor( 6887): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6887): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6887): [parse] Load xml
,V/TelephonyAutoProfiling( 6887): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6887): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 6887): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  831): failed to open /acct/uid_10089/pid_6639/cgroup.procs: No such file or directory
,V/DownloadManager( 3195): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3195): DownloadService onCreate
I/NotificationManager( 3195): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,I/DownloadManager( 3195): in removeSpuriousFiles
V/DownloadManager( 3195): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3195): created cursor android.database.sqlite.SQLiteCursor@2d02f378 on behalf of 3195
I/DownloadManager( 3195): in trimDatabase
V/DownloadManager( 3195): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3195): created cursor android.database.sqlite.SQLiteCursor@127822b6 on behalf of 3195
,I/ActivityManager(  831): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6916 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3195): DownloadService onStartCommand
I/CheckinService( 4164): Checkin interval check for package: unspecified last checkin: 1452292017927 min interval config: 0 actual interval: 30216
,V/DownloadManager( 3195): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3195): created cursor android.database.sqlite.SQLiteCursor@f2fcf24 on behalf of 3195
,D/WeatherAncestor( 2729): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:27:28
,I/CheckinService( 4164): Checking schedule, now: 1452292048231 next: 1452292047875
I/CheckinService( 4164): active receiver: enabled
,V/DownloadManager( 3195): DownloadService onDestroy
,D/UpdateThreadPoolManager( 2729): 2 : This is isUpdating : false
D/WeatherAncestor( 2729): connectivity changed - connection : true
D/Weather_cast( 2729): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2729): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:27:28
D/WeatherService( 2729): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/CheckinService( 4164): Preparing to send checkin request
I/EventLogService( 4164): Accumulating logs since 1452292009193
I/ActivityManager(  831): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6944 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  831): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2729): 2 : Utils getTopActivity com.lge.launcher2 / true
I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 365us total 25.240ms
,D/WeatherService( 2729): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2729): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 22.566ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 22.192ms
,W/ResourcesManager( 6944): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 4164): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 4164): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  831): Explicit concurrent mark sweep GC freed 17018(934KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.412ms total 148.316ms
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel_SMS( 6944): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6944): MmsConfig.loadMmsSettings
I/Babel_SMS( 6944): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6944): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6944): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6944): MmsConfig.loadFromResources
E/Babel_SMS( 6944): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6944): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 6944): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6944): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6944): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6944): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6944): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6944): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6944): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6944): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6944): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6944): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6944): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6944): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6944): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6944): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6944): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6944): found sensor: Motion Accel, handle=46
,I/ActivityManager(  831): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6972 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
W/Settings( 6944): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6944): startup - clean
,W/ResourcesManager( 6972): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6972): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/art     ( 6944): CheckpointMarkThreadRoots callback created = 0xb042d960
,I/art     ( 6944): CheckpointMarkThreadRoots callback created = 0xb042d940
,I/Babel   ( 6944): deleted: false for 0
,I/MultiDex( 6972): VM with version 2.1.0 has multidex support
I/MultiDex( 6972): install
,I/MultiDex( 6972): VM has multidex support, MultiDex support library is disabled.
I/ActivityManager(  831): Process com.google.android.apps.magazines (pid 6667) has died
,V/AlarmManager(  831): RTC_WAKEUP set : Alarm{244eaa53 type 0 when 1452292047875 com.google.android.gms} when 1452292047875
I/ActivityManager(  831): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6992 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  831): RTC_WAKEUP set : Alarm{3c95ff90 type 0 when 1452292049113 com.android.vending} when 1452292049113
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  831): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7010 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 6944): Unsupported mime audio/x-lg-flac
,V/JNIHelp ( 6972): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/AudioCapabilities( 6944): Unsupported mime audio/adpcm
W/AudioCapabilities( 6944): Unsupported mime audio/g726
W/AudioCapabilities( 6944): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6944): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6944): Unsupported mime video/mjpg
W/VideoCapabilities( 6944): Unsupported mime video/theora
,W/ActivityThread( 6972): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6972): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@a135de: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6972): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6972): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6972): com.google.android.gms: cancel(39789) by com.google.android.gms
W/AudioCapabilities( 6944): Unsupported mime audio/evrc
,W/AudioCapabilities( 6944): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6944): Unrecognized profile 2130706433 for video/avc
D/Finsky  ( 6992): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/AudioCapabilities( 6944): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6944): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6944): Unsupported mime audio/evrc
I/art     ( 6972): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6972): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
W/VideoCapabilities( 6944): Unsupported mime video/mp4v-esdp
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7010): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/VideoCapabilities( 6944): Unsupported profile 4 for video/mp4v-es
,I/GAv4    ( 7010): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7010):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7010):   adb logcat -s GAv4
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7010): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/VideoCapabilities( 6944): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6944): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6944): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6944): Unrecognized profile 2130706433 for video/avc
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7010): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7010): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,I/vclib   ( 6944): onServiceConnected
W/Babel   ( 6944): Attempted to change video mute state without an active call.
,D/Finsky  ( 6992): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/GAv4    ( 7010): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/Settings( 6992): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6992): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6992): com.android.vending: cancel(-1050172287) by com.android.vending
D/libc-netbsd( 6944): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6944): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6944): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6944): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  284): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  284): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  284): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  284): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  284): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  284): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  284): res_queryN name = xxxxx succeed
,I/System.out( 6944): propertyValue:false
I/NotificationManager( 6944): com.google.android.talk: cancel(10436) by com.google.android.talk
D/WVCdm   (  288): Instantiating CDM.
W/GAv4    ( 7010): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/WVCdm   (  288): CdmEngine::OpenSession
I/WVCdm   (  288): Level3 Library Dec 11 2014 16:13:16
W/GAv4    ( 7010): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/WVCdm   (  288): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  288): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  288): L1 library not specified. Falling Back to L3
,I/Babel   ( 6944): connection state changed from UNKNOWN to CONNECTED
I/jxcore-log( 6138): Test app app.js loaded
I/jxcore-log( 6138): 
I/ActivityManager(  831): Process com.google.android.apps.plus (pid 6753) has died
,V/DownloadManager( 3195): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
I/Choreographer( 6138): Skipped 820 frames!  The application may be doing too much work on its main thread.
V/DownloadManager( 3195): created cursor android.database.sqlite.SQLiteCursor@2ddbb442 on behalf of 6992
D/Finsky  ( 6992): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6992): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 6992): Skipping gmscore version check
I/chromium( 6138): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/Finsky  ( 6992): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/WVCdm   (  288): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  288): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  288): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  288): CdmEngine::GenerateKeyRequest
,D/NativeLibraryUtils( 6972): Install completed successfully. count=14 extracted=0
D/WVCdm   (  288): PrepareKeyRequest: nonce=3155535654
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/Finsky  ( 6992): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/Finsky  ( 6992): [855] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6992): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/WebViewFactory( 7010): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/WVCdm   (  288): CdmEngine::OpenSession
,I/ActivityManager(  831): Process com.google.android.music:main (pid 6777) has died
,I/LibraryLoader( 7010): Time to load native libraries: 1 ms (timestamps 3392-3393)
,I/LibraryLoader( 7010): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7010): Binding Chromium to main looper Looper (main, tid 1) {35f4d28e}
I/LibraryLoader( 7010): Expected native library version number "",actual native library version number ""
I/chromium( 7010): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7010): Initializing chromium process, singleProcess=true
,W/art     ( 7010): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7010): ApplicationContext is null in ApplicationStatus
W/chromium( 7010): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7010): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7010): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7010): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7010): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7010): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7010): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7010): Remote Branch: 
I/Adreno-EGL( 7010): Local Patches: 
I/Adreno-EGL( 7010): Reconstruct Branch: 
V/AudioPolicyService(  288): registerClient() client 0xb551c920, uid 10079
,W/AudioManagerAndroid( 7010): Requires BLUETOOTH permission
I/NSApplication( 7010): Starting up...
,I/ActivityManager(  831): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7101 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 7101): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  831): Killing 6818:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  831): failed to open /acct/uid_10021/pid_6818/cgroup.procs: No such file or directory
,I/ActivityManager(  831): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7129 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/sensors_hal_Time(  831): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  831): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  831): tsOffsetIs: Apps: 114217817930; DSPS: 3840770; Offset : -3004935056
,I/MusicStore( 7129): Database version: 120
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7129): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7129): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7129): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7129): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7129): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7129): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7129): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7129): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@397d6531: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7129): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 7129): GMSCore installation verified
I/ConfigStore( 7129): Config Database version: 1
,I/art     ( 3901): Explicit concurrent mark sweep GC freed 3065(122KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 386us total 51.985ms
,I/MediaRouter( 7129): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7129): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7129): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7129): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  831): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7163 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7129): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7129): Using platform SSLCertificateSocketFactory
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  831): Killing 6841:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/ResourcesManager( 7163): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7163): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7163): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  831): failed to open /acct/uid_1000/pid_6841/cgroup.procs: No such file or directory
,I/NotificationManager( 7129): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 7163): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 7163): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/WVCdm   (  288): CdmEngine::CloseSession
I/WVCdm   (  288): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  288): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  288): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  288): CdmEngine::GenerateKeyRequest
D/WVCdm   (  288): PrepareKeyRequest: nonce=2768713013
,D/eas_req ( 7163): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  831): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7187 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/HubEmail( 7163): JNI_OnLoad()
I/HubEmail( 7163): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7163): registerNatives()
I/HubEmail( 7163): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7163): registerNativeMethods()
I/HubEmail( 7163): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7163): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 7163): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  831): Killing 6865:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  831): failed to open /acct/uid_10011/pid_6865/cgroup.procs: No such file or directory
,D/LGDMClient( 7187): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7187): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7187): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7187): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7187): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7187): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7187): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 7187): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  831): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7211 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
W/ContextImpl( 7187): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7187): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7187): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
,D/LGDMClient( 7187): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7187): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7187): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  831): Killing 6887:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  831): failed to open /acct/uid_10038/pid_6887/cgroup.procs: No such file or directory
,I/art     (  831): Explicit concurrent mark sweep GC freed 21759(999KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.204ms total 150.709ms
,I/AppUp4:AppBoxCP( 7211): onCreate
,W/AppUp4:DB( 7211):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7211):  setFingerPrint start
I/AppUp4:DB( 7211):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7211):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7211):  SDK version = 0
I/AppUp4:DB( 7211):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7211): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7211): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7211): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7211): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7211): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7211): onReceive
,I/AppUp4:CustModeStarterReceiver( 7211): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7211): Context : android.app.ReceiverRestrictedContext@c731485
D/AppUp4:CustFacade( 7211): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7211): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7211): begin check event
,I/AppUp4:CustModeStarterReceiver( 7211): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7211): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7211): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7211): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7211): handleAsyncCustNotification do not startCustService
I/ActivityManager(  831): Killing 6916:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  831): failed to open /acct/uid_10051/pid_6916/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3158): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3158): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3158): networkInfo.isConnected() = true
,D/PhoneState( 3158): setPdpRejectCasuse : false
I/ActivityManager(  831): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7230 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7230): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7230): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7230): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  831): Killing 6944:com.google.android.talk/u0a61 (adj 15): empty #11
,D/PhoneMonitor( 7230): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7230): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7230): [parse] Load xml
V/TelephonyAutoProfiling( 7230): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7230): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7230): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  831): failed to open /acct/uid_10061/pid_6944/cgroup.procs: No such file or directory
V/DownloadManager( 3195): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3195): DownloadService onCreate
I/DownloadManager( 3195): in removeSpuriousFiles
V/DownloadManager( 3195): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/NotificationManager( 3195): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,V/DownloadManager( 3195): created cursor android.database.sqlite.SQLiteCursor@24840c53 on behalf of 3195
I/DownloadManager( 3195): in trimDatabase
V/DownloadManager( 3195): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3195): created cursor android.database.sqlite.SQLiteCursor@2ff51289 on behalf of 3195
I/ActivityManager(  831): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7252 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3195): DownloadService onStartCommand
V/DownloadManager( 3195): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3195): created cursor android.database.sqlite.SQLiteCursor@39391aaf on behalf of 3195
I/CheckinService( 4164): Checkin interval check for package: unspecified last checkin: 1452292017927 min interval config: 0 actual interval: 35857
,V/DownloadManager( 3195): DownloadService onDestroy
,I/ActivityManager(  831): Killing 7010:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
I/MusicWidget( 2684): mDelayedStopHandler : unbind
,W/libprocessgroup(  831): failed to open /acct/uid_10079/pid_7010/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2729): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:27:34
D/UpdateThreadPoolManager( 2729): 2 : This is isUpdating : false
D/WeatherAncestor( 2729): connectivity changed - connection : true
D/Weather_cast( 2729): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2729): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:27:34
D/WeatherService( 2729): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  831): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7272 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  831): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2729): 2 : Utils getTopActivity com.lge.launcher2 / true
I/art     (  308): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 330us total 28.495ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 21.646ms
,I/MusicBrowser( 2738): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 25.563ms
,D/WeatherService( 2729): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2729): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/MusicBrowser( 2738): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2738): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2738): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2738): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2738): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
,I/MusicBrowser( 2738): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2738): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  831):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@14e9468acom.lge.music.MediaPlaybackService$6@138d44fb
,D/MusicBrowser( 2738): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
W/ResourcesManager( 7272): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/MusicBrowser( 2738): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2738): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2738): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2738): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@22557401
,I/MusicBrowser( 2738): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2738): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2738): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2738): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2738): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2738): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2738): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2738): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2738): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2738): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2738): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2738): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2738): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2738): reset
,V/MediaPlayer[Native]( 2738): setListener
,V/MediaPlayer[Native]( 2738): disconnect
V/MediaPlayer[Native]( 2738): destructor
V/AudioFlinger(  288): releasing 19 from 2738 for -1
V/AudioFlinger(  288):  decremented refcount to 0
V/AudioFlinger(  288): purging stale effects
V/MediaPlayer[Native]( 2738): disconnect
,D/MusicBrowser( 2738): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2738): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2738): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2738): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2738): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2738): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2738): [SmartShareManagerClient] unregisterListener: 860686616
W/SmartShareClient( 2738): [SmartShareManagerClient] unregisterListener invalid listener: 860686616
I/SmartShareClient( 2738): [SmartShareManagerClient] terminate service: 2738/MediaPlaybackService/147547887
E/HomeCloudIF( 2738): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2738): [SmartShareManagerClient] unbindService context:android.app.Application@31225f71
V/CloudHub( 2738): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2738): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2738): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2738): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2738): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  831): Killing 6992:com.android.vending/u0a36 (adj 15): empty #11
I/CloudHub( 2738): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29996
,W/libprocessgroup(  831): failed to open /acct/uid_10036/pid_6992/cgroup.procs: No such file or directory
,I/Babel_SMS( 7272): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7272): MmsConfig.loadMmsSettings
I/Babel_SMS( 7272): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,I/Babel_SMS( 7272): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7272): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7272): MmsConfig.loadFromResources
E/Babel_SMS( 7272): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7272): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 7272): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7272): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7272): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7272): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7272): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7272): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7272): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7272): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7272): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7272): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7272): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7272): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7272): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7272): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7272): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7272): found sensor: Motion Accel, handle=46
,I/WVCdm   (  288): CdmEngine::CloseSession
I/WVCdm   (  288): L3 Terminate.
W/Settings( 7272): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7272): startup - clean
I/Babel   ( 7272): deleted: false for 0
,I/art     ( 7272): CheckpointMarkThreadRoots callback created = 0xb042d8e0
I/art     ( 7272): CheckpointMarkThreadRoots callback created = 0xb042d8b0
,I/ActivityManager(  831): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7310 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/AudioCapabilities( 7272): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7272): Unsupported mime audio/adpcm
W/AudioCapabilities( 7272): Unsupported mime audio/g726
W/AudioCapabilities( 7272): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 7272): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7272): Unsupported mime video/mjpg
W/VideoCapabilities( 7272): Unsupported mime video/theora
,W/AudioCapabilities( 7272): Unsupported mime audio/evrc
,W/AudioCapabilities( 7272): Unsupported mime audio/qcelp
W/VideoCapabilities( 7272): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7272): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7272): Unsupported mime audio/qcelp
W/AudioCapabilities( 7272): Unsupported mime audio/evrc
W/VideoCapabilities( 7272): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7272): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7272): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7272): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7272): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7272): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7272): onServiceConnected
W/Babel   ( 7272): Attempted to change video mute state without an active call.
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7310): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7310): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 7310): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7310):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7310):   adb logcat -s GAv4
I/NotificationManager( 7272): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 7272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  284): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  284): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  284): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  284): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  284): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  284): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  284): res_queryN name = xxxxx succeed
I/System.out( 7272): propertyValue:false
W/GAv4    ( 7310): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7310): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7310): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7310): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7272): connection state changed from UNKNOWN to CONNECTED
W/GAv4    ( 7310): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/ActivityManager(  831): Killing 6731:com.android.chrome/u0a48 (adj 15): empty #11
I/dex2oat ( 7332): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=38 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/libprocessgroup(  831): failed to open /acct/uid_10048/pid_6731/cgroup.procs: No such file or directory
I/dex2oat ( 7332): dex2oat took 91.662ms (threads: 4)
,I/Adreno-EGL( 6972): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6972): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6972): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6972): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6972): Remote Branch: 
I/Adreno-EGL( 6972): Local Patches: 
I/Adreno-EGL( 6972): Reconstruct Branch: 
,I/WebViewFactory( 7310): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/Adreno-EGL( 6972): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6972): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6972): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6972): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6972): Remote Branch: 
I/Adreno-EGL( 6972): Local Patches: 
I/Adreno-EGL( 6972): Reconstruct Branch: 
,I/LibraryLoader( 7310): Time to load native libraries: 3 ms (timestamps 7936-7939)
I/LibraryLoader( 7310): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7310): Binding Chromium to main looper Looper (main, tid 1) {35f4d28e}
I/LibraryLoader( 7310): Expected native library version number "",actual native library version number ""
I/chromium( 7310): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7310): Initializing chromium process, singleProcess=true
W/art     ( 7310): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7310): ApplicationContext is null in ApplicationStatus
W/chromium( 7310): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7310): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7310): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7310): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7310): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7310): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7310): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7310): Remote Branch: 
I/Adreno-EGL( 7310): Local Patches: 
I/Adreno-EGL( 7310): Reconstruct Branch: 
V/AudioPolicyService(  288): registerClient() client 0xb383bb20, uid 10079
,W/AudioManagerAndroid( 7310): Requires BLUETOOTH permission
I/NSApplication( 7310): Starting up...
I/Adreno-EGL( 6972): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6972): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6972): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6972): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6972): Remote Branch: 
I/Adreno-EGL( 6972): Local Patches: 
I/Adreno-EGL( 6972): Reconstruct Branch: 
,I/ActivityManager(  831): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7378 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  831): Killing 7101:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  831): failed to open /acct/uid_10086/pid_7101/cgroup.procs: No such file or directory
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/ActivityManager(  831): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7397 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  831): Killing 7129:com.google.android.music:main/u0a81 (adj 15): empty #11
,I/CheckinRequestBuilder( 4164): Classify the device as Phone.
,W/libprocessgroup(  831): failed to open /acct/uid_10081/pid_7129/cgroup.procs: No such file or directory
,W/ResourcesManager( 7397): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/libc-netbsd( 4164): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4164): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4164): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4164): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  284): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  284): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  284): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  284): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  284): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  284): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  284): res_queryN name = xxxxx succeed
I/System.out( 4164): propertyValue:false
,D/libc-netbsd( 4164): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4164): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4164): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4164): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4164): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4164): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 4164): Sending checkin request (9847 bytes)
,I/ActivityManager(  831): Killing 7163:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  831): failed to open /acct/uid_10021/pid_7163/cgroup.procs: No such file or directory
,D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  831): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7428 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 7428): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  831): Message: 20
D/BluetoothManagerService(  831): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b237a1b:true
,D/BluetoothAdapterService(1013208552)( 1989): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@777a07e
D/BluetoothAdapterService(1013208552)( 1989): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@777a07e
,I/CheckinRequestBuilder( 4164): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 4164): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  831): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7449 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7428): Create singleton instance
D/UEI.SmartControl( 7449): Quickset Services start...
,I/UEI.SmartControl( 7449): Manufacture = LGE
D/UEI.SmartControl( 7449): File observer start...
E/UEI.SmartControl( 7449): IR Port is disabled: false
D/UEI.SmartControl( 7449): Starting file observer...
D/UEI.SmartControl( 7449): Extracting JNI libs...
D/UEI.SmartControl( 7449): --- this system supports 32-bit or 64-bit only
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AudioManager( 7428): getMode name:com.lge.qremote
,I/CheckinService( 4164): Checkin interval check for package: unspecified last checkin: 1452292017927 min interval config: 0 actual interval: 38803
,D/WearableService( 1731): callingUid 10006, callindPid: 1731
,D/LocationInitializer( 4164): Restart initialization of location
D/AuthorizationBluetoothService( 1731): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/MDM     ( 1731): [143] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinRequestBuilder( 4164): Classify the device as Phone.
I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
,W/GCoreFlp( 1731): No location to return for getLastLocation()
W/FusedLocationProvider( 1731): location=null
I/AudioManager( 7428): getMode name:com.lge.qremote
W/ContextImpl( 3559): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/CheckinTask( 4164): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 4164): Checking schedule, now: 1452292056847 next: 1452819305841
I/CheckinService( 4164): active receiver: disabled
,D/UEI.SmartControl( 7449): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7449): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7449): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/CheckinService( 4164): Checking schedule, now: 1452292056893 next: 1452819305841
I/CheckinService( 4164): active receiver: disabled
,D/CheckinService( 4164): Recording last checkin time for package unspecified as 1452292056905
I/UEI.SmartControl( 7449): --- Selecting new region: 2
,I/UEI.SmartControl( 7449): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7449): Platform has CIR...
D/UEI.SmartControl( 7449): NO CIR support, need to check package...
I/UEI.SmartControl( 7449): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7449): QS Service created
,V/SetupWizard( 7230): Connected to Gservices successfully
,E/UEI.SmartControl( 7449): QS start get config
D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/UEI.SmartControl( 7449): Loading JNI Libs...
,D/UEI.SmartControl( 7449):  configuring local db...
D/UEI.SmartControl( 7449):  ---- Has DB8: true
,D/UEI.SmartControl( 7449): QS start statue = true Error code = 0
D/UEI.SmartControl( 7449): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7449): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7449): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7449): IRRCPlayer_nativeInit ++ 
,D/irrcClient( 7449): IrrcClient ++ 
D/irrcClient( 7449): getIrrcService ++ 
D/irrcClient( 7449): getIrrcService -- 
D/irrcClient( 7449): IrrcClient -- 
W/irrc_jni( 7449): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 7449): Services init done
I/UEI.SmartControl( 7449): Device manager: loading config....
D/UEI.SmartControl( 7449): QS Service init finished
D/UEI.SmartControl( 7449): QS Service version name: 0.1.73
D/UEI.SmartControl( 7449): QS Service version code: 1073
D/UEI.SmartControl( 7449): Service requested: Control
D/UEI.SmartControl( 7449): Config is loaded...
D/UEI.SmartControl( 7449):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7449): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 7449): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 7449): Internal service binding...
D/UEI.SmartControl( 7449): -----IControl: 11
D/UEI.SmartControl( 7449): Caller: com.lge.qremote
D/UEI.SmartControl( 7449): ------------ IControl registerCallback...
I/UEI.SmartControl( 7449): Registering callback...
D/UEI.SmartControl( 7449): -----IControl: 19
,D/UEI.SmartControl( 7449): Caller: com.lge.qremote
I/UEI.SmartControl( 7449): Registering Services Ready callback...
I/UEI.SmartControl( 7449): Notify client services are ready...
D/UEI.SmartControl( 7449): -----IControl: 8
D/UEI.SmartControl( 7449): Caller: com.lge.qremote
I/AudioManager( 7428): getMode name:com.lge.qremote
I/ActivityManager(  831): Killing 7211:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/ActivityManager(  831): Killing 7187:com.lge.lgdmsclient/1000 (adj 15): empty #12
,W/libprocessgroup(  831): failed to open /acct/uid_10011/pid_7211/cgroup.procs: No such file or directory
,W/libprocessgroup(  831): failed to open /acct/uid_1000/pid_7187/cgroup.procs: No such file or directory
I/AudioManager( 7428): getMode name:com.lge.qremote
I/art     (  831): Explicit concurrent mark sweep GC freed 16664(814KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.524ms total 174.026ms
,I/AudioManager( 7428): getMode name:com.lge.qremote
I/[SystemUI]QPairHandler( 1375): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/InputReader(  831): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QSlideListController( 1375): onReceive = android.intent.action.PACKAGE_CHANGED
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
,W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1375): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,V/NetworkPolicy(  831): [LG_RESTRICTED] checkMobilePolicy_type()
D/libc-netbsd(  831): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  831): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  831): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  831): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  284): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  284): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  284): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  284): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  284): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  284): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  284): res_queryN name = xxxxx succeed
I/System.out(  831): propertyValue:false
D/administrator(  831): Handling package changes for user 0
,I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/ActivityManager(  831): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7528 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/AppUp4:AppBoxCP( 7528): onCreate
W/AppUp4:DB( 7528):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7528):  setFingerPrint start
I/AppUp4:DB( 7528):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7528):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7528):  SDK version = 0
I/AppUp4:DB( 7528):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7528): AppBoxApplication onCreate()
I/NotificationManager( 7272): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 7272): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7272): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/AppUp4:CustModeStarterReceiver( 7528): onReceive
I/AppUp4:CustModeStarterReceiver( 7528): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 7528): Context : android.app.ReceiverRestrictedContext@eba7ce
D/AppUp4:CustFacade( 7528): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7528): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7528): begin check event
I/AppUp4:CustModeStarterReceiver( 7528): Event For Nothing, skip.
,I/ActivityManager(  831): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7550 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,V/JNIHelp ( 7272): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/NotificationService(  831): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  831): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  831): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/System  ( 7272): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7272): Installed default security provider GmsCore_OpenSSL
,W/ResourcesManager(  831): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  831): Process com.google.android.apps.magazines (pid 7310) has died
,D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
I/BackupManagerService(  831): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/ResourceType(  831): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,V/BackupManagerService(  831): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  831): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@31c9341c
W/ResourcesManager( 7550): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7550): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7550): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1731): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  831): applying state to connected service
,I/AppConfig( 7550): Total System Memory = 906309632
,I/GalleryUtils( 7550): Application Heap = 96 MB
,I/AppConfig( 7550): App Tier : NOT_DEF
D/SystemHelper( 7550): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  831): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7574 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ResourcesManager( 7574): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7574): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7574): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 7574): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7574): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7574): BUILD Country: EU
I/SystemConfig( 7574): BUILD Operator: OPEN
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
,I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/charger_monitor(  483): init target 500000
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
W/Settings(  831): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  831): battery changed pluggedType: 2
W/Settings(  831): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/charger_monitor(  483): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
,I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1989): Disconnected process message: 10, size: 0
I/ActivityManager(  831): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7593 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  831): Killing 7252:com.lge.drmservice/u0a51 (adj 15): empty #11
,D/libc-netbsd(  831): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  831): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/SystemConfig( 7574): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7574): existFile = false
I/SystemConfig( 7574): canReadFile = false
I/SystemConfig( 7574): systemFeature RCS result false
D/SystemConfig( 7574): refreshRcsSupport() :false
I/ActivityManager(  831): Process com.google.android.apps.plus (pid 7397) has died
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
W/libprocessgroup(  831): failed to open /acct/uid_10051/pid_7252/cgroup.procs: No such file or directory
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1989): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  831): battery changed pluggedType: 2
W/Settings(  831): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  831): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LockScreenSettings( 7593): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7593): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7593): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,D/LockScreenSettings( 7593): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7593): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
,D/LockScreenSettings( 7593): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  831): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7610 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 7610): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1943): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  831): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7638 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 297us total 24.789ms
,I/ActivityManager(  831): Killing 2738:com.lge.music/u0a28 (adj 15): empty #11
I/art     (  308): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 302us total 26.499ms
,V/AudioFlinger(  288): 2738 died, releasing its sessions
V/AudioFlinger(  288):  pid 1750 @ 0
V/AudioFlinger(  288):  pid 3158 @ 1
V/AudioFlinger(  288):  pid 3158 @ 2
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 25.067ms
,W/libprocessgroup(  831): failed to open /acct/uid_10028/pid_2738/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 1943): UpdateCorporaTask done [took 179 ms] updated apps [took 179 ms] 
D/Finsky  ( 7638): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,D/Finsky  ( 7638): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7638): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7638): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7638): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3195): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3195): created cursor android.database.sqlite.SQLiteCursor@27134e45 on behalf of 7638
D/Finsky  ( 7638): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7638): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 7638): Skipping gmscore version check
I/ActivityManager(  831): Killing 7378:com.android.chrome/u0a48 (adj 15): empty #11
,W/libprocessgroup(  831): failed to open /acct/uid_10048/pid_7378/cgroup.procs: No such file or directory
,I/ActivityManager(  831): Killing 7230:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  831): failed to open /acct/uid_10038/pid_7230/cgroup.procs: No such file or directory
,D/Finsky  ( 7638): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 4164): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 4164): Null package name or gms related package.  Ignoreing.
D/Finsky  ( 7638): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 4164): updateResources: need to parse f{com.google.android.gms}
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/Icing   ( 4164): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4164): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  831): Killing 7528:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  831): failed to open /acct/uid_10011/pid_7528/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 7449): Internal timer expired: 1
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  831): Killing 7272:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  831): failed to open /acct/uid_10061/pid_7272/cgroup.procs: No such file or directory
,D/charger_monitor(  483): init target 500000
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
,D/HeadsetStateMachine( 1989): Disconnected process message: 10, size: 0
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
W/Settings(  831): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  831): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/charger_monitor(  483): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/WifiController(  831): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  831): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  831): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  831): tsOffsetIs: Apps: 134218569745; DSPS: 4496154; Offset : -3004915715
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/AlarmManager(  831): ELAPSED_WAKEUP set : Alarm{3020b1b2 type 2 when 140273 com.google.android.gms} when 140273
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1731): Vacuum at: now=1452292077977 tag=VacuumService
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/libc-netbsd(  831): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  831): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  831): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  831): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  284): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  284): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  284): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  284): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  284): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  284): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  284): res_queryN name = xxxxx succeed
I/System.out(  831): propertyValue:false
D/AlarmManagerService(  831): Setting time of day to sec=1452292079
,W/AlarmManagerService(  831): Unable to set rtc to 1452292079: Invalid argument
I/[SystemUI]Clock( 1375): onReceive = android.intent.action.TIME_SET
,I/LgeClockWidgetControlView( 1375): time changed, timezoneChanged : false
,D/WeatherService( 2729): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 23:27:59
D/WeatherService( 2729): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2729): 2 : This is isUpdating : false
D/WeatherService( 2729): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2729): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2729): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2729): 2 : Fixed theme : optimus
,I/ActivityManager(  831): Start proc com.lge.email for broadcast com.lge.email/.receiver.UpdateScheduleReceiver: pid=7745 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
W/ActivityManager(  831): getTasks: caller 10024 is using old GET_TASKS but privileged; allowing
D/WeatherReflect( 2729): 2 : Map key string is -2
,I/[LGHome]LGDateChangeReceiver( 1876): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=8 currentDate=-1 dayofweek=6 currentDayOfWeek=-1
D/lim     ( 2729): 2 : time = 23:27
,I/WeatherReflect( 2729): Model Name : LG-D722
,D/WeatherTheme( 2729): 2 : exactly same view!
D/WeatherTheme( 2729): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
D/WeatherService( 2729): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 23:27:59
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/[LGHome]LGCalendarIcon( 1876): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Fri date= 8
,D/PowerManagerServiceEx(  831): acquireWakeLockInternal: lock=21045627, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=831
I/[LGHome]LGCalendarIcon( 1876): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Fri date= 8
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
W/ResourcesManager( 7745): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7745): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7745): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/LGEmail ( 7745): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7745): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  831): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=7769 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/ActivityManager(  831): Killing 7550:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/libprocessgroup(  831): failed to open /acct/uid_10023/pid_7550/cgroup.procs: No such file or directory
,D/ALBootInit( 7769): ====action==>android.intent.action.TIME_SET
,D/ALBootInit( 7769): Alarm ALBootInit: TIME_SET
D/Alarms  ( 7769): [setNextAlert] start
D/Alarms  ( 7769): [setNextAlert] (1)
,D/Alarms  ( 7769):  minTime  = 0
D/Alarms  ( 7769):  -- OK multi -- 0
E/jeny.kim( 7769): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 7769): [setNextAlert]setNextAlert temp_AlarmLinkText + 
I/CommonUtil( 7769): BUILD Operator: OPEN
,D/Alarms  ( 7769): broadcastToWidgetProvider : false
I/DigitalAppWidgetProvider( 7769): onReceive: android.intent.action.ALARM_CHANGED
I/ActivityManager(  831): Killing 7574:com.android.contacts/u0a18 (adj 15): empty #11
D/Alarms  ( 7769): Enter formatDayAndTime(final Context context, long timeInMiliSec)
,W/libprocessgroup(  831): failed to open /acct/uid_10018/pid_7574/cgroup.procs: No such file or directory
,V/SettingsProvider(  831): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
D/WeatherAncestor( 2729): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 23:28:0
I/DigitalAppWidgetProvider( 7769): onReceive: android.intent.action.TIME_SET
D/UpdateThreadPoolManager( 2729): 2 : This is isUpdating : false
,V/DigitalAppWidgetProvider( 7769): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@11e72da
D/Weather_cast( 2729): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2729): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 23:28:0
D/WeatherService( 2729): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
W/ActivityManager(  831): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2729): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2729): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2729): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
V/DigitalAppWidgetProvider( 7769): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@11e72da
D/QuickCoverProvider( 7769): onReceiver
,I/ActivityManager(  831): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=7792 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
I/art     (  831): Explicit concurrent mark sweep GC freed 44405(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.241ms total 152.164ms
,W/ResourcesManager( 7792): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/CalendarApplication( 7792): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 7792): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 7792): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@3458f4c9, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@eba7ce, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@8cb66ef, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@3d1d5fc, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@c731485, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@11e72da, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@2f91830b, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@3c6455e8, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@22557401, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@2180e2a6, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@3b5344e7, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@131ce894, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@28a44f3d, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@24488332, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@35854883, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@3e29fa00, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@1e0ba239, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@777a07e, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@49e9df, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@2634b62c, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@25fb28f5, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@14e9468a, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@138d44fb, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@334d0918, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@31225f71, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@271d4156, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@2fe135d7, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@3c959ec4, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@31ac81ad, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@2ec41ce2, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@23195873, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@6afe330, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@173c8ba9, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@50b252e, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@3aa708cf, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@3ce8025c, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@ea93965, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@16a8663a, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@3fb562eb, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1120e848, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@17906e1, lg_preferences_recent_t,imezones=com.android.calendar.adaptation.PreferenceKey$KeyData@33a6ac06, l
,D/GeneralPreferenceUtils( 7792): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 7792): [init]
I/Config  ( 7792): LGCalendar ver.4.40.17
I/Config  ( 7792): start check model
I/Config  ( 7792): start check native_ca
,I/Config  ( 7792): Config Operator=OPEN, Country=EU
D/Config  ( 7792): [setDefaultValuesToPref]
D/Config  ( 7792): [parseProfiles]
D/ProfilesParser( 7792): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 7792): [debug_displayParseInfos] profile.operator = null
D/Config  ( 7792): [updateProfiletoCountryInfo]
D/GeneralPreference( 7792): [checkAndMigrateOldPreference]
E/AgendaWidgetManager( 7792): [updateWidgets] 
,I/InitNotificationRingtoneService( 7792): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 7792): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,I/AlertUtils( 7792): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 7792): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 7792): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 7792): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 7792): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 7792): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 7792): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/AlertUtils( 7792): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 7792): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 7792): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 7792): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
,I/AlertUtils( 7792): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 7792): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 7792): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 7792): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,I/AlertUtils( 7792): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 7792): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 7792): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 7792): End InitializeAlertRingtoneService.onHandleIntent
,W/HolidayIntentService( 7792): onHandleIntent
D/MonthWidgetProvider( 7792): [onReceive]
D/CalendarWidgetProvider( 7792): [onReceive]
D/CalendarWidgetProvider( 7792): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
,D/CalendarTypeController( 7792): [onUpdateAndInitCalendarTime]
D/HolidayDataLoader( 7792): readJsonAsset : holiday.json
D/WeekWidgetProvider( 7792): [onReceive]
D/CalendarWidgetProvider( 7792): [onReceive]
D/CalendarWidgetProvider( 7792): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 7792): [onUpdateAndInitCalendarTime]
D/WeatherAncestor( 2729): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 23:28:1
D/UpdateThreadPoolManager( 2729): 2 : This is isUpdating : false
D/Weather_cast( 2729): 2 : set auto-update time : 1/9 2:28
D/WeatherAncestor( 2729): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 23:28:1
D/WeatherService( 2729): 2 : onStartCommand, intent!=null, action: android.intent.action.TIME_SET
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ActivityManager(  831): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7816 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
W/ActivityManager(  831): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2729): 2 : Utils getTopActivity com.lge.launcher2 / true
,E/HolidayIntentService( 7792): onHandleIntent:holiday data empty
,D/WeatherService( 2729): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2729): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/ActivityManager(  831): Killing 7593:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
W/libprocessgroup(  831): failed to open /acct/uid_10069/pid_7593/cgroup.procs: No such file or directory
,D/TimeService( 7816): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1452292081329
,D/        ( 7816): TimeServiceNative: User Time to be set is 1452292081329
D/QC-time-services( 7816): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 7816): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 7816): Lib:time_genoff_operation: pargs->ts_val = 1452292081329
,D/QC-time-services( 7816): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  323): Daemon: Connection accepted:time_genoff
D/QC-time-services(  323): Daemon:Received base = 2, unit = 1, operation = 0,value = 1452292081329
D/QC-time-services(  323): Daemon:genoff_opr: Base = 2, val = 1452292081329, operation = 0
D/QC-time-services(  323): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS4/22/70 2:29:39
D/QC-time-services(  323): Daemon:Value read from RTC seconds = 12191379000
D/QC-time-services(  323): Daemon:new time 1452292081329 
D/QC-time-services(  323): Daemon: delta 1440100702329 genoff 1440100702329 
D/QC-time-services(  323): Daemon:genoff_persistent_update: Writing genoff = 1440100702329 to memory
,D/QC-time-services(  323): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  323): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  323): Updating the TOD offset
D/QC-time-services(  323): Daemon:genoff_persistent_update: Writing genoff = 1440100702329 to memory
D/QC-time-services(  323): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  323): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services( 7816): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
E/QC-time-services(  323): Daemon:Update to modem bit set
D/QC-time-services(  323): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  323): Daemon: Base = 2, Value being sent to MODEM = 1124135902329
E/QC-time-services(  323): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  323): Daemon: Time-services: Waiting to acceptconnection
I/CheckinService( 4164): Checkin interval check for package: unspecified last checkin: 1452292056905 min interval config: 0 actual interval: 24461
,I/ActivityManager(  831): Killing 7610:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  831): failed to open /acct/uid_10086/pid_7610/cgroup.procs: No such file or directory
,D/WeatherService( 2729): 2 : TimeTick Intent has been received, Time(hour:min:sec) 23:28:1
,D/WeatherService( 2729): 2 : TimeTick Intent And Screen On
D/WeatherService( 2729): 2 : SDK version : 21
W/ActivityManager(  831): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2729): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2729): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2729): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2729): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2729): 2 : This is isUpdating : false
D/WeatherService( 2729): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2729): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2729): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2729): 2 : Fixed theme : optimus
D/WeatherReflect( 2729): 2 : Map key string is -2
D/lim     ( 2729): 2 : time = 23:28
I/WeatherReflect( 2729): Model Name : LG-D722
D/WeatherTheme( 2729): 2 : Different view - status_min_formatted : 27 != 28
D/WeatherTheme( 2729): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2729): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2729): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2729): currentPackage=com.lge.sizechangable.weather.theme.optimus
,D/Weather4x2_optimus( 2729): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2729): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2729): forecast size is 0
D/Theme   ( 2729): strTheme: com.lge.launcher2.theme.optimus
,D/Theme   ( 2729): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
,D/Theme   ( 2729): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2729): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2729): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2729): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2729): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2729): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2729): url is : null
D/Theme   ( 2729): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2729): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2729): 2 : update view, appWidgetId: 2
D/WeatherService( 2729): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 23:28:1
D/PowerManagerServiceEx(  831): releaseWakeLockInternal: lock=21045627 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/PowerManagerService(  831): ALS enabled for SRE
D/PowerManagerServiceEx(  831): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (31086 ms ago)
,D/qdlights(  831): set_light_backlight: 253
,D/qdlights(  831): set_light_backlight: 250
D/qdlights(  831): set_light_backlight: 247
,D/qdlights(  831): set_light_backlight: 243
,D/qdlights(  831): set_light_backlight: 240
,D/qdlights(  831): set_light_backlight: 237
,D/qdlights(  831): set_light_backlight: 233
,D/qdlights(  831): set_light_backlight: 230
,D/qdlights(  831): set_light_backlight: 227
,D/qdlights(  831): set_light_backlight: 223
,D/qdlights(  831): set_light_backlight: 220
,D/qdlights(  831): set_light_backlight: 217
,D/qdlights(  831): set_light_backlight: 213
,D/qdlights(  831): set_light_backlight: 210
,D/qdlights(  831): set_light_backlight: 207
,D/qdlights(  831): set_light_backlight: 203
,D/qdlights(  831): set_light_backlight: 200
,D/qdlights(  831): set_light_backlight: 197
,D/qdlights(  831): set_light_backlight: 193
,D/qdlights(  831): set_light_backlight: 190
,D/qdlights(  831): set_light_backlight: 187
,D/qdlights(  831): set_light_backlight: 183
,D/qdlights(  831): set_light_backlight: 180
,D/qdlights(  831): set_light_backlight: 177
,D/qdlights(  831): set_light_backlight: 173
,D/qdlights(  831): set_light_backlight: 170
,D/qdlights(  831): set_light_backlight: 167
,D/qdlights(  831): set_light_backlight: 163
,D/qdlights(  831): set_light_backlight: 160
,D/qdlights(  831): set_light_backlight: 157
,D/qdlights(  831): set_light_backlight: 153
,D/qdlights(  831): set_light_backlight: 150
,D/qdlights(  831): set_light_backlight: 147
,D/qdlights(  831): set_light_backlight: 143
,D/qdlights(  831): set_light_backlight: 140
,D/qdlights(  831): set_light_backlight: 137
,D/qdlights(  831): set_light_backlight: 133
,D/qdlights(  831): set_light_backlight: 130
,D/qdlights(  831): set_light_backlight: 127
,D/qdlights(  831): set_light_backlight: 123
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/qdlights(  831): set_light_backlight: 120
,D/qdlights(  831): set_light_backlight: 117
,D/qdlights(  831): set_light_backlight: 113
,D/qdlights(  831): set_light_backlight: 110
,D/qdlights(  831): set_light_backlight: 107
,D/qdlights(  831): set_light_backlight: 103
,D/qdlights(  831): set_light_backlight: 100
,D/qdlights(  831): set_light_backlight: 97
,D/qdlights(  831): set_light_backlight: 93
,D/qdlights(  831): set_light_backlight: 90
,D/qdlights(  831): set_light_backlight: 87
,D/qdlights(  831): set_light_backlight: 83
,D/qdlights(  831): set_light_backlight: 80
,D/qdlights(  831): set_light_backlight: 77
,D/qdlights(  831): set_light_backlight: 73
,D/qdlights(  831): set_light_backlight: 70
,D/qdlights(  831): set_light_backlight: 67
,D/qdlights(  831): set_light_backlight: 63
,D/qdlights(  831): set_light_backlight: 60
,D/qdlights(  831): set_light_backlight: 57
,D/qdlights(  831): set_light_backlight: 53
,D/qdlights(  831): set_light_backlight: 50
,D/qdlights(  831): set_light_backlight: 47
,D/qdlights(  831): set_light_backlight: 43
,D/qdlights(  831): set_light_backlight: 40
,D/qdlights(  831): set_light_backlight: 37
,D/qdlights(  831): set_light_backlight: 33
,D/qdlights(  831): set_light_backlight: 30
,D/qdlights(  831): set_light_backlight: 27
,D/qdlights(  831): set_light_backlight: 23
,D/qdlights(  831): set_light_backlight: 20
,D/qdlights(  831): set_light_backlight: 17
,D/qdlights(  831): set_light_backlight: 13
,D/qdlights(  831): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  831): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  831): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  831): tsOffsetIs: Apps: 154219318123; DSPS: 5151539; Offset : -3004935329
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PowerManagerService(  831): ALS enabled for SRE
D/PowerManagerServiceEx(  831): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (38074 ms ago)
,I/PowerManagerService(  831): Going to sleep due to screen timeout (uid 1000)...
I/PowerManagerService(  831): ALS enabled for SRE
D/PowerManagerServiceEx(  831): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (38091 ms ago)
,W/ContextImpl(  831): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  831): Sleeping (uid 1000)...
D/LPWGController(  831): [updateScreenState] screen on = false
D/LPWGController(  831): disable proximity sensor
,D/LPWGController(  831): enable proximity sensor
I/SensorManager(  831): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@1da09761] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  831): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  831): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  831): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  831): activate: handle is 48, enable
,V/sensors_hal_Ctx(  831): activate sensors is 1400000000000
D/sensors_hal_Thresh(  831): enable: handle=48
I/sensors_hal_SAM(  831): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  831): waitForResponse: timeout=1000
V/sensors_hal_SAM(  831): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  831): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  831): enable: Received response: 0
D/PowerManagerServiceEx(  831): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (38146 ms ago)
I/Adreno-EGL(  831): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  831): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  831): Build Date: 03/02/15 Mon
I/Adreno-EGL(  831): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  831): Remote Branch: 
I/Adreno-EGL(  831): Local Patches: 
I/Adreno-EGL(  831): Reconstruct Branch: 
,D/PermissionCache(  245): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1061 us)
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/Sensors (  431): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  831): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  831): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  831): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  831): processInd: handle 48, count=1
V/sensors_hal_Thresh(  831): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  831): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  831): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  831): poll: count: 256
I/sensors_hal_Ctx(  831): poll: released wakelock sensor_ind
D/sensors_hal_Util(  831): waitForResponse: timeout=0
D/LPWGController(  831): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  831): current mode = 1  value = 1 1
I/LPWGController(  831): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  831): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  831): set_light_backlight: 0
,I/SensorManager(  831): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  831): activate: handle is 46, disable
V/sensors_hal_Ctx(  831): activate sensors is 1000000000000
D/sensors_hal_LP2(  831): enable: handle=46
,D/sensors_hal_LP2(  831): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  831): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  245): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  245): hwc_blank: Blanking display: 0
,I/DisplayManagerService(  831): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/sensors_hal_SAM(  831): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  831): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,V/ActivityManager(  831): Display changed displayId=0
,D/DSDPConnection( 1750): Display #0 changed.
,D/qdhwcomposer(  245): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  831): Excessive delay in setPowerMode(): 202ms
,I/qdhwcomposer(  245): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  831): Got set_interactive hint
D/KeyguardViewMediator( 1375): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1375): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1334): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1334): notifyScreenOffLocked
D/SmartCoverViewMediator( 1334): handleNotifyScreenOFF
D/KeyguardViewMediator( 1375): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1375): handleNotifyScreenOff
,D/ScreenTurnOffBySensor( 1375): unregisterProximitySensor
,D/StatusBarWindowView( 1375): onScreenTurnedOff why = 3
D/WifiServerServiceExt(  831): sendKtScanInterval  mRtspPlay : false
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
V/AudioFlinger(  288): setParameters(): io 0, keyvalue screen_state=on, calling pid 831
,D/audio_hw_primary(  288): adev_set_parameters: enter: screen_state=on
,V/voice   (  288): voice_set_parameters: enter: screen_state=on
V/compress_voip(  288): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  288): voice_extn_compress_voip_set_parameters: exit
V/voice   (  288): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  288): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  288): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  288): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  288): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  288): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  288): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  288): adev_set_parameters: exit with code(0)
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/WifiServerServiceExt(  831): set CMD_KT_SCAN_INTERVAL
,D/GpsLocationProvider(  831): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1839): |CORE| sendScreenState: state:true
I/LEDService( 1803): getCurrentHighestLGLedRecord() start. size = 1
,D/LNfcService( 1786): action : android.intent.action.SCREEN_ON
D/LEDService( 1803): stopPatternFlashing()
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
I/Cliptray Service( 1803): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/Cliptray Service( 1803): lockStatus = 0
I/LEDService( 1803): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
,D/NfcServiceNXP( 1786): mScreenState : 3, mInProvisionMode : false
,D/NfcServiceNXP( 1786): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
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
I/LEDService( 1803): updateLightsLocked : turn off led
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1803): RESTART MSG
D/SplitWindow(  831): check instance of lgWin Window{33176b74 u0 SearchPanel}
,D/Ulp_jni (  831): JNI:system_update. Event-0
,D/InputDispatcher(  831): Window went away: Window{2fc818a7 u0 SearchPanel}
,I/[SystemUI]Clock( 1375): onReceive = android.intent.action.SCREEN_ON
,I/LgeClockWidgetControlView( 1375): time changed, timezoneChanged : false
,I/Sensors (  431): sns_pwr.c(301):releasing wakelock
,V/PhoneApp( 1750): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2729): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 23:28:17
,D/WeatherService( 2729): 2 : ACTION screen on
D/WeatherService( 2729): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2729): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2729): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 23:28:17
W/Settings(  831): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  831): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  831): ACTION_SCREEN_ON
D/AppCleanupService( 4022): android.intent.action.SCREEN_ON
,V/AudioFlinger(  288): setParameters(): io 0, keyvalue screen_state=off, calling pid 831
,D/audio_hw_primary(  288): adev_set_parameters: enter: screen_state=off
V/voice   (  288): voice_set_parameters: enter: screen_state=off
V/compress_voip(  288): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  288): voice_extn_compress_voip_set_parameters: exit
V/voice   (  288): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  288): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  288): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  288): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  288): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  288): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  288): adev_set_parameters: exit with code(0)
D/WifiController(  831): CMD_SCREEN_OFF 
D/WifiController(  831): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  831): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1839): |CORE| sendScreenState: state:false
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
,I/[LGHome]EVENT( 1876): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1750): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2729): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 23:28:17
D/WeatherService( 2729): 2 : ACTION screen off
D/WeatherService( 2729): 2 : TimeTick Receiver Unregister
D/WeatherService( 2729): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 23:28:17
W/Settings(  831): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  831): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  831): ACTION_SCREEN_OFF
D/AppCleanupService( 4022): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 4022): AppUsageStatsSaveTask
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
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/charger_monitor(  483): init target 500000
,D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1989): Disconnected process message: 10, size: 0
W/Settings(  831): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  831): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  831): battery changed pluggedType: 2
D/HeadsetStateMachine( 1989): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
,D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
W/Settings(  831): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  831): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  831): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,D/KeyguardViewMediator( 1375): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  831): ELAPSED_WAKEUP set : Alarm{336e489d type 2 when 164028 com.android.systemui} when 164028
,D/PhoneUtils( 1750): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1750): getCallState : 0
,D/PhoneUtils( 1750): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1375): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1375): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  831): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  831): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  831): tsOffsetIs: Apps: 174220430096; DSPS: 5806935; Offset : -3004922040
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  483): init target 500000
,D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/HeadsetStateMachine( 1989): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  831): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  831): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  831): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,V/AlarmManager(  831): ELAPSED_WAKEUP set : Alarm{682f112 type 2 when 190046 android} when 190046
,V/AlarmManager(  831): ELAPSED_WAKEUP set : Alarm{312050e3 type 2 when 190048 com.google.android.gms} when 190048
,I/art     ( 1731): Explicit concurrent mark sweep GC freed 43835(2MB) AllocSpace objects, 38(608KB) LOS objects, 40% free, 13MB/22MB, paused 1.820ms total 112.360ms
,I/PhenotypeConfigurator( 1731): Scheduling Phenotype for one-off execution 5112 seconds from now (1452292127961)
D/GetConfigurationSnapshotOperation( 1731): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1731): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1731): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  831): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  284): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  284): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  284): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  284): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  284): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  284): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  284): res_queryN name = xxxxx succeed
I/System.out( 1731): propertyValue:false
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/LocationManagerService(  831): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LocationManagerService(  831): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  831): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  831): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  831): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  831): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  831): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  831): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  831): tsOffsetIs: Apps: 194221122380; DSPS: 6462318; Offset : -3004933666
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  831): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  831): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  831): tsOffsetIs: Apps: 214221806694; DSPS: 7117700; Offset : -3004918655
,I/ClearcutLoggerApiImpl( 1731): disconnect managed GoogleApiClient
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  831): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  831): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  831): tsOffsetIs: Apps: 234222509552; DSPS: 7773083; Offset : -3004918092
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  483): init target 500000
,D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1989): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 271, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 271
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  831): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  831): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  831): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  831): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  831): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  831): tsOffsetIs: Apps: 254223201159; DSPS: 8428466; Offset : -3004928206
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  831): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  831): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  831): tsOffsetIs: Apps: 274223889899; DSPS: 9083849; Offset : -3004941267
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  831): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  831): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  831): tsOffsetIs: Apps: 294224563800; DSPS: 9739231; Offset : -3004938883
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/jxcore-log( 6138): --= Surplus to requirements =--
I/jxcore-log( 6138): 
I/jxcore-log( 6138): ****TEST TOOK:  ms ****
I/jxcore-log( 6138): 
I/jxcore-log( 6138): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6138): 
,D/AndroidRuntime( 7956): 
D/AndroidRuntime( 7956): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7956): CheckJNI is OFF
,D/AndroidRuntime( 7956): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  831): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
,I/ActivityManager(  831): Killing 6138:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  831): WIN DEATH: Window{1d4deeff u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/InputDispatcher(  831): Focus left window: Window{1d4deeff u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  831): Window went away: Window{1d4deeff u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  831): Skipping PackageSetting{2002e29 com.example.hello/10317} due to missing metadata
,I/ActivityManager(  831):   Force finishing activity ActivityRecord{30476e09 u0 com.test.thalitest/.MainActivity t220}
,V/ActivityManager(  831): Display changed displayId=0
,D/DSDPConnection( 1750): Display #0 changed.
D/charger_monitor(  483): init target 500000
,D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
W/ActivityManager(  831): Spurious death for ProcessRecord{2b3738d3 6138:com.test.thalitest/u0a316}, curProc for 6138: null
I/ActivityManager(  831): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  831):   Force finishing activity ActivityRecord{30476e09 u0 com.test.thalitest/.MainActivity t220 f}
W/ActivityManager(  831): Duplicate finish request for ActivityRecord{30476e09 u0 com.test.thalitest/.MainActivity t220 f}
,I/[LGHome]EVENT( 1876): [Launcher.java:5203:onStart()]onStart
D/KeyguardModel( 1375): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/[LGHome]EVENT( 1876): [Launcher.java:776:onResume()]onResume
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,I/art     ( 1943): Explicit concurrent mark sweep GC freed 9346(545KB) AllocSpace objects, 3(72KB) LOS objects, 39% free, 12MB/21MB, paused 6.209ms total 111.687ms
I/art     ( 4164): Explicit concurrent mark sweep GC freed 4712(251KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 14MB/18MB, paused 1.802ms total 111.437ms
,I/InputReader(  831): Reconfiguring input devices.  changes=0x00000010
W/System.err( 3559): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/GeofencerStateMachine( 1731): Ignoring removeGeofence because network location is disabled.
W/System.err( 3559): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3559): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
,W/System.err( 3559): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3559): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3559): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3559): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3559): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3559): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3559): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3559): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3559): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/PackageChangeReceiver( 7745): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/ActivityManager(  831): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7988 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1876): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/ActivityManager(  831): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7994 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/[LGHome]LGActivityUtil( 1876): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1876): [Launcher.java:929:onResume()]onResume end
I/Activity( 1876): Activity.onPostResume() called 
,I/[SystemUI]QSlideListController( 1375): onReceive = android.intent.action.PACKAGE_REMOVED
,I/[LGHome]EVENT( 1876): [Launcher.java:986:onPause()]onPause
,I/art     (  831): Explicit concurrent mark sweep GC freed 37865(2MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 23MB/35MB, paused 9.229ms total 292.603ms
I/art     (  831): WaitForGcToComplete blocked for 191.027ms for cause Explicit
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 271, mChargingStatus=5, mChargingStop=false
,D/HeadsetStateMachine( 1989): Disconnected process message: 10, size: 0
I/LockScreenSettings( 7988): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,W/[LGHome]LGWallpaperInfo( 1876): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1876): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
I/SystemUI[Framework](  831): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1375): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1375): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 271
W/PhoneWindowManagerEx(  831): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  831): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  831): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  831): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@21de9a98,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  831): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  831): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/PhoneWindowManagerEx(  831): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  831): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  831): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  831): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@21de9a98,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  831): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher(  831): Focus entered window: Window{18b98781 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/KeyguardModel( 1375): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1375): createShortcutInfo...
I/AppUp4:AppBoxCP( 7994): onCreate
W/AppUp4:DB( 7994):  [AppBoxDatabaseHelper] construct
D/KeyguardModel( 1375): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1375): createShortcutInfo...
,W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1375): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1375): createShortcutInfo...
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/AppUp4:DB( 7994):  setFingerPrint start
I/AppUp4:DB( 7994):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
D/KeyguardModel( 1375): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1375): createShortcutInfo...
I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1375): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1375): createShortcutInfo...
I/AppUp4:DB( 7994):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7994):  SDK version = 0
,I/[LGHome]EVENT( 1876): [Launcher.java:5214:onStop()]onStop
I/AppUp4:DB( 7994):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7994): AppBoxApplication onCreate()
D/KeyguardModel( 1375): handleShortcutListChanged...
I/[LGHome]EVENT( 1876): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
D/KeyguardModel( 1375): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1375): createShortcutInfo...
I/PhoneWindow( 1876): [setNavigationBarColor] color=0x 0
D/KeyguardModel( 1375): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1375): createShortcutInfo...
,W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1375): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1375): createShortcutInfo...
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1375): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1375): createShortcutInfo...
D/administrator(  831): Handling package changes for user 0
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,D/KeyguardModel( 1375): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1375): createShortcutInfo...
I/ActivityManager(  831): Killing 6972:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
D/AppUp4:PreloadHelper( 7994): added Exclude : com.test.thalitest
,D/KeyguardModel( 1375): handleShortcutListChanged...
,W/InputMethodManagerService(  831): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  831): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8025 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  831): Killing 7638:com.android.vending/u0a36 (adj 15): empty #11
I/art     (  831): Explicit concurrent mark sweep GC freed 6998(386KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 10.916ms total 309.335ms
W/InputMethodManagerService(  831): Got RemoteException sending setActive(false) notification to pid 6138 uid 10316
,I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/libprocessgroup(  831): failed to open /acct/uid_10006/pid_6972/cgroup.procs: No such file or directory
W/libprocessgroup(  831): failed to open /acct/uid_10036/pid_7638/cgroup.procs: No such file or directory
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/Timeline(  831): Timeline: Activity_windows_visible id: ActivityRecord{3da6dbdd u0 com.lge.launcher2/.Launcher t219} time:308313
I/NotificationService(  831): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  831): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  831): Receieved: android.intent.action.PACKAGE_REMOVED
W/Settings(  831): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  831): battery changed pluggedType: 2
W/Settings(  831): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TaskPersister(  831): removeObsoleteFile: deleting file=220_task.xml
,D/PhoneStatusBar( 1375): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
W/IInputConnectionWrapper( 1876): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/[SystemUI]NavigationThemeResource( 1375): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1375):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1375): , Keyguard show=false, IME shown=false, Panel expanded=false
E/b       ( 1628): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1876): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1876): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/AndroidRuntime( 7956): Shutting down VM
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
,W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
,W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
,W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
W/ResourcesManager(  831): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,W/ResourcesManager( 8025): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8025): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 8025): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8025): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 8025): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
E/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
W/IInputConnectionWrapper( 1876): getTextAfterCursor on inactive InputConnection
,I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/IndexDatabaseHelper( 8025): Using schema version: 115
,I/IndexDatabaseHelper( 8025): Index is fine
I/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,W/ResourceType(  831): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/Timeline( 1876): Timeline: Activity_idle id: android.os.BinderProxy@380d8d4a time:308841
,W/FileUtils( 1876): Failed to chmod(/data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
I/art     ( 1876): Explicit concurrent mark sweep GC freed 28261(1545KB) AllocSpace objects, 20(2MB) LOS objects, 40% free, 15MB/25MB, paused 1.203ms total 56.651ms

```
