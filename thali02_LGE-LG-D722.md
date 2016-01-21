#### Test 56449660bb41d23_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
D/Finsky  ( 5620): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
I/Icing   ( 5691): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
I/Icing   ( 5691): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  847): android: cancelAsUser(2) by android
,--------- beginning of system
I/ActivityManager(  847): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6281 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
W/ResourcesManager( 6281): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6281): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-21 16:40:38.546 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/MultiDex( 6281): VM with version 2.1.0 has multidex support
I/MultiDex( 6281): install
I/MultiDex( 6281): VM has multidex support, MultiDex support library is disabled.
I/qtaguid ( 5620): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5620): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5620): untagSocket(41) failed with errno -22
D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 94803463144; DSPS: 3204335; Offset : -2993120582
I/art     ( 5601): Explicit concurrent mark sweep GC freed 2755(110KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 487us total 30.113ms
V/JNIHelp ( 6281): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ActivityThread( 6281): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6281): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@b8dfe4c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6281): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6281): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6281): com.google.android.gms: cancel(39789) by com.google.android.gms
E/MDM     ( 1735): [138] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1735): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 5691): Restart initialization of location
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1735): com.google.android.gms: cancel(0) by com.google.android.gms
D/ChimeraCfgMgr( 6281): Reading stored module config
W/GCoreFlp( 1735): No location to return for getLastLocation()
W/FusedLocationProvider( 1735): location=null
D/ChimeraCfgMgr( 6281): Loading module com.google.android.gms.car from APK com.google.android.gms
D/AndroidRuntime( 6298): 
D/AndroidRuntime( 6298): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6298): CheckJNI is OFF
D/CAR.SERVICE( 6281): Connecting to CarCallService...
I/art     ( 5620): CheckpointMarkThreadRoots callback created = 0xb042d740
D/NativeLibraryUtils( 6281): Install completed successfully. count=14 extracted=0
I/art     ( 6281): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6281): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5620): CheckpointMarkThreadRoots callback created = 0xb0574ea0
D/CAR.SERVICE( 6281): com.google.android.projection.gearhead isn't installed.
D/CAR.TEL.Service( 6281): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 6281): Creating a new PhoneAdapter instance
W/ActivityManager(  847): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6281): setListener: com.google.android.gms.car.dn@d19c98b
W/ActivityManager(  847): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6281): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6281): Starting CarCallService with initial phone null
I/NotificationManager( 6281): com.google.android.gms: cancel(10436) by com.google.android.gms
D/CAR.SERVICE( 6281): Package validated; name: com.android.vending
I/NotificationManager( 5620): com.android.vending: cancel(10436) by com.android.vending
V/Finsky  ( 5620): [1] GearheadStateMonitor.access$100: mIsProjecting:false
I/GAV2    ( 5948): Thread[GAThread,5,main]: No campaign data found.
I/GAv4-SVC( 5691): Google Analytics 8.4.89 is starting up.
D/AndroidRuntime( 6298): Calling main entry com.android.commands.am.Am
I/ActivityManager(  847): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/art     (  847): Explicit concurrent mark sweep GC freed 22703(1163KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.669ms total 155.383ms
D/ActivityManager(  847): setTaskToReturnTo : TaskRecord{3983299d #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  847): setTaskToReturnTo : TaskRecord{3983299d #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  847): AppWindowTokenEx init.. 
D/InputDispatcher(  847): Focus left window: Window{1c52ceb3 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 6298): Shutting down VM
I/[LGHome]EVENT( 1882): [Launcher.java:986:onPause()]onPause
D/ContextHelper(  847): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/SplitWindow(  847): check instance of lgWin Window{2fc2f13f u0 Starting com.test.thalitest}
I/ActivityManager(  847): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6346 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1882): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[LGHome]EVENT( 1882): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  847): Starting window displayed
I/SystemUI[Framework](  847): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1377): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  847): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  847): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  847): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  847): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@69c6f5,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  847): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,I/[SystemUI]NavigationThemeResource( 1377): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1377):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1377): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1377): draw background and invalidate : color = 10000000
D/BarTransitions( 1377): draw background and invalidate : color = 8080808
I/HotwordDetector( 1959): Closing mic
I/MicrophoneInputStream( 1959): mic_close com.google.android.apps.gsa.speech.audio.u@279bf441
V/AudioRecord( 1959): stop()
D/AudioRecord( 1959): AudioRecord->stop()
V/AudioFlinger(  282): RecordHandle::stop()
V/AudioFlinger(  282): RecordThread::stop
V/AudioFlinger(  282): Record stopped OK
V/AudioPolicyManager(  282): stopInput() input 17
V/AudioPolicyService(  282): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  282): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing release audio patch
D/audio_hw_primary(  282): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/AudioFlinger::PatchPanel(  282): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  282): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  282): ThreadBase::setParameters() routing=0
V/audio_hw_primary(  282): stop_input_stream: enter: usecase(7: audio-record)
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
V/AudioFlinger(  282): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  282): RecordThread: loop starting
V/AudioFlinger(  282): processConfigEvents_l() remaining events 1
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb3846000
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
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb3846000
V/AudioFlinger(  282): RecordThread: loop stopping
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioRecord( 1959): stop()
V/AudioRecord( 1959): stop()
V/AudioRecord( 1959): stop()
V/AudioFlinger(  282): RecordHandle::stop()
V/AudioFlinger(  282): RecordThread::stop
V/AudioPolicyManager(  282): releaseInput() 17
V/AudioPolicyManager(  282): closeInput(17)
V/AudioFlinger(  282): closeInput() 17
V/AudioSystem(  282): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): ThreadBase::exit
V/AudioFlinger(  282): RecordThread: loop starting
V/AudioFlinger(  282): RecordThread 0xb3846000 exiting
D/audio_hw_primary(  282): adev_close_input_stream: enter:stream_handle(0xb546dd40)
D/audio_hw_primary(  282): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioPolicyService(  282): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  282): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing update audio port list
V/AudioSystem(  847): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioSystem( 1959): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3167): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyManager(  282): releaseInput() exit
V/AudioFlinger(  282): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioSystem( 2006): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): removeClient_l() pid 1959, calling pid 282
V/AudioSystem( 1755): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2115): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1377): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): releasing 16 from 1959 for -1
V/AudioFlinger(  282):  decremented refcount to 0
V/AudioFlinger(  282): purging stale effects
I/HotwordRecognitionRnr( 1959): Hotword detection finished
I/HotwordRecognitionRnr( 1959): Stopping hotword detection.
D/ContextHelper( 6346): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 6346): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  847): android: cancelAsUser(2) by android
I/LibraryLoader( 6346): Time to load native libraries: 2 ms (timestamps 6229-6231)
I/LibraryLoader( 6346): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6346): Binding Chromium to main looper Looper (main, tid 1) {24d8ec9a}
I/LibraryLoader( 6346): Expected native library version number "",actual native library version number ""
I/chromium( 6346): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6346): Initializing chromium process, singleProcess=true
W/art     ( 6346): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6346): ApplicationContext is null in ApplicationStatus
W/chromium( 6346): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6346): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6346): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6346): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6346): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6346): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6346): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6346): Remote Branch: 
I/Adreno-EGL( 6346): Local Patches: 
I/Adreno-EGL( 6346): Reconstruct Branch: 
I/qtaguid ( 5620): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5620): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5620): untagSocket(41) failed with errno -22
V/AudioPolicyService(  282): registerClient() client 0xb4027300, uid 10316
D/BluetoothManagerService(  847): Message: 20
D/BluetoothManagerService(  847): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9eeab41:true
,D/BluetoothAdapterService(499726438)( 2006): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@196719ec
W/art     ( 6346): Attempt to remove local handle scope entry from IRT, ignoring
,W/ResourcesManager( 5620): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5620): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/AwContents( 6346): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6346): CordovaWebView is running on device made by: LGE
,W/art     ( 6346): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6346): Attempt to remove local handle scope entry from IRT, ignoring
W/ResourcesManager( 5620): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/Finsky  ( 5620): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  847): RTC_WAKEUP set : Alarm{1617e6b1 type 0 when 1453390840549 com.android.vending} when 1453390840549
,I/Activity( 6346): Activity.onPostResume() called 
,D/AlertService( 6060): Beginning updateAlertNotification
D/OpenGLRenderer( 6346): Render dirty regions requested: true
I/OpenGLRenderer( 6346): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6346): Enabling debug mode 0
D/Atlas   ( 6346): Validating map...
,D/SplitWindow(  847): check instance of lgWin Window{1e0a5b3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  847): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6404 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/chromium( 6346): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/DeviceConnectionService( 1735): client connected with version: 8296000
,D/Finsky  ( 5620): [686] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/InputDispatcher(  847): Focus entered window: Window{1e0a5b3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/Finsky  ( 5620): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/NotificationManager(  847): android: cancelAsUser(2) by android
D/Finsky  ( 5620): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
W/ResourcesManager( 6404): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/InputMethodManagerService(  847): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  847): Displayed com.test.thalitest/.MainActivity: +1s225ms
I/Timeline(  847): Timeline: Activity_windows_visible id: ActivityRecord{3ff4be12 u0 com.test.thalitest/.MainActivity t222} time:96944
,D/CalendarProvider2( 6404): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@30e73189
I/Timeline( 6346): Timeline: Activity_idle id: android.os.BinderProxy@bf22431 time:96952
D/libc-netbsd( 5620): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5620): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5620): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5620): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  277): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/CalendarProvider2( 6404): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 6404): Created com.android.providers.calendar.CalendarAlarmManager@24d8ec9a(com.android.providers.calendar.CalendarProvider2@30e73189)
,D/AlertService( 6060): No fired or scheduled alerts
I/NotificationManager( 6060): com.android.calendar: cancel(0) by com.android.calendar
,I/NotificationManager( 6060): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6060): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6060): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6060): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6060): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6060): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6060): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6060): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6060): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6060): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6060): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6060): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6060): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6060): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6060): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6060): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6060): com.android.calendar: cancel(17) by com.android.calendar
,I/NotificationManager( 6060): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6060): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6060): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 6060): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
,I/System.out( 5620): propertyValue:false
,D/AlarmScheduler( 6060): No events found starting within 1 week.
W/BindingManager( 6346): Cannot call determinedVisibility() - never saw a connection for the pid: 6346
I/ActivityManager(  847): Killing 6060:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  847): failed to open /acct/uid_10013/pid_6060/cgroup.procs: No such file or directory
,I/ActivityManager(  847): Killing 5784:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  847): failed to open /acct/uid_10061/pid_5784/cgroup.procs: No such file or directory
,D/JsMessageQueue( 6346): Set native->JS mode to OnlineEventsBridgeMode
I/ActivityManager(  847): Killing 6158:com.android.gallery3d/u0a23 (adj 15): empty #11
,I/ActivityManager(  847): Killing 6137:com.lge.appbox.client/u0a11 (adj 15): empty #12
,W/libprocessgroup(  847): failed to open /acct/uid_10023/pid_6158/cgroup.procs: No such file or directory
,W/libprocessgroup(  847): failed to open /acct/uid_10011/pid_6137/cgroup.procs: No such file or directory
D/jxcore_app_log( 6346): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622748672
,I/ActivityManager(  847): Process com.google.android.gm (pid 5948) has died
,I/chromium( 6346): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/art     ( 6346): CheckpointMarkThreadRoots callback created = 0x9f6b5420
,I/art     ( 6346): CheckpointMarkThreadRoots callback created = 0x9f6b53f0
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/art     ( 6346): Background sticky concurrent mark sweep GC freed 2286(173KB) AllocSpace objects, 0(0B) LOS objects, 0% free, 22MB/22MB, paused 5.683ms total 17.089ms
,W/jxcore-log( 6346): Initializing JXcore engine
,W/jxcore-log( 6346): JXcore engine is ready
W/Thread-781( 6438): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5840]" dev="sockfs" ino=5840 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-781( 6438): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-781( 6438): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8628]" dev="sockfs" ino=8628 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-781( 6438): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-781( 6438): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-781( 6438): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[31159]" dev="sockfs" ino=31159 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 6346): Starting JXcore engine
,W/jxcore-log( 6346): Platform android
W/jxcore-log( 6346): 
W/jxcore-log( 6346): Process ARCH arm
W/jxcore-log( 6346): 
,D/CAR.SERVICE( 6281): mConnectedToCar = false, abort
,E/ActivityThread( 6281): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@322e0b13 that was originally bound here
E/ActivityThread( 6281): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@322e0b13 that was originally bound here
E/ActivityThread( 6281): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6281): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6281): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6281): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6281): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6281): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6281): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6281): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6281): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6281): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6281): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6281): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6281): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6281): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6281): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6281): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6281): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6281): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6281): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6281): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6281): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6281): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6281): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6281): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3319c35a that was originally bound here
E/ActivityThread( 6281): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3319c35a that was originally bound here
E/ActivityThread( 6281): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6281): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6281): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6281): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6281): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6281): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6281): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6281): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6281): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6281): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6281): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6281): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6281): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6281): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6281): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6281): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6281): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6281): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6281): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6281): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6281): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6281): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  847): Unbind failed: could not find connection for android.os.BinderProxy@7eb74ff
,I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-58 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-21 16:40:44.577 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/jxcore-log( 6346): JXcore Cordova bridge is ready!
I/jxcore-log( 6346): 
W/jxcore-log( 6346): JXcore engine is started
,I/jxcore-log( 6346): Toggling radios to true
I/jxcore-log( 6346): 
,D/BluetoothAdapter( 6346): enable(): BT is already enabled..!
V/AlarmManager(  847): RTC_WAKEUP set : Alarm{3f2e7915 type 0 when 1453390844815 com.google.android.googlequicksearchbox} when 1453390844815
D/WifiServiceImplEx(  847): setWifiEnabled: true pid=6346, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService(  847): setWifiEnabled: true pid=6346, uid=10316
,D/WifiServiceImplEx(  847): disconnect pid=6346, uid=10316, packageName=com.test.thalitest
D/WifiServiceImplEx(  847): reconnect pid=6346, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 6346): Radios toggled
I/jxcore-log( 6346): 
I/jxcore-log( 6346): My device name is: LGE-LG-D722
I/jxcore-log( 6346): 
,I/wpa_supplicant( 2715): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2715): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
,E/WifiStateMachine(  847): WifiStateMachine: Leaving Connected state
D/WfdsMonitor( 1804): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,E/WifiConfigStore(  847): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/LGWifiP2pService(  847): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  847): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  277): Clearing all IP addresses on wlan0
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1735): Read error: ssl=0xaaee0a00: I/O error during system call, Connection timed out
,D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1735): SSL shutdown failed: ssl=0xaaee0a00: I/O error during system call, Broken pipe
D/ConnectivityService(  847): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/WifiStateMachine(  847): Start Disconnecting Watchdog 1
I/wpa_supplicant( 2715): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiHS20(  847): hidePasspointNotification off =false
,I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 16:40:44.987 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1377): mWifiConnected = false, mWifiLevel = 0
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WifiHS20(  847): hidePasspointNotification off =false
D/LGWifiP2pService(  847): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/CommandListener(  277): Clearing all IP addresses on wlan0
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  847): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 16:40:44.995 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,I/[SystemUI]QuickSettingsHandler( 1377): Got action android.net.wifi.STATE_CHANGE at null
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]QuickSettingsHandler( 1377): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1377): Remote
D/ConnectivityService(  847): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
I/[SystemUI]StatusBar.NetworkController( 1377): mWifiConnected = false, mWifiLevel = 0
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1377): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1377): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1377): Remote
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): ValidatedState{ when=-10ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): DefaultState{ when=-18ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): Forcing reevaluation
I/ActivityManager(  847): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6480 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,D/WifiHS20(  847): hidePasspointNotification off =false
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
I/art     (  312): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 293us total 22.171ms
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 16:40:45.094 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1377): mWifiConnected = false, mWifiLevel = 0
I/art     (  312): Explicit concurrent mark sweep GC freed 7(224B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 296us total 23.748ms
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1377): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1377): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1377): Remote
,D/WifiNetworkAgent(  847): NetworkAgent: NetworkAgent channel lost
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 16:40:45.119 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1377): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20(  847): hidePasspointNotification off =false
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1377): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1377): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1377): Remote
D/ConnectivityService(  847): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  847): disableDataServiceNotify
I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 22.158ms
,I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 16:40:45.129 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1377): mWifiConnected = false, mWifiLevel = 0
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/DSQN    (  847): stop dsqn bin
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1377): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1377): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1377): Remote
D/WifiServerServiceExt(  847): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  847): setSupplicantStateDISCONNECTED
D/WifiServerServiceExt(  847): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  847): setSupplicantStateSCANNING
,D/ConnectivityService(  847): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/DhcpStateMachine(  847): StoppedState
D/DhcpStateMachine(  847): StoppedState{ when=-161ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  847):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  847):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  847): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  847): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1377): CM callback handler got msg 524292
D/CSLegacyTypeTracker(  847): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  847): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  847): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/QCNEJ   ( 1840): |CORE| No family connected
D/ConnectivityService(  847): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  847): MasterInitialState.processMessage what=3
D/ConnectivityService(  847): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy(  847): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService(  847): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  847): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  847): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WIFI    (  847): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  847):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkManagementService(  847): Removing idletimer
D/TelephonyNetworkFactory-1( 1755): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1755):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/Tethering(  847): MasterInitialState.processMessage what=3
V/NetworkPolicy(  847): [LG_RESTRICTED] !!!isConnected  type  :1
W/QCNEJ   ( 1840): |CORE| No family connected
I/QCNEJ   ( 1840): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1840): |CORE| sendDefaultNwMsg: default = -1
,W/Settings(  847): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/ConnectivityService(  847): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/TelephonyIcons( 1377): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1377): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/TelephonyIcons( 1377): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1377): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/ResourcesManager( 6480): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6480): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6480): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6480): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6480): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/IndexDatabaseHelper( 6480): Using schema version: 115
,I/IndexDatabaseHelper( 6480): Index is fine
,I/ActivityManager(  847): Process com.google.android.apps.plus (pid 6220) has died
,V/WiFiOffLoadBroadcast( 6480): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6480): MCCMNC not supported: null
I/ActivityManager(  847): Process com.android.contacts (pid 6178) has died
,W/System.err( 4798): java.net.SocketTimeoutException
,W/System.err( 4798): 	at libcore.io.IoBridge.maybeThrowAfterRecvfrom(IoBridge.java:598)
W/System.err( 4798): 	at libcore.io.IoBridge.recvfrom(IoBridge.java:556)
W/System.err( 4798): 	at java.net.PlainDatagramSocketImpl.doRecv(PlainDatagramSocketImpl.java:163)
W/System.err( 4798): 	at java.net.PlainDatagramSocketImpl.receive(PlainDatagramSocketImpl.java:171)
W/System.err( 4798): 	at java.net.DatagramSocket.receive(DatagramSocket.java:274)
W/System.err( 4798): 	at com.lge.drmservice.activation.DrmSntpClient.processRequest(DrmSntpClient.java:257)
W/System.err( 4798): 	at com.lge.drmservice.activation.DrmSntpClient.run(DrmSntpClient.java:127)
W/System.err( 4798): Caused by: android.system.ErrnoException: recvfrom failed: EAGAIN (Try again)
W/System.err( 4798): 	at libcore.io.Posix.recvfromBytes(Native Method)
W/System.err( 4798): 	at libcore.io.Posix.recvfrom(Posix.java:161)
W/System.err( 4798): 	at libcore.io.BlockGuardOs.recvfrom(BlockGuardOs.java:250)
W/System.err( 4798): 	at libcore.io.IoBridge.recvfrom(IoBridge.java:553)
W/System.err( 4798): 	... 5 more
D/DrmSntpClient( 4798): Server : 3
I/ActivityManager(  847): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6511 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/DrmSntpClient( 4798): Automatic sync but WiFi isn't enabled
D/DrmService( 4798): Completed !! request = 2
D/DrmService( 4798): Request count = 0
V/DrmService( 4798): Service onDestroy
,I/PCSuite ( 6511): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6511): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6511): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2715): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/ActivityManager(  847): Process com.lge.qremote (pid 5071) has died
,D/UEI.SmartControl( 5760): Service.onUnbind: IControl
D/UEI.SmartControl( 5760): Service.onDestroy
D/UEI.SmartControl( 5760): Shutdown IRRCPlayer... 
I/wpa_supplicant( 2715): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
W/irrc_jni( 5760): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 5760): ~IrrcClient ++ 
D/irrcClient( 5760): ~IrrcClient -- 
W/irrc_jni( 5760): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 5760): Blaster closed
D/UEI.SmartControl( 5760): Blaster closed
D/UEI.SmartControl( 5760): Shut down QS...
D/UEI.SmartControl( 5760): Stopped file observer...
I/UEI.SmartControl( 5760): QS lib stop result = true
D/UEI.SmartControl( 5760): QS shutdown complete
,I/ActivityManager(  847): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6534 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
D/LocSvc_java(  847): onReceive
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,D/WifiServerServiceExt(  847): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  847): setSupplicantStateASSOCIATING
D/WifiServerServiceExt(  847): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  847): setSupplicantStateASSOCIATED
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 16:40:46.214 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1377): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 16:40:46.215 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1377): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1377): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1377): Remote
I/[SystemUI]StatusBar.NetworkController( 1377): mWifiConnected = false, mWifiLevel = 0
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1377): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1377): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1377): Remote
,W/ResourcesManager( 6534): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  847): Message: 20
,D/BluetoothManagerService(  847): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1e8504f7:true
D/BluetoothAdapterService(499726438)( 2006): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@196719ec
D/BluetoothAdapterService(499726438)( 2006): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@196719ec
V/WiFiOffLoadBroadcast( 6480): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6480): MCCMNC not supported: null
I/PCSuite ( 6511): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6511): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6511): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6480): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6480): MCCMNC not supported: null
I/PCSuite ( 6511): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6511): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6511): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  847): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6554 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6554): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6554): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6554): MmsConfig.loadMmsSettings
I/Babel_SMS( 6554): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6554): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6554): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6554): MmsConfig.loadFromResources
,E/Babel_SMS( 6554): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6554): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/rmt_storage(  275): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
,I/rmt_storage(  275): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  275): wakelock acquired: 1, error no: 42
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  275): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  275): 
I/rmt_storage(  275): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/art     ( 6554): CheckpointMarkThreadRoots callback created = 0xaaf53290
,D/SensorManager( 6554): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6554): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6554): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6554): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6554): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6554): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6554): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6554): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6554): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6554): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6554): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6554): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6554): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6554): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6554): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6554): found sensor: Motion Accel, handle=46
I/art     ( 6554): CheckpointMarkThreadRoots callback created = 0xaaf53280
,W/Settings( 6554): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6554): startup - clean
I/Babel   ( 6554): deleted: false for 0
,V/WiFiOffLoadBroadcast( 6480): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6480): MCCMNC not supported: null
W/AudioCapabilities( 6554): Unsupported mime audio/x-lg-flac
I/PCSuite ( 6511): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6511): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6511): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/AudioCapabilities( 6554): Unsupported mime audio/adpcm
W/AudioCapabilities( 6554): Unsupported mime audio/g726
V/WiFiOffLoadBroadcast( 6480): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/AudioCapabilities( 6554): Unsupported mime audio/x-ms-wma
D/WiFiOffLoadBroadcast( 6480): MCCMNC not supported: null
W/AudioCapabilities( 6554): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6554): Unsupported mime video/mjpg
W/VideoCapabilities( 6554): Unsupported mime video/theora
V/WiFiOffLoadBroadcast( 6480): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6480): Not supported operator for automatic switch
,V/WiFiOffLoadBroadcast( 6480): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6480): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6480): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6480): MCCMNC not supported: null
W/AudioCapabilities( 6554): Unsupported mime audio/evrc
,W/AudioCapabilities( 6554): Unsupported mime audio/qcelp
W/VideoCapabilities( 6554): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6554): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6554): Unsupported mime audio/qcelp
W/AudioCapabilities( 6554): Unsupported mime audio/evrc
W/VideoCapabilities( 6554): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6554): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6554): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6554): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6554): Unrecognized profile 2130706433 for video/avc
D/UEI.SmartControl( 5760): QS Service created
,W/VideoCapabilities( 6554): Unrecognized profile 2130706433 for video/avc
V/LGMDMManager( 6534): Create singleton instance
,I/vclib   ( 6554): onServiceConnected
W/Babel   ( 6554): Attempted to change video mute state without an active call.
E/UEI.SmartControl( 5760): QS start get config
,D/UEI.SmartControl( 5760):  configuring local db...
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
I/NotificationManager( 6554): com.google.android.talk: cancel(10436) by com.google.android.talk
I/AudioManager( 6534): getMode name:com.lge.qremote
,D/UEI.SmartControl( 5760):  ---- Has DB8: true
,D/UEI.SmartControl( 5760): QS start statue = true Error code = 0
D/UEI.SmartControl( 5760): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5760): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5760): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 5760): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5760): IrrcClient ++ 
D/irrcClient( 5760): getIrrcService ++ 
D/irrcClient( 5760): getIrrcService -- 
D/irrcClient( 5760): IrrcClient -- 
W/irrc_jni( 5760): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5760): Services init done
I/UEI.SmartControl( 5760): Device manager: loading config....
D/UEI.SmartControl( 5760): QS Service init finished
D/UEI.SmartControl( 5760): QS Service version name: 0.1.73
D/UEI.SmartControl( 5760): QS Service version code: 1073
,D/UEI.SmartControl( 5760): Service requested: Control
D/UEI.SmartControl( 5760): Config is loaded...
D/UEI.SmartControl( 5760):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5760): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 5760): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 5760): Internal service binding...
D/UEI.SmartControl( 5760): -----IControl: 11
D/UEI.SmartControl( 5760): File observer start...
E/UEI.SmartControl( 5760): IR Port is disabled: false
D/UEI.SmartControl( 5760): Starting file observer...
D/UEI.SmartControl( 5760): Caller: com.lge.qremote
D/UEI.SmartControl( 5760): ------------ IControl registerCallback...
I/UEI.SmartControl( 5760): Registering callback...
D/UEI.SmartControl( 5760): -----IControl: 19
D/UEI.SmartControl( 5760): Caller: com.lge.qremote
I/UEI.SmartControl( 5760): Registering Services Ready callback...
I/UEI.SmartControl( 5760): Notify client services are ready...
D/UEI.SmartControl( 5760): -----IControl: 8
D/UEI.SmartControl( 5760): Caller: com.lge.qremote
I/AudioManager( 6534): getMode name:com.lge.qremote
,I/ActivityManager(  847): Killing 6203:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,I/ActivityManager(  847): Killing 4798:com.lge.drmservice/u0a51 (adj 15): empty #12
,W/libprocessgroup(  847): failed to open /acct/uid_10069/pid_6203/cgroup.procs: No such file or directory
,W/libprocessgroup(  847): failed to open /acct/uid_10051/pid_4798/cgroup.procs: No such file or directory
I/AudioManager( 6534): getMode name:com.lge.qremote
I/AudioManager( 6534): getMode name:com.lge.qremote
,D/ConnectivityService(  847): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  847): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1377): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/GpsLocationProvider(  847): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  847): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6600 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/GpsLocationProvider(  847): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  847): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider(  847): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LocSvc_java(  847): onReceive
D/LocSvc_java(  847): got connectivity action
,I/[SystemUI]QuickSettingsHandler( 1377): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/LocSvc_java(  847): broadcast - no network connections
D/LocSvc_java(  847): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  847): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  847): onReceive
D/LocSvc_java(  847): got connectivity action
D/LocSvc_java(  847): broadcast - no network connections
D/LocSvc_java(  847): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  847): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  847): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  847): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  847): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  847): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  847): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  847): ignore wifi update if we are not in OPENING or CLOSING
,D/NetworkChangeNotifierAutoDetect( 1959): Network connectivity changed, type is: 6
,I/MusicStore( 6600): Database version: 120
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6600): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/ActivityManager(  847): Process com.android.vending (pid 5620) has died
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6600): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6600): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6600): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6600): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  847): Process com.google.android.gms:car (pid 6281) has died
,V/JNIHelp ( 6600): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6600): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6600): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1f100457: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6600): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6600): GMSCore installation verified
,I/ConfigStore( 6600): Config Database version: 1
,I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 16:40:49.204 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1377): mWifiConnected = false, mWifiLevel = 0
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServerServiceExt(  847): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  847): setSupplicantStateFOUR_WAY_HANDSHAKE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 16:40:49.208 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1377): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1377): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1377): Remote
I/[SystemUI]StatusBar.NetworkController( 1377): mWifiConnected = false, mWifiLevel = 0
I/wpa_supplicant( 2715): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2715): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiServerServiceExt(  847): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  847): setSupplicantStateGROUP_HANDSHAKE
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 4
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1377): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1377): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1377): Remote
I/WifiServiceExtension(  847): setVHTCapabilityType  : false
I/WifiServerServiceExt(  847): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  847): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  847): setSecurityType  : 2
,W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1377): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  847): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  847): Got NetworkAgent Messenger
D/ConnectivityService(  847): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  847): NetworkAgent connected
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 16:40:49.286 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1377): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1377): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1377): Remote
I/[SystemUI]StatusBar.NetworkController( 1377): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-21 16:40:49.29 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
E/WifiConfigStore(  847): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.sys,temui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1377): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1377): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1377): Remote
E/WifiConfigStore(  847): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  277): Setting iface cfg
E/WifiStateMachine(  847): Start Dhcp Watchdog 2
D/DhcpStateMachine(  847): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  847): WaitBeforeStartState
D/ConnectivityService(  847): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,D/LGWifiP2pService(  847): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@61b7016 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@61b7016 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  847): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  847): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  847): Current State is mWaitBeforeStartState.
,D/DhcpStateMachine(  847): DHCP Start wake lock is acquired.
V/LgDhcpStateMachineHelper(  847): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/CommandListener(  277): Setting iface cfg
I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  277): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  847): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  847): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  847): setSupplicantStateCOMPLETED
,D/WifiServerServiceExt(  847): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  847): setSupplicantStateCOMPLETED
D/ConnectivityService(  847): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  847): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  847): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,E/WifiStateMachine(  847): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  847): ignoring duplicate network state non-change
I/[SystemUI]StatusBar.NetworkController( 1377): mWifiConnected = false, mWifiLevel = 0
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  847): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  847): Adding iface wlan0 to network 101
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-21 16:40:49.471 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-21 16:40:49.474 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]QuickSettingsHandler( 1377): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1377): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1377): Remote
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/[SystemUI]StatusBar.NetworkController( 1377): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
E/WifiStateMachine(  847): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1377): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1377): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1377): Remote
D/WifiHS20(  847): [PASSPOINT] passpointNotification: hs20AP list is checked
E/ConnectivityService(  847): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  847): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  847): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
I/[SystemUI]StatusBar.NetworkController( 1377): mWifiConnected = true, mWifiLevel = 2
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-21 16:40:49.489 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Netd    (  277): netlink response contains error (File exists)
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System ,to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  847): [PASSPOINT] passpointNotification: hs20AP list is checked
D/ConnectivityService(  847): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  847): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  847): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  847): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-21 16:40:49.494 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/Nat464Xlat(  847): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  847): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  847): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  847): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  847):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  847):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  847):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
I/[SystemUI]QuickSettingsHandler( 1377): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1377): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1377): Remote
I/[SystemUI]StatusBar.NetworkController( 1377): mWifiConnected = true, mWifiLevel = 2
D/ConnectivityService(  847):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  847):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  847): currentScore = 0, newScore = 20
D/ConnectivityService(  847):    accepting network in place of null
D/ConnectivityService(  847): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/TelephonyNetworkFactory-1( 1755): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1755):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1377): Got action android.net.wifi.STATE_CHANGE at null
D/WIFI    (  847): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  847):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/[SystemUI]QuickSettingsHandler( 1377): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1377): Remote
E/ConnectivityService(  847): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  847): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  847): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  847): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1840): |CORE| No family connected
I/QCNEJ   ( 1840): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/ConnectivityService(  847): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  847): [e] list.add(nai) empty : false size: 1
I/QCNEJ   ( 1840): |CORE| sendDefaultNwMsg: default = 1
D/ConnectivityService(  847): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  847): validation of new default Network = false
D/ConnectivityService(  847): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  847): enableDataServiceNotify 
D/DSQN    (  847): start dsqn bin
D/TelephonyIcons( 1377): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1377): updateLGTelephonySignalStrength : !hasService()
D/ConnectivityService(  847): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  847):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/ConnectivityService(  847):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  847): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1377): CM callback handler got msg 524290
I/DSQN    ( 6650): DSQN samuel.seo ver 141203
E/DSQN    ( 6650): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6650): created command queue thread
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/DSQN    ( 6650): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6650): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,I/art     (  847): Explicit concurrent mark sweep GC freed 61829(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 12.804ms total 280.498ms
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): [LWD] Start DNSResolver start to wait
V/NetworkPolicy(  847): [LG_RESTRICTED] checkMobilePolicy_type()
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): [LWD] wait 500ms before dns check
D/DhcpStateMachine(  847): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper(  847): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  847): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/MediaRouter( 6600): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
I/dhcpcd  ( 6655): version 5.5.6 starting
V/MusicLeanback( 6600): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
E/dhcpcd  ( 6655): get_duid: Read-only file system
,I/NetworkMonitor( 6600): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6600): type=WIFI subType= reason=null isConnected=true
,I/dhcpcd  ( 6655): wlan0: rebinding lease of 192.168.1.134
,I/ActivityManager(  847): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6664 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6600): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6600): Using platform SSLCertificateSocketFactory
,I/NotificationManager( 6600): com.google.android.music: cancel(1061) by com.google.android.music
,W/ResourcesManager( 6664): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6664): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6664): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  847): Process com.google.android.talk (pid 6554) has died
,I/LGEmail ( 6664): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): [LWD] DNSResolver start dns
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  277): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/LGEmail ( 6664): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/libc-netbsd(  277): res_queryN name = xxxxx succeed
,I/System.out(  847): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/DSQN    ( 6650): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6650): restart monitoring
,I/DSQN    ( 6650): dsqn report finish
D/LGDataListener(  277): argv[0]=dsqncommand
D/LGDataListener(  277): argv[1]=wlan0
D/LGDataListener(  277): argv[2]=1
D/LGDataListener(  277): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  847): DSQM DsqnNotification wlan0  1
D/DSQN    (  847): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 21 Jan 2016 15:40:50 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453390850239], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453390850216]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): Validated
D/ConnectivityService(  847): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  847): rematching NetworkAgentInfo [WIFI () - 101]
D/WifiDataContinuityService(  847): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
D/ConnectivityService(  847):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  847):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  847):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  847): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  847): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  847):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  847):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  847): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  847): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  847): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1377): CM callback handler got msg 524290
I/WifiServerServiceExt(  847): set CMD_CAPTIVE_CHECK_COMPLETED
D/WIFI    (  847): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  847):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1755): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1755):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/TelephonyIcons( 1377): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1377): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/eas_req ( 6664): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  847): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6692 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/ConnectivityService(  847): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/HubEmail( 6664): JNI_OnLoad()
I/HubEmail( 6664): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6664): registerNatives()
I/HubEmail( 6664): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6664): registerNativeMethods()
I/HubEmail( 6664): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6664): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6664): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 6692): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6692): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6692): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6692): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,D/LGDMClient( 6692): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6692): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6692): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6692): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  847): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6719 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6692): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6692): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6692): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6692): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMClient( 6692): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6692): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/dhcpcd  ( 6655): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/AppUp4:AppBoxCP( 6719): onCreate
W/AppUp4:DB( 6719):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6719):  setFingerPrint start
I/AppUp4:DB( 6719):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6719):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6719):  SDK version = 0
,I/AppUp4:DB( 6719):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6719): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6719): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6719): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6719): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6719): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6719): onReceive
,I/AppUp4:CustModeStarterReceiver( 6719): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6719): Context : android.app.ReceiverRestrictedContext@218fd9cb
D/AppUp4:CustFacade( 6719): isCustomizationCompleted : false
I/dhcpcd  ( 6655): wlan0: leased 192.168.1.134 for 86400 seconds
D/AppUp4:CustFacade( 6719): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6719): begin check event
I/AppUp4:CustModeStarterReceiver( 6719): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6719): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6719): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6719): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6719): handleAsyncCustNotification do not startCustService
I/ActivityManager(  847): Killing 6404:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/libprocessgroup(  847): failed to open /acct/uid_10014/pid_6404/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3167): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3167): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3167): networkInfo.isConnected() = false
I/ActivityManager(  847): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6752 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/Netd    (  277): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  847): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  847): identical MTU - not setting
D/Nat464Xlat(  847): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  847): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  847):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  847):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  847): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  847): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  847): enableDataServiceNotify 
D/DSQN    (  847): start dsqn bin
D/ConnectivityManager.CallbackHandler( 1377): CM callback handler got msg 524295
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-21 16:40:51.099 DNS addrs= 192.168.1.1, 0.0.0.0, 
,D/DSQN    (  847): dsqn is running restart
I/DSQN    ( 6780): DSQN samuel.seo ver 141203
E/DSQN    ( 6780): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6780): created command queue thread
,I/DSQN    ( 6780): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6780): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/PhoneMonitor( 6752): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6752): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6752): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  847): Killing 6480:com.android.settings/1000 (adj 15): empty #11
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  847): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  847): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  847): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  847): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  847): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  847): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  847): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  847): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  847): RunningState
,W/libprocessgroup(  847): failed to open /acct/uid_1000/pid_6480/cgroup.procs: No such file or directory
,D/PhoneMonitor( 6752): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 6752): [loadFeatureFromXml] *** start feature loading from xml
V/DownloadManager( 3191): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/TelephonyAutoProfiling( 6752): [parse] Load xml
V/DownloadManager( 3191): DownloadService onCreate
V/TelephonyAutoProfiling( 6752): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6752): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
I/DownloadManager( 3191): in removeSpuriousFiles
I/NotificationManager( 3191): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,V/DownloadManager( 3191): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/PhoneMonitor( 6752): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
V/DownloadManager( 3191): created cursor android.database.sqlite.SQLiteCursor@14a0639e on behalf of 3191
I/DownloadManager( 3191): in trimDatabase
V/DownloadManager( 3191): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3191): created cursor android.database.sqlite.SQLiteCursor@b8dfe4c on behalf of 3191
I/ActivityManager(  847): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6793 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/DownloadManager( 3191): DownloadService onStartCommand
V/DownloadManager( 3191): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3191): created cursor android.database.sqlite.SQLiteCursor@2b1baa on behalf of 3191
I/CheckinService( 5691): Checkin interval check for package: unspecified last checkin: 1453390825187 min interval config: 0 actual interval: 26271
,I/CheckinService( 5691): Disabling old GoogleServicesFramework version
,D/WeatherAncestor( 2819): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:40:51
,D/UpdateThreadPoolManager( 2819): 2 : This is isUpdating : false
D/WeatherAncestor( 2819): connectivity changed - connection : true
D/Weather_cast( 2819): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2819): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:40:51
D/WeatherService( 2819): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  847): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6816 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  847): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2819): 2 : Utils getTopActivity com.lge.launcher2 / true
V/DownloadManager( 3191): DownloadService onDestroy
,D/WeatherService( 2819): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2819): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/CheckinService( 5691): Checking schedule, now: 1453390851662 next: 1453390855138
I/CheckinService( 5691): active receiver: disabled
,V/AlarmManager(  847): ELAPSED_WAKEUP set : Alarm{22ccc95 type 2 when 107882 com.google.android.gms} when 107882
,I/ActivityManager(  847): Killing 6511:com.lge.sync/1000 (adj 15): empty #11
,W/ResourcesManager( 6816): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/libprocessgroup(  847): failed to open /acct/uid_1000/pid_6511/cgroup.procs: No such file or directory
,I/Babel_SMS( 6816): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6816): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6816): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6816): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6816): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6816): MmsConfig.loadFromResources
E/Babel_SMS( 6816): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6816): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,I/art     ( 6816): CheckpointMarkThreadRoots callback created = 0xb042d800
,D/SensorManager( 6816): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6816): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6816): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6816): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6816): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6816): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6816): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6816): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6816): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6816): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6816): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6816): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6816): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6816): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6816): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6816): found sensor: Motion Accel, handle=46
I/art     ( 6816): CheckpointMarkThreadRoots callback created = 0xb042d7f0
,W/Settings( 6816): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6816): startup - clean
,I/Babel   ( 6816): deleted: false for 0
,I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-58 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-21 16:40:52.341 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/jxcore-log( 6346): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6346): 
,I/ActivityManager(  847): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6852 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/art     (  312): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 293us total 20.967ms
I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 313us total 20.341ms
,V/WifiInternetCheck(  847): Single check msg out of sync, ignoring.
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 20.878ms
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/AudioCapabilities( 6816): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6816): Unsupported mime audio/adpcm
W/AudioCapabilities( 6816): Unsupported mime audio/g726
,W/AudioCapabilities( 6816): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6816): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6816): Unsupported mime video/mjpg
,D/ConnectivityService(  847): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  847): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  847): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NetworkMonitor( 6600): type=WIFI subType= reason=null isConnected=true
I/[SystemUI]QuickSettingsHandler( 1377): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  847): onReceive
D/LocSvc_java(  847): got connectivity action
D/LocSvc_java(  847): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
,D/LocSvc_java(  847): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  847): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  847): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  847): ignore wifi update if we are not in OPENING or CLOSING
,D/NetworkChangeNotifierAutoDetect( 1959): Network connectivity changed, type is: 2
W/VideoCapabilities( 6816): Unsupported mime video/theora
,W/AudioCapabilities( 6816): Unsupported mime audio/evrc
,W/AudioCapabilities( 6816): Unsupported mime audio/qcelp
W/VideoCapabilities( 6816): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6816): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6816): Unsupported mime audio/qcelp
W/AudioCapabilities( 6816): Unsupported mime audio/evrc
,W/VideoCapabilities( 6816): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6816): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6816): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6816): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6816): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6816): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6816): onServiceConnected
,W/Babel   ( 6816): Attempted to change video mute state without an active call.
I/NotificationManager( 6816): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6816): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6816): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6816): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6816): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  277): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 6816): propertyValue:false
,D/UEI.SmartControl( 5760): Internal timer expired: 2
,I/DSQN    ( 6780): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6780): restart monitoring
D/LGDataListener(  277): argv[0]=dsqncommand
D/LGDataListener(  277): argv[1]=wlan0
D/LGDataListener(  277): argv[2]=1
D/LGDataListener(  277): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 6780): dsqn report finish
D/DSQN    (  847): DSQM DsqnNotification wlan0  1
D/DSQN    (  847): start to monitor internet connection
I/Babel   ( 6816): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  847): Killing 5760:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 6534): android.os.DeadObjectException
,W/System.err( 6534): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6534): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6534): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6534): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 6534): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6534): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6534): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6534): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6534): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6534): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6534): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6534): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6534): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6534): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6534): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6534): android.os.DeadObjectException
W/System.err( 6534): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6534): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6534): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6534): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 6534): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6534): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6534): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6534): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6534): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6534): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6534): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6534): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6534): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6534): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6534): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  847): failed to open /acct/uid_10089/pid_5760/cgroup.procs: No such file or directory
W/ActivityManager(  847): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,I/ActivityManager(  847): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6883 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 6883): Quickset Services start...
,I/UEI.SmartControl( 6883): Manufacture = LGE
,D/UEI.SmartControl( 6883): File observer start...
E/UEI.SmartControl( 6883): IR Port is disabled: false
D/UEI.SmartControl( 6883): Starting file observer...
D/UEI.SmartControl( 6883): Extracting JNI libs...
D/UEI.SmartControl( 6883): --- this system supports 32-bit or 64-bit only
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6852): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6852): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6852): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6852): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6852): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6852):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6852):   adb logcat -s GAv4
W/GAv4    ( 6852): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6852): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6852): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/ActivityManager(  847): Process com.google.android.music:main (pid 6600) has died
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/UEI.SmartControl( 6883): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6883): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6883): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/jxcore-log( 6346): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6346): 
I/jxcore-log( 6346): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6346): 
I/UEI.SmartControl( 6883): --- Selecting new region: 2
I/UEI.SmartControl( 6883): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6883): Platform has CIR...
D/UEI.SmartControl( 6883): NO CIR support, need to check package...
I/UEI.SmartControl( 6883): Model: LG-D722 uses JNI
,D/UEI.SmartControl( 6883): QS Service created
E/UEI.SmartControl( 6883): QS start get config
,I/WebViewFactory( 6852): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  277): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
I/jxcore-log( 6346): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6346): 
,D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out(  847): propertyValue:false
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  277): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out(  847): propertyValue:false
,I/LibraryLoader( 6852): Time to load native libraries: 3 ms (timestamps 9928-9931)
I/LibraryLoader( 6852): Expected native library version number "",actual native library version number ""
D/UEI.SmartControl( 6883): Loading JNI Libs...
D/UEI.SmartControl( 6883):  configuring local db...
V/WebViewChromiumFactoryProvider( 6852): Binding Chromium to main looper Looper (main, tid 1) {1db3927c}
I/LibraryLoader( 6852): Expected native library version number "",actual native library version number ""
I/chromium( 6852): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6852): Initializing chromium process, singleProcess=true
W/art     ( 6852): Attempt to remove local handle scope entry from IRT, ignoring
,I/jxcore-log( 6346): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6346): 
E/SysUtils( 6852): ApplicationContext is null in ApplicationStatus
I/jxcore-log( 6346): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6346): 
,W/chromium( 6852): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
I/jxcore-log( 6346): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6346): 
V/WifiInternetCheck(  847): isHttpConnectionAvailable - We got a valid response : 204
,E/libEGL  ( 6852): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6852): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6852): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6852): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6852): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6852): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6852): Remote Branch: 
I/Adreno-EGL( 6852): Local Patches: 
I/Adreno-EGL( 6852): Reconstruct Branch: 
V/AudioPolicyService(  282): registerClient() client 0xb4140b00, uid 10079
,W/AudioManagerAndroid( 6852): Requires BLUETOOTH permission
I/NSApplication( 6852): Starting up...
,I/ActivityManager(  847): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6955 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 6883):  ---- Has DB8: true
,D/UEI.SmartControl( 6883): QS start statue = true Error code = 0
D/UEI.SmartControl( 6883): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6883): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6883): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6883): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6883): IrrcClient ++ 
D/irrcClient( 6883): getIrrcService ++ 
,D/irrcClient( 6883): getIrrcService -- 
D/irrcClient( 6883): IrrcClient -- 
W/irrc_jni( 6883): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6883): Services init done
I/UEI.SmartControl( 6883): Device manager: loading config....
D/UEI.SmartControl( 6883): QS Service init finished
D/UEI.SmartControl( 6883): QS Service version name: 0.1.73
D/UEI.SmartControl( 6883): QS Service version code: 1073
D/UEI.SmartControl( 6883): Config is loaded...
,D/UEI.SmartControl( 6883): Service requested: Control
I/ActivityManager(  847): Killing 6534:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 6883): -----IControl: 11
,D/UEI.SmartControl( 6883): Caller: com.lge.qremote
D/UEI.SmartControl( 6883): ------------ IControl registerCallback...
I/UEI.SmartControl( 6883): Registering callback...
D/UEI.SmartControl( 6883):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6883): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 6883): Internal service binding...
W/libprocessgroup(  847): failed to open /acct/uid_10106/pid_6534/cgroup.procs: No such file or directory
I/ActivityManager(  847): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6980 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  847): Killing 6664:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  847): failed to open /acct/uid_10021/pid_6664/cgroup.procs: No such file or directory
,W/ResourcesManager( 6980): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  847): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6997 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  847): RTC_WAKEUP set : Alarm{d8cb374 type 0 when 1453390854575 com.android.vending} when 1453390854575
,D/Finsky  ( 6997): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6997): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6997): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6997): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6997): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3191): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3191): created cursor android.database.sqlite.SQLiteCursor@29c2b338 on behalf of 6997
D/Ads     ( 6997): Skipping gmscore version check
D/Finsky  ( 6997): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6997): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 6997): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 6997): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/Finsky  ( 6997): [865] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6997): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  847): Killing 6692:com.lge.lgdmsclient/1000 (adj 15): empty #11
,I/iu.SyncManager( 5691): SYNC; picasa accounts
,W/libprocessgroup(  847): failed to open /acct/uid_1000/pid_6692/cgroup.procs: No such file or directory
,D/NetworkLogImpl( 5691): Loaded NetworkSpeedPredictor
I/iu.Environment( 5691): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/ActivityManager(  847): Killing 6719:com.lge.appbox.client/u0a11 (adj 15): empty #11
I/iu.UploadsManager( 5691): num queued entries: 0
,I/iu.UploadsManager( 5691): num updated entries: 0
I/iu.SyncManager( 5691): NEXT; no task
W/libprocessgroup(  847): failed to open /acct/uid_10011/pid_6719/cgroup.procs: No such file or directory
,I/ActivityManager(  847): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7060 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  847): Explicit concurrent mark sweep GC freed 46115(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.149ms total 189.665ms
,I/MusicStore( 7060): Database version: 120
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7060): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7060): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files,
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7060): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,W/ResourcesManager( 7060): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7060): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7060): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,V/AlarmManager(  847): RTC_WAKEUP set : Alarm{8897410 type 0 when 1453390855138 com.google.android.gms} when 1453390855138
,W/ActivityThread( 7060): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7060): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1f100457: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7060): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7060): GMSCore installation verified
,I/ConfigStore( 7060): Config Database version: 1
,I/MediaRouter( 7060): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7060): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7060): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7060): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  847): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7097 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7060): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7060): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  847): Killing 6752:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/ResourcesManager( 7097): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7097): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7097): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  847): failed to open /acct/uid_10038/pid_6752/cgroup.procs: No such file or directory
,I/NotificationManager( 7060): com.google.android.music: cancel(1061) by com.google.android.music
I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/LGEmail ( 7097): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,V/AlarmManager(  847): RTC_WAKEUP set : Alarm{39b0d72b type 0 when 1453390857527 com.google.android.googlequicksearchbox} when 1453390857527
D/LGEmail ( 7097): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/ActivityManager(  847): Process com.google.android.apps.magazines (pid 6852) has died
,D/eas_req ( 7097): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  847): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7146 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7097): JNI_OnLoad()
I/HubEmail( 7097): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7097): registerNatives()
I/HubEmail( 7097): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7097): registerNativeMethods()
I/HubEmail( 7097): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7097): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 7097): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 7146): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7146): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 7146): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7146): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7146): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7146): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7146): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 7146): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  847): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7181 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7146): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7146): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 7146): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7146): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7146): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7146): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  847): Killing 6793:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  847): failed to open /acct/uid_10051/pid_6793/cgroup.procs: No such file or directory
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/AppUp4:AppBoxCP( 7181): onCreate
W/AppUp4:DB( 7181):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7181):  setFingerPrint start
,I/AppUp4:DB( 7181):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7181):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7181):  SDK version = 0
I/AppUp4:DB( 7181):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7181): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7181): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7181): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7181): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 7181): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7181): onReceive
I/AppUp4:CustModeStarterReceiver( 7181): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7181): Context : android.app.ReceiverRestrictedContext@218fd9cb
D/AppUp4:CustFacade( 7181): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7181): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7181): begin check event
I/AppUp4:CustModeStarterReceiver( 7181): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7181): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7181): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7181): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7181): handleAsyncCustNotification do not startCustService
I/ActivityManager(  847): Killing 6816:com.google.android.talk/u0a61 (adj 15): empty #11
D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 114804237772; DSPS: 3859721; Offset : -2993139983
,W/libprocessgroup(  847): failed to open /acct/uid_10061/pid_6816/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3167): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3167): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3167): networkInfo.isConnected() = false
I/ActivityManager(  847): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7205 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7205): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7205): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7205): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  847): Killing 6883:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
D/PhoneMonitor( 7205): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7205): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7205): [parse] Load xml
,V/TelephonyAutoProfiling( 7205): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7205): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7205): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
E/libprocessgroup(  847): failed to kill 1 processes for processgroup 6883
,V/DownloadManager( 3191): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3191): DownloadService onCreate
,I/ActivityManager(  847): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7229 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/NotificationManager( 3191): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,I/DownloadManager( 3191): in removeSpuriousFiles
V/DownloadManager( 3191): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,I/CheckinService( 5691): Checkin interval check for package: unspecified last checkin: 1453390825187 min interval config: 0 actual interval: 34053
V/DownloadManager( 3191): created cursor android.database.sqlite.SQLiteCursor@2fd18f11 on behalf of 3191
,I/DownloadManager( 3191): in trimDatabase
V/DownloadManager( 3191): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3191): DownloadService onStartCommand
V/DownloadManager( 3191): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3191): created cursor android.database.sqlite.SQLiteCursor@368bcae4 on behalf of 3191
V/DownloadManager( 3191): created cursor android.database.sqlite.SQLiteCursor@21af0b4d on behalf of 3191
I/CheckinService( 5691): Checking schedule, now: 1453390859282 next: 1453390855138
I/CheckinService( 5691): active receiver: enabled
,I/CheckinService( 5691): Preparing to send checkin request
,I/EventLogService( 5691): Accumulating logs since 1453390815656
,V/DownloadManager( 3191): DownloadService onDestroy
,D/WeatherAncestor( 2819): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:40:59
,D/UpdateThreadPoolManager( 2819): 2 : This is isUpdating : false
D/WeatherAncestor( 2819): connectivity changed - connection : true
D/Weather_cast( 2819): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2819): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:40:59
D/WeatherService( 2819): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  847): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7260 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  847): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2819): 2 : Utils getTopActivity com.lge.launcher2 / true
I/art     (  312): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 20.930ms
,D/WeatherService( 2819): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2819): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 314us total 21.322ms
I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 299us total 20.597ms
,W/ResourcesManager( 7260): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/CheckinRequestBuilder( 5691): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5691): Failed to find provider info for com.google.android.wearable.settings
,I/Babel_SMS( 7260): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7260): MmsConfig.loadMmsSettings
I/Babel_SMS( 7260): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7260): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7260): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7260): MmsConfig.loadFromResources
E/Babel_SMS( 7260): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7260): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 7260): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7260): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7260): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
,D/SensorManager( 7260): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7260): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7260): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7260): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7260): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7260): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7260): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7260): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7260): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7260): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7260): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7260): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7260): found sensor: Motion Accel, handle=46
W/Settings( 7260): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7260): startup - clean
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Babel   ( 7260): deleted: false for 0
I/art     ( 7260): CheckpointMarkThreadRoots callback created = 0xb042d8a0
,I/art     ( 7260): CheckpointMarkThreadRoots callback created = 0xb042d870
,I/ActivityManager(  847): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7292 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicWidget( 2752): mDelayedStopHandler : unbind
W/AudioCapabilities( 7260): Unsupported mime audio/x-lg-flac
,I/[SystemUI]TimeTickManager( 1377): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1377): called onTimeUpdated()
D/WeatherService( 2819): 2 : TimeTick Intent has been received, Time(hour:min:sec) 16:41:0
D/WeatherService( 2819): 2 : TimeTick Intent And Screen On
D/WeatherService( 2819): 2 : SDK version : 21
W/ActivityManager(  847): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2819): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2819): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2819): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2819): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2819): 2 : This is isUpdating : false
D/WeatherService( 2819): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2819): 2 : buildUpdate, appWidgetId: 2
W/AudioCapabilities( 7260): Unsupported mime audio/adpcm
W/AudioCapabilities( 7260): Unsupported mime audio/g726
W/AudioCapabilities( 7260): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7260): Unsupported mime audio/wma-voice
,I/[SystemUI]Clock( 1377): called onTimeUpdated()
D/WeatherTheme( 2819): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2819): 2 : Fixed theme : optimus
I/LgeClockWidgetControlView( 1377): called onTimeUpdated()
I/[SystemUI]DateView( 1377): called onTimeUpdated()
I/[SystemUI]DateView( 1377): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1377): handleTimeUpdate
W/VideoCapabilities( 7260): Unsupported mime video/mjpg
D/WeatherReflect( 2819): 2 : Map key string is -2
,W/VideoCapabilities( 7260): Unsupported mime video/theora
D/lim     ( 2819): 2 : time = 16:41
,I/MusicBrowser( 2115): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
I/MusicBrowser( 2115): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2115): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
I/WeatherReflect( 2819): Model Name : LG-D722
D/WeatherTheme( 2819): 2 : Different view - status_min_formatted : 40 != 41
D/WeatherTheme( 2819): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
,D/WeatherReflect( 2819): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/MusicBrowser( 2115): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2115): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2115): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
D/Theme   ( 2819): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2819): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2819): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2819): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/MusicBrowser( 2115): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2115): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,I/MediaFocusControl(  847):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@2fa1e8d8com.lge.music.MediaPlaybackService$6@bf22431
D/MusicBrowser( 2115): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
,D/Weather4x2_optimus( 2819): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2819): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2819): forecast size is 0
D/Theme   ( 2819): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2819): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2819): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2819): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2819): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2819): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2819): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2819): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2819): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2819): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2819): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2819): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2819): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2819): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2819): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2819): url is : null
I/MusicBrowser( 2115): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2115): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
D/Theme   ( 2819): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2819): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2819): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/MusicBrowser( 2115): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
D/WeatherAncestor( 2819): 2 : update view, appWidgetId: 2
D/WeatherService( 2819): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 16:41:0
I/MusicBrowser( 2115): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@2c047a7
I/MusicBrowser( 2115): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2115): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2115): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2115): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2115): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2115): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2115): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2115): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2115): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2115): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/art     ( 5601): Explicit concurrent mark sweep GC freed 2060(77KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 8.158ms total 58.774ms
W/AudioCapabilities( 7260): Unsupported mime audio/evrc
W/AudioCapabilities( 7260): Unsupported mime audio/qcelp
I/MusicBrowser( 2115): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
W/VideoCapabilities( 7260): Unrecognized profile 2130706433 for video/avc
I/MusicBrowser( 2115): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2115): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2115): reset
,W/AudioCapabilities( 7260): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7260): Unsupported mime audio/qcelp
,W/AudioCapabilities( 7260): Unsupported mime audio/evrc
I/ActivityManager(  847): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7309 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/MediaPlayer[Native]( 2115): setListener
V/MediaPlayer[Native]( 2115): disconnect
V/MediaPlayer[Native]( 2115): destructor
V/AudioFlinger(  282): releasing 19 from 2115 for -1
V/AudioFlinger(  282):  decremented refcount to 0
V/AudioFlinger(  282): purging stale effects
,V/MediaPlayer[Native]( 2115): disconnect
D/MusicBrowser( 2115): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
,I/SmartShareClient( 2115): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2115): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2115): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2115): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2115): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2115): [SmartShareManagerClient] unregisterListener: 201754390
W/SmartShareClient( 2115): [SmartShareManagerClient] unregisterListener invalid listener: 201754390
I/SmartShareClient( 2115): [SmartShareManagerClient] terminate service: 2115/MediaPlaybackService/243817797
W/VideoCapabilities( 7260): Unsupported mime video/mp4v-esdp
I/[LgeWidgetLib]LgeAppWidgetHostView( 1882): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/HomeCloudIF( 2115): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2115): [SmartShareManagerClient] unbindService context:android.app.Application@2cf46897
V/CloudHub( 2115): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2115): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,W/ResourcesManager( 7309): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7309): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/CloudHub( 2115): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2115): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2115): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  847): Killing 6955:com.android.chrome/u0a48 (adj 15): empty #11
,I/VideoCapabilities( 7260): Unsupported profile 4 for video/mp4v-es
I/CloudHub( 2115): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29984
W/VideoCapabilities( 7260): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7260): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7260): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7260): Unrecognized profile 2130706433 for video/avc
E/[LgeWidgetLib]LgeAppWidgetHostView( 1882): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/MultiDex( 7309): VM with version 2.1.0 has multidex support
I/MultiDex( 7309): install
,I/MultiDex( 7309): VM has multidex support, MultiDex support library is disabled.
W/libprocessgroup(  847): failed to open /acct/uid_10048/pid_6955/cgroup.procs: No such file or directory
,I/vclib   ( 7260): onServiceConnected
W/Babel   ( 7260): Attempted to change video mute state without an active call.
,D/libc-netbsd( 7260): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7260): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7260): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7260): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  277): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
,I/System.out( 7260): propertyValue:false
I/NotificationManager( 7260): com.google.android.talk: cancel(10436) by com.google.android.talk
V/JNIHelp ( 7309): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7292): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 7292): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7292):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7292):   adb logcat -s GAv4
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7292): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7292): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
W/GAv4    ( 7292): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7292): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/ActivityThread( 7309): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/GAv4    ( 7292): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/System  ( 7309): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@b8dfe4c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7309): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 7309): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7309): com.google.android.gms: cancel(39789) by com.google.android.gms
W/GAv4    ( 7292): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/art     ( 7309): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7309): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/Babel   ( 7260): connection state changed from UNKNOWN to CONNECTED
,I/art     (  847): Explicit concurrent mark sweep GC freed 15187(749KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.248ms total 151.747ms
,I/ActivityManager(  847): Killing 6980:com.google.android.apps.plus/u0a86 (adj 15): empty #11
D/NativeLibraryUtils( 7309): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  847): failed to open /acct/uid_10086/pid_6980/cgroup.procs: No such file or directory
,D/WVCdm   (  282): Instantiating CDM.
,I/WVCdm   (  282): CdmEngine::OpenSession
I/WVCdm   (  282): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  282): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  282): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  282): L1 library not specified. Falling Back to L3
,I/WVCdm   (  282): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  282): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  282): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  282): CdmEngine::GenerateKeyRequest
D/WVCdm   (  282): PrepareKeyRequest: nonce=3642477245
I/WebViewFactory( 7292): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/ActivityManager(  847): Process com.google.android.music:main (pid 7060) has died
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/LibraryLoader( 7292): Time to load native libraries: 15 ms (timestamps 7739-7754)
,I/LibraryLoader( 7292): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7292): Binding Chromium to main looper Looper (main, tid 1) {1db3927c}
I/LibraryLoader( 7292): Expected native library version number "",actual native library version number ""
I/chromium( 7292): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7292): Initializing chromium process, singleProcess=true
W/art     ( 7292): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7292): ApplicationContext is null in ApplicationStatus
W/chromium( 7292): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7292): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7292): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7292): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7292): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7292): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7292): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7292): Remote Branch: 
I/Adreno-EGL( 7292): Local Patches: 
I/Adreno-EGL( 7292): Reconstruct Branch: 
I/art     ( 7309): CheckpointMarkThreadRoots callback created = 0xb04caec0
,V/AudioPolicyService(  282): registerClient() client 0xb4027880, uid 10079
,I/NSApplication( 7292): Starting up...
W/AudioManagerAndroid( 7292): Requires BLUETOOTH permission
,I/art     ( 7309): CheckpointMarkThreadRoots callback created = 0xb04caeb0
I/ActivityManager(  847): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7373 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/WVCdm   (  282): CdmEngine::OpenSession
,I/ActivityManager(  847): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7394 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  847): Killing 6997:com.android.vending/u0a36 (adj 15): empty #11
,W/libprocessgroup(  847): failed to open /acct/uid_10036/pid_6997/cgroup.procs: No such file or directory
,W/ResourcesManager( 7394): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  847): Killing 7097:com.lge.email/u0a21 (adj 15): empty #11
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,W/libprocessgroup(  847): failed to open /acct/uid_10021/pid_7097/cgroup.procs: No such file or directory
,I/ActivityManager(  847): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=7421 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,W/ResourcesManager( 7421): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7421): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7421): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7421): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7421): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/IndexDatabaseHelper( 7421): Using schema version: 115
,I/IndexDatabaseHelper( 7421): Index is fine
V/WiFiOffLoadBroadcast( 7421): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7421): MCCMNC not supported: null
I/ActivityManager(  847): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7439 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  847): Killing 7146:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  847): failed to open /acct/uid_1000/pid_7146/cgroup.procs: No such file or directory
,I/WVCdm   (  282): CdmEngine::CloseSession
,I/WVCdm   (  282): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  282): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  282): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  282): CdmEngine::GenerateKeyRequest
I/ActivityManager(  847): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7459 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager(  847): Killing 7181:com.lge.appbox.client/u0a11 (adj 15): empty #11
D/WVCdm   (  282): PrepareKeyRequest: nonce=3241037811
,W/libprocessgroup(  847): failed to open /acct/uid_10011/pid_7181/cgroup.procs: No such file or directory
W/ResourcesManager( 7459): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  847): Message: 20
D/BluetoothManagerService(  847): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@27e7b4a7:true
,D/BluetoothAdapterService(499726438)( 2006): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@196719ec
,D/BluetoothAdapterService(499726438)( 2006): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@196719ec
V/WiFiOffLoadBroadcast( 7421): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7421): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 7421): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7421): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 7421): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7421): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 7421): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7421): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 7421): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7421): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 7421): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7421): MCCMNC not supported: null
I/PCSuite ( 7439): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 7439): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7421): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7421): MCCMNC not supported: null
I/PCSuite ( 7439): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 7439): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/GCM     ( 1735): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
,I/ActivityManager(  847): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7487 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 1735): propertyValue:false
,I/jxcore-log( 6346): Test app app.js loaded
I/jxcore-log( 6346): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6346): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 6346): BLE advertisement is supported
I/jxcore-log( 6346): 
I/chromium( 6346): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/MusicStore( 7487): Database version: 120
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7487): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7487): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7487): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7487): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7487): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7487): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7487): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1f100457: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7487): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7487): GMSCore installation verified
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  847): Process com.google.android.talk (pid 7260) has died
I/ConfigStore( 7487): Config Database version: 1
,I/MediaRouter( 7487): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7487): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7487): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7487): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  847): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7520 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7487): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7487): Using platform SSLCertificateSocketFactory
,I/NotificationManager( 7487): com.google.android.music: cancel(1061) by com.google.android.music
,W/ResourcesManager( 7520): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7520): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7520): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/LGEmail ( 7520): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7520): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7520): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  847): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7544 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7520): JNI_OnLoad()
I/HubEmail( 7520): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7520): registerNatives()
I/HubEmail( 7520): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7520): registerNativeMethods()
I/HubEmail( 7520): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7520): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  847): Killing 7229:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  847): failed to open /acct/uid_10051/pid_7229/cgroup.procs: No such file or directory
,W/Settings( 7520): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 7544): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7544): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7544): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7544): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7544): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,I/WVCdm   (  282): CdmEngine::CloseSession
I/WVCdm   (  282): L3 Terminate.
D/LGDMClient( 7544): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7544): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/ActivityManager(  847): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7569 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/art     (  312): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 21.041ms
,I/LGDMClient( 7544): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 22.590ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 20.800ms
,W/ContextImpl( 7544): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7544): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7544): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7544): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMClient( 7544): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7544): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  847): Killing 2115:com.lge.music/u0a28 (adj 15): empty #11
V/AudioFlinger(  282): 2115 died, releasing its sessions
V/AudioFlinger(  282):  pid 1755 @ 0
V/AudioFlinger(  282):  pid 3167 @ 1
V/AudioFlinger(  282):  pid 3167 @ 2
,I/AppUp4:AppBoxCP( 7569): onCreate
,W/AppUp4:DB( 7569):  [AppBoxDatabaseHelper] construct
W/libprocessgroup(  847): failed to open /acct/uid_10028/pid_2115/cgroup.procs: No such file or directory
I/AppUp4:DB( 7569):  setFingerPrint start
I/AppUp4:DB( 7569):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7569):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7569):  SDK version = 0
,I/AppUp4:DB( 7569):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7569): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7569): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7569): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7569): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7569): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7569): onReceive
I/AppUp4:CustModeStarterReceiver( 7569): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 7569): Context : android.app.ReceiverRestrictedContext@218fd9cb
D/AppUp4:CustFacade( 7569): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7569): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7569): begin check event
I/AppUp4:CustModeStarterReceiver( 7569): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7569): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7569): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7569): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7569): handleAsyncCustNotification do not startCustService
I/ActivityManager(  847): Killing 7292:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
I/dex2oat ( 7587): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=40 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/LgeMiscReceiver( 3167): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3167): action = android.net.conn.CONNECTIVITY_CHANGE
W/libprocessgroup(  847): failed to open /acct/uid_10079/pid_7292/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3167): networkInfo.isConnected() = true
,D/PhoneState( 3167): setPdpRejectCasuse : false
D/MobileConnectivityChangeReceiver( 7205): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7205): onReceive CONNECTIVITY_CHANGE networkType=1
V/DownloadManager( 3191): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3191): DownloadService onCreate
I/DownloadManager( 3191): in removeSpuriousFiles
I/NotificationManager( 3191): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3191): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3191): created cursor android.database.sqlite.SQLiteCursor@322e0b13 on behalf of 3191
,I/DownloadManager( 3191): in trimDatabase
V/DownloadManager( 3191): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3191): created cursor android.database.sqlite.SQLiteCursor@36e0f49 on behalf of 3191
I/ActivityManager(  847): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7598 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3191): DownloadService onStartCommand
V/DownloadManager( 3191): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3191): created cursor android.database.sqlite.SQLiteCursor@2f64456f on behalf of 3191
I/dex2oat ( 7587): dex2oat took 104.129ms (threads: 4)
,I/Adreno-EGL( 7309): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7309): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7309): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7309): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7309): Remote Branch: 
I/Adreno-EGL( 7309): Local Patches: 
I/Adreno-EGL( 7309): Reconstruct Branch: 
,V/DownloadManager( 3191): DownloadService onDestroy
,I/ActivityManager(  847): Killing 7373:com.android.chrome/u0a48 (adj 15): empty #11
W/libprocessgroup(  847): failed to open /acct/uid_10048/pid_7373/cgroup.procs: No such file or directory
D/WeatherAncestor( 2819): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:41:6
,D/UpdateThreadPoolManager( 2819): 2 : This is isUpdating : false
D/WeatherAncestor( 2819): connectivity changed - connection : true
D/Weather_cast( 2819): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2819): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:41:6
,D/WeatherService( 2819): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
D/charger_monitor(  492): init target 500000
I/ActivityManager(  847): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7621 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  847): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2819): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/KeyguardUpdateMonitor( 1377): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/WeatherService( 2819): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2819): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/[SystemUI]LGPowerUI( 1377): onReceive = com.lge.android.intent.action.BATTERYEX
D/charger_monitor(  492): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[SystemUI]LGPowerUI( 1377): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/Adreno-EGL( 7309): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7309): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7309): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7309): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7309): Remote Branch: 
I/Adreno-EGL( 7309): Local Patches: 
I/Adreno-EGL( 7309): Reconstruct Branch: 
I/[SystemUI]LGPowerUI( 1377): On Skip Timer : true
D/KeyguardUpdateMonitor( 1377): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/[SystemUI]LGPowerUI( 1377): onReceive = android.intent.action.BATTERY_CHANGED
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1377): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2006): Disconnected process message: 10, size: 0
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  847): battery changed pluggedType: 2
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]BatterySaverHandler( 1377): onReceive = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1377): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
I/[SystemUI]LGPowerUI( 1377): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1377): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2006): Disconnected process message: 10, size: 0
D/WifiController(  847): battery changed pluggedType: 2
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]BatterySaverHandler( 1377): onReceive = android.intent.action.BATTERY_CHANGED
W/ResourcesManager( 7621): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Adreno-EGL( 7309): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7309): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7309): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7309): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7309): Remote Branch: 
I/Adreno-EGL( 7309): Local Patches: 
I/Adreno-EGL( 7309): Reconstruct Branch: 
,I/Babel_SMS( 7621): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7621): MmsConfig.loadMmsSettings
,I/art     ( 7621): CheckpointMarkThreadRoots callback created = 0xb042d4f0
,I/art     (  847): Explicit concurrent mark sweep GC freed 19596(941KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.815ms total 155.982ms
,I/Babel_SMS( 7621): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7621): MmsConfig.loadFromDatabase
I/art     ( 7621): CheckpointMarkThreadRoots callback created = 0xb042d4e0
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/CheckinRequestBuilder( 5691): Classify the device as Phone.
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,E/Babel_SMS( 7621): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7621): MmsConfig.loadFromResources
E/Babel_SMS( 7621): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7621): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7621): found sensor: LGE Accelerometer Sensor, handle=0
,D/SensorManager( 7621): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7621): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7621): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7621): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7621): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7621): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7621): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7621): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7621): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7621): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7621): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7621): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7621): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7621): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7621): found sensor: Motion Accel, handle=46
D/libc-netbsd( 5691): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5691): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Settings( 7621): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/libc-netbsd( 5691): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5691): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
I/Babel_Crash( 7621): startup - clean
I/Babel   ( 7621): deleted: false for 0
,I/ActivityManager(  847): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7653 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 7621): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7621): Unsupported mime audio/adpcm
W/AudioCapabilities( 7621): Unsupported mime audio/g726
W/AudioCapabilities( 7621): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 7621): Unsupported mime audio/wma-voice
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 5691): propertyValue:false
W/VideoCapabilities( 7621): Unsupported mime video/mjpg
W/VideoCapabilities( 7621): Unsupported mime video/theora
,W/AudioCapabilities( 7621): Unsupported mime audio/evrc
,W/AudioCapabilities( 7621): Unsupported mime audio/qcelp
W/VideoCapabilities( 7621): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7621): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7621): Unsupported mime audio/qcelp
W/AudioCapabilities( 7621): Unsupported mime audio/evrc
W/VideoCapabilities( 7621): Unsupported mime video/mp4v-esdp
,I/ActivityManager(  847): Process com.google.android.music:main (pid 7487) has died
I/VideoCapabilities( 7621): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7621): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7621): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7621): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7621): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7621): onServiceConnected
,W/Babel   ( 7621): Attempted to change video mute state without an active call.
,I/NotificationManager( 7621): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 7621): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7621): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7621): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7621): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  277): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 7621): propertyValue:false
D/libc-netbsd( 5691): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5691): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7653): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7653): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7653): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7653): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 7653): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7653):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7653):   adb logcat -s GAv4
,W/GAv4    ( 7653): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7653): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7653): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
D/libc-netbsd( 5691): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5691): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5691): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5691): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Babel   ( 7621): connection state changed from UNKNOWN to CONNECTED
I/CheckinTask( 5691): Sending checkin request (9686 bytes)
,I/WebViewFactory( 7653): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-54 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-21 16:41:07.397 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/LibraryLoader( 7653): Time to load native libraries: 3 ms (timestamps 3592-3595)
I/LibraryLoader( 7653): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7653): Binding Chromium to main looper Looper (main, tid 1) {1db3927c}
I/LibraryLoader( 7653): Expected native library version number "",actual native library version number ""
I/chromium( 7653): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7653): Initializing chromium process, singleProcess=true
,W/art     ( 7653): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7653): ApplicationContext is null in ApplicationStatus
I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
W/chromium( 7653): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7653): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7653): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7653): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7653): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7653): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7653): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7653): Remote Branch: 
I/Adreno-EGL( 7653): Local Patches: 
I/Adreno-EGL( 7653): Reconstruct Branch: 
V/AudioPolicyService(  282): registerClient() client 0xb4027780, uid 10079
,W/AudioManagerAndroid( 7653): Requires BLUETOOTH permission
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/NSApplication( 7653): Starting up...
,I/ActivityManager(  847): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7719 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  847): Killing 7394:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  847): failed to open /acct/uid_10086/pid_7394/cgroup.procs: No such file or directory
,I/ActivityManager(  847): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7738 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  847): Killing 7421:com.android.settings/1000 (adj 15): empty #11
W/libprocessgroup(  847): failed to open /acct/uid_1000/pid_7421/cgroup.procs: No such file or directory
,W/ResourcesManager( 7738): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 5691): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 5691): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinRequestBuilder( 5691): Classify the device as Phone.
,I/CheckinTask( 5691): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5691): Checking schedule, now: 1453390868108 next: 1453918117104
I/CheckinService( 5691): active receiver: disabled
,I/ActivityManager(  847): Killing 7439:com.lge.sync/1000 (adj 15): empty #11
D/CheckinService( 5691): Recording last checkin time for package unspecified as 1453390868146
,W/libprocessgroup(  847): failed to open /acct/uid_1000/pid_7439/cgroup.procs: No such file or directory
,I/ActivityManager(  847): Killing 7544:com.lge.lgdmsclient/1000 (adj 15): empty #11
,I/ActivityManager(  847): Killing 7520:com.lge.email/u0a21 (adj 15): empty #12
,W/libprocessgroup(  847): failed to open /acct/uid_1000/pid_7544/cgroup.procs: No such file or directory
,W/libprocessgroup(  847): failed to open /acct/uid_10021/pid_7520/cgroup.procs: No such file or directory
I/CheckinService( 5691): Checkin interval check for package: unspecified last checkin: 1453390868146 min interval config: 0 actual interval: 121
,I/CheckinService( 5691): Checking schedule, now: 1453390868279 next: 1453918117104
I/CheckinService( 5691): active receiver: disabled
W/ContextImpl( 3599): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,D/WearableService( 1735): callingUid 10006, callindPid: 1735
,D/AuthorizationBluetoothService( 1735): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 5691): Restart initialization of location
E/MDM     ( 1735): [84] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1735): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1735): No location to return for getLastLocation()
W/FusedLocationProvider( 1735): location=null
,I/ActivityManager(  847): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7788 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7459): Create singleton instance
,D/UEI.SmartControl( 7788): Quickset Services start...
,I/UEI.SmartControl( 7788): Manufacture = LGE
,D/UEI.SmartControl( 7788): File observer start...
E/UEI.SmartControl( 7788): IR Port is disabled: false
D/UEI.SmartControl( 7788): Starting file observer...
D/UEI.SmartControl( 7788): Extracting JNI libs...
D/UEI.SmartControl( 7788): --- this system supports 32-bit or 64-bit only
I/AudioManager( 7459): getMode name:com.lge.qremote
,V/SetupWizard( 7205): Connected to Gservices successfully
,D/GCM     ( 1735): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1735): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/UEI.SmartControl( 7788): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7788): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7788): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7788): --- Selecting new region: 2
,I/UEI.SmartControl( 7788): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7788): Platform has CIR...
D/UEI.SmartControl( 7788): NO CIR support, need to check package...
,I/UEI.SmartControl( 7788): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7788): QS Service created
E/UEI.SmartControl( 7788): QS start get config
,D/UEI.SmartControl( 7788): Loading JNI Libs...
,D/UEI.SmartControl( 7788):  configuring local db...
D/UEI.SmartControl( 7788):  ---- Has DB8: true
,D/UEI.SmartControl( 7788): QS start statue = true Error code = 0
D/UEI.SmartControl( 7788): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7788): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7788): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7788): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7788): IrrcClient ++ 
D/irrcClient( 7788): getIrrcService ++ 
,D/irrcClient( 7788): getIrrcService -- 
D/irrcClient( 7788): IrrcClient -- 
W/irrc_jni( 7788): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7788): Services init done
I/UEI.SmartControl( 7788): Device manager: loading config....
D/UEI.SmartControl( 7788): QS Service init finished
,D/UEI.SmartControl( 7788): QS Service version name: 0.1.73
D/UEI.SmartControl( 7788): Config is loaded...
D/UEI.SmartControl( 7788): QS Service version code: 1073
D/UEI.SmartControl( 7788): Service requested: Control
D/UEI.SmartControl( 7788): Internal service binding...
D/UEI.SmartControl( 7788): -----IControl: 11
D/UEI.SmartControl( 7788): Caller: com.lge.qremote
D/UEI.SmartControl( 7788): ------------ IControl registerCallback...
,I/UEI.SmartControl( 7788): Registering callback...
D/UEI.SmartControl( 7788): -----IControl: 19
D/UEI.SmartControl( 7788): Caller: com.lge.qremote
I/UEI.SmartControl( 7788): Registering Services Ready callback...
I/UEI.SmartControl( 7788): Notify client services are ready...
D/UEI.SmartControl( 7788): -----IControl: 8
D/UEI.SmartControl( 7788):  ----- QS SDK is ready!!!
,D/UEI.SmartControl( 7788): Caller: com.lge.qremote
I/UEI.SmartControl( 7788): Notify AllClients services are ready: 0
I/AudioManager( 7459): getMode name:com.lge.qremote
I/AudioManager( 7459): getMode name:com.lge.qremote
,I/AudioManager( 7459): getMode name:com.lge.qremote
,I/[SystemUI]QPairHandler( 1377): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[SystemUI]QSlideListController( 1377): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1840): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/[SystemUI]QSlideLoader( 1377): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1377): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,I/InputReader(  847): Reconfiguring input devices.  changes=0x00000010
W/[SystemUI]QSlideLoader( 1377): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1377): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1377): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1377): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1377): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1377): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1377): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1377): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1377): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1377): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1377): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/[LGHome]EVENT( 1882): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1882): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1882): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
D/administrator(  847): Handling package changes for user 0
,I/NotificationManager( 7621): com.google.android.talk: cancel(8) by com.google.android.talk
,I/AppUp4:CustModeStarterReceiver( 7569): onReceive
I/AppUp4:CustModeStarterReceiver( 7569): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 7569): Context : android.app.ReceiverRestrictedContext@218fd9cb
D/AppUp4:CustFacade( 7569): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7569): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7569): begin check event
I/AppUp4:CustModeStarterReceiver( 7569): Event For Nothing, skip.
W/ResourcesManager( 7621): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7621): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/[LGHome]Launcher( 1882): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/ActivityManager(  847): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7831 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,V/JNIHelp ( 7621): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7621): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7621): Installed default security provider GmsCore_OpenSSL
,W/ResourcesManager( 7831): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7831): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7831): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/NotificationService(  847): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  847): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  847): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  847): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/LCardEmulationManager( 1791): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1791): getDefaultRoute
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
V/BackupManagerService(  847): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  847): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@6e69b1d
,W/ResourcesManager(  847): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/AppConfig( 7831): Total System Memory = 906309632
I/GalleryUtils( 7831): Application Heap = 96 MB
,I/AppConfig( 7831): App Tier : NOT_DEF
D/SystemHelper( 7831): region [EU], country [EU], operator [OPEN], sub-operator []
,W/ResourceType(  847): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  847): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7858 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ResourcesManager( 7858): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7858): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7858): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7858): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7858): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1882): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1735): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ActivityManager(  847): Process com.google.android.apps.magazines (pid 7653) has died
,I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
D/LocationProviderProxy(  847): applying state to connected service
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-58 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-21 16:41:10.49 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/SystemConfig( 7858): BUILD Country: EU
I/SystemConfig( 7858): BUILD Operator: OPEN
,I/art     (  847): Explicit concurrent mark sweep GC freed 27979(1409KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.700ms total 172.445ms
,I/ActivityManager(  847): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7879 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 7858): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7858): existFile = false
I/SystemConfig( 7858): canReadFile = false
I/SystemConfig( 7858): systemFeature RCS result false
,D/SystemConfig( 7858): refreshRcsSupport() :false
,I/LockScreenSettings( 7879): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7879): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7879): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7879): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7879): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7879): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/UpdateIcingCorporaServi( 1959): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/charger_monitor(  492): init target 500000
,I/ActivityManager(  847): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7900 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 7738): CheckpointMarkThreadRoots callback created = 0xaaf34370
I/art     ( 7738): CheckpointMarkThreadRoots callback created = 0xaaf34350
,D/KeyguardUpdateMonitor( 1377): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1377): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1377): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1377): On Skip Timer : true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/KeyguardUpdateMonitor( 1377): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
I/[SystemUI]LGPowerUI( 1377): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1377): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2006): Disconnected process message: 10, size: 0
D/charger_monitor(  492): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 288, mChargingStatus=5, mChargingStop=false
,W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  847): battery changed pluggedType: 2
I/ActivityManager(  847): Killing 7598:com.lge.drmservice/u0a51 (adj 15): empty #11
I/[SystemUI]BatterySaverHandler( 1377): onReceive = android.intent.action.BATTERY_CHANGED
,I/UpdateIcingCorporaServi( 1959): UpdateCorporaTask done [took 118 ms] updated apps [took 118 ms] 
,W/libprocessgroup(  847): failed to open /acct/uid_10051/pid_7598/cgroup.procs: No such file or directory
,D/Finsky  ( 7900): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7900): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7900): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7900): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 7900): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3191): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3191): created cursor android.database.sqlite.SQLiteCursor@23ff5705 on behalf of 7900
D/Finsky  ( 7900): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7900): [1] Libraries$2.run: Finished loading 1 libraries.
I/ActivityManager(  847): Killing 7719:com.android.chrome/u0a48 (adj 15): empty #11
,D/Ads     ( 7900): Skipping gmscore version check
W/libprocessgroup(  847): failed to open /acct/uid_10048/pid_7719/cgroup.procs: No such file or directory
,I/ActivityManager(  847): Killing 7205:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  847): failed to open /acct/uid_10038/pid_7205/cgroup.procs: No such file or directory
,D/Finsky  ( 7900): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 5691): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 5691): Null package name or gms related package.  Ignoreing.
I/CheckinService( 5691): Done disabling old GoogleServicesFramework version
,D/Finsky  ( 7900): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 5691): updateResources: need to parse f{com.google.android.gms}
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/Icing   ( 5691): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 5691): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  847): Killing 7788:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 7459): android.os.DeadObjectException
,W/libprocessgroup(  847): failed to open /acct/uid_10089/pid_7788/cgroup.procs: No such file or directory
W/ActivityManager(  847): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
W/System.err( 7459): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7459): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7459): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7459): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7459): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7459): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7459): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7459): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7459): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7459): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7459): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7459): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7459): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7459): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7459): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7459): android.os.DeadObjectException
W/System.err( 7459): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7459): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7459): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7459): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7459): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7459): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7459): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7459): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7459): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7459): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7459): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7459): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7459): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7459): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7459): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
,I/ActivityManager(  847): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7968 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  312): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 299us total 46.264ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 20.855ms
,D/UEI.SmartControl( 7968): Quickset Services start...
,I/UEI.SmartControl( 7968): Manufacture = LGE
,D/UEI.SmartControl( 7968): File observer start...
E/UEI.SmartControl( 7968): IR Port is disabled: false
D/UEI.SmartControl( 7968): Starting file observer...
D/UEI.SmartControl( 7968): Extracting JNI libs...
D/UEI.SmartControl( 7968): --- this system supports 32-bit or 64-bit only
I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 20.473ms
D/UEI.SmartControl( 7968): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7968): --- Checking lib: libqs_armeabi-v7a.zip
,D/UEI.SmartControl( 7968): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7968): --- Selecting new region: 2
I/UEI.SmartControl( 7968): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7968): Platform has CIR...
D/UEI.SmartControl( 7968): NO CIR support, need to check package...
I/UEI.SmartControl( 7968): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7968): QS Service created
E/UEI.SmartControl( 7968): QS start get config
,D/UEI.SmartControl( 7968): Loading JNI Libs...
,D/UEI.SmartControl( 7968):  configuring local db...
,D/UEI.SmartControl( 7968):  ---- Has DB8: true
D/UEI.SmartControl( 7968): QS start statue = true Error code = 0
,D/UEI.SmartControl( 7968): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7968): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7968): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7968): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7968): IrrcClient ++ 
D/irrcClient( 7968): getIrrcService ++ 
,D/irrcClient( 7968): getIrrcService -- 
D/irrcClient( 7968): IrrcClient -- 
W/irrc_jni( 7968): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7968): Services init done
I/UEI.SmartControl( 7968): Device manager: loading config....
D/UEI.SmartControl( 7968): QS Service init finished
D/UEI.SmartControl( 7968): QS Service version name: 0.1.73
,D/UEI.SmartControl( 7968): QS Service version code: 1073
D/UEI.SmartControl( 7968): Service requested: Control
D/UEI.SmartControl( 7968): Config is loaded...
D/UEI.SmartControl( 7968): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 7968): -----IControl: 11
I/ActivityManager(  847): Killing 7569:com.lge.appbox.client/u0a11 (adj 15): empty #11
D/UEI.SmartControl( 7968): Caller: com.lge.qremote
D/UEI.SmartControl( 7968): ------------ IControl registerCallback...
I/UEI.SmartControl( 7968): Registering callback...
D/UEI.SmartControl( 7968): -----IControl: 19
D/UEI.SmartControl( 7968): Caller: com.lge.qremote
I/UEI.SmartControl( 7968): Registering Services Ready callback...
I/UEI.SmartControl( 7968): Notify client services are ready...
D/UEI.SmartControl( 7968): -----IControl: 8
D/UEI.SmartControl( 7968): Caller: com.lge.qremote
D/UEI.SmartControl( 7968):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 7968): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7968): Internal service binding...
W/libprocessgroup(  847): failed to open /acct/uid_10011/pid_7569/cgroup.procs: No such file or directory
I/AudioManager( 7459): getMode name:com.lge.qremote
I/AudioManager( 7459): getMode name:com.lge.qremote
,I/AudioManager( 7459): getMode name:com.lge.qremote
I/ActivityManager(  847): Killing 7621:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  847): failed to open /acct/uid_10061/pid_7621/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 134804964744; DSPS: 4515105; Offset : -2993145094
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/UEI.SmartControl( 7968): Internal timer expired: 1
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,V/AlarmManager(  847): ELAPSED_WAKEUP set : Alarm{3270e408 type 2 when 140395 com.google.android.gms} when 140395
,I/art     ( 1735): Explicit concurrent mark sweep GC freed 37121(2MB) AllocSpace objects, 25(400KB) LOS objects, 40% free, 13MB/22MB, paused 1.800ms total 104.667ms
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1735): Vacuum at: now=1453390884563 tag=VacuumService
,W/InstanceID/Rpc( 5691): Found 10006
,I/PhenotypeConfigurator( 1735): Scheduling Phenotype for one-off execution 7512 seconds from now (1453390884970)
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/GetConfigurationSnapshotOperation( 1735): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1735): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1735): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  847): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
,I/System.out( 1735): propertyValue:false
D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-53 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-21 16:41:25.561 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/LocationManagerService(  847): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/LocationManagerService(  847): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  847): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LocationManagerService(  847): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-58 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-21 16:41:28.583 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PowerManagerService(  847): ALS enabled for SRE
,D/PowerManagerServiceEx(  847): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (28042 ms ago)
D/qdlights(  847): set_light_backlight: 254
,D/qdlights(  847): set_light_backlight: 251
,D/qdlights(  847): set_light_backlight: 247
,D/qdlights(  847): set_light_backlight: 244
,D/qdlights(  847): set_light_backlight: 241
,D/qdlights(  847): set_light_backlight: 237
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,D/qdlights(  847): set_light_backlight: 234
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/qdlights(  847): set_light_backlight: 231
,D/qdlights(  847): set_light_backlight: 227
,D/qdlights(  847): set_light_backlight: 224
,D/qdlights(  847): set_light_backlight: 221
,D/qdlights(  847): set_light_backlight: 217
,D/qdlights(  847): set_light_backlight: 214
,D/qdlights(  847): set_light_backlight: 211
,D/qdlights(  847): set_light_backlight: 207
,D/qdlights(  847): set_light_backlight: 204
,D/qdlights(  847): set_light_backlight: 201
,D/qdlights(  847): set_light_backlight: 197
,D/qdlights(  847): set_light_backlight: 194
,D/qdlights(  847): set_light_backlight: 191
,D/qdlights(  847): set_light_backlight: 187
,D/qdlights(  847): set_light_backlight: 184
,D/qdlights(  847): set_light_backlight: 181
,D/qdlights(  847): set_light_backlight: 177
,D/qdlights(  847): set_light_backlight: 174
,D/qdlights(  847): set_light_backlight: 171
,D/qdlights(  847): set_light_backlight: 167
,D/qdlights(  847): set_light_backlight: 164
,D/qdlights(  847): set_light_backlight: 161
,D/qdlights(  847): set_light_backlight: 157
,D/qdlights(  847): set_light_backlight: 154
,D/qdlights(  847): set_light_backlight: 151
,D/qdlights(  847): set_light_backlight: 147
,D/qdlights(  847): set_light_backlight: 144
,D/qdlights(  847): set_light_backlight: 141
,D/qdlights(  847): set_light_backlight: 137
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
D/qdlights(  847): set_light_backlight: 134
,D/qdlights(  847): set_light_backlight: 131
,D/qdlights(  847): set_light_backlight: 127
,D/qdlights(  847): set_light_backlight: 124
,D/qdlights(  847): set_light_backlight: 121
,D/qdlights(  847): set_light_backlight: 117
,D/qdlights(  847): set_light_backlight: 114
,D/qdlights(  847): set_light_backlight: 111
,D/qdlights(  847): set_light_backlight: 107
,D/qdlights(  847): set_light_backlight: 104
,D/qdlights(  847): set_light_backlight: 101
,D/qdlights(  847): set_light_backlight: 98
,D/qdlights(  847): set_light_backlight: 94
,D/qdlights(  847): set_light_backlight: 91
,D/qdlights(  847): set_light_backlight: 88
,D/qdlights(  847): set_light_backlight: 84
,D/qdlights(  847): set_light_backlight: 81
,D/qdlights(  847): set_light_backlight: 78
,D/qdlights(  847): set_light_backlight: 74
,D/qdlights(  847): set_light_backlight: 71
,D/qdlights(  847): set_light_backlight: 68
,D/qdlights(  847): set_light_backlight: 64
,D/qdlights(  847): set_light_backlight: 61
,D/qdlights(  847): set_light_backlight: 58
,D/qdlights(  847): set_light_backlight: 54
,D/qdlights(  847): set_light_backlight: 51
,D/qdlights(  847): set_light_backlight: 48
,D/qdlights(  847): set_light_backlight: 44
,D/qdlights(  847): set_light_backlight: 41
,D/qdlights(  847): set_light_backlight: 38
,D/qdlights(  847): set_light_backlight: 34
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/qdlights(  847): set_light_backlight: 31
,D/qdlights(  847): set_light_backlight: 28
,D/qdlights(  847): set_light_backlight: 24
,D/qdlights(  847): set_light_backlight: 21
,D/qdlights(  847): set_light_backlight: 18
,D/qdlights(  847): set_light_backlight: 14
,D/qdlights(  847): set_light_backlight: 11
,D/qdlights(  847): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 154805781768; DSPS: 5170492; Offset : -2993151941
,I/PowerManagerService(  847): ALS enabled for SRE
D/PowerManagerServiceEx(  847): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (35016 ms ago)
I/PowerManagerService(  847): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  847): ALS enabled for SRE
D/PowerManagerServiceEx(  847): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (35028 ms ago)
,W/ContextImpl(  847): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  847): Sleeping (uid 1000)...
D/LPWGController(  847): [updateScreenState] screen on = false
D/LPWGController(  847): disable proximity sensor
,D/LPWGController(  847): enable proximity sensor
I/SensorManager(  847): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@abcdd50] by com.android.server.power.ProximitySensorListener.enable():120
I/sensors_hal_Ctx(  847): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  847): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
,D/sensors_hal_SAM(  847): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  847): activate: handle is 48, enable
V/sensors_hal_Ctx(  847): activate sensors is 1400000000000
D/sensors_hal_Thresh(  847): enable: handle=48
I/sensors_hal_SAM(  847): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  847): waitForResponse: timeout=1000
V/sensors_hal_SAM(  847): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  847): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  847): enable: Received response: 0
D/PowerManagerServiceEx(  847): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (35069 ms ago)
I/Adreno-EGL(  847): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  847): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  847): Build Date: 03/02/15 Mon
I/Adreno-EGL(  847): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  847): Remote Branch: 
I/Adreno-EGL(  847): Local Patches: 
I/Adreno-EGL(  847): Reconstruct Branch: 
,D/PermissionCache(  245): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1001 us)
,I/Sensors (  430): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  847): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  847): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  847): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  847): processInd: handle 48, count=1
V/sensors_hal_Thresh(  847): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  847): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  847): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  847): poll: count: 256
I/sensors_hal_Ctx(  847): poll: released wakelock sensor_ind
D/sensors_hal_Util(  847): waitForResponse: timeout=0
D/LPWGController(  847): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  847): current mode = 1  value = 1 1
I/LPWGController(  847): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  847): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  847): set_light_backlight: 0
,I/SensorManager(  847): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  847): activate: handle is 46, disable
V/sensors_hal_Ctx(  847): activate sensors is 1000000000000
D/sensors_hal_LP2(  847): enable: handle=46
D/sensors_hal_LP2(  847): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  847): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  245): Set power mode=0, type=0 flinger=0xb6082000
,D/qdhwcomposer(  245): hwc_blank: Blanking display: 0
V/sensors_hal_SAM(  847): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  847): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
I/DisplayManagerService(  847): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  847): Display changed displayId=0
,D/DSDPConnection( 1755): Display #0 changed.
,D/qdhwcomposer(  245): hwc_blank: Done blanking display: 0
I/qdhwcomposer(  245): handle_blank_event: dpy:0 panel power state: 0
,D/SurfaceControl(  847): Excessive delay in setPowerMode(): 235ms
I/QCOM PowerHAL(  847): Got set_interactive hint
D/KeyguardViewMediator( 1377): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1377): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1333): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1377): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1377): handleNotifyScreenOff
D/SmartCoverViewMediator( 1333): notifyScreenOffLocked
D/SmartCoverViewMediator( 1333): handleNotifyScreenOFF
D/ScreenTurnOffBySensor( 1377): unregisterProximitySensor
,D/StatusBarWindowView( 1377): onScreenTurnedOff why = 3
D/WifiServerServiceExt(  847): sendKtScanInterval  mRtspPlay : false
,I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1377): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/WifiServerServiceExt(  847): set CMD_KT_SCAN_INTERVAL
,V/AudioFlinger(  282): setParameters(): io 0, keyvalue screen_state=on, calling pid 847
D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=on
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
D/KeyguardUpdateMonitor( 1377): handleTimeUpdate
,D/GpsLocationProvider(  847): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1377): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1840): |CORE| sendScreenState: state:true
I/LEDService( 1804): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1804): stopPatternFlashing()
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
I/LEDService( 1804): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
I/LEDService( 1804): updateLightsLocked : turn off led
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1804): RESTART MSG
,D/SplitWindow(  847): check instance of lgWin Window{123616f u0 SearchPanel}
,I/Cliptray Service( 1804): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/Cliptray Service( 1804): lockStatus = 0
D/InputDispatcher(  847): Window went away: Window{39d571b8 u0 SearchPanel}
,I/[SystemUI]Clock( 1377): onReceive = android.intent.action.SCREEN_ON
,I/LgeClockWidgetControlView( 1377): time changed, timezoneChanged : false
,D/LNfcService( 1791): action : android.intent.action.SCREEN_ON
D/NfcServiceNXP( 1791): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1791): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1791): isRequireNfcCRouting() return true
D/LNfcService( 1791): isHCERoutingtoHost() return : true
D/NfcService( 1791): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1791): mEnableLPD: true
D/NfcService( 1791): mEnableReader: false
D/NfcService( 1791): mEnableHostRouting: true
D/NfcService( 1791): newParams.techmask= mTechMask: default
D/NfcService( 1791): mEnableLPD: true
D/NfcService( 1791): mEnableReader: false
D/NfcService( 1791): mEnableHostRouting: true
D/NfcService( 1791): screenState= 3
D/NfcService( 1791): Discovery configuration equal, not updating.
,D/Ulp_jni (  847): JNI:system_update. Event-0
,V/PhoneApp( 1755): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): ACTION_SCREEN_ON
,D/WeatherService( 2819): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 16:41:40
D/WeatherService( 2819): 2 : ACTION screen on
D/WeatherService( 2819): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2819): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherService( 2819): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 16:41:40
D/AppCleanupService( 4024): android.intent.action.SCREEN_ON
,V/AudioFlinger(  282): setParameters(): io 0, keyvalue screen_state=off, calling pid 847
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
D/WifiController(  847): CMD_SCREEN_OFF 
D/WifiController(  847): shouldWifiStayAwake TRUE
,I/Sensors (  430): sns_pwr.c(301):releasing wakelock
D/GpsLocationProvider(  847): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1377): onReceive = android.intent.action.SCREEN_OFF
,I/QCNEJ   ( 1840): |CORE| sendScreenState: state:false
,I/LEDService( 1804): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1804): stopPatternFlashing()
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
I/LEDService( 1804): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
I/LEDService( 1804): updateLightsLocked : turn on led
E/LEDService( 1804): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1804): Can't handle this request of patternId:0
D/LEDHandler( 1804): RESTART MSG
D/VolumeVibrator( 1804): clear
I/Cliptray Service( 1804): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,D/LNfcService( 1791): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1791): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1882): [Launcher.java:1711:onReceive()]Screen Off
V/PhoneApp( 1755): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): ACTION_SCREEN_OFF
D/WeatherService( 2819): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 16:41:40
D/WeatherService( 2819): 2 : ACTION screen off
D/WeatherService( 2819): 2 : TimeTick Receiver Unregister
D/WeatherService( 2819): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 16:41:40
,D/AppCleanupService( 4024): android.intent.action.SCREEN_OFF
D/AppCleanupService( 4024): AppUsageStatsSaveTask
,E/NxpNfcJni( 1791): getReconnectState = 0x0
,D/LCardEmulationManager( 1791): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1791): getDefaultRoute
D/LNfcService( 1791): isRequireNfcCRouting() return true
D/LNfcService( 1791): isHCERoutingtoHost() return : true
D/NfcService( 1791): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1791): mEnableLPD: true
D/NfcService( 1791): mEnableReader: false
D/NfcService( 1791): mEnableHostRouting: true
D/NfcService( 1791): newParams.techmask= mTechMask: 0
D/NfcService( 1791): mEnableLPD: true
D/NfcService( 1791): mEnableReader: false
D/NfcService( 1791): mEnableHostRouting: true
D/NfcService( 1791): screenState= 1
E/NxpNfcJni( 1791): getReconnectState = 0x0
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/KeyguardViewMediator( 1377): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  847): ELAPSED_WAKEUP set : Alarm{e9a7e7c type 2 when 160974 com.android.systemui} when 160974
,D/PhoneUtils( 1755): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1755): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1755): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1755): getCallState : 0
,D/PhoneUtils( 1755): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1755): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1755): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1377): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1377): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 174806511447; DSPS: 5825876; Offset : -2993154631
,I/[SystemUI]TimeTickManager( 1377): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1377): called onTimeUpdated()
I/[SystemUI]Clock( 1377): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1377): called onTimeUpdated()
I/[SystemUI]DateView( 1377): called onTimeUpdated()
I/[SystemUI]DateView( 1377): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1377): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/PowerManagerServiceEx(  847): acquireWakeLockInternal: lock=439997189, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=847
,V/AlarmManager(  847): ELAPSED_WAKEUP set : Alarm{3c88f5a type 2 when 186902 com.google.android.gms} when 186902
D/PowerManagerServiceEx(  847): releaseWakeLockInternal: lock=439997189 [*alarm*], flags=0x0
,D/KeyguardUpdateMonitor( 1377): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1377): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1377): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1377): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  492): init target 500000
D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 2006): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1377): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1377): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1377): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1377): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  847): battery changed pluggedType: 2
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  847): ELAPSED_WAKEUP set : Alarm{31aea58b type 2 when 190432 android} when 190432
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 194807266857; DSPS: 6481260; Offset : -2993131513
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1377): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1377): onReceive = com.lge.android.intent.action.BATTERYEX
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1377): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1377): On Skip Timer : true
D/charger_monitor(  492): init target 500000
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 2006): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1377): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1377): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1377): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  847): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1377): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2006): Disconnected process message: 10, size: 0
,W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1377): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1377): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1377): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
D/WifiController(  847): battery changed pluggedType: 2
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1377): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 214808031224; DSPS: 7136646; Offset : -2993160317
,I/ClearcutLoggerApiImpl( 1735): disconnect managed GoogleApiClient
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 234808701893; DSPS: 7792027; Offset : -2993131038
,I/[SystemUI]TimeTickManager( 1377): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1377): called onTimeUpdated()
I/[SystemUI]Clock( 1377): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1377): called onTimeUpdated()
I/[SystemUI]DateView( 1377): called onTimeUpdated()
I/[SystemUI]DateView( 1377): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1377): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  492): init target 500000
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1377): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1377): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1377): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1377): On Skip Timer : true
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 2006): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1377): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1377): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1377): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1377): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  847): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 254809376000; DSPS: 8447409; Offset : -2993128161
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 274810073441; DSPS: 9102792; Offset : -2993132156
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 294810764995; DSPS: 9758175; Offset : -2993142922
,I/[SystemUI]TimeTickManager( 1377): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1377): called onTimeUpdated()
I/[SystemUI]Clock( 1377): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1377): called onTimeUpdated()
I/[SystemUI]DateView( 1377): called onTimeUpdated()
I/[SystemUI]DateView( 1377): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1377): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  492): init target 500000
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1377): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1377): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1377): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1377): On Skip Timer : true
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1377): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1377): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1377): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
,D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2006): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1377): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  847): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1377): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1377): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1377): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1377): On Skip Timer : true
D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1377): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1377): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1377): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1377): On Skip Timer : true
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1377): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1377): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1377): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
,D/HeadsetStateMachine( 2006): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1377): onReceive = android.intent.action.BATTERY_CHANGED
,W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  847): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 314811435249; DSPS: 10413557; Offset : -2993144003
,D/KeyguardUpdateMonitor( 1377): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1377): onReceive = com.lge.android.intent.action.BATTERYEX
D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1377): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1377): On Skip Timer : true
D/KeyguardUpdateMonitor( 1377): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1377): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1377): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2006): Disconnected process message: 10, size: 0
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  847): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1377): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6346): --= Surplus to requirements =--
I/jxcore-log( 6346): 
I/jxcore-log( 6346): ****TEST TOOK:  ms ****
I/jxcore-log( 6346): 
I/jxcore-log( 6346): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6346): 
,D/AndroidRuntime( 8120): 
D/AndroidRuntime( 8120): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8120): CheckJNI is OFF
,D/AndroidRuntime( 8120): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  847): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
,I/ActivityManager(  847): Killing 6346:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  847): WIN DEATH: Window{1e0a5b3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/PackageSettings(  847): Skipping PackageSetting{264d3a9c com.example.hello/10317} due to missing metadata
D/InputDispatcher(  847): Focus left window: Window{1e0a5b3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  847): Window went away: Window{1e0a5b3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  847):   Force finishing activity ActivityRecord{3ff4be12 u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  847): Display changed displayId=0
D/DSDPConnection( 1755): Display #0 changed.
,W/ActivityManager(  847): Spurious death for ProcessRecord{324f0668 6346:com.test.thalitest/u0a316}, curProc for 6346: null
,I/ActivityManager(  847): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/[LGHome]EVENT( 1882): [Launcher.java:5203:onStart()]onStart
,I/[LGHome]EVENT( 1882): [Launcher.java:776:onResume()]onResume
,D/KeyguardModel( 1377): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,W/System.err( 3599): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,I/art     ( 1959): Explicit concurrent mark sweep GC freed 9312(524KB) AllocSpace objects, 3(71KB) LOS objects, 40% free, 12MB/21MB, paused 2.026ms total 96.007ms
W/System.err( 3599): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
,W/System.err( 3599): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3599): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3599): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3599): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3599): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3599): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3599): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3599): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3599): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3599): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/QCNEJ   ( 1840): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/GeofencerStateMachine( 1735): Ignoring removeGeofence because network location is disabled.
I/InputReader(  847): Reconfiguring input devices.  changes=0x00000010
I/art     ( 5691): Explicit concurrent mark sweep GC freed 6690(351KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 13MB/17MB, paused 811us total 92.890ms
,I/ActivityManager(  847): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8152 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/[LGHome]EVENT( 1882): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1882): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/[SystemUI]QSlideListController( 1377): onReceive = android.intent.action.PACKAGE_REMOVED
,D/KeyguardModel( 1377): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1377): createShortcutInfo...
D/KeyguardModel( 1377): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1377): createShortcutInfo...
I/[LGHome]LGActivityUtil( 1882): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1882): [Launcher.java:929:onResume()]onResume end
I/Activity( 1882): Activity.onPostResume() called 
W/ResourcesManager( 1377): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 1377): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourceType( 1377): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1377): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1377): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1377): createShortcutInfo...
,I/[LGHome]EVENT( 1882): [Launcher.java:986:onPause()]onPause
,W/[LGHome]LGWallpaperInfo( 1882): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1882): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
W/ResourcesManager( 1377): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1377): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1377): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
W/ResourceType( 1377): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1377): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1377): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1377): createShortcutInfo...
,W/ResourcesManager( 1377): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1377): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1377): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,W/ResourceType( 1377): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1377): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/SystemUI[Framework](  847): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
D/KeyguardModel( 1377): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1377): createShortcutInfo...
W/PhoneWindowManagerEx(  847): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  847): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  847): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  847): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@69c6f5,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  847): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  847): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  847): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  847): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  847): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  847): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@69c6f5,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  847): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher(  847): Focus entered window: Window{1c52ceb3 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
,I/[LGHome]EVENT( 1882): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1882): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/KeyguardModel( 1377): handleShortcutListChanged...
I/[LGHome]LGPlusHomeDBManager( 1882): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
,I/[LGHome]EVENT( 1882): [Launcher.java:5214:onStop()]onStop
I/art     (  847): Explicit concurrent mark sweep GC freed 56454(3MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 4.034ms total 253.797ms
I/art     (  847): WaitForGcToComplete blocked for 178.197ms for cause Explicit
I/[LGHome]EVENT( 1882): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
W/ResourcesManager( 8152): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8152): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8152): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/PhoneWindow( 1882): [setNavigationBarColor] color=0x 0
D/KeyguardModel( 1377): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1377): createShortcutInfo...
D/KeyguardModel( 1377): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1377): createShortcutInfo...
,W/ResourceType( 1377): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1377): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1377): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1377): createShortcutInfo...
W/ResourceType( 1377): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1377): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1377): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1377): createShortcutInfo...
W/ResourceType( 1377): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1377): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,D/KeyguardModel( 1377): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1377): createShortcutInfo...
D/KeyguardModel( 1377): handleShortcutListChanged...
D/administrator(  847): Handling package changes for user 0
,W/InputMethodManagerService(  847): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,W/InputMethodManagerService(  847): Got RemoteException sending setActive(false) notification to pid 6346 uid 10316
I/art     (  847): Explicit concurrent mark sweep GC freed 6887(419KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 6.975ms total 265.705ms
,I/LGEmail ( 8152): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 8152): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/[LGHome]Launcher.Model( 1882): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1882): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1882): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,I/Timeline(  847): Timeline: Activity_windows_visible id: ActivityRecord{3a4c6e41 u0 com.lge.launcher2/.Launcher t221} time:321693
I/[LGHome]EVENT( 1882): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1882): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1882): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
W/IInputConnectionWrapper( 1882): getTextBeforeCursor on inactive InputConnection
,I/[LGHome]Launcher.Model( 1882): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1882): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,E/b       ( 1615): Unable to connect to the editor to retrieve text... will retry later
D/AndroidRuntime( 8120): Shutting down VM
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1882): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1882): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 1882): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1882): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1882): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1882): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/LCardEmulationManager( 1791): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1791): getDefaultRoute
W/Resources( 1882): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
,W/Resources( 1882): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1882): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1882): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1882): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1882): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
,W/Resources( 1882): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1882): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1882): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1882): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
,W/Resources( 1882): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1882): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
,I/NotificationService(  847): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,D/BackupManagerService(  847): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  847): Receieved: android.intent.action.PACKAGE_REMOVED
D/PhoneStatusBar( 1377): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
,D/TaskPersister(  847): removeObsoleteFile: deleting file=222_task.xml
D/PhoneStatusBar( 1377): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1377): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1377):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1377): , Keyguard show=false, IME shown=false, Panel expanded=false
,I/PackageChangeReceiver( 8152): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/ActivityManager(  847): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8178 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  847): Killing 7831:com.android.gallery3d/u0a23 (adj 15): empty #11
W/ResourcesManager(  847): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1882): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,W/libprocessgroup(  847): failed to open /acct/uid_10023/pid_7831/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 8178): onCreate
,W/AppUp4:DB( 8178):  [AppBoxDatabaseHelper] construct
E/[LgeWidgetLib]LgeAppWidgetHostView( 1882): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1882): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1882): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1882): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/SQLiteDatabase( 8178): Failed to open database '/data/data/com.lge.appbox.client/databases/appbox.db'.
E/SQLiteDatabase( 8178): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8178): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8178): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/SQLiteDatabase( 8178): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/SQLiteDatabase( 8178): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/SQLiteDatabase( 8178): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/SQLiteDatabase( 8178): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8178): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/SQLiteDatabase( 8178): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/SQLiteDatabase( 8178): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/SQLiteDatabase( 8178): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 8178): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 8178): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8178): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 8178): 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
E/SQLiteDatabase( 8178): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
E/SQLiteDatabase( 8178): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
E/SQLiteDatabase( 8178): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
E/SQLiteDatabase( 8178): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
E/SQLiteDatabase( 8178): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
E/SQLiteDatabase( 8178): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
E/SQLiteDatabase( 8178): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 8178): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8178): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 8178): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/SQLiteDatabase( 8178): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 8178): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 8178): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/SQLiteDatabase( 8178): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,I/[LGHome]EVENT( 1882): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]Launcher( 1882): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1882): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1882): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1882): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
D/AndroidRuntime( 8178): Shutting down VM
I/[LGHome]EVENT( 1882): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
--------- beginning of crash
E/AndroidRuntime( 8178): FATAL EXCEPTION: main
E/AndroidRuntime( 8178): Process: com.lge.appbox.client, PID: 8178
E/AndroidRuntime( 8178): java.lang.RuntimeException: Unable to get provider com.lge.appbox.databases.AppBoxContentProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8178): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5106)
E/AndroidRuntime( 8178): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
E/AndroidRuntime( 8178): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
E/AndroidRuntime( 8178): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
E/AndroidRuntime( 8178): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 8178): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8178): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 8178): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/AndroidRuntime( 8178): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8178): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8178): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/AndroidRuntime( 8178): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/AndroidRuntime( 8178): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8178): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 8178): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/AndroidRuntime( 8178): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/AndroidRuntime( 8178): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/AndroidRuntime( 8178): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/AndroidRuntime( 8178): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 8178): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/AndroidRuntime( 8178): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/AndroidRuntime( 8178): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/AndroidRuntime( 8178): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/AndroidRuntime( 8178): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 8178): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 8178): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 8178): 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
E/AndroidRuntime( 8178): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
E/AndroidRuntime( 8178): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
E/AndroidRuntime( 8178): 	at android.app.ActivityTh,read.installProvider(ActivityThread.java:5103)
E/AndroidRuntime( 8178): 	... 11 more
I/[LGHome]EVENT( 1882): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
,I/[LGHome]Launcher( 1882): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/[LGHome]Launcher( 1882): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/DropBoxManagerService(  847): Can't write: system_app_crash
E/DropBoxManagerService(  847): java.io.FileNotFoundException: /data/system/dropbox/drop119.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  847): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  847): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  847): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  847): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  847): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  847): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12621)
E/DropBoxManagerService(  847): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  847): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  847): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  847): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  847): 	... 5 more
,I/ActivityManager(  847): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8199 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/Process ( 8178): Sending signal. PID: 8178 SIG: 9
W/ResourceType(  847): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LgeWidgetLib]LgeAppWidgetHostView( 1882): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1882): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1882): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]EVENT( 1882): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/ActivityManager(  847): Process com.lge.appbox.client (pid 8178) has died
I/[LGHome]Launcher( 1882): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/SharedPreferencesImpl( 1882): Couldn't rename file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml to backup file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml.bak

```
