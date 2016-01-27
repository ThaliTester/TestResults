#### Test 564496604206eac_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/Icing   ( 4199): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
I/Icing   ( 4199): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
--------- beginning of system
I/ActivityManager(  860): Killing 5951:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  860): failed to open /acct/uid_10011/pid_5951/cgroup.procs: No such file or directory
D/AndroidRuntime( 6041): 
D/AndroidRuntime( 6041): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6041): CheckJNI is OFF
D/AndroidRuntime( 6041): Calling main entry com.android.commands.am.Am
I/ActivityManager(  860): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/ActivityManager(  860): setTaskToReturnTo : TaskRecord{3f0344b3 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  860): setTaskToReturnTo : TaskRecord{3f0344b3 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  860): AppWindowTokenEx init.. 
D/ContextHelper(  860): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/SplitWindow(  860): check instance of lgWin Window{2574d9c u0 Starting com.test.thalitest}
I/[LGHome]EVENT( 1877): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  860): Focus left window: Window{c6ac085 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 6041): Shutting down VM
I/ActivityManager(  860): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6056 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1877): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[LGHome]EVENT( 1877): [Launcher.java:5214:onStop()]onStop
I/HotwordDetector( 1939): Closing mic
I/WindowStateAnimator(  860): Starting window displayed
I/MicrophoneInputStream( 1939): mic_close com.google.android.apps.gsa.speech.audio.u@287f04dc
I/SystemUI[Framework](  860): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1373): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
V/AudioRecord( 1939): stop()
D/AudioRecord( 1939): AudioRecord->stop()
W/PhoneWindowManagerEx(  860): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  860): setLGSystemUiVisibility(0x0)
V/AudioFlinger(  282): RecordHandle::stop()
D/StatusBarManagerServiceEx(  860): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
V/AudioFlinger(  282): RecordThread::stop
I/SystemUI[Framework](  860): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@fb8a806,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  860): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
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
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb39dc000
D/audio_hw_primary(  282): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
I/[SystemUI]NavigationThemeResource( 1373): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1373):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1373): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1373): draw background and invalidate : color = 18000000
D/BarTransitions( 1373): draw background and invalidate : color = 312f2f2f
,V/audio_hw_primary(  282): stop_input_stream: enter: usecase(7: audio-record)
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
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb39dc000
V/AudioFlinger(  282): RecordThread: loop stopping
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioRecord( 1939): stop()
V/AudioRecord( 1939): stop()
V/AudioRecord( 1939): stop()
V/AudioFlinger(  282): releasing 16 from 1939 for -1
V/AudioFlinger(  282):  decremented refcount to 0
V/AudioFlinger(  282): purging stale effects
V/AudioFlinger(  282): RecordHandle::stop()
V/AudioFlinger(  282): RecordThread::stop
V/AudioPolicyManager(  282): releaseInput() 17
V/AudioPolicyManager(  282): closeInput(17)
V/AudioFlinger(  282): closeInput() 17
V/AudioSystem(  282): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1373): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  860): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1939): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): ThreadBase::exit
V/AudioFlinger(  282): RecordThread: loop starting
V/AudioSystem( 1750): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): RecordThread 0xb39dc000 exiting
V/AudioSystem( 2012): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  282): adev_close_input_stream: enter:stream_handle(0xb546e1a0)
D/audio_hw_primary(  282): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioSystem( 2618): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3231): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  282): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  282): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyManager(  282): releaseInput() exit
V/AudioFlinger(  282): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  282): removeClient_l() pid 1939, calling pid 282
I/HotwordRecognitionRnr( 1939): Stopping hotword detection.
I/HotwordRecognitionRnr( 1939): Hotword detection finished
D/ContextHelper( 6056): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 6056): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 6056): Time to load native libraries: 3 ms (timestamps 3128-3131)
I/LibraryLoader( 6056): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6056): Binding Chromium to main looper Looper (main, tid 1) {17070c71}
I/LibraryLoader( 6056): Expected native library version number "",actual native library version number ""
I/chromium( 6056): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6056): Initializing chromium process, singleProcess=true
W/art     ( 6056): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6056): ApplicationContext is null in ApplicationStatus
I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
W/chromium( 6056): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6056): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6056): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6056): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6056): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6056): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6056): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6056): Remote Branch: 
I/Adreno-EGL( 6056): Local Patches: 
I/Adreno-EGL( 6056): Reconstruct Branch: 
V/AudioPolicyService(  282): registerClient() client 0xb40272c0, uid 10316
D/BluetoothManagerService(  860): Message: 20
D/BluetoothManagerService(  860): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@381ac3ff:true
,D/BluetoothAdapterService(900660909)( 2012): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3af047eb
W/art     ( 6056): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6056): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6056): CordovaWebView is running on device made by: LGE
,W/art     ( 6056): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6056): Attempt to remove local handle scope entry from IRT, ignoring
I/Activity( 6056): Activity.onPostResume() called 
,D/OpenGLRenderer( 6056): Render dirty regions requested: true
I/OpenGLRenderer( 6056): Initialized EGL, version 1.4
D/OpenGLRenderer( 6056): Enabling debug mode 0
,D/Atlas   ( 6056): Validating map...
,D/SplitWindow(  860): check instance of lgWin Window{2bf2aaef u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 6056): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  860): Focus entered window: Window{2bf2aaef u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  860): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  860): Displayed com.test.thalitest/.MainActivity: +1s89ms
I/Timeline(  860): Timeline: Activity_windows_visible id: ActivityRecord{28c4fa70 u0 com.test.thalitest/.MainActivity t222} time:93807
,I/Timeline( 6056): Timeline: Activity_idle id: android.os.BinderProxy@20f0d1f4 time:93822
,W/BindingManager( 6056): Cannot call determinedVisibility() - never saw a connection for the pid: 6056
,W/ActivityManager(  860): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
,V/AlarmManager(  860): RTC_WAKEUP set : Alarm{2bdf89e8 type 0 when 1453712642066 com.android.providers.contacts} when 1453712642066
V/AlarmManager(  860): ELAPSED_WAKEUP set : Alarm{1ba29801 type 2 when 59933 com.google.android.talk} when 59933
V/AlarmManager(  860): RTC_WAKEUP set : Alarm{11175c94 type 0 when 1453885496629 com.android.vending} when 1453885496629
,D/Finsky  ( 5540): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
D/AlertService( 5890): Beginning updateAlertNotification
,D/AlertService( 5890): No fired or scheduled alerts
I/NotificationManager( 5890): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 5890): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 5890): com.android.calendar: cancel(2) by com.android.calendar
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 5890): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 5890): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5890): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 5890): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 5890): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 5890): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 5890): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 5890): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 5890): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 5890): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 5890): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 5890): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 5890): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 5890): com.android.calendar: cancel(16) by com.android.calendar
,I/NotificationManager( 5890): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5890): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 5890): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 5890): com.android.calendar: cancel(20) by com.android.calendar
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/JsMessageQueue( 6056): Set native->JS mode to OnlineEventsBridgeMode
,D/AlertService( 5890): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
I/NotificationManager(  860): android: cancelAsUser(2) by android
D/AlarmScheduler( 5890): No events found starting within 1 week.
,D/libc-netbsd( 5540): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5540): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5540): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5540): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  275): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 5540): propertyValue:false
D/libc-netbsd( 5540): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5540): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5540): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5540): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  860): Process com.android.contacts (pid 5753) has died
,D/jxcore_app_log( 6056): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622768128
,I/ActivityManager(  860): Process com.android.calendar (pid 5890) has died
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  860): android: cancelAsUser(2) by android
I/chromium( 6056): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/qtaguid ( 5540): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5540): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5540): untagSocket(41) failed with errno -22
D/Finsky  ( 5540): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/art     ( 6056): Background sticky concurrent mark sweep GC freed 22495(1793KB) AllocSpace objects, 4(60KB) LOS objects, 4% free, 11MB/11MB, paused 7.087ms total 54.581ms
I/art     ( 6056): CheckpointMarkThreadRoots callback created = 0x9f6ab5d0
,I/art     ( 6056): CheckpointMarkThreadRoots callback created = 0x9f6ab5a0
,I/ActivityManager(  860): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6141 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  860): android: cancelAsUser(2) by android
,W/ResourcesManager( 6141): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6141): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6141): VM with version 2.1.0 has multidex support
I/MultiDex( 6141): install
I/MultiDex( 6141): VM has multidex support, MultiDex support library is disabled.
,I/qtaguid ( 5540): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5540): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5540): untagSocket(41) failed with errno -22
V/JNIHelp ( 6141): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6141): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6141): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@221817cb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6141): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6141): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6141): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1731): callingUid 10006, callindPid: 1731
,D/ChimeraCfgMgr( 6141): Reading stored module config
D/AuthorizationBluetoothService( 1731): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 4199): Restart initialization of location
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
E/MDM     ( 1731): [120] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/ChimeraCfgMgr( 6141): Loading module com.google.android.gms.car from APK com.google.android.gms
,W/GCoreFlp( 1731): No location to return for getLastLocation()
W/FusedLocationProvider( 1731): location=null
,D/CAR.SERVICE( 6141): Connecting to CarCallService...
,I/art     ( 6141): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6141): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 6141): Install completed successfully. count=14 extracted=0
I/art     ( 5540): CheckpointMarkThreadRoots callback created = 0xaafa0140
,I/art     (  860): Explicit concurrent mark sweep GC freed 27346(1330KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.805ms total 195.398ms
D/CAR.SERVICE( 6141): com.google.android.projection.gearhead isn't installed.
,I/art     ( 5540): CheckpointMarkThreadRoots callback created = 0xaafa0100
,D/CAR.TEL.Service( 6141): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 6141): Creating a new PhoneAdapter instance
W/ActivityManager(  860): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6141): setListener: com.google.android.gms.car.dn@1183dd16
,W/ActivityManager(  860): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6141): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6141): Starting CarCallService with initial phone null
I/NotificationManager( 6141): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/art     ( 5521): Explicit concurrent mark sweep GC freed 8026(403KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 394us total 60.449ms
,D/CAR.SERVICE( 6141): Package validated; name: com.android.vending
,I/NotificationManager( 5540): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 5540): [1] GearheadStateMonitor.access$100: mIsProjecting:false
D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 96380636115; DSPS: 3249664; Offset : -2801608441
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  860): android: cancelAsUser(2) by android
,I/qtaguid ( 5540): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5540): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5540): untagSocket(41) failed with errno -22
,W/ResourcesManager( 5540): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5540): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5540): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 5540): [1] DailyHygiene.access$600: Logging device features
,W/jxcore-log( 6056): Initializing JXcore engine
W/jxcore-log( 6056): JXcore engine is ready
I/art     ( 6056): Background sticky concurrent mark sweep GC freed 47001(4MB) AllocSpace objects, 0(0B) LOS objects, 13% free, 22MB/26MB, paused 1.220ms total 104.809ms
,V/AlarmManager(  860): RTC_WAKEUP set : Alarm{45c53f9 type 0 when 1453885499619 com.android.vending} when 1453885499619
I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
,I/[SystemUI]Clock( 1373): called onTimeUpdated()
I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
,I/[SystemUI]DateView( 1373): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
D/DeviceConnectionService( 1731): client connected with version: 8296000
,D/Finsky  ( 5540): [689] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 5540): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 5540): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/NotificationManager(  860): android: cancelAsUser(2) by android
,W/Thread-751( 6139): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5811]" dev="sockfs" ino=5811 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-751( 6139): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-751( 6139): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8376]" dev="sockfs" ino=8376 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-751( 6139): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-751( 6139): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-751( 6139): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[28852]" dev="sockfs" ino=28852 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 6056): Starting JXcore engine
,D/libc-netbsd( 5540): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5540): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5540): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5540): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  275): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
,D/libc-netbsd(  275): res_queryN name = xxxxx succeed
,I/System.out( 5540): propertyValue:false
W/jxcore-log( 6056): Platform android
W/jxcore-log( 6056): 
,W/jxcore-log( 6056): Process ARCH arm
W/jxcore-log( 6056): 
D/PowerManagerServiceEx(  860): acquireWakeLockInternal: lock=523751443, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=860
,D/WeatherService( 2612): 2 : TimeTick Intent has been received, Time(hour:min:sec) 10:5:0
D/WeatherService( 2612): 2 : TimeTick Intent And Screen On
D/WeatherService( 2612): 2 : SDK version : 21
,W/ActivityManager(  860): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2612): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2612): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2612): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2612): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2612): 2 : This is isUpdating : false
D/WeatherService( 2612): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2612): 2 : buildUpdate, appWidgetId: 2
,D/WeatherTheme( 2612): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2612): 2 : Fixed theme : optimus
D/WeatherReflect( 2612): 2 : Map key string is -2
,D/lim     ( 2612): 2 : time = 10:05
I/WeatherReflect( 2612): Model Name : LG-D722
D/WeatherTheme( 2612): 2 : Different view - status_min_formatted : 04 != 05
D/WeatherTheme( 2612): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2612): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2612): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2612): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2612): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2612): currentPackage=com.lge.sizechangable.weather.theme.optimus
,D/Weather4x2_optimus( 2612): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2612): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2612): forecast size is 0
,D/Theme   ( 2612): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2612): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2612): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2612): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2612): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2612): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2612): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2612): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2612): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2612): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2612): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2612): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2612): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2612): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2612): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2612): url is : null
D/Theme   ( 2612): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2612): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2612): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2612): 2 : update view, appWidgetId: 2
I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
D/WeatherService( 2612): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 10:5:0
I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
D/PowerManagerServiceEx(  860): releaseWakeLockInternal: lock=523751443 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,V/AlarmManager(  860): RTC_WAKEUP set : Alarm{354d597 type 0 when 1453885500527 com.google.android.googlequicksearchbox} when 1453885500527
,I/jxcore-log( 6056): JXcore Cordova bridge is ready!
I/jxcore-log( 6056): 
W/jxcore-log( 6056): JXcore engine is started
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/jxcore-log( 6056): Toggling radios to true
I/jxcore-log( 6056): 
,D/BluetoothAdapter( 6056): enable(): BT is already enabled..!
D/WifiServiceImplEx(  860): setWifiEnabled: true pid=6056, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  860): setWifiEnabled: true pid=6056, uid=10316
D/WifiServiceImplEx(  860): disconnect pid=6056, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  860): reconnect pid=6056, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 6056): Radios toggled
I/jxcore-log( 6056): 
I/jxcore-log( 6056): My device name is: LGE-LG-D722
I/jxcore-log( 6056): 
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2807): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2807): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine(  860): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  860): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WfdsMonitor( 1803): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/LGWifiP2pService(  860): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  860): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  860): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  275): Clearing all IP addresses on wlan0
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 7
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
V/NativeCrypto( 1731): Read error: ssl=0xb045ae00: I/O error during system call, Connection timed out
D/libc-netbsd(  860): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  860): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1731): SSL shutdown failed: ssl=0xb045ae00: I/O error during system call, Broken pipe
D/libc-netbsd(  860): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  860): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  860): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  860): ignoring duplicate network state non-change
D/WifiHS20(  860): hidePasspointNotification off =false
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  860): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/libc-netbsd(  860): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  860): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  860): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-27 10:05:01.176 DNS addrs= 0.0.0.0, 0.0.0.0, 
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/ConnectivityService(  860): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  860): ValidatedState{ when=-3ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  860): DefaultState{ when=-11ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  860): Forcing reevaluation
,D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
I/ActivityManager(  860): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6224 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/WifiHS20(  860): hidePasspointNotification off =false
,W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine(  860): Start Disconnecting Watchdog 1
D/WifiOffDelayIfNotUsed(  860): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGWifiP2pService(  860): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  860): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2807): wlan0: CTRL-EVENT-SCAN-STARTED 
D/CommandListener(  275): Clearing all IP addresses on wlan0
,D/ConnectivityService(  860): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  860): disableDataServiceNotify
D/WifiHS20(  860): hidePasspointNotification off =false
D/DSQN    (  860): stop dsqn bin
W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  860): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-27 10:05:01.268 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-27 10:05:01.269 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  860): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/ConnectivityService(  860):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  860):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  860): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  860): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  860): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  860): Disconnected - quitting
D/Nat464Xlat(  860): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524292
D/CSLegacyTypeTracker(  860): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  860): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  860): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  860): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  860): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  860): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
W/QCNEJ   ( 1839): |CORE| No family connected
W/QCNEJ   ( 1839): |CORE| No family connected
I/QCNEJ   ( 1839): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/WifiNetworkAgent(  860): NetworkAgent: NetworkAgent channel lost
V/NetworkPolicy(  860): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy(  860): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService(  860): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  860): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/QCNEJ   ( 1839): |CORE| sendDefaultNwMsg: default = -1
D/Tethering(  860): MasterInitialState.processMessage what=3
D/Tethering(  860): MasterInitialState.processMessage what=3
D/TelephonyNetworkFactory-1( 1750): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService(  860): Removing idletimer
D/TelephonyNetworkFactory-1( 1750):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WifiHS20(  860): hidePasspointNotification off =false
,I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-27 10:05:01.311 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  860): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/Settings(  860): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  860): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-27 10:05:01.315 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiServerServiceExt(  860): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  860): setSupplicantStateDISCONNECTED
D/WIFI    (  860): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  860):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiServerServiceExt(  860): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  860): setSupplicantStateSCANNING
D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
D/DhcpStateMachine(  860): StoppedState
D/DhcpStateMachine(  860): StoppedState{ when=-84ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
W/ResourcesManager( 6224): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6224): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
W/ResourcesManager( 6224): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
,W/ResourcesManager( 6224): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6224): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/IndexDatabaseHelper( 6224): Using schema version: 115
,I/IndexDatabaseHelper( 6224): Index is fine
I/ActivityManager(  860): Process com.android.gallery3d (pid 5975) has died
,V/WiFiOffLoadBroadcast( 6224): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6224): MCCMNC not supported: null
I/ActivityManager(  860): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6248 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  860): Process com.lge.lockscreensettings (pid 5778) has died
,I/PCSuite ( 6248): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6248): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6248): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6224): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6224): MCCMNC not supported: null
I/PCSuite ( 6248): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6248): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6248): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6224): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6224): MCCMNC not supported: null
I/PCSuite ( 6248): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6248): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6248): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6224): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6224): MCCMNC not supported: null
I/PCSuite ( 6248): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6248): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6248): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6224): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6224): MCCMNC not supported: null
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2807): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/LocSvc_java(  860): onReceive
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-27 10:05:02.425 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  860): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  860): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-27 10:05:02.438 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/WifiServerServiceExt(  860): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  860): setSupplicantStateASSOCIATING
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2807): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiServerServiceExt(  860): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  860): setSupplicantStateASSOCIATED
V/WiFiOffLoadBroadcast( 6224): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 6224): Not supported operator for automatic switch
,V/WiFiOffLoadBroadcast( 6224): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6224): MCCMNC not supported: null
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-27 10:05:02.478 DNS addrs= 0.0.0.0, 0.0.0.0, 
,I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  860): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/wpa_supplicant( 2807): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2807): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-27 10:05:02.496 DNS addrs= 0.0.0.0, 0.0.0.0, 
W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
,D/WifiOffDelayIfNotUsed(  860): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt(  860): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  860): setSupplicantStateFOUR_WAY_HANDSHAKE
I/WifiServiceExtension(  860): setVHTCapabilityType  : false
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
,V/WiFiOffLoadBroadcast( 6224): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/WifiServerServiceExt(  860): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  860): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  860): setSecurityType  : 2
,D/WiFiOffLoadBroadcast( 6224): MCCMNC not supported: null
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-27 10:05:02.548 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  860): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  860): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-27 10:05:02.55 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
V/WiFiOffLoadBroadcast( 6224): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  860): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  860): Got NetworkAgent Messenger
D/ConnectivityService(  860): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  860): NetworkAgent connected
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
E/WifiConfigStore(  860): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/WiFiOffLoadBroadcast( 6224): MCCMNC not supported: null
E/WifiConfigStore(  860): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 9
,D/libc-netbsd(  860): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  860): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  860): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  860): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  275): Setting iface cfg
E/WifiStateMachine(  860): Start Dhcp Watchdog 2
V/WiFiOffLoadBroadcast( 6224): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/DhcpStateMachine(  860): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  860): WaitBeforeStartState
D/WifiServerServiceExt(  860): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  860): setSupplicantStateGROUP_HANDSHAKE
,D/ConnectivityService(  860): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/WiFiOffLoadBroadcast( 6224): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6224): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6224): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6224): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6224): MCCMNC not supported: null
,E/WifiStateMachine(  860): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  860): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  860): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@14824995 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  860): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@14824995 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper(  860): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  860): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  860): DHCP Start wake lock is acquired.
D/CommandListener(  275): Setting iface cfg
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  860): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  860): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  275): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  860): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  860): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  860): setSupplicantStateCOMPLETED
D/WifiServerServiceExt(  860): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  860): setSupplicantStateCOMPLETED
D/ConnectivityService(  860): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  860): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  860): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  860): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  860): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  860): ignoring duplicate network state non-change
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-27 10:05:02.708 DNS addrs= 192.168.1.1, 0.0.0.0, 
W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
D/WifiOffDelayIfNotUsed(  860): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
V/WiFiOffLoadBroadcast( 6224): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  860): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
D/ConnectivityService(  860): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-27 10:05:02.715 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
D/ConnectivityService(  860): Adding iface wlan0 to network 101
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiHS20(  860): [PASSPOINT] passpointNotification: hs20AP list is checked
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = true, mWifiLevel = 2
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-27 10:05:02.721 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
E/WifiStateMachine(  860): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  860): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  860): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-27 10:05:02.733 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  860): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WiFiOffLoadBroadcast( 6224): MCCMNC not supported: null
E/ConnectivityService(  860): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  860): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  860): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  275): netlink response contains error (File exists)
,D/ConnectivityService(  860): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  860): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  860): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  860): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  860): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  860): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  860): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  860): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  860): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  860): DefaultState{ when=-3ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  860): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  860): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  860): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  860):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  860):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  860):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  860):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  860):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  860): currentScore = 0, newScore = 20
D/ConnectivityService(  860):    accepting network in place of null
D/ConnectivityService(  860): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1750): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1750):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WIFI    (  860): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  860):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/ConnectivityService(  860): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  860): [LWD] Start DNSResolver start to wait
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = true, mWifiLevel = 2
D/CSLegacyTypeTracker(  860): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  860): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
D/Tethering(  860): MasterInitialState.processMessage what=3
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/ConnectivityService(  860): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
W/QCNEJ   ( 1839): |CORE| No family connected
I/QCNEJ   ( 1839): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/CSLegacyTypeTracker(  860): [e] list.add(nai) empty : false size: 1
I/QCNEJ   ( 1839): |CORE| sendDefaultNwMsg: default = 1
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  860): [LWD] wait 500ms before dns check
D/ConnectivityService(  860): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/ConnectivityService(  860): validation of new default Network = false
D/ConnectivityService(  860): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  860): enableDataServiceNotify 
D/DSQN    (  860): start dsqn bin
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
V/WiFiOffLoadBroadcast( 6224): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/NetworkPolicy(  860): [LG_RESTRICTED] checkMobilePolicy_type()
D/WiFiOffLoadBroadcast( 6224): MCCMNC not supported: null
,D/ConnectivityService(  860): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  860):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  860):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  860): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524290
I/DSQN    ( 6289): DSQN samuel.seo ver 141203
E/DSQN    ( 6289): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6289): created command queue thread
I/DSQN    ( 6289): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6289): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,V/WiFiOffLoadBroadcast( 6224): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
D/WiFiOffLoadBroadcast( 6224): MCCMNC not supported: null
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/PCSuite ( 6248): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6248): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6224): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6224): MCCMNC not supported: null
I/PCSuite ( 6248): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6248): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/DhcpStateMachine(  860): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper(  860): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  860): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/dhcpcd  ( 6292): version 5.5.6 starting
E/dhcpcd  ( 6292): get_duid: Read-only file system
,I/dhcpcd  ( 6292): wlan0: rebinding lease of 192.168.1.134
,I/ActivityManager(  860): Killing 5475:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,I/dhcpcd  ( 6292): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/dhcpcd  ( 6292): wlan0: leased 192.168.1.134 for 86400 seconds
,W/libprocessgroup(  860): failed to open /acct/uid_10086/pid_5475/cgroup.procs: No such file or directory
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  860): [LWD] DNSResolver start dns
D/libc-netbsd(  860): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  860): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  860): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  860): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  275): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  860): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  860): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  860): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  860): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  860): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  860): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  860): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  860): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  860): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  860): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  860): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  860): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  860): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  860): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  860): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  860): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  860): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  860): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  860): RunningState
,D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out(  860): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  860): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  860): Checking http://clients3.google.com/generate_204 on "NG700"
,D/libc-netbsd(  860): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  860): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/DSQN    ( 6289): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6289): restart monitoring
,D/LGDataListener(  275): argv[0]=dsqncommand
D/LGDataListener(  275): argv[1]=wlan0
D/LGDataListener(  275): argv[2]=1
D/LGDataListener(  275): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 6289): dsqn report finish
D/DSQN    (  860): DSQM DsqnNotification wlan0  1
D/DSQN    (  860): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  860): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 27 Jan 2016 09:05:03 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453885503350], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453885503333]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  860): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  860): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  860): Validated
,D/ConnectivityService(  860): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  860): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  860):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  860):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  860):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  860): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  860): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  860):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  860):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WifiDataContinuityService(  860): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
I/WifiServerServiceExt(  860): set CMD_CAPTIVE_CHECK_COMPLETED
D/ConnectivityService(  860): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  860): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  860): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  860): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  860):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1750): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1750):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
,D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/CAR.SERVICE( 6141): mConnectedToCar = false, abort
,E/ActivityThread( 6141): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2fd843e that was originally bound here
E/ActivityThread( 6141): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2fd843e that was originally bound here
E/ActivityThread( 6141): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6141): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6141): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6141): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6141): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6141): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6141): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6141): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6141): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6141): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6141): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6141): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6141): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6141): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6141): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6141): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6141): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6141): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6141): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6141): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6141): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6141): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6141): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6141): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2a571231 that was originally bound here
E/ActivityThread( 6141): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2a571231 that was originally bound here
E/ActivityThread( 6141): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6141): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6141): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6141): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6141): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6141): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6141): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6141): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6141): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6141): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6141): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6141): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6141): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6141): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6141): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6141): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6141): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6141): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6141): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6141): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6141): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6141): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  860): Unbind failed: could not find connection for android.os.BinderProxy@123275b4
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/ConnectivityService(  860): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/ConnectivityService(  860): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  860): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  860): onReceive
D/LocSvc_java(  860): got connectivity action
,D/LocSvc_java(  860): broadcast - no network connections
D/LocSvc_java(  860): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  860): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  860): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  860): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  860): ignore wifi update if we are not in OPENING or CLOSING
,I/ActivityManager(  860): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6336 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/GpsLocationProvider(  860): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java(  860): onReceive
D/LocSvc_java(  860): got connectivity action
D/LocSvc_java(  860): broadcast - no network connections
D/LocSvc_java(  860): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  860): Sending msg: 4 arg1:0 arg2:1
,D/LocSvc_java(  860): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  860): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  860): ignore wifi update if we are not in OPENING or CLOSING
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  860): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  860): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  860): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  860): identical MTU - not setting
D/Nat464Xlat(  860): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  860): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  860):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  860):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  860): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  860): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  860): enableDataServiceNotify 
,D/DSQN    (  860): start dsqn bin
,I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524295
I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-27 10:05:04.409 DNS addrs= 192.168.1.1, 0.0.0.0, 
,D/DSQN    (  860): dsqn is running restart
D/GpsLocationProvider(  860): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/DSQN    ( 6363): DSQN samuel.seo ver 141203
E/DSQN    ( 6363): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6363): created command queue thread
I/DSQN    ( 6363): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6363): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,D/GpsLocationProvider(  860): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider(  860): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager(  860): Process com.google.android.gms:car (pid 6141) has died
,I/MusicStore( 6336): Database version: 120
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6336): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6336): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6336): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,W/ResourcesManager( 6336): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6336): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6336): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6336): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6336): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@bbb8a52: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6336): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6336): GMSCore installation verified
I/ActivityManager(  860): Process com.android.providers.calendar (pid 6012) has died
,I/ConfigStore( 6336): Config Database version: 1
,I/ActivityManager(  860): Process com.google.android.talk (pid 5654) has died
,I/MediaRouter( 6336): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6336): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6336): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6336): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  860): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6388 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/rmt_storage(  271): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  271): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  271): wakelock acquired: 1, error no: 42
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-61 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-27 10:05:05.627 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  271): 
I/rmt_storage(  271): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
,V/WifiInternetCheck(  860): Single check msg out of sync, ignoring.
I/GHttpClientFactory( 6336): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 6336): Using platform SSLCertificateSocketFactory
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/ConnectivityService(  860): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  860): onReceive
D/LocSvc_java(  860): got connectivity action
D/LocSvc_java(  860): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  860): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  860): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  860): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  860): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  860): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/ResourcesManager( 6388): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6388): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/GpsLocationProvider(  860): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ResourcesManager( 6388): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  860): Process com.android.vending (pid 5540) has died
,D/UEI.SmartControl( 5626): Service.onTrimMemory: 80
,E/UEI.SmartControl( 5626): Setup service releasing memory...
I/PhoneApp( 1750): onTrimMemory: 10
I/PhoneApp( 1750): trim memory
I/NetworkMonitor( 6336): type=WIFI subType= reason=null isConnected=true
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/NotificationManager( 6336): com.google.android.music: cancel(1061) by com.google.android.music
I/art     ( 5626): Explicit concurrent mark sweep GC freed 160(17KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 376us total 56.183ms
I/NotificationManager( 1939): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/LGEmail ( 6388): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6388): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6388): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  860): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6423 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6388): JNI_OnLoad()
I/HubEmail( 6388): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6388): registerNatives()
I/HubEmail( 6388): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6388): registerNativeMethods()
I/HubEmail( 6388): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6388): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6388): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 6423): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6423): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6423): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6423): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,D/LGDMClient( 6423): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6423): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6423): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6423): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  860): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6450 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6423): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6423): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6423): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6423): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6423): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6423): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/AppUp4:AppBoxCP( 6450): onCreate
,W/AppUp4:DB( 6450):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6450):  setFingerPrint start
I/AppUp4:DB( 6450):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6450):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6450):  SDK version = 0
I/AppUp4:DB( 6450):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6450): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6450): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6450): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6450): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6450): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6450): onReceive
I/AppUp4:CustModeStarterReceiver( 6450): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 6450): Context : android.app.ReceiverRestrictedContext@430ea56
D/AppUp4:CustFacade( 6450): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6450): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6450): begin check event
I/AppUp4:CustModeStarterReceiver( 6450): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6450): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6450): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6450): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6450): handleAsyncCustNotification do not startCustService
,I/LgeMiscReceiver( 3231): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3231): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3231): networkInfo.isConnected() = false
,D/libc-netbsd(  860): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  860): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  860): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  860): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  275): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
,I/ActivityManager(  860): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6470 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
,I/System.out(  860): propertyValue:false
I/art     (  308): Explicit concurrent mark sweep GC freed 705(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.205ms total 23.762ms
D/libc-netbsd(  860): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  860): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  860): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  860): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  275): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out(  860): propertyValue:false
,I/art     (  308): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 4.347ms total 25.797ms
,I/DSQN    ( 6363): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6363): restart monitoring
I/DSQN    ( 6363): dsqn report finish
D/LGDataListener(  275): argv[0]=dsqncommand
D/LGDataListener(  275): argv[1]=wlan0
D/LGDataListener(  275): argv[2]=1
D/LGDataListener(  275): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  860): DSQM DsqnNotification wlan0  1
D/DSQN    (  860): start to monitor internet connection
V/WifiInternetCheck(  860): isHttpConnectionAvailable - We got a valid response : 204
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 307us total 21.483ms
D/PhoneMonitor( 6470): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6470): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6470): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  860): Killing 6224:com.android.settings/1000 (adj 15): empty #11
,D/PhoneMonitor( 6470): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
W/libprocessgroup(  860): failed to open /acct/uid_1000/pid_6224/cgroup.procs: No such file or directory
,V/TelephonyAutoProfiling( 6470): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6470): [parse] Load xml
V/DownloadManager( 3213): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,I/CheckinService( 4199): Checkin interval check for package: unspecified last checkin: 1453885482343 min interval config: 0 actual interval: 24946
V/DownloadManager( 3213): DownloadService onCreate
,I/ActivityManager(  860): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6497 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/NotificationManager( 3213): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3213): in removeSpuriousFiles
,V/DownloadManager( 3213): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/TelephonyAutoProfiling( 6470): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6470): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
V/DownloadManager( 3213): created cursor android.database.sqlite.SQLiteCursor@361aeb45 on behalf of 3213
D/PhoneMonitor( 6470): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/DownloadManager( 3213): in trimDatabase
V/DownloadManager( 3213): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3213): created cursor android.database.sqlite.SQLiteCursor@3983629a on behalf of 3213
V/DownloadManager( 3213): DownloadService onStartCommand
V/DownloadManager( 3213): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/CheckinService( 4199): Checking schedule, now: 1453885507414 next: 1453885512276
I/CheckinService( 4199): active receiver: disabled
V/DownloadManager( 3213): created cursor android.database.sqlite.SQLiteCursor@3283f6c1 on behalf of 3213
I/ActivityManager(  860): Killing 5626:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 4973): android.os.DeadObjectException
,W/System.err( 4973): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 4973): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 4973): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 4973): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 4973): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 4973): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 4973): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4973): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4973): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4973): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 4973): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4973): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4973): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 4973): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 4973): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 4973): android.os.DeadObjectException
W/System.err( 4973): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 4973): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 4973): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 4973): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 4973): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 4973): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 4973): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4973): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4973): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4973): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 4973): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4973): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4973): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 4973): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 4973): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  860): failed to open /acct/uid_10089/pid_5626/cgroup.procs: No such file or directory
W/ActivityManager(  860): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,V/DownloadManager( 3213): DownloadService onDestroy
D/WeatherAncestor( 2612): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:5:7
,I/ActivityManager(  860): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6534 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UpdateThreadPoolManager( 2612): 2 : This is isUpdating : false
D/WeatherAncestor( 2612): connectivity changed - connection : true
D/Weather_cast( 2612): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2612): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:5:7
D/WeatherService( 2612): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  860): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6559 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  860): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2612): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2612): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2612): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/UEI.SmartControl( 6534): Quickset Services start...
I/UEI.SmartControl( 6534): Manufacture = LGE
,D/UEI.SmartControl( 6534): File observer start...
E/UEI.SmartControl( 6534): IR Port is disabled: false
,D/UEI.SmartControl( 6534): Starting file observer...
D/UEI.SmartControl( 6534): Extracting JNI libs...
D/UEI.SmartControl( 6534): --- this system supports 32-bit or 64-bit only
W/ResourcesManager( 6559): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/SQLiteConnectionPool( 4199): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/UEI.SmartControl( 6534): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6534): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6534): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 6534): --- Selecting new region: 2
I/UEI.SmartControl( 6534): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6534): Platform has CIR...
D/UEI.SmartControl( 6534): NO CIR support, need to check package...
I/UEI.SmartControl( 6534): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6534): QS Service created
E/UEI.SmartControl( 6534): QS start get config
,I/Babel_SMS( 6559): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6559): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6559): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6559): MmsConfig.loadFromDatabase
D/UEI.SmartControl( 6534): Loading JNI Libs...
,D/UEI.SmartControl( 6534):  configuring local db...
,E/Babel_SMS( 6559): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6559): MmsConfig.loadFromResources
E/Babel_SMS( 6559): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6559): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/art     ( 6559): CheckpointMarkThreadRoots callback created = 0xb042d840
,I/art     ( 6559): CheckpointMarkThreadRoots callback created = 0xb042d830
,D/SensorManager( 6559): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6559): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6559): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
,D/SensorManager( 6559): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6559): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6559): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6559): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6559): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6559): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6559): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6559): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6559): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6559): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6559): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6559): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6559): found sensor: Motion Accel, handle=46
I/ActivityManager(  860): Process com.google.android.music:main (pid 6336) has died
,W/Settings( 6559): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6559): startup - clean
I/Babel   ( 6559): deleted: false for 0
,D/UEI.SmartControl( 6534):  ---- Has DB8: true
,D/UEI.SmartControl( 6534): QS start statue = true Error code = 0
D/UEI.SmartControl( 6534): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6534): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6534): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6534): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6534): IrrcClient ++ 
D/irrcClient( 6534): getIrrcService ++ 
D/irrcClient( 6534): getIrrcService -- 
D/irrcClient( 6534): IrrcClient -- 
W/irrc_jni( 6534): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 6534): Services init done
I/UEI.SmartControl( 6534): Device manager: loading config....
D/UEI.SmartControl( 6534): Config is loaded...
D/UEI.SmartControl( 6534):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6534): Notify AllClients services are ready: 0
,I/art     (  860): Explicit concurrent mark sweep GC freed 84599(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.712ms total 202.212ms
,D/UEI.SmartControl( 6534): QS Service init finished
,D/UEI.SmartControl( 6534): QS Service version name: 0.1.73
D/UEI.SmartControl( 6534): QS Service version code: 1073
D/UEI.SmartControl( 6534): Service requested: Control
I/ActivityManager(  860): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6594 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 6534): Internal service binding...
,D/UEI.SmartControl( 6534): -----IControl: 11
D/UEI.SmartControl( 6534): Caller: com.lge.qremote
D/UEI.SmartControl( 6534): ------------ IControl registerCallback...
I/UEI.SmartControl( 6534): Registering callback...
D/UEI.SmartControl( 6534): -----IControl: 19
D/UEI.SmartControl( 6534): Caller: com.lge.qremote
I/UEI.SmartControl( 6534): Registering Services Ready callback...
W/AudioCapabilities( 6559): Unsupported mime audio/x-lg-flac
I/UEI.SmartControl( 6534): Notify client services are ready...
W/AudioCapabilities( 6559): Unsupported mime audio/adpcm
,W/AudioCapabilities( 6559): Unsupported mime audio/g726
W/AudioCapabilities( 6559): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6559): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6559): Unsupported mime video/mjpg
D/UEI.SmartControl( 6534): -----IControl: 8
D/UEI.SmartControl( 6534): Caller: com.lge.qremote
W/VideoCapabilities( 6559): Unsupported mime video/theora
,W/AudioCapabilities( 6559): Unsupported mime audio/evrc
W/AudioCapabilities( 6559): Unsupported mime audio/qcelp
W/VideoCapabilities( 6559): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6559): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6559): Unsupported mime audio/qcelp
W/AudioCapabilities( 6559): Unsupported mime audio/evrc
I/jxcore-log( 6056): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6056): 
,W/VideoCapabilities( 6559): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 6559): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6559): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6559): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6559): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6559): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6559): onServiceConnected
,W/Babel   ( 6559): Attempted to change video mute state without an active call.
I/NotificationManager( 6559): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6559): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6559): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6559): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6559): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  275): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 6559): propertyValue:false
,I/Babel   ( 6559): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  860): Killing 6248:com.lge.sync/1000 (adj 15): empty #11
W/libprocessgroup(  860): failed to open /acct/uid_1000/pid_6248/cgroup.procs: No such file or directory
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6594): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6594): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6594): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/GAv4    ( 6594): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6594):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6594):   adb logcat -s GAv4
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6594): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 6594): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6594): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6594): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
V/AlarmManager(  860): ELAPSED_WAKEUP set : Alarm{127ead96 type 2 when 106926 com.google.android.gms} when 106926
I/WebViewFactory( 6594): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6594): Time to load native libraries: 2 ms (timestamps 7311-7313)
,I/LibraryLoader( 6594): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6594): Binding Chromium to main looper Looper (main, tid 1) {264289bb}
I/LibraryLoader( 6594): Expected native library version number "",actual native library version number ""
I/chromium( 6594): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6594): Initializing chromium process, singleProcess=true
,W/art     ( 6594): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6594): ApplicationContext is null in ApplicationStatus
W/chromium( 6594): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6594): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6594): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6594): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6594): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6594): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6594): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6594): Remote Branch: 
I/Adreno-EGL( 6594): Local Patches: 
I/Adreno-EGL( 6594): Reconstruct Branch: 
V/AudioPolicyService(  282): registerClient() client 0xb40271a0, uid 10079
,W/AudioManagerAndroid( 6594): Requires BLUETOOTH permission
I/NSApplication( 6594): Starting up...
I/ActivityManager(  860): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6659 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  860): Killing 4973:com.lge.qremote/u0a106 (adj 15): empty #11
,I/jxcore-log( 6056): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6056): 
,W/libprocessgroup(  860): failed to open /acct/uid_10106/pid_4973/cgroup.procs: No such file or directory
,I/jxcore-log( 6056): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6056): 
,I/jxcore-log( 6056): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6056): 
I/jxcore-log( 6056): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6056): 
,I/ActivityManager(  860): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6678 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/jxcore-log( 6056): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6056): 
I/ActivityManager(  860): Killing 6388:com.lge.email/u0a21 (adj 15): empty #11
,I/jxcore-log( 6056): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6056): 
I/jxcore-log( 6056): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6056): 
,W/libprocessgroup(  860): failed to open /acct/uid_10021/pid_6388/cgroup.procs: No such file or directory
,W/ResourcesManager( 6678): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
V/AlarmManager(  860): RTC_WAKEUP set : Alarm{3c4715b8 type 0 when 1453885510862 com.google.android.googlequicksearchbox} when 1453885510862
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  860): Killing 6423:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  860): failed to open /acct/uid_1000/pid_6423/cgroup.procs: No such file or directory
,I/ActivityManager(  860): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6706 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 6706): Database version: 120
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6706): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6706): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6706): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/ResourcesManager( 6706): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6706): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6706): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6706): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6706): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@bbb8a52: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6706): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6706): GMSCore installation verified
I/ConfigStore( 6706): Config Database version: 1
,I/MediaRouter( 6706): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6706): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6706): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6706): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  860): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6753 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6706): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6706): Using platform SSLCertificateSocketFactory
I/ActivityManager(  860): Killing 6450:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/ResourcesManager( 6753): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6753): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6753): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  860): failed to open /acct/uid_10011/pid_6450/cgroup.procs: No such file or directory
,I/NotificationManager( 6706): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6753): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6753): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6753): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  860): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6788 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/HubEmail( 6753): JNI_OnLoad()
I/HubEmail( 6753): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/HubEmail( 6753): registerNatives()
I/HubEmail( 6753): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6753): registerNativeMethods()
I/HubEmail( 6753): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6753): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  860): Killing 6470:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  860): failed to open /acct/uid_10038/pid_6470/cgroup.procs: No such file or directory
I/ActivityManager(  860): Process com.google.android.talk (pid 6559) has died
,W/Settings( 6753): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 6788): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6788): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6788): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6788): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6788): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6788): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager(  860): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6821 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/LGDMClient( 6788): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6788): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 6788): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 6788): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6788): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6788): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6788): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6788): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/AppUp4:AppBoxCP( 6821): onCreate
W/AppUp4:DB( 6821):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6821):  setFingerPrint start
I/AppUp4:DB( 6821):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6821):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6821):  SDK version = 0
I/AppUp4:DB( 6821):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6821): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6821): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6821): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6821): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6821): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 6821): onReceive
I/AppUp4:CustModeStarterReceiver( 6821): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6821): Context : android.app.ReceiverRestrictedContext@430ea56
D/AppUp4:CustFacade( 6821): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6821): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6821): begin check event
I/AppUp4:CustModeStarterReceiver( 6821): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6821): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6821): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6821): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6821): handleAsyncCustNotification do not startCustService
I/ActivityManager(  860): Killing 6497:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  860): failed to open /acct/uid_10051/pid_6497/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3231): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3231): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3231): networkInfo.isConnected() = false
,I/ActivityManager(  860): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6846 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 21.662ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 325us total 20.135ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 20.493ms
,D/PhoneMonitor( 6846): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6846): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6846): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  860): Killing 6534:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/libprocessgroup(  860): failed to open /acct/uid_10089/pid_6534/cgroup.procs: No such file or directory
,V/DownloadManager( 3213): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3213): DownloadService onCreate
I/DownloadManager( 3213): in removeSpuriousFiles
I/NotificationManager( 3213): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3213): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3213): created cursor android.database.sqlite.SQLiteCursor@3c45a54 on behalf of 3213
I/DownloadManager( 3213): in trimDatabase
V/DownloadManager( 3213): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3213): created cursor android.database.sqlite.SQLiteCursor@1f183dfd on behalf of 3213
,D/PhoneMonitor( 6846): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6846): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6846): [parse] Load xml
,I/ActivityManager(  860): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6869 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/TelephonyAutoProfiling( 6846): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6846): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
V/DownloadManager( 3213): DownloadService onStartCommand
V/DownloadManager( 3213): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/CheckinService( 4199): Checkin interval check for package: unspecified last checkin: 1453885482343 min interval config: 0 actual interval: 31510
V/DownloadManager( 3213): created cursor android.database.sqlite.SQLiteCursor@1e31b543 on behalf of 3213
,V/AlarmManager(  860): RTC_WAKEUP set : Alarm{105ea3a7 type 0 when 1453885512276 com.google.android.gms} when 1453885512276
,D/PhoneMonitor( 6846): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/ActivityManager(  860): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6891 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  860): RTC_WAKEUP set : Alarm{852c054 type 0 when 1453885513873 com.android.vending} when 1453885513873
,V/DownloadManager( 3213): DownloadService onDestroy
,I/CheckinService( 4199): Checking schedule, now: 1453885514041 next: 1453885512276
I/CheckinService( 4199): active receiver: enabled
,I/CheckinService( 4199): Preparing to send checkin request
I/EventLogService( 4199): Accumulating logs since 1453885473580
,D/WeatherAncestor( 2612): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:5:14
,D/UpdateThreadPoolManager( 2612): 2 : This is isUpdating : false
D/WeatherAncestor( 2612): connectivity changed - connection : true
D/Weather_cast( 2612): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2612): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:5:14
D/WeatherService( 2612): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/CheckinRequestBuilder( 4199): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  860): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6911 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  860): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2612): 2 : Utils getTopActivity com.lge.launcher2 / true
,E/ActivityThread( 4199): Failed to find provider info for com.google.android.wearable.settings
D/WeatherService( 2612): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2612): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6911): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/Finsky  ( 6891): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/art     (  860): Explicit concurrent mark sweep GC freed 23444(1255KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.975ms total 159.514ms
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel_SMS( 6911): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6911): MmsConfig.loadMmsSettings
I/Babel_SMS( 6911): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6911): MmsConfig.loadFromDatabase
D/Finsky  ( 6891): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,E/Babel_SMS( 6911): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6911): MmsConfig.loadFromResources
E/Babel_SMS( 6911): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6911): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,W/Settings( 6891): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6891): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6891): com.android.vending: cancel(-1050172287) by com.android.vending
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  860): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6957 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/Ads     ( 6891): Skipping gmscore version check
D/Finsky  ( 6891): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6891): [1] Libraries$2.run: Finished loading 1 libraries.
V/DownloadManager( 3213): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3213): created cursor android.database.sqlite.SQLiteCursor@17afbcf9 on behalf of 6891
I/art     ( 6911): CheckpointMarkThreadRoots callback created = 0xb042d8f0
,D/SensorManager( 6911): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6911): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6911): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6911): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6911): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6911): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6911): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6911): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6911): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6911): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6911): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6911): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6911): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6911): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6911): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6911): found sensor: Motion Accel, handle=46
W/ResourcesManager( 6957): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6957): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Finsky  ( 6891): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/Settings( 6911): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6911): startup - clean
,I/art     ( 6911): CheckpointMarkThreadRoots callback created = 0xb042d8e0
W/art     ( 6911): Suspending all threads took: 10.111ms
,D/Finsky  ( 6891): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Babel   ( 6911): deleted: false for 0
,I/MultiDex( 6957): VM with version 2.1.0 has multidex support
I/MultiDex( 6957): install
,I/MultiDex( 6957): VM has multidex support, MultiDex support library is disabled.
D/Finsky  ( 6891): [855] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,I/ActivityManager(  860): Process com.google.android.apps.magazines (pid 6594) has died
,D/Finsky  ( 6891): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
V/JNIHelp ( 6957): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  860): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6981 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityThread( 6957): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6957): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@221817cb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6957): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 6957): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 6957): com.google.android.gms: cancel(39789) by com.google.android.gms
W/AudioCapabilities( 6911): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6911): Unsupported mime audio/adpcm
,W/AudioCapabilities( 6911): Unsupported mime audio/g726
W/AudioCapabilities( 6911): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6911): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6911): Unsupported mime video/mjpg
W/VideoCapabilities( 6911): Unsupported mime video/theora
,W/AudioCapabilities( 6911): Unsupported mime audio/evrc
,W/AudioCapabilities( 6911): Unsupported mime audio/qcelp
W/VideoCapabilities( 6911): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6911): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6911): Unsupported mime audio/qcelp
W/AudioCapabilities( 6911): Unsupported mime audio/evrc
I/art     ( 6957): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6957): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/VideoCapabilities( 6911): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6911): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6911): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6911): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6911): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6911): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6911): onServiceConnected
W/Babel   ( 6911): Attempted to change video mute state without an active call.
,I/NotificationManager( 6911): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6911): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6911): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6911): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6911): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  275): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 6911): propertyValue:false
,D/NativeLibraryUtils( 6957): Install completed successfully. count=14 extracted=0
,I/Babel   ( 6911): connection state changed from UNKNOWN to CONNECTED
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  860): Process com.google.android.music:main (pid 6706) has died
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6981): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6981): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6981): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6981):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6981):   adb logcat -s GAv4
,D/WVCdm   (  282): Instantiating CDM.
I/WVCdm   (  282): CdmEngine::OpenSession
I/WVCdm   (  282): Level3 Library Dec 11 2014 16:13:16
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6981): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
W/GAv4    ( 6981): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6981): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/WVCdm   (  282): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  282): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  282): L1 library not specified. Falling Back to L3
,W/GAv4    ( 6981): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,W/GAv4    ( 6981): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WVCdm   (  282): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  282): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  282): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  282): CdmEngine::GenerateKeyRequest
D/WVCdm   (  282): PrepareKeyRequest: nonce=3032675939
I/WebViewFactory( 6981): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6981): Time to load native libraries: 2 ms (timestamps 3750-3752)
I/LibraryLoader( 6981): Expected native library version number "",actual native library version number ""
,I/art     ( 6957): CheckpointMarkThreadRoots callback created = 0xb04cbe60
V/WebViewChromiumFactoryProvider( 6981): Binding Chromium to main looper Looper (main, tid 1) {264289bb}
I/LibraryLoader( 6981): Expected native library version number "",actual native library version number ""
I/chromium( 6981): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6981): Initializing chromium process, singleProcess=true
W/art     ( 6981): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6981): ApplicationContext is null in ApplicationStatus
I/art     ( 6957): CheckpointMarkThreadRoots callback created = 0xb04cbe50
W/chromium( 6981): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6981): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6981): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6981): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6981): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6981): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6981): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6981): Remote Branch: 
I/Adreno-EGL( 6981): Local Patches: 
I/Adreno-EGL( 6981): Reconstruct Branch: 
,V/AudioPolicyService(  282): registerClient() client 0xb40271a0, uid 10079
,I/NSApplication( 6981): Starting up...
W/AudioManagerAndroid( 6981): Requires BLUETOOTH permission
,I/ActivityManager(  860): Killing 6753:com.lge.email/u0a21 (adj 15): empty #11
,I/dex2oat ( 7043): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/libprocessgroup(  860): failed to open /acct/uid_10021/pid_6753/cgroup.procs: No such file or directory
,I/dex2oat ( 7043): dex2oat took 95.276ms (threads: 4)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/Adreno-EGL( 6957): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6957): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6957): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6957): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6957): Remote Branch: 
I/Adreno-EGL( 6957): Local Patches: 
I/Adreno-EGL( 6957): Reconstruct Branch: 
I/ActivityManager(  860): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7049 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Adreno-EGL( 6957): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6957): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6957): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6957): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6957): Remote Branch: 
I/Adreno-EGL( 6957): Local Patches: 
I/Adreno-EGL( 6957): Reconstruct Branch: 
,I/Adreno-EGL( 6957): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6957): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6957): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6957): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6957): Remote Branch: 
I/Adreno-EGL( 6957): Local Patches: 
I/Adreno-EGL( 6957): Reconstruct Branch: 
,I/MusicStore( 7049): Database version: 120
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7049): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/WVCdm   (  282): CdmEngine::OpenSession
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7049): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7049): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7049): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7049): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7049): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7049): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7049): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@bbb8a52: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7049): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 7049): GMSCore installation verified
I/ConfigStore( 7049): Config Database version: 1
,I/art     ( 5521): Explicit concurrent mark sweep GC freed 1732(63KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 398us total 33.243ms
,I/MediaRouter( 7049): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7049): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7049): type=WIFI subType= reason=null isConnected=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/NetworkMonitor( 7049): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  860): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7082 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7049): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7049): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  860): Killing 6788:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/ResourcesManager( 7082): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7082): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7082): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/WVCdm   (  282): CdmEngine::CloseSession
,W/libprocessgroup(  860): failed to open /acct/uid_1000/pid_6788/cgroup.procs: No such file or directory
,I/NotificationManager( 7049): com.google.android.music: cancel(1061) by com.google.android.music
I/WVCdm   (  282): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  282): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  282): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  282): CdmEngine::GenerateKeyRequest
D/WVCdm   (  282): PrepareKeyRequest: nonce=3797229329
I/LGEmail ( 7082): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 7082): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7082): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  860): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7109 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/HubEmail( 7082): JNI_OnLoad()
I/HubEmail( 7082): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7082): registerNatives()
I/HubEmail( 7082): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7082): registerNativeMethods()
I/HubEmail( 7082): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7082): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  860): Killing 6821:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  860): failed to open /acct/uid_10011/pid_6821/cgroup.procs: No such file or directory
W/Settings( 7082): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 7109): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7109): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7109): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 7109): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/LGDMClient( 7109): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7109): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager(  860): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7136 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/LGDMClient( 7109): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 7109): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 7109): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 7109): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7109): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
,D/LGDMClient( 7109): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7109): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7109): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  860): Killing 6846:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/AppUp4:AppBoxCP( 7136): onCreate
,W/AppUp4:DB( 7136):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7136):  setFingerPrint start
I/AppUp4:DB( 7136):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7136):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7136):  SDK version = 0
I/AppUp4:DB( 7136):  beforefinger == newfinger no write in DB
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time(  860): tsOffsetIs: Apps: 116381378764; DSPS: 3905049; Offset : -2801628758
I/MusicWidget( 2566): mDelayedStopHandler : unbind
,W/libprocessgroup(  860): failed to open /acct/uid_10038/pid_6846/cgroup.procs: No such file or directory
,D/AppUp4:AppBoxApplication( 7136): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7136): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7136): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7136): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7136): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7136): onReceive
I/AppUp4:CustModeStarterReceiver( 7136): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7136): Context : android.app.ReceiverRestrictedContext@430ea56
,D/AppUp4:CustFacade( 7136): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7136): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7136): begin check event
I/AppUp4:CustModeStarterReceiver( 7136): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7136): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7136): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7136): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7136): handleAsyncCustNotification do not startCustService
I/ActivityManager(  860): Killing 6869:com.lge.drmservice/u0a51 (adj 15): empty #11
,I/MusicBrowser( 2618): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2618): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2618): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2618): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2618): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2618): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
W/libprocessgroup(  860): failed to open /acct/uid_10051/pid_6869/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3231): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3231): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3231): networkInfo.isConnected() = true
D/PhoneState( 3231): setPdpRejectCasuse : false
I/ActivityManager(  860): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7158 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/MusicBrowser( 2618): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2618): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  860):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@20f0d1f4com.lge.music.MediaPlaybackService$6@3d39ed1d
,D/MusicBrowser( 2618): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2618): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/jxcore-log( 6056): Test app app.js loaded
I/jxcore-log( 6056): 
I/MusicBrowser( 2618): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2618): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2618): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@13e955e2
I/MusicBrowser( 2618): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2618): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2618): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6056): setDiscoveryMode: Mode set to BLE
I/jxcore-log( 6056): BLE advertisement is supported
I/jxcore-log( 6056): 
I/MusicBrowser( 2618): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2618): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2618): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2618): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2618): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2618): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2618): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2618): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2618): [MediaPlaybackService.java:6745:release()] oooooo 
,I/MusicBrowser( 2618): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2618): reset
V/MediaPlayer[Native]( 2618): setListener
V/MediaPlayer[Native]( 2618): disconnect
V/MediaPlayer[Native]( 2618): destructor
,V/AudioFlinger(  282): releasing 19 from 2618 for -1
V/AudioFlinger(  282):  decremented refcount to 0
V/AudioFlinger(  282): purging stale effects
V/MediaPlayer[Native]( 2618): disconnect
D/MusicBrowser( 2618): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/chromium( 6056): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/SmartShareClient( 2618): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2618): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2618): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2618): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2618): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2618): [SmartShareManagerClient] unregisterListener: 962001810
W/SmartShareClient( 2618): [SmartShareManagerClient] unregisterListener invalid listener: 962001810
I/SmartShareClient( 2618): [SmartShareManagerClient] terminate service: 2618/MediaPlaybackService/374622744
E/HomeCloudIF( 2618): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2618): [SmartShareManagerClient] unbindService context:android.app.Application@f9bc963
,V/CloudHub( 2618): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2618): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2618): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
,I/MusicBrowser( 2618): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2618): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
,I/ActivityManager(  860): Killing 6891:com.android.vending/u0a36 (adj 15): empty #11
I/CloudHub( 2618): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29974
,D/PhoneMonitor( 7158): Register our PhoneStateListener
,W/libprocessgroup(  860): failed to open /acct/uid_10036/pid_6891/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7158): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7158): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  860): Killing 6911:com.google.android.talk/u0a61 (adj 15): empty #11
D/PhoneMonitor( 7158): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7158): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 7158): [parse] Load xml
V/TelephonyAutoProfiling( 7158): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7158): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 7158): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  860): failed to open /acct/uid_10061/pid_6911/cgroup.procs: No such file or directory
,V/DownloadManager( 3213): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3213): DownloadService onCreate
I/DownloadManager( 3213): in removeSpuriousFiles
I/NotificationManager( 3213): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3213): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3213): created cursor android.database.sqlite.SQLiteCursor@a30629f on behalf of 3213
I/DownloadManager( 3213): in trimDatabase
V/DownloadManager( 3213): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/ActivityManager(  860): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7180 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3213): DownloadService onStartCommand
I/art     (  308): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 22.783ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 20.227ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 20.218ms
,V/DownloadManager( 3213): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/art     (  860): Explicit concurrent mark sweep GC freed 23026(1043KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 1.848ms total 184.705ms
,V/DownloadManager( 3213): created cursor android.database.sqlite.SQLiteCursor@3a62fb5 on behalf of 3213
V/DownloadManager( 3213): created cursor android.database.sqlite.SQLiteCursor@b49a64a on behalf of 3213
I/CheckinService( 4199): Checkin interval check for package: unspecified last checkin: 1453885482343 min interval config: 0 actual interval: 37563
I/ActivityManager(  860): Killing 6981:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,E/libprocessgroup(  860): failed to kill 1 processes for processgroup 6981
,D/WeatherAncestor( 2612): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:5:20
I/WVCdm   (  282): CdmEngine::CloseSession
,I/WVCdm   (  282): L3 Terminate.
I/CheckinRequestBuilder( 4199): Classify the device as Phone.
,V/DownloadManager( 3213): DownloadService onDestroy
D/UpdateThreadPoolManager( 2612): 2 : This is isUpdating : false
D/WeatherAncestor( 2612): connectivity changed - connection : true
D/Weather_cast( 2612): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2612): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 10:5:20
D/WeatherService( 2612): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
W/ActivityManager(  860): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2612): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2612): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2612): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/ActivityManager(  860): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7206 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/libc-netbsd( 4199): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4199): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4199): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4199): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
W/ResourcesManager( 7206): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 4199): propertyValue:false
,D/libc-netbsd( 4199): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4199): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4199): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4199): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4199): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4199): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 4199): Sending checkin request (9726 bytes)
,I/Babel_SMS( 7206): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7206): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7206): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7206): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7206): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7206): MmsConfig.loadFromResources
E/Babel_SMS( 7206): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7206): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-27 10:05:20.683 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/art     ( 7206): CheckpointMarkThreadRoots callback created = 0xb042d440
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/SensorManager( 7206): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7206): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7206): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7206): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7206): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7206): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7206): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7206): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7206): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7206): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7206): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7206): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7206): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7206): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7206): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7206): found sensor: Motion Accel, handle=46
I/art     ( 7206): CheckpointMarkThreadRoots callback created = 0xb042d430
,W/Settings( 7206): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7206): startup - clean
,I/Babel   ( 7206): deleted: false for 0
,I/art     ( 6678): CheckpointMarkThreadRoots callback created = 0xb042d330
,I/art     ( 6678): CheckpointMarkThreadRoots callback created = 0xb042d320
I/ActivityManager(  860): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7246 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 4199): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 4199): Failed to find provider info for com.google.android.wearable.settings
I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,W/AudioCapabilities( 7206): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 7206): Unsupported mime audio/adpcm
,W/AudioCapabilities( 7206): Unsupported mime audio/g726
W/AudioCapabilities( 7206): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7206): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7206): Unsupported mime video/mjpg
W/VideoCapabilities( 7206): Unsupported mime video/theora
,W/AudioCapabilities( 7206): Unsupported mime audio/evrc
,W/AudioCapabilities( 7206): Unsupported mime audio/qcelp
W/VideoCapabilities( 7206): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7206): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7206): Unsupported mime audio/qcelp
W/AudioCapabilities( 7206): Unsupported mime audio/evrc
W/VideoCapabilities( 7206): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7206): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7206): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7206): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7206): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7206): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 7206): onServiceConnected
,W/Babel   ( 7206): Attempted to change video mute state without an active call.
I/NotificationManager( 7206): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 7206): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7206): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7206): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7206): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  275): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 7206): propertyValue:false
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7246): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ContextImpl( 7246): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7246): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/GAv4    ( 7246): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7246):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7246):   adb logcat -s GAv4
I/Babel   ( 7206): connection state changed from UNKNOWN to CONNECTED
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7246): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/ActivityManager(  860): Killing 6659:com.android.chrome/u0a48 (adj 15): empty #11
,W/libprocessgroup(  860): failed to open /acct/uid_10048/pid_6659/cgroup.procs: No such file or directory
,W/GAv4    ( 7246): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/CheckinRequestBuilder( 4199): Classify the device as Phone.
,W/GAv4    ( 7246): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 7246): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/CheckinTask( 4199): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4199): Checking schedule, now: 1453885521297 next: 1454412770292
I/CheckinService( 4199): active receiver: disabled
,I/CheckinService( 4199): Checking schedule, now: 1453885521326 next: 1454412770292
I/CheckinService( 4199): active receiver: disabled
,D/CheckinService( 4199): Recording last checkin time for package unspecified as 1453885521337
I/ActivityManager(  860): Killing 7049:com.google.android.music:main/u0a81 (adj 15): empty #11
,I/ActivityManager(  860): Killing 6678:com.google.android.apps.plus/u0a86 (adj 15): empty #12
,W/libprocessgroup(  860): failed to open /acct/uid_10081/pid_7049/cgroup.procs: No such file or directory
,W/libprocessgroup(  860): failed to open /acct/uid_10086/pid_6678/cgroup.procs: No such file or directory
I/WebViewFactory( 7246): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7246): Time to load native libraries: 3 ms (timestamps 8999-9002)
I/LibraryLoader( 7246): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7246): Binding Chromium to main looper Looper (main, tid 1) {264289bb}
I/LibraryLoader( 7246): Expected native library version number "",actual native library version number ""
I/chromium( 7246): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7246): Initializing chromium process, singleProcess=true
,W/art     ( 7246): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7246): ApplicationContext is null in ApplicationStatus
W/chromium( 7246): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7246): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7246): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7246): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7246): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7246): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7246): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7246): Remote Branch: 
I/Adreno-EGL( 7246): Local Patches: 
I/Adreno-EGL( 7246): Reconstruct Branch: 
V/AudioPolicyService(  282): registerClient() client 0xb39b5a40, uid 10079
,W/AudioManagerAndroid( 7246): Requires BLUETOOTH permission
I/NSApplication( 7246): Starting up...
,I/ActivityManager(  860): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7313 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  860): Killing 7082:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  860): failed to open /acct/uid_10021/pid_7082/cgroup.procs: No such file or directory
,I/ActivityManager(  860): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7335 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  860): Killing 7109:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  860): failed to open /acct/uid_1000/pid_7109/cgroup.procs: No such file or directory
,W/ResourcesManager( 7335): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  860): Killing 2618:com.lge.music/u0a28 (adj 15): empty #11
,V/AudioFlinger(  282): 2618 died, releasing its sessions
V/AudioFlinger(  282):  pid 1750 @ 0
V/AudioFlinger(  282):  pid 3231 @ 1
V/AudioFlinger(  282):  pid 3231 @ 2
,W/libprocessgroup(  860): failed to open /acct/uid_10028/pid_2618/cgroup.procs: No such file or directory
,D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  860): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7359 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 7359): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  860): Message: 20
D/BluetoothManagerService(  860): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3a0aa6e2:true
,D/BluetoothAdapterService(900660909)( 2012): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3af047eb
D/BluetoothAdapterService(900660909)( 2012): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3af047eb
I/ActivityManager(  860): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7377 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7359): Create singleton instance
,D/UEI.SmartControl( 7377): Quickset Services start...
,I/UEI.SmartControl( 7377): Manufacture = LGE
D/UEI.SmartControl( 7377): File observer start...
E/UEI.SmartControl( 7377): IR Port is disabled: false
D/UEI.SmartControl( 7377): Starting file observer...
D/UEI.SmartControl( 7377): Extracting JNI libs...
D/UEI.SmartControl( 7377): --- this system supports 32-bit or 64-bit only
I/AudioManager( 7359): getMode name:com.lge.qremote
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
I/CheckinService( 4199): Checkin interval check for package: unspecified last checkin: 1453885521337 min interval config: 0 actual interval: 1593
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
,I/System.out( 1731): propertyValue:false
D/LocationInitializer( 4199): Restart initialization of location
D/WearableService( 1731): callingUid 10006, callindPid: 1731
,D/AuthorizationBluetoothService( 1731): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/CheckinService( 4199): Checking schedule, now: 1453885522996 next: 1454412770292
I/CheckinService( 4199): active receiver: disabled
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
,W/GCoreFlp( 1731): No location to return for getLastLocation()
,W/FusedLocationProvider( 1731): location=null
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/MDM     ( 1731): [143] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/SetupWizard( 7158): Connected to Gservices successfully
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/ContextImpl( 3605): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/AudioManager( 7359): getMode name:com.lge.qremote
,D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/UEI.SmartControl( 7377): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7377): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7377): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 7377): --- Selecting new region: 2
I/UEI.SmartControl( 7377): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7377): Platform has CIR...
D/UEI.SmartControl( 7377): NO CIR support, need to check package...
I/UEI.SmartControl( 7377): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7377): QS Service created
,E/UEI.SmartControl( 7377): QS start get config
,D/UEI.SmartControl( 7377): Loading JNI Libs...
,D/UEI.SmartControl( 7377):  configuring local db...
D/UEI.SmartControl( 7377):  ---- Has DB8: true
,D/UEI.SmartControl( 7377): QS start statue = true Error code = 0
D/UEI.SmartControl( 7377): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7377): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7377): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7377): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7377): IrrcClient ++ 
D/irrcClient( 7377): getIrrcService ++ 
D/irrcClient( 7377): getIrrcService -- 
D/irrcClient( 7377): IrrcClient -- 
W/irrc_jni( 7377): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7377): Services init done
,I/UEI.SmartControl( 7377): Device manager: loading config....
D/UEI.SmartControl( 7377): QS Service init finished
D/UEI.SmartControl( 7377): QS Service version name: 0.1.73
D/UEI.SmartControl( 7377): Config is loaded...
D/UEI.SmartControl( 7377): QS Service version code: 1073
D/UEI.SmartControl( 7377): Service requested: Control
D/UEI.SmartControl( 7377): Internal service binding...
D/UEI.SmartControl( 7377): -----IControl: 11
D/UEI.SmartControl( 7377): Caller: com.lge.qremote
D/UEI.SmartControl( 7377): ------------ IControl registerCallback...
I/UEI.SmartControl( 7377): Registering callback...
,D/UEI.SmartControl( 7377): -----IControl: 19
D/UEI.SmartControl( 7377): Caller: com.lge.qremote
I/UEI.SmartControl( 7377): Registering Services Ready callback...
I/UEI.SmartControl( 7377): Notify client services are ready...
D/UEI.SmartControl( 7377): -----IControl: 8
D/UEI.SmartControl( 7377): Caller: com.lge.qremote
I/AudioManager( 7359): getMode name:com.lge.qremote
D/UEI.SmartControl( 7377):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 7377): Notify AllClients services are ready: 0
I/AudioManager( 7359): getMode name:com.lge.qremote
,I/AudioManager( 7359): getMode name:com.lge.qremote
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-58 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-27 10:05:23.687 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QPairHandler( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[SystemUI]QSlideListController( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/InputReader(  860): Reconfiguring input devices.  changes=0x00000010
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1373): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 7136): onReceive
I/AppUp4:CustModeStarterReceiver( 7136): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 7136): Context : android.app.ReceiverRestrictedContext@430ea56
D/AppUp4:CustFacade( 7136): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7136): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7136): begin check event
I/AppUp4:CustModeStarterReceiver( 7136): Event For Nothing, skip.
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,W/ResourcesManager( 7206): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7206): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/administrator(  860): Handling package changes for user 0
,I/NotificationManager( 7206): com.google.android.talk: cancel(8) by com.google.android.talk
I/ActivityManager(  860): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7451 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,V/JNIHelp ( 7206): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ResourcesManager( 7451): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7451): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7451): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/System  ( 7206): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7206): Installed default security provider GmsCore_OpenSSL
,I/art     (  860): Explicit concurrent mark sweep GC freed 23563(1179KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.446ms total 170.603ms
,I/AppConfig( 7451): Total System Memory = 906309632
,I/GalleryUtils( 7451): Application Heap = 96 MB
I/AppConfig( 7451): App Tier : NOT_DEF
D/SystemHelper( 7451): region [EU], country [EU], operator [OPEN], sub-operator []
,D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
I/NotificationService(  860): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  860): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  860): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  860): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/ResourcesManager(  860): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  860): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7472 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,V/BackupManagerService(  860): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  860): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2e4de17c
,W/ResourceType(  860): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
W/ResourcesManager( 7472): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7472): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7472): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7472): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7472): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1731): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  860): applying state to connected service
,I/SystemConfig( 7472): BUILD Country: EU
I/SystemConfig( 7472): BUILD Operator: OPEN
,I/ActivityManager(  860): Killing 7180:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  860): failed to open /acct/uid_10051/pid_7180/cgroup.procs: No such file or directory
,I/ActivityManager(  860): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7495 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  860): Killing 7246:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
W/libprocessgroup(  860): failed to open /acct/uid_10079/pid_7246/cgroup.procs: No such file or directory
,V/AlarmManager(  860): ELAPSED_WAKEUP set : Alarm{a4d7a44 type 2 when 122793 com.google.android.gms} when 122793
I/SystemConfig( 7472): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7472): existFile = false
I/SystemConfig( 7472): canReadFile = false
I/SystemConfig( 7472): systemFeature RCS result false
D/SystemConfig( 7472): refreshRcsSupport() :false
I/LockScreenSettings( 7495): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7495): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7495): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7495): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7495): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7495): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/UpdateIcingCorporaServi( 1939): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/art     ( 7335): Suspending all threads took: 6.625ms
,I/ActivityManager(  860): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7516 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     ( 7335): CheckpointMarkThreadRoots callback created = 0xb042d590
I/art     ( 7335): CheckpointMarkThreadRoots callback created = 0xb042d570
,I/ActivityManager(  860): Killing 7313:com.android.chrome/u0a48 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1939): UpdateCorporaTask done [took 112 ms] updated apps [took 112 ms] 
,W/libprocessgroup(  860): failed to open /acct/uid_10048/pid_7313/cgroup.procs: No such file or directory
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/Finsky  ( 7516): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7516): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7516): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7516): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7516): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3213): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3213): created cursor android.database.sqlite.SQLiteCursor@11edced8 on behalf of 7516
D/Finsky  ( 7516): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7516): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 7516): Skipping gmscore version check
I/ActivityManager(  860): Killing 7158:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  860): failed to open /acct/uid_10038/pid_7158/cgroup.procs: No such file or directory
,D/Finsky  ( 7516): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 4199): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4199): Null package name or gms related package.  Ignoreing.
D/Finsky  ( 7516): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 4199): updateResources: need to parse f{com.google.android.gms}
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/Icing   ( 4199): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4199): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ActivityManager(  860): Killing 7377:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 7359): android.os.DeadObjectException
,W/System.err( 7359): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7359): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7359): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7359): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7359): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7359): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7359): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7359): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7359): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7359): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7359): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7359): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7359): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7359): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7359): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7359): android.os.DeadObjectException
W/System.err( 7359): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7359): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7359): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7359): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7359): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7359): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7359): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7359): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7359): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7359): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7359): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7359): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7359): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7359): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7359): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  860): failed to open /acct/uid_10089/pid_7377/cgroup.procs: No such file or directory
W/ActivityManager(  860): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,I/ActivityManager(  860): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7568 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 336us total 31.554ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 21.303ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 21.354ms
,D/UEI.SmartControl( 7568): Quickset Services start...
,I/UEI.SmartControl( 7568): Manufacture = LGE
,D/UEI.SmartControl( 7568): File observer start...
E/UEI.SmartControl( 7568): IR Port is disabled: false
D/UEI.SmartControl( 7568): Starting file observer...
D/UEI.SmartControl( 7568): Extracting JNI libs...
D/UEI.SmartControl( 7568): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7568): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7568): --- Checking lib: libqs_armeabi-v7a.zip
,D/UEI.SmartControl( 7568): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7568): --- Selecting new region: 2
I/UEI.SmartControl( 7568): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7568): Platform has CIR...
D/UEI.SmartControl( 7568): NO CIR support, need to check package...
I/UEI.SmartControl( 7568): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7568): QS Service created
E/UEI.SmartControl( 7568): QS start get config
,D/UEI.SmartControl( 7568): Loading JNI Libs...
,D/UEI.SmartControl( 7568):  configuring local db...
D/UEI.SmartControl( 7568):  ---- Has DB8: true
,D/UEI.SmartControl( 7568): QS start statue = true Error code = 0
D/UEI.SmartControl( 7568): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7568): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 7568): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7568): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7568): IrrcClient ++ 
D/irrcClient( 7568): getIrrcService ++ 
D/irrcClient( 7568): getIrrcService -- 
D/irrcClient( 7568): IrrcClient -- 
W/irrc_jni( 7568): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 7568): Services init done
I/UEI.SmartControl( 7568): Device manager: loading config....
D/UEI.SmartControl( 7568): QS Service init finished
D/UEI.SmartControl( 7568): QS Service version name: 0.1.73
,D/UEI.SmartControl( 7568): QS Service version code: 1073
D/UEI.SmartControl( 7568): Service requested: Control
D/UEI.SmartControl( 7568): Config is loaded...
D/UEI.SmartControl( 7568):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 7568): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7568): Request IControl service: devices are loaded...
D/UEI.SmartControl( 7568): -----IControl: 11
I/ActivityManager(  860): Killing 7136:com.lge.appbox.client/u0a11 (adj 15): empty #11
D/UEI.SmartControl( 7568): Caller: com.lge.qremote
D/UEI.SmartControl( 7568): ------------ IControl registerCallback...
I/UEI.SmartControl( 7568): Registering callback...
D/UEI.SmartControl( 7568): -----IControl: 19
D/UEI.SmartControl( 7568): Caller: com.lge.qremote
I/UEI.SmartControl( 7568): Registering Services Ready callback...
I/UEI.SmartControl( 7568): Notify client services are ready...
,D/UEI.SmartControl( 7568): -----IControl: 8
D/UEI.SmartControl( 7568): Caller: com.lge.qremote
W/libprocessgroup(  860): failed to open /acct/uid_10011/pid_7136/cgroup.procs: No such file or directory
,I/AudioManager( 7359): getMode name:com.lge.qremote
D/UEI.SmartControl( 7568): Internal service binding...
I/AudioManager( 7359): getMode name:com.lge.qremote
,I/AudioManager( 7359): getMode name:com.lge.qremote
,I/ActivityManager(  860): Killing 7206:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  860): failed to open /acct/uid_10061/pid_7206/cgroup.procs: No such file or directory
,D/charger_monitor(  478): init target 500000
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
,D/charger_monitor(  478): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
,D/WifiController(  860): battery changed pluggedType: 2
W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 2012): Disconnected process message: 10, size: 0
,I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/UEI.SmartControl( 7568): Internal timer expired: 1
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 136382235162; DSPS: 4560437; Offset : -2801626591
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,V/AlarmManager(  860): ELAPSED_WAKEUP set : Alarm{25e91e5b type 2 when 139308 com.google.android.gms} when 139308
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1731): Vacuum at: now=1453885542182 tag=VacuumService
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  860): ALS enabled for SRE
D/PowerManagerServiceEx(  860): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (30766 ms ago)
,D/qdlights(  860): set_light_backlight: 251
,D/qdlights(  860): set_light_backlight: 248
,D/qdlights(  860): set_light_backlight: 245
,D/qdlights(  860): set_light_backlight: 241
,D/qdlights(  860): set_light_backlight: 238
,D/qdlights(  860): set_light_backlight: 235
,D/qdlights(  860): set_light_backlight: 231
,D/qdlights(  860): set_light_backlight: 228
,D/qdlights(  860): set_light_backlight: 225
,D/qdlights(  860): set_light_backlight: 221
,D/qdlights(  860): set_light_backlight: 218
,D/qdlights(  860): set_light_backlight: 215
,D/qdlights(  860): set_light_backlight: 211
,D/qdlights(  860): set_light_backlight: 208
,D/qdlights(  860): set_light_backlight: 205
,D/qdlights(  860): set_light_backlight: 201
,D/qdlights(  860): set_light_backlight: 198
,D/qdlights(  860): set_light_backlight: 195
,D/qdlights(  860): set_light_backlight: 191
,D/qdlights(  860): set_light_backlight: 188
,D/qdlights(  860): set_light_backlight: 185
,D/qdlights(  860): set_light_backlight: 181
,D/qdlights(  860): set_light_backlight: 178
,D/qdlights(  860): set_light_backlight: 175
,D/qdlights(  860): set_light_backlight: 171
,D/qdlights(  860): set_light_backlight: 168
,D/qdlights(  860): set_light_backlight: 165
,D/qdlights(  860): set_light_backlight: 161
,D/qdlights(  860): set_light_backlight: 158
,D/qdlights(  860): set_light_backlight: 155
,D/qdlights(  860): set_light_backlight: 151
,D/qdlights(  860): set_light_backlight: 148
,D/qdlights(  860): set_light_backlight: 145
,D/qdlights(  860): set_light_backlight: 141
,D/qdlights(  860): set_light_backlight: 138
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/qdlights(  860): set_light_backlight: 135
,D/qdlights(  860): set_light_backlight: 131
,D/qdlights(  860): set_light_backlight: 128
,D/qdlights(  860): set_light_backlight: 125
,D/qdlights(  860): set_light_backlight: 121
,D/qdlights(  860): set_light_backlight: 118
,D/qdlights(  860): set_light_backlight: 115
,D/qdlights(  860): set_light_backlight: 111
,D/qdlights(  860): set_light_backlight: 108
,D/qdlights(  860): set_light_backlight: 105
,D/qdlights(  860): set_light_backlight: 101
,D/qdlights(  860): set_light_backlight: 98
,D/qdlights(  860): set_light_backlight: 95
,D/qdlights(  860): set_light_backlight: 91
,D/qdlights(  860): set_light_backlight: 88
,D/qdlights(  860): set_light_backlight: 85
,D/qdlights(  860): set_light_backlight: 81
,D/qdlights(  860): set_light_backlight: 78
,D/qdlights(  860): set_light_backlight: 75
,D/qdlights(  860): set_light_backlight: 71
,D/qdlights(  860): set_light_backlight: 68
,D/qdlights(  860): set_light_backlight: 65
,D/qdlights(  860): set_light_backlight: 61
,D/qdlights(  860): set_light_backlight: 58
,D/qdlights(  860): set_light_backlight: 55
,D/qdlights(  860): set_light_backlight: 51
,D/qdlights(  860): set_light_backlight: 48
,D/qdlights(  860): set_light_backlight: 45
,D/qdlights(  860): set_light_backlight: 41
,D/qdlights(  860): set_light_backlight: 38
,D/qdlights(  860): set_light_backlight: 35
,D/qdlights(  860): set_light_backlight: 31
,D/qdlights(  860): set_light_backlight: 28
,D/qdlights(  860): set_light_backlight: 25
,D/qdlights(  860): set_light_backlight: 21
,D/qdlights(  860): set_light_backlight: 18
,D/qdlights(  860): set_light_backlight: 15
,D/qdlights(  860): set_light_backlight: 11
,D/qdlights(  860): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 156383805883; DSPS: 5215848; Offset : -2801612163
,D/PowerManagerServiceEx(  860): acquireWakeLockInternal: lock=523751443, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=860
,D/WeatherService( 2612): 2 : TimeTick Intent has been received, Time(hour:min:sec) 10:6:0
D/WeatherService( 2612): 2 : TimeTick Intent And Screen On
D/WeatherService( 2612): 2 : SDK version : 21
W/ActivityManager(  860): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2612): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2612): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2612): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2612): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 2612): 2 : This is isUpdating : false
D/WeatherService( 2612): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2612): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2612): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2612): 2 : Fixed theme : optimus
D/WeatherReflect( 2612): 2 : Map key string is -2
,D/lim     ( 2612): 2 : time = 10:06
I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/WeatherReflect( 2612): Model Name : LG-D722
D/WeatherTheme( 2612): 2 : Different view - status_min_formatted : 05 != 06
D/WeatherTheme( 2612): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2612): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
,I/[SystemUI]Clock( 1373): called onTimeUpdated()
I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
D/Theme   ( 2612): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2612): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2612): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2612): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
D/Weather4x2_optimus( 2612): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2612): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2612): forecast size is 0
D/Theme   ( 2612): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2612): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2612): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2612): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2612): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2612): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2612): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2612): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2612): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2612): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2612): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
,D/Theme   ( 2612): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2612): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2612): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2612): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2612): url is : null
D/Theme   ( 2612): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2612): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2612): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
,D/WeatherAncestor( 2612): 2 : update view, appWidgetId: 2
D/WeatherService( 2612): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 10:6:0
D/PowerManagerServiceEx(  860): releaseWakeLockInternal: lock=523751443 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/PowerManagerService(  860): ALS enabled for SRE
D/PowerManagerServiceEx(  860): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (37760 ms ago)
I/PowerManagerService(  860): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  860): ALS enabled for SRE
D/PowerManagerServiceEx(  860): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (37767 ms ago)
W/ContextImpl(  860): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  860): Sleeping (uid 1000)...
D/LPWGController(  860): [updateScreenState] screen on = false
,D/LPWGController(  860): disable proximity sensor
D/LPWGController(  860): enable proximity sensor
I/SensorManager(  860): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@3ed68d10] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  860): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  860): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  860): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  860): activate: handle is 48, enable
V/sensors_hal_Ctx(  860): activate sensors is 1400000000000
D/sensors_hal_Thresh(  860): enable: handle=48
I/sensors_hal_SAM(  860): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  860): waitForResponse: timeout=1000
V/sensors_hal_SAM(  860): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  860): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  860): enable: Received response: 0
D/PowerManagerServiceEx(  860): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (37801 ms ago)
,I/Adreno-EGL(  860): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  860): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  860): Build Date: 03/02/15 Mon
I/Adreno-EGL(  860): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  860): Remote Branch: 
I/Adreno-EGL(  860): Local Patches: 
I/Adreno-EGL(  860): Reconstruct Branch: 
,D/PermissionCache(  248): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1012 us)
,I/Sensors (  417): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  860): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  860): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  860): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  860): processInd: handle 48, count=1
V/sensors_hal_Thresh(  860): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  860): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  860): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  860): poll: count: 256
I/sensors_hal_Ctx(  860): poll: released wakelock sensor_ind
D/sensors_hal_Util(  860): waitForResponse: timeout=0
D/LPWGController(  860): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  860): current mode = 1  value = 1 1
I/LPWGController(  860): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  860): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/qdlights(  860): set_light_backlight: 0
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/SensorManager(  860): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
I/sensors_hal_Ctx(  860): activate: handle is 46, disable
V/sensors_hal_Ctx(  860): activate sensors is 1000000000000
D/sensors_hal_LP2(  860): enable: handle=46
D/sensors_hal_LP2(  860): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  860): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  248): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  248): hwc_blank: Blanking display: 0
I/DisplayManagerService(  860): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/sensors_hal_SAM(  860): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  860): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
V/ActivityManager(  860): Display changed displayId=0
,D/DSDPConnection( 1750): Display #0 changed.
D/qdhwcomposer(  248): hwc_blank: Done blanking display: 0
D/SurfaceControl(  860): Excessive delay in setPowerMode(): 221ms
,I/qdhwcomposer(  248): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  860): Got set_interactive hint
,D/KeyguardViewMediator( 1373): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1334): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1334): notifyScreenOffLocked
D/SmartCoverViewMediator( 1334): handleNotifyScreenOFF
D/KeyguardViewMediator( 1373): notifyScreenOffLocked
D/KeyguardViewMediator( 1373): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1373): handleNotifyScreenOff
,D/WifiServerServiceExt(  860): sendKtScanInterval  mRtspPlay : false
,D/ScreenTurnOffBySensor( 1373): unregisterProximitySensor
V/AudioFlinger(  282): setParameters(): io 0, keyvalue screen_state=on, calling pid 860
,D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=on
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
D/StatusBarWindowView( 1373): onScreenTurnedOff why = 3
I/WifiServerServiceExt(  860): set CMD_KT_SCAN_INTERVAL
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/GpsLocationProvider(  860): receive broadcast intent, action: android.intent.action.SCREEN_ON
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
,I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1839): |CORE| sendScreenState: state:true
I/LEDService( 1803): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1803): stopPatternFlashing()
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
I/LEDService( 1803): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1785): action : android.intent.action.SCREEN_ON
I/LEDService( 1803): updateLightsLocked : turn off led
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
I/Cliptray Service( 1803): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/Cliptray Service( 1803): lockStatus = 0
D/LEDHandler( 1803): RESTART MSG
D/NfcServiceNXP( 1785): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1785): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1785): isRequireNfcCRouting() return true
D/LNfcService( 1785): isHCERoutingtoHost() return : true
D/NfcService( 1785): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1785): mEnableLPD: true
D/NfcService( 1785): mEnableReader: false
D/NfcService( 1785): mEnableHostRouting: true
D/NfcService( 1785): newParams.techmask= mTechMask: default
D/NfcService( 1785): mEnableLPD: true
D/NfcService( 1785): mEnableReader: false
D/NfcService( 1785): mEnableHostRouting: true
D/NfcService( 1785): screenState= 3
D/NfcService( 1785): Discovery configuration equal, not updating.
D/Ulp_jni (  860): JNI:system_update. Event-0
,I/ActivityManager(  860): Process com.google.android.gms.unstable (pid 6957) has died
,D/SplitWindow(  860): check instance of lgWin Window{51da42f u0 SearchPanel}
,D/InputDispatcher(  860): Window went away: Window{3e18a518 u0 SearchPanel}
,I/[SystemUI]Clock( 1373): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1373): time changed, timezoneChanged : false
,V/PhoneApp( 1750): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2612): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 10:6:1
D/WeatherService( 2612): 2 : ACTION screen on
,D/WeatherService( 2612): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2612): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2612): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 10:6:1
W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  860): ACTION_SCREEN_ON
D/AppCleanupService( 4036): android.intent.action.SCREEN_ON
,V/AudioFlinger(  282): setParameters(): io 0, keyvalue screen_state=off, calling pid 860
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
D/WifiController(  860): CMD_SCREEN_OFF 
D/WifiController(  860): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  860): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.SCREEN_OFF
,I/QCNEJ   ( 1839): |CORE| sendScreenState: state:false
,I/LEDService( 1803): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1803): stopPatternFlashing()
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
I/LEDService( 1803): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1803): clear
D/LNfcService( 1785): action : android.intent.action.SCREEN_OFF
I/LEDService( 1803): updateLightsLocked : turn on led
E/LEDService( 1803): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1803): Can't handle this request of patternId:0
D/LEDHandler( 1803): RESTART MSG
I/Cliptray Service( 1803): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1785): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1877): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1750): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2612): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 10:6:1
D/WeatherService( 2612): 2 : ACTION screen off
D/WeatherService( 2612): 2 : TimeTick Receiver Unregister
D/WeatherService( 2612): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 10:6:1
W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  860): ACTION_SCREEN_OFF
D/AppCleanupService( 4036): android.intent.action.SCREEN_OFF
D/AppCleanupService( 4036): AppUsageStatsSaveTask
,E/NxpNfcJni( 1785): getReconnectState = 0x0
,I/ActivityManager(  860): Process com.android.contacts (pid 7472) has died
,D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
D/LNfcService( 1785): isRequireNfcCRouting() return true
D/LNfcService( 1785): isHCERoutingtoHost() return : true
D/NfcService( 1785): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1785): mEnableLPD: true
D/NfcService( 1785): mEnableReader: false
D/NfcService( 1785): mEnableHostRouting: true
D/NfcService( 1785): newParams.techmask= mTechMask: 0
D/NfcService( 1785): mEnableLPD: true
D/NfcService( 1785): mEnableReader: false
D/NfcService( 1785): mEnableHostRouting: true
D/NfcService( 1785): screenState= 1
E/NxpNfcJni( 1785): getReconnectState = 0x0
,I/Sensors (  417): sns_pwr.c(301):releasing wakelock
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/KeyguardViewMediator( 1373): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  860): ELAPSED_WAKEUP set : Alarm{20ff6a3c type 2 when 163669 com.android.systemui} when 163669
,D/PhoneUtils( 1750): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1750): getCallState : 0
,D/PhoneUtils( 1750): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1373): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1373): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 176384473949; DSPS: 5871230; Offset : -2801615666
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/charger_monitor(  478): init target 500000
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
,D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2012): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  860): battery changed pluggedType: 2
I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  860): ELAPSED_WAKEUP set : Alarm{586b3c5 type 2 when 189098 com.google.android.gms} when 189098
,I/PhenotypeConfigurator( 1731): Scheduling Phenotype for one-off execution 3266 seconds from now (1453885592027)
,D/GetConfigurationSnapshotOperation( 1731): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1731): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1731): Using platform SSLCertificateSocketFactory
,I/art     ( 1731): Explicit concurrent mark sweep GC freed 45005(2MB) AllocSpace objects, 32(512KB) LOS objects, 40% free, 13MB/22MB, paused 1.520ms total 99.222ms
,D/LocationManagerService(  860): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 1731): propertyValue:false
,V/AlarmManager(  860): ELAPSED_WAKEUP set : Alarm{351c5972 type 2 when 189830 android} when 189830
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/LocationManagerService(  860): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  860): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  860): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 196385304149; DSPS: 6526617; Offset : -2801610222
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ClearcutLoggerApiImpl( 1731): disconnect managed GoogleApiClient
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 216386060755; DSPS: 7182002; Offset : -2801615904
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 236386734394; DSPS: 7837384; Offset : -2801614094
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  478): init target 500000
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2012): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  860): battery changed pluggedType: 2
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 256387489387; DSPS: 8492769; Offset : -2801621625
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 276388238338; DSPS: 9148154; Offset : -2801635300
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  860): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  860): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  860): tsOffsetIs: Apps: 296388917392; DSPS: 9803536; Offset : -2801627842
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/charger_monitor(  478): init target 500000
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2012): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  860): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  860): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  860): battery changed pluggedType: 2
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  478): init target 500000
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/jxcore-log( 6056): --= Surplus to requirements =--
I/jxcore-log( 6056): 
I/jxcore-log( 6056): ****TEST TOOK:  ms ****
I/jxcore-log( 6056): 
I/jxcore-log( 6056): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6056): 
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/AndroidRuntime( 7749): 
D/AndroidRuntime( 7749): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7749): CheckJNI is OFF
,D/AndroidRuntime( 7749): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  860): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
,I/ActivityManager(  860): Killing 6056:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  860): WIN DEATH: Window{2bf2aaef u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/InputDispatcher(  860): Focus left window: Window{2bf2aaef u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  860): Window went away: Window{2bf2aaef u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/PackageSettings(  860): Skipping PackageSetting{1ae8305b com.example.hello/10317} due to missing metadata
,I/ActivityManager(  860):   Force finishing activity ActivityRecord{28c4fa70 u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  860): Display changed displayId=0
D/DSDPConnection( 1750): Display #0 changed.
,W/ActivityManager(  860): Spurious death for ProcessRecord{3d19a4ca 6056:com.test.thalitest/u0a316}, curProc for 6056: null
,I/ActivityManager(  860): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  860):   Force finishing activity ActivityRecord{28c4fa70 u0 com.test.thalitest/.MainActivity t222 f}
W/ActivityManager(  860): Duplicate finish request for ActivityRecord{28c4fa70 u0 com.test.thalitest/.MainActivity t222 f}
,D/KeyguardModel( 1373): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/[LGHome]EVENT( 1877): [Launcher.java:5203:onStart()]onStart
,I/InputReader(  860): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 1939): Explicit concurrent mark sweep GC freed 10027(667KB) AllocSpace objects, 3(71KB) LOS objects, 39% free, 12MB/21MB, paused 17.455ms total 105.934ms
I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/art     ( 4199): Explicit concurrent mark sweep GC freed 4028(211KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 14MB/18MB, paused 2.386ms total 117.384ms
W/System.err( 3605): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,W/System.err( 3605): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3605): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3605): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/GeofencerStateMachine( 1731): Ignoring removeGeofence because network location is disabled.
W/System.err( 3605): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3605): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3605): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3605): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3605): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3605): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3605): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3605): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/[LGHome]EVENT( 1877): [Launcher.java:776:onResume()]onResume
,I/ActivityManager(  860): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7780 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/[LGHome]EVENT( 1877): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/KeyguardModel( 1373): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1373): createShortcutInfo...
I/[SystemUI]QSlideListController( 1373): onReceive = android.intent.action.PACKAGE_REMOVED
D/KeyguardModel( 1373): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1373): createShortcutInfo...
W/ResourcesManager( 1373): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1373): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
,W/PackageManager( 1373): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1373): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1373): createShortcutInfo...
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1373): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1373): createShortcutInfo...
,W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1373): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1373): createShortcutInfo...
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1373): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1373): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/art     (  860): Explicit concurrent mark sweep GC freed 63831(3MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 9.974ms total 271.788ms
I/art     (  860): WaitForGcToComplete blocked for 202.982ms for cause Explicit
,D/administrator(  860): Handling package changes for user 0
,W/ActivityManager(  860): Activity pause timeout for ActivityRecord{213c3950 u0 com.lge.launcher2/.Launcher t221}
,I/NotificationService(  860): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  860): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  860): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  860): removeObsoleteFile: deleting file=222_task.xml
,I/art     (  860): Explicit concurrent mark sweep GC freed 8422(465KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 4.393ms total 255.618ms
,I/art     (  860): WaitForGcToComplete blocked for 309.271ms for cause Explicit
D/AndroidRuntime( 7749): Shutting down VM
,I/art     (  860): Explicit concurrent mark sweep GC freed 3547(215KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.595ms total 178.244ms
,D/KeyguardModel( 1373): handleShortcutListChanged...
,D/KeyguardModel( 1373): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1373): createShortcutInfo...
I/[LGHome]LGActivityUtil( 1877): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1877): [Launcher.java:929:onResume()]onResume end
I/Activity( 1877): Activity.onPostResume() called 
D/KeyguardModel( 1373): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1373): createShortcutInfo...
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1373): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1373): createShortcutInfo...
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/[LGHome]EVENT( 1877): [Launcher.java:986:onPause()]onPause
D/KeyguardModel( 1373): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1373): createShortcutInfo...
,W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1373): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1373): createShortcutInfo...
I/Choreographer( 1877): Skipped 45 frames!  The application may be doing too much work on its main thread.
D/KeyguardModel( 1373): handleShortcutListChanged...
W/[LGHome]LGWallpaperInfo( 1877): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1877): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
,W/ResourcesManager( 7780): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7780): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7780): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemUI[Framework](  860): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
,D/PhoneStatusBar( 1373): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
W/PhoneWindowManagerEx(  860): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  860): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  860): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  860): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@fb8a806,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  860): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  860): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  860): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  860): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  860): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  860): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@fb8a806,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  860): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher(  860): Focus entered window: Window{c6ac085 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/PhoneStatusBar( 1373): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1373): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1373):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1373): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
,I/[LGHome]EVENT( 1877): [Launcher.java:5214:onStop()]onStop
I/[LGHome]EVENT( 1877): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,I/PhoneWindow( 1877): [setNavigationBarColor] color=0x 0
W/InputMethodManagerService(  860): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  860): Got RemoteException sending setActive(false) notification to pid 6056 uid 10316
,D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
,I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/ResourcesManager(  860): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Timeline(  860): Timeline: Activity_windows_visible id: ActivityRecord{213c3950 u0 com.lge.launcher2/.Launcher t221} time:310493
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,W/ResourceType(  860): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,W/IInputConnectionWrapper( 1877): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1617): Unable to connect to the editor to retrieve text... will retry later
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1877): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1877): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,W/FileUtils( 7780): Failed to chmod(/data/data/com.lge.email/databases/sqt.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
W/IInputConnectionWrapper( 1877): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/LGEmail ( 7780): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 7780): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
,W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}

```
