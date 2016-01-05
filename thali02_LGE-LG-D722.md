#### Test 549702617d40def_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
D/UEI.SmartControl( 5690): Internal timer expired: 1
,D/AndroidRuntime( 6089): 
D/AndroidRuntime( 6089): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6089): CheckJNI is OFF
I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/AndroidRuntime( 6089): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  938): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  938): setTaskToReturnTo : TaskRecord{2883cc9e #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  938): setTaskToReturnTo : TaskRecord{2883cc9e #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  938): AppWindowTokenEx init.. 
D/ContextHelper(  938): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  938): Focus left window: Window{3e86f931 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 6089): Shutting down VM
I/[LGHome]EVENT( 1878): [Launcher.java:986:onPause()]onPause
D/SplitWindow(  938): check instance of lgWin Window{6a2d438 u0 Starting com.test.thalitest}
I/ActivityManager(  938): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6108 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1878): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[LGHome]EVENT( 1878): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  938): Starting window displayed
I/SystemUI[Framework](  938): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
I/HotwordDetector( 1940): Closing mic
D/PhoneStatusBar( 1371): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  938): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  938): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  938): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  938): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@23694287,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  938): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1371): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1371):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1371): , Keyguard show=false, IME shown=false, Panel expanded=false
I/MicrophoneInputStream( 1940): mic_close com.google.android.apps.gsa.speech.audio.u@111eadad
D/BarTransitions( 1371): draw background and invalidate : color = 15000000
V/AudioRecord( 1940): stop()
D/AudioRecord( 1940): AudioRecord->stop()
V/AudioFlinger(  285): RecordHandle::stop()
V/AudioFlinger(  285): RecordThread::stop
D/BarTransitions( 1371): draw background and invalidate : color = 11111111
V/AudioFlinger(  285): Record stopped OK
V/AudioPolicyManager(  285): stopInput() input 17
V/AudioPolicyService(  285): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  285): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  285): AudioCommandThread() waking up
V/AudioPolicyService(  285): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  285): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  285): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  285): ThreadBase::setParameters() routing=0
V/AudioFlinger(  285): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  285): processConfigEvents_l() remaining events 1
V/AudioFlinger(  285): processConfigEvents_l() DONE thread 0xb3852000
,D/audio_hw_primary(  285): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 94261544083; DSPS: 3186790; Offset : -3001223941
V/audio_hw_primary(  285): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  285): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  285): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  285): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  285): disable_audio_route: exit
E/audio_hw_primary(  285): disable_snd_device: enter 144
D/hardware_info(  285): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  285): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  285): stop_input_stream: exit: status(0)
V/audio_hw_primary(  285): in_standby: exit:  status(0)
V/AudioFlinger(  285): RecordThread: loop stopping
V/AudioPolicyManager(  285): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  285): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  285): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  285): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
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
V/AudioFlinger(  285): processConfigEvents_l() DONE thread 0xb3852000
V/AudioFlinger(  285): RecordThread: loop stopping
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
V/AudioRecord( 1940): stop()
V/AudioRecord( 1940): stop()
V/AudioRecord( 1940): stop()
V/AudioFlinger(  285): releasing 16 from 1940 for -1
V/AudioFlinger(  285):  decremented refcount to 0
V/AudioFlinger(  285): purging stale effects
V/AudioFlinger(  285): RecordHandle::stop()
V/AudioFlinger(  285): RecordThread::stop
V/AudioPolicyManager(  285): releaseInput() 17
V/AudioPolicyManager(  285): closeInput(17)
V/AudioFlinger(  285): closeInput() 17
V/AudioSystem(  285): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  938): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1371): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1940): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1990): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1746): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  285): ThreadBase::exit
V/AudioSystem( 2758): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3181): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  285): RecordThread: loop starting
V/AudioFlinger(  285): RecordThread 0xb3852000 exiting
D/audio_hw_primary(  285): adev_close_input_stream: enter:stream_handle(0xb546dd40)
D/audio_hw_primary(  285): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/audio_hw_primary(  285): in_standby: exit:  status(0)
V/AudioPolicyService(  285): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  285): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  285): AudioCommandThread() waking up
V/AudioPolicyService(  285): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
V/AudioPolicyManager(  285): releaseInput() exit
V/AudioFlinger(  285): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  285): removeClient_l() pid 1940, calling pid 285
I/HotwordRecognitionRnr( 1940): Stopping hotword detection.
I/HotwordRecognitionRnr( 1940): Hotword detection finished
D/ContextHelper( 6108): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 6108): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 6108): Time to load native libraries: 11 ms (timestamps 4563-4574)
I/LibraryLoader( 6108): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6108): Binding Chromium to main looper Looper (main, tid 1) {e0497d6}
I/LibraryLoader( 6108): Expected native library version number "",actual native library version number ""
I/chromium( 6108): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6108): Initializing chromium process, singleProcess=true
W/art     ( 6108): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6108): ApplicationContext is null in ApplicationStatus
W/chromium( 6108): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6108): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6108): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6108): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6108): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6108): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6108): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6108): Remote Branch: 
I/Adreno-EGL( 6108): Local Patches: 
I/Adreno-EGL( 6108): Reconstruct Branch: 
V/AudioPolicyService(  285): registerClient() client 0xb57e67c0, uid 10316
D/BluetoothManagerService(  938): Message: 20
D/BluetoothManagerService(  938): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@afafc5a:true
D/BluetoothAdapterService(252336994)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@37ab5ac8
I/ActivityManager(  938): Start proc com.google.process.gapps for content provider com.google.android.gsf/.settings.GoogleSettingsProvider: pid=6162 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/art     ( 6108): Attempt to remove local handle scope entry from IRT, ignoring
,I/GservicesProvider( 6162): Gservices pushing to system: true; secure/global: true
,W/AwContents( 6108): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6108): CordovaWebView is running on device made by: LGE
,W/art     ( 6108): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6108): Attempt to remove local handle scope entry from IRT, ignoring
D/Finsky  ( 5839): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  938): RTC_WAKEUP set : Alarm{330b23ac type 0 when 1451956833623 com.android.vending} when 1451956833623
I/Activity( 6108): Activity.onPostResume() called 
,I/GoogleHttpClient( 6162): GMS http client unavailable, use old client
D/OpenGLRenderer( 6108): Render dirty regions requested: true
I/OpenGLRenderer( 6108): Initialized EGL, version 1.4
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/OpenGLRenderer( 6108): Enabling debug mode 0
I/GoogleHttpClient( 6162): GMS http client unavailable, use old client
,D/Atlas   ( 6108): Validating map...
D/SplitWindow(  938): check instance of lgWin Window{391c1329 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/chromium( 6108): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/NotificationManager(  938): android: cancelAsUser(2) by android
,I/GAV2    ( 5906): Thread[GAThread,5,main]: No campaign data found.
D/InputDispatcher(  938): Focus entered window: Window{391c1329 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/libc-netbsd( 5839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  281): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out( 5839): propertyValue:false
D/libc-netbsd( 5839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/InputMethodManagerService(  938): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  938): Displayed com.test.thalitest/.MainActivity: +1s173ms
I/Timeline(  938): Timeline: Activity_windows_visible id: ActivityRecord{8aa737f u0 com.test.thalitest/.MainActivity t220} time:95232
I/Timeline( 6108): Timeline: Activity_idle id: android.os.BinderProxy@1b7f5b74 time:95258
,D/libc-netbsd( 5839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/QCNEJ   ( 1841): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-54 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-05 02:20:33.973 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
W/BindingManager( 6108): Cannot call determinedVisibility() - never saw a connection for the pid: 6108
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  938): android: cancelAsUser(2) by android
,I/qtaguid ( 5839): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5839): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5839): untagSocket(41) failed with errno -22
D/Finsky  ( 5839): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  938): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6206 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  938): android: cancelAsUser(2) by android
,W/ResourcesManager( 6206): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6206): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  938): Process com.android.contacts (pid 5767) has died
,I/MultiDex( 6206): VM with version 2.1.0 has multidex support
I/MultiDex( 6206): install
,I/MultiDex( 6206): VM has multidex support, MultiDex support library is disabled.
D/AlertService( 5971): Beginning updateAlertNotification
,D/AlertService( 5971): No fired or scheduled alerts
I/NotificationManager( 5971): com.android.calendar: cancel(0) by com.android.calendar
,I/NotificationManager( 5971): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 5971): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 5971): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 5971): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5971): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 5971): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 5971): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 5971): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 5971): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 5971): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 5971): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 5971): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 5971): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 5971): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 5971): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 5971): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 5971): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5971): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 5971): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 5971): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 5971): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,V/JNIHelp ( 6206): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/JsMessageQueue( 6108): Set native->JS mode to OnlineEventsBridgeMode
D/AlarmScheduler( 5971): No events found starting within 1 week.
,I/qtaguid ( 5839): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5839): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5839): untagSocket(41) failed with errno -22
W/ActivityThread( 6206): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6206): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3c8bdd28: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6206): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6206): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6206): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1732): callingUid 10006, callindPid: 1732
,E/MDM     ( 1732): [140] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 4128): Restart initialization of location
,D/ChimeraCfgMgr( 6206): Reading stored module config
D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1732): No location to return for getLastLocation()
,W/FusedLocationProvider( 1732): location=null
D/ChimeraCfgMgr( 6206): Loading module com.google.android.gms.car from APK com.google.android.gms
D/jxcore_app_log( 6108): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622762496
,D/JX-Cordova( 6108): jxcore cordova android initializing
D/CAR.SERVICE( 6206): Connecting to CarCallService...
,I/art     ( 6108): CheckpointMarkThreadRoots callback created = 0x9a9f9460
I/art     ( 6206): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6206): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 6206): Install completed successfully. count=14 extracted=0
I/art     ( 6108): CheckpointMarkThreadRoots callback created = 0x9a9f9430
I/art     ( 5839): CheckpointMarkThreadRoots callback created = 0xb042d870
,D/CAR.SERVICE( 6206): com.google.android.projection.gearhead isn't installed.
I/art     ( 5839): CheckpointMarkThreadRoots callback created = 0xb042d840
,D/CAR.TEL.Service( 6206): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 6206): Creating a new PhoneAdapter instance
,W/ActivityManager(  938): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6206): setListener: com.google.android.gms.car.dn@372f6617
W/ActivityManager(  938): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6206): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6206): Starting CarCallService with initial phone null
I/NotificationManager( 6206): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/CAR.SERVICE( 6206): Package validated; name: com.android.vending
,I/NotificationManager( 5839): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 5839): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,I/ActivityManager(  938): Process com.google.android.talk (pid 5601) has died
,I/art     (  938): Explicit concurrent mark sweep GC freed 19058(942KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.404ms total 166.796ms
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  938): android: cancelAsUser(2) by android
,I/qtaguid ( 5839): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5839): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5839): untagSocket(41) failed with errno -22
,W/ResourcesManager( 5839): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5839): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  938): Process com.android.calendar (pid 5971) has died
W/ResourcesManager( 5839): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 5839): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  938): RTC_WAKEUP set : Alarm{24d8b570 type 0 when 1451956836452 com.android.vending} when 1451956836452
,D/DeviceConnectionService( 1732): client connected with version: 8296000
,D/Finsky  ( 5839): [739] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  938): android: cancelAsUser(2) by android
,D/Finsky  ( 5839): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5839): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
D/libc-netbsd( 5839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  281): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  281): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
,I/System.out( 5839): propertyValue:false
W/jxcore-log( 6108): Initializing JXcore engine
,W/jxcore-log( 6108): JXcore engine is ready
W/jxcore-log( 6108): Starting JXcore engine
,I/ActivityManager(  938): Process com.android.gallery3d (pid 6027) has died
,W/.test.thalitest( 6108): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7495]" dev="sockfs" ino=7495 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6108): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6108): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6496]" dev="sockfs" ino=6496 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6108): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6108): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6108): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[29416]" dev="sockfs" ino=29416 scontext=u:r:untrusted_app:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 6108): Platform android
W/jxcore-log( 6108): 
,W/jxcore-log( 6108): Process ARCH arm
W/jxcore-log( 6108): 
I/ActivityManager(  938): Process com.google.android.apps.plus (pid 5814) has died
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/ActivityManager(  938): Process com.android.providers.calendar (pid 6058) has died
,V/AlarmManager(  938): RTC_WAKEUP set : Alarm{13b2b046 type 0 when 1451956837863 com.google.android.googlequicksearchbox} when 1451956837863
,I/jxcore-log( 6108): JXcore Cordova bridge is ready!
I/jxcore-log( 6108): 
,W/jxcore-log( 6108): JXcore engine is started
I/Choreographer( 6108): Skipped 196 frames!  The application may be doing too much work on its main thread.
I/chromium( 6108): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/jxcore-log( 6108): Toggling radios to true
I/jxcore-log( 6108): 
,D/BluetoothAdapter( 6108): enable(): BT is already enabled..!
D/WifiServiceImplEx(  938): setWifiEnabled: true pid=6108, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  938): setWifiEnabled: true pid=6108, uid=10316
D/WifiServiceImplEx(  938): disconnect pid=6108, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  938): reconnect pid=6108, uid=10316, packageName=com.test.thalitest
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/jxcore-log( 6108): Radios toggled
I/jxcore-log( 6108): 
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2698): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2698): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine(  938): WifiStateMachine: Leaving Connected state
,D/WfdsMonitor( 1805): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiConfigStore(  938): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/LGWifiP2pService(  938): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  938): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  938): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  281): Clearing all IP addresses on wlan0
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 7
,V/NativeCrypto( 1732): Read error: ssl=0xb045bc00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1732): SSL shutdown failed: ssl=0xb045bc00: I/O error during system call, Broken pipe
D/libc-netbsd(  938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 10
,I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 7
D/libc-netbsd(  938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  938): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/WifiHS20(  938): hidePasspointNotification off =false
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-05 02:20:38.386 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  938): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
D/libc-netbsd(  938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  938): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
,D/ConnectivityService(  938): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  938): ValidatedState{ when=-3ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  938): DefaultState{ when=-9ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  938): Forcing reevaluation
,D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
I/ActivityManager(  938): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6286 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
E/WifiStateMachine(  938): Start Disconnecting Watchdog 1
D/WifiHS20(  938): hidePasspointNotification off =false
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  938): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/LGWifiP2pService(  938): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  938): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2698): wlan0: CTRL-EVENT-SCAN-STARTED 
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-05 02:20:38.467 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
D/CommandListener(  281): Clearing all IP addresses on wlan0
,D/ConnectivityService(  938): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  938): disableDataServiceNotify
D/DSQN    (  938): stop dsqn bin
D/WifiHS20(  938): hidePasspointNotification off =false
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-05 02:20:38.502 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  938): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
,D/ConnectivityService(  938): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  938):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  938):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WifiNetworkAgent(  938): NetworkAgent: NetworkAgent channel lost
D/ConnectivityService(  938): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  938): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  938): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  938): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  938): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1371): CM callback handler got msg 524292
D/CSLegacyTypeTracker(  938): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  938): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  938): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  938): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  938): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/Tethering(  938): MasterInitialState.processMessage what=3
D/ConnectivityService(  938): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  938): MasterInitialState.processMessage what=3
V/NetworkPolicy(  938): [LG_RESTRICTED] !!!isConnected  type  :1
W/QCNEJ   ( 1841): |CORE| No family connected
V/NetworkPolicy(  938): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService(  938): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  938): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService(  938): Removing idletimer
W/QCNEJ   ( 1841): |CORE| No family connected
I/QCNEJ   ( 1841): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/WifiHS20(  938): hidePasspointNotification off =false
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  938): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  938): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/ConnectivityService(  938): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
I/QCNEJ   ( 1841): |CORE| sendDefaultNwMsg: default = -1
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/DhcpStateMachine(  938): StoppedState
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-05 02:20:38.551 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-05 02:20:38.552 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/DhcpStateMachine(  938): StoppedState{ when=-84ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiServerServiceExt(  938): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  938): setSupplicantStateDISCONNECTED
D/WIFI    (  938): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  938):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1746): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiServerServiceExt(  938): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  938): setSupplicantStateSCANNING
D/TelephonyNetworkFactory-1( 1746):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/TelephonyIcons( 1371): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1371): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/TelephonyIcons( 1371): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1371): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
W/ResourcesManager( 6286): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6286): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,W/ResourcesManager( 6286): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6286): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6286): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/IndexDatabaseHelper( 6286): Using schema version: 115
,I/IndexDatabaseHelper( 6286): Index is fine
V/WiFiOffLoadBroadcast( 6286): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6286): MCCMNC not supported: null
I/ActivityManager(  938): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6310 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/PCSuite ( 6310): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6310): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6310): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6286): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6286): MCCMNC not supported: null
,I/PCSuite ( 6310): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6310): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6310): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  938): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6332 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6332): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2698): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
I/Babel_SMS( 6332): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6332): MmsConfig.loadMmsSettings
,I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2698): wlan0: Associated with c0:ff:d4:d3:aa:48
D/LocSvc_java(  938): onReceive
I/Babel_SMS( 6332): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6332): MmsConfig.loadFromDatabase
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-05 02:20:39.652 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  938): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-05 02:20:39.655 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  938): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt(  938): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  938): setSupplicantStateASSOCIATING
D/WifiServerServiceExt(  938): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  938): setSupplicantStateASSOCIATED
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-05 02:20:39.677 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/WifiOffDelayIfNotUsed(  938): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  938): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt(  938): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  938): setSupplicantStateFOUR_WAY_HANDSHAKE
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-05 02:20:39.681 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/wpa_supplicant( 2698): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2698): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/WifiServiceExtension(  938): setVHTCapabilityType  : false
I/WifiServerServiceExt(  938): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  938): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  938): setSecurityType  : 2
,E/Babel_SMS( 6332): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6332): MmsConfig.loadFromResources
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  938): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-05 02:20:39.728 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  938): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-05 02:20:39.736 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
E/Babel_SMS( 6332): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6332): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/ConnectivityService(  938): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  938): Got NetworkAgent Messenger
D/ConnectivityService(  938): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  938): NetworkAgent connected
D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
E/WifiConfigStore(  938): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  938): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  281): Setting iface cfg
E/WifiStateMachine(  938): Start Dhcp Watchdog 2
D/DhcpStateMachine(  938): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  938): WaitBeforeStartState
D/WifiServerServiceExt(  938): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  938): setSupplicantStateGROUP_HANDSHAKE
I/QCNEJ   ( 1841): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-57 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-05 02:20:39.793 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/ConnectivityService(  938): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/SensorManager( 6332): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6332): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6332): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6332): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6332): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6332): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6332): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6332): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6332): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6332): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6332): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6332): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6332): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6332): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6332): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6332): found sensor: Motion Accel, handle=46
,I/art     ( 6332): CheckpointMarkThreadRoots callback created = 0xb042d810
,W/Settings( 6332): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6332): startup - clean
,I/Babel   ( 6332): deleted: false for 0
,I/art     ( 6332): CheckpointMarkThreadRoots callback created = 0xb042d7f0
E/WifiStateMachine(  938): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  938): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  938): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@26aa759d target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  938): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@26aa759d target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper(  938): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  938): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  938): DHCP Start wake lock is acquired.
,D/CommandListener(  281): Setting iface cfg
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  281): Trying to bring up wlan0
,V/LgDhcpStateMachineHelper(  938): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,D/WifiServerServiceExt(  938): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  938): setSupplicantStateCOMPLETED
D/ConnectivityService(  938): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,D/LGWifiP2pService(  938): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  938): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiServerServiceExt(  938): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  938): setSupplicantStateCOMPLETED
D/ConnectivityService(  938): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  938): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  938): ignoring duplicate network state non-change
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  938): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-05 02:20:39.911 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  938): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  938): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-05 02:20:39.915 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/ConnectivityService(  938): Adding iface wlan0 to network 101
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
E/WifiStateMachine(  938): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20(  938): [PASSPOINT] passpointNotification: hs20AP list is checked
D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
,I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-05 02:20:39.927 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  938): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  938): [PASSPOINT] passpointNotification: hs20AP list is checked
,I/QCNEJ   ( 1841): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-05 02:20:39.939 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1841): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  938): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = true, mWifiLevel = 2
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = true, mWifiLevel = 2
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,E/ConnectivityService(  938): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  938): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  938): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
E/Netd    (  281): netlink response contains error (File exists)
D/ConnectivityService(  938): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/ConnectivityService(  938): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  938): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  938): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  938): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  938): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  938): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  938): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  938): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  938): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  938): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  938):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  938):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  938):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  938):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  938):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  938): currentScore = 0, newScore = 20
D/ConnectivityService(  938):    accepting network in place of null
D/ConnectivityService(  938): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/WiFiOffLoadBroadcast( 6286): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/TelephonyNetworkFactory-1( 1746): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  938): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  938):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1746):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
E/ConnectivityService(  938): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  938): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  938): [LWD] Start DNSResolver start to wait
D/ConnectivityService(  938): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  938): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  938): [e] list.add(nai) empty : false size: 1
D/Tethering(  938): MasterInitialState.processMessage what=3
D/ConnectivityService(  938): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Do,mains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
W/QCNEJ   ( 1841): |CORE| No family connected
I/QCNEJ   ( 1841): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
,I/QCNEJ   ( 1841): |CORE| sendDefaultNwMsg: default = 1
D/ConnectivityService(  938): validation of new default Network = false
D/ConnectivityService(  938): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  938): enableDataServiceNotify 
D/DSQN    (  938): start dsqn bin
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  938): [LWD] wait 500ms before dns check
V/NetworkPolicy(  938): [LG_RESTRICTED] checkMobilePolicy_type()
,D/ConnectivityService(  938): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  938):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  938):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  938): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1371): CM callback handler got msg 524290
D/TelephonyIcons( 1371): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1371): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/DSQN    ( 6369): DSQN samuel.seo ver 141203
E/DSQN    ( 6369): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6369): created command queue thread
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/DSQN    ( 6369): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6369): Interface wlan0 netmask 255.255.255.0 0xc0a80186
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
W/AudioCapabilities( 6332): Unsupported mime audio/x-lg-flac
D/WiFiOffLoadBroadcast( 6286): MCCMNC not supported: null
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/PCSuite ( 6310): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6310): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6310): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/AudioCapabilities( 6332): Unsupported mime audio/adpcm
,V/WiFiOffLoadBroadcast( 6286): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/AudioCapabilities( 6332): Unsupported mime audio/g726
W/AudioCapabilities( 6332): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6332): Unsupported mime audio/wma-voice
D/WiFiOffLoadBroadcast( 6286): MCCMNC not supported: null
W/VideoCapabilities( 6332): Unsupported mime video/mjpg
I/PCSuite ( 6310): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6310): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6310): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,W/VideoCapabilities( 6332): Unsupported mime video/theora
V/WiFiOffLoadBroadcast( 6286): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/DhcpStateMachine(  938): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper(  938): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  938): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/WiFiOffLoadBroadcast( 6286): MCCMNC not supported: null
,I/dhcpcd  ( 6372): version 5.5.6 starting
E/dhcpcd  ( 6372): get_duid: Read-only file system
V/WiFiOffLoadBroadcast( 6286): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6286): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6286): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6286): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 6286): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/AudioCapabilities( 6332): Unsupported mime audio/evrc
,D/WiFiOffLoadBroadcast( 6286): MCCMNC not supported: null
I/dhcpcd  ( 6372): wlan0: rebinding lease of 192.168.1.134
W/AudioCapabilities( 6332): Unsupported mime audio/qcelp
,V/WiFiOffLoadBroadcast( 6286): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6286): MCCMNC not supported: null
W/VideoCapabilities( 6332): Unrecognized profile 2130706433 for video/avc
,V/WiFiOffLoadBroadcast( 6286): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6286): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6286): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6286): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6286): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/AudioCapabilities( 6332): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6332): Unsupported mime audio/qcelp
W/AudioCapabilities( 6332): Unsupported mime audio/evrc
D/WiFiOffLoadBroadcast( 6286): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6286): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6286): MCCMNC not supported: null
W/VideoCapabilities( 6332): Unsupported mime video/mp4v-esdp
V/WiFiOffLoadBroadcast( 6286): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6286): MCCMNC not supported: null
I/VideoCapabilities( 6332): Unsupported profile 4 for video/mp4v-es
V/WiFiOffLoadBroadcast( 6286): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6286): MCCMNC not supported: null
I/PCSuite ( 6310): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6310): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
W/VideoCapabilities( 6332): Unrecognized profile 2130706433 for video/avc
V/WiFiOffLoadBroadcast( 6286): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/VideoCapabilities( 6332): Unrecognized profile 2130706433 for video/avc
D/WiFiOffLoadBroadcast( 6286): MCCMNC not supported: null
W/VideoCapabilities( 6332): Unrecognized profile 2130706433 for video/avc
I/PCSuite ( 6310): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6310): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
W/VideoCapabilities( 6332): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  938): Killing 5791:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  938): [LWD] DNSResolver start dns
D/libc-netbsd(  938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  281): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
W/libprocessgroup(  938): failed to open /acct/uid_10069/pid_5791/cgroup.procs: No such file or directory
I/vclib   ( 6332): onServiceConnected
W/Babel   ( 6332): Attempted to change video mute state without an active call.
D/CAR.SERVICE( 6206): mConnectedToCar = false, abort
I/NotificationManager( 6332): com.google.android.talk: cancel(10436) by com.google.android.talk
,E/ActivityThread( 6206): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1c5b521f that was originally bound here
E/ActivityThread( 6206): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1c5b521f that was originally bound here
E/ActivityThread( 6206): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6206): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6206): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6206): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6206): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6206): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6206): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6206): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6206): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6206): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6206): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6206): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6206): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6206): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6206): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6206): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6206): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6206): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6206): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6206): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6206): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6206): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6206): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out(  938): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  938): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  938): Checking http://clients3.google.com/generate_204 on "NG700"
E/ActivityThread( 6206): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2d810a96 that was originally bound here
E/ActivityThread( 6206): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2d810a96 that was originally bound here
E/ActivityThread( 6206): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6206): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6206): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6206): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6206): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6206): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6206): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6206): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6206): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6206): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6206): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6206): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6206): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6206): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6206): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6206): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6206): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6206): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6206): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6206): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6206): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6206): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,W/ActivityManager(  938): Unbind failed: could not find connection for android.os.BinderProxy@2dcc2e0b
D/libc-netbsd(  938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/DSQN    ( 6369): first global connection report this to start monitoring at DSQM.
,I/DSQN    ( 6369): restart monitoring
D/LGDataListener(  281): argv[0]=dsqncommand
D/LGDataListener(  281): argv[1]=wlan0
D/LGDataListener(  281): argv[2]=1
D/LGDataListener(  281): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  938): DSQM DsqnNotification wlan0  1
D/DSQN    (  938): start to monitor internet connection
I/DSQN    ( 6369): dsqn report finish
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  938): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 05 Jan 2016 01:20:40 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1451956840651], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1451956840574]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  938): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  938): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  938): Validated
D/ConnectivityService(  938): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  938): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  938):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  938):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  938):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  938): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  938): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  938):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  938):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  938): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  938): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  938): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  938): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  938):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1371): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1746): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1746):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WifiDataContinuityService(  938): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
I/WifiServerServiceExt(  938): set CMD_CAPTIVE_CHECK_COMPLETED
D/TelephonyIcons( 1371): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1371): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/charger_monitor(  474): init target 500000
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  938): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,D/charger_monitor(  474): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 6
D/WifiController(  938): battery changed pluggedType: 2
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
D/libc-netbsd(  938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1841): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-05 02:20:40.9 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/ConnectivityService(  938): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  938): identical MTU - not setting
D/Nat464Xlat(  938): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  938): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  938):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  938):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  938): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  938): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  938): enableDataServiceNotify 
D/DSQN    (  938): start dsqn bin
D/ConnectivityManager.CallbackHandler( 1371): CM callback handler got msg 524295
,D/DSQN    (  938): dsqn is running restart
I/DSQN    ( 6387): DSQN samuel.seo ver 141203
E/DSQN    ( 6387): DSQN sock connect success to lgdatalistenerd
,I/DSQN    ( 6387): created command queue thread
I/DSQN    ( 6387): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6387): Interface wlan0 netmask 255.255.255.0 0xc0a80186
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/ConnectivityService(  938): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/dhcpcd  ( 6372): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/dhcpcd  ( 6372): wlan0: leased 192.168.1.134 for 86400 seconds
,I/rmt_storage(  278): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  278): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  278): wakelock acquired: 1, error no: 42
,I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  278): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
,I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  278): 
D/ConnectivityService(  938): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  938): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.conn.CONNECTIVITY_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/GpsLocationProvider(  938): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java(  938): onReceive
D/LocSvc_java(  938): got connectivity action
,D/LocSvc_java(  938): broadcast - no network connections
D/LocSvc_java(  938): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  938): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  938): onReceive
D/LocSvc_java(  938): got connectivity action
D/LocSvc_java(  938): broadcast - no network connections
D/LocSvc_java(  938): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  938): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  938): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  938): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  938): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  938): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  938): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  938): ignore wifi update if we are not in OPENING or CLOSING
,D/GpsLocationProvider(  938): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  938): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  938): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6418 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/GpsLocationProvider(  938): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  306): Explicit concurrent mark sweep GC freed 705(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 20.745ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 20.152ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 20.516ms
,D/libc-netbsd(  938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  938): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  938): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  938): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/LgDhcpStateMachineHelper(  938): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  938): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  938): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  938): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  938): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  938): RunningState
I/MusicStore( 6418): Database version: 120
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6418): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6418): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6418): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6418): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6418): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6418): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,W/ActivityThread( 6418): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6418): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@276fc8a3: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6418): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6418): GMSCore installation verified
I/ConfigStore( 6418): Config Database version: 1
,I/ActivityManager(  938): Process com.google.android.gms:car (pid 6206) has died
,I/MediaRouter( 6418): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6418): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6418): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6418): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  938): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6447 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6418): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6418): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 6447): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6447): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6447): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/NotificationManager( 6418): com.google.android.music: cancel(1061) by com.google.android.music
,I/QCNEJ   ( 1841): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-05 02:20:42.811 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/LGEmail ( 6447): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,V/WifiInternetCheck(  938): Single check msg out of sync, ignoring.
,D/LGEmail ( 6447): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
D/ConnectivityService(  938): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  938): onReceive
D/LocSvc_java(  938): got connectivity action
D/LocSvc_java(  938): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
,D/LocSvc_java(  938): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  938): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  938): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  938): ignore wifi update if we are not in OPENING or CLOSING
I/NetworkMonitor( 6418): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider(  938): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  938): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/eas_req ( 6447): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  938): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6481 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6447): JNI_OnLoad()
I/HubEmail( 6447): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6447): registerNatives()
I/HubEmail( 6447): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6447): registerNativeMethods()
I/HubEmail( 6447): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6447): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6447): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  938): Killing 5906:com.google.android.gm/u0a53 (adj 15): empty #11
,W/libprocessgroup(  938): failed to open /acct/uid_10053/pid_5906/cgroup.procs: No such file or directory
D/LGDMClient( 6481): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6481): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6481): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6481): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,I/ActivityManager(  938): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6505 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/LGDMClient( 6481): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6481): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6481): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6481): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 6481): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 6481): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6481): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6481): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6481): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6481): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  938): Killing 5839:com.android.vending/u0a36 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/AppUp4:AppBoxCP( 6505): onCreate
,W/AppUp4:DB( 6505):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6505):  setFingerPrint start
I/AppUp4:DB( 6505):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6505):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6505):  SDK version = 0
I/AppUp4:DB( 6505):  beforefinger == newfinger no write in DB
W/libprocessgroup(  938): failed to open /acct/uid_10036/pid_5839/cgroup.procs: No such file or directory
,D/AppUp4:AppBoxApplication( 6505): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6505): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6505): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6505): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6505): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 6505): onReceive
I/AppUp4:CustModeStarterReceiver( 6505): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6505): Context : android.app.ReceiverRestrictedContext@23bc0a57
D/AppUp4:CustFacade( 6505): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6505): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6505): begin check event
I/AppUp4:CustModeStarterReceiver( 6505): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6505): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6505): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6505): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6505): handleAsyncCustNotification do not startCustService
I/ActivityManager(  938): Killing 6332:com.google.android.talk/u0a61 (adj 15): empty #11
,D/libc-netbsd(  938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  281): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
W/libprocessgroup(  938): failed to open /acct/uid_10061/pid_6332/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3181): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3181): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3181): networkInfo.isConnected() = false
I/ActivityManager(  938): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6536 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/libc-netbsd(  281): res_queryN name = xxxxx succeed
,I/System.out(  938): propertyValue:false
D/libc-netbsd(  938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  938): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  938): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  281): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out(  938): propertyValue:false
I/DSQN    ( 6387): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6387): restart monitoring
,I/DSQN    ( 6387): dsqn report finish
D/LGDataListener(  281): argv[0]=dsqncommand
D/LGDataListener(  281): argv[1]=wlan0
D/LGDataListener(  281): argv[2]=1
D/LGDataListener(  281): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  938): DSQM DsqnNotification wlan0  1
D/DSQN    (  938): start to monitor internet connection
V/WifiInternetCheck(  938): isHttpConnectionAvailable - We got a valid response : 204
,D/PhoneMonitor( 6536): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6536): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6536): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  938): Killing 6286:com.android.settings/1000 (adj 15): empty #11
,D/PhoneMonitor( 6536): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 6536): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6536): [parse] Load xml
V/TelephonyAutoProfiling( 6536): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6536): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6536): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  938): failed to open /acct/uid_1000/pid_6286/cgroup.procs: No such file or directory
,I/CheckinService( 4128): Checkin interval check for package: unspecified last checkin: 1451956818670 min interval config: 0 actual interval: 25852
,V/DownloadManager( 3204): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3204): DownloadService onCreate
,I/DownloadManager( 3204): in removeSpuriousFiles
I/NotificationManager( 3204): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3204): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3204): created cursor android.database.sqlite.SQLiteCursor@5919f4b on behalf of 3204
I/ActivityManager(  938): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6565 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/CheckinService( 4128): Checking schedule, now: 1451956844580 next: 1451956848619
I/CheckinService( 4128): active receiver: disabled
V/DownloadManager( 3204): DownloadService onStartCommand
,V/DownloadManager( 3204): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 3204): in trimDatabase
V/DownloadManager( 3204): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3204): created cursor android.database.sqlite.SQLiteCursor@f93dbe6 on behalf of 3204
,V/DownloadManager( 3204): created cursor android.database.sqlite.SQLiteCursor@28d8e527 on behalf of 3204
I/ActivityManager(  938): Killing 5690:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 5030): android.os.DeadObjectException
,W/System.err( 5030): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5030): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5030): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5030): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5030): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5030): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5030): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5030): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5030): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5030): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5030): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5030): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5030): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5030): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5030): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5030): android.os.DeadObjectException
W/System.err( 5030): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5030): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5030): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5030): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5030): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5030): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5030): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5030): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5030): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5030): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5030): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5030): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5030): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5030): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5030): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/libprocessgroup(  938): failed to open /acct/uid_10089/pid_5690/cgroup.procs: No such file or directory
,W/ActivityManager(  938): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
D/WeatherAncestor( 2741): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 2:20:44
,I/ActivityManager(  938): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6595 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/DownloadManager( 3204): DownloadService onDestroy
D/UpdateThreadPoolManager( 2741): 2 : This is isUpdating : false
D/WeatherAncestor( 2741): connectivity changed - connection : true
D/Weather_cast( 2741): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2741): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 2:20:45
W/SQLiteConnectionPool( 4128): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/WeatherService( 2741): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  938): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6613 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  938): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2741): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2741): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2741): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6613): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6595): Quickset Services start...
I/UEI.SmartControl( 6595): Manufacture = LGE
,D/UEI.SmartControl( 6595): File observer start...
E/UEI.SmartControl( 6595): IR Port is disabled: false
D/UEI.SmartControl( 6595): Starting file observer...
D/UEI.SmartControl( 6595): Extracting JNI libs...
D/UEI.SmartControl( 6595): --- this system supports 32-bit or 64-bit only
,V/AlarmManager(  938): ELAPSED_WAKEUP set : Alarm{3c64aef0 type 2 when 106783 com.google.android.gms} when 106783
,D/UEI.SmartControl( 6595): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6595): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6595): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 6595): --- Selecting new region: 2
,I/UEI.SmartControl( 6595): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6595): Platform has CIR...
D/UEI.SmartControl( 6595): NO CIR support, need to check package...
I/art     (  938): Explicit concurrent mark sweep GC freed 80418(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.515ms total 225.040ms
,I/UEI.SmartControl( 6595): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6595): QS Service created
E/UEI.SmartControl( 6595): QS start get config
,D/UEI.SmartControl( 6595): Loading JNI Libs...
,D/UEI.SmartControl( 6595):  configuring local db...
,I/Babel_SMS( 6613): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6613): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6613): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6613): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6613): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6613): MmsConfig.loadFromResources
E/Babel_SMS( 6613): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6613): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/art     ( 6613): CheckpointMarkThreadRoots callback created = 0xb042d770
I/art     ( 6613): CheckpointMarkThreadRoots callback created = 0xb042d760
,D/SensorManager( 6613): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6613): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6613): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6613): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6613): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6613): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6613): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6613): found sensor: LGE Step Detector Sensor, handle=43
,D/SensorManager( 6613): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6613): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6613): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6613): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6613): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6613): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6613): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6613): found sensor: Motion Accel, handle=46
D/UEI.SmartControl( 6595):  ---- Has DB8: true
,D/UEI.SmartControl( 6595): QS start statue = true Error code = 0
D/UEI.SmartControl( 6595): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6595): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6595): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6595): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6595): IrrcClient ++ 
,D/irrcClient( 6595): getIrrcService ++ 
W/Settings( 6613): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/irrcClient( 6595): getIrrcService -- 
D/irrcClient( 6595): IrrcClient -- 
W/irrc_jni( 6595): IRRCPlayer_nativeInit -- 
I/Babel_Crash( 6613): startup - clean
D/UEI.SmartControl( 6595): Services init done
,I/UEI.SmartControl( 6595): Device manager: loading config....
D/UEI.SmartControl( 6595): QS Service init finished
I/Babel   ( 6613): deleted: false for 0
D/UEI.SmartControl( 6595): QS Service version name: 0.1.73
D/UEI.SmartControl( 6595): QS Service version code: 1073
D/UEI.SmartControl( 6595): Config is loaded...
D/UEI.SmartControl( 6595): Service requested: Control
D/UEI.SmartControl( 6595): -----IControl: 11
,D/UEI.SmartControl( 6595): Caller: com.lge.qremote
D/UEI.SmartControl( 6595): ------------ IControl registerCallback...
I/UEI.SmartControl( 6595): Registering callback...
D/UEI.SmartControl( 6595): Internal service binding...
D/UEI.SmartControl( 6595): -----IControl: 19
D/UEI.SmartControl( 6595): Caller: com.lge.qremote
I/UEI.SmartControl( 6595): Registering Services Ready callback...
I/UEI.SmartControl( 6595): Notify client services are ready...
D/UEI.SmartControl( 6595): -----IControl: 8
D/UEI.SmartControl( 6595): Caller: com.lge.qremote
,D/UEI.SmartControl( 6595):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6595): Notify AllClients services are ready: 0
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  938): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6658 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  938): Killing 6310:com.lge.sync/1000 (adj 15): empty #11
,W/libprocessgroup(  938): failed to open /acct/uid_1000/pid_6310/cgroup.procs: No such file or directory
,W/AudioCapabilities( 6613): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6613): Unsupported mime audio/adpcm
,W/AudioCapabilities( 6613): Unsupported mime audio/g726
W/AudioCapabilities( 6613): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6613): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6613): Unsupported mime video/mjpg
,W/VideoCapabilities( 6613): Unsupported mime video/theora
W/AudioCapabilities( 6613): Unsupported mime audio/evrc
,W/AudioCapabilities( 6613): Unsupported mime audio/qcelp
W/VideoCapabilities( 6613): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6613): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6613): Unsupported mime audio/qcelp
W/AudioCapabilities( 6613): Unsupported mime audio/evrc
W/VideoCapabilities( 6613): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6613): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6613): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6613): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6613): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6613): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6613): onServiceConnected
,W/Babel   ( 6613): Attempted to change video mute state without an active call.
I/NotificationManager( 6613): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6613): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6613): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6613): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6613): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  281): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out( 6613): propertyValue:false
,I/Babel   ( 6613): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  938): Killing 5030:com.lge.qremote/u0a106 (adj 15): empty #11
,W/libprocessgroup(  938): failed to open /acct/uid_10106/pid_5030/cgroup.procs: No such file or directory
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6658): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6658): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6658): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6658): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6658): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6658):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6658):   adb logcat -s GAv4
W/GAv4    ( 6658): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6658): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6658): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 6658): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6658): Time to load native libraries: 1 ms (timestamps 8348-8349)
I/LibraryLoader( 6658): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6658): Binding Chromium to main looper Looper (main, tid 1) {1904e058}
I/LibraryLoader( 6658): Expected native library version number "",actual native library version number ""
I/chromium( 6658): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/BrowserStartupController( 6658): Initializing chromium process, singleProcess=true
W/art     ( 6658): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6658): ApplicationContext is null in ApplicationStatus
W/chromium( 6658): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6658): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6658): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6658): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6658): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6658): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6658): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6658): Remote Branch: 
I/Adreno-EGL( 6658): Local Patches: 
I/Adreno-EGL( 6658): Reconstruct Branch: 
I/ActivityManager(  938): Process com.google.android.music:main (pid 6418) has died
,V/AudioPolicyService(  285): registerClient() client 0xb551c640, uid 10079
,W/AudioManagerAndroid( 6658): Requires BLUETOOTH permission
I/NSApplication( 6658): Starting up...
,I/ActivityManager(  938): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6722 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/ActivityManager(  938): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6741 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  938): Killing 6447:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  938): failed to open /acct/uid_10021/pid_6447/cgroup.procs: No such file or directory
,W/ResourcesManager( 6741): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  938): Killing 6481:com.lge.lgdmsclient/1000 (adj 15): empty #11
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/libprocessgroup(  938): failed to open /acct/uid_1000/pid_6481/cgroup.procs: No such file or directory
,V/AlarmManager(  938): RTC_WAKEUP set : Alarm{3a95af7b type 0 when 1451956848016 com.google.android.googlequicksearchbox} when 1451956848016
I/ActivityManager(  938): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6769 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  306): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 20.897ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 20.516ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 20.715ms
,I/MusicStore( 6769): Database version: 120
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6769): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6769): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6769): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6769): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6769): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6769): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6769): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6769): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@276fc8a3: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6769): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6769): GMSCore installation verified
I/ConfigStore( 6769): Config Database version: 1
,I/MediaRouter( 6769): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6769): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6769): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6769): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  938): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6797 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/GHttpClientFactory( 6769): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 6769): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  938): Killing 6505:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/ResourcesManager( 6797): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6797): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6797): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  938): failed to open /acct/uid_10011/pid_6505/cgroup.procs: No such file or directory
,I/NotificationManager( 6769): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6797): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6797): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6797): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  938): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6829 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6797): JNI_OnLoad()
I/HubEmail( 6797): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/HubEmail( 6797): registerNatives()
I/HubEmail( 6797): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6797): registerNativeMethods()
I/HubEmail( 6797): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6797): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  938): Killing 6536:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  938): failed to open /acct/uid_10038/pid_6536/cgroup.procs: No such file or directory
,W/Settings( 6797): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 6829): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6829): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6829): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6829): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6829): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6829): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6829): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6829): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  938): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6853 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6829): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6829): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6829): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6829): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6829): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 6829): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  938): Killing 6565:com.lge.drmservice/u0a51 (adj 15): empty #11
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/libprocessgroup(  938): failed to open /acct/uid_10051/pid_6565/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 6853): onCreate
,W/AppUp4:DB( 6853):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6853):  setFingerPrint start
I/AppUp4:DB( 6853):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6853):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6853):  SDK version = 0
I/AppUp4:DB( 6853):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 6853): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6853): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6853): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6853): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6853): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6853): onReceive
I/AppUp4:CustModeStarterReceiver( 6853): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6853): Context : android.app.ReceiverRestrictedContext@23bc0a57
,D/AppUp4:CustFacade( 6853): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6853): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6853): begin check event
I/AppUp4:CustModeStarterReceiver( 6853): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6853): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6853): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6853): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6853): handleAsyncCustNotification do not startCustService
I/ActivityManager(  938): Killing 6595:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/libprocessgroup(  938): failed to open /acct/uid_10089/pid_6595/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3181): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3181): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3181): networkInfo.isConnected() = false
I/ActivityManager(  938): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6875 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6875): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6875): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6875): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  938): Killing 6613:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  938): failed to open /acct/uid_10061/pid_6613/cgroup.procs: No such file or directory
,V/DownloadManager( 3204): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3204): DownloadService onCreate
,I/NotificationManager( 3204): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3204): in removeSpuriousFiles
V/DownloadManager( 3204): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/PhoneMonitor( 6875): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6875): [loadFeatureFromXml] *** start feature loading from xml
V/DownloadManager( 3204): created cursor android.database.sqlite.SQLiteCursor@1f59897d on behalf of 3204
D/TelephonyAutoProfiling( 6875): [parse] Load xml
V/TelephonyAutoProfiling( 6875): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6875): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
I/DownloadManager( 3204): in trimDatabase
V/DownloadManager( 3204): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3204): created cursor android.database.sqlite.SQLiteCursor@764acc3 on behalf of 3204
,D/PhoneMonitor( 6875): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/ActivityManager(  938): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6904 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/AlarmManager(  938): RTC_WAKEUP set : Alarm{3e03fd2b type 0 when 1451956848619 com.google.android.gms} when 1451956848619
V/DownloadManager( 3204): DownloadService onStartCommand
I/ActivityManager(  938): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6914 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  938): RTC_WAKEUP set : Alarm{19181588 type 0 when 1451956850628 com.android.vending} when 1451956850628
,I/CheckinService( 4128): Checkin interval check for package: unspecified last checkin: 1451956818670 min interval config: 0 actual interval: 32050
V/DownloadManager( 3204): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3204): created cursor android.database.sqlite.SQLiteCursor@57a4079 on behalf of 3204
,I/CheckinService( 4128): Checking schedule, now: 1451956850776 next: 1451956848619
I/CheckinService( 4128): active receiver: enabled
V/DownloadManager( 3204): DownloadService onDestroy
,I/CheckinService( 4128): Preparing to send checkin request
I/EventLogService( 4128): Accumulating logs since 1451956811129
,D/WeatherAncestor( 2741): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 2:20:50
,D/UpdateThreadPoolManager( 2741): 2 : This is isUpdating : false
D/WeatherAncestor( 2741): connectivity changed - connection : true
D/Weather_cast( 2741): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2741): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 2:20:50
D/WeatherService( 2741): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/CheckinRequestBuilder( 4128): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  938): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6945 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  938): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,E/ActivityThread( 4128): Failed to find provider info for com.google.android.wearable.settings
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/Weather.Utils( 2741): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2741): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2741): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6945): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Finsky  ( 6914): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/art     (  938): Explicit concurrent mark sweep GC freed 22214(1219KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.718ms total 175.170ms
,I/jxcore-log( 6108): Test app app.js loaded
I/jxcore-log( 6108): 
,I/Choreographer( 6108): Skipped 784 frames!  The application may be doing too much work on its main thread.
I/chromium( 6108): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/Babel_SMS( 6945): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6945): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6945): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6945): MmsConfig.loadFromDatabase
,D/Finsky  ( 6914): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 6914): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6914): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6914): com.android.vending: cancel(-1050172287) by com.android.vending
,E/Babel_SMS( 6945): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6945): MmsConfig.loadFromResources
E/Babel_SMS( 6945): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6945): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 6945): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6945): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6945): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6945): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6945): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6945): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6945): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6945): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6945): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6945): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6945): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6945): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6945): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6945): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6945): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6945): found sensor: Motion Accel, handle=46
,I/art     ( 6945): CheckpointMarkThreadRoots callback created = 0xb042d8f0
,I/art     ( 6945): CheckpointMarkThreadRoots callback created = 0xb042d8c0
,I/ActivityManager(  938): Process com.google.android.apps.magazines (pid 6658) has died
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 3204): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3204): created cursor android.database.sqlite.SQLiteCursor@1c5b521f on behalf of 6914
,W/Settings( 6945): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6945): startup - clean
D/Finsky  ( 6914): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6914): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 6914): Skipping gmscore version check
,D/Finsky  ( 6914): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 6914): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Babel   ( 6945): deleted: false for 0
I/ActivityManager(  938): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6997 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  938): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7014 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6997): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6997): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/AudioCapabilities( 6945): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6945): Unsupported mime audio/adpcm
W/AudioCapabilities( 6945): Unsupported mime audio/g726
,W/AudioCapabilities( 6945): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6945): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6945): Unsupported mime video/mjpg
W/VideoCapabilities( 6945): Unsupported mime video/theora
,W/AudioCapabilities( 6945): Unsupported mime audio/evrc
,W/AudioCapabilities( 6945): Unsupported mime audio/qcelp
W/VideoCapabilities( 6945): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6945): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6945): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6945): Unsupported mime audio/evrc
W/VideoCapabilities( 6945): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6945): Unsupported profile 4 for video/mp4v-es
,D/Finsky  ( 6914): [875] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 6914): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
W/VideoCapabilities( 6945): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6945): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6945): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6945): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6945): onServiceConnected
W/Babel   ( 6945): Attempted to change video mute state without an active call.
I/NotificationManager( 6945): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6945): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6945): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6945): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6945): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  281): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out( 6945): propertyValue:false
I/MultiDex( 6997): VM with version 2.1.0 has multidex support
I/MultiDex( 6997): install
I/MultiDex( 6997): VM has multidex support, MultiDex support library is disabled.
,I/Babel   ( 6945): connection state changed from UNKNOWN to CONNECTED
,V/JNIHelp ( 6997): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,W/ActivityThread( 6997): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6997): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3c8bdd28: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6997): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6997): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6997): com.google.android.gms: cancel(39789) by com.google.android.gms
I/GAv4    ( 7014): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7014):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7014):   adb logcat -s GAv4
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7014): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7014): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
I/art     ( 6997): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6997): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
W/ContextImpl( 7014): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
W/GAv4    ( 7014): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7014): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 7014): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  938): Killing 6722:com.android.chrome/u0a48 (adj 15): empty #11
W/GAv4    ( 7014): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  938): failed to open /acct/uid_10048/pid_6722/cgroup.procs: No such file or directory
,D/NativeLibraryUtils( 6997): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  285): Instantiating CDM.
,I/WVCdm   (  285): CdmEngine::OpenSession
I/WVCdm   (  285): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  285): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/WVCdm   (  285): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  285): L1 library not specified. Falling Back to L3
I/WVCdm   (  285): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  285): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  285): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  285): CdmEngine::GenerateKeyRequest
D/WVCdm   (  285): PrepareKeyRequest: nonce=356234839
I/WebViewFactory( 7014): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/ActivityManager(  938): Process com.google.android.music:main (pid 6769) has died
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 114262267513; DSPS: 3842173; Offset : -3001201843
,I/LibraryLoader( 7014): Time to load native libraries: 2 ms (timestamps 4290-4292)
I/LibraryLoader( 7014): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7014): Binding Chromium to main looper Looper (main, tid 1) {1904e058}
I/LibraryLoader( 7014): Expected native library version number "",actual native library version number ""
I/chromium( 7014): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7014): Initializing chromium process, singleProcess=true
W/art     ( 7014): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7014): ApplicationContext is null in ApplicationStatus
W/chromium( 7014): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7014): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7014): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7014): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7014): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7014): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7014): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7014): Remote Branch: 
I/Adreno-EGL( 7014): Local Patches: 
I/Adreno-EGL( 7014): Reconstruct Branch: 
I/art     ( 6997): CheckpointMarkThreadRoots callback created = 0xb042d570
,I/art     ( 6997): CheckpointMarkThreadRoots callback created = 0xb042d560
,V/AudioPolicyService(  285): registerClient() client 0xb551cd60, uid 10079
I/NSApplication( 7014): Starting up...
W/AudioManagerAndroid( 7014): Requires BLUETOOTH permission
I/ActivityManager(  938): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7079 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/dex2oat ( 7080): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/ActivityManager(  938): Process com.lge.email (pid 6797) has died
,I/dex2oat ( 7080): dex2oat took 108.673ms (threads: 4)
,I/Adreno-EGL( 6997): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6997): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6997): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6997): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6997): Remote Branch: 
I/Adreno-EGL( 6997): Local Patches: 
I/Adreno-EGL( 6997): Reconstruct Branch: 
,I/Adreno-EGL( 6997): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6997): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6997): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6997): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6997): Remote Branch: 
I/Adreno-EGL( 6997): Local Patches: 
I/Adreno-EGL( 6997): Reconstruct Branch: 
,I/Adreno-EGL( 6997): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6997): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6997): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6997): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6997): Remote Branch: 
I/Adreno-EGL( 6997): Local Patches: 
I/Adreno-EGL( 6997): Reconstruct Branch: 
,I/ActivityManager(  938): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7105 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  306): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 295us total 22.960ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 305us total 20.546ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 20.045ms
,I/MusicStore( 7105): Database version: 120
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7105): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7105): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7105): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/WVCdm   (  285): CdmEngine::OpenSession
W/ResourcesManager( 7105): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7105): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7105): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7105): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7105): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@276fc8a3: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7105): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7105): GMSCore installation verified
I/ConfigStore( 7105): Config Database version: 1
,I/art     ( 6162): Explicit concurrent mark sweep GC freed 2052(88KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 379us total 25.635ms
,I/MediaRouter( 7105): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7105): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7105): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7105): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  938): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7139 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7105): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7105): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  938): Killing 6829:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/ResourcesManager( 7139): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7139): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7139): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  938): failed to open /acct/uid_1000/pid_6829/cgroup.procs: No such file or directory
,I/NotificationManager( 7105): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 7139): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7139): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/WVCdm   (  285): CdmEngine::CloseSession
,I/WVCdm   (  285): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  285): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  285): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  285): CdmEngine::GenerateKeyRequest
D/eas_req ( 7139): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
D/WVCdm   (  285): PrepareKeyRequest: nonce=1307255312
I/ActivityManager(  938): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7172 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/HubEmail( 7139): JNI_OnLoad()
I/HubEmail( 7139): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7139): registerNatives()
I/HubEmail( 7139): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7139): registerNativeMethods()
I/HubEmail( 7139): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7139): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 7139): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  938): Killing 6853:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  938): failed to open /acct/uid_10011/pid_6853/cgroup.procs: No such file or directory
D/LGDMClient( 7172): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7172): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7172): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7172): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7172): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7172): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7172): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 7172): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  938): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7196 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7172): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7172): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7172): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
,D/LGDMClient( 7172): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7172): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
I/MusicWidget( 2666): mDelayedStopHandler : unbind
,D/LGDMClient( 7172): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  938): Killing 6875:com.google.android.setupwizard/u0a38 (adj 15): empty #11
I/MusicBrowser( 2758): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2758): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2758): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2758): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2758): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2758): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
,W/libprocessgroup(  938): failed to open /acct/uid_10038/pid_6875/cgroup.procs: No such file or directory
I/MusicBrowser( 2758): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2758): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  938):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@1b7f5b74com.lge.music.MediaPlaybackService$6@32cf789d
,D/MusicBrowser( 2758): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
,I/MusicBrowser( 2758): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2758): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2758): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2758): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@1f0cf4f3
I/MusicBrowser( 2758): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2758): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2758): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2758): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2758): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2758): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2758): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2758): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2758): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2758): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2758): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2758): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2758): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2758): reset
V/MediaPlayer[Native]( 2758): setListener
V/MediaPlayer[Native]( 2758): disconnect
V/MediaPlayer[Native]( 2758): destructor
,V/AudioFlinger(  285): releasing 19 from 2758 for -1
V/AudioFlinger(  285):  decremented refcount to 0
V/AudioFlinger(  285): purging stale effects
V/MediaPlayer[Native]( 2758): disconnect
D/MusicBrowser( 2758): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2758): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2758): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2758): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2758): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2758): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2758): [SmartShareManagerClient] unregisterListener: 1065640210
W/SmartShareClient( 2758): [SmartShareManagerClient] unregisterListener invalid listener: 1065640210
I/SmartShareClient( 2758): [SmartShareManagerClient] terminate service: 2758/MediaPlaybackService/693043185
E/HomeCloudIF( 2758): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2758): [SmartShareManagerClient] unbindService context:android.app.Application@6dd00e3
,V/CloudHub( 2758): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2758): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2758): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2758): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,D/MusicBrowser( 2758): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
,I/ActivityManager(  938): Killing 6904:com.lge.drmservice/u0a51 (adj 15): empty #11
I/CloudHub( 2758): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29976
,I/art     (  938): Explicit concurrent mark sweep GC freed 18829(863KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.242ms total 171.001ms
,I/AppUp4:AppBoxCP( 7196): onCreate
,W/AppUp4:DB( 7196):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7196):  setFingerPrint start
I/AppUp4:DB( 7196):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7196):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7196):  SDK version = 0
I/AppUp4:DB( 7196):  beforefinger == newfinger no write in DB
W/libprocessgroup(  938): failed to open /acct/uid_10051/pid_6904/cgroup.procs: No such file or directory
,D/AppUp4:AppBoxApplication( 7196): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7196): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7196): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7196): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7196): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7196): onReceive
I/AppUp4:CustModeStarterReceiver( 7196): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7196): Context : android.app.ReceiverRestrictedContext@23bc0a57
D/AppUp4:CustFacade( 7196): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7196): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7196): begin check event
I/AppUp4:CustModeStarterReceiver( 7196): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7196): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7196): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7196): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7196): handleAsyncCustNotification do not startCustService
I/ActivityManager(  938): Killing 6914:com.android.vending/u0a36 (adj 15): empty #11
,W/libprocessgroup(  938): failed to open /acct/uid_10036/pid_6914/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3181): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3181): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3181): networkInfo.isConnected() = true
D/PhoneState( 3181): setPdpRejectCasuse : false
I/ActivityManager(  938): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7215 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7215): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7215): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7215): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  938): Killing 6945:com.google.android.talk/u0a61 (adj 15): empty #11
,D/PhoneMonitor( 7215): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7215): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7215): [parse] Load xml
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/TelephonyAutoProfiling( 7215): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7215): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7215): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  938): failed to open /acct/uid_10061/pid_6945/cgroup.procs: No such file or directory
,I/CheckinService( 4128): Checkin interval check for package: unspecified last checkin: 1451956818670 min interval config: 0 actual interval: 37390
,V/DownloadManager( 3204): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3204): DownloadService onCreate
I/NotificationManager( 3204): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,I/DownloadManager( 3204): in removeSpuriousFiles
V/DownloadManager( 3204): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3204): created cursor android.database.sqlite.SQLiteCursor@8e1996c on behalf of 3204
I/DownloadManager( 3204): in trimDatabase
V/DownloadManager( 3204): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3204): created cursor android.database.sqlite.SQLiteCursor@1d06fbca on behalf of 3204
I/ActivityManager(  938): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7245 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3204): DownloadService onStartCommand
V/DownloadManager( 3204): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3204): created cursor android.database.sqlite.SQLiteCursor@1904e058 on behalf of 3204
,I/ActivityManager(  938): Killing 7014:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,E/libprocessgroup(  938): failed to kill 1 processes for processgroup 7014
,D/WeatherAncestor( 2741): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 2:20:56
,V/DownloadManager( 3204): DownloadService onDestroy
D/UpdateThreadPoolManager( 2741): 2 : This is isUpdating : false
D/WeatherAncestor( 2741): connectivity changed - connection : true
D/Weather_cast( 2741): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2741): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 2:20:56
D/WeatherService( 2741): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  938): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7265 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  938): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2741): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2741): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2741): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 7265): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7265): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7265): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7265): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7265): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7265): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7265): MmsConfig.loadFromResources
E/Babel_SMS( 7265): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7265): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7265): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7265): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7265): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7265): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7265): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7265): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7265): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7265): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7265): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7265): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7265): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7265): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7265): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7265): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7265): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7265): found sensor: Motion Accel, handle=46
,I/WVCdm   (  285): CdmEngine::CloseSession
I/WVCdm   (  285): L3 Terminate.
,W/Settings( 7265): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7265): startup - clean
I/CheckinRequestBuilder( 4128): Classify the device as Phone.
,I/art     ( 7265): CheckpointMarkThreadRoots callback created = 0xaaf3bb30
,I/Babel   ( 7265): deleted: false for 0
D/libc-netbsd( 4128): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4128): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4128): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4128): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  281): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
,I/art     ( 7265): CheckpointMarkThreadRoots callback created = 0xaaf3bb00
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out( 4128): propertyValue:false
,I/ActivityManager(  938): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7307 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
W/AudioCapabilities( 7265): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7265): Unsupported mime audio/adpcm
D/libc-netbsd( 4128): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4128): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/AudioCapabilities( 7265): Unsupported mime audio/g726
W/AudioCapabilities( 7265): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7265): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7265): Unsupported mime video/mjpg
W/VideoCapabilities( 7265): Unsupported mime video/theora
,D/libc-netbsd( 4128): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4128): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4128): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4128): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/CheckinTask( 4128): Sending checkin request (9796 bytes)
W/AudioCapabilities( 7265): Unsupported mime audio/evrc
W/AudioCapabilities( 7265): Unsupported mime audio/qcelp
W/VideoCapabilities( 7265): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7265): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7265): Unsupported mime audio/qcelp
W/AudioCapabilities( 7265): Unsupported mime audio/evrc
W/VideoCapabilities( 7265): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7265): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7265): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7265): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7265): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7265): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7265): onServiceConnected
W/Babel   ( 7265): Attempted to change video mute state without an active call.
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7307): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,I/NotificationManager( 7265): com.google.android.talk: cancel(10436) by com.google.android.talk
W/ContextImpl( 7307): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
D/libc-netbsd( 7265): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7265): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7265): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7265): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  281): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
,D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/GAv4    ( 7307): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7307):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7307):   adb logcat -s GAv4
I/System.out( 7265): propertyValue:false
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7307): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,W/GAv4    ( 7307): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7307): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/Babel   ( 7265): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  938): Killing 7079:com.android.chrome/u0a48 (adj 15): empty #11
W/GAv4    ( 7307): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 7307): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  938): failed to open /acct/uid_10048/pid_7079/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 4128): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4128): Failed to find provider info for com.google.android.wearable.settings
I/WebViewFactory( 7307): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/art     ( 6741): CheckpointMarkThreadRoots callback created = 0xaaf06f20
,I/LibraryLoader( 7307): Time to load native libraries: 2 ms (timestamps 9170-9172)
I/LibraryLoader( 7307): Expected native library version number "",actual native library version number ""
I/art     ( 6741): CheckpointMarkThreadRoots callback created = 0xaaf06f10
,V/WebViewChromiumFactoryProvider( 7307): Binding Chromium to main looper Looper (main, tid 1) {1904e058}
I/LibraryLoader( 7307): Expected native library version number "",actual native library version number ""
I/chromium( 7307): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7307): Initializing chromium process, singleProcess=true
W/art     ( 7307): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7307): ApplicationContext is null in ApplicationStatus
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/chromium( 7307): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7307): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7307): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7307): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7307): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7307): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7307): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7307): Remote Branch: 
I/Adreno-EGL( 7307): Local Patches: 
I/Adreno-EGL( 7307): Reconstruct Branch: 
I/CheckinRequestBuilder( 4128): Classify the device as Phone.
,I/CheckinTask( 4128): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4128): Checking schedule, now: 1451956857852 next: 1452484106847
I/CheckinService( 4128): active receiver: disabled
,I/QCNEJ   ( 1841): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-05 02:20:57.877 DNS addrs= 192.168.1.1, 0.0.0.0, 
V/AudioPolicyService(  285): registerClient() client 0xb4027180, uid 10079
,W/AudioManagerAndroid( 7307): Requires BLUETOOTH permission
I/CheckinService( 4128): Checking schedule, now: 1451956857897 next: 1452484106847
I/CheckinService( 4128): active receiver: disabled
I/NSApplication( 7307): Starting up...
D/CheckinService( 4128): Recording last checkin time for package unspecified as 1451956857907
,I/ActivityManager(  938): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7374 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  938): Killing 6741:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  938): Killing 7139:com.lge.email/u0a21 (adj 15): empty #11
,I/ActivityManager(  938): Killing 7105:com.google.android.music:main/u0a81 (adj 15): empty #12
,W/libprocessgroup(  938): failed to open /acct/uid_10086/pid_6741/cgroup.procs: No such file or directory
,W/libprocessgroup(  938): failed to open /acct/uid_10021/pid_7139/cgroup.procs: No such file or directory
W/libprocessgroup(  938): failed to open /acct/uid_10081/pid_7105/cgroup.procs: No such file or directory
I/ActivityManager(  938): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7393 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  938): Killing 7172:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  938): failed to open /acct/uid_1000/pid_7172/cgroup.procs: No such file or directory
,W/ResourcesManager( 7393): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  938): Killing 2758:com.lge.music/u0a28 (adj 15): empty #11
,V/AudioFlinger(  285): 2758 died, releasing its sessions
V/AudioFlinger(  285):  pid 1746 @ 0
V/AudioFlinger(  285):  pid 3181 @ 1
V/AudioFlinger(  285):  pid 3181 @ 2
,W/libprocessgroup(  938): failed to open /acct/uid_10028/pid_2758/cgroup.procs: No such file or directory
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  281): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  938): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7422 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,D/libc-netbsd(  281): res_queryN name = xxxxx succeed
,I/System.out( 1732): propertyValue:false
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/ResourcesManager( 7422): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/BluetoothManagerService(  938): Message: 20
,D/BluetoothManagerService(  938): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2db17a36:true
D/BluetoothAdapterService(252336994)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@37ab5ac8
D/BluetoothAdapterService(252336994)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@37ab5ac8
,I/ActivityManager(  938): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7442 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7422): Create singleton instance
I/art     (  306): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 343us total 24.949ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 23.963ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 370us total 23.064ms
,D/UEI.SmartControl( 7442): Quickset Services start...
,I/UEI.SmartControl( 7442): Manufacture = LGE
I/AudioManager( 7422): getMode name:com.lge.qremote
,D/UEI.SmartControl( 7442): File observer start...
E/UEI.SmartControl( 7442): IR Port is disabled: false
D/UEI.SmartControl( 7442): Starting file observer...
D/UEI.SmartControl( 7442): Extracting JNI libs...
D/UEI.SmartControl( 7442): --- this system supports 32-bit or 64-bit only
I/CheckinService( 4128): Checkin interval check for package: unspecified last checkin: 1451956857907 min interval config: 0 actual interval: 1175
,I/CheckinService( 4128): Checking schedule, now: 1451956859089 next: 1452484106847
I/CheckinService( 4128): active receiver: disabled
D/WearableService( 1732): callingUid 10006, callindPid: 1732
,W/ContextImpl( 3538): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
E/MDM     ( 1732): [84] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 4128): Restart initialization of location
,D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
,W/GCoreFlp( 1732): No location to return for getLastLocation()
,W/FusedLocationProvider( 1732): location=null
V/SetupWizard( 7215): Connected to Gservices successfully
,D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/UEI.SmartControl( 7442): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7442): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7442): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,V/AlarmManager(  938): ELAPSED_WAKEUP set : Alarm{295f0cd4 type 2 when 120712 android} when 120712
,I/UEI.SmartControl( 7442): --- Selecting new region: 2
I/UEI.SmartControl( 7442): -- Running on KitKat(19) and above! JNI will be used.
I/AudioManager( 7422): getMode name:com.lge.qremote
D/UEI.SmartControl( 7442): Platform has CIR...
D/UEI.SmartControl( 7442): NO CIR support, need to check package...
,I/UEI.SmartControl( 7442): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7442): QS Service created
D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,E/UEI.SmartControl( 7442): QS start get config
,D/UEI.SmartControl( 7442): Loading JNI Libs...
,D/UEI.SmartControl( 7442):  configuring local db...
I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
,I/[SystemUI]Clock( 1371): called onTimeUpdated()
I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
,I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/UEI.SmartControl( 7442):  ---- Has DB8: true
,D/UEI.SmartControl( 7442): QS start statue = true Error code = 0
D/UEI.SmartControl( 7442): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7442): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7442): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7442): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7442): IrrcClient ++ 
D/irrcClient( 7442): getIrrcService ++ 
,D/irrcClient( 7442): getIrrcService -- 
D/irrcClient( 7442): IrrcClient -- 
W/irrc_jni( 7442): IRRCPlayer_nativeInit -- 
I/UEI.SmartControl( 7442): Device manager: loading config....
D/UEI.SmartControl( 7442): Services init done
D/UEI.SmartControl( 7442): QS Service init finished
D/UEI.SmartControl( 7442): Config is loaded...
,D/UEI.SmartControl( 7442): QS Service version name: 0.1.73
D/UEI.SmartControl( 7442): QS Service version code: 1073
D/UEI.SmartControl( 7442): Service requested: Control
D/UEI.SmartControl( 7442): Internal service binding...
D/UEI.SmartControl( 7442): -----IControl: 11
D/UEI.SmartControl( 7442): Caller: com.lge.qremote
D/UEI.SmartControl( 7442): ------------ IControl registerCallback...
I/UEI.SmartControl( 7442): Registering callback...
,D/UEI.SmartControl( 7442): -----IControl: 19
D/UEI.SmartControl( 7442): Caller: com.lge.qremote
I/UEI.SmartControl( 7442): Registering Services Ready callback...
I/UEI.SmartControl( 7442): Notify client services are ready...
D/UEI.SmartControl( 7442): -----IControl: 8
D/UEI.SmartControl( 7442): Caller: com.lge.qremote
I/AudioManager( 7422): getMode name:com.lge.qremote
,D/UEI.SmartControl( 7442):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 7442): Notify AllClients services are ready: 0
,I/art     (  938): Explicit concurrent mark sweep GC freed 17674(857KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.338ms total 140.592ms
,I/AudioManager( 7422): getMode name:com.lge.qremote
I/AudioManager( 7422): getMode name:com.lge.qremote
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/PowerManagerServiceEx(  938): acquireWakeLockInternal: lock=571089472, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=938
,D/WeatherService( 2741): 2 : TimeTick Intent has been received, Time(hour:min:sec) 2:21:0
D/WeatherService( 2741): 2 : TimeTick Intent And Screen On
D/WeatherService( 2741): 2 : SDK version : 21
W/ActivityManager(  938): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2741): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2741): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2741): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2741): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2741): 2 : This is isUpdating : false
D/WeatherService( 2741): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2741): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2741): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2741): 2 : Fixed theme : optimus
D/WeatherReflect( 2741): 2 : Map key string is -2
,D/lim     ( 2741): 2 : time = 02:21
,I/WeatherReflect( 2741): Model Name : LG-D722
D/WeatherTheme( 2741): 2 : Different view - status_min_formatted : 20 != 21
D/WeatherTheme( 2741): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2741): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2741): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2741): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2741): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2741): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/Weather4x2_optimus( 2741): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2741): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2741): forecast size is 0
,D/Theme   ( 2741): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2741): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2741): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2741): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2741): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2741): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2741): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2741): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2741): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2741): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2741): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2741): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2741): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2741): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2741): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2741): url is : null
D/Theme   ( 2741): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2741): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2741): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2741): 2 : update view, appWidgetId: 2
,D/WeatherService( 2741): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 2:21:0
D/PowerManagerServiceEx(  938): releaseWakeLockInternal: lock=571089472 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[SystemUI]QPairHandler( 1371): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader(  938): Reconfiguring input devices.  changes=0x00000010
,I/QCNEJ   ( 1841): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[SystemUI]QSlideListController( 1371): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1841): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1841): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-05 02:21:00.92 DNS addrs= 192.168.1.1, 0.0.0.0, 
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
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
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/AppUp4:CustModeStarterReceiver( 7196): onReceive
,I/AppUp4:CustModeStarterReceiver( 7196): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 7196): Context : android.app.ReceiverRestrictedContext@23bc0a57
D/AppUp4:CustFacade( 7196): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7196): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7196): begin check event
I/AppUp4:CustModeStarterReceiver( 7196): Event For Nothing, skip.
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/administrator(  938): Handling package changes for user 0
,I/art     ( 1787): Background sticky concurrent mark sweep GC freed 90107(5MB) AllocSpace objects, 0(0B) LOS objects, 36% free, 8MB/14MB, paused 1.121ms total 119.059ms
,I/ActivityManager(  938): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7529 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/ActivityManager(  938): Process com.google.android.apps.magazines (pid 7307) has died
,I/NotificationManager( 7265): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 7265): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7265): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 7529): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7529): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7529): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
V/JNIHelp ( 7265): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/LCardEmulationManager( 1787): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1787): getDefaultRoute
,I/NotificationService(  938): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  938): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  938): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  938): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/System  ( 7265): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7265): Installed default security provider GmsCore_OpenSSL
V/BackupManagerService(  938): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  938): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@16107e56
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/ResourcesManager(  938): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/AppConfig( 7529): Total System Memory = 906309632
I/GalleryUtils( 7529): Application Heap = 96 MB
I/AppConfig( 7529): App Tier : NOT_DEF
,D/SystemHelper( 7529): region [EU], country [EU], operator [OPEN], sub-operator []
W/ResourceType(  938): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  938): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7551 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1732): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  938): applying state to connected service
W/ResourcesManager( 7551): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7551): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7551): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7551): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7551): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/SystemConfig( 7551): BUILD Country: EU
I/SystemConfig( 7551): BUILD Operator: OPEN
,I/ActivityManager(  938): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7571 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 7551): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7551): existFile = false
I/SystemConfig( 7551): canReadFile = false
I/SystemConfig( 7551): systemFeature RCS result false
D/SystemConfig( 7551): refreshRcsSupport() :false
,I/ActivityManager(  938): Killing 7245:com.lge.drmservice/u0a51 (adj 15): empty #11
,I/LockScreenSettings( 7571): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,W/libprocessgroup(  938): failed to open /acct/uid_10051/pid_7245/cgroup.procs: No such file or directory
,D/LockScreenSettings( 7571): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7571): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,D/LockScreenSettings( 7571): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7571): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7571): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/UpdateIcingCorporaServi( 1940): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
,I/ActivityManager(  938): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7595 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 7393): CheckpointMarkThreadRoots callback created = 0xb042d4b0
I/art     ( 7393): CheckpointMarkThreadRoots callback created = 0xb042d490
,I/ActivityManager(  938): Killing 7374:com.android.chrome/u0a48 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1940): UpdateCorporaTask done [took 109 ms] updated apps [took 109 ms] 
,W/libprocessgroup(  938): failed to open /acct/uid_10048/pid_7374/cgroup.procs: No such file or directory
,D/Finsky  ( 7595): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/Finsky  ( 7595): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7595): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7595): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 7595): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3204): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3204): created cursor android.database.sqlite.SQLiteCursor@2d810a96 on behalf of 7595
D/Finsky  ( 7595): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7595): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7595): Skipping gmscore version check
I/ActivityManager(  938): Killing 7215:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  938): failed to open /acct/uid_10038/pid_7215/cgroup.procs: No such file or directory
,D/Finsky  ( 7595): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 4128): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 4128): Null package name or gms related package.  Ignoreing.
,D/Finsky  ( 7595): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 4128): updateResources: need to parse f{com.google.android.gms}
,I/Icing   ( 4128): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4128): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  938): Killing 7442:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 7422): android.os.DeadObjectException
,W/System.err( 7422): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7422): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7422): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7422): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7422): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7422): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7422): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7422): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7422): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7422): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7422): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7422): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7422): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7422): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7422): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7422): android.os.DeadObjectException
W/System.err( 7422): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7422): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7422): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7422): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7422): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7422): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7422): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7422): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7422): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7422): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7422): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7422): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7422): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7422): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7422): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  938): failed to open /acct/uid_10089/pid_7442/cgroup.procs: No such file or directory
,W/ActivityManager(  938): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/ActivityManager(  938): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7645 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 7645): Quickset Services start...
,I/UEI.SmartControl( 7645): Manufacture = LGE
D/UEI.SmartControl( 7645): File observer start...
E/UEI.SmartControl( 7645): IR Port is disabled: false
D/UEI.SmartControl( 7645): Starting file observer...
D/UEI.SmartControl( 7645): Extracting JNI libs...
D/UEI.SmartControl( 7645): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7645): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7645): --- Checking lib: libqs_armeabi-v7a.zip
,D/UEI.SmartControl( 7645): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7645): --- Selecting new region: 2
,I/UEI.SmartControl( 7645): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7645): Platform has CIR...
D/UEI.SmartControl( 7645): NO CIR support, need to check package...
I/UEI.SmartControl( 7645): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7645): QS Service created
E/UEI.SmartControl( 7645): QS start get config
,D/UEI.SmartControl( 7645): Loading JNI Libs...
,D/UEI.SmartControl( 7645):  configuring local db...
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/UEI.SmartControl( 7645):  ---- Has DB8: true
,D/UEI.SmartControl( 7645): QS start statue = true Error code = 0
D/UEI.SmartControl( 7645): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7645): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7645): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7645): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7645): IrrcClient ++ 
D/irrcClient( 7645): getIrrcService ++ 
,D/irrcClient( 7645): getIrrcService -- 
,D/irrcClient( 7645): IrrcClient -- 
W/irrc_jni( 7645): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7645): Services init done
,I/UEI.SmartControl( 7645): Device manager: loading config....
D/UEI.SmartControl( 7645): Config is loaded...
D/UEI.SmartControl( 7645): QS Service init finished
D/UEI.SmartControl( 7645): QS Service version name: 0.1.73
D/UEI.SmartControl( 7645): QS Service version code: 1073
D/UEI.SmartControl( 7645): Service requested: Control
I/ActivityManager(  938): Killing 7196:com.lge.appbox.client/u0a11 (adj 15): empty #11
,D/UEI.SmartControl( 7645): -----IControl: 11
D/UEI.SmartControl( 7645): Caller: com.lge.qremote
D/UEI.SmartControl( 7645): ------------ IControl registerCallback...
I/UEI.SmartControl( 7645): Registering callback...
D/UEI.SmartControl( 7645): -----IControl: 19
D/UEI.SmartControl( 7645): Caller: com.lge.qremote
I/UEI.SmartControl( 7645): Registering Services Ready callback...
D/UEI.SmartControl( 7645):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7645): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 7645): -----IControl: 8
D/UEI.SmartControl( 7645): Caller: com.lge.qremote
W/libprocessgroup(  938): failed to open /acct/uid_10011/pid_7196/cgroup.procs: No such file or directory
D/UEI.SmartControl( 7645): Internal service binding...
I/AudioManager( 7422): getMode name:com.lge.qremote
,I/AudioManager( 7422): getMode name:com.lge.qremote
,I/AudioManager( 7422): getMode name:com.lge.qremote
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/charger_monitor(  474): init target 500000
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
,D/charger_monitor(  474): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  938): battery changed pluggedType: 2
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  938): Killing 7265:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  938): failed to open /acct/uid_10061/pid_7265/cgroup.procs: No such file or directory
,I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/UEI.SmartControl( 7645): Internal timer expired: 1
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 134263123339; DSPS: 4497561; Offset : -3001200640
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,V/AlarmManager(  938): ELAPSED_WAKEUP set : Alarm{b3dd3ec type 2 when 146938 com.google.android.gms} when 146938
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1732): Vacuum at: now=1451956885821 tag=VacuumService
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/PowerManagerService(  938): ALS enabled for SRE
D/PowerManagerServiceEx(  938): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (28505 ms ago)
,D/qdlights(  938): set_light_backlight: 254
,D/qdlights(  938): set_light_backlight: 251
D/qdlights(  938): set_light_backlight: 247
,D/qdlights(  938): set_light_backlight: 244
,D/qdlights(  938): set_light_backlight: 241
,D/qdlights(  938): set_light_backlight: 237
,D/qdlights(  938): set_light_backlight: 234
,D/qdlights(  938): set_light_backlight: 231
,D/qdlights(  938): set_light_backlight: 227
,D/qdlights(  938): set_light_backlight: 224
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
D/qdlights(  938): set_light_backlight: 221
,D/qdlights(  938): set_light_backlight: 217
,D/qdlights(  938): set_light_backlight: 214
,D/qdlights(  938): set_light_backlight: 211
,D/qdlights(  938): set_light_backlight: 207
,D/qdlights(  938): set_light_backlight: 204
,D/qdlights(  938): set_light_backlight: 201
,D/qdlights(  938): set_light_backlight: 197
,D/qdlights(  938): set_light_backlight: 194
,D/qdlights(  938): set_light_backlight: 191
,D/qdlights(  938): set_light_backlight: 187
,D/qdlights(  938): set_light_backlight: 184
,D/qdlights(  938): set_light_backlight: 181
,D/qdlights(  938): set_light_backlight: 177
,D/qdlights(  938): set_light_backlight: 174
,D/qdlights(  938): set_light_backlight: 171
,D/qdlights(  938): set_light_backlight: 167
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/qdlights(  938): set_light_backlight: 164
D/qdlights(  938): set_light_backlight: 161
,D/qdlights(  938): set_light_backlight: 157
,D/qdlights(  938): set_light_backlight: 154
,D/qdlights(  938): set_light_backlight: 151
,D/qdlights(  938): set_light_backlight: 147
,D/qdlights(  938): set_light_backlight: 144
,D/qdlights(  938): set_light_backlight: 141
,D/qdlights(  938): set_light_backlight: 137
,D/qdlights(  938): set_light_backlight: 134
,D/qdlights(  938): set_light_backlight: 131
,D/qdlights(  938): set_light_backlight: 127
,D/qdlights(  938): set_light_backlight: 124
,D/qdlights(  938): set_light_backlight: 121
,D/qdlights(  938): set_light_backlight: 117
,D/qdlights(  938): set_light_backlight: 114
,D/qdlights(  938): set_light_backlight: 111
,D/qdlights(  938): set_light_backlight: 107
,D/qdlights(  938): set_light_backlight: 104
,D/qdlights(  938): set_light_backlight: 101
,D/qdlights(  938): set_light_backlight: 97
,D/qdlights(  938): set_light_backlight: 94
,D/qdlights(  938): set_light_backlight: 91
,D/qdlights(  938): set_light_backlight: 87
,D/qdlights(  938): set_light_backlight: 84
,D/qdlights(  938): set_light_backlight: 81
,D/qdlights(  938): set_light_backlight: 77
,D/qdlights(  938): set_light_backlight: 74
,D/qdlights(  938): set_light_backlight: 71
,D/qdlights(  938): set_light_backlight: 67
,D/qdlights(  938): set_light_backlight: 64
,D/qdlights(  938): set_light_backlight: 61
,D/qdlights(  938): set_light_backlight: 57
,D/qdlights(  938): set_light_backlight: 54
,D/qdlights(  938): set_light_backlight: 51
,D/qdlights(  938): set_light_backlight: 47
,D/qdlights(  938): set_light_backlight: 44
,D/qdlights(  938): set_light_backlight: 41
,D/qdlights(  938): set_light_backlight: 37
,D/qdlights(  938): set_light_backlight: 34
,D/qdlights(  938): set_light_backlight: 31
,D/qdlights(  938): set_light_backlight: 27
,D/qdlights(  938): set_light_backlight: 24
,D/qdlights(  938): set_light_backlight: 21
,D/qdlights(  938): set_light_backlight: 17
,D/qdlights(  938): set_light_backlight: 14
,D/qdlights(  938): set_light_backlight: 11
,D/qdlights(  938): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 154263797811; DSPS: 5152944; Offset : -3001228176
,I/PowerManagerService(  938): ALS enabled for SRE
D/PowerManagerServiceEx(  938): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (35500 ms ago)
I/PowerManagerService(  938): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  938): ALS enabled for SRE
D/PowerManagerServiceEx(  938): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (35512 ms ago)
W/ContextImpl(  938): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  938): Sleeping (uid 1000)...
D/LPWGController(  938): [updateScreenState] screen on = false
D/LPWGController(  938): disable proximity sensor
D/LPWGController(  938): enable proximity sensor
,I/SensorManager(  938): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@2961446d] by com.android.server.power.ProximitySensorListener.enable():120
I/sensors_hal_Ctx(  938): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  938): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
,D/sensors_hal_SAM(  938): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  938): activate: handle is 48, enable
V/sensors_hal_Ctx(  938): activate sensors is 1400000000000
D/sensors_hal_Thresh(  938): enable: handle=48
I/sensors_hal_SAM(  938): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  938): waitForResponse: timeout=1000
V/sensors_hal_SAM(  938): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  938): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  938): enable: Received response: 0
D/PowerManagerServiceEx(  938): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (35553 ms ago)
I/Adreno-EGL(  938): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  938): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  938): Build Date: 03/02/15 Mon
I/Adreno-EGL(  938): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  938): Remote Branch: 
I/Adreno-EGL(  938): Local Patches: 
I/Adreno-EGL(  938): Reconstruct Branch: 
,D/PermissionCache(  246): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1185 us)
,I/Sensors (  422): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  938): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  938): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  938): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  938): processInd: handle 48, count=1
V/sensors_hal_Thresh(  938): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  938): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  938): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  938): poll: count: 256
I/sensors_hal_Ctx(  938): poll: released wakelock sensor_ind
D/sensors_hal_Util(  938): waitForResponse: timeout=0
D/LPWGController(  938): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  938): current mode = 1  value = 1 1
I/LPWGController(  938): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  938): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/qdlights(  938): set_light_backlight: 0
,I/SensorManager(  938): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  938): activate: handle is 46, disable
V/sensors_hal_Ctx(  938): activate sensors is 1000000000000
D/sensors_hal_LP2(  938): enable: handle=46
D/sensors_hal_LP2(  938): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  938): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  246): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  246): hwc_blank: Blanking display: 0
I/DisplayManagerService(  938): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/sensors_hal_SAM(  938): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  938): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,V/ActivityManager(  938): Display changed displayId=0
,D/DSDPConnection( 1746): Display #0 changed.
,D/qdhwcomposer(  246): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  938): Excessive delay in setPowerMode(): 183ms
I/qdhwcomposer(  246): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  938): Got set_interactive hint
,D/KeyguardViewMediator( 1371): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1333): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1333): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1333): handleNotifyScreenOFF
D/KeyguardViewMediator( 1371): notifyScreenOffLocked
D/KeyguardViewMediator( 1371): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1371): handleNotifyScreenOff
,D/ScreenTurnOffBySensor( 1371): unregisterProximitySensor
,D/WifiServerServiceExt(  938): sendKtScanInterval  mRtspPlay : false
,D/StatusBarWindowView( 1371): onScreenTurnedOff why = 3
I/WifiServerServiceExt(  938): set CMD_KT_SCAN_INTERVAL
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
V/AudioFlinger(  285): setParameters(): io 0, keyvalue screen_state=on, calling pid 938
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
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
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
,I/Sensors (  422): sns_pwr.c(301):releasing wakelock
,D/GpsLocationProvider(  938): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1841): |CORE| sendScreenState: state:true
I/LEDService( 1805): getCurrentHighestLGLedRecord() start. size = 1
,I/Cliptray Service( 1805): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/LEDService( 1805): stopPatternFlashing()
D/Cliptray Service( 1805): lockStatus = 0
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
I/LEDService( 1805): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
I/LEDService( 1805): updateLightsLocked : turn off led
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1805): RESTART MSG
D/SplitWindow(  938): check instance of lgWin Window{4294f0 u0 SearchPanel}
,D/LNfcService( 1787): action : android.intent.action.SCREEN_ON
,D/NfcServiceNXP( 1787): mScreenState : 3, mInProvisionMode : false
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
D/InputDispatcher(  938): Window went away: Window{3b35eec5 u0 SearchPanel}
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]Clock( 1371): onReceive = android.intent.action.SCREEN_ON
,I/LgeClockWidgetControlView( 1371): time changed, timezoneChanged : false
,D/Ulp_jni (  938): JNI:system_update. Event-0
,V/PhoneApp( 1746): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  938): ACTION_SCREEN_ON
,D/WeatherService( 2741): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 2:21:36
D/WeatherService( 2741): 2 : ACTION screen on
D/WeatherService( 2741): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2741): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherService( 2741): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 2:21:36
,D/AppCleanupService( 3990): android.intent.action.SCREEN_ON
,V/AudioFlinger(  285): setParameters(): io 0, keyvalue screen_state=off, calling pid 938
D/audio_hw_primary(  285): adev_set_parameters: enter: screen_state=off
V/voice   (  285): voice_set_parameters: enter: screen_state=off
V/compress_voip(  285): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  285): voice_extn_compress_voip_set_parameters: exit
V/voice   (  285): voice_set_parameters: exit with code(0)
,V/msm8974_platform_lge(  285): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  285): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  285): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  285): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  285): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  285): adev_set_parameters: exit with code(0)
D/WifiController(  938): CMD_SCREEN_OFF 
D/WifiController(  938): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  938): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1841): |CORE| sendScreenState: state:false
,I/LEDService( 1805): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1805): stopPatternFlashing()
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
I/LEDService( 1805): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1805): clear
I/Cliptray Service( 1805): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/LEDService( 1805): updateLightsLocked : turn on led
,E/LEDService( 1805): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1805): Can't handle this request of patternId:0
D/LEDHandler( 1805): RESTART MSG
D/LNfcService( 1787): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1787): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1878): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1746): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  938): ACTION_SCREEN_OFF
D/WeatherService( 2741): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 2:21:36
D/WeatherService( 2741): 2 : ACTION screen off
D/WeatherService( 2741): 2 : TimeTick Receiver Unregister
D/WeatherService( 2741): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 2:21:36
,D/AppCleanupService( 3990): android.intent.action.SCREEN_OFF
D/AppCleanupService( 3990): AppUsageStatsSaveTask
E/NxpNfcJni( 1787): getReconnectState = 0x0
,D/LCardEmulationManager( 1787): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1787): getDefaultRoute
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
,D/NfcService( 1787): screenState= 1
E/NxpNfcJni( 1787): getReconnectState = 0x0
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  938): ELAPSED_WAKEUP set : Alarm{75aba69 type 2 when 161430 com.android.systemui} when 161430
,D/KeyguardViewMediator( 1371): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/PhoneUtils( 1746): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1746): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1746): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1746): getCallState : 0
,D/PhoneUtils( 1746): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1746): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1746): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1371): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1371): doKeyguard: not showing because lockscreen is off
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  474): init target 500000
,D/charger_monitor(  474): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  938): battery changed pluggedType: 2
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  938): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 174264590094; DSPS: 5808330; Offset : -3001229402
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  474): init target 500000
,D/charger_monitor(  474): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  938): battery changed pluggedType: 2
D/PowerManagerServiceEx(  938): acquireWakeLockInternal: lock=571089472, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=938
,V/AlarmManager(  938): ELAPSED_WAKEUP set : Alarm{1ca38cee type 2 when 187708 com.google.android.gms} when 187708
D/PowerManagerServiceEx(  938): releaseWakeLockInternal: lock=571089472 [*alarm*], flags=0x0
,I/art     ( 1732): Explicit concurrent mark sweep GC freed 45161(2MB) AllocSpace objects, 29(464KB) LOS objects, 39% free, 13MB/22MB, paused 1.700ms total 163.637ms
,I/PhenotypeConfigurator( 1732): Scheduling Phenotype for one-off execution 4931 seconds from now (1451956926760)
,D/GetConfigurationSnapshotOperation( 1732): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1732): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1732): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  938): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/art     (  938): Explicit concurrent mark sweep GC freed 55425(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 23MB/35MB, paused 2.260ms total 157.609ms
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  281): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out( 1732): propertyValue:false
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,V/AlarmManager(  938): ELAPSED_WAKEUP set : Alarm{b56c787 type 2 when 189060 android} when 189060
,D/LocationManagerService(  938): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  938): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  938): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  938): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  938): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ClearcutLoggerApiImpl( 1732): disconnect managed GoogleApiClient
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 194265364097; DSPS: 6463715; Offset : -3001218286
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 214266209662; DSPS: 7119103; Offset : -3001227187
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 234266888404; DSPS: 7774485; Offset : -3001220197
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  474): init target 500000
,D/charger_monitor(  474): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  938): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 254267738812; DSPS: 8429873; Offset : -3001223891
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 274268409170; DSPS: 9085255; Offset : -3001225023
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 294269080517; DSPS: 9740637; Offset : -3001224985
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  474): init target 500000
,D/charger_monitor(  474): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 269, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 269
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 269
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  938): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 314269788634; DSPS: 10396020; Offset : -3001218617
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 334270871752; DSPS: 11051415; Offset : -3001203900
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/LocationManagerService(  938): remove aeda6f2
,D/LocationManagerService(  938): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  938): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  938): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  938): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  938): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  938): acquireWakeLockInternal: lock=571089472, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=938
,D/PowerManagerServiceEx(  938): releaseWakeLockInternal: lock=571089472 [*alarm*], flags=0x0
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 354271571015; DSPS: 11706798; Offset : -3001206932
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  474): init target 500000
,D/charger_monitor(  474): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 268
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 268, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 268
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  938): battery changed pluggedType: 2
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 374272355227; DSPS: 12362184; Offset : -3001215838
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 394273186156; DSPS: 13017571; Offset : -3001208728
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/charger_monitor(  474): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  474): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 269
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 269, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 269
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  938): battery changed pluggedType: 2
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 414273944898; DSPS: 13672956; Offset : -3001213003
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/charger_monitor(  474): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 269, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 269
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 269
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  938): battery changed pluggedType: 2
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  474): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 268
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 268
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 268, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  938): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 434274617547; DSPS: 14328338; Offset : -3001211480
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 454275372019; DSPS: 14983723; Offset : -3001219947
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 474276024980; DSPS: 15639104; Offset : -3001209810
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  474): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 266, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 266
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 266
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  938): battery changed pluggedType: 2
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 494276787368; DSPS: 16294489; Offset : -3001208642
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 514277434079; DSPS: 16949871; Offset : -3001233552
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 534278197769; DSPS: 17605255; Offset : -3001201972
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  474): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 265, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 265
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 265
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  938): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 554279060678; DSPS: 18260644; Offset : -3001224175
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 574279818066; DSPS: 18916029; Offset : -3001229520
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 594280692539; DSPS: 19571417; Offset : -3001209825
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  474): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 265, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 265
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 265
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  938): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 614281366020; DSPS: 20226799; Offset : -3001207392
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 634282109503; DSPS: 20882184; Offset : -3001227447
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 654282774963; DSPS: 21537566; Offset : -3001233218
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/charger_monitor(  474): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 264, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 264
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 264
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  938): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 674283448133; DSPS: 22192948; Offset : -3001231227
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 694284108282; DSPS: 22848329; Offset : -3001212077
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 714284757284; DSPS: 23503711; Offset : -3001234227
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/charger_monitor(  474): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 263, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 263
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 263
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  938): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 734285605089; DSPS: 24159098; Offset : -3001210397
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 754286266644; DSPS: 24814480; Offset : -3001220463
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 774287014448; DSPS: 25469864; Offset : -3001204585
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  474): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 262
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 262
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 262, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  938): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 794287729908; DSPS: 26125248; Offset : -3001221809
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 814288447298; DSPS: 26780631; Offset : -3001207051
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 834289196509; DSPS: 27436016; Offset : -3001220103
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  474): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 854289875460; DSPS: 28091398; Offset : -3001212486
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/charger_monitor(  474): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 261, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 261
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 261
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  938): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 261
,D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 261, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 261
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  938): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 874290687484; DSPS: 28746785; Offset : -3001224567
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 894291359924; DSPS: 29402167; Offset : -3001223123
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  474): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 914292126687; DSPS: 30057552; Offset : -3001220289
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 934292879909; DSPS: 30712937; Offset : -3001229668
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/PowerManagerServiceEx(  938): acquireWakeLockInternal: lock=571089472, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=938
,V/AlarmManager(  938): ELAPSED_WAKEUP set : Alarm{3a7207f type 2 when 952713 com.android.bluetooth} when 952713
W/bt-smp  ( 1990): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1990): Plain text(LSB ~ MSB) = 09 e3 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 1990): Encrypted text(LSB ~ MSB) = 84 28 f7 60 51 c6 31 aa 53 2f 5b 8a dd d3 fa f9 
W/bt-btm  ( 1990): Stopping oneshot timer
I/ActivityManager(  938): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7890 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/DigitalAppWidgetProvider( 7890): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7890): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@10bddb98
D/PowerManagerServiceEx(  938): releaseWakeLockInternal: lock=571089472 [*alarm*], flags=0x0
,I/ActivityManager(  938): Killing 7529:com.android.gallery3d/u0a23 (adj 15): empty #11
W/libprocessgroup(  938): failed to open /acct/uid_10023/pid_7529/cgroup.procs: No such file or directory
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 954293465682; DSPS: 31368316; Offset : -3001225006
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  474): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 260, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 260
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 260
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  938): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 974294225570; DSPS: 32023701; Offset : -3001226781
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 994294985354; DSPS: 32679086; Offset : -3001229103
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1014295642066; DSPS: 33334467; Offset : -3001213599
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/PowerManagerServiceEx(  938): acquireWakeLockInternal: lock=571089472, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=938
,V/AlarmManager(  938): ELAPSED_WAKEUP set : Alarm{1b49b84c type 2 when 1020306 com.google.android.gms} when 1020306
D/PowerManagerServiceEx(  938): releaseWakeLockInternal: lock=571089472 [*alarm*], flags=0x0
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  474): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1034296382162; DSPS: 33989851; Offset : -3001206445
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1054297059029; DSPS: 34645234; Offset : -3001231560
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1074297796209; DSPS: 35300618; Offset : -3001226438
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  474): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1094298617243; DSPS: 35956005; Offset : -3001229457
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1114299264891; DSPS: 36611386; Offset : -3001222991
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1134299930769; DSPS: 37266768; Offset : -3001228291
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  474): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1154303337637; DSPS: 37922239; Offset : -3001208849
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1174304005807; DSPS: 38577621; Offset : -3001211960
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1194304745018; DSPS: 39233005; Offset : -3001205042
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  474): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 259, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 259
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 259
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  938): battery changed pluggedType: 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1214305518395; DSPS: 39888391; Offset : -3001225825
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/UsageStatsService(  938): User[0] Flushing usage stats to disk
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1234306359221; DSPS: 40543778; Offset : -3001208582
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1254307028120; DSPS: 41199160; Offset : -3001210653
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  474): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1274307702747; DSPS: 41854542; Offset : -3001207960
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1294308471958; DSPS: 42509928; Offset : -3001232285
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1314309135961; DSPS: 43165309; Offset : -3001208967
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  474): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 258, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 258
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 258
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  938): battery changed pluggedType: 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1334309904442; DSPS: 43820694; Offset : -3001203322
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1354310785426; DSPS: 44476083; Offset : -3001207452
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1374311441980; DSPS: 45131465; Offset : -3001221947
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  474): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 258, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 258
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 258
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  938): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1394312119786; DSPS: 45786847; Offset : -3001215527
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1414312836809; DSPS: 46442231; Offset : -3001231342
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1434313605447; DSPS: 47097616; Offset : -3001225150
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/charger_monitor(  474): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1454314463669; DSPS: 47753004; Offset : -3001221914
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1474315227463; DSPS: 48408389; Offset : -3001220694
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1494315949590; DSPS: 49063773; Offset : -3001231016
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  474): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 257, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 257
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 257
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  938): battery changed pluggedType: 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1514316674166; DSPS: 49719156; Offset : -3001208578
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1534317339523; DSPS: 50374538; Offset : -3001214503
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/PowerManagerServiceEx(  938): acquireWakeLockInternal: lock=571089472, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=938
,V/AlarmManager(  938): ELAPSED_WAKEUP set : Alarm{2b52d095 type 2 when 1548408 android} when 1548408
,D/PowerManagerServiceEx(  938): releaseWakeLockInternal: lock=571089472 [*alarm*], flags=0x0
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1554318019724; DSPS: 51029920; Offset : -3001205638
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  474): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1574318696487; DSPS: 51685303; Offset : -3001231066
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1594319328250; DSPS: 52340683; Offset : -3001209393
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1614319991784; DSPS: 52996065; Offset : -3001217169
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  474): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 257, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 257
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 257
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  938): battery changed pluggedType: 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1634320675788; DSPS: 53651447; Offset : -3001204499
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1654321344165; DSPS: 54306829; Offset : -3001207613
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1674321993220; DSPS: 54962211; Offset : -3001229737
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  474): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 257
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 257
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 257, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  938): battery changed pluggedType: 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1694322849462; DSPS: 55617598; Offset : -3001197781
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1714323613882; DSPS: 56272984; Offset : -3001227157
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1734324368666; DSPS: 56928369; Offset : -3001235026
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/charger_monitor(  474): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1754325135898; DSPS: 57583754; Offset : -3001231332
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1774325911932; DSPS: 58239139; Offset : -3001217665
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1794326653174; DSPS: 58894523; Offset : -3001209028
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  474): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1814327317020; DSPS: 59549905; Offset : -3001216515
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1834327992221; DSPS: 60205287; Offset : -3001212310
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/PowerManagerServiceEx(  938): acquireWakeLockInternal: lock=571089472, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=938
,V/AlarmManager(  938): ELAPSED_WAKEUP set : Alarm{1297459b type 2 when 1852853 com.android.bluetooth} when 1852853
,W/bt-smp  ( 1990): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1990): Plain text(LSB ~ MSB) = c7 82 41 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 1990): Encrypted text(LSB ~ MSB) = 87 67 52 01 37 3f 36 58 e9 e9 d1 c8 4f c9 ed 78 
W/bt-btm  ( 1990): Stopping oneshot timer
I/ProcessStatsService(  938): Prepared write state in 17ms
,I/ProcessStatsService(  938): Prepared write state in 17ms
,I/DigitalAppWidgetProvider( 7890): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7890): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@10bddb98
,D/PowerManagerServiceEx(  938): releaseWakeLockInternal: lock=571089472 [*alarm*], flags=0x0
I/ProcessStatsService(  938): Pruning old procstats: /data/system/procstats/state-2016-01-03-23-30-06.bin
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1854328639609; DSPS: 60860668; Offset : -3001206260
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,V/AlarmManager(  938): RTC_WAKEUP set : Alarm{32800d38 type 0 when 1451958605950 com.google.android.gms} when 1451958605950
,D/LocationManagerService(  938): getAllProviders()=[passive, gps, network]
,I/EventLogService( 4128): Aggregate from 1451956850848 (log), 1451956805805 (data)
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10006
,D/DnsProxyListener(  281): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out( 1732): propertyValue:false
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager(  938): android: cancelAsUser(2) by android
,I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  474): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1841): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1841): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 257, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 257
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 257
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  938): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  938): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  938): battery changed pluggedType: 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1874329317570; DSPS: 61516051; Offset : -3001230464
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  938): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  938): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  938): tsOffsetIs: Apps: 1894330291574; DSPS: 62171442; Offset : -3001202036
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
,TIME-OUT KILL (timeout was 1800000ms),I/ThermalEngine(  298): Sensor:pa_therm0:27000 mC
D/AndroidRuntime( 8108): 
D/AndroidRuntime( 8108): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8108): CheckJNI is OFF
D/AndroidRuntime( 8108): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  938): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  938): Killing 6108:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  938): WIN DEATH: Window{391c1329 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  938): Focus left window: Window{391c1329 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  938): Window went away: Window{391c1329 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  938): Skipping PackageSetting{24bdd7db com.example.hello/10317} due to missing metadata
I/ActivityManager(  938):   Force finishing activity ActivityRecord{8aa737f u0 com.test.thalitest/.MainActivity t220}
V/ActivityManager(  938): Display changed displayId=0
D/DSDPConnection( 1746): Display #0 changed.
W/ActivityManager(  938): Spurious death for ProcessRecord{9be9567 6108:com.test.thalitest/u0a316}, curProc for 6108: null
I/ActivityManager(  938): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  938):   Force finishing activity ActivityRecord{8aa737f u0 com.test.thalitest/.MainActivity t220 f}
W/ActivityManager(  938): Duplicate finish request for ActivityRecord{8aa737f u0 com.test.thalitest/.MainActivity t220 f}
I/art     ( 1940): Explicit concurrent mark sweep GC freed 9931(664KB) AllocSpace objects, 3(72KB) LOS objects, 40% free, 12MB/20MB, paused 2.286ms total 72.245ms
D/KeyguardModel( 1371): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/QCNEJ   ( 1841): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[LGHome]EVENT( 1878): [Launcher.java:5203:onStart()]onStart
I/InputReader(  938): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1732): Ignoring removeGeofence because network location is disabled.
W/System.err( 3538): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
I/[LGHome]EVENT( 1878): [Launcher.java:776:onResume()]onResume
W/System.err( 3538): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3538): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3538): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3538): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3538): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3538): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3538): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3538): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3538): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3538): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3538): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/art     ( 4128): Explicit concurrent mark sweep GC freed 5911(338KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 14MB/18MB, paused 892us total 145.721ms
I/ActivityManager(  938): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8140 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1878): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/KeyguardModel( 1371): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1371): createShortcutInfo...
I/[SystemUI]QSlideListController( 1371): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]LGActivityUtil( 1878): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/KeyguardModel( 1371): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1371): createShortcutInfo...
I/[LGHome]EVENT( 1878): [Launcher.java:929:onResume()]onResume end
I/Activity( 1878): Activity.onPostResume() called 
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1371): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1371): createShortcutInfo...
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1371): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1371): createShortcutInfo...
I/[LGHome]EVENT( 1878): [Launcher.java:986:onPause()]onPause
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1371): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1371): createShortcutInfo...
W/[LGHome]LGWallpaperInfo( 1878): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1878): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
I/SystemUI[Framework](  938): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  938): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  938): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  938): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  938): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@23694287,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  938): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  938): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  938): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  938): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  938): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  938): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@23694287,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  938): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/art     (  938): Explicit concurrent mark sweep GC freed 50180(3MB) AllocSpace objects, 10(330KB) LOS objects, 33% free, 23MB/35MB, paused 3.803ms total 227.840ms
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1371): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1371): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/art     (  938): WaitForGcToComplete blocked for 98.822ms for cause Explicit
D/KeyguardModel( 1371): handleShortcutListChanged...
D/InputDispatcher(  938): Focus entered window: Window{3e86f931 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/administrator(  938): Handling package changes for user 0
D/KeyguardModel( 1371): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1371): createShortcutInfo...
D/KeyguardModel( 1371): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1371): createShortcutInfo...
I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1371): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1371): createShortcutInfo...
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/[LGHome]EVENT( 1878): [Launcher.java:5214:onStop()]onStop
D/KeyguardModel( 1371): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1371): createShortcutInfo...
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1371): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1371): createShortcutInfo...
I/[LGHome]EVENT( 1878): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1878): [setNavigationBarColor] color=0x 0
D/KeyguardModel( 1371): handleShortcutListChanged...
W/ResourcesManager( 8140): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8140): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8140): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/NotificationService(  938): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  938): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  938): Receieved: android.intent.action.PACKAGE_REMOVED
D/PhoneStatusBar( 1371): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/TaskPersister(  938): removeObsoleteFile: deleting file=220_task.xml
D/PhoneStatusBar( 1371): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1371): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1371):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1371): , Keyguard show=false, IME shown=false, Panel expanded=false
I/art     (  938): Explicit concurrent mark sweep GC freed 5207(312KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.980ms total 271.578ms
I/LGEmail ( 8140): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 8140): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
D/AndroidRuntime( 8108): Shutting down VM
W/InputMethodManagerService(  938): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  938): Got RemoteException sending setActive(false) notification to pid 6108 uid 10316
D/LCardEmulationManager( 1787): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1787): getDefaultRoute
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/Timeline(  938): Timeline: Activity_windows_visible id: ActivityRecord{36d6fcef u0 com.lge.launcher2/.Launcher t219} time:1907379
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
W/IInputConnectionWrapper( 1878): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1615): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1878): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1878): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1878): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
I/PackageChangeReceiver( 8140): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
W/ResourcesManager(  938): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/ActivityManager(  938): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8168 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  938): Killing 7551:com.android.contacts/u0a18 (adj 15): empty #11
W/libprocessgroup(  938): failed to open /acct/uid_10018/pid_7551/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 8168): onCreate
W/AppUp4:DB( 8168):  [AppBoxDatabaseHelper] construct

```
