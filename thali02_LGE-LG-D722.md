#### Test 50650278ec2c976_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
D/libc-netbsd( 6063): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6063): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  967): android: cancelAsUser(2) by android
D/sensors_hal_Time(  967): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  967): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  967): tsOffsetIs: Apps: 94956606217; DSPS: 3209306; Offset : -2987246587
I/qtaguid ( 6063): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6063): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6063): untagSocket(41) failed with errno -22
D/Finsky  ( 6063): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  967): android: cancelAsUser(2) by android
--------- beginning of system
I/ActivityManager(  967): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6158 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
D/PowerManagerServiceEx(  967): acquireWakeLockInternal: lock=743967298, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=967
D/WeatherService( 2667): 2 : TimeTick Intent has been received, Time(hour:min:sec) 17:9:0
D/WeatherService( 2667): 2 : TimeTick Intent And Screen On
D/WeatherService( 2667): 2 : SDK version : 21
W/ActivityManager(  967): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2667): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2667): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2667): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2667): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2667): 2 : This is isUpdating : false
D/WeatherService( 2667): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2667): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2667): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2667): 2 : Fixed theme : optimus
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/WeatherReflect( 2667): 2 : Map key string is -2
D/lim     ( 2667): 2 : time = 17:09
I/WeatherReflect( 2667): Model Name : LG-D722
D/WeatherTheme( 2667): 2 : Different view - status_min_formatted : 08 != 09
D/WeatherTheme( 2667): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2667): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2667): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2667): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2667): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2667): currentPackage=com.lge.sizechangable.weather.theme.optimus
W/ResourcesManager( 6158): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6158): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Weather4x2_optimus( 2667): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2667): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2667): forecast size is 0
D/Theme   ( 2667): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2667): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2667): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2667): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2667): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2667): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2667): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2667): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2667): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2667): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2667): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2667): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2667): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2667): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2667): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2667): url is : null
D/Theme   ( 2667): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2667): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2667): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2667): 2 : update view, appWidgetId: 2
D/WeatherService( 2667): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 17:9:0
D/PowerManagerServiceEx(  967): releaseWakeLockInternal: lock=743967298 [*alarm*], flags=0x0
I/MultiDex( 6158): VM with version 2.1.0 has multidex support
I/MultiDex( 6158): install
I/MultiDex( 6158): VM has multidex support, MultiDex support library is disabled.
D/AndroidRuntime( 6150): 
D/AndroidRuntime( 6150): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/qtaguid ( 6063): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6063): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6063): untagSocket(41) failed with errno -22
D/AndroidRuntime( 6150): CheckJNI is OFF
V/JNIHelp ( 6158): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
W/ActivityThread( 6158): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6158): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1f0a24d5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6158): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6158): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6158): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1731): callingUid 10006, callindPid: 1731
E/MDM     ( 1731): [119] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/ChimeraCfgMgr( 6158): Reading stored module config
E/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
D/ChimeraCfgMgr( 6158): Loading module com.google.android.gms.car from APK com.google.android.gms
I/art     ( 6063): CheckpointMarkThreadRoots callback created = 0xb0564710
D/AndroidRuntime( 6150): Calling main entry com.android.commands.am.Am
D/AuthorizationBluetoothService( 1731): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 4279): Restart initialization of location
W/SQLiteConnectionPool( 4279): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/ActivityManager(  967): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-54 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-14 17:09:00.584 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/art     ( 6063): CheckpointMarkThreadRoots callback created = 0xb05646e0
D/NativeLibraryUtils( 6158): Install completed successfully. count=14 extracted=0
D/ActivityManager(  967): setTaskToReturnTo : TaskRecord{3fbff5ff #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  967): setTaskToReturnTo : TaskRecord{3fbff5ff #220 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  967): AppWindowTokenEx init.. 
D/ContextHelper(  967): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/[LGHome]EVENT( 1876): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  967): Focus left window: Window{1c9655e6 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 6150): Shutting down VM
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/SplitWindow(  967): check instance of lgWin Window{33ccbecd u0 Starting com.test.thalitest}
I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ActivityManager(  967): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6204 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/GCoreFlp( 1731): No location to return for getLastLocation()
W/FusedLocationProvider( 1731): location=null
I/[LGHome]EVENT( 1876): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
D/CAR.SERVICE( 6158): Connecting to CarCallService...
I/[LGHome]EVENT( 1876): [Launcher.java:5214:onStop()]onStop
I/HotwordDetector( 1940): Closing mic
I/art     ( 6158): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6158): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/MicrophoneInputStream( 1940): mic_close com.google.android.apps.gsa.speech.audio.u@28c2ef03
V/AudioRecord( 1940): stop()
D/AudioRecord( 1940): AudioRecord->stop()
V/AudioFlinger(  280): RecordHandle::stop()
V/AudioFlinger(  280): RecordThread::stop
V/AudioFlinger(  280): Record stopped OK
V/AudioPolicyManager(  280): stopInput() input 16
V/AudioPolicyService(  280): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  280): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  280): releaseAudioPatch handle 17
V/AudioFlinger::PatchPanel(  280): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  280): ThreadBase::setParameters() routing=0
V/AudioFlinger(  280): sendConfigEvent_l() num events 1 event 2
I/WindowStateAnimator(  967): Starting window displayed
V/AudioFlinger(  280): processConfigEvents_l() remaining events 1
V/AudioFlinger(  280): processConfigEvents_l() DONE thread 0xb3836000
D/audio_hw_primary(  280): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
I/SystemUI[Framework](  967): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
W/PhoneWindowManagerEx(  967): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  967): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  967): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  967): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1bf6bf46,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  967): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1373): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
I/[SystemUI]NavigationThemeResource( 1373): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1373):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1373): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1373): draw background and invalidate : color = 13000000
,D/BarTransitions( 1373): draw background and invalidate : color = 1a191919
D/CAR.SERVICE( 6158): com.google.android.projection.gearhead isn't installed.
V/audio_hw_primary(  280): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  280): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  280): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  280): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  280): disable_audio_route: exit
E/audio_hw_primary(  280): disable_snd_device: enter 144
D/hardware_info(  280): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  280): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  280): stop_input_stream: exit: status(0)
V/audio_hw_primary(  280): in_standby: exit:  status(0)
V/AudioFlinger(  280): RecordThread: loop stopping
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioPolicyManager(  280): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  280): removeAudioPatch() handle 18 af handle 17
V/AudioPolicyService(  280): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  280): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioPolicyService(  280): AudioCommandThread() adding set parameter string hotword_active=0, io 16 ,delay 0
V/AudioPolicyService(  280): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing set parameters string hotword_active=0, io 16
V/AudioFlinger(  280): setParameters(): io 16, keyvalue hotword_active=0, calling pid 280
V/AudioFlinger(  280): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  280): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  280): RecordThread: loop starting
V/AudioFlinger(  280): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  280): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  280): in_set_parameters: exit: status(0)
V/AudioFlinger(  280): processConfigEvents_l() DONE thread 0xb3836000
V/AudioFlinger(  280): RecordThread: loop stopping
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioRecord( 1940): stop()
V/AudioRecord( 1940): stop()
V/AudioRecord( 1940): stop()
V/AudioFlinger(  280): releasing 15 from 1940 for -1
V/AudioFlinger(  280): RecordHandle::stop()
V/AudioFlinger(  280): RecordThread::stop
V/AudioFlinger(  280):  decremented refcount to 0
V/AudioFlinger(  280): purging stale effects
V/AudioPolicyManager(  280): releaseInput() 16
V/AudioPolicyManager(  280): closeInput(16)
V/AudioFlinger(  280): closeInput() 16
V/AudioSystem(  280): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem(  967): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  280): ThreadBase::exit
V/AudioSystem( 1749): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  280): RecordThread: loop starting
V/AudioSystem( 1985): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  280): RecordThread 0xb3836000 exiting
V/AudioSystem( 3202): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1373): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1940): ioConfigChanged() event 4, ioHandle 16
D/audio_hw_primary(  280): adev_close_input_stream: enter:stream_handle(0xb546dd40)
D/audio_hw_primary(  280): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/audio_hw_primary(  280): in_standby: exit:  status(0)
V/AudioPolicyService(  280): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  280): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  280): releaseInput() exit
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioFlinger(  280): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  280): removeClient_l() pid 1940, calling pid 280
D/CAR.TEL.Service( 6158): Creating a new CarCallService.
V/AudioSystem( 2698): ioConfigChanged() event 4, ioHandle 16
I/HotwordRecognitionRnr( 1940): Stopping hotword detection.
I/HotwordRecognitionRnr( 1940): Hotword detection finished
D/CAR.TEL.PhoneAdapter( 6158): Creating a new PhoneAdapter instance
W/ActivityManager(  967): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6158): setListener: com.google.android.gms.car.dn@1d9195a8
W/ActivityManager(  967): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6158): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6158): Starting CarCallService with initial phone null
D/ContextHelper( 6204): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/NotificationManager( 6158): com.google.android.gms: cancel(10436) by com.google.android.gms
I/art     ( 6063): WaitForGcToComplete blocked for 171.556ms for cause HomogeneousSpaceCompact
I/WebViewFactory( 6204): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
D/CAR.SERVICE( 6158): Package validated; name: com.android.vending
I/LibraryLoader( 6204): Time to load native libraries: 10 ms (timestamps 6447-6457)
I/LibraryLoader( 6204): Expected native library version number "",actual native library version number ""
I/NotificationManager( 6063): com.android.vending: cancel(10436) by com.android.vending
V/Finsky  ( 6063): [1] GearheadStateMonitor.access$100: mIsProjecting:false
V/WebViewChromiumFactoryProvider( 6204): Binding Chromium to main looper Looper (main, tid 1) {1e2cba0b}
I/LibraryLoader( 6204): Expected native library version number "",actual native library version number ""
I/chromium( 6204): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6204): Initializing chromium process, singleProcess=true
W/art     ( 6204): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6204): ApplicationContext is null in ApplicationStatus
W/chromium( 6204): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6204): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6204): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6204): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6204): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6204): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6204): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6204): Remote Branch: 
I/Adreno-EGL( 6204): Local Patches: 
I/Adreno-EGL( 6204): Reconstruct Branch: 
V/AudioPolicyService(  280): registerClient() client 0xb57e7660, uid 10316
D/BluetoothManagerService(  967): Message: 20
,D/BluetoothManagerService(  967): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c3d8ef5:true
D/BluetoothAdapterService(501935079)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1c7587f5
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/art     ( 6204): Attempt to remove local handle scope entry from IRT, ignoring
I/NotificationManager(  967): android: cancelAsUser(2) by android
W/AwContents( 6204): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6204): CordovaWebView is running on device made by: LGE
,W/art     ( 6204): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6204): Attempt to remove local handle scope entry from IRT, ignoring
I/Activity( 6204): Activity.onPostResume() called 
,D/OpenGLRenderer( 6204): Render dirty regions requested: true
I/OpenGLRenderer( 6204): Initialized EGL, version 1.4
D/OpenGLRenderer( 6204): Enabling debug mode 0
,D/Atlas   ( 6204): Validating map...
,D/SplitWindow(  967): check instance of lgWin Window{d59bef4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 6204): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/qtaguid ( 6063): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6063): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6063): untagSocket(41) failed with errno -22
,D/InputDispatcher(  967): Focus entered window: Window{d59bef4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/InputMethodManagerService(  967): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  967): Displayed com.test.thalitest/.MainActivity: +1s131ms
I/Timeline(  967): Timeline: Activity_windows_visible id: ActivityRecord{23e99fcc u0 com.test.thalitest/.MainActivity t220} time:97061
,I/Timeline( 6204): Timeline: Activity_idle id: android.os.BinderProxy@bfde456 time:97068
W/BindingManager( 6204): Cannot call determinedVisibility() - never saw a connection for the pid: 6204
,W/ResourcesManager( 6063): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6063): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6063): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/JsMessageQueue( 6204): Set native->JS mode to OnlineEventsBridgeMode
,D/Finsky  ( 6063): [1] WearSupportService.startHygiene: disabled
,D/Finsky  ( 6063): [1] DailyHygiene.access$600: Logging device features
V/AlarmManager(  967): RTC_WAKEUP set : Alarm{1edb39bf type 0 when 1450109342201 com.android.vending} when 1450109342201
,D/DeviceConnectionService( 1731): client connected with version: 8296000
D/Finsky  ( 6063): [749] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  967): android: cancelAsUser(2) by android
,D/libc-netbsd( 6063): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6063): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6063): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6063): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  276): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 6063): propertyValue:false
,W/ProcessCpuTracker(  967): Skipping unknown process pid 6176
W/ProcessCpuTracker(  967): Skipping unknown process pid 6177
,W/ProcessCpuTracker(  967): Skipping unknown process pid 6180
W/ProcessCpuTracker(  967): Skipping unknown process pid 6203
W/ProcessCpuTracker(  967): Skipping unknown process pid 6263
I/ActivityManager(  967): Killing 5352:com.google.android.talk/u0a61 (adj 15): empty #11
,D/jxcore_app_log( 6204): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622792704
,D/JX-Cordova( 6204): jxcore cordova android initializing
W/libprocessgroup(  967): failed to open /acct/uid_10061/pid_5352/cgroup.procs: No such file or directory
,I/art     ( 6204): CheckpointMarkThreadRoots callback created = 0x9ae34430
,I/art     ( 6204): CheckpointMarkThreadRoots callback created = 0x9ae34400
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/art     (  967): Explicit concurrent mark sweep GC freed 40048(1908KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 4.899ms total 206.192ms
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/jxcore-log( 6204): Initializing JXcore engine
,W/jxcore-log( 6204): JXcore engine is ready
W/jxcore-log( 6204): Starting JXcore engine
,W/.test.thalitest( 6204): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8510]" dev="sockfs" ino=8510 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6204): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6204): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6483]" dev="sockfs" ino=6483 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6204): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6204): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/.test.thalitest( 6204): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[28886]" dev="sockfs" ino=28886 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 6204): Platform android
W/jxcore-log( 6204): 
W/jxcore-log( 6204): Process ARCH arm
W/jxcore-log( 6204): 
,I/ActivityManager(  967): Killing 5972:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/libprocessgroup(  967): failed to open /acct/uid_10023/pid_5972/cgroup.procs: No such file or directory
,I/jxcore-log( 6204): JXcore Cordova bridge is ready!
I/jxcore-log( 6204): 
,W/jxcore-log( 6204): JXcore engine is started
I/chromium( 6204): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/Choreographer( 6204): Skipped 188 frames!  The application may be doing too much work on its main thread.
V/AlarmManager(  967): RTC_WAKEUP set : Alarm{1763e242 type 0 when 1450109345969 com.google.android.googlequicksearchbox} when 1450109345969
,D/CAR.SERVICE( 6158): mConnectedToCar = false, abort
,E/ActivityThread( 6158): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1fb1c490 that was originally bound here
E/ActivityThread( 6158): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1fb1c490 that was originally bound here
E/ActivityThread( 6158): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6158): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6158): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6158): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6158): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6158): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6158): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6158): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6158): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6158): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6158): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6158): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6158): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6158): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6158): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6158): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6158): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6158): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6158): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6158): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6158): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6158): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6158): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/ActivityThread( 6158): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@21b0e9cb that was originally bound here
E/ActivityThread( 6158): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@21b0e9cb that was originally bound here
E/ActivityThread( 6158): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6158): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6158): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6158): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6158): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6158): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6158): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6158): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6158): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6158): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6158): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6158): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6158): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6158): 	at android.app.ActivityThread.acce,ss$1900(ActivityThread.java:155)
E/ActivityThread( 6158): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6158): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6158): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6158): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6158): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6158): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6158): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6158): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  967): Unbind failed: could not find connection for android.os.BinderProxy@2583a253
,I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-14 17:09:06.615 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/jxcore-log( 6204): Toggling radios to true
I/jxcore-log( 6204): 
,D/BluetoothAdapter( 6204): enable(): BT is already enabled..!
D/WifiServiceImplEx(  967): setWifiEnabled: true pid=6204, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  967): setWifiEnabled: true pid=6204, uid=10316
,D/WifiServiceImplEx(  967): disconnect pid=6204, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  967): reconnect pid=6204, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 6204): Radios toggled
I/jxcore-log( 6204): 
D/BluetoothManagerService(  967): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 6204): Got Device Bluetooth address: F8:95:C7:87:85:54
I/jxcore-log( 6204): 
,I/jxcore-log( 6204): Perf Test app loaded loaded
I/jxcore-log( 6204): 
I/jxcore-log( 6204): check test folder
I/jxcore-log( 6204): 
I/jxcore-log( 6204): found test : ./testFindPeers.js
I/jxcore-log( 6204): 
,I/wpa_supplicant( 2750): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,I/wpa_supplicant( 2750): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,E/WifiStateMachine(  967): WifiStateMachine: Leaving Connected state
I/jxcore-log( 6204): found test : ./testSendData.js
I/jxcore-log( 6204): 
E/WifiConfigStore(  967): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
,D/WfdsMonitor( 1803): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/LGWifiP2pService(  967): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  967): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  967): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  276): Clearing all IP addresses on wlan0
,I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 7
D/libc-netbsd(  967): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  967): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1731): Read error: ssl=0xaaede600: I/O error during system call, Connection timed out
D/libc-netbsd(  967): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  967): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WifiHS20(  967): hidePasspointNotification off =false
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-14 17:09:07.982 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  967): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
D/libc-netbsd(  967): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/ConnectivityService(  967): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/libc-netbsd(  967): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
V/NativeCrypto( 1731): SSL shutdown failed: ssl=0xaaede600: I/O error during system call, Broken pipe
,D/ConnectivityService(  967): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
,I/ActivityManager(  967): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6323 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
E/WifiStateMachine(  967): Start Disconnecting Watchdog 1
D/WifiHS20(  967): hidePasspointNotification off =false
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGWifiP2pService(  967): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  967): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 2750): wlan0: CTRL-EVENT-SCAN-STARTED 
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  967): ValidatedState{ when=-6ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  967): DefaultState{ when=-13ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  967): Forcing reevaluation
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
,I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-14 17:09:08.075 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/CommandListener(  276): Clearing all IP addresses on wlan0
,D/ConnectivityService(  967): Default network via Wi-Fi disconnect. stop DSQN
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-14 17:09:08.089 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/DSQN    (  967): disableDataServiceNotify
D/WifiHS20(  967): hidePasspointNotification off =false
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/DSQN    (  967): stop dsqn bin
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
,I/chromium( 6204): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/rmt_storage(  273): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
,I/rmt_storage(  273): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  273): wakelock acquired: 1, error no: 42
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
D/WifiNetworkAgent(  967): NetworkAgent: NetworkAgent channel lost
D/ConnectivityService(  967): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/DhcpStateMachine(  967): StoppedState
D/DhcpStateMachine(  967): StoppedState{ when=-76ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  967): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  967): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  967): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  967): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  967): Disconnected - quitting
D/CSLegacyTypeTracker(  967): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  967): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-14 17:09:08.159 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiHS20(  967): hidePasspointNotification off =false
,D/ConnectivityService(  967): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-14 17:09:08.167 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiServerServiceExt(  967): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  967): setSupplicantStateDISCONNECTED
V/NetworkPolicy(  967): [LG_RESTRICTED] !!!isConnected  type  :1
W/QCNEJ   ( 1838): |CORE| No family connected
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  967): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  967): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy(  967): [LG_RESTRICTED] !!!isConnected  type  :1
W/QCNEJ   ( 1838): |CORE| No family connected
I/QCNEJ   ( 1838): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/QCNEJ   ( 1838): |CORE| sendDefaultNwMsg: default = -1
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/Tethering(  967): MasterInitialState.processMessage what=3
,D/Tethering(  967): MasterInitialState.processMessage what=3
D/ConnectivityService(  967): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/WifiServerServiceExt(  967): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  967): setSupplicantStateSCANNING
D/ConnectivityService(  967): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  967): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService(  967): Removing idletimer
D/WIFI    (  967): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  967):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
W/Settings(  967): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/ConnectivityService(  967): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  273): 
I/rmt_storage(  273): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/ActivityManager(  967): Process com.google.android.apps.plus (pid 6034) has died
,D/TelephonyNetworkFactory-1( 1749): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1749):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/ResourcesManager( 6323): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6323): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6323): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6323): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6323): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/IndexDatabaseHelper( 6323): Using schema version: 115
,I/IndexDatabaseHelper( 6323): Index is fine
I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,V/WiFiOffLoadBroadcast( 6323): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6323): MCCMNC not supported: null
I/ActivityManager(  967): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6352 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/PCSuite ( 6352): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6352): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6352): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6323): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6323): MCCMNC not supported: null
I/PCSuite ( 6352): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6352): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6352): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/ActivityManager(  967): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6374 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  967): Killing 5992:com.android.contacts/u0a18 (adj 15): empty #11
W/libprocessgroup(  967): failed to open /acct/uid_10018/pid_5992/cgroup.procs: No such file or directory
,W/ResourcesManager( 6374): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2750): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
I/Babel_SMS( 6374): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6374): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6374): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6374): MmsConfig.loadFromDatabase
D/LocSvc_java(  967): onReceive
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-14 17:09:09.231 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [SCANNING]
,I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-14 17:09:09.236 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
D/WifiServerServiceExt(  967): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  967): setSupplicantStateASSOCIATING
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/wpa_supplicant( 2750): wlan0: Associated with c0:ff:d4:d3:aa:48
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
D/WifiServerServiceExt(  967): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  967): setSupplicantStateASSOCIATED
,E/Babel_SMS( 6374): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6374): MmsConfig.loadFromResources
E/Babel_SMS( 6374): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6374): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-14 17:09:09.271 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt(  967): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  967): setSupplicantStateFOUR_WAY_HANDSHAKE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-14 17:09:09.275 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/wpa_supplicant( 2750): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2750): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiServerServiceExt(  967): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  967): setSupplicantStateGROUP_HANDSHAKE
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 4
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
,I/WifiServiceExtension(  967): setVHTCapabilityType  : false
I/WifiServerServiceExt(  967): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,I/WifiServerServiceExt(  967): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  967): setSecurityType  : 2
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-14 17:09:09.319 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-14 17:09:09.322 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/SensorManager( 6374): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6374): found sensor: LGE Magnetometer Sensor, handle=10
D/ConnectivityService(  967): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/SensorManager( 6374): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6374): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6374): found sensor: LGE Gravity Sensor, handle=29
D/ConnectivityService(  967): Got NetworkAgent Messenger
D/ConnectivityService(  967): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  967): NetworkAgent connected
,D/SensorManager( 6374): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6374): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6374): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6374): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6374): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
D/SensorManager( 6374): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
E/WifiConfigStore(  967): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/SensorManager( 6374): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6374): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6374): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6374): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6374): found sensor: Motion Accel, handle=46
E/WifiConfigStore(  967): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  967): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  967): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  967): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  967): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  276): Setting iface cfg
E/WifiStateMachine(  967): Start Dhcp Watchdog 2
D/DhcpStateMachine(  967): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  967): WaitBeforeStartState
,D/ConnectivityService(  967): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
W/Settings( 6374): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6374): startup - clean
I/art     ( 6374): CheckpointMarkThreadRoots callback created = 0xb042d4b0
,I/art     ( 6374): CheckpointMarkThreadRoots callback created = 0xb042d490
I/Babel   ( 6374): deleted: false for 0
,E/WifiStateMachine(  967): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  967): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  967): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@9d2e590 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  967): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@9d2e590 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  967): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper(  967): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/DhcpStateMachine(  967): DHCP Start wake lock is acquired.
D/CommandListener(  276): Setting iface cfg
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  967): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  967): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  276): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  967): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  967): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  967): setSupplicantStateCOMPLETED
D/WifiServerServiceExt(  967): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  967): setSupplicantStateCOMPLETED
D/ConnectivityService(  967): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,D/LGWifiP2pService(  967): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  967): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  967): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  967): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  967): ignoring duplicate network state non-change
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-14 17:09:09.487 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-14 17:09:09.488 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
D/ConnectivityService(  967): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
D/ConnectivityService(  967): Adding iface wlan0 to network 101
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
E/WifiStateMachine(  967): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/WifiHS20(  967): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-14 17:09:09.506 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,E/ConnectivityService(  967): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  967): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/WifiHS20(  967): [PASSPOINT] passpointNotification: hs20AP list is checked
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  967): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  276): netlink response contains error (File exists)
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-14 17:09:09.516 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/ConnectivityService(  967): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  967): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  967): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  967): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  967): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = true, mWifiLevel = 2
D/libc-netbsd(  967): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  967): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  967): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  967): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  967): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  967): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  967): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  967): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  967):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  967):   checking if request is satisfied: Network,Request [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  967):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  967):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  967):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  967): currentScore = 0, newScore = 20
D/ConnectivityService(  967):    accepting network in place of null
D/ConnectivityService(  967): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1749): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1749):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
E/ConnectivityService(  967): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  967): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  967): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WIFI    (  967): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  967):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  967): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  967): [e] list.add(nai) empty : false size: 1
D/ConnectivityService(  967): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
W/QCNEJ   ( 1838): |CORE| No family connected
I/QCNEJ   ( 1838): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/Tethering(  967): MasterInitialState.processMessage what=3
I/QCNEJ   ( 1838): |CORE| sendDefaultNwMsg: default = 1
D/ConnectivityService(  967): validation of new default Network = false
D/ConnectivityService(  967): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  967): enableDataServiceNotify 
D/DSQN    (  967): start dsqn bin
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  967): [LWD] Start DNSResolver start to wait
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  967): [LWD] wait 500ms before dns check
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = true, mWifiLevel = 2
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
D/ConnectivityService(  967): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
V/NetworkPolicy(  967): [LG_RESTRICTED] checkMobilePolicy_type()
,D/ConnectivityService(  967): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524290
I/DSQN    ( 6416): DSQN samuel.seo ver 141203
E/DSQN    ( 6416): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6416): created command queue thread
I/DSQN    ( 6416): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6416): Interface wlan0 netmask 255.255.255.0 0xc0a80186
V/WiFiOffLoadBroadcast( 6323): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6323): MCCMNC not supported: null
D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
W/AudioCapabilities( 6374): Unsupported mime audio/x-lg-flac
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
W/AudioCapabilities( 6374): Unsupported mime audio/adpcm
W/AudioCapabilities( 6374): Unsupported mime audio/g726
I/PCSuite ( 6352): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6352): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6352): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/AudioCapabilities( 6374): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6374): Unsupported mime audio/wma-voice
V/WiFiOffLoadBroadcast( 6323): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/VideoCapabilities( 6374): Unsupported mime video/mjpg
D/WiFiOffLoadBroadcast( 6323): MCCMNC not supported: null
W/VideoCapabilities( 6374): Unsupported mime video/theora
I/PCSuite ( 6352): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6352): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6352): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6323): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6323): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6323): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6323): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6323): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6323): MCCMNC not supported: null
W/AudioCapabilities( 6374): Unsupported mime audio/evrc
,W/AudioCapabilities( 6374): Unsupported mime audio/qcelp
W/VideoCapabilities( 6374): Unrecognized profile 2130706433 for video/avc
V/WiFiOffLoadBroadcast( 6323): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6323): MCCMNC not supported: null
W/AudioCapabilities( 6374): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6374): Unsupported mime audio/qcelp
W/AudioCapabilities( 6374): Unsupported mime audio/evrc
V/WiFiOffLoadBroadcast( 6323): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/DhcpStateMachine(  967): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper(  967): [bssid] hash key :c0:ff:d4:d3:aa:48
,D/LgDhcpStateMachineHelper(  967): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,D/WiFiOffLoadBroadcast( 6323): MCCMNC not supported: null
W/VideoCapabilities( 6374): Unsupported mime video/mp4v-esdp
I/dhcpcd  ( 6419): version 5.5.6 starting
E/dhcpcd  ( 6419): get_duid: Read-only file system
V/WiFiOffLoadBroadcast( 6323): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6323): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6323): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/VideoCapabilities( 6374): Unsupported profile 4 for video/mp4v-es
D/WiFiOffLoadBroadcast( 6323): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6323): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/VideoCapabilities( 6374): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6374): Unrecognized profile 2130706433 for video/avc
D/WiFiOffLoadBroadcast( 6323): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6323): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/dhcpcd  ( 6419): wlan0: rebinding lease of 192.168.1.134
W/VideoCapabilities( 6374): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6374): Unrecognized profile 2130706433 for video/avc
D/WiFiOffLoadBroadcast( 6323): MCCMNC not supported: null
I/vclib   ( 6374): onServiceConnected
,W/Babel   ( 6374): Attempted to change video mute state without an active call.
V/WiFiOffLoadBroadcast( 6323): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/NotificationManager( 6374): com.google.android.talk: cancel(10436) by com.google.android.talk
D/WiFiOffLoadBroadcast( 6323): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 6323): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6323): MCCMNC not supported: null
I/PCSuite ( 6352): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6352): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6323): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6323): MCCMNC not supported: null
I/PCSuite ( 6352): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6352): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,I/ActivityManager(  967): Killing 6017:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
W/libprocessgroup(  967): failed to open /acct/uid_10069/pid_6017/cgroup.procs: No such file or directory
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  967): [LWD] DNSResolver start dns
,D/libc-netbsd(  967): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  967): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  967): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  967): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  276): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
,I/System.out(  967): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  967): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  967): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  967): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  967): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/DSQN    ( 6416): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6416): restart monitoring
,D/LGDataListener(  276): argv[0]=dsqncommand
D/LGDataListener(  276): argv[1]=wlan0
D/LGDataListener(  276): argv[2]=1
D/LGDataListener(  276): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 6416): dsqn report finish
D/DSQN    (  967): DSQM DsqnNotification wlan0  1
D/DSQN    (  967): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  967): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 14 Dec 2015 16:09:10 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450109350137], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450109350114]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  967): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  967): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  967): Validated
D/ConnectivityService(  967): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  967): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  967):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  967):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  967):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  967): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  967): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WifiDataContinuityService(  967): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
D/ConnectivityService(  967): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  967): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  967): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1749): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1749):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/WifiServerServiceExt(  967): set CMD_CAPTIVE_CHECK_COMPLETED
D/WIFI    (  967): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  967):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/ConnectivityService(  967): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/dhcpcd  ( 6419): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/dhcpcd  ( 6419): wlan0: leased 192.168.1.134 for 86400 seconds
I/Netd    (  276): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  967): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  967): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  967): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  967): identical MTU - not setting
D/Nat464Xlat(  967): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  967): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  967):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  967): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524295
,D/ConnectivityService(  967): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  967): enableDataServiceNotify 
D/DSQN    (  967): start dsqn bin
I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-14 17:09:10.923 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/DSQN    (  967): dsqn is running restart
,I/DSQN    ( 6475): DSQN samuel.seo ver 141203
E/DSQN    ( 6475): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6475): created command queue thread
I/DSQN    ( 6475): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6475): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,D/libc-netbsd(  967): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  967): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  967): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  967): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  967): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  967): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  967): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  967): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  967): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  967): CheckDhcpDirectory [Lease File Count] : 3
,V/LgDhcpStateMachineHelper(  967): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  967): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  967): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  967): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  967): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  967): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  967): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  967): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  967): RunningState
I/NotificationManager( 1940): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,D/ConnectivityService(  967): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/GpsLocationProvider(  967): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  967): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  967): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java(  967): onReceive
D/LocSvc_java(  967): got connectivity action
I/ActivityManager(  967): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6486 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/GpsLocationProvider(  967): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java(  967): broadcast - no network connections
D/LocSvc_java(  967): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  967): Sending msg: 4 arg1:0 arg2:1
D/GpsLocationProvider(  967): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LocSvc_java(  967): onReceive
D/LocSvc_java(  967): got connectivity action
D/LocSvc_java(  967): broadcast - no network connections
D/LocSvc_java(  967): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  967): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  967): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  967): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
,I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,V/AlarmManager(  967): ELAPSED_WAKEUP set : Alarm{fcbdee type 2 when 106455 com.google.android.gms} when 106455
,I/MusicStore( 6486): Database version: 120
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6486): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6486): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6486): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6486): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6486): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6486): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6486): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6486): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3ded8a84: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6486): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6486): GMSCore installation verified
,I/ConfigStore( 6486): Config Database version: 1
,I/MediaRouter( 6486): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6486): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6486): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6486): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  967): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6520 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6486): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6486): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 6520): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6520): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6520): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  967): Killing 6111:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/libprocessgroup(  967): failed to open /acct/uid_10014/pid_6111/cgroup.procs: No such file or directory
,I/NotificationManager( 6486): com.google.android.music: cancel(1061) by com.google.android.music
I/ActivityManager(  967): Process com.android.vending (pid 6063) has died
,I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-14 17:09:12.386 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/LGEmail ( 6520): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6520): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,V/WifiInternetCheck(  967): Single check msg out of sync, ignoring.
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/ConnectivityService(  967): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  967): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  967): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  967): onReceive
D/LocSvc_java(  967): got connectivity action
D/LocSvc_java(  967): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  967): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  967): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
I/NetworkMonitor( 6486): type=WIFI subType= reason=null isConnected=true
,D/eas_req ( 6520): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  967): Process com.google.android.talk (pid 6374) has died
,I/ActivityManager(  967): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6550 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/HubEmail( 6520): JNI_OnLoad()
I/HubEmail( 6520): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6520): registerNatives()
I/HubEmail( 6520): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6520): registerNativeMethods()
I/HubEmail( 6520): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6520): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6520): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/BluetoothAdapterService(501935079)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1c7587f5
,I/jxcore-log( 6204): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 6204): 
D/LGDMClient( 6550): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6550): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6550): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6550): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6550): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6550): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6550): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6550): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  967): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6577 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 316us total 33.386ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 23.650ms
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 20.292ms
,W/ContextImpl( 6550): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6550): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6550): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6550): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6550): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6550): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/AppUp4:AppBoxCP( 6577): onCreate
,W/AppUp4:DB( 6577):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6577):  setFingerPrint start
I/AppUp4:DB( 6577):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6577):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6577):  SDK version = 0
I/AppUp4:DB( 6577):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6577): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6577): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6577): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6577): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6577): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6577): onReceive
I/AppUp4:CustModeStarterReceiver( 6577): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6577): Context : android.app.ReceiverRestrictedContext@293cc0e8
,D/AppUp4:CustFacade( 6577): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6577): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6577): begin check event
I/AppUp4:CustModeStarterReceiver( 6577): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6577): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6577): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6577): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6577): handleAsyncCustNotification do not startCustService
I/ActivityManager(  967): Killing 6158:com.google.android.gms:car/u0a6 (adj 15): empty #11
,W/libprocessgroup(  967): failed to open /acct/uid_10006/pid_6158/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3202): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3202): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3202): networkInfo.isConnected() = false
I/ActivityManager(  967): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6606 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6606): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6606): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6606): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  967): Killing 6323:com.android.settings/1000 (adj 15): empty #11
W/libprocessgroup(  967): failed to open /acct/uid_1000/pid_6323/cgroup.procs: No such file or directory
,I/CheckinService( 4279): Checkin interval check for package: unspecified last checkin: 1450109324244 min interval config: 0 actual interval: 29210
,V/DownloadManager( 3263): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3263): DownloadService onCreate
I/NotificationManager( 3263): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,I/DownloadManager( 3263): in removeSpuriousFiles
V/DownloadManager( 3263): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/PhoneMonitor( 6606): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6606): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 6606): [parse] Load xml
V/DownloadManager( 3263): created cursor android.database.sqlite.SQLiteCursor@1f0a24d5 on behalf of 3263
V/TelephonyAutoProfiling( 6606): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6606): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
I/DownloadManager( 3263): in trimDatabase
V/DownloadManager( 3263): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
V/DownloadManager( 3263): created cursor android.database.sqlite.SQLiteCursor@21f753db on behalf of 3263
I/ActivityManager(  967): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6637 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/CheckinService( 4279): Checking schedule, now: 1450109353506 next: 1450109354192
I/CheckinService( 4279): active receiver: disabled
V/DownloadManager( 3263): DownloadService onStartCommand
V/DownloadManager( 3263): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/PhoneMonitor( 6606): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
V/DownloadManager( 3263): created cursor android.database.sqlite.SQLiteCursor@11553951 on behalf of 3263
,V/DownloadManager( 3263): DownloadService onDestroy
,I/ActivityManager(  967): Killing 5711:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 5154): android.os.DeadObjectException
,W/System.err( 5154): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5154): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5154): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5154): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5154): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5154): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5154): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5154): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5154): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5154): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5154): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5154): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5154): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5154): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5154): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5154): android.os.DeadObjectException
W/System.err( 5154): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5154): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5154): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5154): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5154): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5154): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5154): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5154): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5154): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5154): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5154): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5154): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5154): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5154): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5154): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
D/libc-netbsd(  967): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  967): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  967): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  967): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  276): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
W/libprocessgroup(  967): failed to open /acct/uid_10089/pid_5711/cgroup.procs: No such file or directory
,W/ActivityManager(  967): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
D/WeatherAncestor( 2667): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:9:13
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
,I/System.out(  967): propertyValue:false
D/libc-netbsd(  967): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  967): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  967): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  967): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  276): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out(  967): propertyValue:false
I/DSQN    ( 6475): first global connection report this to start monitoring at DSQM.
,I/DSQN    ( 6475): restart monitoring
D/LGDataListener(  276): argv[0]=dsqncommand
D/LGDataListener(  276): argv[1]=wlan0
D/LGDataListener(  276): argv[2]=1
D/LGDataListener(  276): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  967): DSQM DsqnNotification wlan0  1
D/DSQN    (  967): start to monitor internet connection
I/DSQN    ( 6475): dsqn report finish
I/ActivityManager(  967): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6668 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/UpdateThreadPoolManager( 2667): 2 : This is isUpdating : false
,D/WeatherAncestor( 2667): connectivity changed - connection : true
D/Weather_cast( 2667): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2667): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:9:13
V/WifiInternetCheck(  967): isHttpConnectionAvailable - We got a valid response : 204
D/WeatherService( 2667): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  967): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6685 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  967): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2667): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2667): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2667): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/UEI.SmartControl( 6668): Quickset Services start...
,I/UEI.SmartControl( 6668): Manufacture = LGE
D/UEI.SmartControl( 6668): File observer start...
E/UEI.SmartControl( 6668): IR Port is disabled: false
D/UEI.SmartControl( 6668): Starting file observer...
D/UEI.SmartControl( 6668): Extracting JNI libs...
W/ResourcesManager( 6685): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/UEI.SmartControl( 6668): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 6668): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6668): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6668): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 6668): --- Selecting new region: 2
I/UEI.SmartControl( 6668): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6668): Platform has CIR...
D/UEI.SmartControl( 6668): NO CIR support, need to check package...
I/UEI.SmartControl( 6668): Model: LG-D722 uses JNI
,D/UEI.SmartControl( 6668): QS Service created
I/Babel_SMS( 6685): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6685): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6685): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6685): MmsConfig.loadFromDatabase
E/UEI.SmartControl( 6668): QS start get config
,E/Babel_SMS( 6685): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6685): MmsConfig.loadFromResources
E/Babel_SMS( 6685): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6685): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6685): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6685): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6685): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6685): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6685): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6685): found sensor: LGE Linear Acceleration Sensor, handle=30
,D/SensorManager( 6685): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6685): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6685): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6685): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6685): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6685): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6685): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6685): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6685): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6685): found sensor: Motion Accel, handle=46
D/UEI.SmartControl( 6668): Loading JNI Libs...
,D/UEI.SmartControl( 6668):  configuring local db...
W/Settings( 6685): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6685): startup - clean
I/art     ( 6685): CheckpointMarkThreadRoots callback created = 0xb042d810
,I/art     ( 6685): CheckpointMarkThreadRoots callback created = 0xb042d7f0
,I/Babel   ( 6685): deleted: false for 0
I/ActivityManager(  967): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6721 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 6668):  ---- Has DB8: true
,D/UEI.SmartControl( 6668): QS start statue = true Error code = 0
D/UEI.SmartControl( 6668): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6668): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6668): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6668): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6668): IrrcClient ++ 
,D/irrcClient( 6668): getIrrcService ++ 
D/irrcClient( 6668): getIrrcService -- 
D/irrcClient( 6668): IrrcClient -- 
W/irrc_jni( 6668): IRRCPlayer_nativeInit -- 
W/AudioCapabilities( 6685): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6685): Unsupported mime audio/adpcm
W/AudioCapabilities( 6685): Unsupported mime audio/g726
W/AudioCapabilities( 6685): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6685): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6685): Unsupported mime video/mjpg
W/VideoCapabilities( 6685): Unsupported mime video/theora
,D/UEI.SmartControl( 6668): Services init done
I/UEI.SmartControl( 6668): Device manager: loading config....
D/UEI.SmartControl( 6668): QS Service init finished
,D/UEI.SmartControl( 6668): QS Service version name: 0.1.73
D/UEI.SmartControl( 6668): QS Service version code: 1073
D/UEI.SmartControl( 6668): Service requested: Control
D/UEI.SmartControl( 6668): Config is loaded...
W/AudioCapabilities( 6685): Unsupported mime audio/evrc
,W/AudioCapabilities( 6685): Unsupported mime audio/qcelp
D/UEI.SmartControl( 6668):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6668): Notify AllClients services are ready: 0
W/VideoCapabilities( 6685): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6685): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6685): Unsupported mime audio/qcelp
W/AudioCapabilities( 6685): Unsupported mime audio/evrc
D/UEI.SmartControl( 6668): Request IControl service: devices are loaded...
I/ActivityManager(  967): Killing 6352:com.lge.sync/1000 (adj 15): empty #11
D/UEI.SmartControl( 6668): -----IControl: 11
D/UEI.SmartControl( 6668): Caller: com.lge.qremote
D/UEI.SmartControl( 6668): ------------ IControl registerCallback...
I/UEI.SmartControl( 6668): Registering callback...
D/UEI.SmartControl( 6668): -----IControl: 19
,D/UEI.SmartControl( 6668): Caller: com.lge.qremote
I/UEI.SmartControl( 6668): Registering Services Ready callback...
I/UEI.SmartControl( 6668): Notify client services are ready...
D/UEI.SmartControl( 6668): -----IControl: 8
D/UEI.SmartControl( 6668): Caller: com.lge.qremote
W/VideoCapabilities( 6685): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6685): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6685): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6685): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6685): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6685): Unrecognized profile 2130706433 for video/avc
D/UEI.SmartControl( 6668): Internal service binding...
W/libprocessgroup(  967): failed to open /acct/uid_1000/pid_6352/cgroup.procs: No such file or directory
,I/vclib   ( 6685): onServiceConnected
W/Babel   ( 6685): Attempted to change video mute state without an active call.
D/libc-netbsd( 6685): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6685): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6685): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6685): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  276): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  276): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 6685): propertyValue:false
I/NotificationManager( 6685): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/Babel   ( 6685): connection state changed from UNKNOWN to CONNECTED
I/art     (  967): Explicit concurrent mark sweep GC freed 83609(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 1.888ms total 196.092ms
,I/ActivityManager(  967): Killing 5154:com.lge.qremote/u0a106 (adj 15): empty #11
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6721): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6721): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6721): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/libprocessgroup(  967): failed to open /acct/uid_10106/pid_5154/cgroup.procs: No such file or directory
W/ContextImpl( 6721): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6721): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6721):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6721):   adb logcat -s GAv4
,W/GAv4    ( 6721): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6721): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6721): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 6721): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6721): Time to load native libraries: 2 ms (timestamps 475-477)
I/LibraryLoader( 6721): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6721): Binding Chromium to main looper Looper (main, tid 1) {28deed45}
I/LibraryLoader( 6721): Expected native library version number "",actual native library version number ""
I/chromium( 6721): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6721): Initializing chromium process, singleProcess=true
W/art     ( 6721): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6721): ApplicationContext is null in ApplicationStatus
W/chromium( 6721): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6721): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6721): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6721): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6721): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6721): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6721): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6721): Remote Branch: 
I/Adreno-EGL( 6721): Local Patches: 
I/Adreno-EGL( 6721): Reconstruct Branch: 
V/AudioPolicyService(  280): registerClient() client 0xb57e75a0, uid 10079
W/AudioManagerAndroid( 6721): Requires BLUETOOTH permission
,I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-53 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-14 17:09:15.404 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/NSApplication( 6721): Starting up...
,I/ActivityManager(  967): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6790 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  967): Killing 6486:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  967): failed to open /acct/uid_10081/pid_6486/cgroup.procs: No such file or directory
,I/ActivityManager(  967): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6809 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  967): Killing 6520:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  967): failed to open /acct/uid_10021/pid_6520/cgroup.procs: No such file or directory
,W/ResourcesManager( 6809): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  967): Killing 6550:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  967): failed to open /acct/uid_1000/pid_6550/cgroup.procs: No such file or directory
,I/ActivityManager(  967): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6836 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 6836): Database version: 120
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6836): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
V/AlarmManager(  967): RTC_WAKEUP set : Alarm{c2c341e type 0 when 1450109353290 com.google.android.gms} when 1450109353290
V/AlarmManager(  967): RTC_WAKEUP set : Alarm{13e784ff type 0 when 1450109354192 com.google.android.gms} when 1450109354192
,I/ActivityManager(  967): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6860 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  967): RTC_WAKEUP set : Alarm{205382cc type 0 when 1450109356395 com.android.vending} when 1450109356395
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6836): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6836): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/ResourcesManager( 6836): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6836): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6836): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/Finsky  ( 6860): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/ActivityThread( 6836): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6836): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3ded8a84: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6836): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6836): GMSCore installation verified
,I/ConfigStore( 6836): Config Database version: 1
,D/Finsky  ( 6860): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/MediaRouter( 6836): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,W/Settings( 6860): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6860): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
I/NotificationManager( 6860): com.android.vending: cancel(-1050172287) by com.android.vending
V/MusicLeanback( 6836): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6836): type=WIFI subType= reason=null isConnected=true
,D/Ads     ( 6860): Skipping gmscore version check
,D/Finsky  ( 6860): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6860): [1] Libraries$2.run: Finished loading 1 libraries.
,V/DownloadManager( 3263): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3263): created cursor android.database.sqlite.SQLiteCursor@1b8d52b7 on behalf of 6860
I/NetworkMonitor( 6836): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  967): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6913 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6836): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/Finsky  ( 6860): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/ResourcesManager( 6913): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6913): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6913): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/GoogleURLConnFactory( 6836): Using platform SSLCertificateSocketFactory
,D/Finsky  ( 6860): [835] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,I/LGEmail ( 6913): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 6913): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/Finsky  ( 6860): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/Finsky  ( 6860): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  967): Killing 6606:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/ActivityManager(  967): Killing 6577:com.lge.appbox.client/u0a11 (adj 15): empty #12
,W/libprocessgroup(  967): failed to open /acct/uid_10038/pid_6606/cgroup.procs: No such file or directory
,W/libprocessgroup(  967): failed to open /acct/uid_10011/pid_6577/cgroup.procs: No such file or directory
I/NotificationManager( 6836): com.google.android.music: cancel(1061) by com.google.android.music
,D/eas_req ( 6913): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  967): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6942 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 27.455ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 22.718ms
,I/HubEmail( 6913): JNI_OnLoad()
I/HubEmail( 6913): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6913): registerNatives()
I/HubEmail( 6913): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6913): registerNativeMethods()
I/HubEmail( 6913): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6913): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 23.328ms
V/AlarmManager(  967): RTC_WAKEUP set : Alarm{2fbe5aea type 0 when 1450109357536 com.google.android.googlequicksearchbox} when 1450109357536
I/ActivityManager(  967): Killing 6637:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  967): failed to open /acct/uid_10051/pid_6637/cgroup.procs: No such file or directory
W/Settings( 6913): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 6942): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6942): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6942): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6942): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,D/LGDMClient( 6942): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6942): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6942): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6942): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  967): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6981 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6942): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6942): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6942): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
,D/LGDMClient( 6942): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6942): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6942): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  967): Killing 6668:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/libprocessgroup(  967): failed to open /acct/uid_10089/pid_6668/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 6981): onCreate
W/AppUp4:DB( 6981):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6981):  setFingerPrint start
I/AppUp4:DB( 6981):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6981):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6981):  SDK version = 0
I/AppUp4:DB( 6981):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 6981): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6981): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6981): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6981): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6981): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6981): onReceive
I/AppUp4:CustModeStarterReceiver( 6981): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6981): Context : android.app.ReceiverRestrictedContext@293cc0e8
D/AppUp4:CustFacade( 6981): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6981): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6981): begin check event
I/AppUp4:CustModeStarterReceiver( 6981): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6981): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6981): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6981): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6981): handleAsyncCustNotification do not startCustService
I/ActivityManager(  967): Killing 6685:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  967): failed to open /acct/uid_10061/pid_6685/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3202): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3202): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3202): networkInfo.isConnected() = false
I/ActivityManager(  967): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7008 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7008): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7008): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7008): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  967): Killing 6721:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
D/PhoneMonitor( 7008): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 7008): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7008): [parse] Load xml
V/TelephonyAutoProfiling( 7008): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7008): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 7008): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
V/DownloadManager( 3263): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
W/libprocessgroup(  967): failed to open /acct/uid_10079/pid_6721/cgroup.procs: No such file or directory
,V/DownloadManager( 3263): DownloadService onCreate
I/DownloadManager( 3263): in removeSpuriousFiles
V/DownloadManager( 3263): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/NotificationManager( 3263): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3263): created cursor android.database.sqlite.SQLiteCursor@3aea2a24 on behalf of 3263
,I/DownloadManager( 3263): in trimDatabase
V/DownloadManager( 3263): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3263): created cursor android.database.sqlite.SQLiteCursor@e090742 on behalf of 3263
I/ActivityManager(  967): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7030 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3263): DownloadService onStartCommand
V/DownloadManager( 3263): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3263): created cursor android.database.sqlite.SQLiteCursor@1fb1c490 on behalf of 3263
,I/CheckinService( 4279): Checkin interval check for package: unspecified last checkin: 1450109324244 min interval config: 0 actual interval: 33974
I/CheckinService( 4279): Checking schedule, now: 1450109358233 next: 1450109354192
I/CheckinService( 4279): active receiver: enabled
,I/CheckinService( 4279): Preparing to send checkin request
I/EventLogService( 4279): Accumulating logs since 1450109316382
V/DownloadManager( 3263): DownloadService onDestroy
,D/WeatherAncestor( 2667): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:9:18
,D/UpdateThreadPoolManager( 2667): 2 : This is isUpdating : false
D/WeatherAncestor( 2667): connectivity changed - connection : true
D/Weather_cast( 2667): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2667): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:9:18
D/WeatherService( 2667): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/CheckinRequestBuilder( 4279): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  967): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7053 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  967): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2667): 2 : Utils getTopActivity com.lge.launcher2 / true
E/ActivityThread( 4279): Failed to find provider info for com.google.android.wearable.settings
D/WeatherService( 2667): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2667): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/art     (  967): Explicit concurrent mark sweep GC freed 23064(1131KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.320ms total 169.209ms
,W/ResourcesManager( 7053): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel_SMS( 7053): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7053): MmsConfig.loadMmsSettings
I/Babel_SMS( 7053): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7053): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7053): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7053): MmsConfig.loadFromResources
E/Babel_SMS( 7053): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7053): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7053): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7053): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7053): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
,D/SensorManager( 7053): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7053): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7053): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7053): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7053): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7053): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7053): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7053): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7053): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7053): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7053): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7053): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7053): found sensor: Motion Accel, handle=46
W/Settings( 7053): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 7053): startup - clean
,I/Babel   ( 7053): deleted: false for 0
,I/art     ( 7053): CheckpointMarkThreadRoots callback created = 0xb042d470
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
,I/art     ( 7053): CheckpointMarkThreadRoots callback created = 0xb042d450
,D/libc-netbsd(  276): res_queryN name = xxxxx succeed
,I/System.out( 1731): propertyValue:false
W/art     ( 7053): Suspending all threads took: 5.391ms
,I/ActivityManager(  967): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7087 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/AudioCapabilities( 7053): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 7053): Unsupported mime audio/adpcm
,W/AudioCapabilities( 7053): Unsupported mime audio/g726
W/AudioCapabilities( 7053): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7053): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7053): Unsupported mime video/mjpg
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/VideoCapabilities( 7053): Unsupported mime video/theora
,W/AudioCapabilities( 7053): Unsupported mime audio/evrc
,W/AudioCapabilities( 7053): Unsupported mime audio/qcelp
W/VideoCapabilities( 7053): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7053): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7053): Unsupported mime audio/qcelp
W/AudioCapabilities( 7053): Unsupported mime audio/evrc
W/VideoCapabilities( 7053): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7053): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7053): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7053): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7053): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7053): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 7053): onServiceConnected
,W/Babel   ( 7053): Attempted to change video mute state without an active call.
I/NotificationManager( 7053): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 7053): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7053): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7053): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7053): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  276): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 7053): propertyValue:false
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7087): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/GAv4    ( 7087): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7087):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7087):   adb logcat -s GAv4
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7087): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7087): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7087): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7087): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/Babel   ( 7053): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  967): Killing 6790:com.android.chrome/u0a48 (adj 15): empty #11
W/GAv4    ( 7087): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7087): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/libprocessgroup(  967): failed to open /acct/uid_10048/pid_6790/cgroup.procs: No such file or directory
,I/NotificationManager(  967): android: cancelAsUser(2) by android
,I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
,I/ActivityManager(  967): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7129 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/WebViewFactory( 7087): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
W/ResourcesManager( 7129): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7129): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/LibraryLoader( 7087): Time to load native libraries: 2 ms (timestamps 4841-4843)
,I/LibraryLoader( 7087): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7087): Binding Chromium to main looper Looper (main, tid 1) {28deed45}
I/LibraryLoader( 7087): Expected native library version number "",actual native library version number ""
I/chromium( 7087): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7087): Initializing chromium process, singleProcess=true
W/art     ( 7087): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7087): ApplicationContext is null in ApplicationStatus
I/MultiDex( 7129): VM with version 2.1.0 has multidex support
I/MultiDex( 7129): install
I/MultiDex( 7129): VM has multidex support, MultiDex support library is disabled.
,W/chromium( 7087): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7087): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7087): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7087): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7087): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7087): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7087): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7087): Remote Branch: 
I/Adreno-EGL( 7087): Local Patches: 
I/Adreno-EGL( 7087): Reconstruct Branch: 
V/JNIHelp ( 7129): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/sensors_hal_Time(  967): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  967): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  967): tsOffsetIs: Apps: 114957411470; DSPS: 3864693; Offset : -2987263199
,V/AudioPolicyService(  280): registerClient() client 0xb57e75e0, uid 10079
,W/AudioManagerAndroid( 7087): Requires BLUETOOTH permission
I/NSApplication( 7087): Starting up...
W/ActivityThread( 7129): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7129): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1f0a24d5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7129): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 7129): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7129): com.google.android.gms: cancel(39789) by com.google.android.gms
I/ActivityManager(  967): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7168 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 7129): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 7129): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/ActivityManager(  967): Killing 6836:com.google.android.music:main/u0a81 (adj 15): empty #11
,I/art     ( 6809): CheckpointMarkThreadRoots callback created = 0xb042dd90
,I/art     ( 6809): CheckpointMarkThreadRoots callback created = 0xb042dd70
,D/NativeLibraryUtils( 7129): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  967): failed to open /acct/uid_10081/pid_6836/cgroup.procs: No such file or directory
,I/ActivityManager(  967): Killing 6860:com.android.vending/u0a36 (adj 15): empty #11
W/libprocessgroup(  967): failed to open /acct/uid_10036/pid_6860/cgroup.procs: No such file or directory
,D/WVCdm   (  280): Instantiating CDM.
,I/WVCdm   (  280): CdmEngine::OpenSession
,I/WVCdm   (  280): Level3 Library Dec 11 2014 16:13:16
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
,W/WVCdm   (  280): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  280): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  280): L1 library not specified. Falling Back to L3
I/ActivityManager(  967): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7192 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 1731): propertyValue:false
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/WVCdm   (  280): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  280): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  280): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  280): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  280): PrepareKeyRequest: nonce=1245248659
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/MusicStore( 7192): Database version: 120
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7192): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7192): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7192): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,I/art     ( 4011): Explicit concurrent mark sweep GC freed 2155(81KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 934us total 29.774ms
,I/art     ( 7129): CheckpointMarkThreadRoots callback created = 0xb042d560
W/ResourcesManager( 7192): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7192): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 7129): CheckpointMarkThreadRoots callback created = 0xb042d550
V/JNIHelp ( 7192): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7192): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7192): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3ded8a84: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7192): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7192): GMSCore installation verified
I/ConfigStore( 7192): Config Database version: 1
,I/dex2oat ( 7220): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/MediaRouter( 7192): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7192): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7192): type=WIFI subType= reason=null isConnected=true
,I/dex2oat ( 7220): dex2oat took 109.599ms (threads: 4)
,I/Adreno-EGL( 7129): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7129): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7129): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7129): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7129): Remote Branch: 
I/Adreno-EGL( 7129): Local Patches: 
I/Adreno-EGL( 7129): Reconstruct Branch: 
,I/NetworkMonitor( 7192): type=WIFI subType= reason=null isConnected=true
,D/LGDMClient( 6942): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6942): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6942): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 6942): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
I/NetworkStateForAutoUpdateMonitor( 6981): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6981): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6981): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6981): [onReceive] request level :IDLE....
,D/LGDMClient( 6942): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
D/LGDMClient( 6942): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6942): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/AppUp4:CustModeStarterReceiver( 6981): onReceive
I/AppUp4:CustModeStarterReceiver( 6981): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6981): Context : android.app.ReceiverRestrictedContext@293cc0e8
D/AppUp4:CustFacade( 6981): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6981): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6981): begin check event
I/AppUp4:CustModeStarterReceiver( 6981): Event For GoodConnectivity, noConnectivity : false, but skip! 
I/LGDMClient( 6942): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
W/Settings( 6913): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3202): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3202): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3202): networkInfo.isConnected() = true
D/PhoneState( 3202): setPdpRejectCasuse : false
D/MobileConnectivityChangeReceiver( 7008): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7008): onReceive CONNECTIVITY_CHANGE networkType=1
,W/ContextImpl( 6942): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3263): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3263): DownloadService onCreate
I/DownloadManager( 3263): in removeSpuriousFiles
E/LGDMClient( 6942): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/WeatherAncestor( 2667): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:9:20
,V/DownloadManager( 3263): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 6942): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6942): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/NotificationManager( 3263): com.android.providers.downloads: cancelAll by com.android.providers.downloads
D/LGDMClient( 6942): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
V/DownloadManager( 3263): DownloadService onStartCommand
I/GHttpClientFactory( 7192): Using our fixed implementation of GMSCore's GoogleHttpClient
V/DownloadManager( 3263): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3263): created cursor android.database.sqlite.SQLiteCursor@1d1699bc on behalf of 3263
D/UpdateThreadPoolManager( 2667): 2 : This is isUpdating : false
D/WeatherAncestor( 2667): connectivity changed - connection : true
D/Weather_cast( 2667): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2667): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:9:20
D/WeatherService( 2667): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3263): created cursor android.database.sqlite.SQLiteCursor@28deed45 on behalf of 3263
W/ActivityManager(  967): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2667): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2667): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2667): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/LGDMClient( 6942): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/GoogleURLConnFactory( 7192): Using platform SSLCertificateSocketFactory
I/DownloadManager( 3263): in trimDatabase
V/DownloadManager( 3263): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3263): created cursor android.database.sqlite.SQLiteCursor@1b943c9a on behalf of 3263
,D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  967): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7239 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/NotificationManager( 7192): com.google.android.music: cancel(1061) by com.google.android.music
I/ActivityManager(  967): Killing 7192:com.google.android.music:main/u0a81 (adj 15): empty #11
,I/WVCdm   (  280): CdmEngine::OpenSession
W/libprocessgroup(  967): failed to open /acct/uid_10081/pid_7192/cgroup.procs: No such file or directory
V/DownloadManager( 3263): DownloadService onDestroy
,W/ResourcesManager( 7239): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  967): Message: 20
D/BluetoothManagerService(  967): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1ff10b09:true
,D/BluetoothAdapterService(501935079)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1c7587f5
D/BluetoothAdapterService(501935079)( 1985): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1c7587f5
I/ActivityManager(  967): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7262 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7239): Create singleton instance
,D/UEI.SmartControl( 7262): Quickset Services start...
,I/UEI.SmartControl( 7262): Manufacture = LGE
D/UEI.SmartControl( 7262): File observer start...
E/UEI.SmartControl( 7262): IR Port is disabled: false
D/UEI.SmartControl( 7262): Starting file observer...
D/UEI.SmartControl( 7262): Extracting JNI libs...
D/UEI.SmartControl( 7262): --- this system supports 32-bit or 64-bit only
I/AudioManager( 7239): getMode name:com.lge.qremote
,D/UEI.SmartControl( 7262): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7262): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7262): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7262): --- Selecting new region: 2
I/UEI.SmartControl( 7262): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7262): Platform has CIR...
D/UEI.SmartControl( 7262): NO CIR support, need to check package...
I/UEI.SmartControl( 7262): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7262): QS Service created
I/art     (  967): Explicit concurrent mark sweep GC freed 15624(721KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.602ms total 150.472ms
,I/CheckinService( 4279): Checkin interval check for package: unspecified last checkin: 1450109324244 min interval config: 0 actual interval: 37472
E/UEI.SmartControl( 7262): QS start get config
D/WearableService( 1731): callingUid 10006, callindPid: 1731
,I/EventLogService( 4279): Aggregate from 1450109358282 (log), 1450107553197 (data)
D/AuthorizationBluetoothService( 1731): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 4279): Restart initialization of location
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
,E/MDM     ( 1731): [142] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/GCoreFlp( 1731): No location to return for getLastLocation()
W/FusedLocationProvider( 1731): location=null
W/ContextImpl( 3655): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,D/UEI.SmartControl( 7262): Loading JNI Libs...
D/UEI.SmartControl( 7262):  configuring local db...
,I/AudioManager( 7239): getMode name:com.lge.qremote
,I/MusicWidget( 2567): mDelayedStopHandler : unbind
,I/MusicBrowser( 2698): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2698): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2698): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2698): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2698): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2698): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2698): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2698): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,I/MediaFocusControl(  967):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@3e63ae71com.lge.music.MediaPlaybackService$6@bfde456
,D/MusicBrowser( 2698): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
,I/MusicBrowser( 2698): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
D/UEI.SmartControl( 7262):  ---- Has DB8: true
,D/UEI.SmartControl( 7262): QS start statue = true Error code = 0
D/UEI.SmartControl( 7262): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7262): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 7262): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7262): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7262): IrrcClient ++ 
D/irrcClient( 7262): getIrrcService ++ 
D/irrcClient( 7262): getIrrcService -- 
D/irrcClient( 7262): IrrcClient -- 
W/irrc_jni( 7262): IRRCPlayer_nativeInit -- 
,I/ActivityManager(  967): Process com.lge.email (pid 6913) has died
I/MusicBrowser( 2698): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2698): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
D/UEI.SmartControl( 7262): Services init done
I/UEI.SmartControl( 7262): Device manager: loading config....
D/UEI.SmartControl( 7262): QS Service init finished
,I/MusicBrowser( 2698): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@2c910394
I/MusicBrowser( 2698): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
D/UEI.SmartControl( 7262): QS Service version name: 0.1.73
D/UEI.SmartControl( 7262): QS Service version code: 1073
D/UEI.SmartControl( 7262): Service requested: Control
D/UEI.SmartControl( 7262): Config is loaded...
I/MusicBrowser( 2698): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2698): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2698): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2698): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2698): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2698): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2698): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2698): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2698): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
D/UEI.SmartControl( 7262):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7262): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7262): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 7262): Internal service binding...
I/MusicBrowser( 2698): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/UEI.SmartControl( 7262): -----IControl: 11
I/MusicBrowser( 2698): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2698): [MediaPlaybackService.java:6706:stop()] oooooo 
,D/UEI.SmartControl( 7262): Caller: com.lge.qremote
D/UEI.SmartControl( 7262): ------------ IControl registerCallback...
I/MediaPlayer[Native]( 2698): reset
I/UEI.SmartControl( 7262): Registering callback...
D/UEI.SmartControl( 7262): -----IControl: 19
D/UEI.SmartControl( 7262): Caller: com.lge.qremote
I/UEI.SmartControl( 7262): Registering Services Ready callback...
I/UEI.SmartControl( 7262): Notify client services are ready...
D/UEI.SmartControl( 7262): -----IControl: 8
D/UEI.SmartControl( 7262): Caller: com.lge.qremote
I/AudioManager( 7239): getMode name:com.lge.qremote
,I/ActivityManager(  967): Killing 6981:com.lge.appbox.client/u0a11 (adj 15): empty #11
V/MediaPlayer[Native]( 2698): setListener
V/MediaPlayer[Native]( 2698): disconnect
V/MediaPlayer[Native]( 2698): destructor
V/AudioFlinger(  280): releasing 18 from 2698 for -1
V/AudioFlinger(  280):  decremented refcount to 0
V/AudioFlinger(  280): purging stale effects
V/MediaPlayer[Native]( 2698): disconnect
D/MusicBrowser( 2698): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2698): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2698): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2698): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2698): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2698): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2698): [SmartShareManagerClient] unregisterListener: 657497303
W/SmartShareClient( 2698): [SmartShareManagerClient] unregisterListener invalid listener: 657497303
I/SmartShareClient( 2698): [SmartShareManagerClient] terminate service: 2698/MediaPlaybackService/517481946
E/HomeCloudIF( 2698): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2698): [SmartShareManagerClient] unbindService context:android.app.Application@24c679c4
W/libprocessgroup(  967): failed to open /acct/uid_10011/pid_6981/cgroup.procs: No such file or directory
,I/AudioManager( 7239): getMode name:com.lge.qremote
I/WVCdm   (  280): CdmEngine::CloseSession
V/CloudHub( 2698): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
,V/CloudHub( 2698): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2698): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2698): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2698): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/CloudHub( 2698): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29996
I/AudioManager( 7239): getMode name:com.lge.qremote
,I/ActivityManager(  967): Killing 6942:com.lge.lgdmsclient/1000 (adj 15): empty #11
I/WVCdm   (  280): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  280): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  280): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  280): CdmEngine::GenerateKeyRequest
D/WVCdm   (  280): PrepareKeyRequest: nonce=425805273
W/libprocessgroup(  967): failed to open /acct/uid_1000/pid_6942/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/WVCdm   (  280): CdmEngine::CloseSession
,I/WVCdm   (  280): L3 Terminate.
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/Adreno-EGL( 7129): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7129): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7129): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7129): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7129): Remote Branch: 
I/Adreno-EGL( 7129): Local Patches: 
I/Adreno-EGL( 7129): Reconstruct Branch: 
,I/Adreno-EGL( 7129): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7129): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7129): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7129): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7129): Remote Branch: 
I/Adreno-EGL( 7129): Local Patches: 
I/Adreno-EGL( 7129): Reconstruct Branch: 
,I/CheckinRequestBuilder( 4279): Classify the device as Phone.
,D/libc-netbsd( 4279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 4279): propertyValue:false
D/libc-netbsd( 4279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 4279): Sending checkin request (9751 bytes)
,I/CheckinRequestBuilder( 4279): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4279): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinRequestBuilder( 4279): Classify the device as Phone.
,I/CheckinTask( 4279): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4279): Checking schedule, now: 1450109365864 next: 1450636614860
I/CheckinService( 4279): active receiver: disabled
,I/CheckinService( 4279): Checking schedule, now: 1450109365911 next: 1450636614860
I/CheckinService( 4279): active receiver: disabled
,D/CheckinService( 4279): Recording last checkin time for package unspecified as 1450109365921
V/SetupWizard( 7008): Connected to Gservices successfully
,D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  967): Killing 7087:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,I/ActivityManager(  967): Killing 7030:com.lge.drmservice/u0a51 (adj 15): empty #12
,W/libprocessgroup(  967): failed to open /acct/uid_10079/pid_7087/cgroup.procs: No such file or directory
,W/libprocessgroup(  967): failed to open /acct/uid_10051/pid_7030/cgroup.procs: No such file or directory
D/UEI.SmartControl( 7262): Internal timer expired: 1
,I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-14 17:09:27.467 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/QCNEJ   ( 1838): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QPairHandler( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader(  967): Reconfiguring input devices.  changes=0x00000010
I/[SystemUI]QSlideListController( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
,W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
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
I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/administrator(  967): Handling package changes for user 0
,I/ActivityManager(  967): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7350 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 20.798ms
,I/NotificationManager( 7053): com.google.android.talk: cancel(8) by com.google.android.talk
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 282us total 21.359ms
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 20.679ms
,W/ResourcesManager( 7053): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7053): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/AppUp4:AppBoxCP( 7350): onCreate
W/AppUp4:DB( 7350):  [AppBoxDatabaseHelper] construct
,V/JNIHelp ( 7053): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/AppUp4:DB( 7350):  setFingerPrint start
I/AppUp4:DB( 7350):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 7350):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7350):  SDK version = 0
I/AppUp4:DB( 7350):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7350): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7350): onReceive
I/AppUp4:CustModeStarterReceiver( 7350): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 7350): Context : android.app.ReceiverRestrictedContext@1907b385
D/AppUp4:CustFacade( 7350): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7350): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7350): begin check event
I/AppUp4:CustModeStarterReceiver( 7350): Event For Nothing, skip.
W/System  ( 7053): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7053): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  967): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7371 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/NotificationService(  967): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  967): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  967): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  967): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/ResourcesManager(  967): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  967): Process com.google.android.apps.plus (pid 6809) has died
,D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
,V/BackupManagerService(  967): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  967): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1c162519
W/ResourcesManager( 7371): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7371): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7371): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,W/ResourceType(  967): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1731): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/AppConfig( 7371): Total System Memory = 906309632
,I/GalleryUtils( 7371): Application Heap = 96 MB
I/AppConfig( 7371): App Tier : NOT_DEF
,D/SystemHelper( 7371): region [EU], country [EU], operator [OPEN], sub-operator []
,D/LocationProviderProxy(  967): applying state to connected service
I/ActivityManager(  967): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7396 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ResourcesManager( 7396): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7396): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7396): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7396): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7396): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7396): BUILD Country: EU
I/SystemConfig( 7396): BUILD Operator: OPEN
,I/ActivityManager(  967): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7418 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  967): Killing 7168:com.android.chrome/u0a48 (adj 15): empty #11
W/libprocessgroup(  967): failed to open /acct/uid_10048/pid_7168/cgroup.procs: No such file or directory
,I/SystemConfig( 7396): pm.hasSystemFeature(com.lge.ims.rcs) = false
,I/SystemConfig( 7396): existFile = false
I/SystemConfig( 7396): canReadFile = false
I/SystemConfig( 7396): systemFeature RCS result false
D/SystemConfig( 7396): refreshRcsSupport() :false
I/LockScreenSettings( 7418): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7418): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7418): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7418): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7418): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7418): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  967): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7439 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  967): Killing 2698:com.lge.music/u0a28 (adj 15): empty #11
V/AudioFlinger(  280): 2698 died, releasing its sessions
,V/AudioFlinger(  280):  pid 1749 @ 0
V/AudioFlinger(  280):  pid 3202 @ 1
V/AudioFlinger(  280):  pid 3202 @ 2
,W/libprocessgroup(  967): failed to open /acct/uid_10028/pid_2698/cgroup.procs: No such file or directory
,W/ResourcesManager( 7439): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1940): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  967): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7469 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  967): Killing 7008:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1940): UpdateCorporaTask done [took 103 ms] updated apps [took 103 ms] 
,W/libprocessgroup(  967): failed to open /acct/uid_10038/pid_7008/cgroup.procs: No such file or directory
,D/Finsky  ( 7469): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7469): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7469): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7469): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7469): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3263): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3263): created cursor android.database.sqlite.SQLiteCursor@1d9195a8 on behalf of 7469
D/Finsky  ( 7469): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7469): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7469): Skipping gmscore version check
,D/Finsky  ( 7469): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 4279): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4279): Null package name or gms related package.  Ignoreing.
D/Finsky  ( 7469): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 4279): updateResources: need to parse f{com.google.android.gms}
,I/art     (  967): Explicit concurrent mark sweep GC freed 30250(1526KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.289ms total 172.923ms
,I/ActivityManager(  967): Killing 7129:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  967): failed to open /acct/uid_10006/pid_7129/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/charger_monitor(  482): init target 500000
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 296, mChargingStatus=5, mChargingStop=false
D/charger_monitor(  482): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  967): battery changed pluggedType: 2
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
,I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/Icing   ( 4279): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4279): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  967): Killing 7262:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 7239): android.os.DeadObjectException
,W/System.err( 7239): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7239): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7239): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7239): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7239): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7239): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7239): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7239): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7239): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7239): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7239): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7239): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7239): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7239): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7239): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7239): android.os.DeadObjectException
W/System.err( 7239): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7239): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7239): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7239): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7239): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7239): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7239): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7239): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7239): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7239): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7239): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7239): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7239): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7239): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7239): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  967): failed to open /acct/uid_10089/pid_7262/cgroup.procs: No such file or directory
W/ActivityManager(  967): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,I/ActivityManager(  967): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7559 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 7559): Quickset Services start...
,I/UEI.SmartControl( 7559): Manufacture = LGE
D/UEI.SmartControl( 7559): File observer start...
E/UEI.SmartControl( 7559): IR Port is disabled: false
D/UEI.SmartControl( 7559): Starting file observer...
D/UEI.SmartControl( 7559): Extracting JNI libs...
D/UEI.SmartControl( 7559): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7559): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7559): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7559): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7559): --- Selecting new region: 2
I/UEI.SmartControl( 7559): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7559): Platform has CIR...
,D/UEI.SmartControl( 7559): NO CIR support, need to check package...
I/UEI.SmartControl( 7559): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7559): QS Service created
E/UEI.SmartControl( 7559): QS start get config
,D/UEI.SmartControl( 7559): Loading JNI Libs...
,D/UEI.SmartControl( 7559):  configuring local db...
D/UEI.SmartControl( 7559):  ---- Has DB8: true
,D/UEI.SmartControl( 7559): QS start statue = true Error code = 0
D/UEI.SmartControl( 7559): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7559): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7559): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7559): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7559): IrrcClient ++ 
D/irrcClient( 7559): getIrrcService ++ 
D/irrcClient( 7559): getIrrcService -- 
D/irrcClient( 7559): IrrcClient -- 
W/irrc_jni( 7559): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7559): Services init done
,I/UEI.SmartControl( 7559): Device manager: loading config....
D/UEI.SmartControl( 7559): QS Service init finished
D/UEI.SmartControl( 7559): QS Service version name: 0.1.73
D/UEI.SmartControl( 7559): QS Service version code: 1073
D/UEI.SmartControl( 7559): Service requested: Control
D/UEI.SmartControl( 7559): Config is loaded...
D/UEI.SmartControl( 7559):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7559): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 7559): Request IControl service: devices are loaded...
,I/ActivityManager(  967): Killing 7239:com.lge.qremote/u0a106 (adj 15): empty #11
W/libprocessgroup(  967): failed to open /acct/uid_10106/pid_7239/cgroup.procs: No such file or directory
D/UEI.SmartControl( 7559): Internal service binding...
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,D/UEI.SmartControl( 7559): Internal timer expired: 1
,I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-14 17:09:39.532 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/UEI.SmartControl( 7559): Service.onUnbind: IControl
D/UEI.SmartControl( 7559): Service.onDestroy
W/System.err( 7559): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@1deaebe7
W/System.err( 7559): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 7559): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 7559): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 7559): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 7559): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 7559): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2983)
W/System.err( 7559): 	at android.app.ActivityThread.access$2200(ActivityThread.java:155)
W/System.err( 7559): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1426)
W/System.err( 7559): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7559): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7559): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7559): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7559): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7559): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7559): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7559): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@1deaebe7
,D/UEI.SmartControl( 7559): Shutdown IRRCPlayer... 
W/irrc_jni( 7559): IRRCPlayer_nativeFinalize ++ 
,D/irrcClient( 7559): ~IrrcClient ++ 
,D/irrcClient( 7559): ~IrrcClient -- 
W/irrc_jni( 7559): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 7559): Blaster closed
D/UEI.SmartControl( 7559): Blaster closed
D/UEI.SmartControl( 7559): Shut down QS...
D/UEI.SmartControl( 7559): Stopped file observer...
I/UEI.SmartControl( 7559): QS lib stop result = true
D/UEI.SmartControl( 7559): QS shutdown complete
D/sensors_hal_Time(  967): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  967): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  967): tsOffsetIs: Apps: 134958065421; DSPS: 4520074; Offset : -2987250951
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-14 17:09:42.544 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,V/AlarmManager(  967): ELAPSED_WAKEUP set : Alarm{1ff3308f type 2 when 139358 com.google.android.gms} when 139358
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1731): Vacuum at: now=1450109384388 tag=VacuumService
,I/PhenotypeConfigurator( 1731): Scheduling Phenotype for one-off execution 1791 seconds from now (1450109384719)
,D/GetConfigurationSnapshotOperation( 1731): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/art     ( 1731): Explicit concurrent mark sweep GC freed 45657(2MB) AllocSpace objects, 28(448KB) LOS objects, 40% free, 13MB/22MB, paused 1.754ms total 104.973ms
,I/PhenotypeFlagCommitter( 1731): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1731): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  967): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 1731): propertyValue:false
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-53 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-14 17:09:45.566 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/LocationManagerService(  967): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  967): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  967): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-14 17:09:51.595 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  967): ALS enabled for SRE
D/PowerManagerServiceEx(  967): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (29486 ms ago)
,D/qdlights(  967): set_light_backlight: 254
,D/qdlights(  967): set_light_backlight: 251
D/qdlights(  967): set_light_backlight: 248
,D/qdlights(  967): set_light_backlight: 244
,D/qdlights(  967): set_light_backlight: 241
,D/qdlights(  967): set_light_backlight: 238
,D/qdlights(  967): set_light_backlight: 234
,D/qdlights(  967): set_light_backlight: 231
,D/qdlights(  967): set_light_backlight: 228
,D/qdlights(  967): set_light_backlight: 224
,D/qdlights(  967): set_light_backlight: 221
,D/qdlights(  967): set_light_backlight: 218
,D/qdlights(  967): set_light_backlight: 214
,D/qdlights(  967): set_light_backlight: 211
,D/qdlights(  967): set_light_backlight: 208
,D/qdlights(  967): set_light_backlight: 204
,D/qdlights(  967): set_light_backlight: 201
,D/qdlights(  967): set_light_backlight: 198
,I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,D/qdlights(  967): set_light_backlight: 194
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-14 17:09:54.623 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
D/qdlights(  967): set_light_backlight: 191
,D/qdlights(  967): set_light_backlight: 188
,D/qdlights(  967): set_light_backlight: 184
,D/qdlights(  967): set_light_backlight: 181
,D/qdlights(  967): set_light_backlight: 178
,D/qdlights(  967): set_light_backlight: 174
,D/qdlights(  967): set_light_backlight: 171
,D/qdlights(  967): set_light_backlight: 168
,D/qdlights(  967): set_light_backlight: 164
,D/qdlights(  967): set_light_backlight: 161
,D/qdlights(  967): set_light_backlight: 158
,D/qdlights(  967): set_light_backlight: 154
,D/qdlights(  967): set_light_backlight: 151
,D/qdlights(  967): set_light_backlight: 148
,D/qdlights(  967): set_light_backlight: 144
,D/qdlights(  967): set_light_backlight: 141
,D/qdlights(  967): set_light_backlight: 138
,D/qdlights(  967): set_light_backlight: 134
,D/qdlights(  967): set_light_backlight: 131
,D/qdlights(  967): set_light_backlight: 128
,D/qdlights(  967): set_light_backlight: 124
,D/qdlights(  967): set_light_backlight: 121
,D/qdlights(  967): set_light_backlight: 118
,D/qdlights(  967): set_light_backlight: 114
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/qdlights(  967): set_light_backlight: 111
D/qdlights(  967): set_light_backlight: 108
,D/qdlights(  967): set_light_backlight: 104
,D/qdlights(  967): set_light_backlight: 101
,D/qdlights(  967): set_light_backlight: 98
,D/qdlights(  967): set_light_backlight: 94
,D/qdlights(  967): set_light_backlight: 91
,D/qdlights(  967): set_light_backlight: 88
,D/qdlights(  967): set_light_backlight: 84
,D/qdlights(  967): set_light_backlight: 81
,D/qdlights(  967): set_light_backlight: 78
,D/qdlights(  967): set_light_backlight: 74
,D/qdlights(  967): set_light_backlight: 71
,D/qdlights(  967): set_light_backlight: 68
,D/qdlights(  967): set_light_backlight: 64
,D/qdlights(  967): set_light_backlight: 61
,D/qdlights(  967): set_light_backlight: 58
,D/qdlights(  967): set_light_backlight: 54
,D/qdlights(  967): set_light_backlight: 51
,D/qdlights(  967): set_light_backlight: 48
,D/qdlights(  967): set_light_backlight: 44
,D/qdlights(  967): set_light_backlight: 41
,D/qdlights(  967): set_light_backlight: 38
,D/qdlights(  967): set_light_backlight: 34
,D/qdlights(  967): set_light_backlight: 31
,D/qdlights(  967): set_light_backlight: 28
,D/qdlights(  967): set_light_backlight: 24
,D/qdlights(  967): set_light_backlight: 21
,D/qdlights(  967): set_light_backlight: 18
,D/qdlights(  967): set_light_backlight: 14
,D/qdlights(  967): set_light_backlight: 11
,D/qdlights(  967): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-14 17:09:57.634 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/sensors_hal_Time(  967): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  967): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  967): tsOffsetIs: Apps: 154958849424; DSPS: 5175460; Offset : -2987260326
,D/PowerManagerServiceEx(  967): acquireWakeLockInternal: lock=743967298, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=967
,D/WeatherService( 2667): 2 : TimeTick Intent has been received, Time(hour:min:sec) 17:10:0
,D/WeatherService( 2667): 2 : TimeTick Intent And Screen On
D/WeatherService( 2667): 2 : SDK version : 21
W/ActivityManager(  967): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2667): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2667): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2667): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2667): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2667): 2 : This is isUpdating : false
D/WeatherService( 2667): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2667): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2667): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2667): 2 : Fixed theme : optimus
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
,D/WeatherReflect( 2667): 2 : Map key string is -2
D/lim     ( 2667): 2 : time = 17:10
I/WeatherReflect( 2667): Model Name : LG-D722
D/WeatherTheme( 2667): 2 : Different view - status_min_formatted : 09 != 10
D/WeatherTheme( 2667): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
,D/WeatherReflect( 2667): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
I/[SystemUI]Clock( 1373): called onTimeUpdated()
I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
D/Theme   ( 2667): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2667): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2667): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2667): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/[SystemUI]DateView( 1373): called onTimeUpdated()
,I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
D/Weather4x2_optimus( 2667): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2667): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2667): forecast size is 0
D/Theme   ( 2667): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2667): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2667): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2667): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2667): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2667): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2667): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2667): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2667): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2667): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2667): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2667): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2667): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2667): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2667): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2667): url is : null
,D/Theme   ( 2667): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2667): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2667): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2667): 2 : update view, appWidgetId: 2
D/WeatherService( 2667): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 17:10:0
D/PowerManagerServiceEx(  967): releaseWakeLockInternal: lock=743967298 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-14 17:10:00.655 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  967): ALS enabled for SRE
D/PowerManagerServiceEx(  967): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (36475 ms ago)
I/PowerManagerService(  967): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  967): ALS enabled for SRE
D/PowerManagerServiceEx(  967): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (36486 ms ago)
W/ContextImpl(  967): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  967): Sleeping (uid 1000)...
D/LPWGController(  967): [updateScreenState] screen on = false
D/LPWGController(  967): disable proximity sensor
D/LPWGController(  967): enable proximity sensor
I/SensorManager(  967): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@3ea73b77] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  967): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  967): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  967): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  967): activate: handle is 48, enable
V/sensors_hal_Ctx(  967): activate sensors is 1400000000000
D/sensors_hal_Thresh(  967): enable: handle=48
I/sensors_hal_SAM(  967): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  967): waitForResponse: timeout=1000
,V/sensors_hal_SAM(  967): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  967): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  967): enable: Received response: 0
D/PowerManagerServiceEx(  967): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (36524 ms ago)
I/Adreno-EGL(  967): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  967): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  967): Build Date: 03/02/15 Mon
I/Adreno-EGL(  967): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  967): Remote Branch: 
I/Adreno-EGL(  967): Local Patches: 
I/Adreno-EGL(  967): Reconstruct Branch: 
,D/PermissionCache(  244): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (975 us)
,I/Sensors (  412): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  967): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  967): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  967): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  967): processInd: handle 48, count=1
V/sensors_hal_Thresh(  967): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  967): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  967): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  967): poll: count: 256
I/sensors_hal_Ctx(  967): poll: released wakelock sensor_ind
D/sensors_hal_Util(  967): waitForResponse: timeout=0
D/LPWGController(  967): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  967): current mode = 1  value = 1 1
I/LPWGController(  967): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  967): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  967): set_light_backlight: 0
,I/SensorManager(  967): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
I/sensors_hal_Ctx(  967): activate: handle is 46, disable
V/sensors_hal_Ctx(  967): activate sensors is 1000000000000
D/sensors_hal_LP2(  967): enable: handle=46
D/sensors_hal_LP2(  967): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  967): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
I/DisplayManagerService(  967): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  967): Display changed displayId=0
D/SurfaceFlinger(  244): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  244): hwc_blank: Blanking display: 0
,D/DSDPConnection( 1749): Display #0 changed.
,V/sensors_hal_SAM(  967): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  967): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/qdhwcomposer(  244): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  967): Excessive delay in setPowerMode(): 171ms
,I/qdhwcomposer(  244): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  967): Got set_interactive hint
D/KeyguardViewMediator( 1373): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1331): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1373): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1331): notifyScreenOffLocked
D/SmartCoverViewMediator( 1331): handleNotifyScreenOFF
,D/KeyguardViewMediator( 1373): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1373): handleNotifyScreenOff
I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-12-14 17:10:02.151 DNS addrs= 192.168.1.1, 0.0.0.0, 
,D/ScreenTurnOffBySensor( 1373): unregisterProximitySensor
D/WifiServerServiceExt(  967): sendKtScanInterval  mRtspPlay : false
I/WifiServerServiceExt(  967): set CMD_KT_SCAN_INTERVAL
,D/StatusBarWindowView( 1373): onScreenTurnedOff why = 3
V/AudioFlinger(  280): setParameters(): io 0, keyvalue screen_state=on, calling pid 967
D/audio_hw_primary(  280): adev_set_parameters: enter: screen_state=on
,V/voice   (  280): voice_set_parameters: enter: screen_state=on
V/compress_voip(  280): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  280): voice_extn_compress_voip_set_parameters: exit
V/voice   (  280): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  280): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  280): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  280): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  280): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  280): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  280): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  280): adev_set_parameters: exit with code(0)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/GpsLocationProvider(  967): receive broadcast intent, action: android.intent.action.SCREEN_ON
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.SCREEN_ON
,I/QCNEJ   ( 1838): |CORE| sendScreenState: state:true
,I/LEDService( 1803): getCurrentHighestLGLedRecord() start. size = 1
,D/LNfcService( 1785): action : android.intent.action.SCREEN_ON
D/LEDService( 1803): stopPatternFlashing()
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
I/Cliptray Service( 1803): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/LEDService( 1803): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
D/Cliptray Service( 1803): lockStatus = 0
I/LEDService( 1803): updateLightsLocked : turn off led
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
D/NfcServiceNXP( 1785): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1785): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1785): isRequireNfcCRouting() return true
,D/LNfcService( 1785): isHCERoutingtoHost() return : true
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
D/LEDHandler( 1803): RESTART MSG
D/Ulp_jni (  967): JNI:system_update. Event-0
D/SplitWindow(  967): check instance of lgWin Window{c079702 u0 SearchPanel}
,D/InputDispatcher(  967): Window went away: Window{ebb8da5 u0 SearchPanel}
,I/[SystemUI]Clock( 1373): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1373): time changed, timezoneChanged : false
,V/PhoneApp( 1749): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
D/WeatherService( 2667): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 17:10:2
,D/WeatherService( 2667): 2 : ACTION screen on
D/WeatherService( 2667): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2667): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2667): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 17:10:2
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  967): ACTION_SCREEN_ON
D/AppCleanupService( 4132): android.intent.action.SCREEN_ON
,V/AudioFlinger(  280): setParameters(): io 0, keyvalue screen_state=off, calling pid 967
D/audio_hw_primary(  280): adev_set_parameters: enter: screen_state=off
V/voice   (  280): voice_set_parameters: enter: screen_state=off
V/compress_voip(  280): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  280): voice_extn_compress_voip_set_parameters: exit
V/voice   (  280): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  280): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  280): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  280): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  280): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  280): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  280): adev_set_parameters: exit with code(0)
D/WifiController(  967): CMD_SCREEN_OFF 
D/WifiController(  967): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  967): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.SCREEN_OFF
,I/QCNEJ   ( 1838): |CORE| sendScreenState: state:false
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
D/LNfcService( 1785): action : android.intent.action.SCREEN_OFF
I/Cliptray Service( 1803): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1785): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1876): [Launcher.java:1711:onReceive()]Screen Off
V/PhoneApp( 1749): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2667): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 17:10:2
D/WeatherService( 2667): 2 : ACTION screen off
D/WeatherService( 2667): 2 : TimeTick Receiver Unregister
D/WeatherService( 2667): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 17:10:2
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): ACTION_SCREEN_OFF
D/AppCleanupService( 4132): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 4132): AppUsageStatsSaveTask
,I/ActivityManager(  967): Process com.google.android.talk (pid 7053) has died
,E/NxpNfcJni( 1785): getReconnectState = 0x0
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
,I/Sensors (  412): sns_pwr.c(301):releasing wakelock
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,D/KeyguardViewMediator( 1373): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  967): ELAPSED_WAKEUP set : Alarm{3cca1813 type 2 when 162307 com.android.systemui} when 162307
,D/PhoneUtils( 1749): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1749): getCallState : 0
,D/PhoneUtils( 1749): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1373): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1373): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  967): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  967): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  967): tsOffsetIs: Apps: 174959527333; DSPS: 5830842; Offset : -2987253908
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/charger_monitor(  482): init target 500000
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 293, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 293
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 293
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
,W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  967): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
V/AlarmManager(  967): ELAPSED_WAKEUP set : Alarm{27143a50 type 2 when 187729 com.google.android.gms} when 187729
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  967): ELAPSED_WAKEUP set : Alarm{37416449 type 2 when 190691 android} when 190691
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  967): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  967): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  967): tsOffsetIs: Apps: 194960492586; DSPS: 6486234; Offset : -2987264880
,I/ClearcutLoggerApiImpl( 1731): disconnect managed GoogleApiClient
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  967): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  967): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  967): tsOffsetIs: Apps: 214961181953; DSPS: 7141617; Offset : -2987276922
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/art     ( 1373): Background sticky concurrent mark sweep GC freed 57901(3MB) AllocSpace objects, 63(2MB) LOS objects, 19% free, 23MB/29MB, paused 3.910ms total 224.310ms
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  967): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  967): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  967): tsOffsetIs: Apps: 234961855331; DSPS: 7796999; Offset : -2987277197
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/charger_monitor(  482): init target 500000
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 291, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 291
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  967): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  967): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  967): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  967): tsOffsetIs: Apps: 254962712251; DSPS: 8452387; Offset : -2987272581
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  967): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  967): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  967): tsOffsetIs: Apps: 274967736305; DSPS: 9107911; Offset : -2987255650
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 291, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 291
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  967): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  967): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  967): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  967): tsOffsetIs: Apps: 294968518537; DSPS: 9763297; Offset : -2987264869
,D/HeadsetStateMachine( 1985): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  967): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  967): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  967): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  967): tsOffsetIs: Apps: 314969251133; DSPS: 10418681; Offset : -2987265189
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC

```
