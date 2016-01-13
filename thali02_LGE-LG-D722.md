#### Test 5590220275263c8_thali02_LGE-LG-D722 Logs


```
--------- beginning of system
W/libprocessgroup(  855): failed to open /acct/uid_10013/pid_5829/cgroup.procs: No such file or directory
,--------- beginning of main
D/Finsky  ( 5491): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/AlarmManager(  855): RTC_WAKEUP set : Alarm{1f1c5dd3 type 0 when 1452695566162 com.android.vending} when 1452695566162
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  855): android: cancelAsUser(2) by android
D/libc-netbsd( 5491): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5491): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5491): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5491): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  280): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 5491): propertyValue:false
D/libc-netbsd( 5491): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5491): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5491): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5491): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/AndroidRuntime( 6157): 
D/AndroidRuntime( 6157): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6157): CheckJNI is OFF
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
I/NotificationManager(  855): android: cancelAsUser(2) by android
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/qtaguid ( 5491): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5491): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5491): untagSocket(41) failed with errno -22
D/AndroidRuntime( 6157): Calling main entry com.android.commands.am.Am
D/Finsky  ( 5491): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
I/ActivityManager(  855): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  855): setTaskToReturnTo : TaskRecord{35017d79 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  855): setTaskToReturnTo : TaskRecord{35017d79 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  855): AppWindowTokenEx init.. 
D/ContextHelper(  855): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  855): Focus left window: Window{13868203 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 6157): Shutting down VM
I/[LGHome]EVENT( 1880): [Launcher.java:986:onPause()]onPause
D/SplitWindow(  855): check instance of lgWin Window{15f22396 u0 Starting com.test.thalitest}
I/ActivityManager(  855): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6188 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1880): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/ActivityManager(  855): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6213 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/[LGHome]EVENT( 1880): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  855): Starting window displayed
I/SystemUI[Framework](  855): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
W/PhoneWindowManagerEx(  855): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  855): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  855): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  855): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1e4ca447,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  855): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1375): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[SystemUI]NavigationThemeResource( 1375): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1375):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1375): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1375): draw background and invalidate : color = f000000
D/BarTransitions( 1375): draw background and invalidate : color = 6060606
I/HotwordDetector( 1945): Closing mic
I/MicrophoneInputStream( 1945): mic_close com.google.android.apps.gsa.speech.audio.u@65f2489
V/AudioRecord( 1945): stop()
I/NotificationManager(  855): android: cancelAsUser(2) by android
D/AudioRecord( 1945): AudioRecord->stop()
V/AudioFlinger(  285): RecordHandle::stop()
V/AudioFlinger(  285): RecordThread::stop
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
V/AudioFlinger(  285): processConfigEvents_l() DONE thread 0xb3a58000
D/audio_hw_primary(  285): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
W/ResourcesManager( 6213): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6213): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
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
V/AudioFlinger(  285): processConfigEvents_l() DONE thread 0xb3a58000
V/AudioFlinger(  285): RecordThread: loop stopping
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
V/AudioRecord( 1945): stop()
V/AudioRecord( 1945): stop()
V/AudioRecord( 1945): stop()
V/AudioFlinger(  285): RecordHandle::stop()
V/AudioFlinger(  285): RecordThread::stop
V/AudioPolicyManager(  285): releaseInput() 17
V/AudioPolicyManager(  285): closeInput(17)
V/AudioFlinger(  285): closeInput() 17
V/AudioSystem(  285): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1375): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  285): ThreadBase::exit
V/AudioFlinger(  285): RecordThread: loop starting
V/AudioSystem( 1990): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  285): releasing 16 from 1945 for -1
V/AudioFlinger(  285):  decremented refcount to 0
V/AudioFlinger(  285): purging stale effects
V/AudioFlinger(  285): RecordThread 0xb3a58000 exiting
V/AudioSystem( 3133): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  855): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  285): adev_close_input_stream: enter:stream_handle(0xb546e1a0)
D/audio_hw_primary(  285): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  285): in_standby: exit:  status(0)
V/AudioSystem( 1750): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2010): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1945): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  285): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  285): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  285): AudioCommandThread() waking up
V/AudioPolicyService(  285): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
V/AudioPolicyManager(  285): releaseInput() exit
V/AudioFlinger(  285): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  285): removeClient_l() pid 1945, calling pid 285
I/HotwordRecognitionRnr( 1945): Stopping hotword detection.
I/HotwordRecognitionRnr( 1945): Hotword detection finished
D/ContextHelper( 6188): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/MultiDex( 6213): VM with version 2.1.0 has multidex support
I/MultiDex( 6213): install
I/MultiDex( 6213): VM has multidex support, MultiDex support library is disabled.
I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-54 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 15:32:47.686 DNS addrs= 192.168.1.1, 0.0.0.0, 
V/JNIHelp ( 6213): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/SQLiteConnectionPool( 4127): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/WebViewFactory( 6188): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
W/ActivityThread( 6213): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6213): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2c0d046e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6213): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6213): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6213): com.google.android.gms: cancel(39789) by com.google.android.gms
E/MDM     ( 1733): [119] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/LibraryLoader( 6188): Time to load native libraries: 14 ms (timestamps 4624-4638)
I/LibraryLoader( 6188): Expected native library version number "",actual native library version number ""
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 4127): Restart initialization of location
D/ChimeraCfgMgr( 6213): Reading stored module config
I/qtaguid ( 5491): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5491): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5491): untagSocket(41) failed with errno -22
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
V/WebViewChromiumFactoryProvider( 6188): Binding Chromium to main looper Looper (main, tid 1) {1e01030c}
I/LibraryLoader( 6188): Expected native library version number "",actual native library version number ""
W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
D/ChimeraCfgMgr( 6213): Loading module com.google.android.gms.car from APK com.google.android.gms
I/chromium( 6188): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6188): Initializing chromium process, singleProcess=true
W/art     ( 6188): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6188): ApplicationContext is null in ApplicationStatus
,W/chromium( 6188): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6188): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6188): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6188): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6188): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6188): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6188): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6188): Remote Branch: 
I/Adreno-EGL( 6188): Local Patches: 
I/Adreno-EGL( 6188): Reconstruct Branch: 
D/sensors_hal_Time(  855): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  855): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  855): tsOffsetIs: Apps: 94891111740; DSPS: 3207893; Offset : -3007476211
,D/NativeLibraryUtils( 6213): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 6213): Connecting to CarCallService...
,V/AudioPolicyService(  285): registerClient() client 0xb39b08a0, uid 10316
,D/BluetoothManagerService(  855): Message: 20
D/BluetoothManagerService(  855): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@15d0240b:true
D/BluetoothAdapterService(255935480)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@38dce70e
,I/art     ( 6213): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6213): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/CAR.SERVICE( 6213): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6213): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6213): Creating a new PhoneAdapter instance
W/ActivityManager(  855): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6213): setListener: com.google.android.gms.car.dn@16c0ae15
W/ActivityManager(  855): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6213): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6213): Starting CarCallService with initial phone null
I/NotificationManager( 6213): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/art     ( 5491): CheckpointMarkThreadRoots callback created = 0xb056f430
W/art     ( 6188): Attempt to remove local handle scope entry from IRT, ignoring
I/art     ( 5491): CheckpointMarkThreadRoots callback created = 0xb056f400
,W/AwContents( 6188): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6188): CordovaWebView is running on device made by: LGE
,W/art     ( 6188): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6188): Attempt to remove local handle scope entry from IRT, ignoring
D/CAR.SERVICE( 6213): Package validated; name: com.android.vending
,I/Activity( 6188): Activity.onPostResume() called 
D/OpenGLRenderer( 6188): Render dirty regions requested: true
I/OpenGLRenderer( 6188): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6188): Enabling debug mode 0
I/NotificationManager( 5491): com.android.vending: cancel(10436) by com.android.vending
,D/Atlas   ( 6188): Validating map...
,V/Finsky  ( 5491): [1] GearheadStateMonitor.access$100: mIsProjecting:false
D/SplitWindow(  855): check instance of lgWin Window{b3625fb u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 6188): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  855): Focus entered window: Window{b3625fb u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  855): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  855): Displayed com.test.thalitest/.MainActivity: +1s407ms
I/Timeline(  855): Timeline: Activity_windows_visible id: ActivityRecord{a737abe u0 com.test.thalitest/.MainActivity t222} time:95369
I/Timeline( 6188): Timeline: Activity_idle id: android.os.BinderProxy@2517954b time:95390
,D/UEI.SmartControl( 6028): Internal timer expired: 1
,W/BindingManager( 6188): Cannot call determinedVisibility() - never saw a connection for the pid: 6188
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  855): android: cancelAsUser(2) by android
,I/qtaguid ( 5491): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5491): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5491): untagSocket(41) failed with errno -22
,D/JsMessageQueue( 6188): Set native->JS mode to OnlineEventsBridgeMode
,W/ResourcesManager( 5491): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5491): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5491): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 5491): [1] DailyHygiene.access$600: Logging device features
,D/jxcore_app_log( 6188): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622764032
D/JX-Cordova( 6188): jxcore cordova android initializing
V/AlarmManager(  855): RTC_WAKEUP set : Alarm{2bbb8fe1 type 0 when 1452695569664 com.android.vending} when 1452695569664
,D/DeviceConnectionService( 1733): client connected with version: 8296000
D/Finsky  ( 5491): [655] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5491): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 5491): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  855): android: cancelAsUser(2) by android
I/art     ( 6188): CheckpointMarkThreadRoots callback created = 0x9a4b9cd0
,D/libc-netbsd( 5491): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5491): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5491): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5491): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  280): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
I/art     ( 6188): CheckpointMarkThreadRoots callback created = 0x9a4b9ca0
,D/libc-netbsd(  280): res_queryN name = xxxxx succeed
,I/System.out( 5491): propertyValue:false
,I/ActivityManager(  855): Killing 5218:com.google.android.talk/u0a61 (adj 15): empty #11
,I/art     (  855): Explicit concurrent mark sweep GC freed 28272(1710KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.498ms total 155.982ms
,W/libprocessgroup(  855): failed to open /acct/uid_10061/pid_5218/cgroup.procs: No such file or directory
W/jxcore-log( 6188): Initializing JXcore engine
,W/jxcore-log( 6188): JXcore engine is ready
W/jxcore-log( 6188): Starting JXcore engine
,W/.test.thalitest( 6188): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6326]" dev="sockfs" ino=6326 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6188): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6188): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6463]" dev="sockfs" ino=6463 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6188): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6188): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6188): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[29873]" dev="sockfs" ino=29873 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
I/ActivityManager(  855): Process com.google.android.apps.plus (pid 6010) has died
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/jxcore-log( 6188): Platform android
W/jxcore-log( 6188): 
W/jxcore-log( 6188): Process ARCH arm
W/jxcore-log( 6188): 
,I/ActivityManager(  855): Process com.android.contacts (pid 5969) has died
,V/AlarmManager(  855): RTC_WAKEUP set : Alarm{32ab14bf type 0 when 1452695572521 com.google.android.googlequicksearchbox} when 1452695572521
,I/jxcore-log( 6188): JXcore Cordova bridge is ready!
I/jxcore-log( 6188): 
,W/jxcore-log( 6188): JXcore engine is started
I/chromium( 6188): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/jxcore-log( 6188): Toggling radios to true
I/jxcore-log( 6188): 
,D/BluetoothAdapter( 6188): enable(): BT is already enabled..!
D/WifiServiceImplEx(  855): setWifiEnabled: true pid=6188, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  855): setWifiEnabled: true pid=6188, uid=10316
D/WifiServiceImplEx(  855): disconnect pid=6188, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  855): reconnect pid=6188, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 6188): Radios toggled
I/jxcore-log( 6188): 
I/jxcore-log( 6188): My device name is: LGE-LG-D722
I/jxcore-log( 6188): 
,I/wpa_supplicant( 2723): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/wpa_supplicant( 2723): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine(  855): WifiStateMachine: Leaving Connected state
,I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
D/WfdsMonitor( 1805): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiConfigStore(  855): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/LGWifiP2pService(  855): InactiveState{ when=-6ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  855): P2pEnabledState{ when=-6ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  855): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  280): Clearing all IP addresses on wlan0
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 7
,V/NativeCrypto( 1733): Read error: ssl=0xaaf12c00: I/O error during system call, Connection timed out
V/NativeCrypto( 1733): SSL shutdown failed: ssl=0xaaf12c00: I/O error during system call, Broken pipe
,D/ConnectivityService(  855): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
,I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 7
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  855): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): ValidatedState{ when=-4ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): DefaultState{ when=-15ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  855): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): Forcing reevaluation
D/WifiHS20(  855): hidePasspointNotification off =false
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  855): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-13 15:32:53.175 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
,I/ActivityManager(  855): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6335 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,E/WifiStateMachine(  855): Start Disconnecting Watchdog 1
D/WifiHS20(  855): hidePasspointNotification off =false
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  855): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGWifiP2pService(  855): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  855): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2723): wlan0: CTRL-EVENT-SCAN-STARTED 
,I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-13 15:32:53.26 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
D/CommandListener(  280): Clearing all IP addresses on wlan0
D/ConnectivityService(  855): Default network via Wi-Fi disconnect. stop DSQN
D/WifiHS20(  855): hidePasspointNotification off =false
D/DSQN    (  855): disableDataServiceNotify
D/DSQN    (  855): stop dsqn bin
D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-13 15:32:53.27 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  855): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/WifiNetworkAgent(  855): NetworkAgent: NetworkAgent channel lost
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
,I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/ConnectivityService(  855): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/WifiHS20(  855): hidePasspointNotification off =false
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  855): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService(  855):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  855):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-13 15:32:53.29 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  855): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  855): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  855): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-13 15:32:53.298 DNS addrs= 0.0.0.0, 0.0.0.0, 
,I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/ConnectivityManager.CallbackHandler( 1375): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): Disconnected - quitting
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/WifiServerServiceExt(  855): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  855): setSupplicantStateDISCONNECTED
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/CSLegacyTypeTracker(  855): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
D/CSLegacyTypeTracker(  855): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/ConnectivityService(  855): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy(  855): [LG_RESTRICTED] !!!isConnected  type  :1
W/QCNEJ   ( 1840): |CORE| No family connected
D/Tethering(  855): MasterInitialState.processMessage what=3
D/ConnectivityService(  855): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  855): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  855): MasterInitialState.processMessage what=3
V/NetworkPolicy(  855): [LG_RESTRICTED] !!!isConnected  type  :1
W/QCNEJ   ( 1840): |CORE| No family connected
I/QCNEJ   ( 1840): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/ConnectivityService(  855): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/WifiServerServiceExt(  855): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  855): setSupplicantStateSCANNING
D/ConnectivityService(  855): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  855): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService(  855): Removing idletimer
,D/WIFI    (  855): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  855):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/QCNEJ   ( 1840): |CORE| sendDefaultNwMsg: default = -1
D/DhcpStateMachine(  855): StoppedState
D/DhcpStateMachine(  855): StoppedState{ when=-90ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings(  855): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/ConnectivityService(  855): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/TelephonyNetworkFactory-1( 1750): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1750):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/TelephonyIcons( 1375): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1375): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
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
W/ResourcesManager( 6335): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6335): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6335): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6335): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6335): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/IndexDatabaseHelper( 6335): Using schema version: 115
,I/IndexDatabaseHelper( 6335): Index is fine
D/CAR.SERVICE( 6213): mConnectedToCar = false, abort
,E/ActivityThread( 6213): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1efed05d that was originally bound here
E/ActivityThread( 6213): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1efed05d that was originally bound here
E/ActivityThread( 6213): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6213): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6213): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6213): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6213): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6213): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6213): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6213): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6213): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6213): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6213): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6213): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6213): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6213): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6213): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6213): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6213): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6213): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6213): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6213): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6213): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6213): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6213): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6213): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@29769bcc that was originally bound here
E/ActivityThread( 6213): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@29769bcc that was originally bound here
E/ActivityThread( 6213): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6213): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6213): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6213): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6213): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6213): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6213): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6213): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6213): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6213): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6213): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6213): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6213): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6213): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6213): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6213): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6213): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6213): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6213): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6213): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6213): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6213): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  855): Unbind failed: could not find connection for android.os.BinderProxy@3de4378c
V/WiFiOffLoadBroadcast( 6335): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6335): MCCMNC not supported: null
I/ActivityManager(  855): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6361 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/PCSuite ( 6361): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6361): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6361): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  855): Process com.lge.qremote (pid 4929) has died
,D/UEI.SmartControl( 6028): Service.onUnbind: IControl
D/UEI.SmartControl( 6028): Service.onDestroy
D/UEI.SmartControl( 6028): Shutdown IRRCPlayer... 
W/irrc_jni( 6028): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6028): ~IrrcClient ++ 
D/irrcClient( 6028): ~IrrcClient -- 
,W/irrc_jni( 6028): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6028): Blaster closed
D/UEI.SmartControl( 6028): Blaster closed
D/UEI.SmartControl( 6028): Shut down QS...
D/UEI.SmartControl( 6028): Stopped file observer...
I/UEI.SmartControl( 6028): QS lib stop result = true
D/UEI.SmartControl( 6028): QS shutdown complete
I/ActivityManager(  855): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6381 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 6381): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  855): Message: 20
D/BluetoothManagerService(  855): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2449b7b6:true
,I/ActivityManager(  855): Process com.google.android.music:main (pid 5705) has died
,D/BluetoothAdapterService(255935480)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@38dce70e
D/BluetoothAdapterService(255935480)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@38dce70e
I/ActivityManager(  855): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6401 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2723): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,W/ResourcesManager( 6401): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/LocSvc_java(  855): onReceive
,W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  855): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-13 15:32:54.406 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  855): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-13 15:32:54.415 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
D/WifiServerServiceExt(  855): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  855): setSupplicantStateASSOCIATING
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/wpa_supplicant( 2723): wlan0: Associated with c0:ff:d4:d3:aa:48
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
,I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
D/WifiServerServiceExt(  855): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  855): setSupplicantStateASSOCIATED
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
,W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  855): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-13 15:32:54.461 DNS addrs= 0.0.0.0, 0.0.0.0, 
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
D/WifiOffDelayIfNotUsed(  855): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt(  855): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  855): setSupplicantStateFOUR_WAY_HANDSHAKE
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-13 15:32:54.463 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
,I/wpa_supplicant( 2723): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2723): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
D/WifiServerServiceExt(  855): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  855): setSupplicantStateGROUP_HANDSHAKE
I/WifiServiceExtension(  855): setVHTCapabilityType  : false
I/WifiServerServiceExt(  855): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  855): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  855): setSecurityType  : 2
,I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  855): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-13 15:32:54.511 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-13 15:32:54.512 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  855): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/ConnectivityService(  855): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  855): Got NetworkAgent Messenger
D/ConnectivityService(  855): NetworkAgentInf,o [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  855): NetworkAgent connected
,D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
E/WifiConfigStore(  855): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  855): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 9
,D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  280): Setting iface cfg
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/WifiStateMachine(  855): Start Dhcp Watchdog 2
D/DhcpStateMachine(  855): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  855): WaitBeforeStartState
I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-56 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-13 15:32:54.559 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/ConnectivityService(  855): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,E/WifiStateMachine(  855): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  855): Current State is mWaitBeforeStartState.
,D/LGWifiP2pService(  855): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@bba92d4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  855): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@bba92d4 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  855): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper(  855): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  855): DHCP Start wake lock is acquired.
D/CommandListener(  280): Setting iface cfg
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  280): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  855): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  855): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  855): setSupplicantStateCOMPLETED
D/ConnectivityService(  855): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  855): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  855): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  855): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  855): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  855): ignoring duplicate network state non-change
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  855): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 15:32:54.674 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  855): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 15:32:54.677 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
D/ConnectivityService(  855): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
D/ConnectivityService(  855): Adding iface wlan0 to network 101
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
,I/Babel_SMS( 6401): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6401): MmsConfig.loadMmsSettings
E/WifiStateMachine(  855): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiHS20(  855): [PASSPOINT] passpointNotification: hs20AP list is checked
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = true, mWifiLevel = 2
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 15:32:54.705 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
E/ConnectivityService(  855): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  855): Adding Route [fe80::/64 -> :: wlan0] to network 101
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  855): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/WifiOffDelayIfNotUsed(  855): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WifiHS20(  855): [PASSPOINT] passpointNotification: hs20AP list is checked
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  280): netlink response contains error (File exists)
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/ConnectivityService(  855): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  855): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  855): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  855): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  855): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 15:32:54.717 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/ConnectivityService(  855): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  855): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/Conne,ctivityService(  855): rematching NetworkAgentInfo [WIFI () - 101]
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/ConnectivityService(  855):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  855):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  855):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  855):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  855):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  855): currentScore = 0, newScore = 20
D/ConnectivityService(  855):    accepting network in place of null
D/ConnectivityService(  855): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WIFI    (  855): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  855):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/ConnectivityService(  855): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  855): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  855): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  855): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  855): [e] list.add(nai) empty : false size: 1
D/ConnectivityService(  855): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/TelephonyNetworkFactory-1( 1750): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  855): validation of new default Network = false
D/ConnectivityService(  855): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  855): enableDataServiceNotify 
D/DSQN    (  855): start dsqn bin
W/QCNEJ   ( 1840): |CORE| No family connected
I/QCNEJ   ( 1840): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  855): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/TelephonyNetworkFactory-1( 1750):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/Tethering(  855): MasterInitialState.processMessage what=3
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1840): |CORE| sendDefaultNwMsg: default = 1
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  280): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx,, class = 1, type = 1
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
I/Babel_SMS( 6401): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6401): MmsConfig.loadFromDatabase
,D/ConnectivityService(  855): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  855):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  855):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  855): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = true, mWifiLevel = 2
I/DSQN    ( 6436): DSQN samuel.seo ver 141203
,E/DSQN    ( 6436): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6436): created command queue thread
I/DSQN    ( 6436): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6436): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/ConnectivityManager.CallbackHandler( 1375): CM callback handler got msg 524290
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): [LWD] Start DNSResolver start to wait
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): [LWD] wait 500ms before dns check
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
E/Babel_SMS( 6401): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6401): MmsConfig.loadFromResources
,E/Babel_SMS( 6401): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6401): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
,I/System.out(  855): propertyValue:false
D/TelephonyIcons( 1375): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1375): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/SensorManager( 6401): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6401): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6401): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6401): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6401): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6401): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6401): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6401): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6401): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6401): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6401): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6401): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6401): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6401): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6401): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6401): found sensor: Motion Accel, handle=46
D/DhcpStateMachine(  855): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper(  855): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  855): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,W/Settings( 6401): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6401): startup - clean
I/dhcpcd  ( 6440): version 5.5.6 starting
,E/dhcpcd  ( 6440): get_duid: Read-only file system
I/Babel   ( 6401): deleted: false for 0
,I/dhcpcd  ( 6440): wlan0: rebinding lease of 192.168.1.134
,V/WiFiOffLoadBroadcast( 6335): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6335): MCCMNC not supported: null
I/art     ( 6401): CheckpointMarkThreadRoots callback created = 0xb042d8a0
I/PCSuite ( 6361): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6361): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6361): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/AudioCapabilities( 6401): Unsupported mime audio/x-lg-flac
,V/WiFiOffLoadBroadcast( 6335): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6335): MCCMNC not supported: null
W/AudioCapabilities( 6401): Unsupported mime audio/adpcm
I/PCSuite ( 6361): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
W/AudioCapabilities( 6401): Unsupported mime audio/g726
D/PCSuite ( 6361): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6361): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,W/AudioCapabilities( 6401): Unsupported mime audio/x-ms-wma
V/WiFiOffLoadBroadcast( 6335): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6335): MCCMNC not supported: null
I/PCSuite ( 6361): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6361): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6361): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6335): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/AudioCapabilities( 6401): Unsupported mime audio/wma-voice
D/WiFiOffLoadBroadcast( 6335): MCCMNC not supported: null
W/VideoCapabilities( 6401): Unsupported mime video/mjpg
W/VideoCapabilities( 6401): Unsupported mime video/theora
,I/art     ( 6401): CheckpointMarkThreadRoots callback created = 0xb042d880
W/AudioCapabilities( 6401): Unsupported mime audio/evrc
,W/AudioCapabilities( 6401): Unsupported mime audio/qcelp
W/VideoCapabilities( 6401): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6401): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6401): Unsupported mime audio/qcelp
W/AudioCapabilities( 6401): Unsupported mime audio/evrc
,D/UEI.SmartControl( 6028): QS Service created
V/LGMDMManager( 6381): Create singleton instance
W/VideoCapabilities( 6401): Unsupported mime video/mp4v-esdp
,E/UEI.SmartControl( 6028): QS start get config
D/UEI.SmartControl( 6028):  configuring local db...
,I/VideoCapabilities( 6401): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6401): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6401): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6401): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6401): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6401): onServiceConnected
W/Babel   ( 6401): Attempted to change video mute state without an active call.
I/NotificationManager( 6401): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/AudioManager( 6381): getMode name:com.lge.qremote
V/WiFiOffLoadBroadcast( 6335): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 6335): Not supported operator for automatic switch
,V/WiFiOffLoadBroadcast( 6335): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6335): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6335): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): [LWD] DNSResolver start dns
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  280): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/WiFiOffLoadBroadcast( 6335): MCCMNC not supported: null
I/dhcpcd  ( 6440): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,V/WiFiOffLoadBroadcast( 6335): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6335): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6335): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out(  855): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): Checking http://clients3.google.com/generate_204 on "NG700"
I/dhcpcd  ( 6440): wlan0: leased 192.168.1.134 for 86400 seconds
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/WiFiOffLoadBroadcast( 6335): MCCMNC not supported: null
I/DSQN    ( 6436): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6436): restart monitoring
,E/lowmemorykiller(  244): Error writing /proc/6213/oom_score_adj; errno=22
I/DSQN    ( 6436): dsqn report finish
D/LGDataListener(  280): argv[0]=dsqncommand
D/LGDataListener(  280): argv[1]=wlan0
D/LGDataListener(  280): argv[2]=1
D/LGDataListener(  280): notifyDSQN DSQN STARTMONITOR wlan0 1
V/WiFiOffLoadBroadcast( 6335): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/DSQN    (  855): DSQM DsqnNotification wlan0  1
D/DSQN    (  855): start to monitor internet connection
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 13 Jan 2016 14:32:55 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452695575384], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452695575365]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): Don't send network conditions - lacking user consent.
D/WifiServiceExtension( 1805): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  855): Validated
D/ConnectivityService(  855): Validated NetworkAgentInfo [WIFI () - 101]
D/WifiDataContinuityService(  855): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
I/WifiServerServiceExt(  855): set CMD_CAPTIVE_CHECK_COMPLETED
D/ConnectivityService(  855): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  855):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  855):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  855):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  855): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  855): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  855):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  855):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  855): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  855): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  855): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory-1( 1750): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1750):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/ConnectivityManager.CallbackHandler( 1375): CM callback handler got msg 524290
D/WIFI    (  855): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  855):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/WiFiOffLoadBroadcast( 6335): MCCMNC not supported: null
E/lowmemorykiller(  244): Error writing /proc/6213/oom_score_adj; errno=22
,D/UEI.SmartControl( 6028):  ---- Has DB8: true
,D/UEI.SmartControl( 6028): QS start statue = true Error code = 0
D/UEI.SmartControl( 6028): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6028): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6028): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6028): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6028): IrrcClient ++ 
D/irrcClient( 6028): getIrrcService ++ 
,D/irrcClient( 6028): getIrrcService -- 
D/irrcClient( 6028): IrrcClient -- 
W/irrc_jni( 6028): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6028): Services init done
I/UEI.SmartControl( 6028): Device manager: loading config....
D/UEI.SmartControl( 6028): Config is loaded...
I/ActivityManager(  855): Process com.google.android.gms:car (pid 6213) has died
,V/WiFiOffLoadBroadcast( 6335): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/UEI.SmartControl( 6028): QS Service init finished
D/TelephonyIcons( 1375): null signal icon name: drawable/stat_sys_signal_null
D/UEI.SmartControl( 6028): QS Service version name: 0.1.73
D/UEI.SmartControl( 6028): QS Service version code: 1073
D/UEI.SmartControl( 6028): Service requested: Control
I/[SystemUI]LGNetworkController( 1375): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/UEI.SmartControl( 6028): -----IControl: 11
D/UEI.SmartControl( 6028): File observer start...
E/UEI.SmartControl( 6028): IR Port is disabled: false
D/UEI.SmartControl( 6028): Starting file observer...
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/UEI.SmartControl( 6028): Caller: com.lge.qremote
D/UEI.SmartControl( 6028): ------------ IControl registerCallback...
I/UEI.SmartControl( 6028): Registering callback...
D/WiFiOffLoadBroadcast( 6335): MCCMNC not supported: null
D/UEI.SmartControl( 6028): -----IControl: 19
D/UEI.SmartControl( 6028): Caller: com.lge.qremote
I/UEI.SmartControl( 6028): Registering Services Ready callback...
I/UEI.SmartControl( 6028): Notify client services are ready...
D/UEI.SmartControl( 6028): Internal service binding...
D/UEI.SmartControl( 6028): -----IControl: 8
D/UEI.SmartControl( 6028): Caller: com.lge.qremote
V/WiFiOffLoadBroadcast( 6335): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/UEI.SmartControl( 6028):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6028): Notify AllClients services are ready: 0
,D/WiFiOffLoadBroadcast( 6335): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6335): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6335): MCCMNC not supported: null
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 6
,V/WiFiOffLoadBroadcast( 6335): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  855): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/WiFiOffLoadBroadcast( 6335): MCCMNC not supported: null
I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 15:32:55.596 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/ConnectivityService(  855): identical MTU - not setting
D/Nat464Xlat(  855): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  855): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  855):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  855):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  855): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  855): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  855): enableDataServiceNotify 
D/DSQN    (  855): start dsqn bin
D/ConnectivityManager.CallbackHandler( 1375): CM callback handler got msg 524295
I/PCSuite ( 6361): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6361): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6335): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6335): MCCMNC not supported: null
I/PCSuite ( 6361): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6361): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/DSQN    (  855): dsqn is running restart
,I/AudioManager( 6381): getMode name:com.lge.qremote
I/DSQN    ( 6478): DSQN samuel.seo ver 141203
E/DSQN    ( 6478): DSQN sock connect success to lgdatalistenerd
,I/DSQN    ( 6478): created command queue thread
I/DSQN    ( 6478): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6478): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  855): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  855): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  855): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  855): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  855): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  855): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  855): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  855): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  855): RunningState
I/AudioManager( 6381): getMode name:com.lge.qremote
,I/AudioManager( 6381): getMode name:com.lge.qremote
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/ConnectivityService(  855): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/ConnectivityService(  855): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/ConnectivityService(  855): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  855): onReceive
D/LocSvc_java(  855): got connectivity action
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LocSvc_java(  855): broadcast - no network connections
D/LocSvc_java(  855): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
,D/LocSvc_java(  855): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  855): getAGpsConnectionInfo connType - 4
I/ActivityManager(  855): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6488 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/LocSvc_java(  855): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  855): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  855): onReceive
D/LocSvc_java(  855): got connectivity action
D/LocSvc_java(  855): broadcast - no network connections
D/LocSvc_java(  855): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  855): Sending msg: 4 arg1:0 arg2:1
D/GpsLocationProvider(  855): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java(  855): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  855): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  855): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  855): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  855): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider(  855): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,I/MusicStore( 6488): Database version: 120
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6488): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/rmt_storage(  278): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
,I/rmt_storage(  278): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  278): wakelock acquired: 1, error no: 42
I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  278): 
I/rmt_storage(  278): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6488): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6488): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6488): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6488): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  855): Process com.android.providers.calendar (pid 6056) has died
,V/JNIHelp ( 6488): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6488): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6488): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1c0dc601: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6488): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6488): GMSCore installation verified
,I/ConfigStore( 6488): Config Database version: 1
,I/MediaRouter( 6488): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6488): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6488): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6488): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  855): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6532 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 15:32:57.574 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/GHttpClientFactory( 6488): Using our fixed implementation of GMSCore's GoogleHttpClient
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/GoogleURLConnFactory( 6488): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 6532): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6532): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6532): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/NotificationManager( 1945): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/NotificationManager( 6488): com.google.android.music: cancel(1061) by com.google.android.music
,V/WifiInternetCheck(  855): Single check msg out of sync, ignoring.
,D/ConnectivityService(  855): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  855): onReceive
D/LocSvc_java(  855): got connectivity action
D/LocSvc_java(  855): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  855): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  855): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  855): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  855): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  855): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/NetworkMonitor( 6488): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider(  855): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/LGEmail ( 6532): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6532): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/ActivityManager(  855): Process com.android.vending (pid 5491) has died
,D/eas_req ( 6532): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  855): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6570 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6532): JNI_OnLoad()
I/HubEmail( 6532): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6532): registerNatives()
I/HubEmail( 6532): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6532): registerNativeMethods()
I/HubEmail( 6532): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6532): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 6532): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 6570): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6570): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6570): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6570): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6570): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6570): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6570): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6570): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  855): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6594 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6570): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,I/art     (  305): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 301us total 26.322ms
I/art     (  305): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 22.620ms
,E/LGDMClient( 6570): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6570): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6570): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6570): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 20.717ms
,D/LGDMClient( 6570): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  855): Killing 5993:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/libprocessgroup(  855): failed to open /acct/uid_10069/pid_5993/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 6594): onCreate
,W/AppUp4:DB( 6594):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6594):  setFingerPrint start
I/AppUp4:DB( 6594):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6594):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6594):  SDK version = 0
I/AppUp4:DB( 6594):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6594): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6594): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6594): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6594): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6594): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6594): onReceive
I/AppUp4:CustModeStarterReceiver( 6594): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6594): Context : android.app.ReceiverRestrictedContext@3ca42455
,D/AppUp4:CustFacade( 6594): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6594): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6594): begin check event
I/AppUp4:CustModeStarterReceiver( 6594): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6594): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6594): call method handleAsyncCustNotification.
,D/AppUp4:CustModeStarterReceiver( 6594): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6594): handleAsyncCustNotification do not startCustService
I/ActivityManager(  855): Killing 6401:com.google.android.talk/u0a61 (adj 15): empty #11
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  280): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
,I/System.out(  855): propertyValue:false
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  280): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out(  855): propertyValue:false
W/libprocessgroup(  855): failed to open /acct/uid_10061/pid_6401/cgroup.procs: No such file or directory
,I/DSQN    ( 6478): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6478): restart monitoring
D/LGDataListener(  280): argv[0]=dsqncommand
D/LGDataListener(  280): argv[1]=wlan0
D/LGDataListener(  280): argv[2]=1
D/LGDataListener(  280): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 6478): dsqn report finish
D/DSQN    (  855): DSQM DsqnNotification wlan0  1
D/DSQN    (  855): start to monitor internet connection
I/LgeMiscReceiver( 3133): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3133): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3133): networkInfo.isConnected() = false
V/WifiInternetCheck(  855): isHttpConnectionAvailable - We got a valid response : 204
,I/ActivityManager(  855): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6622 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6622): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6622): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6622): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  855): Killing 6335:com.android.settings/1000 (adj 15): empty #11
,D/PhoneMonitor( 6622): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6622): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6622): [parse] Load xml
V/TelephonyAutoProfiling( 6622): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6622): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6622): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  855): failed to open /acct/uid_1000/pid_6335/cgroup.procs: No such file or directory
,V/AlarmManager(  855): ELAPSED_WAKEUP set : Alarm{3bb4f599 type 2 when 106083 com.google.android.gms} when 106083
V/DownloadManager( 3161): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3161): DownloadService onCreate
I/NotificationManager( 3161): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3161): in removeSpuriousFiles
I/CheckinService( 4127): Checkin interval check for package: unspecified last checkin: 1452695551555 min interval config: 0 actual interval: 27761
,V/DownloadManager( 3161): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3161): created cursor android.database.sqlite.SQLiteCursor@8295fe9 on behalf of 3161
I/DownloadManager( 3161): in trimDatabase
V/DownloadManager( 3161): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3161): created cursor android.database.sqlite.SQLiteCursor@2c0d046e on behalf of 3161
I/ActivityManager(  855): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6648 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3161): DownloadService onStartCommand
I/CheckinService( 4127): Checking schedule, now: 1452695579365 next: 1452695581501
I/CheckinService( 4127): active receiver: disabled
V/DownloadManager( 3161): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3161): created cursor android.database.sqlite.SQLiteCursor@2379139c on behalf of 3161
,V/DownloadManager( 3161): DownloadService onDestroy
,I/ActivityManager(  855): Killing 6028:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 6381): android.os.DeadObjectException
W/System.err( 6381): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6381): 	at android.os.BinderProxy.transact(Binder.java:496)
,W/System.err( 6381): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6381): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 6381): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6381): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6381): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6381): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6381): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6381): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6381): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6381): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6381): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6381): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6381): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6381): android.os.DeadObjectException
W/System.err( 6381): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6381): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6381): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6381): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 6381): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6381): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6381): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6381): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6381): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6381): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6381): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6381): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6381): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6381): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6381): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  855): failed to open /acct/uid_10089/pid_6028/cgroup.procs: No such file or directory
,W/ActivityManager(  855): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
D/WeatherAncestor( 2632): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:32:59
I/ActivityManager(  855): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6674 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UpdateThreadPoolManager( 2632): 2 : This is isUpdating : false
D/WeatherAncestor( 2632): connectivity changed - connection : true
D/Weather_cast( 2632): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2632): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:32:59
D/WeatherService( 2632): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  855): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6691 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  855): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2632): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2632): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2632): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
,I/art     (  855): Explicit concurrent mark sweep GC freed 73729(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 3.328ms total 185.512ms
,I/[SystemUI]Clock( 1375): called onTimeUpdated()
I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
,W/ResourcesManager( 6691): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/WeatherService( 2632): 2 : TimeTick Intent has been received, Time(hour:min:sec) 15:33:0
,D/WeatherService( 2632): 2 : TimeTick Intent And Screen On
D/WeatherService( 2632): 2 : SDK version : 21
W/ActivityManager(  855): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2632): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2632): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2632): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2632): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2632): 2 : This is isUpdating : false
D/WeatherService( 2632): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2632): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2632): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2632): 2 : Fixed theme : optimus
D/WeatherReflect( 2632): 2 : Map key string is -2
D/lim     ( 2632): 2 : time = 15:33
,I/WeatherReflect( 2632): Model Name : LG-D722
D/WeatherTheme( 2632): 2 : Different view - status_min_formatted : 32 != 33
D/WeatherTheme( 2632): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2632): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2632): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2632): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2632): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2632): currentPackage=com.lge.sizechangable.weather.theme.optimus
D/UEI.SmartControl( 6674): Quickset Services start...
I/UEI.SmartControl( 6674): Manufacture = LGE
D/UEI.SmartControl( 6674): File observer start...
E/UEI.SmartControl( 6674): IR Port is disabled: false
D/UEI.SmartControl( 6674): Starting file observer...
D/UEI.SmartControl( 6674): Extracting JNI libs...
D/UEI.SmartControl( 6674): --- this system supports 32-bit or 64-bit only
,D/Weather4x2_optimus( 2632): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2632): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2632): forecast size is 0
D/Theme   ( 2632): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2632): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2632): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2632): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2632): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2632): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2632): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2632): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2632): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2632): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2632): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2632): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2632): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2632): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2632): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2632): url is : null
D/Theme   ( 2632): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2632): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2632): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
,D/WeatherAncestor( 2632): 2 : update view, appWidgetId: 2
D/WeatherService( 2632): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 15:33:0
D/UEI.SmartControl( 6674): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6674): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6674): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/UEI.SmartControl( 6674): --- Selecting new region: 2
I/UEI.SmartControl( 6674): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6674): Platform has CIR...
,I/ActivityManager(  855): Process com.google.android.music:main (pid 6488) has died
D/UEI.SmartControl( 6674): NO CIR support, need to check package...
I/UEI.SmartControl( 6674): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6674): QS Service created
,E/UEI.SmartControl( 6674): QS start get config
,I/Babel_SMS( 6691): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6691): MmsConfig.loadMmsSettings
E/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/Babel_SMS( 6691): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6691): MmsConfig.loadFromDatabase
D/UEI.SmartControl( 6674): Loading JNI Libs...
D/UEI.SmartControl( 6674):  configuring local db...
,E/Babel_SMS( 6691): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6691): MmsConfig.loadFromResources
E/Babel_SMS( 6691): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6691): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6691): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6691): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6691): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6691): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6691): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6691): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6691): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6691): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6691): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6691): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6691): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6691): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6691): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6691): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6691): found sensor: LGE Relative Motion Detector Sensor, handle=34
,D/SensorManager( 6691): found sensor: Motion Accel, handle=46
I/art     ( 6691): CheckpointMarkThreadRoots callback created = 0xb042d810
,W/Settings( 6691): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6691): startup - clean
,I/art     ( 6691): CheckpointMarkThreadRoots callback created = 0xb042d7f0
,I/Babel   ( 6691): deleted: false for 0
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/UEI.SmartControl( 6674):  ---- Has DB8: true
D/UEI.SmartControl( 6674): QS start statue = true Error code = 0
D/UEI.SmartControl( 6674): QS version = v2.7.11.1_RC1
,D/UEI.SmartControl( 6674): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6674): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6674): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6674): IrrcClient ++ 
D/irrcClient( 6674): getIrrcService ++ 
D/irrcClient( 6674): getIrrcService -- 
,D/irrcClient( 6674): IrrcClient -- 
W/irrc_jni( 6674): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6674): Services init done
,I/UEI.SmartControl( 6674): Device manager: loading config....
I/ActivityManager(  855): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6727 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/UEI.SmartControl( 6674): QS Service init finished
,D/UEI.SmartControl( 6674): QS Service version name: 0.1.73
D/UEI.SmartControl( 6674): Config is loaded...
D/UEI.SmartControl( 6674): QS Service version code: 1073
D/UEI.SmartControl( 6674): Service requested: Control
D/UEI.SmartControl( 6674): -----IControl: 11
D/UEI.SmartControl( 6674): Caller: com.lge.qremote
D/UEI.SmartControl( 6674): ------------ IControl registerCallback...
I/UEI.SmartControl( 6674): Registering callback...
D/UEI.SmartControl( 6674): -----IControl: 19
D/UEI.SmartControl( 6674): Internal service binding...
,D/UEI.SmartControl( 6674): Caller: com.lge.qremote
I/UEI.SmartControl( 6674): Registering Services Ready callback...
I/UEI.SmartControl( 6674): Notify client services are ready...
D/UEI.SmartControl( 6674): -----IControl: 8
D/UEI.SmartControl( 6674): Caller: com.lge.qremote
W/AudioCapabilities( 6691): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6691): Unsupported mime audio/adpcm
,W/AudioCapabilities( 6691): Unsupported mime audio/g726
W/AudioCapabilities( 6691): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6691): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6691): Unsupported mime video/mjpg
W/VideoCapabilities( 6691): Unsupported mime video/theora
,D/UEI.SmartControl( 6674):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6674): Notify AllClients services are ready: 0
W/AudioCapabilities( 6691): Unsupported mime audio/evrc
,W/AudioCapabilities( 6691): Unsupported mime audio/qcelp
W/VideoCapabilities( 6691): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6691): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6691): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6691): Unsupported mime audio/evrc
W/VideoCapabilities( 6691): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6691): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6691): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6691): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6691): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6691): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6691): onServiceConnected
W/Babel   ( 6691): Attempted to change video mute state without an active call.
,I/NotificationManager( 6691): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 6691): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6691): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6691): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6691): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  280): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  280): App 10061 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
,D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 6691): propertyValue:false
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6727): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,I/Babel   ( 6691): connection state changed from UNKNOWN to CONNECTED
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6727): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/ActivityManager(  855): Killing 6361:com.lge.sync/1000 (adj 15): empty #11
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6727): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6727): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6727): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6727):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6727):   adb logcat -s GAv4
,W/libprocessgroup(  855): failed to open /acct/uid_1000/pid_6361/cgroup.procs: No such file or directory
,W/GAv4    ( 6727): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 6727): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6727): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 6727): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6727): Time to load native libraries: 2 ms (timestamps 8435-8437)
I/LibraryLoader( 6727): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6727): Binding Chromium to main looper Looper (main, tid 1) {479651e}
I/LibraryLoader( 6727): Expected native library version number "",actual native library version number ""
I/chromium( 6727): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6727): Initializing chromium process, singleProcess=true
,W/art     ( 6727): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6727): ApplicationContext is null in ApplicationStatus
W/chromium( 6727): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6727): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6727): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6727): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6727): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6727): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6727): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6727): Remote Branch: 
I/Adreno-EGL( 6727): Local Patches: 
I/Adreno-EGL( 6727): Reconstruct Branch: 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/AudioPolicyService(  285): registerClient() client 0xb39b07c0, uid 10079
,W/AudioManagerAndroid( 6727): Requires BLUETOOTH permission
I/NSApplication( 6727): Starting up...
,I/ActivityManager(  855): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6791 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  855): Killing 6381:com.lge.qremote/u0a106 (adj 15): empty #11
I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,W/libprocessgroup(  855): failed to open /acct/uid_10106/pid_6381/cgroup.procs: No such file or directory
,I/ActivityManager(  855): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6811 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  855): Killing 6532:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  855): failed to open /acct/uid_10021/pid_6532/cgroup.procs: No such file or directory
,W/ResourcesManager( 6811): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  855): Killing 6570:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  855): failed to open /acct/uid_1000/pid_6570/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  855): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6835 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  855): RTC_WAKEUP set : Alarm{319a9ca3 type 0 when 1452695581501 com.google.android.gms} when 1452695581501
,V/AlarmManager(  855): RTC_WAKEUP set : Alarm{13a66359 type 0 when 1452695582950 com.google.android.googlequicksearchbox} when 1452695582950
I/MusicStore( 6835): Database version: 120
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6835): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6835): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6835): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,W/ResourcesManager( 6835): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6835): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 6835): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6835): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6835): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1c0dc601: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6835): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6835): GMSCore installation verified
I/ConfigStore( 6835): Config Database version: 1
,I/MediaRouter( 6835): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6835): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6835): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6835): type=WIFI subType= reason=null isConnected=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  855): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6874 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6835): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6835): Using platform SSLCertificateSocketFactory
W/ResourcesManager( 6874): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6874): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6874): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/ActivityManager(  855): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6893 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  855): RTC_WAKEUP set : Alarm{ed6ba9 type 0 when 1452695583856 com.android.vending} when 1452695583856
,I/ActivityManager(  855): Killing 6594:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/NotificationManager( 6835): com.google.android.music: cancel(1061) by com.google.android.music
W/libprocessgroup(  855): failed to open /acct/uid_10011/pid_6594/cgroup.procs: No such file or directory
I/LGEmail ( 6874): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6874): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/Finsky  ( 6893): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/ActivityManager(  855): Process com.uei.lg.quicksetsdk.lite (pid 6674) has died
,D/Finsky  ( 6893): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 6893): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6893): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 6893): com.android.vending: cancel(-1050172287) by com.android.vending
,D/Ads     ( 6893): Skipping gmscore version check
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/Finsky  ( 6893): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6893): [1] Libraries$2.run: Finished loading 1 libraries.
V/DownloadManager( 3161): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3161): created cursor android.database.sqlite.SQLiteCursor@1708f97a on behalf of 6893
D/eas_req ( 6874): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
D/Finsky  ( 6893): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 6893): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  855): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6954 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/art     (  305): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 288us total 21.795ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 293us total 21.125ms
,I/HubEmail( 6874): JNI_OnLoad()
I/HubEmail( 6874): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6874): registerNatives()
I/HubEmail( 6874): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6874): registerNativeMethods()
I/HubEmail( 6874): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/art     ( 6874): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 22.067ms
W/Settings( 6874): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 6954): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6954): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6954): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6954): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6954): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/Finsky  ( 6893): [840] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/LGDMClient( 6954): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/Finsky  ( 6893): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/LGDMClient( 6954): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6954): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  855): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6978 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6954): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
I/ActivityManager(  855): Killing 6622:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,E/LGDMClient( 6954): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6954): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6954): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6954): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6954): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,W/libprocessgroup(  855): failed to open /acct/uid_10038/pid_6622/cgroup.procs: No such file or directory
,I/ActivityManager(  855): Killing 6648:com.lge.drmservice/u0a51 (adj 15): empty #11
I/AppUp4:AppBoxCP( 6978): onCreate
,W/AppUp4:DB( 6978):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6978):  setFingerPrint start
I/AppUp4:DB( 6978):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6978):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6978):  SDK version = 0
,I/AppUp4:DB( 6978):  beforefinger == newfinger no write in DB
W/libprocessgroup(  855): failed to open /acct/uid_10051/pid_6648/cgroup.procs: No such file or directory
,D/AppUp4:AppBoxApplication( 6978): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6978): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6978): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6978): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6978): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6978): onReceive
I/AppUp4:CustModeStarterReceiver( 6978): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6978): Context : android.app.ReceiverRestrictedContext@3ca42455
D/AppUp4:CustFacade( 6978): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6978): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6978): begin check event
I/AppUp4:CustModeStarterReceiver( 6978): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6978): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6978): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6978): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6978): handleAsyncCustNotification do not startCustService
I/ActivityManager(  855): Killing 6691:com.google.android.talk/u0a61 (adj 15): empty #11
I/LgeMiscReceiver( 3133): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
W/libprocessgroup(  855): failed to open /acct/uid_10061/pid_6691/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3133): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3133): networkInfo.isConnected() = false
I/ActivityManager(  855): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7003 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/PhoneMonitor( 7003): Register our PhoneStateListener
,I/art     (  855): Explicit concurrent mark sweep GC freed 24968(1204KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.155ms total 164.415ms
,D/MobileConnectivityChangeReceiver( 7003): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7003): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  855): Killing 6727:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
W/libprocessgroup(  855): failed to open /acct/uid_10079/pid_6727/cgroup.procs: No such file or directory
,I/CheckinService( 4127): Checkin interval check for package: unspecified last checkin: 1452695551555 min interval config: 0 actual interval: 34719
,V/DownloadManager( 3161): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3161): DownloadService onCreate
I/DownloadManager( 3161): in removeSpuriousFiles
,I/NotificationManager( 3161): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3161): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3161): created cursor android.database.sqlite.SQLiteCursor@3931952b on behalf of 3161
,I/DownloadManager( 3161): in trimDatabase
V/DownloadManager( 3161): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3161): created cursor android.database.sqlite.SQLiteCursor@18242321 on behalf of 3161
,D/PhoneMonitor( 7003): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
I/ActivityManager(  855): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7043 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/DownloadManager( 3161): DownloadService onStartCommand
V/TelephonyAutoProfiling( 7003): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7003): [parse] Load xml
V/TelephonyAutoProfiling( 7003): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7003): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,I/jxcore-log( 6188): Test app app.js loaded
I/jxcore-log( 6188): 
V/DownloadManager( 3161): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/PhoneMonitor( 7003): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,V/DownloadManager( 3161): created cursor android.database.sqlite.SQLiteCursor@34b25907 on behalf of 3161
I/CheckinService( 4127): Checking schedule, now: 1452695586402 next: 1452695581501
I/CheckinService( 4127): active receiver: enabled
,V/DownloadManager( 3161): DownloadService onDestroy
,I/chromium( 6188): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/CheckinService( 4127): Preparing to send checkin request
I/EventLogService( 4127): Accumulating logs since 1452695543209
,I/CheckinRequestBuilder( 4127): Checkin reason type: 8 attempt count: 1
,D/WeatherAncestor( 2632): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:33:6
E/ActivityThread( 4127): Failed to find provider info for com.google.android.wearable.settings
D/UpdateThreadPoolManager( 2632): 2 : This is isUpdating : false
D/WeatherAncestor( 2632): connectivity changed - connection : true
D/Weather_cast( 2632): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2632): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:33:6
D/WeatherService( 2632): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  855): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7072 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  855): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2632): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2632): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2632): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 7072): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  855): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7091 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/Babel_SMS( 7072): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7072): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7072): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7072): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7072): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7072): MmsConfig.loadFromResources
E/Babel_SMS( 7072): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7072): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,W/ResourcesManager( 7091): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7091): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/SensorManager( 7072): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7072): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7072): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7072): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7072): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7072): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7072): found sensor: LGE Rotation Vector Sensor, handle=36
,D/SensorManager( 7072): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7072): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7072): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7072): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7072): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7072): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7072): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7072): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7072): found sensor: Motion Accel, handle=46
I/ActivityManager(  855): Process com.google.android.music:main (pid 6835) has died
,W/art     ( 7091): Verification of void com.google.android.gms.common.app.GmsApplication.<init>() took 117.959ms
W/Settings( 7072): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 7072): startup - clean
,I/art     ( 7072): CheckpointMarkThreadRoots callback created = 0xb042d450
,I/Babel   ( 7072): deleted: false for 0
,I/MultiDex( 7091): VM with version 2.1.0 has multidex support
I/MultiDex( 7091): install
I/MultiDex( 7091): VM has multidex support, MultiDex support library is disabled.
I/art     ( 7072): CheckpointMarkThreadRoots callback created = 0xb042d430
V/JNIHelp ( 7091): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7091): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7091): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2c0d046e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7091): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  855): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7118 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/NotificationManager( 7091): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 7091): com.google.android.gms: cancel(39789) by com.google.android.gms
W/AudioCapabilities( 7072): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 7072): Unsupported mime audio/adpcm
W/AudioCapabilities( 7072): Unsupported mime audio/g726
W/AudioCapabilities( 7072): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7072): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7072): Unsupported mime video/mjpg
W/VideoCapabilities( 7072): Unsupported mime video/theora
,W/AudioCapabilities( 7072): Unsupported mime audio/evrc
,W/AudioCapabilities( 7072): Unsupported mime audio/qcelp
W/VideoCapabilities( 7072): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7072): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7072): Unsupported mime audio/qcelp
W/AudioCapabilities( 7072): Unsupported mime audio/evrc
I/art     ( 7091): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7091): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/VideoCapabilities( 7072): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 7072): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7072): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7072): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7072): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7072): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 7072): onServiceConnected
W/Babel   ( 7072): Attempted to change video mute state without an active call.
,D/libc-netbsd( 7072): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 7072): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7072): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7072): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  280): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 7072): propertyValue:false
I/NotificationManager( 7072): com.google.android.talk: cancel(10436) by com.google.android.talk
I/Babel   ( 7072): connection state changed from UNKNOWN to CONNECTED
,D/NativeLibraryUtils( 7091): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  285): Instantiating CDM.
I/WVCdm   (  285): CdmEngine::OpenSession
I/WVCdm   (  285): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  285): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  285): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  285): L1 library not specified. Falling Back to L3
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7118): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7118): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/WVCdm   (  285): CdmEngine::QueryKeyControlInfo
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/WVCdm   (  285): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  285): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  285): CdmEngine::GenerateKeyRequest
W/ContextImpl( 7118): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/GAv4    ( 7118): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7118):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7118):   adb logcat -s GAv4
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7118): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
D/WVCdm   (  285): PrepareKeyRequest: nonce=1120310248
W/GAv4    ( 7118): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7118): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7118): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/ActivityManager(  855): Process com.android.vending (pid 6893) has died
,D/sensors_hal_Time(  855): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  855): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  855): tsOffsetIs: Apps: 114891841159; DSPS: 3863277; Offset : -3007477366
,I/art     ( 7091): CheckpointMarkThreadRoots callback created = 0xb04cbdc0
I/art     ( 7091): CheckpointMarkThreadRoots callback created = 0xb04cbdb0
,I/WebViewFactory( 7118): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/dex2oat ( 7164): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/LibraryLoader( 7118): Time to load native libraries: 2 ms (timestamps 5103-5105)
,I/LibraryLoader( 7118): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7118): Binding Chromium to main looper Looper (main, tid 1) {479651e}
I/LibraryLoader( 7118): Expected native library version number "",actual native library version number ""
,I/chromium( 7118): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/dex2oat ( 7164): dex2oat took 109.415ms (threads: 4)
I/BrowserStartupController( 7118): Initializing chromium process, singleProcess=true
,W/art     ( 7118): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7118): ApplicationContext is null in ApplicationStatus
I/Adreno-EGL( 7091): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7091): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7091): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7091): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7091): Remote Branch: 
I/Adreno-EGL( 7091): Local Patches: 
I/Adreno-EGL( 7091): Reconstruct Branch: 
W/chromium( 7118): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7118): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7118): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7118): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7118): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7118): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7118): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7118): Remote Branch: 
I/Adreno-EGL( 7118): Local Patches: 
I/Adreno-EGL( 7118): Reconstruct Branch: 
V/AudioPolicyService(  285): registerClient() client 0xb39b0880, uid 10079
,W/AudioManagerAndroid( 7118): Requires BLUETOOTH permission
I/NSApplication( 7118): Starting up...
I/Adreno-EGL( 7091): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7091): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7091): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7091): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7091): Remote Branch: 
I/Adreno-EGL( 7091): Local Patches: 
I/Adreno-EGL( 7091): Reconstruct Branch: 
,I/ActivityManager(  855): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7190 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  855): Process com.lge.email (pid 6874) has died
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/Adreno-EGL( 7091): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7091): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7091): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7091): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7091): Remote Branch: 
I/Adreno-EGL( 7091): Local Patches: 
I/Adreno-EGL( 7091): Reconstruct Branch: 
,I/MusicStore( 7190): Database version: 120
,I/WVCdm   (  285): CdmEngine::OpenSession
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7190): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/MusicWidget( 2553): mDelayedStopHandler : unbind
,I/MusicBrowser( 2010): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2010): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2010): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2010): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2010): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2010): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2010): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2010): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  855):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@2517954bcom.lge.music.MediaPlaybackService$6@3d899b28
,D/MusicBrowser( 2010): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2010): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2010): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2010): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2010): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@2b4fb0d1
I/MusicBrowser( 2010): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2010): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2010): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2010): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2010): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2010): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2010): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2010): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2010): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2010): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2010): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2010): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2010): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2010): reset
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7190): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7190): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
V/MediaPlayer[Native]( 2010): setListener
V/MediaPlayer[Native]( 2010): disconnect
V/MediaPlayer[Native]( 2010): destructor
,V/AudioFlinger(  285): releasing 19 from 2010 for -1
V/AudioFlinger(  285):  decremented refcount to 0
V/AudioFlinger(  285): purging stale effects
V/MediaPlayer[Native]( 2010): disconnect
D/MusicBrowser( 2010): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2010): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2010): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2010): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2010): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2010): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2010): [SmartShareManagerClient] unregisterListener: 164458561
W/SmartShareClient( 2010): [SmartShareManagerClient] unregisterListener invalid listener: 164458561
I/SmartShareClient( 2010): [SmartShareManagerClient] terminate service: 2010/MediaPlaybackService/475389503
E/HomeCloudIF( 2010): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2010): [SmartShareManagerClient] unbindService context:android.app.Application@17f2c9e6
,W/ResourcesManager( 7190): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7190): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/CloudHub( 2010): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2010): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2010): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
,I/MusicBrowser( 2010): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2010): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/CloudHub( 2010): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29989
,V/JNIHelp ( 7190): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7190): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7190): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1c0dc601: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7190): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7190): GMSCore installation verified
,I/ConfigStore( 7190): Config Database version: 1
,I/art     ( 6100): Explicit concurrent mark sweep GC freed 2079(89KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 377us total 39.974ms
,I/MediaRouter( 7190): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7190): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7190): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7190): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  855): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7224 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7190): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7190): Using platform SSLCertificateSocketFactory
W/ResourcesManager( 7224): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7224): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7224): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  855): Killing 6954:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/libprocessgroup(  855): failed to open /acct/uid_1000/pid_6954/cgroup.procs: No such file or directory
,I/NotificationManager( 7190): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 7224): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7224): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/WVCdm   (  285): CdmEngine::CloseSession
,I/WVCdm   (  285): CdmEngine::QueryKeyControlInfo
,D/eas_req ( 7224): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
W/WVCdm   (  285): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  285): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  285): CdmEngine::GenerateKeyRequest
D/WVCdm   (  285): PrepareKeyRequest: nonce=476000096
,I/ActivityManager(  855): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7256 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7224): JNI_OnLoad()
I/HubEmail( 7224): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7224): registerNatives()
I/HubEmail( 7224): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7224): registerNativeMethods()
I/HubEmail( 7224): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7224): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  855): Killing 6978:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  855): failed to open /acct/uid_10011/pid_6978/cgroup.procs: No such file or directory
W/Settings( 7224): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 7256): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7256): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7256): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7256): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7256): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7256): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager(  855): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7279 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/LGDMClient( 7256): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/art     (  855): Explicit concurrent mark sweep GC freed 15109(737KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.137ms total 168.931ms
,I/LGDMClient( 7256): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 7256): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,I/AppUp4:AppBoxCP( 7279): onCreate
,W/AppUp4:DB( 7279):  [AppBoxDatabaseHelper] construct
E/LGDMClient( 7256): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7256): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7256): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7256): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
I/AppUp4:DB( 7279):  setFingerPrint start
I/AppUp4:DB( 7279):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7279):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7279):  SDK version = 0
,I/AppUp4:DB( 7279):  beforefinger == newfinger no write in DB
D/LGDMClient( 7256): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
D/AppUp4:AppBoxApplication( 7279): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7279): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7279): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7279): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7279): [onReceive] request level :IDLE....
I/ActivityManager(  855): Killing 7003:com.google.android.setupwizard/u0a38 (adj 15): empty #11
I/AppUp4:CustModeStarterReceiver( 7279): onReceive
I/AppUp4:CustModeStarterReceiver( 7279): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7279): Context : android.app.ReceiverRestrictedContext@3ca42455
D/AppUp4:CustFacade( 7279): isCustomizationCompleted : false
,W/libprocessgroup(  855): failed to open /acct/uid_10038/pid_7003/cgroup.procs: No such file or directory
,D/AppUp4:CustFacade( 7279): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7279): begin check event
I/AppUp4:CustModeStarterReceiver( 7279): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7279): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7279): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7279): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7279): handleAsyncCustNotification do not startCustService
I/ActivityManager(  855): Killing 7043:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  855): failed to open /acct/uid_10051/pid_7043/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3133): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3133): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3133): networkInfo.isConnected() = true
D/PhoneState( 3133): setPdpRejectCasuse : false
,I/ActivityManager(  855): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7302 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/art     (  305): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 294us total 23.615ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 261us total 20.263ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 261us total 21.567ms
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/PhoneMonitor( 7302): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7302): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7302): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  855): Killing 7072:com.google.android.talk/u0a61 (adj 15): empty #11
D/PhoneMonitor( 7302): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7302): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7302): [parse] Load xml
,V/TelephonyAutoProfiling( 7302): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7302): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 7302): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  855): failed to open /acct/uid_10061/pid_7072/cgroup.procs: No such file or directory
V/DownloadManager( 3161): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3161): DownloadService onCreate
I/NotificationManager( 3161): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3161): in removeSpuriousFiles
,V/DownloadManager( 3161): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3161): created cursor android.database.sqlite.SQLiteCursor@1ae93dd2 on behalf of 3161
I/DownloadManager( 3161): in trimDatabase
V/DownloadManager( 3161): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3161): created cursor android.database.sqlite.SQLiteCursor@28917ea3 on behalf of 3161
I/ActivityManager(  855): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7324 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3161): DownloadService onStartCommand
V/DownloadManager( 3161): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/CheckinService( 4127): Checkin interval check for package: unspecified last checkin: 1452695551555 min interval config: 0 actual interval: 39417
V/DownloadManager( 3161): created cursor android.database.sqlite.SQLiteCursor@26dd1559 on behalf of 3161
,V/DownloadManager( 3161): DownloadService onDestroy
I/ActivityManager(  855): Killing 7118:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,W/libprocessgroup(  855): failed to open /acct/uid_10079/pid_7118/cgroup.procs: No such file or directory
D/WeatherAncestor( 2632): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:33:11
,D/UpdateThreadPoolManager( 2632): 2 : This is isUpdating : false
D/WeatherAncestor( 2632): connectivity changed - connection : true
D/Weather_cast( 2632): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2632): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:33:11
D/WeatherService( 2632): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  855): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7341 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  855): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2632): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2632): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2632): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 7341): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7341): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7341): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7341): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7341): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7341): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7341): MmsConfig.loadFromResources
E/Babel_SMS( 7341): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7341): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7341): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7341): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7341): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7341): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7341): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7341): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7341): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7341): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7341): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7341): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7341): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7341): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7341): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7341): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7341): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7341): found sensor: Motion Accel, handle=46
,W/Settings( 7341): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7341): startup - clean
I/art     ( 7341): CheckpointMarkThreadRoots callback created = 0xb042d4b0
,I/Babel   ( 7341): deleted: false for 0
,I/art     ( 7341): CheckpointMarkThreadRoots callback created = 0xb042d490
,I/ActivityManager(  855): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7372 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
W/AudioCapabilities( 7341): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7341): Unsupported mime audio/adpcm
W/AudioCapabilities( 7341): Unsupported mime audio/g726
W/AudioCapabilities( 7341): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7341): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7341): Unsupported mime video/mjpg
W/VideoCapabilities( 7341): Unsupported mime video/theora
,W/AudioCapabilities( 7341): Unsupported mime audio/evrc
,W/AudioCapabilities( 7341): Unsupported mime audio/qcelp
W/VideoCapabilities( 7341): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7341): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7341): Unsupported mime audio/qcelp
,W/AudioCapabilities( 7341): Unsupported mime audio/evrc
W/VideoCapabilities( 7341): Unsupported mime video/mp4v-esdp
,I/WVCdm   (  285): CdmEngine::CloseSession
,I/VideoCapabilities( 7341): Unsupported profile 4 for video/mp4v-es
I/WVCdm   (  285): L3 Terminate.
W/VideoCapabilities( 7341): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7341): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7341): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7341): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 7341): onServiceConnected
W/Babel   ( 7341): Attempted to change video mute state without an active call.
,I/NotificationManager( 7341): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 7341): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7341): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7341): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7341): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  280): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 7341): propertyValue:false
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7372): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7372): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7372): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
I/GAv4    ( 7372): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7372):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7372):   adb logcat -s GAv4
W/ContextImpl( 7372): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/Babel   ( 7341): connection state changed from UNKNOWN to CONNECTED
I/ActivityManager(  855): Killing 6791:com.android.chrome/u0a48 (adj 15): empty #11
,W/libprocessgroup(  855): failed to open /acct/uid_10048/pid_6791/cgroup.procs: No such file or directory
,W/GAv4    ( 7372): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 7372): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7372): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 7372): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/art     ( 6811): CheckpointMarkThreadRoots callback created = 0xb042dd80
I/art     ( 6811): CheckpointMarkThreadRoots callback created = 0xb042dd70
,I/LibraryLoader( 7372): Time to load native libraries: 2 ms (timestamps 9244-9246)
I/LibraryLoader( 7372): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7372): Binding Chromium to main looper Looper (main, tid 1) {479651e}
I/LibraryLoader( 7372): Expected native library version number "",actual native library version number ""
I/chromium( 7372): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7372): Initializing chromium process, singleProcess=true
,W/art     ( 7372): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7372): ApplicationContext is null in ApplicationStatus
W/chromium( 7372): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7372): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7372): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7372): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7372): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7372): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7372): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7372): Remote Branch: 
I/Adreno-EGL( 7372): Local Patches: 
I/Adreno-EGL( 7372): Reconstruct Branch: 
V/AudioPolicyService(  285): registerClient() client 0xb3ac1980, uid 10079
,W/AudioManagerAndroid( 7372): Requires BLUETOOTH permission
I/NSApplication( 7372): Starting up...
I/ActivityManager(  855): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7440 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  855): Killing 6811:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  855): failed to open /acct/uid_10086/pid_6811/cgroup.procs: No such file or directory
,I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 15:33:12.668 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  855): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7459 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  855): Killing 2010:com.lge.music/u0a28 (adj 15): empty #11
V/AudioFlinger(  285): 2010 died, releasing its sessions
,V/AudioFlinger(  285):  pid 1750 @ 0
V/AudioFlinger(  285):  pid 3133 @ 1
V/AudioFlinger(  285):  pid 3133 @ 2
W/libprocessgroup(  855): failed to open /acct/uid_10028/pid_2010/cgroup.procs: No such file or directory
,W/ResourcesManager( 7459): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  855): Killing 7190:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  855): failed to open /acct/uid_10081/pid_7190/cgroup.procs: No such file or directory
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 1733): propertyValue:false
,I/ActivityManager(  855): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7495 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/ResourcesManager( 7495): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  855): Message: 20
,D/BluetoothManagerService(  855): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fa088e8:true
D/BluetoothAdapterService(255935480)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@38dce70e
D/BluetoothAdapterService(255935480)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@38dce70e
,I/ActivityManager(  855): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7520 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/LGMDMManager( 7495): Create singleton instance
,I/CheckinRequestBuilder( 4127): Classify the device as Phone.
,D/UEI.SmartControl( 7520): Quickset Services start...
,I/UEI.SmartControl( 7520): Manufacture = LGE
D/UEI.SmartControl( 7520): File observer start...
E/UEI.SmartControl( 7520): IR Port is disabled: false
D/UEI.SmartControl( 7520): Starting file observer...
D/UEI.SmartControl( 7520): Extracting JNI libs...
D/libc-netbsd( 4127): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/UEI.SmartControl( 7520): --- this system supports 32-bit or 64-bit only
D/libc-netbsd( 4127): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/AudioManager( 7495): getMode name:com.lge.qremote
D/libc-netbsd( 4127): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4127): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
I/CheckinService( 4127): Checkin interval check for package: unspecified last checkin: 1452695551555 min interval config: 0 actual interval: 42151
,D/WearableService( 1733): callingUid 10006, callindPid: 1733
,D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 4127): propertyValue:false
D/LocationInitializer( 4127): Restart initialization of location
,E/MDM     ( 1733): [144] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
W/ContextImpl( 3517): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager(  855): Process com.lge.email (pid 7224) has died
,D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
I/AudioManager( 7495): getMode name:com.lge.qremote
,D/libc-netbsd( 4127): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4127): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
,D/libc-netbsd( 4127): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4127): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4127): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4127): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 4127): Sending checkin request (9795 bytes)
,D/UEI.SmartControl( 7520): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7520): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7520): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7520): --- Selecting new region: 2
,I/ActivityManager(  855): Process com.lge.appbox.client (pid 7279) has died
,I/UEI.SmartControl( 7520): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7520): Platform has CIR...
D/UEI.SmartControl( 7520): NO CIR support, need to check package...
I/UEI.SmartControl( 7520): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7520): QS Service created
E/UEI.SmartControl( 7520): QS start get config
,D/UEI.SmartControl( 7520): Loading JNI Libs...
,D/UEI.SmartControl( 7520):  configuring local db...
D/UEI.SmartControl( 7520):  ---- Has DB8: true
,D/UEI.SmartControl( 7520): QS start statue = true Error code = 0
D/UEI.SmartControl( 7520): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7520): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7520): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7520): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7520): IrrcClient ++ 
D/irrcClient( 7520): getIrrcService ++ 
,D/irrcClient( 7520): getIrrcService -- 
D/irrcClient( 7520): IrrcClient -- 
W/irrc_jni( 7520): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7520): Services init done
I/UEI.SmartControl( 7520): Device manager: loading config....
D/UEI.SmartControl( 7520): QS Service init finished
,D/UEI.SmartControl( 7520): QS Service version name: 0.1.73
D/UEI.SmartControl( 7520): Config is loaded...
D/UEI.SmartControl( 7520): QS Service version code: 1073
D/UEI.SmartControl( 7520): Service requested: Control
D/UEI.SmartControl( 7520): Internal service binding...
D/UEI.SmartControl( 7520): -----IControl: 11
D/UEI.SmartControl( 7520): Caller: com.lge.qremote
,D/UEI.SmartControl( 7520): ------------ IControl registerCallback...
,I/UEI.SmartControl( 7520): Registering callback...
D/UEI.SmartControl( 7520): -----IControl: 19
D/UEI.SmartControl( 7520): Caller: com.lge.qremote
I/UEI.SmartControl( 7520): Registering Services Ready callback...
I/UEI.SmartControl( 7520): Notify client services are ready...
D/UEI.SmartControl( 7520): -----IControl: 8
D/UEI.SmartControl( 7520): Caller: com.lge.qremote
I/AudioManager( 7495): getMode name:com.lge.qremote
,D/UEI.SmartControl( 7520):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 7520): Notify AllClients services are ready: 0
I/AudioManager( 7495): getMode name:com.lge.qremote
,I/AudioManager( 7495): getMode name:com.lge.qremote
,I/CheckinRequestBuilder( 4127): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4127): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinRequestBuilder( 4127): Classify the device as Phone.
,I/art     (  855): Explicit concurrent mark sweep GC freed 16592(770KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.100ms total 151.800ms
,I/CheckinTask( 4127): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4127): Checking schedule, now: 1452695594807 next: 1453222843799
I/CheckinService( 4127): active receiver: disabled
,V/NetworkPolicy(  855): [LG_RESTRICTED] checkMobilePolicy_type()
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  280): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out(  855): propertyValue:false
,I/CheckinService( 4127): Checking schedule, now: 1452695594844 next: 1453222843799
I/CheckinService( 4127): active receiver: disabled
D/CheckinService( 4127): Recording last checkin time for package unspecified as 1452695594853
,V/SetupWizard( 7302): Connected to Gservices successfully
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 15:33:15.673 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/libc-netbsd(  855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/AlarmManagerService(  855): Setting time of day to sec=1452695596
,W/AlarmManagerService(  855): Unable to set rtc to 1452695596: Invalid argument
I/[SystemUI]Clock( 1375): onReceive = android.intent.action.TIME_SET
,I/LgeClockWidgetControlView( 1375): time changed, timezoneChanged : false
,D/WeatherService( 2632): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 15:33:16
,I/ActivityManager(  855): Start proc com.lge.email for broadcast com.lge.email/.receiver.UpdateScheduleReceiver: pid=7578 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,D/WeatherService( 2632): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 2632): 2 : This is isUpdating : false
D/WeatherService( 2632): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2632): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2632): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2632): 2 : Fixed theme : optimus
W/ActivityManager(  855): getTasks: caller 10024 is using old GET_TASKS but privileged; allowing
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
D/WeatherReflect( 2632): 2 : Map key string is -2
,D/lim     ( 2632): 2 : time = 15:33
I/WeatherReflect( 2632): Model Name : LG-D722
D/WeatherTheme( 2632): 2 : exactly same view!
D/WeatherTheme( 2632): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
D/WeatherService( 2632): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 15:33:16
I/InputReader(  855): Reconfiguring input devices.  changes=0x00000010
,I/QCNEJ   ( 1840): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[SystemUI]QPairHandler( 1375): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[SystemUI]QSlideListController( 1375): onReceive = android.intent.action.PACKAGE_CHANGED
,W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
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
,W/ResourcesManager( 7578): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7578): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7578): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[LGHome]LGDateChangeReceiver( 1880): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=13 currentDate=-1 dayofweek=4 currentDayOfWeek=-1
,I/[LGHome]LGCalendarIcon( 1880): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 13
,I/[LGHome]LGCalendarIcon( 1880): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 13
,I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/art     ( 1786): Background sticky concurrent mark sweep GC freed 84664(4MB) AllocSpace objects, 0(0B) LOS objects, 35% free, 9MB/14MB, paused 2.857ms total 107.301ms
,I/ActivityManager(  855): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7613 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/LGEmail ( 7578): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/administrator(  855): Handling package changes for user 0
D/LGEmail ( 7578): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,W/ResourcesManager( 7341): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7341): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/NotificationManager( 7341): com.google.android.talk: cancel(8) by com.google.android.talk
,I/AppUp4:AppBoxCP( 7613): onCreate
,W/AppUp4:DB( 7613):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7613):  setFingerPrint start
,I/AppUp4:DB( 7613):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7613):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7613):  SDK version = 0
I/AppUp4:DB( 7613):  beforefinger == newfinger no write in DB
V/JNIHelp ( 7341): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/AppUp4:AppBoxApplication( 7613): AppBoxApplication onCreate()
,I/AppUp4:CustModeStarterReceiver( 7613): onReceive
I/AppUp4:CustModeStarterReceiver( 7613): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 7613): Context : android.app.ReceiverRestrictedContext@2ae32a5e
D/AppUp4:CustFacade( 7613): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7613): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7613): begin check event
I/AppUp4:CustModeStarterReceiver( 7613): Event For Nothing, skip.
,I/ActivityManager(  855): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7638 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/System  ( 7341): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7341): Installed default security provider GmsCore_OpenSSL
I/NotificationService(  855): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  855): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  855): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/ActivityManager(  855): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=7656 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
I/BackupManagerService(  855): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/art     (  305): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 312us total 22.996ms
,I/ActivityManager(  855): Killing 7256:com.lge.lgdmsclient/1000 (adj 15): empty #11
,I/art     (  305): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 303us total 21.372ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 20.691ms
,W/libprocessgroup(  855): failed to open /acct/uid_1000/pid_7256/cgroup.procs: No such file or directory
,D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
W/ResourcesManager(  855): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/BackupManagerService(  855): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/ResourcesManager( 7638): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7638): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
V/BackupManagerService(  855): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@170ac749
W/ResourcesManager( 7638): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,D/ALBootInit( 7656): ====action==>android.intent.action.TIME_SET
,D/ALBootInit( 7656): Alarm ALBootInit: TIME_SET
D/Alarms  ( 7656): [setNextAlert] start
D/Alarms  ( 7656): [setNextAlert] (1)
,D/Alarms  ( 7656):  minTime  = 0
,D/Alarms  ( 7656):  -- OK multi -- 0
E/jeny.kim( 7656): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 7656): [setNextAlert]setNextAlert temp_AlarmLinkText + 
W/ResourceType(  855): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  855): Process com.google.android.apps.magazines (pid 7372) has died
,I/AppConfig( 7638): Total System Memory = 906309632
I/GalleryUtils( 7638): Application Heap = 96 MB
I/AppConfig( 7638): App Tier : NOT_DEF
,I/CommonUtil( 7656): BUILD Operator: OPEN
D/Alarms  ( 7656): broadcastToWidgetProvider : false
D/Alarms  ( 7656): Enter formatDayAndTime(final Context context, long timeInMiliSec)
D/SystemHelper( 7638): region [EU], country [EU], operator [OPEN], sub-operator []
,I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/SettingsProvider(  855): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
I/DigitalAppWidgetProvider( 7656): onReceive: android.intent.action.TIME_SET
,V/DigitalAppWidgetProvider( 7656): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3b38e6a
V/DigitalAppWidgetProvider( 7656): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3b38e6a
,D/QuickCoverProvider( 7656): onReceiver
I/GCoreNlp( 1733): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ActivityManager(  855): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=7683 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  855): Process com.android.chrome (pid 7440) has died
,I/ActivityManager(  855): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7700 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ResourcesManager( 7683): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7700): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7700): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7700): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7700): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7700): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,D/CalendarApplication( 7683): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 7683): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 7683): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@31e9a799, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@2ae32a5e, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@1c55de3f, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@1e01030c, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@3ca42455, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@3b38e6a, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@18d41f5b, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@f4143f8, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@2b4fb0d1, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@b742736, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@e2b5637, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@2242a7a4, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@324d890d, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@17d380c2, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@2e551ed3, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@13d49a10, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@30d6a909, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@38dce70e, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@748d52f, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@1c51473c, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@26b7ccc5, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@2204661a, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@2517954b, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@3d899b28, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@9cd7041, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@17f2c9e6, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@39c83b27, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@37141d4, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@373fcf7d, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@2f119e72, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@26f362c3, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@238aa740, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@3c7ee679, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@26d72fbe, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@51f681f, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@2712f76c, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@33fe7135, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@2dd289ca, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@4dc673b, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@bee1e58, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@31b1ebb1, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@1a777896
,D/LocationProviderProxy(  855): applying state to connected service
D/GeneralPreferenceUtils( 7683): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 7683): [init]
,I/Config  ( 7683): LGCalendar ver.4.40.17
I/Config  ( 7683): start check model
I/Config  ( 7683): start check native_ca
I/Config  ( 7683): Config Operator=OPEN, Country=EU
D/Config  ( 7683): [setDefaultValuesToPref]
D/Config  ( 7683): [parseProfiles]
D/ProfilesParser( 7683): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 7683): [debug_displayParseInfos] profile.operator = null
D/Config  ( 7683): [updateProfiletoCountryInfo]
D/GeneralPreference( 7683): [checkAndMigrateOldPreference]
E/AgendaWidgetManager( 7683): [updateWidgets] 
,I/InitNotificationRingtoneService( 7683): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 7683): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
I/AlertUtils( 7683): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 7683): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 7683): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,I/AlertUtils( 7683): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 7683): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 7683): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,I/AlertUtils( 7683): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 7683): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 7683): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 7683): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 7683): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 7683): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 7683): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 7683): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 7683): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,I/AlertUtils( 7683): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 7683): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 7683): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 7683): End InitializeAlertRingtoneService.onHandleIntent
,I/SystemConfig( 7700): BUILD Country: EU
I/SystemConfig( 7700): BUILD Operator: OPEN
W/HolidayIntentService( 7683): onHandleIntent
,D/MonthWidgetProvider( 7683): [onReceive]
D/HolidayDataLoader( 7683): readJsonAsset : holiday.json
D/CalendarWidgetProvider( 7683): [onReceive]
D/CalendarWidgetProvider( 7683): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 7683): [onUpdateAndInitCalendarTime]
D/WeekWidgetProvider( 7683): [onReceive]
D/CalendarWidgetProvider( 7683): [onReceive]
D/CalendarWidgetProvider( 7683): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 7683): [onUpdateAndInitCalendarTime]
D/WeatherAncestor( 2632): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 15:33:18
,D/UpdateThreadPoolManager( 2632): 2 : This is isUpdating : false
D/Weather_cast( 2632): 2 : set auto-update time : 1/13 18:33
D/WeatherAncestor( 2632): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 15:33:18
D/WeatherService( 2632): 2 : onStartCommand, intent!=null, action: android.intent.action.TIME_SET
I/ActivityManager(  855): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7730 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
E/HolidayIntentService( 7683): onHandleIntent:holiday data empty
,W/ProcessCpuTracker(  855): Skipping unknown process pid 7459
,I/ActivityManager(  855): Process com.google.android.apps.plus (pid 7459) has died
,W/ActivityManager(  855): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2632): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2632): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2632): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/ActivityManager(  855): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7749 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  855): Killing 7324:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  855): failed to open /acct/uid_10051/pid_7324/cgroup.procs: No such file or directory
I/SystemConfig( 7700): pm.hasSystemFeature(com.lge.ims.rcs) = false
,I/SystemConfig( 7700): existFile = false
I/SystemConfig( 7700): canReadFile = false
I/SystemConfig( 7700): systemFeature RCS result false
D/SystemConfig( 7700): refreshRcsSupport() :false
,D/TimeService( 7730): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1452695598379
D/        ( 7730): TimeServiceNative: User Time to be set is 1452695598379
D/QC-time-services( 7730): Lib:time_genoff_operation: pargs->base = 2
,D/QC-time-services( 7730): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 7730): Lib:time_genoff_operation: pargs->ts_val = 1452695598379
D/QC-time-services( 7730): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  319): Daemon: Connection accepted:time_genoff
D/QC-time-services(  319): Daemon:Received base = 2, unit = 1, operation = 0,value = 1452695598379
D/QC-time-services(  319): Daemon:genoff_opr: Base = 2, val = 1452695598379, operation = 0
D/QC-time-services(  319): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS4/26/70 18:34:54
D/QC-time-services(  319): Daemon:Value read from RTC seconds = 12594894000
D/QC-time-services(  319): Daemon:new time 1452695598379 
D/QC-time-services(  319): Daemon: delta 1440100704379 genoff 1440100704379 
D/QC-time-services(  319): Daemon:genoff_persistent_update: Writing genoff = 1440100704379 to memory
D/QC-time-services(  319): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  319): Daemon:time_persistent_memory_opr:Genoff write operation 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/LockScreenSettings( 7749): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
D/QC-time-services(  319): Updating the TOD offset
D/QC-time-services(  319): Daemon:genoff_persistent_update: Writing genoff = 1440100704379 to memory
D/QC-time-services(  319): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  319): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  319): Daemon:Update to modem bit set
,D/QC-time-services(  319): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  319): Daemon: Base = 2, Value being sent to MODEM = 1124135904379
E/QC-time-services( 7730): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
I/ActivityManager(  855): Killing 7520:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
E/QC-time-services(  319): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  319): Daemon: Time-services: Waiting to acceptconnection
W/System.err( 7495): android.os.DeadObjectException
,W/System.err( 7495): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7495): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7495): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7495): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7495): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7495): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7495): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7495): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7495): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7495): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7495): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7495): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7495): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7495): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7495): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7495): android.os.DeadObjectException
W/System.err( 7495): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7495): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7495): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7495): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7495): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7495): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7495): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7495): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7495): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7495): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7495): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7495): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7495): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7495): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7495): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  855): failed to open /acct/uid_10089/pid_7520/cgroup.procs: No such file or directory
W/ActivityManager(  855): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,I/ActivityManager(  855): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7768 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/LockScreenSettings( 7749): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7749): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7749): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7749): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7749): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  855): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7785 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  855): Killing 7495:com.lge.qremote/u0a106 (adj 15): empty #11
,W/libprocessgroup(  855): failed to open /acct/uid_10106/pid_7495/cgroup.procs: No such file or directory
I/CheckinService( 4127): Checkin interval check for package: unspecified last checkin: 1452695594853 min interval config: 0 actual interval: 3874
,I/ActivityManager(  855): Killing 7302:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/ResourcesManager( 7785): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 7768): Quickset Services start...
I/UEI.SmartControl( 7768): Manufacture = LGE
D/UEI.SmartControl( 7768): File observer start...
E/UEI.SmartControl( 7768): IR Port is disabled: false
D/UEI.SmartControl( 7768): Starting file observer...
D/UEI.SmartControl( 7768): Extracting JNI libs...
D/UEI.SmartControl( 7768): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7768): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7768): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7768): --- Extracting JNI libs: libqs_armeabi-v7a.zip
W/libprocessgroup(  855): failed to open /acct/uid_10038/pid_7302/cgroup.procs: No such file or directory
I/UEI.SmartControl( 7768): --- Selecting new region: 2
I/UEI.SmartControl( 7768): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7768): Platform has CIR...
D/UEI.SmartControl( 7768): NO CIR support, need to check package...
I/UEI.SmartControl( 7768): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7768): QS Service created
E/UEI.SmartControl( 7768): QS start get config
,I/ActivityManager(  855): Killing 7578:com.lge.email/u0a21 (adj 15): empty #11
,D/UEI.SmartControl( 7768): Loading JNI Libs...
,D/UEI.SmartControl( 7768):  configuring local db...
W/libprocessgroup(  855): failed to open /acct/uid_10021/pid_7578/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 1945): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  855): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7815 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1945): UpdateCorporaTask done [took 66 ms] updated apps [took 66 ms] 
,D/UEI.SmartControl( 7768):  ---- Has DB8: true
,D/UEI.SmartControl( 7768): QS start statue = true Error code = 0
,D/UEI.SmartControl( 7768): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7768): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 7768): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7768): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7768): IrrcClient ++ 
D/irrcClient( 7768): getIrrcService ++ 
D/irrcClient( 7768): getIrrcService -- 
D/irrcClient( 7768): IrrcClient -- 
W/irrc_jni( 7768): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 7768): Services init done
I/UEI.SmartControl( 7768): Device manager: loading config....
,D/UEI.SmartControl( 7768): QS Service init finished
,D/UEI.SmartControl( 7768): QS Service version name: 0.1.73
D/UEI.SmartControl( 7768): QS Service version code: 1073
D/UEI.SmartControl( 7768): Config is loaded...
D/UEI.SmartControl( 7768): Service requested: Control
I/art     (  855): Explicit concurrent mark sweep GC freed 27411(1417KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.485ms total 152.050ms
I/ActivityManager(  855): Killing 7613:com.lge.appbox.client/u0a11 (adj 15): empty #11
,D/UEI.SmartControl( 7768):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7768): Notify AllClients services are ready: 0
W/libprocessgroup(  855): failed to open /acct/uid_10011/pid_7613/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 7768): Request IControl service: devices are loaded...
D/UEI.SmartControl( 7768): Service.onUnbind: IControl
D/UEI.SmartControl( 7768): Service.onDestroy
D/UEI.SmartControl( 7768): Shutdown IRRCPlayer... 
W/irrc_jni( 7768): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 7768): ~IrrcClient ++ 
,D/irrcClient( 7768): ~IrrcClient -- 
W/irrc_jni( 7768): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 7768): Blaster closed
D/UEI.SmartControl( 7768): Blaster closed
D/UEI.SmartControl( 7768): Shut down QS...
D/UEI.SmartControl( 7768): Stopped file observer...
I/UEI.SmartControl( 7768): QS lib stop result = true
D/UEI.SmartControl( 7768): QS shutdown complete
D/UEI.SmartControl( 7768): QS Service created
,E/UEI.SmartControl( 7768): QS start get config
D/UEI.SmartControl( 7768):  configuring local db...
,D/Finsky  ( 7815): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/UEI.SmartControl( 7768):  ---- Has DB8: true
,D/UEI.SmartControl( 7768): QS start statue = true Error code = 0
D/UEI.SmartControl( 7768): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7768): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7768): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7768): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7768): IrrcClient ++ 
D/irrcClient( 7768): getIrrcService ++ 
D/irrcClient( 7768): getIrrcService -- 
D/irrcClient( 7768): IrrcClient -- 
W/irrc_jni( 7768): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 7768): Services init done
I/UEI.SmartControl( 7768): Device manager: loading config....
D/UEI.SmartControl( 7768): QS Service init finished
D/UEI.SmartControl( 7768): QS Service version name: 0.1.73
D/UEI.SmartControl( 7768): QS Service version code: 1073
D/UEI.SmartControl( 7768): Service requested: Control
D/UEI.SmartControl( 7768): Config is loaded...
D/UEI.SmartControl( 7768):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7768): Notify AllClients services are ready: 0
,D/Finsky  ( 7815): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 7815): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7815): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/UEI.SmartControl( 7768): Request IControl service: devices are loaded...
I/NotificationManager( 7815): com.android.vending: cancel(-1050172287) by com.android.vending
E/ActivityThread( 7768): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@f4143f8 that was originally bound here
E/ActivityThread( 7768): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@f4143f8 that was originally bound here
E/ActivityThread( 7768): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 7768): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 7768): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 7768): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 7768): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 7768): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 7768): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 7768): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 7768): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 7768): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 7768): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 7768): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 7768): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 7768): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 7768): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 7768): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 7768): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 7768): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/UEI.SmartControl( 7768): Internal service binding...
,V/DownloadManager( 3161): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3161): created cursor android.database.sqlite.SQLiteCursor@37b361ff on behalf of 7815
I/ActivityManager(  855): Killing 7638:com.android.gallery3d/u0a23 (adj 15): empty #11
,D/Ads     ( 7815): Skipping gmscore version check
W/libprocessgroup(  855): failed to open /acct/uid_10023/pid_7638/cgroup.procs: No such file or directory
,D/Finsky  ( 7815): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7815): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7815): [1] Libraries$2.run: Finished loading 1 libraries.
I/DigitalAppWidgetProvider( 7656): onReceive: android.intent.action.ALARM_CHANGED
,D/PackageBroadcastService( 4127): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
D/Finsky  ( 7815): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/WeatherAncestor( 2632): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 15:33:19
I/PackageBroadcastService( 4127): Null package name or gms related package.  Ignoreing.
D/UpdateThreadPoolManager( 2632): 2 : This is isUpdating : false
,D/Weather_cast( 2632): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2632): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 15:33:19
D/WeatherService( 2632): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
I/ActivityManager(  855): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7864 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ActivityManager(  855): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2632): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2632): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2632): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/Icing   ( 4127): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 7864): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  855): Message: 20
,D/BluetoothManagerService(  855): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1fd6509:true
D/BluetoothAdapterService(255935480)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@38dce70e
D/BluetoothAdapterService(255935480)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@38dce70e
V/LGMDMManager( 7864): Create singleton instance
,I/AudioManager( 7864): getMode name:com.lge.qremote
,D/UEI.SmartControl( 7768): -----IControl: 11
D/UEI.SmartControl( 7768): File observer start...
E/UEI.SmartControl( 7768): IR Port is disabled: false
D/UEI.SmartControl( 7768): Starting file observer...
D/UEI.SmartControl( 7768): Caller: com.lge.qremote
D/UEI.SmartControl( 7768): ------------ IControl registerCallback...
I/UEI.SmartControl( 7768): Registering callback...
D/UEI.SmartControl( 7768): -----IControl: 19
D/UEI.SmartControl( 7768): Caller: com.lge.qremote
I/UEI.SmartControl( 7768): Registering Services Ready callback...
I/UEI.SmartControl( 7768): Notify client services are ready...
,D/UEI.SmartControl( 7768): -----IControl: 8
D/UEI.SmartControl( 7768): Caller: com.lge.qremote
I/AudioManager( 7864): getMode name:com.lge.qremote
I/ActivityManager(  855): Killing 7700:com.android.contacts/u0a18 (adj 15): empty #11
,W/libprocessgroup(  855): failed to open /acct/uid_10018/pid_7700/cgroup.procs: No such file or directory
,I/AudioManager( 7864): getMode name:com.lge.qremote
I/AudioManager( 7864): getMode name:com.lge.qremote
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
D/charger_monitor(  463): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  855): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
I/Icing   ( 4127): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4127): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  855): Killing 7683:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  855): failed to open /acct/uid_10013/pid_7683/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  855): Killing 7341:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  855): failed to open /acct/uid_10061/pid_7341/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,E/UEI.SmartControl( 7768): file observer is disposed!
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/UEI.SmartControl( 7768): Internal timer expired: 2
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  855): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  855): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  855): tsOffsetIs: Apps: 134894187661; DSPS: 4518714; Offset : -3009505845
,I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 15:33:30.712 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/AlarmManager(  855): ELAPSED_WAKEUP set : Alarm{7d5add4 type 2 when 138281 com.google.android.gms} when 138281
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1733): Vacuum at: now=1452695611704 tag=VacuumService
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 15:33:33.737 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  855): ALS enabled for SRE
D/PowerManagerServiceEx(  855): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (29582 ms ago)
,D/qdlights(  855): set_light_backlight: 253
,D/qdlights(  855): set_light_backlight: 250
D/qdlights(  855): set_light_backlight: 246
,D/qdlights(  855): set_light_backlight: 243
,D/qdlights(  855): set_light_backlight: 240
,D/qdlights(  855): set_light_backlight: 236
,D/qdlights(  855): set_light_backlight: 233
,D/qdlights(  855): set_light_backlight: 230
,D/qdlights(  855): set_light_backlight: 226
,D/qdlights(  855): set_light_backlight: 223
,D/qdlights(  855): set_light_backlight: 220
,D/qdlights(  855): set_light_backlight: 216
,D/qdlights(  855): set_light_backlight: 213
,D/qdlights(  855): set_light_backlight: 210
,D/qdlights(  855): set_light_backlight: 206
,D/qdlights(  855): set_light_backlight: 203
,D/qdlights(  855): set_light_backlight: 200
,D/qdlights(  855): set_light_backlight: 196
,D/qdlights(  855): set_light_backlight: 193
,D/qdlights(  855): set_light_backlight: 190
,D/qdlights(  855): set_light_backlight: 186
,D/qdlights(  855): set_light_backlight: 183
,D/qdlights(  855): set_light_backlight: 180
,D/qdlights(  855): set_light_backlight: 176
,D/qdlights(  855): set_light_backlight: 173
,D/qdlights(  855): set_light_backlight: 170
,D/qdlights(  855): set_light_backlight: 166
,D/qdlights(  855): set_light_backlight: 163
,D/qdlights(  855): set_light_backlight: 160
,D/qdlights(  855): set_light_backlight: 156
,D/qdlights(  855): set_light_backlight: 153
,D/qdlights(  855): set_light_backlight: 150
,D/qdlights(  855): set_light_backlight: 146
,D/qdlights(  855): set_light_backlight: 143
,D/qdlights(  855): set_light_backlight: 140
,D/qdlights(  855): set_light_backlight: 136
,D/qdlights(  855): set_light_backlight: 133
,D/qdlights(  855): set_light_backlight: 130
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/qdlights(  855): set_light_backlight: 126
,D/qdlights(  855): set_light_backlight: 123
,D/qdlights(  855): set_light_backlight: 120
,D/qdlights(  855): set_light_backlight: 116
,D/qdlights(  855): set_light_backlight: 113
,D/qdlights(  855): set_light_backlight: 110
,D/qdlights(  855): set_light_backlight: 106
,D/qdlights(  855): set_light_backlight: 103
,D/qdlights(  855): set_light_backlight: 100
,D/qdlights(  855): set_light_backlight: 96
,D/qdlights(  855): set_light_backlight: 93
,D/qdlights(  855): set_light_backlight: 90
,D/qdlights(  855): set_light_backlight: 86
,D/qdlights(  855): set_light_backlight: 83
,D/qdlights(  855): set_light_backlight: 80
,D/qdlights(  855): set_light_backlight: 76
,D/qdlights(  855): set_light_backlight: 73
,D/qdlights(  855): set_light_backlight: 70
,D/qdlights(  855): set_light_backlight: 66
,D/qdlights(  855): set_light_backlight: 63
,D/qdlights(  855): set_light_backlight: 60
,D/qdlights(  855): set_light_backlight: 56
,D/qdlights(  855): set_light_backlight: 53
,D/qdlights(  855): set_light_backlight: 50
,D/qdlights(  855): set_light_backlight: 46
,D/qdlights(  855): set_light_backlight: 43
,D/qdlights(  855): set_light_backlight: 40
,D/qdlights(  855): set_light_backlight: 36
,D/qdlights(  855): set_light_backlight: 33
,D/qdlights(  855): set_light_backlight: 30
,D/qdlights(  855): set_light_backlight: 26
,D/qdlights(  855): set_light_backlight: 23
,D/qdlights(  855): set_light_backlight: 20
,D/qdlights(  855): set_light_backlight: 16
,D/qdlights(  855): set_light_backlight: 13
,D/qdlights(  855): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 15:33:45.799 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  855): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  855): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  855): tsOffsetIs: Apps: 154894906769; DSPS: 5174097; Offset : -3009488667
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 15:33:48.822 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  855): ALS enabled for SRE
D/PowerManagerServiceEx(  855): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (36572 ms ago)
I/PowerManagerService(  855): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  855): ALS enabled for SRE
D/PowerManagerServiceEx(  855): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (36590 ms ago)
,W/ContextImpl(  855): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  855): Sleeping (uid 1000)...
D/LPWGController(  855): [updateScreenState] screen on = false
,D/LPWGController(  855): disable proximity sensor
D/LPWGController(  855): enable proximity sensor
I/SensorManager(  855): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@76bed35] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  855): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  855): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  855): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  855): activate: handle is 48, enable
,V/sensors_hal_Ctx(  855): activate sensors is 1400000000000
D/sensors_hal_Thresh(  855): enable: handle=48
I/sensors_hal_SAM(  855): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  855): waitForResponse: timeout=1000
V/sensors_hal_SAM(  855): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  855): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  855): enable: Received response: 0
D/PowerManagerServiceEx(  855): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (36652 ms ago)
I/Adreno-EGL(  855): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  855): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  855): Build Date: 03/02/15 Mon
I/Adreno-EGL(  855): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  855): Remote Branch: 
I/Adreno-EGL(  855): Local Patches: 
I/Adreno-EGL(  855): Reconstruct Branch: 
,D/PermissionCache(  247): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (533 us)
,I/Sensors (  424): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  855): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,I/sensors_hal_SAM(  855): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  855): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  855): processInd: handle 48, count=1
V/sensors_hal_Thresh(  855): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  855): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  855): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  855): poll: count: 256
I/sensors_hal_Ctx(  855): poll: released wakelock sensor_ind
D/sensors_hal_Util(  855): waitForResponse: timeout=0
D/LPWGController(  855): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  855): current mode = 1  value = 1 1
I/LPWGController(  855): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  855): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  855): set_light_backlight: 0
,I/SensorManager(  855): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  855): activate: handle is 46, disable
V/sensors_hal_Ctx(  855): activate sensors is 1000000000000
D/sensors_hal_LP2(  855): enable: handle=46
D/sensors_hal_LP2(  855): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  855): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  247): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  247): hwc_blank: Blanking display: 0
I/DisplayManagerService(  855): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  855): Display changed displayId=0
,V/sensors_hal_SAM(  855): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  855): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1750): Display #0 changed.
,D/qdhwcomposer(  247): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  855): Excessive delay in setPowerMode(): 222ms
,I/qdhwcomposer(  247): handle_blank_event: dpy:0 panel power state: 0
,I/QCOM PowerHAL(  855): Got set_interactive hint
D/KeyguardViewMediator( 1375): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1336): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1336): notifyScreenOffLocked
D/SmartCoverViewMediator( 1336): handleNotifyScreenOFF
,D/KeyguardViewMediator( 1375): notifyScreenOffLocked
D/KeyguardViewMediator( 1375): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1375): handleNotifyScreenOff
,D/WifiServerServiceExt(  855): sendKtScanInterval  mRtspPlay : false
,D/ScreenTurnOffBySensor( 1375): unregisterProximitySensor
I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-13 15:33:50.798 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/StatusBarWindowView( 1375): onScreenTurnedOff why = 3
,V/AudioFlinger(  285): setParameters(): io 0, keyvalue screen_state=on, calling pid 855
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/audio_hw_primary(  285): adev_set_parameters: enter: screen_state=on
V/voice   (  285): voice_set_parameters: enter: screen_state=on
,V/compress_voip(  285): voice_extn_compress_voip_set_parameters: enter: screen_state=on
,V/compress_voip(  285): voice_extn_compress_voip_set_parameters: exit
V/voice   (  285): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  285): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  285): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  285): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  285): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  285): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  285): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  285): adev_set_parameters: exit with code(0)
I/WifiServerServiceExt(  855): set CMD_KT_SCAN_INTERVAL
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
D/GpsLocationProvider(  855): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1840): |CORE| sendScreenState: state:true
I/LEDService( 1805): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1805): stopPatternFlashing()
I/Cliptray Service( 1805): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
I/LEDService( 1805): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
D/Cliptray Service( 1805): lockStatus = 0
I/LEDService( 1805): updateLightsLocked : turn off led
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1786): action : android.intent.action.SCREEN_ON
D/LEDHandler( 1805): RESTART MSG
,D/NfcServiceNXP( 1786): mScreenState : 3, mInProvisionMode : false
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
D/Ulp_jni (  855): JNI:system_update. Event-0
,I/Sensors (  424): sns_pwr.c(301):releasing wakelock
,D/SplitWindow(  855): check instance of lgWin Window{3b66ca58 u0 SearchPanel}
,D/InputDispatcher(  855): Window went away: Window{29b69675 u0 SearchPanel}
,I/[SystemUI]Clock( 1375): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1375): time changed, timezoneChanged : false
,I/art     ( 1733): Explicit concurrent mark sweep GC freed 38982(2MB) AllocSpace objects, 32(512KB) LOS objects, 40% free, 13MB/22MB, paused 1.506ms total 117.722ms
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
V/PhoneApp( 1750): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2632): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 15:33:51
,D/WeatherService( 2632): 2 : ACTION screen on
D/WeatherService( 2632): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2632): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2632): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 15:33:51
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  855): ACTION_SCREEN_ON
,D/AppCleanupService( 3979): android.intent.action.SCREEN_ON
,V/AudioFlinger(  285): setParameters(): io 0, keyvalue screen_state=off, calling pid 855
D/audio_hw_primary(  285): adev_set_parameters: enter: screen_state=off
V/voice   (  285): voice_set_parameters: enter: screen_state=off
V/compress_voip(  285): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  285): voice_extn_compress_voip_set_parameters: exit
V/voice   (  285): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  285): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  285): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  285): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  285): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  285): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  285): adev_set_parameters: exit with code(0)
D/WifiController(  855): CMD_SCREEN_OFF 
D/WifiController(  855): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  855): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.SCREEN_OFF
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/QCNEJ   ( 1840): |CORE| sendScreenState: state:false
,I/LEDService( 1805): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1805): stopPatternFlashing()
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
I/LEDService( 1805): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1805): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1805): clear
I/Cliptray Service( 1805): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1786): action : android.intent.action.SCREEN_OFF
I/LEDService( 1805): updateLightsLocked : turn on led
E/LEDService( 1805): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1805): Can't handle this request of patternId:0
D/LEDHandler( 1805): RESTART MSG
D/NfcServiceNXP( 1786): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1880): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1750): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2632): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 15:33:51
D/WeatherService( 2632): 2 : ACTION screen off
D/WeatherService( 2632): 2 : TimeTick Receiver Unregister
D/WeatherService( 2632): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 15:33:51
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  855): ACTION_SCREEN_OFF
D/AppCleanupService( 3979): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 3979): AppUsageStatsSaveTask
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
,D/KeyguardViewMediator( 1375): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  855): ELAPSED_WAKEUP set : Alarm{347b27b1 type 2 when 162548 com.android.systemui} when 162548
,D/PhoneUtils( 1750): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1750): getCallState : 0
,D/PhoneUtils( 1750): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1375): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1375): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
,I/[SystemUI]Clock( 1375): called onTimeUpdated()
I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  855): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  855): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  855): tsOffsetIs: Apps: 174895679938; DSPS: 5829483; Offset : -3009509007
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  463): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  855): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/PowerManagerServiceEx(  855): acquireWakeLockInternal: lock=40764566, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=855
,V/AlarmManager(  855): ELAPSED_WAKEUP set : Alarm{3041d817 type 2 when 188771 com.google.android.gms} when 188771
D/PowerManagerServiceEx(  855): releaseWakeLockInternal: lock=40764566 [*alarm*], flags=0x0
,I/PhenotypeConfigurator( 1733): Scheduling Phenotype for one-off execution 60 seconds from now (1452695662241)
,D/GetConfigurationSnapshotOperation( 1733): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1733): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1733): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  855): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
,I/System.out( 1733): propertyValue:false
V/AlarmManager(  855): ELAPSED_WAKEUP set : Alarm{1dd1ff9c type 2 when 189413 android} when 189413
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LocationManagerService(  855): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  855): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  855): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  855): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LocationManagerService(  855): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  855): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  855): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  855): tsOffsetIs: Apps: 194896463367; DSPS: 6484868; Offset : -3009488597
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  855): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  855): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  855): tsOffsetIs: Apps: 214897306381; DSPS: 7140256; Offset : -3009499944
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
,I/[SystemUI]Clock( 1375): called onTimeUpdated()
I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  855): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  855): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  855): tsOffsetIs: Apps: 234897982519; DSPS: 7795638; Offset : -3009495375
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  463): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  855): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  855): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  855): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  855): tsOffsetIs: Apps: 254898693813; DSPS: 8451022; Offset : -3009515930
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  855): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  855): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  855): tsOffsetIs: Apps: 274899376201; DSPS: 9106404; Offset : -3009505528
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  463): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  463): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  855): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  855): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  855): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  855): tsOffsetIs: Apps: 294900709371; DSPS: 9761807; Offset : -3009484509
,D/charger_monitor(  463): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  855): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  463): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1805): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1805): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1805): Battery Level Remaining: 100%
D/LEDHandler( 1805): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  855): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  855): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  855): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  855): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  855): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  855): tsOffsetIs: Apps: 314901476447; DSPS: 10417193; Offset : -3009511073
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/jxcore-log( 6188): --= Surplus to requirements =--
I/jxcore-log( 6188): 
I/jxcore-log( 6188): ****TEST TOOK:  ms ****
I/jxcore-log( 6188): 
I/jxcore-log( 6188): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6188): 
,D/AndroidRuntime( 8009): 
D/AndroidRuntime( 8009): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8009): CheckJNI is OFF
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/AndroidRuntime( 8009): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  855): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
,I/ActivityManager(  855): Killing 6188:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  855): WIN DEATH: Window{b3625fb u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/PackageSettings(  855): Skipping PackageSetting{5c268f9 com.example.hello/10317} due to missing metadata
D/InputDispatcher(  855): Focus left window: Window{b3625fb u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  855): Window went away: Window{b3625fb u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  855):   Force finishing activity ActivityRecord{a737abe u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  855): Display changed displayId=0
D/DSDPConnection( 1750): Display #0 changed.
,W/ActivityManager(  855): Spurious death for ProcessRecord{2084a634 6188:com.test.thalitest/u0a316}, curProc for 6188: null
,I/ActivityManager(  855): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  855):   Force finishing activity ActivityRecord{a737abe u0 com.test.thalitest/.MainActivity t222 f}
W/ActivityManager(  855): Duplicate finish request for ActivityRecord{a737abe u0 com.test.thalitest/.MainActivity t222 f}
,I/art     ( 4127): Explicit concurrent mark sweep GC freed 4006(213KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 14MB/18MB, paused 787us total 89.956ms
I/art     ( 1945): Explicit concurrent mark sweep GC freed 9653(657KB) AllocSpace objects, 4(95KB) LOS objects, 40% free, 12MB/20MB, paused 1.504ms total 95.363ms
D/KeyguardModel( 1375): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/QCNEJ   ( 1840): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,W/System.err( 3517): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3517): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3517): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3517): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3517): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3517): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3517): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3517): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3517): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3517): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3517): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3517): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/GeofencerStateMachine( 1733): Ignoring removeGeofence because network location is disabled.
I/InputReader(  855): Reconfiguring input devices.  changes=0x00000010
I/ActivityManager(  855): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8039 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/[LGHome]EVENT( 1880): [Launcher.java:5203:onStart()]onStart
I/[LGHome]EVENT( 1880): [Launcher.java:776:onResume()]onResume
,I/[LGHome]EVENT( 1880): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
,I/[SystemUI]QSlideListController( 1375): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]Launcher.Model( 1880): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/[LGHome]LGActivityUtil( 1880): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/KeyguardModel( 1375): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1375): createShortcutInfo...
I/[LGHome]EVENT( 1880): [Launcher.java:929:onResume()]onResume end
I/Activity( 1880): Activity.onPostResume() called 
D/KeyguardModel( 1375): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1375): createShortcutInfo...
,W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
,W/PackageManager( 1375): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1375): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1375): createShortcutInfo...
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1375): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1375): createShortcutInfo...
I/[LGHome]EVENT( 1880): [Launcher.java:986:onPause()]onPause
,W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1375): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1375): createShortcutInfo...
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1375): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1375): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
W/[LGHome]LGWallpaperInfo( 1880): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1880): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
D/KeyguardModel( 1375): handleShortcutListChanged...
,I/art     (  855): Explicit concurrent mark sweep GC freed 56431(3MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 6.247ms total 288.613ms
I/art     (  855): WaitForGcToComplete blocked for 144.035ms for cause Explicit
I/SystemUI[Framework](  855): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
,W/PhoneWindowManagerEx(  855): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  855): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  855): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  855): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1e4ca447,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  855): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  855): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  855): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  855): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  855): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  855): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1e4ca447,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  855): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher(  855): Focus entered window: Window{13868203 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/KeyguardModel( 1375): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1375): createShortcutInfo...
,D/KeyguardModel( 1375): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1375): createShortcutInfo...
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.android.mms: Resource ID #0x0
,D/KeyguardModel( 1375): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1375): createShortcutInfo...
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1375): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1375): createShortcutInfo...
I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
W/ResourcesManager( 8039): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8039): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8039): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,D/KeyguardModel( 1375): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1375): createShortcutInfo...
I/[LGHome]EVENT( 1880): [Launcher.java:5214:onStop()]onStop
I/[LGHome]EVENT( 1880): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
D/KeyguardModel( 1375): handleShortcutListChanged...
I/PhoneWindow( 1880): [setNavigationBarColor] color=0x 0
,I/LGEmail ( 8039): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 8039): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
D/administrator(  855): Handling package changes for user 0
,I/art     (  855): Explicit concurrent mark sweep GC freed 7234(453KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.357ms total 285.065ms
,I/PackageChangeReceiver( 8039): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/ActivityManager(  855): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8067 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  855): Killing 7730:com.qualcomm.timeservice/1000 (adj 15): empty #11
D/AndroidRuntime( 8009): Shutting down VM
,W/InputMethodManagerService(  855): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  855): Got RemoteException sending setActive(false) notification to pid 6188 uid 10316
,W/libprocessgroup(  855): failed to open /acct/uid_1000/pid_7730/cgroup.procs: No such file or directory
,I/NotificationService(  855): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  855): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  855): Receieved: android.intent.action.PACKAGE_REMOVED
D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
D/PhoneStatusBar( 1375): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/PhoneStatusBar( 1375): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
,D/TaskPersister(  855): removeObsoleteFile: deleting file=222_task.xml
,I/[SystemUI]NavigationThemeResource( 1375): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1375):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1375): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[LGHome]Launcher.Model( 1880): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/AppUp4:AppBoxCP( 8067): onCreate
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
W/AppUp4:DB( 8067):  [AppBoxDatabaseHelper] construct
I/Timeline(  855): Timeline: Activity_windows_visible id: ActivityRecord{15351d56 u0 com.lge.launcher2/.Launcher t221} time:325255
I/AppUp4:DB( 8067):  setFingerPrint start
,I/AppUp4:DB( 8067):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 8067):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 8067):  SDK version = 0
I/AppUp4:DB( 8067):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 8067): AppBoxApplication onCreate()
,W/IInputConnectionWrapper( 1880): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1880): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,E/b       ( 1622): Unable to connect to the editor to retrieve text... will retry later
D/AppUp4:PreloadHelper( 8067): added Exclude : com.test.thalitest
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1880): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1880): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1880): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1880): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  855): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8086 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  855): Killing 7091:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
I/art     (  305): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 305us total 22.643ms
,W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
,W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 21.261ms
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
,W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 21.126ms
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
W/libprocessgroup(  855): failed to open /acct/uid_10006/pid_7091/cgroup.procs: No such file or directory
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,W/ResourcesManager(  855): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1880): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
,I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume

```
